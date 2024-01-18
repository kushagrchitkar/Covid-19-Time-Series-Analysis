# Time Series Analysis on Covid-19 Summarized Twitter Data Using Modified TextRank

## Research Background

During my undergraduate studies, I collaborated with Prof. Pabitra Mitra on a research project focused on the Spatio-Temporal Analysis of Covid-19-related tweets. The objective was to understand the evolution of human sentiments for specific keywords like 'Administration' or 'Disease' over time.

## Methodology

### Dataset
- Our dataset consisted of 185 million tweets posted between April 1, 2020, and September 30, 2020.

### Summarization Technique
- We employed the TextRank algorithm for Extractive Summarization.

### Modification to TextRank
- To enhance the summarization process, we introduced a damping component to adjust the weights of nodes in the TextRank algorithm.

### Optimization Strategy
- Parallel processing was implemented by dividing the daily dataset into four parts, and TextRank was applied independently to each component.

## Results

- **Time Series Generation**
  - We created time series data by using the frequency of specific keywords, resulting in data points.

- **Graphical Trends**
  - The generated graphs successfully linked trends to major global events, providing insights into the evolving sentiments related to Covid-19. An in depth analysis is provided in the paper uploaded in this repository.

## Publication

Our research findings were documented in a paper titled **'Time Series Analysis on Covid-19 Summarized Twitter Data Using Modified TextRank'**, which was accepted for presentation at the International Conference on Computational Intelligence in Pattern Recognition (CIPR-2022). The paper has been published in the Springer LNNS Series (Volume 480).

## Conference Presentation

Our research was presented at the International Conference on Computational Intelligence in Pattern Recognition (CIPR-2022), showcasing the innovative approach and insights gained from the time series analysis of Covid-19-related Twitter data (Presentation also uploaded).

This README provides a concise overview of our research, methodologies, results, and the publication of our findings in the Springer LNNS Series. For more detailed information, please refer to the complete paper.
