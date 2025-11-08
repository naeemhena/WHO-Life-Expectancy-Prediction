# WHO-Life-Expectancy-Prediction
Life Expectancy Prediction for WHO-To assist the World Health Organization (WHO) in predicting average life expectancy across countries. The goal is to provide data-driven insights to help prioritise health interventions and resource allocation, while strictly adhering to the highest standards of data ethics and privacy.
**Project Overview**

Life expectancy is a critical indicator for socio-economic planning and public health policy. Using a dataset provided by the WHO (covering 183 countries from 2000-2015), we built two distinct predictive models to cater to varying levels of data privacy and sensitivity:

- The Max Model: Our most accurate model, achieving an RMSE of 1.18—a 34% improvement over the baseline of 1.80. It utilizes 8 input features and is optimized for detailed policy planning and impact evaluation.
- The Sensitive Friendly Model: A minimalist model designed for privacy-first scenarios. It uses only 4 input features and achieves an RMSE of 2.07, providing a robust prediction without compromising sensitive information.
**Repository Structure**
- 2 Jupyter notebooks
1. Final data analysis, model development and validation
2. The deployable prediction function
