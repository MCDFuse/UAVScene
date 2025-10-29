# MCDFuse
MCDFuse: Visible and infrared image fusion via Mamba-CNN for Enhanced UAV Perception

# UAVScene Dataset
## 📁 Dataset Structure
The dataset is organized as follows:  <br>

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
└── README.txt        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   # Additional dataset usage instructions         <be>


> 🔍 **Notes:**  
> - The `vi/` and `ir/` folders contain aligned visible and infrared images.  
> - The `labels/` folder includes annotations for visible, infrared, and fused modalities.  
> - All annotations are in YOLO format and share filenames by image ID.


## 📦 Dataset Availability

The **UAVSense** dataset includes 300 publicly available example pairs. The data can be downloaded from the following links:

- [Google Drive](https://drive.google.com/drive/folders/1RQ_i2_ZTRqCnNI4rOGPE0JvkvoNIdJLN?usp=sharing)  
- [Baidu Netdisk](https://pan.baidu.com/s/1ERDI1Wv4l95BPzvzVr3r_g) (Extraction code: dxpk)

For access to the full dataset, please contact the corresponding author with a reasonable request.
