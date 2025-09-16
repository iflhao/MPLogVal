# MPLog
MPLog is a multimodal panoptic dataset for intralogistics, collected from two warehouses using synchronized LiDAR and RGB camera data. 
We release some examples from the 2D and 3D validation splits for double-blind review purposes. The full dataset will be made publicly available after the review period concludes.

# Data Format
## 2D Data
Our data for 2D panoptic segmentaion are saved in COCO-format.
## 3D Data
Each fused 3D point cloud is saved as an array named labeled_pc_{area_num}_{index}.npy. Each point has six dimensions for x, y, z, intensity, class ID, and instance ID.
