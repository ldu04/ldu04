# 안녕하세요, 이동욱입니다 👋
> 숭실대학교 전자공학과 3학년입니다.

## 🛠 Tech Stack
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

## 📌 Projects
| 프로젝트 | 설명 | 성과 | 기술 |
|---------|------|------|------|
| [불사 (不死)](https://github.com/ldu04/2026ESWContest_free_HWAJUNGSAENGRYEON) | 노드의 죽음을 데이터로 바꾸는 자가치유 산불 감시 메시 — ESP32 16노드 실물 실증 | 화선 방향 오차 **2.85°** · 16노드 중 **13노드**가 사망 전 경보 수신 | ESP32 · C++ · painlessMesh · Python |
| [carla-project](https://github.com/ldu04/carla-project) | YOLOv8 + C-V2X 기반 대형차 전방 시야 공유 시스템 | — | Python · CARLA · YOLOv8 |
| [cj-box-size-estimation](https://github.com/ldu04/cj-box-size-estimation) | 단일 CCTV 영상 기반 화물 3D 크기 추정 | 공모전 **39팀 중 6위** | Python · YOLO · ONNX |
| [nom_detector](https://github.com/ldu04/nom_detector) | 웹캠 기반 실시간 거북목 감지 및 3단계 경고 시스템 | — | Python · MediaPipe |
| [p5js-portfolio](https://github.com/ldu04/p5js-portfolio) | p5.js 사이버강의 실습 모음 | — | JavaScript |

### 🔥 불사 (不死) — 제24회 임베디드SW경진대회 자유공모 출품작
산불 현장에서 센서 노드는 반드시 타 죽습니다. 그 죽음을 손실로 버리지 않고,
**노드가 죽은 시각과 좌표를 화재 관측 데이터로 역이용**하는 시스템입니다.

- **실물 실증** — ESP32 16노드를 20 cm 간격 4×4 격자에 깔고, 열풍기로 23분에 걸쳐 순차 소사. 재촬영 없이 1회차 성공
- **화선 추정** — 죽은 노드 좌표에 평면을 적합해 방향·속도 역산. 방향 오차 **2.85°**, 속도 오차 **+1.67%**
- **사전 경보** — 16노드 중 **13노드**가 자기가 죽기 전에 도달 예상 경보 수신 (평균 351초 전)
- **자가치유 라우팅** — 중계 노드 강제 이탈 시 재부팅 없이 **15.9초** 만에 메시 재구성
- **오탐 방어** — 통신두절과 실제 소손을 임종신호·이웃 투표·자기 온도로 구분
- 펌웨어(C++/painlessMesh) · 게이트웨이 추정기(Python) · 실시간 관제 대시보드(JS Canvas) 전 계층 구현, 테스트 60건

## 📫 Contact
- Email: bluepoint74@naver.com
