# 2024-산학프로젝트1

<div align="center">

![header](https://capsule-render.vercel.app/api?type=wave&color=&height=300&section=header&text=산학%20프로젝트1&fontSize=90)

*산학프로젝트1 MJU_2024_2*

*본 프로젝트는 AutoEncoder와 EIF Algorithm을 결합한 OES데이터의 새로운 이상탐지 기법을 제시합니다. 현재 학교에서는 반도체 8대공정 중, Oxidation 공정에서의 광스펙트럼을 진단하는 장치인 OES센서 데이터를 unsupervised learning 기반의 Extended Isolation Forest(EIF)를 사용하여 이상탐지를 진행하고 있었습니다. 기존의 방식보다 더 효율적인 방법으로 개선하기 위해 OES데이터를 AutoEncoder를 통해 낮은 차원의 데이터로 가공한 뒤에 EIF알고리즘을 활용하는 방안을 제안하여 개발하게 되었습니다.*


</div>
<br/>
<br/>

## 목차
  - [프로젝트 개요](#프로젝트-개요)
  - [시작 가이드](#시작-가이드)
  - [기술 스택](#기술-스택)
  - [주요 기능](#주요-기능)
  - [참고 문헌](#참고-문헌)

<br/>
<br/>

## 프로젝트 개요
- 프로젝트 이름 : AutoEncoder와 EIF를 활용한 OES 데이터 결함탐지
- 프로젝트 개발기간 : 2024.09-2024.12
- 개발 언어 : Python & Pytorch
- 팀 멤버 : 팀 OYES (조우진, 김민혁, 조민기)

<br/>
<br/>

## 시작 가이드
```
pip install -r requirements.txt
```
<br/>
<br/>

## 기술 스택
- Python, Pytorch, Pandas, Numpy, Matplotlib
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



