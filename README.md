# C++ and OpenCv demo for machine vision.
## Machine vision for embedded systems
Embedded systems are everywhere, most of them in intelligent houses.
But intelligen houses don't require a lot of accuracy and reliability, moreover,
robotics require precise and accurate controllers based on reliable input data.
The responsibility of the reliable intput data mostly belongs to three different 
parts:
- **Sensors.** The resolution and the ability to get the mos accurate and reliable data 
start with a good sensor, in machin vision, this sensor belongs to the camera/s where 
the image is taken. More resolution, bigger sensor and better processor can take better images
in a worst illumination and faster. More cameras can improve the image input data and
can get different types of data as RGB and IR.
- **Environment conditions.** Cameras aren't capable to take all the information 
in any conditions, lights are the most important gap for machine vision, low lights 
reduce the reliability of the image and increase the noise.
- **Algorithms of image processing.** Some algorithms are better to extract characteristics of
the input image, but can be computationally expensive. This is one of the reasons to use C++ 
instead of python.

## Fourier discrete transform
The discrete Fourier transform changes spatial variables for frequency. This transform can
be useful as periodical remover, for example.
