# yolo-rtsp-security-cam
Python RTSP security camera app with motion detection features that are based on image processing instead of a dedicated sensor. Also includes YOLO object detection so you can set it to record only specific things such as people, dogs, other animals or particular objects. All that's required is an RTSP camera and a PC with a GPU capable of running YOLO.

## Getting Started
```bash
sudo apt update
sudo apt install gcc python3-dev python3-pip git ffmpeg
```


```bash
git clone https://github.com/PhazerTech/yolo-rtsp-security-cam
```

Now install the required dependencies with pip:

```bash
cd yolo-rtsp-security-cam
pip3 install -r requirements.txt
```

## Running the App
```commandline
python3 yolo-rtsp-security-cam.py --stream rtsp://192.168.1.5:554/profile2/media.smp --yolo drone --monitor
```
