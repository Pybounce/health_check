sudo apt-get update
sudo apt-get install python3
sudo apt-get install python3-pip
pip3 install flask flask_restful psutil

`nohup python3 app.py &` Does not seem to work here
`nohup python3 app.py > /dev/null 2>&1 &` This works
