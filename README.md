# Yolov8-detecton-result
wafer Defect Detection using YOLOv8
Dataset: WM-811K
Model: YOLOv8m
Classes:
- Center
- Donut
- Scratch
- Edge-Loc
- Edge-Ring
- Loc
- Random
- Near-full
- datasheet link: https://drive.google.com/drive/folders/1QTGPqi35OhFrKSrvcvUtx_qvSA5Inb-s?usp=sharing
The structure of the file will be like:
Datasheet/
         /images
                /train/
                      /Center
                              / images.png
                      /Donut
                      /Scratch
                      /Edge-Loc
                      /Edge-Ring
                      /Loc
                      /Random
                      /Near-full
                /val
                ...
                /test  
         /labels
              /train/
                      /Center
                              /images.txt
                      /Donut
                      /Scratch
                      /Edge-Loc
                      /Edge-Ring
                      /Loc
                      /Random
                      /Near-full
                /val
                ...
                /test 
  

