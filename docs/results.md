---
layout: default
title: Results
---
# Results

## Performance Evaluation

| Method           | MSE  |
| ---------------  | ---- |
| Global Mean      | 4.42 |
| NCF (ReLu)       | 1.22 |
| NCF (Leaky ReLu) | 2.07 |

## Sample Predictions

Cold Start
![Cold Start Recommendations](https://raw.githubusercontent.com/megansin/poetry_pal/gh-pages/docs/rating%201.png "Cold Start Recommendations")


User with 3 Ratings
![3 Rating Recommendations](https://raw.githubusercontent.com/megansin/poetry_pal/gh-pages/docs/rating%202.png "3 Rating Recommendations")

User with 20 Ratings
![20 Rating Recommendations](https://raw.githubusercontent.com/megansin/poetry_pal/gh-pages/docs/rating%203.png "20 Rating Recommendations")

## Challenges and Limitations
Our original idea was to build a book recommendation tool. However, we challenges that shaped our project's evolution. The sheer volume of available books and user interactions posed a significant challenge, overwhelming our computing resources. The magnitude of this dataset exceeded the capabilities of our computing infrastructure, which hindered our ability to process and analyze the extensive book-to-user interactions effectively. Moreover, the sheer size and sparsity of the data made it impractical to load the information into a matrix format. This limitation significantly prevented us from using traditional matrix factorization or similarity-based methods that rely on the matrix representation of user-item interactions.

With these computational constraints and the inability to effectively manipulate the massive volume of book data into a usable format, we redirected our focus towards a more manageable and tailored recommendation domain, opting for a poetry recommendation tool. This pivot allowed us to work with a more concise and curated dataset, enabling us to explore recommendation techniques that were more suited to the available resources. While the transition presented a shift from the original idea, it was significantly more straightforward to implement.