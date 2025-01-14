# Dynamic User Preferences Optimization in Time-Aware Recommendation Systems
Master's thesis
Tampere University
Master’s Degree Programme in Data Science
October 2024

## Overview
In an era where personalization is key to user engagement, **recommendation systems** play a critical role in delivering relevant suggestions tailored to individual preferences. Traditional algorithms often struggle to capture the dynamic nature of user behavior, which evolves over time. This research focuses on **Time-Aware Recommendation Systems**, which incorporate temporal dynamics into the recommendation process to better adapt to these changes.

The core of this work is the exploration and enhancement of the **Time Correlation Coefficient (TCC)** model. While effective, the TCC model has limitations in fully understanding the nuanced and ever-changing nature of user preferences. To address these shortcomings, this research introduces four innovative methodologies that incorporate both **time-awareness** and **item similarity** into the recommendation framework.

The approaches presented in this repository aim to deliver recommendations that are not only accurate but also adaptive to users' evolving interests, thereby improving user experience, retention, and satisfaction.

---

## Key Contributions
This work explores and enhances the TCC model while introducing the following methodologies:

1. **Content-Based Approach**  
   - **Strengths**: High accuracy with moderate computational demands.  
   - **Applications**: Suitable for balanced performance requirements.

2. **Cuckoo Search Optimization**  
   - **Strengths**: Exceptional precision but computationally intensive.  
   - **Applications**: Environments where accuracy is paramount.

3. **Decay Model**  
   - **Strengths**: Prioritizes recent activity by devaluing older interactions.  
   - **Applications**: Systems focusing on short-term user preferences.

4. **Time-Based Approach**  
   - **Strengths**: Simple and efficient, ideal for large-scale systems.  
   - **Applications**: Scenarios with limited resources or massive datasets.

---

## Repository Contents
This repository includes:

1. **Code file ( in notebook:v21_phones_2)**  
   - Implementation of the four proposed methodologies, along with detailed explanations and visualizations.  
   - Notebook is compatible with both **Google Colab** and **Jupyter Notebook**.

2. **Dataset**  
   - The code is designed to work with the **Amazon Phones and Accessories Dataset**, which must be downloaded from Amazon's publicly available datasets.  
   

3. **Results and Insights**  
   - Key observations, including performance metrics are included in the code.

---

## Dataset Information
The notebook uses the **Amazon Cell_Phones_and_Accessories Dataset**.  
To acquire the dataset:  
1. Visit the [Amazon Datasets Repository](https://amazon-reviews-2023.github.io/).  
2. Download the dataset for **Cell_Phones_and_Accessories**.  


---

## How to Run
### Using Google Colab:
1. Open the [notebook file] (path/to/notebook.ipynb) directly in Colab by clicking this link: [Open in Colab] (https://colab.research.google.com/github/ainazeb/Thesis/blob/main/notebooks/v21_phones_2.ipynb)
2. Upload the dataset when prompted or ensure it is accessible from your environment.  
3. Run all cells sequentially to execute the code and view results.

### Using Jupyter Notebook:
1. Clone the repository:
   ```bash
   git clone https://github.com/ainazeb/Thesis.git
   cd Thesis

