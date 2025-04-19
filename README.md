# 송도 국제도시 아파트 실거래가 분석 및 입지 추천

## 📌 프로젝트 개요  
인천 송도국제도시의 아파트 실거래 데이터를 활용해 다음 세 가지 목표를 달성합니다:  
1. **가격 변동 분석**  
   - 연도별·월별 거래 건수와 평균가 추이 시각화  
   - GTX 개통, 금리 변동, 정책 변수 등 외부 요인의 영향 탐색  
2. **가격 예측 모델 개발**  
   - 타깃: 로그 변환된 거래가격(`log_dealAmount`)  
   - 모델: OLS, Ridge, Lasso, ElasticNet 등을 비교  
   - 특성 해석: 변수 중요도 분석 및 해석 가능성 확보  
3. **입지 추천 시스템 구현**  
   - 실거주자·투자자 페르소나별 가중치 반영 점수 산정  
   - Folium 기반 지도·Heatmap 시각화  
   - 상위 단지 추천 및 유사 입지 분석  

---

## ✨ 주요 기능  
- **EDA(탐색적 데이터 분석)**: 거래량·가격 분포, 클러스터링, 상관관계 분석  
- **모델링**: 다중공선성(VIF), 하이퍼파라미터 튜닝, 교차검증  
- **입지 추천**: 회귀 계수 기반 가중치 + 유사 입지 탐색  
- **시각화**: Matplotlib/Seaborn 차트, Folium 지도(HTML)  

---

## 🗂️ 데이터 설명  
- **rename_final_df_with_prediction.csv**  
  - 위치(위도·경도), 전용면적, 층수, 브랜드, 정책·경제 지표  
  - `predicted_log_price` 컬럼: 예측된 로그 가격  

---

## 📦 의존 패키지  
- Python ≥3.8  
- pandas, numpy, scikit-learn  
- matplotlib, seaborn  
- folium  
- jupyter (notebook/lab)  

---

## 📞 연락처  
- 작성자: 강성민  
- GitHub: [Kangsungmin00](https://github.com/Kangsungmin00)  
- LinkedIn: linkedin.com/in/강성민  

---

## 📄 라이선스  
MIT License © 2025 강성민  
