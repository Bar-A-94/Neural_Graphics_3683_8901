<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=180&section=header&text=Neural%20Graphics&fontSize=40&fontColor=ffffff&fontAlignY=36&animation=fadeIn&desc=Training%20a%20diffusion%20model%20from%20scratch&descSize=15&descAlignY=58" width="100%" />

**Neural Graphics · Tel Aviv University**<br/><sub>Instructor: Or Patashnik</sub>

<img src="https://img.shields.io/badge/%F0%9F%8E%93%20Tel%20Aviv%20University-30363d?style=for-the-badge" />
<img src="https://img.shields.io/badge/Term-2024/25%20B-30363d?style=for-the-badge" />
<img src="https://img.shields.io/badge/Python-30363d?style=for-the-badge&logo=python&logoColor=FFD43B" />
<img src="https://img.shields.io/badge/PyTorch-30363d?style=for-the-badge&logo=pytorch&logoColor=EE4C2C" />
<img src="https://img.shields.io/badge/Jupyter-30363d?style=for-the-badge&logo=jupyter&logoColor=F37626" />

</div>

<br/>

> [!NOTE]
> My solution to the Neural Graphics assignment: building and training my own diffusion model, first unconditional, then class-conditioned with classifier-free guidance.

## 🎨 Assignment 1: Train your own diffusion model

| | Part | What I built |
|:-:|---|---|
| 🧱 | **Basic ops and UNet blocks** | The building blocks of the denoiser |
| 🌫️ | **Unconditional diffusion** | UNet architecture · DDPM forward and reverse process · training the denoiser |
| 🎯 | **Class-conditioned diffusion with CFG** | Class conditioning in the UNet · DDPM with classifier-free guidance · training · experimenting with different guidance scales |

📓 **[Solution notebook](solution/Assignment1_Neural_Graphics.ipynb)** · 📄 **[Write-up](solution/writeup.pdf)**

## 🗂️ Structure

```
Neural_Graphics_3683_8901/
├── supplied_files/
│   ├── Assignment1_Neural_Graphics.ipynb   # starter notebook
│   └── NeuralGraphocsEx1.pdf               # assignment
└── solution/
    ├── Assignment1_Neural_Graphics.ipynb   # my solution
    └── writeup.pdf                         # my report
```

## 🙏 Acknowledgments

Thanks to **Or Patashnik** for a great course.

> [!IMPORTANT]
> These are my personal solutions, shared for learning purposes. If you are currently taking this course, please follow its academic integrity guidelines.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" />
