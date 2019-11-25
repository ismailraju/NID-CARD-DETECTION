



train command:

darknet_no_gpu.exe detector train data/cat-dog-obj.data cfg/cat-dog-tiny-yolo.cfg cfg/yolov3-tiny.weights




check training:

 

darknet_no_gpu.exe  detector test data/cat-dog-obj.data cfg/cat-dog-tiny-yolo.cfg backup/cat-dog-tiny-yolo_final.weights dog.jpg