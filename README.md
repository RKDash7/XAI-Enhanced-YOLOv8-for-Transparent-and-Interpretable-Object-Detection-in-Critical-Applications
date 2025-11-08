# XAI-Enhanced-YOLOv8-for-Transparent-and-Interpretable-Object-Detection-in-Critical-Applications
This paper proposes an Explainable AI (XAI)-enhanced YOLOv8 model that combines YOLOv8's rapid detection capabilities with XAI-based explanation techniques.
To explain the working of the Yolov8 model, three different datasets are considered:
1. Drowsiness detection dataset[38]
The dataset comprises 258 images categorized into three classes: Alert, Yawn, and Microsleep. The
training dataset contains 237 images, while the validation and test datasets each contain 12 and 9 images,
respectively. The existing model predicts 91.8% precision and 99.3% recall.
2. Rice leaf disease detection dataset[39]
The dataset contains 5188 images of rice leaves (healthy and infected). The infected leaves are categorized
into Brown spot, Leaf Blight, Leaf Scald, Leaf Blast, Leaf Smut, Narrow brown spot, Rice Bacterial Blight,
Rice Blast, and bacterial leaf blight. The dataset has 3894 images for training, 932 for validation, and 362
for testing.
3. Lung cancer detection dataset[40]
The dataset comprises 4394 images, categorized into 14 distinct disease types, including the normal case.
Of these images, 3184, 1009, and 201 are reserved for training, validation, and testing, respectively. The
existing model achieves 38.2% precision and 30.2% recall.
The datasets mentioned above, along with the pretrained YOLO models, are available at
https://public.roboflow.com/.
