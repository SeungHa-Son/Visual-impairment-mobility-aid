# 🚶‍♂️ AI-based Mobility Assistance Device for the Visually Impaired

This project presents an AI-based mobility assistance device designed to enhance the safety of visually impaired pedestrians.
The system leverages cost-effective hardware and real-time object recognition to deliver text-to-speech (TTS) guidance, enabling users to perceive surrounding elements such as crosswalks, tactile paving, pedestrians, and vehicles.

---

## 🎥 Demo Video
[![Demo Video](https://img.youtube.com/vi/o0KDbAmzD5c/0.jpg)](https://www.youtube.com/watch?v=o0KDbAmzD5c&t=4s)

👉 클릭 시 실제 동작 시연 영상을 확인할 수 있습니다.

---

## 📌 Project Overview
- **프로젝트명**: 시각장애인 보행 보조 장치
- **과목**: 캡스톤디자인
- **목표**
  - 시각장애인의 보행 중 위험 요소를 실시간으로 인식
  - 음성 안내를 통해 보행 의사결정을 지원
  - 고가 장비 없이도 활용 가능한 **저비용·고효율 시스템** 구현

---

## 🧠 System Concept
본 프로젝트는 **카메라 기반 AI 비전 기술(YOLO)**을 활용하여  
보행 환경에서 중요한 시각 정보를 인식하고, 이를 **한국어 음성으로 즉시 안내**합니다.

### 주요 인식 대상
- 횡단보도
- 점자블록 (점형 / 선형)
- 차량
- 보행자
- 신호등

---

## ⚙️ System Architecture

### 🔹 Hardware
- Raspberry Pi 5  
- 1080p USB Camera  
- 휴대용 USB Speaker (음성 출력)  
- 보조 배터리(UPS)

### 🔹 Software
- **YOLOv5 / YOLOv8** 기반 객체 인식
- OpenCV 실시간 영상 처리
- Python 기반 AI 추론
- TTS(Text-to-Speech) 음성 안내

---

## 🔊 Key Features
- 실시간 객체 인식 기반 보행 보조
- 횡단보도 및 점자블록 인식 시 음성 안내
- 중복 음성 출력 방지를 위한 **쿨타임 로직 적용**
- 웨어러블 형태로 양손이 자유로운 착용 방식
- 기존 상용 제품 대비 **압도적인 가격 경쟁력**

---

## 💡 Strengths
- 💰 저비용 대비 높은 기능 완성도
- 🧠 실시간 AI 비전 기반 인식
- 🔊 직관적인 음성 피드백
- 👕 조끼 형태의 웨어러블 디자인으로 사용 편의성 향상

---

## 👥 Team
- 최호수  
- 장진우  
- 정대휴  
- **손승하**










