---
layout: default
title: Methodology
---
# Methodology

## Item-Item Collaborative Filtering
Initially, our approach centered on implementing an item-item Collaborative Filtering (CF) model utilizing the Pearson correlation coefficient. This involved looking at similarities between items based on user interactions, where the Pearson coefficient measured the linear correlation between item ratings by different users. We calculated the similarity matrix for items, leveraging the Pearson coefficient to recommend poems similar to those previously liked by a user. However, we encountered challenges in handling sparsity within the dataset and the inability of the Pearson coefficient to capture complex nonlinear relationships between poems. This method struggled with scalability and failed to offer personalized recommendations that accounted for stuble user preferences beyond direct item associations. Additionally, using this strategy, we could only utilize some of the dataset as we ran out of memory and could only do subsets of the dataset.

## Neural Collaborative Filtering
Recognizing the limitations of the item-item CF approach, we pivoted towards a Neural Collaborative Filtering (CF) model for enhanced performance and personalized recommendations in our poetry recommendation tool. Transitioning to a neural approach enabled us to leverage the power of deep learning to capture intricate patterns in user-poem interactions. Our model could recognize nonlinear relationships and semantic nuances within the poetry dataset by embedding poems and users into latent spaces and employing neural networks. Therefore, we could provide more accurate and personalized recommendations. This shift in strategy empowered the tool to learn hidden representations of poems and user preferences, overcoming the constraints faced earlier with the traditional CF method based on Pearson correlation.
