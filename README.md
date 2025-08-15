# 🧠🎨 Face Generation with GANs (TensorFlow/Keras)

Generate **synthetic face images** using a **Generative Adversarial Network (GAN)** trained on the **CelebA** dataset (resized to 32×32).  
This repo includes:
- A **Discriminator** for real-vs-fake classification
- A **Generator** that maps latent noise → images
- A simple **training loop** with periodic sample saving

> Built with TensorFlow/Keras, tested on CelebA (`img_align_celeba`) and 32×32 RGB images.

---

## ✨ Project Highlights
- Loads images via `image_dataset_from_directory` (label-free, batched)
- Normalizes inputs to `[0, 1]` and trains at **32×32** (fast iteration)
- Custom **DCGAN-style** architectures
- Manual training loop with **on-the-fly sample image saving**

---

## 📁 Dataset
- **CelebA** aligned & cropped images (folder: `img_align_celeba/`)
- Directory structure expected:

- Images are resized to **32×32** during loading.

> ⚠️ Make sure you have the dataset locally. CelebA requires accepting the dataset license from the provider.

---




---



🧯 Ethics & Use

Generated faces must respect dataset licenses and privacy.

Do not use synthetic faces for impersonation or deceitful activity.

Clearly label generated imagery in demos and publications.


---
📜 License

MIT — feel free to use, modify, and share.
If you build on this, a citation or star ⭐ is always appreciated!


---
Author

SANIYA CHHABRA
