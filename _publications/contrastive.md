---
title: "Semi-Supervised Contrastive Learning with Decomposition-based Data Augmentation for Time Series Classification"
collection: publications
category: inter_journal
permalink: /publication/contrastive
date: 2024-05-30
venue: 'Intelligent Data Analysis'
excerpt: ''
paperurl: 'https://content.iospress.com/articles/intelligent-data-analysis/ida240002'
citation: 'Kim, D., Cho, S., Chae, H., Park, J., & Huh, J.* (2024), Semi-Supervised Contrastive Learning with Decomposition-based Data Augmentation for Time Series Classification, to Appear in Intelligent Data Analysis. (SCIE)'
---

While time series data are prevalent across diverse sectors, data labeling process still remains resource-intensive. This results in a scarcity of labeled data for deep learning, emphasizing the importance of semi-supervised learning techniques. Applying semi-supervised learning to time series data presents unique challenges due to its inherent temporal complexities. Efficient contrastive learning for time series requires specialized methods, particularly in the development of tailored data augmentation techniques. In this paper, we propose a single-step, semi-supervised contrastive learning framework named nearest neighbor contrastive learning for time series (\NNCLR). Specifically, the proposed framework incorporates a support set to store representations including their label information, enabling a pseudo-labeling of the unlabeled data based on nearby samples in the latent space. Moreover, our framework presents a novel data augmentation method, which selectively augments only the trend component of the data, effectively preserving their inherent periodic properties and facilitating effective training. For training, we introduce a novel contrastive loss that utilizes the nearest neighbors of augmented data for positive and negative representations. By employing our framework, we unlock the ability to attain high-quality embeddings and achieve remarkable performance in downstream classification tasks, tailored explicitly for time series. Experimental results demonstrate that our method outperforms the state-of-the-art approaches across various benchmarks, validating the effectiveness of our proposed method.
