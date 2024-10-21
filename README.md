# Segment Anything Using Python for Microscopy Data - I2K Workshop 2024

Welcome to the official repository for the **[Segment Anything Using Python for Microscopy Data](https://events.humantechnopole.it/event/1/contributions/31/)** workshop, held at **I2K 2024** on **October 25, 2024** at **9:45 am** in the **Mezzanine Room, Human Technopole**.

This workshop will demonstrate how to use the Segment Anything Model (SAM) for segmenting microscopy data using Python. We will walk through setting up your environment, downloading the model checkpoint, and applying SAM to microscopy datasets. By the end of the workshop, participants will be able to leverage SAM for their image segmentation tasks and make modifications accordingly.

---

## Workshop Details

- **Title**: Segment Anything Using Python for Microscopy Data
- **Date**: October 25, 2024
- **Time**: 9:45 am
- **Location**: Mezzanine Room, Human Technopole

---

## Setup Instructions

Please follow these steps to prepare for the workshop:

### Step 1: Clone the Repository
First, clone this repository to your local machine using the following command:

```bash
git clone -b i2k-2024 https://github.com/rkarmaka/SAM-using-Python-for-Microscopy-Data.git
```

### Step 2: Change Directory
Navigate to the cloned directory:

```bash
cd SAM-using-Python-for-Microscopy-Data
```

### Step 3: Set Up the Environment
Depending on whether or not you have a CUDA-enabled laptop, set up the appropriate environment using conda.

For CUDA-enabled devices (GPUs):
```bash
conda env create -f sam-cuda.yaml
```

For CPU-only devices (including Mac):
```bash
conda env create -f sam-cpu.yaml
```

### Step 4: Download Model Checkpoint
Download the model checkpoint using [this link](https://dl.fbaipublicfiles.com/segment_anything/sam_vit_h_4b8939.pth) and save it inside the `model-checkpoint` folder within the cloned repository.  
**Note:** The model checkpoint file is 2.39 GB, so please ensure that it is downloaded ahead of the workshop.

---

## Bonus Materials

If you're interested in exploring additional materials related to the workshop, here are some resources that may be useful:

- [SAM Paper](https://arxiv.org/abs/2304.02643)  
- [SAM2 Paper](https://arxiv.org/abs/2408.00714)  
- [Workshop Material PDF](https://github.com/rkarmaka/SAM-using-Python-for-Microscopy-Data/blob/i2k-2024/Segment%20Anything%20with%20Python%20for%20Microscopy%20Images-I2K.pdf)

---

Please feel free to reach out if you have any questions, and we look forward to working with you during the workshop!

---

This `README.md` provides a clear overview of the repository and the setup process. Let me know if you need further adjustments!