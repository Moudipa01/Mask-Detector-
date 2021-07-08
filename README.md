# COVID-19 Face Mask Detector

![samples](images/testmask.gif)
# Reproduction
```Shell


cd covid-mask-detector

# Download dataset and export it to pandas DataFrame
python -m covid-mask-detector.data_preparation
```
## Training

```Shell
python -m covid-mask-detector.train
```

## Testing on videos
```sh
python -m covid-mask-detector.video modelPath videoPath
```

### Usage
```
Usage: video.py [OPTIONS] MODELPATH VIDEOPATH

  modelPath: path to model.ckpt

  videoPath: path to video file to annotate

Options:
  --output PATH  specify output path to save video with annotations
```
