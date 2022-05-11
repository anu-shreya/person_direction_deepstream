### DETECTING THE DIRECTION OF A PERSON
This application helps us in finding the direction in which the person is traversing. It is built on Nvidia Deepstream 5.1.
![person-moving](https://user-images.githubusercontent.com/86153411/167947349-0e7838a4-eca0-4f46-b2e4-027d2b7e665b.png)



## Deepstream Setup

This post assumes you have a fully functional Jetson device. If not, you can refer the documentation [here](https://docs.nvidia.com/jetson/jetpack/install-jetpack/index.html).

##  1. Install System Dependencies
```bash
sudo apt install \
libssl1.0.0 \
libgstreamer1.0-0 \
gstreamer1.0-tools \
gstreamer1.0-plugins-good \
gstreamer1.0-plugins-bad \
gstreamer1.0-plugins-ugly \
gstreamer1.0-libav \
libgstrtspserver-1.0-0 \
libjansson4=2.11-1
```
## 2. Install Deepstream
Download the DeepStream 5.1 Jetson Debian package deepstream-5.1_5.1.0-1_arm64.deb, to the Jetson device from [here](https://developer.nvidia.com/deepstream-getting-started). Then enter the command:

```bash
sudo apt install deepstream-5.1_5.1.0-1_arm64.deb
```
For more information, go to the get started page of Deepstream [here](https://docs.nvidia.com/metropolis/deepstream/dev-guide/index.html).

## 3. Clone the repository
```bash
git clone https://github.com/adlokib/bus_lane.git
cd bus_lane
```

## 4. Run the application

   I. To build the application
```bash
make
```
II. Now, run the application by providing the video source path 
```bash
make
```
./person_direction ----------------------------



## Please find the Link of a Demo video below
[here](https://youtu.be/OhjF_XYHkOg)
