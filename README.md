# Ai-for-Trading-Project-3-Smart-Beta-and-Portfolio-Optimization

**Creating and optimizing a smart beta stock portfolio.**

이 프로젝트는 Udacity의 [AI For Trading](https://www.udacity.com/course/ai-for-trading--nd880)의 Project3 내용입니다.

## 개요
* 스마트 베타 포트폴리오를 만들고 퍼포먼스를 확인하기 위해 벤치마크 인덱스와의 Tracking Error를 계산한다.

* 포트폴리오의 가중치를 최적화시키기 위해서 Quadratic Programming을 사용한다.

* 포트폴리오를 리밸런싱하고 성과를 평가하기 위해 회전율을 계산하여, 최적 리배런싱 주기를 결정한다.

* 데이터셋은 Quotemedia에서 주식 종가를 set을 활용했다.

## 내용
* Numpy/Pandas 라이브러리를 사용하여 1) Dollar Volume 기반 및 2) 배당 수익률 기반 포트폴리오 가중치를 계산한다.

* 수익률, 가중치 수익률, 누적 수익률 그리고 Tracking Error를 계산하는 method를 작성한다.

* Convex 최적화 문제(Quadratic Programming)를 해결하기 위해 [CVXPY](http://www.cvxpy.org/) Python 라이브러리를 사용한다.

* 원하는 빈도로 포트폴리오 가중치를 재조정하고 이를 위한 비용 또는 연간 매출액을 반환하는 방법을 구현한다.

## Project3 - Jupyter Notebook
* [Project 3. Smart Beta and Portfolio Optimization](https://nbviewer.jupyter.org/gist/Hwanyy/6d51edd37a365d025df883d0ef8a4a27)

## 사용된 라이브러리들과 version (Dependencies)
* [requirements.txt](https://github.com/Hwanyy/Ai-for-Trading-Project-3-Smart-Beta-and-Portfolio-Optimization/blob/main/requirements.txt)
