
### Difference between ssdlite transfer learned model and original model.

* Here the original ssd lite model resizes the image to 300 x 300 and then normalizes that output image with 127.5. And the proof of this application can be available from the official caffe repo of ssd lite also from [here](https://github.com/chuanqi305/MobileNetv2-SSDLite/blob/master/demo_caffe.py#L33)
<p align="center">
  <img src="images/im1.png" width = 480>
</p>

* There's no clarity on what preprocessing is being applied on transfer learning since it's only dividing the image with 127.5 and substracting one from it.
<p align="center">
  <img src="images/im2.png" width = 480>
</p>

* Even to inspect what preprocessing is applied on it, the node structure in transfer learned image is a bit confusing to deduce.

<p align="center">
  <img src="images/im3.png" width = 480>
</p>
