# Unblur-SLAM: Dense Neural SLAM for Blurry Inputs 

<img width="1888" height="461" alt="blur_teaser_3D" src="https://github.com/user-attachments/assets/f3601d21-4ddd-4443-8be8-10f775126c96" />

Welcome to the official repository for **Unblur-SLAM**, a novel RGB SLAM pipeline designed for sharp 3D reconstruction from blurred image inputs. 

## 📖 Overview
<img width="700" height="266" alt="unblur-slam-overview" src="https://github.com/user-attachments/assets/663d569b-5269-4e7d-b488-709e16c2b130" />


In contrast to previous work, Unblur-SLAM is capable of handling different types of blur and demonstrates state-of-the-art performance in the presence of both motion blur and defocus blur. 

Our system intelligently adjusts its computational effort based on the amount of blur detected in the input image. By treating sharp and blurry frames separately and skipping costly refinements for sharp frames, it avoids the significant slowdowns typical of previous blur-aware SLAM approaches.

## 🚀 Release Plan
The codebase is currently undergoing further refinement and cleanup to ensure it is robust and easy to use. We are fully committed to open-sourcing our work and will release the assets according to the following schedule:

### TODO List
- [ ] **Phase 1:** Open-source the pre-trained model weights and the curated datasets.
- [ ] **Phase 2:** Open-source the complete Unblur-SLAM codebase.

Please star or watch this repository to stay updated on our progress!

## 📝 Citation
[cite_start]If you find our work or datasets helpful in your research, please consider citing our paper:

```bibtex
@inproceedings{unblur_slam_2026,
  title={Unblur-SLAM: Dense Neural SLAM for Blurry Inputs},
  author={Qi Zhang, Denis Rozumny, Francesco Girlanda, Sezer Karaoglu, Marc Pollefeys, Theo Gevers, Martin R. Oswald},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}
