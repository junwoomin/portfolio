자율주행·로보틱스 포트폴리오

[English](README.md)

전우민의 실차 통합, 인지, CARLA 주행 연구, 로봇 및 드론 시뮬레이션 작업을 정리한 포트폴리오입니다.

## 프로젝트와 데모

| 프로젝트 | 작업 및 역할 | 데모 |
| --- | --- | --- |
| ERP42 차선 유지 | 차량 하드웨어·소프트웨어 통합, RS232 통신, ROS 제어, 카메라 기반 차선 인식 및 실차 테스트 | [주행 영상](https://youtu.be/_pjnSMG2kxE) |
| Multi-task 인지와 3D SLAM | Multi-task 모델 개발 및 실차 탑재, 3D SLAM 파이프라인과 캘리브레이션 | [실차 영상](https://youtu.be/ng5Ybwfu_Hg) |
| BEV 로컬 경로 계획 | BEV에서 자차가 이동할 수 있는 로컬 경로 생성 및 시각화 | [데모](https://youtu.be/XU9eV1rfoUM) |
| CARLA에서 ST-P3 구동 | End-to-end 모델을 시뮬레이션에서 실행하고 BEV 관측 및 제어 값 시각화 | [예시](docs/projects.md#st-p3-in-carla) |
| 초기 CARLA 강화학습 연구 | 차량과 교통 신호를 고려한 모델 방향 및 보상 함수 설계 | [주행 데모](https://youtu.be/x9dXy39g8uU) |
| MM-LLM과 주행 강화학습 | 멀티모달 LLM을 활용한 end-to-end 강화학습 연구 | [데모](https://youtu.be/raNKD-_KNF0) |
| Isaac Sim과 장갑 연동 | 장갑 인터페이스와 시뮬레이션 연동 및 강화학습 탐색 | [데모](https://youtu.be/wOnYERak4DE) |
| QT128 라이다와 무한궤도 로봇 | 라이다 포인트 클라우드 시각화 및 무한궤도 차량 사용 | [사진](docs/projects.md#lidar-and-tracked-robot) |
| Depth map to 3D point cloud | 깊이 맵을 3D 포인트 클라우드로 변환 | [예시](docs/projects.md#depth-to-point-cloud) |
| GPS·3D SLAM 캘리브레이션 | 학교의 실제 GPS 위치와 Velodyne 32채널 라이다로 구축한 지도 비교 | [예시](docs/projects.md#gps-and-slam-calibration) |
| AirSim 다중 드론 제어 | Python으로 여러 드론 제어 | [데모](https://youtu.be/yvPjAFwAV1I) |
| AirSim·PX4·QGroundControl | 드론 경로 계획 및 루트 이동 실험 | [데모](https://youtu.be/-G0ETnGmNgc) |

## 연구 글

- **자율주행 자동차를 위한 종단간 학습 기술 중심의 기술 동향**: 공동 저자, 2024년 11월, 제49권 제11호. [DOI](https://doi.org/10.7840/kics.2024.49.11.1614)
- **CARLA 시뮬레이터에서 자율주행을 위한 심층강화학습 성능 비교**: DDPG, SAC, TD3, PPO, TQC 비교 연구 원고.

[프로젝트 상세 및 이미지](docs/projects.md)에서 전체 시각 자료를 볼 수 있습니다.

## 프로젝트별 저장소

| 프로젝트 | 저장소 |
| --- | --- |
| BEV 라벨 정합성 | [HBLR](https://github.com/junwoomin/HBLR) |
| 이웃 차량 BEV 특징 융합 | [FusionFormer](https://github.com/junwoomin/fusionformer) |
| Low Resource Simulation | [LRS](https://github.com/junwoomin/LRS) |
| Fleet occupancy mapping 및 멀티 에이전트 매핑 데모 | [CoReM](https://github.com/junwoomin/CoReM) |
| BEV 주차 | [BEV-Parking](https://github.com/junwoomin/BEV-Parking) |
| SDV UI 및 FMTC 라이다 4개 융합 데모 | [SDV](https://github.com/junwoomin/SDV) |
| BEVFormer·신호등 인지 및 현재 주행 정책 학습 | [AGILEQ-Training](https://github.com/SungjinDavidLee/AGILEQ-Training) |
| 주행 정책 평가 | [AGILEQ-Evaluation](https://github.com/SungjinDavidLee/AGILEQ-Evaluation) |
| Tenstorrent 가속기 작업 | [P100a project](https://github.com/junwoomin/tenstorrent_p100a_project) |
