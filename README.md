# Crop-CLIP

**Search subjects/objects in an image using simple text description and get cropped results.**

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

- **Can also be used to create datasets with some changes in code. In the below example images of Jack daniels bottle has been croped and saved.**

### Search Query on batch - "Jack Daniels"
![dataset](https://github.com/vijishmadhavan/Crop-CLIP/blob/master/Images/data-side.jpg)

### [Hugging Face Space](https://huggingface.co/spaces/Vijish/Crop-CLIP)

## Limitations

- Depends heavily on object detection.

## Acknowledgements
- [Beyond tags and entering the semantic search era on images with OpenAI CLIP](https://towardsdatascience.com/beyond-tags-and-entering-the-semantic-search-era-on-images-with-openai-clip-1f7d629a9978) by [Ramsri Goutham Golla](https://twitter.com/ramsri_goutham)
- [OpenAI's CLIP](https://github.com/openai/CLIP)
- [Natural Language Image Search](https://github.com/haltakov/natural-language-image-search)
- [yolov5](https://github.com/ultralytics/yolov5)



