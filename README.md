# Caltech CS/CNS/EE 155 Miniproject 2: MovieLens Dataset Analysis

## Introduction

This project analyzes the MovieLens dataset, focusing on rating distributions and latent factors affecting movie ratings. The team consists of Sergio Esteban, Lena Wu, and Asav Kumar. We divided the work into basic visualizations and matrix factorization visualizations.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: Matplotlib, Surprise SVD, Numpy, Seaborn, Sklearn, Pandas

## Methodology

### Basic Visualizations

We analyzed the rating distribution across the entire dataset and subsets, identifying normal distributions with slight biases towards higher ratings.

### Matrix Factorization Visualizations

We implemented three methods of matrix factorization to explore latent factors:
1. HW5 SVD with Bias
2. Surprise SVD with Bias
3. Surprise SVD without Bias

## Results

- The average movie rating in the dataset is 3.55 with a standard deviation of 1.03.
- Movies within the top 10 most popular and best categories showed biases towards higher ratings.
- Genre analysis revealed differences in rating patterns among Comedy, Documentary, and Horror movies.
- Matrix factorization methods yielded distinct clustering and alignment of movies, illustrating the impact of biases and latent factors on rating patterns.

## Conclusion

This project provided insights into the MovieLens dataset's rating distribution and the underlying factors through visualizations and matrix factorization techniques. The findings underscore the complexity of user rating behaviors and the potential for bias in movie ratings.