# ObjectDetection
Object Detection using different Deep Learning approaches / Methods.

**MaskRcNN.ipynb**: It is an implementation of mask-rcnn algortihm. MASK-RCNN was proposed in 2017. It is build on faster-rcnn. The mask in the name implies to mask creation or instance segmentation.
1st part is a **backbone model** i.e a resnet50 or resnet101 model to extract features. Than it uses two **Feature Pyramid Networks (FPN)** - 2 because the first pyramid passes high-level features down to the second oyramid; this way it can have acces to both high and low lwvel features. Than it uses **Region Proposal Network**; which uses 200k anchors of different sizes and aspect ratio to find the object inside it. If an anchor box is associated with any object the anchor box may adjust lolocate the object beter. ROI and Bounding box is generated. Than ROiPooling is applied (cropping and resing of dettected object). And lastly segmentation mask is applied. 

**yolo-od.ipynb** YOLO (You Only Look Once) is real-time object detection algorithm. Here i have used yolo-v3 from DarkNet (creators of yolo). The reason behind yolo being famous is that it was the first algorithm to classify and locate an object in one/single step (this is where its name came from).


**imageai.ipynb** It is a little work done to use imageai for object detection on images and video. 
