English | [简体中文](./Readme_cn.md) |

# ONNXOCR
#### Universal OCR, supporting inference in over 80 languages.
Version Update
The PPOCRv4 model converted to an ONNX model for inference achieves higher accuracy and performance, with the inference speed being 5 times faster than using the PaddlePaddle framework.

Advantages:
1.Independent from deep learning training frameworks, it is a general OCR that can be directly deployed.
2.In situations where computational power is limited and accuracy remains unchanged, the PaddleOCR is converted into an ONNX model, which has been 3.reconstructed as an OCR model that can be deployed on computers with ARM architecture and x86 architecture.
4.On computers with equivalent performance, the inference speed has been accelerated by 4-5 times.


Effect Display


![Alt text](result_img/draw_ocr_1.jpg)

![Alt text](result_img/draw_ocr2.jpg)

![Alt text](result_img/draw_ocr3.jpg)

![Alt text](result_img/draw_ocr4.jpg)

![Alt text](result_img/draw_ocr5.jpg)

![Alt text](result_img/draw_ocr.jpg)