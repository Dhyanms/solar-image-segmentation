# 🌞 Solar Image Segmentation Using Deep Learning 🤖

## Project Overview
This project uses **deep learning** to automatically segment **solar images** and detect key features like **sunspots** 🌑, **solar flares** 🔥, and other solar phenomena. Using high-resolution images from **NASA’s Solar Dynamics Observatory (SDO)** 🚀, the aim is to accelerate the analysis of solar events, helping predict space weather and contributing to scientific research! 🌍

---

## Technologies Used
- **Deep Learning Framework**: TensorFlow, Keras 🧠  
- **Programming Language**: Python 🐍  
- **Libraries**:  
   - OpenCV (for image processing) 🖼️  
   - NumPy (for numerical operations) 🔢  
   - Matplotlib (for plotting) 📊

---

## Dataset
This project uses a custom dataset of **400 high-resolution solar images** 🌞, sourced from NASA's SDO. The images were preprocessed and manually annotated with segmentation masks for **sunspots** 🌑 and **solar flares** 🔥. The dataset was enhanced with data augmentation techniques like **flips**, **rotations**, and **zooming** for improved model training. 📸

---

## Model Architecture
The model is an **autoencoder neural network**, designed to compress and reconstruct images while preserving important spatial features 🌐. The **encoder** reduces the image to a latent space, and the **decoder** reconstructs the image into its segmented form. This architecture is perfect for the task, enabling precise segmentation with minimal loss. ⚡

---

## Training & Evaluation
We trained the model using **Binary Cross-Entropy** loss and evaluated it with the **Dice Coefficient**, ensuring the segmented output closely matches the actual features. The model successfully segments key solar features with high accuracy! 🚀

---

## Steps to Run the Project  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/solar-image-segmentation.git
   cd solar-image-segmentation
   ```
2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```
3. **Train the Model**
    run the .ipynb file 

## Results
The model accurately segments **sunspots** 🌑 and **solar flares**🔥, creating clear and useful boundaries. This segmentation provides valuable insights for studying solar activity and enhances our understanding of space weather! 🌌

## Future Directions 
- Expand the dataset to include real-time solar images 🕒 for better performance.
- Experiment with more advanced architectures like U-Net++ or Vision Transformers for improved segmentation accuracy! 🏆
- Deploy a real-time segmentation system for continuous monitoring of solar events! 🌍

## Contributing 
We welcome contributions to improve this project! Fork the repo, make your changes, and submit a pull request to help improve solar image segmentation! 🌱

## Contact 
Feel free to reach out if you have any questions, ideas, or just want to chat about solar activity! 🌞
- Email: dhyanms@gmail.com & kashishvarmaa@gmail.com 📧
- GitHub:  https://github.com/Dhyanms & https://github.com/Kashishvarmaa 🖥️
