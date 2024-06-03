# DeCoF: Generated Video Detection via Frame Consistency
## News 🚀
**[2024/1/31]** Comming soon.    
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
<img src="/pics/data_distribution.png" width=40%>
</p>

## DeCoF.

<p align="center">
<img src="/pics/model-1_1.png" width=80%>
</p>
