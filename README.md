# Md Abu Sufian

**Explainable Multimodal AI for Cardiac Imaging and Cardiomyocyte Ageing.**
PhD researcher in Computer Science at the University of East London, developing explainable and multimodal AI for cardiac imaging, cardiomyocyte ageing, and cardiovascular disease research. My work combines medical imaging, microscopy, spatiotemporal modelling, multimodal data fusion, and clinically relevant validation to develop interpretable AI for cardiovascular research. I am also an Hourly Paid Lecturer at UEL and an MSc Bioinformatics Dissertation Supervisor at Birkbeck, University of London, within the Institute of Structural and Molecular Biology (Birkbeck–UCL). Based in London, UK.

[Google Scholar](https://scholar.google.com/citations?user=8ozStcUAAAAJ&hl=en) · [ResearchGate](https://www.researchgate.net/profile/Md-Abu-Sufian-2) · [LinkedIn](https://www.linkedin.com/in/tacticalbusinessintelligence) · [Personal-Website](https://abusufian.dev)

---

## What I work on

**1. Cardiac image analysis.** Transformer and hybrid CNN–RNN architectures for cardiac MRI and 3D echocardiography — segmentation, structural analysis, and label-efficient training from scribble annotations.

**2. Cardiomyocyte ageing.** Motion and nuclear phenotyping of cardiomyocytes from microscopy time-series, using optical flow and temporal transformers to detect functional decline before it is morphologically obvious.

**3. Explainability and clinical validation.** Post-hoc interpretability, algorithmic-bias auditing, and prospective validation of models against clinical endpoints — so that the output is defensible in a cardiology setting, not only accurate on a benchmark.

Methodologically this means vision transformers, multimodal fusion (imaging + tabular + text), generative augmentation for small clinical cohorts, and survival/prognostic modelling.

---

## Start here

| Project | What it is |
|:--|:--|
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1fac0.png" width="38" align="left" alt="cardiac"> **[triFuse-pytorch](https://github.com/datascintist-abusufian/triFuse-pytorch)** | **TriFuse-SRNet** — dynamic multi-expert fusion with structural recovery for *scribble-supervised* cardiac MRI segmentation. Reference PyTorch implementation, ACDC + MSCMRseg, with training, evaluation and statistical-comparison scripts. |
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f4ca.png" width="38" align="left" alt="dashboard"> **[medical-image-analysis](https://github.com/datascintist-abusufian/medical-image-analysis)** | Streamlit dashboard for segmentation-quality assessment — Dice, IoU, Hausdorff distance, uncertainty and regional performance. Used to audit the outputs of TriFuse-SRNet. |
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f5bc.png" width="38" align="left" alt="vision-language"> **[Structured-Caption-Supervision-for-Domain-Adaptive-Vision-Language-Learning-](https://github.com/datascintist-abusufian/Structured-Caption-Supervision-for-Domain-Adaptive-Vision-Language-Learning-)** | Vision–language learning with structured clinical caption supervision — CLIP and BLIP fine-tuned on BCN20000, cross-dataset validation on ISIC 2019. |
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1fa7a.png" width="38" align="left" alt="clinical"> **[AI-Models-for-Early-Cardiovascular-Diseases-Detection-](https://github.com/datascintist-abusufian/AI-Models-for-Early-Cardiovascular-Diseases-Detection-)** | Early detection and mortality prediction in cardiovascular disease — the platform behind *Diagnostics* 14(12), 1308 (2024). |
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/26a1.png" width="38" align="left" alt="electrophysiology"> **[Advanced-Cardiac-Electrophysiology-Mapping-](https://github.com/datascintist-abusufian/Advanced-Cardiac-Electrophysiology-Mapping-)** | Automated signal windowing and kriging-based spatial interpolation for optical mapping of cardiac electrophysiology — flecainide, low-flow ischaemia and cooling series. |
| <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f52c.png" width="38" align="left" alt="microscopy"> **[Deep-Spatiotemporal-Modelling-of-Cardiomyocyte-Ageing-Dysfunction](https://github.com/datascintist-abusufian/Deep-Spatiotemporal-Modelling-of-Cardiomyocyte-Ageing-Dysfunction)** | Optical-flow–driven detection of cardiomyocyte ageing from microscopy video, with a Transformer over motion phenotypes. Presented at BSCR/BCS (*Heart*, 2025). |

---

## Selected publications

- **Hybrid deep learning for computational precision in cardiac MRI segmentation: integrating autoencoders, CNNs and RNNs for enhanced structural analysis.** *Computers in Biology and Medicine* 186, 109597 (2025).
- **AI-driven thoracic X-ray diagnostics: transformative transfer learning for clinical validation in pulmonary radiography.** *Journal of Personalized Medicine* 14(8), 856 (2024). [DOI](https://doi.org/10.3390/jpm14080856)
- **Mitigating algorithmic bias in AI-driven cardiovascular imaging for fairer diagnostics.** *Diagnostics* 14(23), 2675 (2024). [DOI](https://doi.org/10.3390/diagnostics14232675)
- **Enhancing clinical validation for early cardiovascular disease prediction through simulation, AI and web technology.** *Diagnostics* 14(12), 1308 (2024). [DOI](https://doi.org/10.3390/diagnostics14121308)
- **Hypertension control in resource-constrained settings: bridging socioeconomic gaps with predictive insights.** *IJC Cardiovascular Risk and Prevention* (2025).
- **Advanced transformer-based AI framework for early detection and prediction of cardiomyocyte ageing and injury using motion phenotyping.** *Heart* 111 (Suppl 3), A269–A271 (2025).

Full list on [Google Scholar](https://scholar.google.com/citations?user=8ozStcUAAAAJ&hl=en). I also hold patents registered with the UK Intellectual Property Office.

---

## Repositories by theme

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1fac0.png" width="22" align="top"> <b>Cardiac imaging and segmentation</b></summary>

- [triFuse-pytorch](https://github.com/datascintist-abusufian/triFuse-pytorch) — TriFuse-SRNet, scribble-supervised segmentation (ACDC, MSCMRseg)
- [Cardiac-mri-scribble-segmentation](https://github.com/datascintist-abusufian/Cardiac-mri-scribble-segmentation) — weakly supervised segmentation from scribble labels
- [Generative-Augmentation-Using-VAE-GAN-and-Attention-U-Net](https://github.com/datascintist-abusufian/Generative-Augmentation-Using-VAE-GAN-and-Attention-U-Net) — augmentation for small cardiac cohorts
- [3D-Heart-Imaging-apps](https://github.com/datascintist-abusufian/3D-Heart-Imaging-apps) — 3D cardiac imaging application
- [Enhancing-Hypertrophic-Cardiomyopathy-Diagnosis-with-Deep-Learning-Driven-3D-Echocardiogram-Analysis](https://github.com/datascintist-abusufian/Enhancing-Hypertrophic-Cardiomyopathy-Diagnosis-with-Deep-Learning-Driven-3D-Echocardiogram-Analysis)
- [Deep-Learning-Methods-for-Heart-Image-Analysis](https://github.com/datascintist-abusufian/Deep-Learning-Methods-for-Heart-Image-Analysis) — review and benchmarking
- [AI-Models-for-Early-Cardiovascular-Diseases-Detection-](https://github.com/datascintist-abusufian/AI-Models-for-Early-Cardiovascular-Diseases-Detection-) — code for *Diagnostics* 14(12), 1308 (2024)

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f52c.png" width="22" align="top"> <b>Cardiomyocyte ageing and cell-level phenotyping</b></summary>

- [Deep-Spatiotemporal-Modelling-of-Cardiomyocyte-Ageing-Dysfunction](https://github.com/datascintist-abusufian/Deep-Spatiotemporal-Modelling-of-Cardiomyocyte-Ageing-Dysfunction)
- [Cardiomyocyte-cell-motion-analysis](https://github.com/datascintist-abusufian/Cardiomyocyte-cell-motion-analysis)
- [Cardiomyocyte-Ageing-Nucleus-Data-Analysis](https://github.com/datascintist-abusufian/Cardiomyocyte-Ageing-Nucleus-Data-Analysis)
- [New-Apps-cardiomyocyte](https://github.com/datascintist-abusufian/New-Apps-cardiomyocyte)
- [Cardiac-Cell-Development-Animation-Day-1-8-](https://github.com/datascintist-abusufian/Cardiac-Cell-Development-Animation-Day-1-8-)

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f6e0.png" width="22" align="top"> <b>Research software and clinical tools</b></summary>

- [Advanced-Cardiac-Electrophysiology-Mapping-](https://github.com/datascintist-abusufian/Advanced-Cardiac-Electrophysiology-Mapping-) — automated signal windowing, parallel processing
- [CardioMap-Pro-2.0-Advancing-Cardiac-Research-with-Next-Gen-Analytical-Software](https://github.com/datascintist-abusufian/CardioMap-Pro-2.0-Advancing-Cardiac-Research-with-Next-Gen-Analytical-Software)
- [Heart-Failure-Prediction-Calculator](https://github.com/datascintist-abusufian/Heart-Failure-Prediction-Calculator)
- [Medical_research_sample_size_calculator-](https://github.com/datascintist-abusufian/Medical_research_sample_size_calculator-) — sample-size calculator for cardiology, oncology and epidemiology studies
- [datascintist-abusufian-Neuro-App-AI-driven-4D-brain-image-processing-on-standalone-platforms](https://github.com/datascintist-abusufian/datascintist-abusufian-Neuro-App-AI-driven-4D-brain-image-processing-on-standalone-platforms)

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f50d.png" width="22" align="top"> <b>Explainability, multimodal and foundation models</b></summary>

- [post-hoc-explainer](https://github.com/datascintist-abusufian/post-hoc-explainer) — Streamlit app for cardiovascular risk modelling with feature-importance, ROC and confusion-matrix diagnostics
- [Structured-Caption-Supervision-for-Domain-Adaptive-Vision-Language-Learning-](https://github.com/datascintist-abusufian/Structured-Caption-Supervision-for-Domain-Adaptive-Vision-Language-Learning-)
- [High-Throughput-Multimodal-AI-Fusion-of-OCT-](https://github.com/datascintist-abusufian/High-Throughput-Multimodal-AI-Fusion-of-OCT-) — hypergraph fusion of OCT and functional data for glaucoma detection
- [BioNeuralNet-Leiden](https://github.com/datascintist-abusufian/BioNeuralNet-Leiden) — graph-based multi-omics representation learning
- [FinRAG](https://github.com/datascintist-abusufian/FinRAG) — retrieval-augmented generation over financial documents

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f9ec.png" width="22" align="top"> <b>Clinical prediction beyond cardiology</b></summary>

- [Multivariable-Modelling-Reveals-EGFR-Copy-Number-as-an-Independent-Predictor-of-Survival-in-LUAD](https://github.com/datascintist-abusufian/Multivariable-Modelling-Reveals-EGFR-Copy-Number-as-an-Independent-Predictor-of-Survival-in-LUAD)
- [TM-AHF-A-Text-Mining-a](https://github.com/datascintist-abusufian/TM-AHF-A-Text-Mining-a) — text mining plus vital signs for BNP/NT-proBNP-validated acute heart failure risk stratification
- [Alzheimer-s-Disease-Prediction-Using-Handwriting-and-AI-Models-for-Cognitive-Assessment](https://github.com/datascintist-abusufian/Alzheimer-s-Disease-Prediction-Using-Handwriting-and-AI-Models-for-Cognitive-Assessment)
- [Transformative-Insights-in-Pulmonary-Radiography-AI-Enabled-Innovations](https://github.com/datascintist-abusufian/Transformative-Insights-in-Pulmonary-Radiography-AI-Enabled-Innovations)
- [-Machine-Learning-Strategies-for-Breast-Cancer-Diagnosis-and-Prognosis](https://github.com/datascintist-abusufian/-Machine-Learning-Strategies-for-Breast-Cancer-Diagnosis-and-Prognosis)
- [Early-Pregnancy-Detection-and-prevention-using-Advanced-machine-learning-Algorithms](https://github.com/datascintist-abusufian/Early-Pregnancy-Detection-and-prevention-using-Advanced-machine-learning-Algorithms)
- [Survival-Analysis](https://github.com/datascintist-abusufian/Survival-Analysis)

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/2696.png" width="22" align="top"> <b>Fairness, health policy and population health</b></summary>

- [-Cardiovascular-Health-Tackling-Algorithmic-Bias-in-ML-and-AI-Models](https://github.com/datascintist-abusufian/-Cardiovascular-Health-Tackling-Algorithmic-Bias-in-ML-and-AI-Models)
- [Hypertension-Control-in-Resource-Constrained-Settings](https://github.com/datascintist-abusufian/Hypertension-Control-in-Resource-Constrained-Settings)
- [AI-Enabled-Study-of-Funding-Cuts-in-the-UK-Exploring-Regional-Mental-Health-Disparities](https://github.com/datascintist-abusufian/AI-Enabled-Study-of-Funding-Cuts-in-the-UK-Exploring-Regional-Mental-Health-Disparities)
- [Machine-Learning-and-Public-Health-Predictive-Analysis-of-UK-Traffic-Accident-Severity-and-I](https://github.com/datascintist-abusufian/Machine-Learning-and-Public-Health-Predictive-Analysis-of-UK-Traffic-Accident-Severity-and-I)

</details>

<details>
<summary><img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/72x72/1f4ca.png" width="22" align="top"> <b>Earlier applied data science (pre-PhD)</b></summary>

Kept for provenance; these predate the current research programme.

- [Data-analytics-on-key-indicators-for-the-smart-city-s-urban-services-and-dashboards-for-leadership-a](https://github.com/datascintist-abusufian/Data-analytics-on-key-indicators-for-the-smart-city-s-urban-services-and-dashboards-for-leadership-a)
- [UK-s-Energy-Landscape-An-ESG-Perspective](https://github.com/datascintist-abusufian/UK-s-Energy-Landscape-An-ESG-Perspective)
- [Machine-Learning-and-Sustainability-Metrics-Optimising-Risk-Assessment-and-Default-Prediction.](https://github.com/datascintist-abusufian/Machine-Learning-and-Sustainability-Metrics-Optimising-Risk-Assessment-and-Default-Prediction.)
- [Water-modelling](https://github.com/datascintist-abusufian/Water-modelling) — Bayesian uncertainty quantification for sediment-flux prediction
- [A-Deep-Learning-based-Twitter-Sentiment-Analysis-for-Bitcoin-Market-Predictions-](https://github.com/datascintist-abusufian/A-Deep-Learning-based-Twitter-Sentiment-Analysis-for-Bitcoin-Market-Predictions-)
- [Developing-Trading-Strategies-in-Decentralized-Trading-Markets-Prediction-by-Using-AI-ML-And-Blockc](https://github.com/datascintist-abusufian/Developing-Trading-Strategies-in-Decentralized-Trading-Markets-Prediction-by-Using-AI-ML-And-Blockc)
- [Data-Analytics-for-Esports](https://github.com/datascintist-abusufian/Data-Analytics-for-Esports) · [Boost-Financial-Health-in-the-E-sports-Industry-Machine-Learning-Model-based](https://github.com/datascintist-abusufian/Boost-Financial-Health-in-the-E-sports-Industry-Machine-Learning-Model-based)
- [Micro-Segmentation-Through-Hybrid-Clustering](https://github.com/datascintist-abusufian/Micro-Segmentation-Through-Hybrid-Clustering)

</details>

---

## Teaching, supervision and service

- Hourly Paid Lecturer, University of East London — teaching and supervision of MSc and undergraduate projects
- Dissertation supervisor, MSc Bioinformatics, Birkbeck, University of London
- Editorial involvement, British Society of Cardiovascular Research
- Open to collaboration on cardiac imaging, cardiomyocyte ageing and clinical validation of medical AI

## Toolbox

Python · PyTorch · MONAI · scikit-learn · OpenCV · R · MATLAB · Streamlit · Docker · Git · LaTeX

Imaging: cardiac MRI, 3D echocardiography, OCT, live-cell microscopy, histopathology

## Contact

[abusufian.dev](https://abusufian.dev) · [LinkedIn](https://www.linkedin.com/in/tacticalbusinessintelligence) · [Google Scholar](https://scholar.google.com/citations?user=8ozStcUAAAAJ&hl=en)
