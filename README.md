# NVIDIA-Jetson-Developer
NVIDIA Developer

### NVIDIA Jetson USB Microphone

##### jetson@linux:```lsusb```

##### jetson@linux:```arecord -l``` 

Recording WAVE 'test.wav' : Signed 16 bit Little Endian, Rate 48000 Hz, Stereo

##### jetson@linux:```arecord -D plughw:2,0 -f S16_LE -r 48000 -c 2 test.wav```
