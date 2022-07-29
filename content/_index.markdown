---
title: Home
---

[<img src="https://simpleicons.org/icons/github.svg" style="max-width:15%;min-width:40px;float:right;" alt="Github repo" />](https://github.com/yihui/hugo-xmin)

# Raclette 1 Project

## Abstract
#### Using CNN/CAM to differentiate finger flexion movements 

ECoG-based human motion prediction aims to predict future motion frames to guide various brain-computer interaction tasks. Most of the previous work has focused on solving this time series prediction task using RNN-based frameworks. However, RNN-based frameworks suffer from low spatial resolution problems, which means they can only utilize and provide little information about the spatial location of the electrodes and interactions between the brain areas where the electrodes are implanted in. Based on the fingerflex datasets (*Miller et al., 2009, 2012*) here, we propose a CNN-based prediction framework that not only shows promise in differentiating finger flexion movements, but also provides weighted spatial and functional information of electrodes that may account for the movement differences. Specifically, we use the 3-D format ECoG data as the input of the CNN model. Then, by performing Class Activation Mapping (CAM), we can get a weighted average of the feature maps in the last convolutional layer, from which we can localize which electrodes the model is focusing on based on the current fingerflex task. This can provide important information for neural computing, neurophysiological surgery, and neural circuit analysis.
#### Correlating the attention levels and correctness of responses
Visuospatial attention prioritizes the processing of visual inputs. According to previous research (*Benoni & Tsal, 2010*), there is a high possibility that the wrong response is caused by low attention levels or large attentional variations. In the ECoG-fingerflex dataset by *Miller, et al. (2009)*, we noticed that participants sometimes flex different fingers from what the cue on the screen asked.  Based on the wrong response subsets in the dataset, we assume that there is some modulation or switch in the attention state. Spectral-spatial patterns in dataset intersections’ across overlapping brain regions may pinpoint regions related to the finger-flexion preparation and execution. An investigation of the participants' response time is fairly standard in the study of attention, which helps visualize patterns, discrepancies, and trade-offs in accuracy discreetly. Additionally, attention could also be characterized by the spatial-temporal dynamics of the alpha oscillation (8-14Hz). The increase in alpha activity has been associated with a loss in attentional load. Meanwhile, it is believed that synchronization between frontal and parietal areas acts as a general mechanism for the detection of attention levels. We use the response time (RT), alpha-band activity and the synchronization between frontal and parietal areas as the criteria for the correlation between the attentional level and correct/wrong response. 
## Results 
## Discussion
## Key References
## The Final Presentation
<!-- in this way you could embed a google slide -->
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ0kKJB_M_bQMyuAQMtbWsVwZMUk0nbnsgRSf3-B3gWh_sPxFId-fI7mWnKUdkwBmQB36UXy_Z4tq92/embed?start=false&loop=false&delayms=30000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>



Although it is a minimal theme, it is actually fully functional. It supports pages (including the home page), blog posts, a navigation menu, categories, tags, and RSS. With [a little bit customization](https://github.com/yihui/hugo-xmin/blob/master/exampleSite/layouts/partials/foot_custom.html), it can easily support LaTeX math expressions, e.g.,

<!-- in this way you could insert a video -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9RRQtNnq3s0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



All pages not under the root directory of the website are listed below. You can also visit the list page of a single section, e.g., [posts](/post/), or [notes](/note/). See the [About](/about/) page for the usage of this theme.
