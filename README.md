# About
This is a fork of the ![footbot-robot|https://github.com/ilpincy/argos3/tree/master/src/plugins/robots/foot-bot], the only difference being that its size was increased by
2.939905117267053 to fit the requirements for an experiment on finding the closest light.

# Compiling the code

Make sure you have ARGoS >= 3.0.0-beta55 installed!

Commands:
```shell
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ../src
make
sudo make install
```
