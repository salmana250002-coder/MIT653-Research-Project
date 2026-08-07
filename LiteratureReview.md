# Literature Review: Use of AI in Cybersecurity Threat Detection

**Course:** MIT653 – Research Methods
**Student:** Salman (Solo Group)
**Research Topic:** Use of AI in Cybersecurity Threat Detection

---

## 1. Introduction

This literature review examines three research papers relevant to the use of Artificial Intelligence (AI) and Machine Learning (ML) in cybersecurity threat detection, specifically in the domain of Intrusion Detection Systems (IDS). The papers were selected to represent a foundational study, a recent comprehensive systematic review, and a study addressing key challenges in the field. Together, they provide a well-rounded view of the historical development, current state, and open problems in AI-based threat detection.

---

## 2. Selected Papers

### Paper 1 (Foundational)
**Title:** A Survey of Data Mining and Machine Learning Methods for Cyber Security Intrusion Detection
**Authors:** Anna L. Buczak, Erhan Guven
**Published:** IEEE Communications Surveys & Tutorials, Vol. 18, No. 2, 2016

### Paper 2 (Recent / Comprehensive)
**Title:** A Systematic Literature Study of Machine Learning Techniques Based Intrusion Detection: Datasets, Models, Challenges, and Future Directions
**Authors:** Hafiz Muhammad Raza Ur Rehman, Saira Liaquat, Muhammad Junaid Gul, Muhammad Zeeshan Jhandir, Daniel Gavilanes, Manuel Masias Vergara, Imran Ashraf
**Published:** Journal of Big Data, Vol. 12, Article 264, November 2025 (Open Access)
**DOI:** 10.1186/s40537-025-01323-2

### Paper 3 (Challenges / Unresolved Issues)
**Title:** Adversarial Machine Learning in Network Intrusion Detection Domain: A Systematic Review
**Source:** arXiv preprint, arXiv:2112.03315

---

## 3. Summary of Each Paper

### 3.1 Buczak & Guven (2016)
This paper is one of the most widely cited foundational works in the field of ML-based cybersecurity. It provides a broad survey of data mining and machine learning methods used for intrusion detection, including classifiers such as Support Vector Machines (SVM), decision trees, clustering algorithms, and hybrid approaches. The authors compare methods based on computational complexity and detection performance, and discuss the datasets commonly used at the time (e.g., KDD Cup 99). The paper establishes core terminology and a classification framework that later studies continue to build upon.

**Contribution to topic:** Provides the theoretical and historical foundation for understanding why and how machine learning was first introduced into intrusion detection, forming the basis for evaluating more recent techniques.

### 3.2 Rehman et al. (2025)
This is a recent, comprehensive systematic literature review that follows a PRISMA-based methodology, analyzing 104 peer-reviewed articles published between 2011 and 2024 (sourced from IEEE Xplore, ACM, ScienceDirect, SpringerLink, and Web of Science). The review categorizes ML-based IDS techniques (supervised, unsupervised, deep learning, and hybrid models), compares benchmark datasets (NSL-KDD, CICIDS2017, UNSW-NB15), and evaluates them using standard metrics (accuracy, precision, recall, F1-score, false positive rate). It also identifies dataset limitations (class imbalance, outdated attack types) and algorithmic challenges (overfitting, lack of adaptability to zero-day attacks).

**Contribution to topic:** Offers the most up-to-date and structured overview of the field, directly demonstrating how systematic literature reviews should be conducted (as taught in Week 3 lecture) and providing a taxonomy that can guide the direction of the student's own research question.

### 3.3 Adversarial ML in NIDS – Systematic Review (arXiv)
This paper focuses specifically on a major challenge within AI-based intrusion detection: adversarial machine learning. It systematically reviews studies showing that ML/DL-based Network Intrusion Detection Systems (NIDS) can be deliberately fooled by attackers who craft adversarial inputs, causing the model to misclassify malicious traffic as benign. The review discusses attack techniques, defence strategies, and the general vulnerability of deep learning-based detection systems to such manipulation.

