# Digit-recognition
Digit recognition using PyTorch and neural networks
I also created a script which resize every image thay user upload into program into 28 x 28 px .png file
Here are some examples of how it works:
<p align="center">
  <p>
    It trains on special dataset from MNIST library and then calculates the result after each epoch
  </p>
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/65b7a377-ad87-432f-a4ca-bd623ca28c5a" />    
  <br />
</p>

<p align="center">
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/0180ec3d-0932-4155-817e-3b3766e022e0" />
  <br />
  Example for number '2' from MNIST library 
</p>

<p align="center">
  I tested it also in not easy examples such as Captcha numbers
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/2b4e8727-9610-432b-b401-9e950ccfcbde" />
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/c6310242-076b-425a-b8bf-9c34ec434102" />
  <br />
  Example for number '2' from random Captcha screen
</p>

<p align="center">
  For example below it didn't work because of the quality after program resized the .png image
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/53d8b0f2-1d40-4956-bde7-577b9a57737a" />
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/42edf800-6a89-40eb-8b96-0b8707c2cded" />
  <br />
  Example for number '6' from random Captcha screen
</p>

<p align="center">
  I tried also the "hand made" examples that I did in paint and here is how it looks:
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/d9243d91-4f76-4f2e-a387-3de094aa455eS" />
  <img src="https://github.com/mryt66/Digit-recognition/assets/64143856/4518b47e-3cf3-48b8-8b56-c26c96cc8286" />
  <br />
  Example for number '7' from paint
</p>

When it comes to regular square .png images, the program handles them well. However, issues can arise when working with non-square .png files, such as one with a resolution of 200 x 800 pixels. In such cases, the program may produce unexpected results. While a perfect square isn't necessary, the image should have dimensions that mimic a square to ensure the program works as intended.




