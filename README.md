# Noisy-character-image-benchmark

Character image restoration, as a broad research topic, whose datasets contain diverse benchmarks, e.g., real-world/synthetic noise, handwriting/scan, and character/document. Although recent studies gradually focus on restoring real-world noise, there are still lacking available datasets for evaluation. Well-known public accessible datasets, like denoising-dirty-documents {https://www.kaggle.com/c/denoising-dirty-documents/data}, estimate real-world noisy character images by simply adding synthetic noise to existing character images. Such datasets are obviously not satisfactory to our need for evaluation. Therefore, we introduce a new dataset of real-world degraded character images.

We build a real-world degraded character image dataset by selecting from the historical Chinese character and oracle document datasets. The reason for selecting such images is that most of them have complex real-world degradation modelled by. The dataset includes training and testing sets consisting of noisy-clean character image pairs. Need to notice clean character images are binarized and are manually produced by several philologists. 

Where:
- train-LV1-denoise: The benchmark for charater image denoising, where includes real-world noise. We produce these images by removing noise from the original character images.
- train-LV2-repair: The benchmark for charater image restoration, where includes real-world noise. We produce these images by removing noise from the original character images, and also repair the broken charatcers. 
- test: data for testing purpose. 
