## Project: Safety Helmet Detection

### Vision:
To enhance workplace safety by automatically detecting helmet usage using advanced machine learning and computer vision techniques.

### Motivation:
Head injuries in the construction industry are a major safety concern. From 2003 to 2010, approximately 2,200 fatalities were attributed to head injuries. Ensuring that workers wear helmets can significantly reduce the risk of such injuries.

### Data Collection and Preparation:
- **Data Source**: High-quality images were gathered from the (https://pan.baidu.com/s/1UbFkGm4EppdAU660Vu7SdQ).
- **Annotation Format**: The annotations were reformatted to the YOLO (You Only Look Once) format to be compatible with the model training process.

### Model Training:
- **Models Used**: YOLOv5 and YOLOv8 were selected for their state-of-the-art performance in object detection tasks.
- **Training Duration**: The total training time spanned over 120 hours, with the final model being trained for 26 hours.
- **Dataset Size**: A robust dataset of 7,500 images was used to train the model.
- **Performance Metrics**: The final model achieved a precision rate of 92.90%, indicating high accuracy in detecting helmet usage.

### Application Development:
- **Frameworks**: The application was developed using Streamlit for the user interface and OpenCV for video processing capabilities.
- **Challenges**: Significant effort was dedicated to handling real-time video processing challenges to ensure smooth and efficient operation.
- **Capabilities**: The app can process live video feeds to detect individuals not wearing helmets and update the count of detected instances in real-time.

### Demo:
- **Functionality**: The application identifies people not wearing helmets and provides a real-time update on their count, helping managers ensure safety compliance on construction sites.
- **Access**: You can see the application in action at (https://helmetdet-app.streamlit.app/).

### Unique Strengths:
- **Enhanced Detection Range**: Unlike Google's PPE (Personal Protective Equipment) detector, our model can detect helmets even from distances far beyond the normal sight range, making it exceptionally useful in large-scale construction sites.
- **Comparative Advantage**: The application provides superior detection capabilities compared to existing solutions, such as the Google PPE detector, which can be explored further in the (https://cloud.google.com/vision-ai/docs/ppe-detector-model).
