# YOLO-Image-Search
An end-to-end YOLO-based object detection pipeline on a collection of images, enabling image retrieval based on detected objects and their frequencies.

 End-to-end Streamlit-based application consisting of three stages:<img width="1672" height="941" alt="workflow" src="https://github.com/user-attachments/assets/3a6ad033-8f84-45bc-af8b-deec99299477" />

1. Performed model inferencing using the YOLOv11 object detection model to identify objects in images across 80 classes, and stored detected object labels along with their counts in a metadata.json file. The system also supports directly loading previously generated metadata files.
2. Implemented a user-driven search interface that allows customized image retrieval based on selected object classes and their corresponding counts.
3. Built a visualization module to display the searched images, along with an option to export the filtered search results as a metadata.json file.
