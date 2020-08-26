# Road Crack Detection by using yolov3

To convert the data from xml to yolo format(txt format) (Here you need to adjust the paths)

	python xmltotxt.py

split your data for training  and  validation (Here i have used 80% for train and 20% for val)

	python split_data.py

Now set your configuration files

     set all paths correctly in coco.data file
     save all your classes names in coco.names file
     change the number of classes at 3 places in cfg file , wherever [yolo] present 
     also change the filters = [no of classes + 5] *3 in 3 place just above the [yolo]


Now open the ipynb notebook and follow the procedure
