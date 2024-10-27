# 2024-산학프로젝트1

<div align="center">

![header](https://capsule-render.vercel.app/api?type=wave&color=&height=300&section=header&text=산학%20프로젝트1&fontSize=90)



</div>
<br/>
<br/>

## 목차
  - [프로젝트 개요](#프로젝트-개요)
  - [시작 가이드](#시작-가이드)
  - [기술 스택](#기술-스택)
  - [주요 기능](#주요-기능)
  - [기타 추가 사항들](#기타-추가-사항들)

<br/>
<br/>

## 프로젝트 개요
- 프로젝트 이름 : AutoEncoder와 EIF를 활용한 OES 데이터 결함탐지
- 프로젝트 개발기간 : 2024.09-2024.12
- 개발 언어 : Python & Pytorch
- 팀 멤버 : 팀 @@@(조우진, 김민혁, 조민기)

<br/>
<br/>

## 시작 가이드
```
pip install -r requirements.txt
```
<br/>
<br/>

## 기술 스택
- python, pytorch, pandas, Numpy, Matplotlib
<br/>
<br/>

## 주요 기능
- OES(Optical Emission Spectroscopy)센서 데이터를 Oxidation 공정에서 실시간으로 장비의 센서 데이터를 모니터링하고 결함을 탐지하고, 발생하는  이상을 식별하는  FDC(Fault Detection & Classification)의 효율을 오토인코더를 사용하여 개선합니다.
- 오토인코더를 사용하여 데이터의 차원을 낮은 차원으로 변경한 뒤에 EIF 알고리즘을 활용하여 이상을 탐지하는 방식입니다.
  
<br/>
<br/>

## 참고 문헌
- Hyukjoon Kwon, Sang Jeen Hong, Use of Optical Emission Spectroscopy Data for Fault Detection of Mass Flow Controller in Plasma Etch Equipment, Electronics 2022 11(2)
- Mahmood K. M. Almansoori , Miklos Telek , Anomaly Detection using combination of Autoencoder and Isolation Forest, Department of Networked Systems and Services, Technical University of Budapest, Budapest, Hungary
- sahandha 외 4인, Extended Isolation Forest for Anomaly Detection, url: https://github.com/sahandha/eif



