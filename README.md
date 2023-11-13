# yolo5xDeep
 Yolov5(v6.2) with DeepSort
# env:
conda install pytorch==1.12.0 torchvision==0.13.0 torchaudio==0.12.0 cudatoolkit=11.6 -c pytorch -c conda-forge
# run detect:
python track.py --source handAndStand.mp4 --yolo_weights bestStand.pt --save-txt --save-vid --save-img

