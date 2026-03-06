+++
widget = "experience"
headless = true
active = true
weight = 25

title = "Experiences"
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
  * Building a Video AI Evaluation Platform
    * **Benchmarking:** Build an evaluation pipeline for video understanding and benchmark frontier models (e.g., Gemini, GPT)
    * **Monitoring:** Design a scenario-based evaluation system for daily health checks and regression detection after model updates
    * **Visualization:** Develop an interactive web dashboard to review and share research results and demonstrate outcomes to external partners (e.g., Samsung Electronics)
    * **Infrastructure:** Architect a Ray-based distributed video indexing pipeline to process ~300 videos in parallel and build a Feast-based feature store serving as the single source of truth (SSOT) for video-derived features
  * Research on Video Understanding
    * **Video Scene Segmentation:** Study methods for segmenting videos into meaningful narrative units (scenes) while preserving contextual information
    * **Video RAG:** Explore retrieval-augmented generation approaches that leverage visual and audio signals for efficient storage and retrieval of video knowledge
  """

[[experience]]
  title = "AI Researcher"
  company = "Data Engineering LAB"
  company_url = ""
  location = "Seoul, Korea"
  date_start = "2022-03-01"
  date_end = "2025-05-01"
  description = """
  * Conducted research spanning **video anomaly detection** and **medical image segmentation**, with 4 first-author publications.
    * **Anomaly Detection:** Developed **[AnyAnomaly](https://skiddieahn.github.io/publication/wacv2026-anyanomaly/)**, a zero-shot VAD framework using LVLMs (WACV 2026); developed **[VideoPatchCore](https://skiddieahn.github.io/publication/accv2024-videopatchcore/)** extending PatchCore to the video domain (ACCV 2024); proposed **[MAMA](https://skiddieahn.github.io/publication/ieee-access-2024/)**, an SSL-based framework to amplify anomaly signals via frame destruction (IEEE Access)
    * **Segmentation:** Developed **[DS-UNETR](https://skiddieahn.github.io/publication/bigcomp-2024/)**, a dual-stream fusion U-Net Transformer for 3D medical image segmentation (IEEE BigComp 2024)
  * Graduation thesis: **[VideoPatchCore: An Effective Method to Memorize Normality for Video Anomaly Detection](https://library.yonsei.ac.kr/search/detail/CATTOT000002228093)** · **[Research Portfolio](https://shacoding.com/wp-content/uploads/2019/07/SHA_PF_0222.pdf)**
  * **Advisor:** Prof. Sanghyun Park (sanghyun@yonsei.ac.kr)
  """

+++
