# MCDFuse
MCDFuse: Visible and infrared image fusion via Mamba-CNN for Enhanced UAV Perception

# UAVScene Dataset
## 📁 Dataset Structure
The dataset is organized as follows:
UAVScene/                                                                     <br>
├── images/   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              # Contains visible and infrared image folders   <br>
│ ├── vi/     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                # Visible images                                <br>
│ │ ├── 1.jpg                                                                <br> 
│ │ ├── 2.jpg                                                                <br>
│ │ └── ...                                                                  <br>
│ └── ir/    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                 # Infrared images                               <br>
│ ├── 1.jpg                                                                  <br>
│ ├── 2.jpg                                                                  <br>
│ └── ...                                                                    <br>
├── labels/    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              # YOLO-format annotation files                  <br>
│ ├── vi/       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;              # Annotations for visible images                <br>
│ │ ├── 1.txt                                                                <br>
│ │ ├── 2.txt                                                                <br>
│ │ └── ...                                                                  <br>
│ ├── ir/           &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;          # Annotations for infrared images               <br>
│ │ ├── 1.txt                                                                <br>
│ │ ├── 2.txt                                                                <br>
│ │ └── ...                                                                  <br>
│ └── fused/       &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;     # Annotations for fused images                  <br>
│ │ ├── 1.txt                                                                <br>
│ │ ├── 2.txt                                                                <br>
│ └── ...                                                                    <br>
├── split/          &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;         # Dataset split files                           <br>
│ ├── train.txt     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;       # Training image IDs                            <br>
│ └── test.txt      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;        # Test image IDs                                <br>
└── README.txt        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   # Additional dataset usage instructions         <be>


> 🔍 **Notes:**  
> - The `vi/` and `ir/` folders contain aligned visible and infrared images.  
> - The `labels/` folder includes annotations for visible, infrared, and fused modalities.  
> - All annotations are in YOLO format and share filenames by image ID.

---

## 📦 Dataset Availability

The **UAVSense** dataset will be made publicly available after the official publication of the corresponding paper.  
Until then, access can be granted upon reasonable request to the corresponding author.

