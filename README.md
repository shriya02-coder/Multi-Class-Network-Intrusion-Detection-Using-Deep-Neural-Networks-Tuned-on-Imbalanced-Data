# Multi-Class-Network-Intrusion-Detection-Using-Deep-Neural-Networks-Tuned-on-Imbalanced-Data
This paper presents a novel DL approach for effectively identifying various types of network intrusions, utilizing an enhanced dataset to improve classification accuracy in cybersecurity.

## Abstract
In the current landscape where computer networks are integral yet increasingly vulnerable, the threat of cyberattacks poses a significant risk to critical infrastructure. Conventional network intrusion detection systems are often hampered by limitations such as a lack of diverse samples and suboptimal classification accuracy. This study leverages the comprehensive University of Nevada - Reno Intrusion Detection Dataset (UNR-IDD), which includes standard network traffic and five distinct types of intrusions, to develop an advanced deep neural network for multi-class intrusion detection. The methodology commenced with an in-depth exploratory data analysis, followed by the construction of a baseline Multi-Layer Perceptron model. To enhance the model’s efficacy, a rigorous tuning protocol was employed, incorporating ANOVA for feature selection and a systematic grid search for hyperparameter optimization. The research robustly illustrates the effectiveness of meticulous tuning, using validation accuracy as a guiding metric, and sets a precedent for creating high-performance deep learning-based intrusion detection systems. The insights and methodologies derived from this research have the potential to significantly empower cybersecurity professionals, providing them with critical tools to defend against evolving and sophisticated cyber threats.

## Introduction
Computer networks and network-based critical infrastructure systems are increasingly exposed to malicious cyberattacks, which pose severe disruptive risks. Existing datasets for training machine learning models in network intrusion detection face significant limitations. Many of these datasets lack a diverse range of samples, failing to adequately represent the full spectrum of intrusion techniques. This leads to poor generalization in real-world applications. Moreover, these datasets often suffer from imbalances, with an overemphasis on prevalent attack types like denial-of-service, while rare intrusion classes are underrepresented, resulting in low detection accuracy. Models trained on such data are typically inadequate in identifying atypical anomalies and zero-day attacks.

Addressing these research gaps, the University of Nevada - Reno Intrusion Detection Dataset (UNR-IDD) offers network traffic data that includes normal activities and five distinct classes of cyber intrusions. UNR-IDD stands out for its diverse and balanced sample distribution, which is conducive to building machine learning models capable of robust anomaly detection. While binary classification of traffic as normal or anomalous is valuable, discerning specific intrusion techniques provides deeper insights into attack origins, enabling security analysts to develop more targeted countermeasures. Consequently, UNR-IDD effectively transforms network intrusion detection into a multi-class classification challenge.

Deep neural networks, adept at extracting complex abstract features from raw traffic data, overcome the limitations of manual feature engineering. Their ability to learn representations is particularly suited to the high-dimensional and noisy nature of network traffic data. This research focuses on developing a deep learning model, systematically tuned to accurately categorize UNR-IDD data into normal behavior and five distinct intrusion types. This approach offers a sophisticated solution for real-time cyber threat monitoring.

The methodical experimentation in this study sets a benchmark for developing high-accuracy deep neural network architectures for tasks like multi-class network intrusion detection. It advances the state-of-the-art in applying deep learning to cybersecurity, introducing a structured tuning process that significantly enhances detection accuracy. The developed techniques notably improve the differentiation between normal network traffic and specific intrusion types, empowering security experts with the knowledge to understand attack vectors and fortify network defenses effectively.

## Publication Details
This research is set to be published in the 2023 IEEE International Carnahan Conference on Security Technology and will be included in the Scopus-indexed IEEE Xplore Digital Library.

## Contact for Code
For access to the code and methodologies used in this study, please contact the authors via the following email addresses:
- Shriya Pingulkar: pingulkarshriya@gmail.com
- Shruti Tyagi: tyagishruti4102@gmail.com
- Amaan Shaikh: amaan.jus@gmail.com

## Citation
Please cite this research if utilized in your work.
