---
title: "파이썬을 활용한 데이터 분석 - Numpy [1]"
date: 2023-03-07 21:23 +0900
categories: [study, data analysis]
tags: [python, dataanalysis, pandas, numpy, jupyter, study]     # TAG names should always be lowercase
comments: true
---

# 1. Numpy(Numericlal Python)

- 파이썬 산술연산을 위한 필수적인 패키지
- 과학 계산을 위한 대부분 패키지는 Numpy 배열 객체를 데이터 교환을 위한 공통 언어처럼 사용
- Numpy 자체는 모델링 및 과학계산을 위한 기능 제공을 하지 않음.
<br>

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
 
### 기본적인 ndarray 처리
<iframe id="f1" name="f1" src="/domybest/assets/iframes/2023-03-07/01_basic_ndarray/">Jupyter Notebook</iframe><br>

### ndarray 생성
- 기본적으로 **np.array()**를 이용하여 생성
    - 명시적으로 자료형을 지정하지 않는 한 생성시 적절한 자료형 추론(dtype으로 확인)
- 다양한 ndarray 생성 함수를 이용한 생성
<iframe id="f2" name="f2" src="/domybest/assets/iframes/2023-03-07/02_generation_ndarray/">Jupyter Notebook</iframe><br>

### ndarray 산술연산
- ndarray는 for문이 필요 없이 데이터를 일괄 처리 가능 → 벡터화
- 같은 크기의 ndarray간 산술연산은 배열의 각 원소 단위로 적용됨
- 스칼라 값으로 연산할 경우 모든 원소에 스칼라 값이 적용
- 비교 연산의 경우 bool type을 갖는 ndarray 반환
<iframe id="f3" name="f3" src="/domybest/assets/iframes/2023-03-07/03_calculate_ndarray/">Jupyter Notebook</iframe><br>

- 크기가 다른 ndarray의 경우 브로드캐스팅을 이용헤 하는데 나중에 필요시 다시 기록해보겠다.