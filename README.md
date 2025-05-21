
**Advancing White Blood Cell Classification: A Hybrid Deep Learning Approach with GAN-Based Data Balancing**  

This repository contains the official implementation of the research paper titled **"Advancing WBC Classification: A Hybrid ConvNextV2-Swin Transformer Framework with R3GAN Data Balancing and CLAHE Preprocessing"**, which introduces a novel methodology for highly accurate classification of white blood cells (WBCs) in imbalanced medical imaging datasets.  

### 🔑 **Key Features**  
1. **Hybrid Architecture**: Leverages the strengths of **ConvNextV2** (a modern CNN variant) and **Swin Transformer** (a hierarchical vision transformer) to capture both local and global features in blood cell images, achieving robust feature representation.  
2. **Data Balancing with GANs**: Addresses class imbalance in the Raabin-WBC dataset using advanced generative models:  
   - **R3-GAN** (Recurrent Residual Refinement GAN) and **ECC-GAN** (Edge-Aware Cycle-Consistent GAN) to synthesize high-fidelity, diverse WBC images.  
3. **CLAHE Preprocessing**: Enhances image quality via **Contrast-Limited Adaptive Histogram Equalization (CLAHE)**, improving model sensitivity to subtle cellular structures.  
4. **State-of-the-Art Performance**: Achieves **~99% accuracy** in WBC classification, demonstrating significant improvements over traditional methods.  

### 📝 **Methodology Overview**  
- **Data Augmentation**: R3-GAN and ECC-GAN generate realistic synthetic images to balance underrepresented WBC classes in the Raabin dataset.  
- **CLAHE**: Preprocesses raw images to enhance contrast and highlight critical morphological details.  
- **ConvNextV2-Swin Fusion**: Combines ConvNextV2’s spatial feature extraction with Swin Transformer’s long-range dependency modeling, optimized through cross-stage feature fusion.  

### 📈 **Results**  
The proposed framework outperforms existing approaches in precision, recall, and F1-score, validated on the challenging Raabin-WBC dataset. The hybrid model’s interpretability is further enhanced via attention maps from the Swin Transformer.  



### 🛠 **Usage**  
1. Clone the repository and install dependencies.
2. Set your dataset path: Simply replace the default dataset path in the provided configuration files/scripts with your own dataset path.
3. Run the preprocessing, augmentation, and training scripts — the pipeline handles the rest!

### 🤝 **Contributions**  
Contributions and issues are welcome! Let’s advance computational hematology together.  

---  
**Tags**: Computational Pathology, Medical Imaging, Deep Learning, GANs, Transformers, Data Augmentation, CLAHE, WBC Classification  

This project bridges the gap between vision transformers, CNNs, and generative models, offering a reproducible pipeline for medical image analysis with imbalanced data. 🌟  

---
