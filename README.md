# SNav

저시력자를 위한 스마트 내비게이션

주요 특징:
- 사용자의 실시간 위치 정보를 확인해 음성으로 길 안내
  - 음성 신호기가 있는 횡단보도로만 길을 안내함
- 큼지막한 글씨와 버튼과 고대비 색상을 사용한 저시력자를 위한 UI 사용

## 2023-05-21

- 12 + 1 개의 화면 (MainActivity.java , Activity_main.xml : 임시 화면 전환 테스트 용)
- figma 도구를 사용해 앱 화면 구성 설계
- 1차적으로 모든 화면을 벡터 이미지로 첨부 (❗변경 필요)
- 동적 기능이 필요하지 않은 화면은 벡터 이미지로 첨부 후 필요한 곳에 투명 버튼 배치
  - 인트로 화면 (activity_intro.xml)
  - 로그인 화면 (activity_login.xml)
  - 사용자 정보 및 설정 화면 (activity_setting.xml)

## To-do

- 지도 첨부 (activity_main_nav.xml) 및 동적 기능 구현
- 음성 신호기가 있는 횡단보도 아이콘 배치

## 구현 외 할 일

- 모든 화면 간의 관계도 제작
- 보고서 작성
- 발표 영상 제작 및 제출

## 화면 구성도

<img width="910" alt="image" src="https://github.com/dlwhsk0/SNav/assets/94193594/f1795832-aa09-4401-b6e1-6aed9d89a075">
