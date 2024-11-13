# Swin Transformer Explained

<div align="center">

![Swin Transformer Banner](/assets/images/image.webp)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org/)

</div>

## 📚 About The Project

This repository provides a comprehensive exploration of the Swin Transformer architecture, developed as part of a Deep Learning course project. Our goal is to help others understand this powerful architecture through detailed explanations, visualizations, and practical implementations.

### What is Swin Transformer?

Swin Transformer is a hierarchical vision transformer that uses shifted windows for efficient modeling of visual data. It addresses key limitations of previous vision transformers by:
- Computing self-attention within local windows
- Supporting hierarchical feature maps
- Achieving linear computational complexity relative to image size

## 🎯 Project Structure

```
swin-transformer-explained/
├── docs/                   # Documentation and tutorials
├── src/                    # Source code implementation
├── demos/                  # Interactive demonstrations
├── presentation/          # Presentation materials
└── notebooks/            # Jupyter notebooks for examples
```

## 🚀 Getting Started

### Prerequisites

```bash
python>=3.8
pytorch>=2.0
```

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/swin-transformer-explained.git
cd swin-transformer-explained
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

## 💡 Key Features

- **Theoretical Understanding**
  - Detailed explanation of architecture
  - Mathematical foundations
  - Visual guides and diagrams

- **Implementation**
  - Step-by-step code walkthrough
  - Practical examples
  - Performance optimization tips

- **Demonstrations**
  - Interactive visualizations
  - Real-world applications
  - Performance benchmarks

## 📊 Documentation

For detailed documentation, please visit our [docs](/documentation) directory:

- [Architecture Overview](documentation/architecture.md)
- [Understanding Swin Transformer](documentation/understanding_swin_transformer.md)
- [Demo Tutorial](demo)(https://colab.research.google.com/drive/1DqpJVw0Fe2IlTx0gvcrLE_m6SjssqT4Q?usp=sharing)


## 👥 Team

**Team: Optical Flow**
- Jinghan Gao - [GitHub Profile](https://github.com/jinghgao)
- Calvin Lo - [GitHub Profile](https://github.com/lo-calvin)
- Xinyi Wang - [GitHub Profile](https://github.com/thisissophiawang)

## 📝 Course Information

This project was developed as part of the Computer Vision course at Northeastern University.

## 🔎 References

1. [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)
2. [Official Swin Transformer Implementation](https://github.com/microsoft/Swin-Transformer)

## 📖 Citation

If you find this project helpful, please consider citing:

```bibtex
@techreport{optical_flow_team2024,
    title={Understanding Swin Transformer: A Comprehensive Study},
    author={{Optical Flow Team (Gao, Jinghan and Lo, Calvin and Wang, Xinyi)}},
    institution={University of British Columbia},
    type={Course Project},
    year={2024},
    note={Deep Learning Course Project}
}
```

This project is a comprehensive explanation and implementation of the Swin Transformer architecture, created by Team Optical Flow:
- Jinghan Gao
- Calvin Lo
- Xinyi Wang

For academic use, please ensure to cite both the original work and our educational materials appropriately.
}
```


## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions and feedback, please open an issue in this repository or contact team members directly.

## 🙏 Acknowledgments

- [Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/) for the original Swin Transformer
- [Our course instructor] for guidance and support
- The PyTorch team for their excellent framework

---

Made with ❤️ by Team Optical Flow
</div>
