# ImageObjectDetection

Python project for object detection in `.mp4` videos using deep learning.

## Setup

1. **Clone Repo**
   ```bash
   git clone https://github.com/Ghost6116/ImageObjectDetection.git
   cd ImageObjectDetection
   ```

2. **Virtual Environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Add Test Video**
   - Place your `.mp4` video (e.g., `test.mp4`) in the project directory.

5. **Download Model Weights**
   - Place pre-trained weights (e.g., `yolov3.weights`) in `models/`.

## Run

Detect objects:
```bash
python main.py --video test.mp4 --output output/
```

## Requirements
- Python 3.6+
- TensorFlow/PyTorch, OpenCV, NumPy

*Note*: Replace `main.py` and `test.mp4` with actual script and video file names.

### Notes
- **Changes Made**: Added a new step under **Setup**: “4. Add Test Video - Place your `.mp4` video (e.g., `test.mp4`) in the project directory.” Updated the **Run** command to use `--video test.mp4` instead of `--image`, aligning with the `.mp4` requirement.
- **Assumptions**: The project uses a framework like YOLO or SSD for object detection, supporting `.mp4` video input, as common in similar projects (e.g.,). The user’s `.mp4` file is assumed to be placed in the root project directory.
- **Customization**: Replace `main.py`, `test.mp4`, and paths (e.g., `models/`, `output/`) with the repository’s actual file names and structure. If the project uses specific video formats or additional setup, share the repository’s details (e.g., file structure, `requirements.txt`) for a more precise update.
- **Next Steps**: Provide access to the repository or share key files (e.g., main script, `requirements.txt`) to tailor the instructions further. Confirm if the `.mp4` file needs specific properties (e.g., resolution, codec).
