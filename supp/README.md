# Deep Video Generation, Prediction and Completion of Human Action Sequences
Supplementary Material

## Getting Started

Here are some instructions for viewing our supplementary material on a webpage

### Prerequisites

```
Stable Network Connection
```
```
A Modern Browser (e.g. Edge, Chrome, Firefox)
```

### Running
Just double click on ```index.html``` to open up and you can start reviewing the supplementary!

An alternative is to visit an [anoymous site](https://iamacewhite.github.io/supp/index.html) for a deployed version.

### Appendix
In case you need to refer to the original files for some reason, here are a few instructions.

All our results are in ```qua_res/```

.  
+-- qua_res  
|   +-- comp_input: input for video completion (first and last frame)  
|   +-- comp_input_pose: input pose for video completion  
|   +-- gt: real data for your reference  
|   +-- msgan: video prediction results from Multi-Scale GAN [20]  
|   +-- ours_comp: Our results for video completion  
|   +-- ours_comp_pose: Our pose sequence results for video completion  
|   +-- ours_gen: Our results for video generation  
|   +-- ours_gen_pose: Our pose sequence results for video generation  
|   +-- ours_pred: Our results for video prediction  
|   +-- ours_pred_pose: Our pose sequence results for video prediction  
|   +-- pred_input: input for video prediction (first 4 frames)  
|   +-- pred_input_pose: input pose for video prediction  
|   +-- prednet: video prediction results from PredNet [18]  
|   +-- tpk: video prediction results from PoseVAE [37]  
|   +-- vgan: video generation results from Video-GAN [35]  
|   +-- vgan_comp: video completion results from Conditional Video-GAN [35]  
