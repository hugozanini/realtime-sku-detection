# Real-time & Offline SKU detection in the browser using TensorFlow.js

This repository is part of the tutorial  [Realtime SKU detection in the browser using TensorFlow.js](test.com).  **For a better understanding of how to create a custom object detection model, refer to the post**.


The main branch contains the code used to train the network and the model configuration file. To download the the [SKU 110K dataset](https://github.com/eg4000/SKU110K_CVPR19) in the tf.record format, [click here](https://mega.nz/file/xnBWwBbK#h38Etgjt59z-gdGnK0Gbt3P4D_iM5_PdiWlBLbHiLrc).

Following the [tutorial](test.com),  you are going to develop a solution to perform realt-time and offline inferences thourgh the camera of any device that opens a web broswer.

<body> 
<img  alt="Qries"
src="https://github.com/hugozanini/realtime-sku-detection/blob/main/git-media/demo.gif?raw=true"  width="275" height="600">
</body



<body> <a  href="https://codesandbox.io/s/sku-detection-mobilenet-wtvbj?file=/src/index.js">
<img  alt="Qries"
src="https://raw.githubusercontent.com/hugozanini/realtime-sku-detection/main/git-media/sandbox.png"  width="275" height="145">
</a>
</body
<br>

---
### Training metrics

The training process was monitored through Tensorboard and took around 22h to finish on a 60GB machine using an NVIDIA Tesla P4. The final losses can be checked below:


<body> <a  href="https://codesandbox.io/s/sku-detection-mobilenet-wtvbj?file=/src/index.js">
<img  alt="Qries"
src="https://raw.githubusercontent.com/hugozanini/realtime-sku-detection/main/git-media/total_loss.png"  width="700">
</a>
</body
<br>




## Acknowledgment

This code was developed under the financial assistance of the [Google Developers Group](https://developers.google.com/community/gdg),  which provided all the computational resources for training the models.



## Citation

```
@inproceedings{goldman2019dense,
 author    = {Eran Goldman and Roei Herzig and Aviv Eisenschtat and Jacob Goldberger and Tal Hassner},
 title     = {Precise Detection in Densely Packed Scenes},
 booktitle = {Proc. Conf. Comput. Vision Pattern Recognition (CVPR)},
 year      = {2019}
}
```
