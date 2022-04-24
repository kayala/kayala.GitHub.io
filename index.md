## Jie's Pages

I am an electronic engineer from China, currently living in Dresden, Germany. This is my personal page to introduce my self. You can also have a look on my german resume ([Lebenslauf](https://github.com/kayala/kayala.GitHub.io/blob/main/Lebenslauf_Jie.pdf)).

I am very interested in the field of software development and algorithm optimization.

I successfully completed my master's degree in electrical engineering at TU Dresden. I did a lot of deep learning research in my studies. I did a deep comparison and research on CNNs and optimized them in hardware and accelerated them in software.

After graduation I worked for TU Dresden for two years as a research assistant. At work I have increased my research on parallel algorithms and architectures. I have an in-depth understanding of existing acceleration algorithms and architectures, and developed parallel acceleration algorithms for radar detection.
Embedded development is also my area of interest, I like to develop applications and drivers on STM32, ESP32, Raspberry Pi. And I also learned to use QT for graphical interface development. 

If you're interested, you can see a brief introduction to projects I've worked on here.

### Converlutional neural networks

A Convolutional Neural Network (ConvNet/CNN) is a Deep Learning algorithm, is often utilized for classification and computer vision tasks.

For example, LeNet (or LeNet-5) is a basic convolutional neural network structure proposed in 1989, which can be applied for recognizing MNIST handwritten digit images. Here is an example for [Recognition MNIST handwritten digit images](https://github.com/kayala/project/tree/main/CNNs).

In convolutional neural networks, the computation of convolution is repeated a lot. Therefore, the power consumption of the device can be significantly affected by changing the calculation accuracy of the convolution in the low-power device, which is of great significance to the design of the computing unit.

Therefore, my master thesis is devoted to studying the impact of convolution accuracy on convolutional neural networks. At the same time, convolutional computing accelerator whose accuracy can be changed was designed.

### Mesh networks 

A mesh network is a network in which many nodes are linked together. A mesh network may include multiple routers, switches and other devices. In a full mesh network topology, each node is connected directly to all the other nodes. In a partial mesh topology, only some nodes connect directly to one another. In some cases, a node must go through another node to reach a third node.

ESP 32 is a series of low-cost, low-power system on a chip microcontrollers with integrated Wi-Fi and dual-mode Bluetooth, which is very suitable for building a prototype of mesh network.

Build [Mesh Networks](https://github.com/kayala/project/tree/main/mesh_network) on ESP32.

### Drivers for sensors and EEPROM

Driver for [EEPROM and NTP](https://github.com/kayala/project/tree/main/stm32) on STM32.

### Radar algorithm

[Detector](https://github.com/kayala/project/tree/main/radar_cfar_algorithm).
