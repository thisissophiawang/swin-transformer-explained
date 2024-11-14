# Swin Transformer Explained

<div align="center">

![Swin Transformer Banner](/assets/images/image.webp)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.0+-ee4c2c.svg)](https://pytorch.org/)

</div>

## 📚 About The Project

This repository provides a comprehensive exploration of the Swin Transformer architecture, developed as part of a Deep Learning course project. Our goal is to help others understand this powerful architecture through detailed explanations, visualizations, and practical implementations.


## 👥 Team

**Team: Optical Flow**
- Jinghan Gao - [GitHub Profile](https://github.com/jinghgao)
- Calvin Lo - [GitHub Profile](https://github.com/lo-calvin)
- Xinyi Wang - [GitHub Profile](https://github.com/thisissophiawang)


## What is Swin Transformer?

Swin Transformer is a hierarchical vision transformer that uses shifted windows for efficient modeling of visual data. It addresses key limitations of previous vision transformers by:
- Computing self-attention within local windows
- Supporting hierarchical feature maps
- Achieving linear computational complexity relative to image size

## 🎯 Project Structure

```
swin-transformer-explained/
├── docs/                   # Documentation and tutorials
├── model/                    # swim transformer model code 
├── demos/                  # Interactive demonstrations
├── presentation/          # Presentation materials
└── notebooks/            # Jupyter notebooks for examples
```

## 📊 Documentation

For detailed documentation, please visit our [docs](/documentation) directory:

- [Architecture Overview](documentation/architecture.md)
- [Understanding Swin Transformer](documentation/understanding_swin_transformer.md)
- Demo Tutorial(https://colab.research.google.com/drive/1DqpJVw0Fe2IlTx0gvcrLE_m6SjssqT4Q?usp=sharing)
- Presentation
- [**Related File**](docs/related_file.md): Additional documentation or configurations related to the project.




## 💡 Key Features

- **Theoretical Understanding**
  - Detailed explanation of architecture
  - Visual guides and diagrams

- **Implementation**
  - Step-by-step code walkthrough
  - Practical examples in Demo

- **Demonstrations**
  - Interactive visualizations
  - Real-world applications
  - Performance benchmarks


    
## 🚀 Swin Transformer Performance on COCO Dataset

The following chart illustrates the state-of-the-art performance of Swin Transformer and its variants (such as SwinV2-G) on the COCO test-dev dataset. The chart shows how Swin Transformer models consistently achieve high `box mAP` scores, outperforming other object detection models across different time periods.

![Swin Transformer COCO Performance](assets/images/chart.png)

- **Swin-L (HTC++, multi scale)**: Achieves a box mAP of around 60.
- **Soft Teacher + Swin-L (HTC++, multi scale)**: Further improves the box mAP to approximately 62.
- **SwinV2-G (HTC++)**: Sets a new benchmark with a box mAP of around 64.

This showcases the effectiveness of the Swin Transformer and SwinV2 models in object detection tasks, demonstrating their superior performance on high-resolution images and dense prediction tasks.

_Source: [COCO Object Detection Leaderboard](https://paperswithcode.com/sota/object-detection-on-coco)_



## 📝 Course Information

This project was developed as part of the Computer Vision course at Northeastern University.

## 🔎 References

1. [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)
2. [Official Swin Transformer Implementation](https://github.com/microsoft/Swin-Transformer)
3. [COCO Object Detection Leaderboard](https://paperswithcode.com/sota/object-detection-on-coco)_

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
