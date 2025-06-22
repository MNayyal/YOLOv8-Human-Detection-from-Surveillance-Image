# Human Detection from Surveillance Image using YOLOv8

This project applies YOLOv8 to detect humans in a static surveillance-style image. The script loads an image, detects people using the YOLOv8n model, annotates the image with bounding boxes, and logs the number of people detected along with the current timestamp.

## 📌 Features

- Uses Ultralytics YOLOv8n (nano version) for lightweight and fast inference
- Detects only class `0` (humans)
- Annotates the input image with bounding boxes and a people count
- Logs results to a CSV file including timestamp and count
- Saves annotated image and log file (optional)


## 📷 Example Output

![Example](Screenshot (6466).png)  
*Sample output with bounding boxes drawn around detected persons.*


## 🛠 Requirements

Install dependencies:
```bash
pip install opencv-python ultralytics pandas matplotlib

