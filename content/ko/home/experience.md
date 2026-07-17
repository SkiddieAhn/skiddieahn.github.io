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
  company = "주식회사 파일러"
  company_url = ""
  location = "서울, 대한민국"
  date_start = "2025-07-01"
  date_end = ""
  description = """
  * **Context-aware Video Understanding**
    * **Scene Segmentation:** 비디오의 맥락을 유지한 채 분석하기 위한 멀티모달 Scene Segmentation 모델 연구 및 개발
    * **Video Indexing:** Scene-aware Video Indexing 시스템 설계 및 개발
  * **Video Content Moderation**
    * **Benchmark Dataset:** Video Safety 벤치마크 데이터셋 구축 파이프라인 개발
    * **Model Benchmarking:** Video Safety 모델 벤치마킹 및 성능 고도화
  * **AI Infrastructure**
    * **Scalable AI Infrastructure:** Ray와 vLLM 기반의 대규모 비디오 처리를 위한 분산 AI 파이프라인 설계
    * **Feature Management:** 비디오 파생 피처의 단일 신뢰 데이터(SSOT)를 위한 Feast 기반 Feature Store 구축 및 관리
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
    * **영상 분할:** 3D 의료 영상 분할을 위한 이중 스트림 융합 U-Net Transformer **[DS-UNETR](https://skiddieahn.github.io/publication/bigcomp-2024/)** 개발 (BigComp 2024, ORAL)
  * 졸업 논문: **[VideoPatchCore: An Effective Method to Memorize Normality for Video Anomaly Detection](https://library.yonsei.ac.kr/search/detail/CATTOT000002228093)** · **[연구 포트폴리오](https://shacoding.com/wp-content/uploads/2019/07/SHA_PF_0222.pdf)**
  * **지도교수:** 박상현 교수 (sanghyun@yonsei.ac.kr)
  """

+++