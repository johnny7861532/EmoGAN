# EmoGAN
This repository features an implementation of "EmoGAN: Empowering GAN to Edit Target Face Emotions Using Just a Single Image".

## Compare Result
Transforming from a compact and fierce expression to a relaxed and joyful expression.
The left image represents the original video clip, while the right image shows the corrected result.
![](img/1.png)
![](img/2.png)
![](img/3.png)

## Requirements
- numpy==1.23.5
- opencv-python==4.7.0.72
- onnx==1.14.0
- insightface==0.7.3
- psutil==5.9.5
- tk==0.1.0
- pillow==9.5.0
- torch==2.0.1+cu118; sys_platform != 'darwin'
- torch==2.0.1; sys_platform == 'darwin'
- onnxruntime==1.15.0; sys_platform == 'darwin' and platform_machine != 'arm64'
- onnxruntime-silicon==1.13.1; sys_platform == 'darwin' and platform_machine == 'arm64'
- onnxruntime-gpu==1.15.0; sys_platform != 'darwin'
- tensorflow==2.13.0rc1; sys_platform == 'darwin'
- tensorflow==2.12.0; sys_platform != 'darwin'
- opennsfw2==0.10.2
- protobuf==4.23.2
- tqdm==4.65.0
