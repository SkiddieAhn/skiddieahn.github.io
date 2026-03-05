+++
widget = "experience"
headless = true
active = true
weight = 25

title = "Research Experiences"
subtitle = ""

[design.spacing]
  padding = ["20px", "0", "20px", "0"]

[[experience]]
  title = "ML Research Engineer (Technical Research Personnel)"
  company = "PYLER"
  company_url = ""
  location = "Seoul, Korea"
  date_start = "2025-07-01"
  date_end = ""
  description = """
  * Built an end-to-end ML model evaluation platform
    * **Benchmarking:** Drove large-scale benchmarking of frontier models (e.g., Gemini, GPT-4), improving Video QA performance by 5% over the GPT-4V baseline
    * **Evaluation Framework:** Designed a scenario-driven evaluation framework with scenario packs, evidence bundles, and automated health checks to ensure reproducibility and catch regressions
    * **Visualization Platform:** Built an interactive web dashboard for evaluation results exploration, side-by-side demos, and researcher collaboration; key demonstration platform for enterprise partners including Samsung Electronics
    * **Scalable Infrastructure:** Architected a distributed evaluation system using Ray to process ~300 long videos concurrently, with a Feast-based feature store managing video-derived features as the single source of truth (SSOT)
  * Conducted research on video understanding
    * **Video Scene Segmentation:** Studied methods to divide videos into coherent narrative units while preserving contextual information
    * **Video RAG:** Explored retrieval-augmented generation approaches leveraging visual and auditory features for efficient storage and retrieval of video knowledge
  """

[[experience]]
  title = "AI Researcher"
  company = "Data Engineering LAB"
  company_url = ""
  location = "Seoul, Korea"
  date_start = "2022-03-01"
  date_end = "2025-05-01"
  description = """
  * Conducted research spanning **medical image segmentation** and **video anomaly detection**, with 4 first-author publications at ACCV, WACV, IEEE Access, and BigComp
    * **Segmentation:** Developed DS-UNETR, a dual-stream fusion U-Net Transformer for 3D medical image segmentation (BigComp 2024, ORAL)
    * **Anomaly Detection:** Proposed VideoPatchCore extending PatchCore to the video domain via temporal patch memory (ACCV 2024); developed AnyAnomaly, a zero-shot VAD framework using LVLMs (WACV 2026)
  * Graduation thesis: **[VideoPatchCore: An Effective Method to Memorize Normality for Video Anomaly Detection](https://library.yonsei.ac.kr/search/detail/CATTOT000002228093)** · **[Research Portfolio](https://shacoding.com/wp-content/uploads/2019/07/SHA_PF_0222.pdf)**
  * **Advisor:** Prof. Sanghyun Park (sanghyun@yonsei.ac.kr)
  """

+++
