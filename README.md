# SFMS
Salient Features and Multi-granularity Splitting model

Due to differences in background, lighting, poses, and camera resolutions among images captured by different cameras, coupled with incomplete appearance features, matching identities of occluded pedestrians across multiple camera views poses a challenging, long-term task. However, existing efforts primarily focus on discovering localized parts with simple feature representations, then concatenating them as global features. We found that features obtained in this manner contribute minimally to overall performance. To alleviate this issue, this study explores person re-identification(ReID) with salient features and multi-granularity splitting. We propose a model for salient features extraction and multi-granularity splitting to optimize the extraction of both local and global features for improved recognition. In our model, local features are obtained through horizontal split, while global features are extracted through multi-level deep extraction. Thus, we devise a novel network architecture and related modules, demonstrating outstanding performance across multiple mainstream ReID datasets.
Specifically, our method after re-ranking gets 96.0% mAP score and 97.2% rank-1 accuracy on Market1501, which delivers remarkable performance gains over previous state-of-the-art person re-identification models.
In addition, we also exhibited outstanding performance on both DukeMTMC-reID and CUHK03. 
To further validate the robustness of our approach, we explore the application of our method in the occluded person re-identification problem, and obtain 57.5%/66.2% mAP/rank-1 on Occluded-DukeMTMC.  This resualt underperforms the state-of-the-art method FED by 1.9%  rank-1 accuracy but outperforms it by 1.1% mAP.

![Image text](https://github.com/witbase/SFMS/blob/main/exp20231222A.jpg)
![Image text](https://github.com/witbase/SFMS/blob/main/exp20231222B.jpg)
![Image text](https://github.com/witbase/SFMS/blob/main/exp20231222C.jpg)
![Image text](https://github.com/witbase/SFMS/blob/main/exp20231222D.jpg)
