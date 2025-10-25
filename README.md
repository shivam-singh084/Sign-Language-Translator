# Sign Language Translator

A computer vision project that translates sign language gestures into text using OpenCV and machine learning.

## Features

- Real-time hand detection and tracking
- Data collection for training custom sign language models
- Image preprocessing and normalization

## Requirements

- Python 3.x
- OpenCV
- cvzone
- NumPy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/shivam-singh084/Sign-Language-Translator.git
cd Sign-Language-Translator
```

2. Install required packages:
```bash
pip install opencv-python cvzone numpy
```

## Usage

### Data Collection
Run the data collection script to gather training data:
```bash
python datacollection.py
```

- Press 'm' to capture and save hand gesture images
- Images are saved in the specified folder with timestamps

## Project Structure

- `datacollection.py` - Script for collecting hand gesture data
- `Data/` - Directory containing collected gesture images

## Contributing

Feel free to contribute to this project by submitting pull requests or reporting issues.

## License

This project is open source and available under the MIT License.