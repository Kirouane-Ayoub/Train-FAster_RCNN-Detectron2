# Train Faster R-CNN with (Meta AI's  Detectron2) : 



![1671284329323](https://user-images.githubusercontent.com/99510125/209795158-ff1ac111-1ccf-4fb1-98f7-aafbe09ea54f.png)

What is Faster R-CNN?

Faster R-CNN is an object detection model that improves Fast R-CNN by utilizing a region proposal network (RPN) with the CNN model. The RPN shares full-image convolutional features with the detection network, enabling nearly cost-free region proposals. It is a fully convolutional network that simultaneously predicts object bounds and objectness scores at each position. The RPN is trained end-to-end to generate high-quality region proposals, which Fast R-CNN uses for detection. RPN and Fast R-CNN are merged into a single network by sharing their convolutional features: the RPN component tells the unified network where to look.
As a whole, Faster R-CNN consists of two modules. The first module is a deep fully convolutional network that proposes regions, and the second module is the Fast R-CNN detector that uses the proposed regions.

U can find more about it from here : https://www.linkedin.com/pulse/faster-r-cnn-overview-ayoub-kirouane
