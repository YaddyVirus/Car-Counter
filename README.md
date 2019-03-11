# Car-Counter
Car counter code for deployment on IGL Gas stations. Currently in POC stage

Usage Instructions:
Ensure that Opencv 3.3.0 or higher is installed on your system. I recommend following PyImageSearch's excellent tutotrial if you haven't set that up already.

car_counter.py works normally with video.mp4. The script counts the number of cars passing through and saves it in a variable ready to be posted on to a database.

Car_detector.py is a more advanced version of the previous script that uses MobileNet SSD to detect cars in a real time feed and then counts the number of detections, then uploads them to a specified database.
Please note that the car_detector.py script requieres the caffemodel and MobileNetSSD.txt file to run. Both files need to be in the same directory as the script.
