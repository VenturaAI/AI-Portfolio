eyeDrive: Driver Fatigue Detection System

Context: Road Accident Stats: In India, According to data provided by the Yamuna Expressway Industrial Development Authority, over the last 12 years from Jan 2012 to March 2023, more than 44% of accidents on 165km long and 6 lane wide expressway occurred due to driver dozing off. A total of 488 people died and 3,873 were injured in 3,207 accidents due to drivers dozing off.

1. Recognizing the prevalent challenges of long hours behind the wheel and a high incidence of fatigue-related accidents, our drowsiness and driver fatigue detection app (eyeDrive) emerges as an innovative solution tailored for inexpensive cars.

2. In this project, I leveraged cutting-edge eye-tracking/object detection technology such as Yolo v10 in the app for real-time monitoring of a driver's condition thus, swiftly detecting signs of drowsiness.

3. YOLOv10 supports a full range of vision AI tasks, including detection, segmentation, pose estimation, tracking, and classification. This versatility allows users to leverage YOLOv8's capabilities across diverse applications and domains.

4. With customizable warning alerts, the solution ensures that drivers receive timely notifications, contributing to a reduction in fatigue-related accidents and an overall improvement in road safety.

5. We had prepared a dataset of images with drowsy and awake classes by using pre and post processing, which was further used to train the object detection machine learning model.

6. The net accuracy of the ML model came out to be quite good at 97.8% in successfully detecting the drowsy frames and awake frames when camera is pointed towards the eyes of the driver.

7. An android mobile application was also made using the ml model in the backend.

Application Goal was to provide an inexpensive and easily available solution for driver fatigue detection that is easy to use and portable like ‘apk’ file for Mobile devices.

Methodology:

• Capture video from smartphone camera

• Use the model to detect driver fatigue.

• Ring an alarm on drowsiness detection. It uses Model such as Inception V3 and Yolov10 in background to identify the regions of interest.

• The architecture is scalable to include taking other actions - such as sending notifications, calling an emergency number in case of continuous warnings.

