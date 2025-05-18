# ImageObjectDetection

A project for detecting objects in images using deep learning (e.g., YOLO, SSD).

## Setup

1. **Clone Repo**
   ```bash
   git clone https://github.com/Ghost6116/ImageObjectDetection.git
   cd ImageObjectDetection
   ```

2. **Install Dependencies**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```

3. **Download Model Weights**
   - Get pre-trained weights (e.g., `yolov3.weights`) and place in `models/`.

## Run

Detect objects in an image:
```bash
python main.py --image data/sample.jpg --output output/
```

## Requirements
- Python 3.6+
- TensorFlow/PyTorch, OpenCV, NumPy

*Note*: Check repo for specific model files and script names.
