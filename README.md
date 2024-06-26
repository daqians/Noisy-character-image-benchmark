# Noisy-character-image-benchmark


We build a real-world degraded character image dataset by selecting from the historical Chinese character and oracle document datasets. The reason for selecting such images is that most of them contain complex real-world degradation. The dataset includes training and testing sets consisting of noisy-clean character image pairs. 

Link：https://drive.google.com/drive/folders/1gnlmmxQDJOl4wR2ITiBvnaQRN4nZc3rP?usp=sharing

Where:
- denoise: The benchmark for character image denoising, which includes real-world noise. We produce these images by removing noise from the original character images.
- restore: The benchmark for character image restoration, which includes real-world noise. We produce these images by removing noise from the original character images and also repairing the broken characters.
- gray: The benchmark for character image denoising, which includes real-world noise with a gray background. We produce these images by removing noise from the original character images. 
- test: data for testing purposes. 


For any kind of use of these datasets, please cite the following:
  
@inproceedings{shi2022rcrn,  
  title={RCRN: Real-world character image restoration network via skeleton extraction},  
  author={Shi, Daqian and Diao, Xiaolei and Tang, Hao and Li, Xiaomin and Xing, Hao and Xu, Hao},  
  booktitle={Proceedings of the 30th ACM International Conference on Multimedia},  
  pages={1177--1185},  
  year={2022}  
}  
