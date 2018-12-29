# eye detection
a simple eye detection model made using tensorflow's object detection api trained on custom data

pretrained model used to train custom model: ssd_inception_v2_coco

## how to run:
- install opencv2 and tensorflow on your system
- run object_detection_custom.py `python3 object_detection_custom.py --input_path <path to your input image>`
- a window will open displaying your image with eyes highlighted
- to close the window press any key \
![sample input](https://github.com/planetred-cc/eye_detection/blob/master/sample_input.jpg)
![sample output](https://github.com/planetred-cc/eye_detection/blob/master/sample_output.jpg)


**the result may not be prefect as i neither had the data nor the system that can crunch large amount of data. this model was trained on around 100 images and around 155000 steps and took 2 days to train**

