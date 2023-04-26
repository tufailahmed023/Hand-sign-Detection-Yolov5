
# Hand-sign-Detection-Yolov5

A pet project to decect muliple hand sign usein Yolov5


## Demo

Insert gif or link to demo

![https://raw.githubusercontent.com/tufailahmed023/Hand-sign-Detection-Yolov5/main/Up.jpg] 0
## Installation
#### Clone this repo
```bash
git clone {this repo}
```
#### Create a new conda env 
```bash
conda create {env name} python=3.8 -y 
```
#### Actiavte the env 
```bash
conda actiavte {env name}
```
#### Install requrment.txt
```bash
pip install -r requrment.txt
```

#### Go inside the yolov5 folder 
```
cd {folder path}
```
#### Use the custome model
##### Here my custome model name is best.pt, if yours is diffrent then use that name
```bash
python detect.py --weights {custome model name} --sourse {file path to predict }
```
For real time i.e Using Webcam
```bash
python detect.py --weights {custome model name} --sourse 0
```
  