**Contribution to topic:** Highlights an unresolved and critical limitation of AI-based threat detection — that AI systems can themselves become a target of attack — which is essential for identifying research gaps and future research directions.

---

## 4. Common Themes Across the Papers

- **Shift from traditional to AI-based detection:** All three papers agree that traditional signature-based security systems are no longer sufficient against increasingly sophisticated and evolving cyber threats, and that ML/AI-based approaches offer improved detection of unknown (zero-day) attacks.
- **Dataset dependency:** Papers 1 and 2 both highlight those outdated or imbalanced datasets (e.g., KDD'99, NSL-KDD) significantly affect the reliability and real-world applicability of ML models.
- **Trade-off between accuracy and practicality:** Across all papers, there is a recurring theme that higher-accuracy models (e.g., deep learning, ensemble methods) often come with higher computational cost, reduced interpretability, and greater vulnerability to attack.
- **Need for adaptability:** All three sources stress those static models trained on fixed datasets struggle to keep up with new and evolving attack types.

---

## 5. Key Findings and Methodologies

| Paper | Methodology | Key Finding |
|---|---|---|
| Buczak & Guven (2016) | Narrative/comparative survey of ML and data mining methods | Established a classification of ML methods for IDS and their relative complexity/performance trade-offs |
| Rehman et al. (2025) | PRISMA-based systematic review (104 papers, 2011–2024) | Deep learning and ensemble/hybrid models outperform traditional ML but face scalability, interpretability, and real-time performance challenges |
| Adversarial ML in NIDS (arXiv) | Systematic review of adversarial ML literature | ML/DL-based IDS models are vulnerable to adversarial manipulation, undermining trust in AI-based detection systems |

---

## 6. Research Gaps Identified

Based on the synthesis of these three papers, the following gaps emerge in the current literature:

1. **Lack of real-time, scalable IDS models** that can operate effectively in high-speed, large-scale network environments without sacrificing detection accuracy.
2. **Outdated benchmark datasets** that fail to represent modern, real-world attack patterns (e.g., IoT-based attacks, encrypted traffic).
3. **Limited explainability (XAI)** of deep learning-based detection models, making it difficult for security analysts to trust or interpret AI decisions.
4. **Insufficient robustness against adversarial attacks**, meaning AI-based detection systems can be deliberately deceived by attackers.
5. **Privacy concerns** in centralized ML training approaches, pointing toward the need for privacy-preserving techniques such as federated learning.

---

## 7. Conclusion

The reviewed literature shows a clear evolution in the field: from early foundational surveys establishing core ML techniques for intrusion detection (Buczak & Guven, 2016), to comprehensive, up-to-date systematic reviews mapping the current state of ML/DL-based IDS research (Rehman et al., 2025), to focused studies exposing critical weaknesses such as adversarial vulnerability. Together, these gaps — particularly around explainability, real-time scalability, dataset realism, and adversarial robustness — provide clear direction for future research within the broader topic of "Use of AI in Cybersecurity Threat Detection."

---

## 8. References

1. Buczak, A. L., & Guven, E. (2016). A survey of data mining and machine learning methods for cyber security intrusion detection. *IEEE Communications Surveys & Tutorials*, 18(2), 1153–1176.
2. Rehman, H. M. R. U., Liaquat, S., Gul, M. J., Jhandir, M. Z., Gavilanes, D., Vergara, M. M., & Ashraf, I. (2025). A systematic literature study of machine learning techniques based intrusion detection: datasets, models, challenges, and future directions. *Journal of Big Data*, 12, 264. https://doi.org/10.1186/s40537-025-01323-2
3. Adversarial Machine Learning in Network Intrusion Detection Domain: A Systematic Review. *arXiv preprint*, arXiv:2112.03315.
