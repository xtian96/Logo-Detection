# Logo-Detection
Make sure edge-tpu is installed on the raspberry pi:

echo "deb https://packages.cloud.google.com/apt coral-edgetpu-stable main" | sudo tee /etc/apt/sources.list.d/coral-edgetpu.list
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
sudo apt-get update
sudo apt-get install libedgetpu1-std

install pycoral:
sudo apt-get install python3-pycoral

Run the commands.txt in terminal

FOR LATER USE: Run Coral-commands.txt in terminal
