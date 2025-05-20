![CLIP Cosine Similarity Matrix](./Cosine%20similarity%20matrix%20of%20cats.png)
# 🐱 Project: Multimodal AI with OpenAI CLIP – Cat Image Understanding

This project demonstrates the use of **OpenAI CLIP** (Contrastive Language–Image Pretraining) for **zero-shot classification** and multimodal alignment on a custom dataset of cat images. It explores how CLIP embeds images and text into a shared space and measures similarity using cosine distance.

---

## 📦 Dataset

* 10 cat images downloaded from the COCO dataset ([https://cocodataset.org/#explore](https://cocodataset.org/#explore))
* 10 manually written image prompts (descriptions of cats in different scenes)

---

## 🧠 Project Tasks

* ✅ Load and initialize the CLIP model using `openai/clip`
* ✅ Encode cat images and natural language prompts
* ✅ Compute **cosine similarity matrix** between each image and each text prompt
* ✅ Generate a **10x10 heatmap matrix** visualizing cosine similarities
* ✅ Generate **bar chart probability plots** showing CLIP's top predictions per image

---

## 💻 Files

| File                                                 | Description                                                      |
| ---------------------------------------------------- | ---------------------------------------------------------------- |
| `New_Interacting_with_CLIP_ipynb_AI_Ranran_Hu.ipynb` | Main Python notebook using OpenAI CLIP on cat images             |
| `Cosine similarity matrix of cats.png`               | Heatmap of cosine similarity between image and prompt embeddings |
| `The probability diagrams of 10 cat images.png`      | Bar charts of probability for each image against all 10 prompts  |

---

## 📊 Final Visualizations

### 🔷 Cosine Similarity Matrix

![Cosine Similarity Matrix](./Cosine%20similarity%20matrix%20of%20cats.png)

---

### 🔷 Probability Diagrams

![Probability Diagrams](./The%20probability%20diagrams%20of%2010%20cat%20images.png)

---

## 🔧 Tools Used

* Python (Colab)
* OpenAI CLIP model from `openai/CLIP`
* NumPy, Matplotlib, PIL

---

## 📈 Key Concepts

* **Zero-shot learning**: Classify images using text prompts without fine-tuning
* **Cosine similarity**: Metric to measure alignment between image and text embeddings
* **Multimodal AI**: Linking visual and textual data into one semantic space

---

## 📎 How to Run

You can run the notebook directly via Google Colab:

* Upload your own COCO cat images and write new prompts
* Adjust the similarity thresholds or prompt length
* Re-run the cosine matrix and plot generation sections

---

## 👩‍💻 Author

**Ranran Hu**
M.S. Computer Science – University of Massachusetts Dartmouth
GitHub: [RanranHu168](https://github.com/RanranHu168)

> This project demonstrates my ability to apply foundational multimodal models (like CLIP) to custom datasets for image classification, similarity search, and semantic reasoning.
