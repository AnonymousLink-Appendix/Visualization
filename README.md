# Additional Qualitative Results

This repository contains the official results and demonstration for our paper on generating realistic talking heads from audio input.

---

## 🎥 Video Demonstrations

We conduct qualitative comparisons of our method against Wav2Lip (MM’20), SadTalker (CVPR’23), RealPortrait (ICLR’24), and KDTalker (IJCV’25). In particular, KDTalker is diffusion-based method.

### Example 1 
https://github.com/user-attachments/assets/6f9e1963-6edf-404c-9c11-8df18932dc85

### Example 2
https://github.com/user-attachments/assets/efc54d7a-4c5a-49c3-8c8c-acda4e78dd5f

### Example 3
https://github.com/user-attachments/assets/f96f9879-da73-4330-b5bd-f661b1946413

## 🎥 Robust Generalization in the Wild
Our model excels at generalizing to data it has never seen before. To demonstrate this, we showcase its performance on challenging "in-the-wild" scenarios. 

### 1. Source Image from unseen (VFHQ) dataset + Audio form HDTF dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/465b7849-3aa6-459d-b104-646ebf5ddba7" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/d241f304-07f3-4da2-82a5-028972964b32" muted="false" width="100%"></video> |

### 2. Source Image from unseen (VFHQ) dataset + Audio form unseen dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/a37fb198-350a-412c-bf9a-caba13f58b89" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/fdf5104f-80bf-46e1-ac5c-695a14e2d7e7" muted="false" width="100%"></video> |

### 3. Source Image from unseen (VFHQ) dataset + Audio form unseen (VFHQ) dataset
| Source Img | RETA             | 
|------------|------------|
|<img src="https://github.com/user-attachments/assets/e881348b-432e-4844-a3a6-7bd794aceb32" width="100%"></img> | <video controls loop src="https://github.com/user-attachments/assets/2adcdce6-7fe6-4228-9d8a-5db174d2cf9e" muted="false" width="100%"></video> |
