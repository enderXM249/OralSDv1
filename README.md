# OralSDv1: Multi-Modal Oral Disease Dataset

**OralSDv1** is a **custom-curated, expert-verified multi-modal dataset** designed for research in oral disease classification. This dataset was originally introduced in the paper _"VIT-MEDBERT: A Multi-Modal Transformer-Based Framework for Oral Disease Classification"_. It supports machine learning experiments that integrate both oral images and corresponding textual symptom descriptions.

<img width="533" height="318" alt="image" src="https://github.com/user-attachments/assets/4c7528ea-1d12-4899-b712-b4b2fef82ecd" />

## Dataset Overview

- **Total samples:** 1,163 paired entries
- **Modalities:**
  - **Visual:** High-resolution oral cavity images
  - **Textual:** Symptom descriptions and precautionary advice (e.g., pain intensity, symptom duration, clinical observations)
- **Classes:** Six common oral conditions:
  - **Caries:** Tooth decay and cavities
  - **Calculus:** Tartar/plaque buildup
  - **Gingivitis:** Inflamed gums
  - **Tooth Discoloration:** Staining or abnormal color
  - **Ulcers:** Oral sores
  - **Hypodontia:** Missing teeth
- **Label Balance:** Each folder contains approximately 175–200 samples to ensure balanced representation across all classes[1].

## Repository Structure

```
OralSDv1/
├── Calculus/
├── Caries/
├── Gingivitis/
├── Hypodontia/
├── Mouth_Ulcers/
├── Tooth_Discoloration/
├── classes_.csv
├── classes_.xlsx
├── classes_final.xlsx
```

- Each folder contains samples (image + text) for a specific disease class.
- Annotation files (`classes_.csv`, `.xlsx`) provide metadata and class labels for all samples.

## Intended Usage

OralSDv1 is intended for researchers and developers working in:

- Multi-modal medical AI (image + text)
- Automated oral disease diagnosis/classification
- Health informatics and dental informatics

Possible tasks include:
- Training and validation of multi-modal deep learning models
- Benchmarking oral disease classifiers
- Natural language and computer vision fusion in medical contexts

## How to Use

1. **Clone or Download**:  
   Download the repository or use `git clone` to obtain the dataset.
2. **Data Access**:  
   - Image data is organized by disease class subdirectories.
   - Symptom description and class metadata are found in the provided `.csv`/`.xlsx` files.
3. **Pairing Images and Text**:  
   Use the annotation files to map images to their corresponding textual descriptions.

## Citation

If you use OralSDv1 in your research, please cite:

## Acknowledgements

This dataset was created, annotated, and validated with expert clinical oversight[1].

## License

_The license for the dataset is not explicitly specified in the repository as of this version. Please contact the repository owners or dataset authors for details before commercial or large-scale use._

**Note:**  
This README is based on the structure and scientific description of OralSDv1 from its original publication and the current GitHub repository contents. Update and adapt sections as needed based on additional files, usage policies, or metadata provided in the repository itself[1][2].

[1] https://drive.google.com/file/d/1dUzWpKNQw09PR6nYeYbMUGDD4B7hUw6J/view?usp=sharing
[2] https://drive.google.com/drive/folders/1ludbMx8YCPX0iURlACjh0OB0kuNmueVw?usp=sharing 
