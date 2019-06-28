1. Put `id1_1.jpg` under `/data/facebank/id1/`.

2. Put `MyVideo_1.mp4` under `/data/facebank/`.

3. Just run:
```
python infer_on_video.py -f ./data/facebank/MyVideo_1.mp4 -s ./data/facebank/MyVideo_1_detect --update
```

4. You will get detected images of all frames in video under the folder `/data/frame_imgs_det/`.
