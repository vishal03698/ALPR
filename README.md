# Automatic License Plate Recogniser

## Training on Local machine.
Virtual env or conda env is recommended<br/>  
Download the untrained weigths from the .sh file in config/<br/> 
Run train.py<br/> 
To test using image use yolo.py<br/> 
To test using video use yolo_video.py<br/> 

## Training using Colab
Upload the notebook from colab/<br/> 
Upload the zip file in your google drive in a folder.<br/> 
Mount your drive in colab using the codes in notebook<br/> 
Copy proper path for the zip file from drive.<br/> 
Follow the instructions further on.<br/> 
Impt - Change the runtime of the notebook to GPU<br/> 

### Using Colab trained weights in local machine.
Download the weights from backup folder from colab.<br/> 
Download the yolov3.cfg<br/> 
Copy the weights & yolov3 in config/<br/> 
To test using image use yolo.py<br/> 
To test using video use yolo_video.py<br/> 
