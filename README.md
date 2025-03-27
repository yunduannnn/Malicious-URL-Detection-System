This Repo is from the Paper: Enhancing Online Security: "A Novel Machine Learning Framework for Robust Detection of Known and Unknown Malicious URLs", Owned by Shiyun Li and Omar Dib.

Here is our paper cite link:

J. Theor. Appl. Electron. Commer. Res. 2024, 19(4), 2919-2960; https://doi.org/10.3390/jtaer19040141

Abstract: The rapid expansion of the internet has led to a corresponding surge in malicious online activities, posing significant threats to users and organizations. Cybercriminals exploit malicious uniform resource locators (URLs) to disseminate harmful content, execute phishing schemes, and orchestrate various cyber attacks. As these threats evolve, detecting malicious URLs (MURLs) has become crucial for safeguarding internet users and ensuring a secure online environment. In response to this urgent need, we propose a novel machine learning-driven framework designed to identify known and unknown MURLs effectively. Our approach leverages a comprehensive dataset encompassing various labels—including benign, phishing, defacement, and malware—to engineer a robust set of features validated through extensive statistical analyses. The resulting malicious URL detection system (MUDS) combines supervised machine learning techniques, tree-based algorithms, and advanced data preprocessing, achieving a high detection accuracy of 96.83% for known MURLs. For unknown MURLs, the proposed framework utilizes CL_K-means, a modified k-means clustering algorithm, alongside two additional biased classifiers, achieving 92.54% accuracy on simulated zero-day datasets. With an average processing time of under 14 milliseconds per instance, MUDS is optimized for real-time integration into network endpoint systems. These outcomes highlight the efficacy and efficiency of the proposed MUDS in fortifying online security by identifying and mitigating MURLs, thereby reinforcing the digital landscape against cyber threats.

**<p align="center">Architecture of machine learning-based malicious URL classification</p>**
<p align="center">
<img src="Figures/Application Senario.png" width="280" />
</p>

**<p align="center">The framework of the proposed malicious URL detection system (MUDS)</p>**
<p align="center">
<img src="Figures/Malicious URL Detection System.png" width="280" />
</p>

Readers can check the source code for different part of this paper, including:
1. Feature Statistical Analysis: Malicious_URL_Detection_final_feature_analysis.ipynb
2. Multi-Class-Classification with the best machine learning method: Multi_Class_Classification_With_Best_Machine_Learning_Model.ipynb
3. Example for robustness study of known MUDS: Robustness_Study_Phishing.ipynb
4. Example for binary classifier plus SMOTE: Binary_Classifier_SMOTE.ipynb
5. CL_K-means_BC:Sample_CL_K_means_BC.ipynb

Thanks for reading. Welcome for everyone's comments.
