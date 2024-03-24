# Enhancing Parameter-efficient Fine-tuning with Simple Calibration based on Stable Rank

This is the implementation of the paper:
> Peiyu Liu, Ze-Feng Gao, Xiao Zhang, Wayne Xin Zhao, Ji-Rong Wen. Enhancing Parameter-efficient Fine-tuning with Simple Calibration based on Stable Rank
*Updates*:

* [March 24] First init the project and the code is coming soon.

---
## Abstract
Despite the reduction in trainable parameters, existing lightweight fine-tuning methods are found to be effective in low-resource settings but often fail in high-resource settings, leading to unreliable outcomes. This limitation can be attributed to inflexible strategies: they identify the parameters of the model to be trained before fine-tuning and remain unchanged without taking into account the inherent variance of generalization ability in model components~(\emph{i.e.}, feed-forward, attention layers) and potential changes during the fine-tuning process.
In this paper, we introduce a simple but effective calibration for lightweight fine-tuning PLMs based on the matrix's stable rank according to both model components and the training process.
We proposed both theoretical analyses and experimental verification for the proposed calibration strategy.
Considering efficiency, we further propose time-aware and structure-aware strategies to determine the most crucial time to commence the fine-tuning procedure and selectively apply parameter matrices for lightweight fine-tuning, respectively.Extensive experiments demonstrate the superiority of our proposed fine-tuning approach ~(average improvement $3.1$ for GLUE score compared to lightweight fine-tuning method).

