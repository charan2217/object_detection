# Object Detection

## Overview
This project implements object detection using deep learning models. The repository contains scripts for training, validating, and deploying an object detection model.

## Features
- Train a custom object detection model
- Validate the trained model
- Run inference on new images
- Export the trained model for deployment

## Installation
To get started, clone the repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/charan2217/object_detection.git
cd object_detection

# Install dependencies
pip install -r requirements.txt
```

## Usage
### Training the Model
To train the model, use the following command:
```bash
python train.py --data <path_to_data> --epochs <num_epochs>
```

### Running Inference
To run inference on an image:
```bash
python detect.py --image <path_to_image>
```

### Validating the Model
To validate the trained model:
```bash
python val.py --weights <path_to_model_weights>
```

### Exporting the Model
To export the trained model:
```bash
python export.py --weights <path_to_model_weights>
```

## Files and Directories
- `detect.py` - Runs inference on input images.
- `train.py` - Script for training the object detection model.
- `val.py` - Validates the trained model.
- `export.py` - Converts the trained model for deployment.
- `requirements.txt` - List of dependencies.
- `hubconf.py` - Model configuration file.
- `tutorial.ipynb` - Jupyter notebook with example usage.

## License
This project is licensed under the AGPL-3.0 License.

## Author
[charan2217](https://github.com/charan2217)

## Contributions
Contributions are welcome! Feel free to submit a pull request or open an issue.

