# EMDMC-Demo
This project demonstrates the evaluation of some finetuned EMDMC-CLIP models for breast cancer X-ray image classification, as described in the associated paper. It outputs the classification accuracy for different model parameters.

## Setup Instructions
1. **Install Python 3.10** and required dependencies:
````bash
pip install -r requirements.txt
````
2. **Download Datasets and Models**:
   - The `datasets` and `models` folders are not included in this repository due to size constraints.
   - Download them from: [OneDrive Link](https://uwoca-my.sharepoint.com/:f:/g/personal/zyan297_uwo_ca/EngueT9Tjp9IipVPspSwaF8Bn_V4MukyiPhBKaWm3_E_Rw?e=X46xNN) (replace with your actual OneDrive link).
   - Place the `datasets` and `models` folders in the project root.
3. **Run the Demo**:

````bash
jupyter notebook Evaluation.ipynb
````

## Dependencies
- See `requirements.txt` for the full list of required packages.

## Notes
- Ensure the dataset path in `Evaluation.ipynb` matches the location of your `datasets` folder.
- The finetuned model weights are stored in the `models` folder.