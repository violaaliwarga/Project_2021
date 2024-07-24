**Welcome to My Portfolio!**

This project stands as a cornerstone of my academic journey, culminating in the completion of my Bachelor of Mathematics degree in 2021.
Titled "Using Decision Tree-Based Data Mining to Predict Types of Apparels," it delves into the realm of machine learning applied to fashion
classification using the DeepFashion dataset.

**Introduction**

The DeepFashion dataset was curated by Ziwei Liu and colleagues at The Chinese University of Hong Kong, served as the bedrock for
this research [1]. I was inspired by the pioneering work of Sheeman Jain and Vijay Kumar [2], who explored various algorithms for apparel
classification, I focused specifically on leveraging decision tree methodology to categorize clothing into Upper-Body, Lower-Body, and
Whole-Body categories. This study differed in its approach by employing Fine Annotation from the DeepFashion: Category and Attribute Prediction
Benchmark, ensuring precise integration of detailed garment images and annotations into a unified dataset.

**Project Objectives**

The primary objective was to develop a robust decision tree model capable of accurately categorizing garments based on their visual attributes.
By consolidating diverse data sources into a cohesive spreadsheet and meticulously labeling each item according to its category, I aimed to
streamline the classification process.

**Methodology**

The journey towards optimizing the decision tree model involved rigorous parameter tuning. Initially, I manually adjusted parameters through
iterative processes to refine model accuracy. Subsequently, leveraging the power of GridSearchCV automated parameter optimization further enhanced
the model's performance and interpretability. These meticulous efforts aimed not only to improve accuracy but also to unravel the most influential
attributes driving apparel classification.

**Research Questions**

1. **Optimal Decision Tree Parameters:** Explored through both manual iteration and GridSearchCV to identify parameters yielding the best model performance.
2. **Impactful Attributes:** Identified through comprehensive feature analysis to discern key attributes influencing apparel categorization.
3. **Improvements from Parameter Tuning:** Evaluated the enhancement in model accuracy and complexity management.
4. **Performance of Parameter-Tuned Model:** Assessed the model's robustness and accuracy on training and testing datasets.
5. **Accuracy of Final Labels:** Validated against image annotations to ensure alignment with predicted categories, affirming the model's efficacy.

**Conclusion**

Through the application of Python programming and advanced machine learning techniques with Pandas and Scikit-learn libraries, this project showcases
my proficiency in data analysis and model development. Achieving a commendable classification accuracy of 84%, the decision tree model proved its
efficacy in apparel categorization. Notably, the study highlighted "Dress" as a pivotal feature influencing classification decisions, offering valuable
insights for the fashion industry.

**Implications**

This project underscores the transformative potential of data mining in the apparel sector, offering scalable solutions for inventory management,
customer segmentation, and trend analysis. By harnessing open-source datasets like DeepFashion, this study not only advances academic research but
also offers practical applications with tangible benefits for industry stakeholders.



**References**

[1] Ziwei Liu, Ping Lou, Shi Qiu, Xiaogang Wang, and Xiaoou Tang. "DeepFashion: Powering robust clothes recognition and retrieval with rich annotations." In Proceedings of IEEE Conference on Computer Vision and Pattern Recognition (CVPR), June 2016.

[2] Sheeman Jain and Vijay Kumar. "Machine Learning Approach for Classification of Clothing using Various Algorithms." International Journal of Computer Applications, vol. 154, no. 1, 2016.
