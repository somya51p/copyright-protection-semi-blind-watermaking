# Copyright-protection-semi-blind-watermaking

This project uses a semi-blind watermarking approach to prove ownership of the image.

## Features

-> The aim of this case study is to demonstrate a digital watermarking scheme using visual cryptography for copyright protection of a digital image. 

-> Based on the security property of visual cryptography, the two shares on their own cannot leak any information about the watermark. 

-> The experimental results show that even after the image was modified, the invisible watermark was successfully extracted from it.


## How to run

```
git clone https://github.com/somya51p/copyright-protection-semi-blind-watermaking.git
```
```
cd copyright-protection-semi-blind-watermaking
```
Setup Virtual Environment and activate it.

For Linux -->
```
pip install opencv-python
```
```
pip install numpy
```
Then run the code in jupyter notebook.

1. **Ownership_Gen.ipynb** will generate the Ownership share for our image and watermark.

2. **Master_Gen.ipynb** will generate all the Master shares for each of the sample stolen and modified images. 

3. **Watermark_Gen.ipynb** will extract watermarks using the Ownership share with each of the master shares.

4. **Template_Res.ipynb** will give the accuracy of extracted watermark.

## Made with ♥
