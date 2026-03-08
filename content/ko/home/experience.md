+++
widget = "experience"
headless = true
active = true
weight = 25

title = "경력"
subtitle = ""

[design.spacing]
  padding = ["20px", "0", "20px", "0"]

[[experience]]
  title = "ML Research Engineer (전문연구요원)"
  company = "PYLER"
  company_url = ""
  location = "서울, 대한민국"
  date_start = "2025-07-01"
  date_end = ""
  description = """
  * **Video AI Evaluation Platform 구축**
    * **Benchmarking:** 비디오 이해(Video Understanding)를 위한 평가 파이프라인을 구축하고 Gemini, GPT 등 최신 모델을 벤치마킹
    * **Monitoring:** 시나리오 기반 평가 시스템을 설계하여 모델 성능을 지속적으로 모니터링하고 모델 업데이트 이후 발생하는 성능 저하(regression)를 자동으로 탐지
    * **Visualization:** 연구 결과를 검토·공유하고 외부 파트너(예: 삼성전자)에 시연할 수 있는 인터랙티브 웹 대시보드 개발
    * **Infrastructure:** 약 300개의 비디오를 병렬 처리할 수 있는 Ray 기반 분산 비디오 인덱싱 파이프라인을 설계하고, 비디오 파생 feature의 단일 소스(SSOT) 역할을 하는 Feast 기반 Feature Store 구축
  * **Video Understanding 연구**
    * **Video Scene Segmentation:** 비디오를 의미 있는 서사 단위(scene)로 분할하면서도 문맥 정보를 유지할 수 있는 영상 분할 방법 연구
    * **Video RAG:** 시각 및 음성 정보를 활용하여 비디오 지식을 효율적으로 저장·검색할 수 있는 Retrieval-Augmented Generation(Video RAG) 접근 방식 연구
  """

[[experience]]
  title = "AI 연구원"
  company = "연세대학교 데이터공학연구실"
  company_url = ""
  location = "서울, 대한민국"
  date_start = "2022-03-01"
  date_end = "2025-05-01"
  description = """
  * 비디오 이상 탐지 및 의료 영상 분할 분야 연구, 제1저자 논문 4편 게재
    * **이상 탐지:** LVLM 기반 제로샷 VAD 프레임워크 **[AnyAnomaly](https://skiddieahn.github.io/publication/wacv2026-anyanomaly/)** 개발 (WACV 2026); PatchCore를 비디오 도메인으로 확장한 **[VideoPatchCore](https://skiddieahn.github.io/publication/accv2024-videopatchcore/)** 제안 (ACCV 2024); 프레임 손상을 통한 이상 신호 증폭 SSL 프레임워크 **[MAMA](https://skiddieahn.github.io/publication/ieee-access-2024/)** 개발 (IEEE Access)
    * **의료 영상 분할:** 3D 의료 영상 분할을 위한 이중 스트림 융합 U-Net Transformer **[DS-UNETR](https://skiddieahn.github.io/publication/bigcomp-2024/)** 개발 (BigComp 2024, ORAL)
  * 졸업 논문: **[VideoPatchCore: An Effective Method to Memorize Normality for Video Anomaly Detection](https://library.yonsei.ac.kr/search/detail/CATTOT000002228093)** · **[연구 포트폴리오](https://shacoding.com/wp-content/uploads/2019/07/SHA_PF_0222.pdf)**
  * **지도교수:** 박상현 교수 (sanghyun@yonsei.ac.kr)
  """

+++
