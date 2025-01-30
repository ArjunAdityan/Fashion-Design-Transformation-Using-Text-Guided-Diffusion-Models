# Fashion-Design-Transformation-Using-Text-Guided-Diffusion-Models
This repository contains the implementation of a novel approach for transforming fashion designs using text-guided diffusion models. The project combines LoRA-fine-tuned Stable Diffusion models with perceptual loss optimization to enable automated fashion design modifications while maintaining structural and stylistic integrity.

# Authors
Arjun Adityan (Department of Mathematics, Amrita Vishwa Vidyapeetham, Coimbatore, India)
Kabeleswar (Department of Mathematics, Amrita Vishwa Vidyapeetham, Coimbatore, India)
Karthikeyan Vaiapury (TCS Research and Innovation, IITM Research Park, Chennai, India)
Dr. T Palanisamy (Department of Mathematics, Amrita School of Physical Sciences, Amrita Vishwa Vidyapeetham, Coimbatore, India)
Senthil Kumar Tangavel (Department of Computer Science and Engineering, Amrita School of Computing, Amrita Vishwa Vidyapeetham, Coimbatore, India)

# Key Features
LoRA-Based Fine-Tuning Methodology for efficient domain-specific adaptation
Perceptual Loss Optimization for maintaining structural and stylistic characteristics
Multi-Faceted Evaluation Framework using SSIM and CLIP Score metrics
Fashion-specific dataset implementation using DeepFashion-MultiModal

# Technical Implementation
Framework: PyTorch 2.0
Primary Model: Stable Diffusion XL with LoRA fine-tuning
Hardware Requirements: NVIDIA RTX 3090 or equivalent
Key Dependencies: diffusers, transformers

# Dataset
Training Dataset: DeepFashion MultiModal dataset (44,096 high-resolution fashion images)
Evaluation Dataset: Custom dataset of 1,000 base garment images with 5,000 descriptive prompts
