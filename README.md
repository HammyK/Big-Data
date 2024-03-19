## Overview
Welcome to the INM432 Big Data coursework for the year 2021. This coursework combines theoretical elements with practical components focusing on parallelization and scalability in the cloud using technologies like Spark and TensorFlow/Keras. The tasks encompass various aspects such as data preprocessing, machine learning, performance evaluation, and theoretical reflections.

### Code and Report
This repository contains the code in the form of a Jupyter Notebook named `Big Data.ipynb` along with a PDF report titled `Big Data Report.pdf`. The notebook includes the implementation of tasks such as porting, parallelization, extension, evaluation, and theoretical reflection. Each task is clearly delineated within the notebook along with appropriate code comments and explanations.

## Sections Overview
1. **Section 0: Set-up**
   - Environment setup including imports, authentication with Google Cloud, and mounting Google Drive
2. **Section 1: Data Pre-processing**
   - Pre-processing tasks involving reading image files, creating TF Record files, and measuring speed tests both locally and in the cloud
3. **Section 2: Machine Learning in the Cloud**
   - Training a deep neural network using pre-processed data in TensorFlow/Keras on Google Cloud AI-Platform
4. **Section 3: Theoretical Discussion**
   - Analyzing theoretical aspects based on provided papers, discussing the implications in the context of the coursework

## Report Highlights
- **Question 1:** Analysis of cloud speed tests for image dataset and decoded dataset with insights on performance metrics
- **Question 2:** Parallelizing speed tests with Spark in the cloud, discussing CPU utilization, network loads, and caching
- **Question 3:** Writing TFRecord files to the cloud with Spark, comparing two test scenarios with different configurations
- **Question 4:** Experimentation and evaluation of machine learning strategies in the cloud with varied parameters
- **Question 5:** Theoretical discussion on batch size, repetition, and strategies in big data analytics based on provided papers

For further details and to access the notebook, refer to the provided link: [Big Data.ipynb - Google Colab](https://colab.research.google.com/drive/1BO7hNMy2tKs5jMNuSxG6sb4pTuqwE_I7?usp=sharing).

## References
- Alipourfard, O., Liu, H. H., Chen, J., Venkataraman, S., Yu, M., & Zhang, M. (2017). Cherrypick: Adaptively unearthing the best cloud configurations for big data analytics. In USENIX NSDI 17 (pp. 469-482).
- Smith, S. L., Kindermans, P. J., Ying, C., & Le, Q. V. (2018). Don't Decay the Learning Rate, Increase the Batch Size. In ICLR (no pagination).
