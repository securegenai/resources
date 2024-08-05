# Generative AI Safety and Security Resources

Welcome to this curated list of tools, frameworks, and best practices for securing and responsibly using generative AI. 

This resource is a work in progress. We encourage community contributions! See [Contributing](#contributing) for details.

**Table of Contents**

* [Red Teaming and Adversarial ML](#red-teaming-and-adversarial-ml)
* [Benchmarking and Evaluation](#benchmarking-and-evaluation)
* [Data Security and Privacy](#data-security-and-privacy)
* [Model Explainability and Interpretability](#model-explainability-and-interpretability)
* [AI Ethics and Bias Mitigation](#ai-ethics-and-bias-mitigation)
* [Security Vulnerability Scanning and Monitoring](#security-vulnerability-scanning-and-monitoring)
* [AI Security Frameworks and Standards](#ai-security-frameworks-and-standards)
* [Educational Resources](#educational-resources)
* [Contributing](#contributing)

## Red Teaming and Adversarial ML

* **[Counterfit](https://github.com/Azure/counterfit):** Microsoft's open-source automation tool for security testing of AI systems.
* **[PyRIT](https://github.com/Azure/PyRIT):** Microsoft's Python Risk Identification Toolkit for generative AI, a framework for red teaming foundation models and their applications.
* **[Adversarial Robustness Toolbox (ART)](https://github.com/Trusted-AI/adversarial-robustness-toolbox):** A Python library for machine learning security, including evasion, poisoning, extraction, and inference attacks.
* **[TrojAI](https://github.com/trojai/trojai):**  A Python library for generating trojaned AI models, helpful for simulating backdoor attacks.
* **[Adversarial Policies for Safeguarding LLMs (APSL)](https://arxiv.org/abs/2305.16630):** A framework for creating adversarial policies for red teaming LLMs.
* **[RealToxicityPrompts](https://arxiv.org/abs/2009.11462):**  A dataset of prompts designed to elicit toxic language from language models. 

## Benchmarking and Evaluation

* **[HELM](https://crfm.stanford.edu/helm/latest/):**  Stanford's Holistic Evaluation of Language Models.
* **[MLCommons AI Safety Benchmark](https://mlcommons.org/en/aisafety/):**  A standardized benchmark for measuring LLM safety.
* **[GenAI - Evaluating Generative AI](https://ai-challenges.nist.gov/genai):**  NIST's platform for assessing generative AI technologies.
* **[BIG-bench](https://github.com/google/BIG-bench):**  A collaborative benchmark for measuring language model capabilities.
* **[Dynabench](https://dynabench.org/):**  A platform for dynamic benchmarking of AI models.
* **[EleutherAI Language Model Evaluation Harness](https://github.com/EleutherAI/lm-evaluation-harness):**  A toolkit for evaluating language models.
* **[TruthfulQA](https://github.com/sylinrl/TruthfulQA):**  A benchmark for measuring LLM truthfulness.
* **[Ethics in AI Benchmark](https://ai-benchmark.com/):**  A benchmark for evaluating ethical considerations in AI.
* **[RobustBench](https://robustbench.github.io/):** A benchmark for evaluating the robustness of image classification models.
* **[ImageNet-C](https://github.com/hendrycks/robustness):** A benchmark for evaluating the robustness of image classifiers to corruptions.
* **[GLUE Benchmark](https://gluebenchmark.com/):**  A collection of resources for evaluating NLU models.
* **[Dioptra](https://pages.nist.gov/dioptra/index.html):** NIST's software testbed for assessing the trustworthy characteristics of AI, with a focus on adversarial attacks and data poisoning.
* **[Inspect](https://www.gov.uk/government/news/ai-safety-institute-releases-new-ai-safety-evaluations-platform):** The U.K. AI Safety Institute's toolkit for assessing model capabilities and safety.

## Data Security and Privacy

*   **[Privacy-Preserving Machine Learning (PPML)](https://github.com/topics/privacy-preserving-machine-learning):**  Resources for privacy-preserving techniques.
*   **[Federated Learning](https://github.com/topics/federated-learning):** Resources for training AI models on decentralized data.
*   **[Differential Privacy](https://github.com/topics/differential-privacy):** Resources for adding noise to datasets to protect privacy.
*   **[CrypTen](https://github.com/facebookresearch/CrypTen):**  Meta's framework for privacy-preserving machine learning.
*   **[TensorFlow Privacy](https://github.com/tensorflow/privacy):**  Google's library for training models with differential privacy.
*   **[OpenMined](https://github.com/OpenMined):**  A community developing tools for privacy-preserving machine learning.
*   **[PySyft](https://github.com/OpenMined/PySyft):**  A library for secure and private deep learning.
*   **[Google's Secure AI Framework (SAIF)](https://cloud.google.com/blog/topics/security/introducing-googles-secure-ai-framework-saif):** A taxonomy of AI security risks with recommended mitigations.
*   **[Microsoft's Privacy-Preserving Machine Learning](https://www.microsoft.com/en-us/ai/ai-lab-open-source):** Resources for building privacy-protecting AI systems.

## Model Explainability and Interpretability

*   **[AI Explainability 360](https://github.com/Trusted-AI/AIX360):**  IBM's toolkit for explaining AI model decisions.
*   **[LIME](https://github.com/marcotcr/lime):**  A technique for explaining ML classifier predictions. 
*   **[SHAP](https://github.com/slundberg/shap):**  A method for explaining individual ML model predictions.
*   **[Captum](https://captum.ai/):**  Meta's model interpretability library.
*   **[Gemma Scope](https://www.neuronpedia.org/gemma-scope#learn):** Google Deepmind's set of sparse autoencoders (SAEs) for interpreting Gemma 2 models.
*   **[Mishax](https://deepmind.google/discover/blog/gemma-scope-helping-the-safety-community-shed-light-on-the-inner-workings-of-language-models/):**  Google Deepmind's tool for aiding language model interpretability, used in Gemma Scope development.

## AI Ethics and Bias Mitigation

*   **[AI Fairness 360](https://github.com/IBM/AIF360):**  IBM's toolkit for detecting and mitigating bias.
*   **[Fairlearn](https://fairlearn.org/):**  A Python package for fairness assessment and mitigation.

## Security Vulnerability Scanning and Monitoring

*   **[Fiddler](https://www.fiddler.ai/):**  Platform for monitoring, explaining, and debugging ML models.
*   **[Arthur](https://arthur.ai/):**  Tool for AI model monitoring and governance.
*   **[WhyLabs](https://whylabs.ai/):**  Platform for data quality and model performance monitoring.

## AI Security Frameworks and Standards

*   **[NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework):**  A voluntary framework for managing AI system risks.
*   **[EU Artificial Intelligence Act](https://artificialintelligenceact.eu/):** A proposed regulation for safe and ethical AI in the European Union.
*   **[OECD AI Principles](https://oecd.ai/en/principles/):** Principles for responsible AI stewardship.
*   **[The White House Blueprint for an AI Bill of Rights](https://www.whitehouse.gov/ostp/ai-bill-of-rights/):**  Guidelines for ethical AI development.
*   **[UNESCO Recommendation on the Ethics of Artificial Intelligence](https://en.unesco.org/artificial-intelligence/recommendation-ethics):**  A global framework for ethical AI.
*   **[Google's Secure AI Framework (SAIF)](https://cloud.google.com/blog/topics/security/introducing-googles-secure-ai-framework-saif):**  A taxonomy of AI security risks and mitigations.

## Educational Resources

* **[Partnership on AI](https://www.partnershiponai.org/):** Non-profit advancing responsible AI.

* **[Stanford CRFM](https://crfm.stanford.edu/):** Research center for understanding and improving foundation models.

* **[OpenAI Safety and Security](https://openai.com/safety):**  OpenAI's resource page on AI safety and security.

  

## Contributing

Contributions are welcome! If you know of any tools or resources that should be included, please submit a pull request.
