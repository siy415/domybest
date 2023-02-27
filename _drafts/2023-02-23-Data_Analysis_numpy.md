---
title: "파이썬을 활용한 데이터 분석 - Numpy"
date: 2023-02-22 09:52 +0900
categories: [study, data analysis]
tags: [python, dataanalysis, pandas, numpy, jupyter, study]     # TAG names should always be lowercase
comments: true
img_path: /assets/img/post/2023-02-22/
iframe_path:
---

# 1. Numpy(Numericlal Python)
- 파이썬 산술연산을 위한 필수적인 패키지
- 과학 계산을 위한 대부분 패키지는 Numpy 배열 객체를 데이터 교환을 위한 공통 언어처럼 사용
- Numpy 자체는 모델링 및 과학계산을 위한 기능 제공을 하지 않음.
## 제공 기능
- 다차원 배열 ndarray : 빠른 배열 계산 및 broadcasting 기능 제공
- 반복문 없이 전체 데이터 배열 계산 가능 (표준 수학 함수)
- 배열 데이터를 읽거나 쓰는 기능 + 메모리에 적재된 파일 컨트롤
- 선형대수, 난수 생성, 푸리에 변환 기능 제공
- C, C++ 코드와 연동 가능한 API 제공
<br>
<br>


## 1-1. ndarray
- Numpy의 N차원 배열 객체
- 대귬모 데이터 집합을 담을 수 있는 빠르고 유연한 자료구조.
- 스칼라 원소 간의 연산에 사용하는 문법과 비슷한 방식을 사용 → 수학적인 연산 수행 가능
<br>
<br>

### 기본적인 ndarray 처리
<iframe id="f1" name="f1" src="/assets/iframes/jupyternotebook/test.html">Jupyter Notebook</iframe>