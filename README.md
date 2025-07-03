# 3D 시각화 기반 신축아파트 실내 하자 탐지 어플리케이션

신축 아파트 실내 공간을 스마트폰으로 촬영한 뒤,  
YOLO 기반 하자 탐지와 3D 재구성을 통해 하자 위치를 시각화하는 어플리케이션을 개발하였습니다.

---

## 📌 주요 기능

- 스마트폰 촬영 영상에서 하자 자동 탐지 (YOLOv5)
- NeRF / COLMAP 기반 3D 공간 재구성
- 탐지된 하자 위치를 3D로 시각화
- 안드로이드 앱 기반 사용자 인터페이스 제공

---

## 🛠 기술 스택

- Object Detection: YOLOv5
- 3D Reconstruction: NeRF, COLMAP, NICE-SLAM
- Mobile: Android (Kotlin)
- Server: FastAPI
- 기타: Git, VS Code, Google Drive

---

## 🗂 프로젝트 구조

```
AI_project/
├── 1. 주차별 발표자료/
├── 2. 소스코드/        ← (용량 제한으로 미포함)
├── 3. 보고서/
└── 4. 시연영상/        ← (용량 제한으로 미포함)
```

---


---

## 🔗 자료 링크 (Google Drive)

- 📁 [소스코드 & 시연영상 전체 자료](https://drive.google.com/drive/folders/1Axdyyon16MqmnYgIpVYU90w6bohW7AbA?usp=drive_link)

> GitHub 업로드 제한으로 인해 `.zip`, `.mp4` 등 대용량 파일은 Google Drive에 별도 제공됩니다.

---

## 👤 기여 내용

- 전체 파이프라인 기획 및 기술 구성
- 3D 매핑 구조 설계 및 테스트
- 앱 연동 및 UI 구성
- 발표자료 및 시연환경 구성

---

## 📝 참고

본 프로젝트는 청년 AI·빅데이터 아카데미 실습 과정의 결과물입니다.

