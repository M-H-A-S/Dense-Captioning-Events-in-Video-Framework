# Dense-Captioning-Events-in-Video-Framework
Efficient Framework Architecture for Dense-Captioning Events in Video using Effective Multi-modal Features Extractor and Event Proposals Generator.


# Abstract

One of the most challenging tasks in the field of computer vision is the dense video captioning task. Dense Video Captioning is a way of epitomizing the video’s content, events, objects, and motions into sensible texts. Simply, the task is divided into three main tasks. The first task is to extract important and strong features from the videos such as visual, motion, semantic and audio features. The second task is to generate reasonable event proposals in which the start time and end time for each event in the video. The third task is to produce a coherent and consistent caption for each event.

In the early stages, the researchers in this area used the traditional template-based methods such as Subject, Verb, Object (SVO-based methods). Since these methods are totally dependent on pre-defined templates, the outcome was incredibly subpar and it was unable to persist for very long. 

In contrast, in recent years, and with the advancement of the deep learning techniques, deep learning has a significant impact in solving this problem. However, the vast majority of the existing approaches mostly focus on visual content, and they are ignoring the audio signals entirely. Only a few works used both modalities, but those works either produced subpar findings or failed to emphasize the significance of a dataset with a particular domain. 

To address the dense captioning events in videos problem, I propose efficient framework architecture for dense-captioning events. The framework utilized both modalities RGB, optical flow and audio. As well as the architecture is utilized the best event proposals generator so far in the literature (Dense Boundary Generation). Also, I propose best pre-training strategies for the features extraction task such as TSN, C3D, I3D, R (2+1) D, S3D. In addition, I build captions forsix languages for each video proposals tag which is generated from DBG [3]. The languages are Arabic, Chinese, French, German, Italian, and Spanish. 

To validate the proposed framework, substantial experiments are carried out on the ActivityNet dataset and Youcook2, and the framework clearly outperforms state-of-the-art methods. The evaluation done for proposals generation models using Re-call and Precision. The evaluation of captioning done using mainly the METEOR metric. Interestingly, on the official ActivityNet Caption and Youcook2, the framework achieved new record on the validation dataset which are 99% recall and 99% precision across tIOU. Also, the framework achieved 11.57 for METEOR score.
