# Supplementary
### Effect of Anchor Point Distance Encoding
We compare the effect of our proposed anchor point distance encoding to that of the relative distance encoding used by Geom. Tr.[[1]](#1)
|Method|Rot. Mean|Rot. Med|Tr. Mean|Tr. Med|
|-----|-----|------|------|------|
|Ours w/Relative Distance Encoding From Geom. Tr.[1]|X|X|X|X|
|Ours w/Anchor Point Distance Encoding |X|X|X|X|

### Error Metrics
The error metrics for rotation and translation errors are: 

$R_{err} = arccos(\frac{Tr(R_{pr}R_{gt}^T)-1}{2})$ and $t_{err} = ||t_{pr}-t_{gt}||^2_2$


$R_{pr}$ and $R_{gt}$ are the predicted and ground-truth rotations. Likewise, $t_{pr}$ and $t_{gt}$ are the predicted and ground-truth translations. 


## References
<a id="1">[1]</a> 
Qin, Zheng, et al. "Geometric transformer for fast and robust point cloud registration." 
Proceedings of the IEEE/CVF conference on computer vision and pattern recognition. 2022.
