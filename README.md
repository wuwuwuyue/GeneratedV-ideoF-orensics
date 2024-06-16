# DeCoF: Generated Video Detection via Frame Consistency
![Overview](pics/model-1_1.png)  
## News 🚀
**[2024/1/31]**  Comming soon.    

**[2024/6/7]**  The prompts used for generating videos, the attribute partitioning involved in prompts, and the partitioning of the dataset validation set, test set, and training set have been open-source. You can access it in the `/datas/` folder. Unfortunately, we are unable to directly provide real videos. You can download them from the original dataset based on the video_id of prompts.  

**[2024/6/16]**  All generated videos can be downloaded from [here] (https://pan.baidu.com/s/1j725GWEB2lsGtuUy4Rvl3g?pwd=ptr8) (ptr8), The emergence speed of video generation models far exceeds our imagination. If you expand a subset based on our dataset, we sincerely invite you to release the corresponding generated videos.


## Abstract
> The escalating quality of video generated by advanced video generation methods results in new security challenges, while there have been few relevant research efforts: 1) There is no open-source dataset for generated video detection, 2) No generated video detection method has been proposed so far.
To this end, we propose an open-source dataset and a detection method for generated video for the first time. 
First, we propose a scalable dataset consisting of 964 prompts, covering various forgery targets, scenes, behaviors, and actions, as well as various generation models with different architectures and generation methods, including the most popular commercial models like OpenAI's Sora and Google's Veo.
Second, we found via probing experiments that spatial artifact-based detectors lack generalizability. Hence, we propose a simple yet effective detection model based on frame consistency (DeCoF), which focuses on temporal artifacts by eliminating the impact of spatial artifacts during feature learning.

<p align="center">
<img src="pics/figure1_1.jpg" width=60%>
</p>

## Overview
- **[GeneratedVideoForensics (GVF) dataset.]**
- **[DeCoF.]**
## GeneratedVideoForensics (GVF) dataset.

<p align="center">
<img src="/pics/data_distribution.png" width=50%>
</p>

## DeCoF.

<p align="center">
<img src="/pics/model-1_1.png" width=80%>
</p>
