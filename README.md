# Logo-Detection
 
Install the required dependencies onto your Raspberry Pi

pip3 install opencv-python 

sudo apt-get install libcblas-dev

sudo apt-get install libhdf5-dev

sudo apt-get install libhdf5-serial-dev

sudo apt-get install libatlas-base-dev

sudo apt-get install libjasper-dev 

sudo apt-get install libqtgui4 

sudo apt-get install libqt4-testv

echo "deb https://packages.cloud.google.com/apt coral-edgetpu-stable main" | sudo tee /etc/apt/sources.list.d/coral-edgetpu.list

curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -

sudo apt-get update

sudo apt-get install python3-tflite-runtime



install pycoral:
sudo apt-get install python3-pycoral

Run the python3 detect.py in terminal

FOR LATER USE: 
Make sure edge-tpu is installed on the raspberry pi:

sudo apt-get update
sudo apt-get install libedgetpu1-std

Run Coral-commands.txt in terminal
