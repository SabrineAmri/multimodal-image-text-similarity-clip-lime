# Multimodal Image-Text Similarity and Explanation using CLIP and LIME

This project demonstrates how to use the CLIP (Contrastive Language–Image Pretraining) model to compute the similarity between images and text, and provides explainability for the predictions using the LIME (Local Interpretable Model-agnostic Explanations) framework.

## Project Overview

This project downloads a sample image, processes it along with a provided text, and uses the CLIP model to evaluate the similarity between the image and text. It provides explanations for the model's decision by highlighting key parts of the image and text using LIME.

### Features:
- **CLIP Model**: Computes the similarity between the image and text input.
- **LIME for Image**: Highlights the most important regions of the image that contributed to the similarity score.
- **LIME for Text**: Highlights the most important words in the text that contributed to the similarity score.

### Requirements:
- Python 3.x
- The following Python libraries:
  - `transformers`
  - `lime`
  - `Pillow`
  - `wget`
  - `matplotlib`
  - `numpy`
  - `scikit-image`

### Setup Instructions

1. **Clone the repository**:
    ```bash
    git clone https://github.com/SabrineAmri/multimodal-image-text-similarity-clip-lime.git
    cd multimodal-image-text-similarity-clip-lime
    ```

2. **Install dependencies**:
    You can install the required dependencies using pip:
    ```bash
    pip install transformers lime Pillow wget matplotlib numpy scikit-image
    ```

3. **Run the notebook**:
   Launch Jupyter notebook or JupyterLab, open `multimodal_image_text_similarity_CLIP_LIME.ipynb`, and run the cells step by step.

4. **Test with a sample image**:
   The project downloads a sample image, processes it, and compares it with the provided text. LIME provides visual explanations for both the image and the text.

### Future Improvements:
- Allow users to upload custom images and provide their own text for evaluation.
- Add a user interface to streamline the process.

### Example Output:

When running the notebook, the following steps will be executed:
- Download a sample image from the web.
- Provide a sample text (e.g., "Sharks in Floodwaters").
- CLIP will compute the similarity between the image and the text.
- LIME will generate an explanation, highlighting regions in the image and important words in the text that contribute to the similarity score.

