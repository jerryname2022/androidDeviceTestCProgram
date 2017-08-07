# androidDeviceTestCProgram
#build program for your device
(use make ?)

#push program to your device`s /data/local/tmp/    , 
adb push <your program>  /data/local/tmp/

adb shell

cd /data/local/tmp/
./<your program>
