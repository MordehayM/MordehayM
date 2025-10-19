[![LinkedIn][linkedin-shield]][linkedin-url]


## Hi there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">, I am Mordehay

I hold both a **Bachelor's and Master's degree in Electrical Engineering** with a specialization in **Data and Information Processing** from **Bar-Ilan University**.

🎓 My M.Sc. thesis, conducted under the supervision of **Prof. Sharon Gannot**, focused on **speaker separation** using deep learning methods. This work led to a published paper and an open-source implementation:

## 📚 Publications
### 📝 1.*"Sep-TFAnet-VAD: Joint Voice Activity Detection and Speaker Separation in Reverberant and Noisy Conditions"*,  
  [EURASIP Journal on Audio, Speech, and Music Processing (2025)](https://asmp-eurasipjournals.springeropen.com/articles/10.1186/s13636-025-00404-7)  
  > The increasing complexity of real-world environments, where multiple speakers may converse simultaneously, underscores the importance of effective speech separation.  
  > This paper presents **Sep-TFAnet**, a single-microphone speaker separation network based on time-frequency attention, optimized for noisy and reverberant conditions.  
  > A variant, **Sep-TFAnetVAD**, jointly integrates a voice activity detector (VAD).  
  > The model uses STFT/iSTFT in place of learned encoders and supports low-latency block processing, making it suitable for **human-robot interaction**.  
  > We also introduce [**ARImulti-mic**](https://ieee-dataport.org/documents/arimulti-mic-real-world-speech-recordings-humanoid-robot-ari), a real-world dataset recorded using a humanoid robot. [Project page](https://Sep-TFAnet.github.io)

- 💻 [GitHub Repository: Sep-TFAnet-VAD](https://github.com/MordehayM/Sep-TFAnet-VAD.git)

---
 ### 📝 2. *"A Visual Explanation Approach for Regression Neural Networks Applied to Nearfield Acoustic Holography"*,  
  [IEEE (2023)](https://ieeexplore.ieee.org/document/10097272)  
🧠 I also co-authored a publication addressing interpretability in deep learning for regression tasks:
  > We propose a **Grad-CAM-inspired** approach to interpret neural network decisions for regression models.  
  > The method is applied to **Kirchhoff-Helmholtz-based CNN (KHCNN)** for Nearfield Acoustic Holography using vibrating plates and violin top plates.  
  > Results reveal the most informative regions used by the network for accurate predictions, and the method is validated using NCC and NMSE metrics.
---
### 📝 3.🎧 *"Transient Noise Removal via Diffusion-based Speech Inpainting (2025)"*,
[Link](https://arxiv.org/abs/2508.08890)  


> Real-world audio recordings often contain **transient, non-stationary noises** such as keyboard clicks, door knocks, or coughs, which are particularly challenging for traditional denoising methods.  
> In this work, we introduce **PGDI**, a novel **diffusion-based speech inpainting framework** that reconstructs missing or corrupted speech segments by leveraging the generative power of diffusion models.  
> PGDI progressively **denoises and reconstructs missing segments**, ensuring smooth transitions and high-fidelity synthesis. The process is further **guided by text-based information** extracted using a language model, improving reconstruction accuracy and naturalness.

✨ **Highlights**:
-  **Progressive denoising** enables smooth and natural reconstruction of both short and long gaps.  
-  **Text guidance** enhances performance for long missing segments, while the model remains effective even without text for short gaps.  
-  **Speaker-independent** — no prior knowledge of the speaker is required.  
-  **Voice, style, and prosody preservation**, ensuring realistic and natural-sounding speech.  
-  **Environmental consistency**, maintaining reverberation and acoustic characteristics.  
-  Strong performance on **abrupt, high-energy noise** scenarios such as knocks and coughs.

> We evaluate PGDI with and without access to the ground-truth transcript during inference and demonstrate that **text-guided PGDI excels in long-gap reconstruction**, while **unguided PGDI** remains robust for shorter gaps.




## Technologies
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![C](https://img.shields.io/badge/c-%2300599C.svg?style=for-the-badge&logo=c&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white)
[![Keras][Keras-shield]][Keras-url]
[![TensorFlow][TensorFlow-shield]][TensorFlow-url]
[![Pytorch][Pytorch-shield]][Pytorch-url]
[![Opencv][Opencv-shield]][Opencv-url]

[linkedin-shield]: https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url]: https://linkedin.com/in/mordehay-moradi
[Keras-shield]: https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white
[Keras-url]: https://keras.io/
[TensorFlow-shield]: https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white
[TensorFlow-url]: https://www.tensorflow.org/
[Pytorch-shield]: https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white
[Pytorch-url]: https://pytorch.org/
[Opencv-shield]: https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white
[Opencv-url]: https://opencv.org/
