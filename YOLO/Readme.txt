



train command:

darknet_no_gpu.exe detector train data/cat-dog-obj.data cfg/cat-dog-tiny-yolo.cfg cfg/yolov3-tiny.weights


darknet_no_gpu.exe detector train D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/data/cat-dog-obj.data D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/cfg/cat-dog-tiny-yolo.cfg D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/cfg/yolov3-tiny.weights


D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/dataset


check training:

 

darknet_no_gpu.exe  detector test data/cat-dog-obj.data cfg/cat-dog-tiny-yolo.cfg backup/cat-dog-tiny-yolo_final.weights nid.jpg




darknet_no_gpu.exe  detector test D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/data/cat-dog-obj.data D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/cfg/cat-dog-tiny-yolo.cfg D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/backup/cat-dog-tiny-yolo_final.weights D:/PROJECTS/Python/NID-CARD-DETECTION/YOLO/nid.jpg  -thresh 0