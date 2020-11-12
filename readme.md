# Yolo Object Detection Steps:


## 1.Download "labelimg" an image labeling tool.
https://tzutalin.github.io/labelImg/
Label the images with the labelimg tool and store the image in a folder.




## 2.Create Google Colab notebook and connect to goole drive for your cloud storage.
1. Go to google drive ---> create new folder named yolov3(or any preferable name)
2. Inside Yolov3 upload the image folder in zip folder(Unzip it).upload the files to produce train and test data from the link https://github.com/Dharani1008/Yolov3_tutorial. There will be 2 files(creating-files-data-and-name.py,creating-train-and-test-txt-files.py),Open the files and it contains an location line ('image folder name') in that change the current mage folder location and name.Save it.
3. Inside the image folder there will be classes.txt file. save it as classes.names file and upload it in the image folder.
4. Also create folders with name backup,darknet and custom weights.
5. Inside custom weights folder upload the needed yolo weights which is downloaded from link http://pjreddie.com/media/files/darkn... 
6. Now open google colab and rename the notebook.In the edit tab ---> Notebook settings ---> Change to GPU.
7. Now follow the Notebook which is given in the link 
8. After the training completed.The custom models are saved in the backup folder.
9. To test the trained model another notebook named yolotesting in the link is given.
