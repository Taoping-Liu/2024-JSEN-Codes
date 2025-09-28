## Urinary bladder cancer screening with electronic noses based on few-shot contrastive representation learning and open-set recognition

> Authors: Yingying Jian#, Yunzhe Bi#, Jinhai Fan, Nan Zhang, Weitian Huang, Chan Li*, Weiwei Wu*, Taoping Liu*
>
> Publication date: 2025/1/1
>
> Published in: IEEE Sensors Journal (vol. 25, no. 1, pp. 125-134, Jan. 2025)
>
> DOI: 10.1109/JSEN.2024.3490841
> 
> Abstract: Deploying electronic noses (e-noses) in disease screening tasks in real-world environments is hindered by limited training samples and interference from other nontarget odor categories. To address these challenges, we propose a novel algorithmic framework based on few-shot learning and open-set recognition. First, discriminative and compact odor representations are learned via a contrastive representation learning algorithm under closed-set classification settings. At this stage, an autoencoder-based data hallucination algorithm is employed to augment samples of interest from its related gas samples to alleviate the sample size problem. Then, disease screening is realized by modifying the closed-set model with an open-set recognition algorithm. The proposed framework was evaluated for urinary bladder cancer (UBC) diagnosis. Experimental results demonstrated that the method, trained with only five UBC samples, achieved an F1 score of $0.8907 \pm 0.0158$, even in the presence of ten nontarget odor categories. The F1 scores obtained under three-shot learning and one-shot learning were $0.8393 \pm 0.0082$ and $0.7517 \pm 0.0132$, respectively. Moreover, clinical confounding factors had minimal impact on the result of open-set recognition. This framework shows good potential for applications requiring robust target odor recognition amidst nontarget odor interference.

Description: The codes employed in this study comprise Delta-encoder, ResNet, and OpenMax.
