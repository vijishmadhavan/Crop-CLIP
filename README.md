# Crop-CLIP

You can sponsor me to support my open source work 💖 [sponsor](https://github.com/sponsors/vijishmadhavan?o=sd&sc=t)

**Search subjects/objects in an image using simple text description and get cropped results.**

**Image:** [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Crop-CLIP/blob/master/Crop_CLIP.ipynb)

* 2022-1-04 Added [colab for YouTube videos](https://colab.research.google.com/github/vijishmadhavan/Crop-CLIP/blob/master/Crop_CLIP_Video.ipynb)

**Video:** [<img src="https://colab.research.google.com/assets/colab-badge.svg" align="center">](https://colab.research.google.com/github/vijishmadhavan/Crop-CLIP/blob/master/Crop_CLIP_Video.ipynb)

## Highlights
- [Try the web app :point_down:](#Simple-App)

## Video Results:(Baby Driver Bank Robbery scene)

**- Search the scene and zoom-in to the subject.**

### Search Query on YouTube Video.

#### "Man in suit"

![baby](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/ss.jpg)

#### "Cute boy"

![baby](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/ss2.jpg)


## "Search Query - Crop!"

### "Whats the time"
![Time](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/download%20(3)-side.png)

### "Hoodie guy"
![Hoodie](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/download%20(4)-side.png)

### "Mini Cooper"
![minicooper](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/img1.png)

### "Whiskey Bottle"
![Whiskey](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/download%20(2)-side.png)

## How?

- This is done by combining Object detection [yolov5](https://github.com/ultralytics/yolov5) and OpenAI's [CLIP model](https://github.com/openai/CLIP).
- Detects and crops objects (yolov5s)
- Encode cropped images using CLIP
- Encode search query using CLIP
- Find the best match

## Why?
- #vacation :relaxed:

**Can also be used to create datasets with some changes in code. In the below example images of Jack daniels bottle has been croped and saved.**

### Search Query on batch - "Jack Daniels"
![dataset](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/data-side.jpg)

## Simple App

#### :point_right: [Hugging Face Spaces](https://huggingface.co/spaces/Vijish/Crop-CLIP)  :point_left:

![app](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/ezgif-7-4272b7bcdc.gif)

## Limitations

- Depends heavily on object detection(yolov5). 
- YOLOv5 🚀 is a family of object detection architectures and models pretrained on the COCO dataset, So detection depends on COCO classes.

## Acknowledgements
- [Beyond tags and entering the semantic search era on images with OpenAI CLIP](https://towardsdatascience.com/beyond-tags-and-entering-the-semantic-search-era-on-images-with-openai-clip-1f7d629a9978) by [Ramsri Goutham Golla](https://twitter.com/ramsri_goutham)
- [OpenAI's CLIP](https://github.com/openai/CLIP)
- [Natural Language Image Search](https://github.com/haltakov/natural-language-image-search)
- [yolov5](https://github.com/ultralytics/yolov5)



