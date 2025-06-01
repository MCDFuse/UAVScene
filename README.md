# MCDFuse
MCDFuse: Visible and infrared image fusion via Mamba-CNN for Enhanced UAV Perception

## 📁 Dataset Structure
dataset/
├── images/                  # Contains visible and infrared image folders
│ ├── vi/                    # Visible images
│ │ ├── 1.jpg
│ │ ├── 2.jpg
│ │ └── ...
│ └── ir/                    # Infrared images
│ ├── 1.jpg
│ ├── 2.jpg
│ └── ...
├── labels/                  # YOLO-format annotation files
│ ├── vi/                    # Annotations for visible images
│ │ ├── 1.txt
│ │ ├── 2.txt
│ │ └── ...
│ ├── ir/                    # Annotations for infrared images
│ │ ├── 1.txt
│ │ ├── 2.txt
│ │ └── ...
│ └── fused/                 # Annotations for fused images
│ │ ├── 1.txt
│ │ ├── 2.txt
│ └── ...
├── split/                   # Dataset split files
│ ├── train.txt              # Training image IDs
│ └── test.txt               # Test image IDs
└── README.txt               # Additional dataset usage instructions

## Dataset Availability
The dataset associated with this repository will be made publicly available after the official publication of the related paper.
Before that, access can be granted upon reasonable request to the corresponding author.
