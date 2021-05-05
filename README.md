# C-Python
zeroMQ data interface between C and Python

Install zeroMQ on Ubuntu:
apt-get install clang libzmq5 libzmq3-dev python3 python3-zmq

Compile C code:
clang -I. client.c -lzmq -o client_zmq

Install Python zeroMQ library:
python3 -m pip install zmq