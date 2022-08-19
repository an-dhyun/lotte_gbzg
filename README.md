# 롯데멤버스 빅데이터 경진대회
#### 팀 안다비젼✨

---
## 📍 주제
      온라인 상품 판매량 증진을 위한 추천 시스템 개발 및 개인화 마케팅 전략 제안을 제시한 프로젝트
      고객의 구매 성향을 군집화하여 정의한 고객 세그먼트별로 적용할 연관 상품 홍보 전략 제시 및 더 나아가 개인화된 상품 및 쿠폰을 추천하는 전략을 제안

## 📍 전체 실행 프로세스
#### 1. 탐색적 자료분석 (EDA)
- 오프라인 및 온라인 구매 경향
- 날짜에 따른 상품 구매 현황
- 시간에 따른 상품 구매 현황
- Cohort 분석 기반 고객 리텐션 분석
- 재주문 거래 형태
- 상품 소분류별 재주문까지 걸린 기간
- 인구 특성별 재구매 고객 비율

#### 2. 군집화 분석
- 고객 세그먼트 분석
- 묶음 구매 분석
- RFM 분석
- 고객 세분화
- VIP 고객 분석

#### 3. 추천시스템 구현
- DNN 데이터 분리
- GNN 데이터 분리
- 상품 추천시스템 전처리 및 모델링
- 쿠폰 추천시스템 전처리 및 모델링

<br>

## 📍 Structure
```python
안다비젼 
├── README.md
├── 1. 안다비젼_분석보고서
│    └───안다비젼.pdf
│          
└── 2. 안다비젼_분석코드
     ├─── EDA
     │     ├─── Raw EDA.ipynb
     │     └─── Derived EDA.ipynb
     ├─── Clustering
     │     ├─── Segment.ipynb
     │     └─── RFM.ipynb
     ├─── Recommender system
     │     ├─── data_split_DNN.ipynb
     │     ├─── data_split_BGCN.ipynb
     │     ├─── DNN.ipynb
     │     └─── BGCN.ipynb
     ├─── Reference/BGCN-model
     └─── MetaData.txt

```
<br>

## 📍 개발 환경 및 라이브러리 버전
      각 분석 코드에 작성되어 있습니다.
      
<br>

## 📍 Presentation
저희 프로젝트에 대해 자세하게 알고 싶으시다면, 프로젝트 설명자료를 참고해주세요.
* [![GoogleDrive Badge](https://img.shields.io/badge/Presentation-405263?style=flat-square&logo=Quip&link=https://drive.google.com/file/d/1wkLDchFS6nExMgtldQYKGfVSP6YOjCl-/view?usp=sharing)](https://dguackr-my.sharepoint.com/:b:/g/personal/wlguni_dgu_ac_kr/EYidNeN8JoVMjFR8hUgZ5OsBhma9dxTOdEpLmFiKWp4YLQ?e=PzeZqM)

<br>

## 📍 Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/jihyeon4028"><b>박지현</b></sub></td>
    <td align="center"><a href="https://github.com/an-dhyun"><b>안도현</b></sub></td>
</table>

<br>

## 📍 Citation
```python
@inproceedings{BGCN20,
  author    = {Jianxin Chang and 
               Chen Gao and 
               Xiangnan He and 
               Depeng Jin and 
               Yong Li},
  title     = {Bundle Recommendation with Graph Convolutional Networks},
  booktitle = {Proceedings of the 43nd International {ACM} {SIGIR} Conference on
               Research and Development in Information Retrieval, {SIGIR} 2020, Xi'an,
               China, July 25-30, 2020.},
  year      = {2020},
}
```
