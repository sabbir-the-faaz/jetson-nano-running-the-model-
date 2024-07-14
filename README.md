# jetson-nano-running-the-model-
1. Board Connent
2. Connect webcam 
3. connect jetson with monitor and login id: sabbir password:1819020
4. connect it with wifi hotspot of phone
5. connect pc with the same wifi hotspot of phone
6. download no machine on pc
7. check ip adress of nx server of no machine form jetson nano
8. manually input the nx ip adress of jetson nano on pc's no machine
9. press add
10. double click and try to connect .
11. wait for sometime till it connects
12. if connection is established, disconnect the monitor. Now open terminal.
```
cd ultralytics
source venv/bin/activate
yolo task=segment mode=predict model=best.pt source=0 show=True

```
13. soon the segmentation will be started and you will notice real time segmentation with yolo v8









