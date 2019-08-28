# tfjs-node-example

Using TensorFlow.js with pre-trained MobileNet model for image classification on Node.js

* http://jamesthom.as/blog/2018/08/07/machine-learning-in-node-dot-js-with-tensorflow-dot-js/

Tested:
1. Ubuntu 18.04 Intel
2. Ubuntu 18.04 Jetson TX2
3. Ubuntu 18.04 Jetson Nano
4. Raspbian Raspberry Pi4

Notes:
https://gist.github.com/bigsnarfdude/b9926795b039f89af10ae482db7ac083

## Step 1: Install node and npm

## Step 2: git clone this repo with

`git clone https://github.com/bigsnarfdude/tfjs-node-example.git `

## Step 3: install dependancies

`npm install`

## Step 4: run prediction on panda.jpg against pre-trained model

`node script.js mobilenet/model.json panda.jpg`
