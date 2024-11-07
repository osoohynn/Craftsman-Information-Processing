_기억 장치 관리 전략의 종류_  
반입(Fetch)전략, 배치(Placement)전략, 교체(Replacement)전략

## 🎯 반입(Fetch) 전략
보조기억장치에 보관중인 프로그램이나 데이터를 **언제 주기억장치로 적재할 것인지**를 결정하는 전략
- 요구반입 (Demand Fetch)
  > 데이터 참조 요구를 할 때 적재하는 방법
- 예상 반입 (Anticipatory Fetch)
  > 참조될 데이터를 예상해서 적재하는 방법
<br>

## 🎯 배치(Placement) 전략
새로 반입되는 데이터나 프로그램을 주기억장치에 **어디에 위치시킬 것인지**를 결정하는 전략
- 최초적합 (First Fit)
  > 빈 영역 중 첫번째 영역에 배치
- 최적적합 (Best Fit)
  > 빈 영역 중 단편화(빈 기억 공간)를 가장 작게 남기는 곳에 배치
- 최악적합 (Worst Fit)
  > 빈 영역 중 단편화(빈 기억 공간)를 가장 크게 남기는 곳에 배치
<br>

## 🎯 교체(Replacement) 전략
주기억장치의 모든 영역이 이미 사용중일 때, 새로운 데이터나 프로그램을 **어느 영역을 교체하여 사용할 것인지** 결정하는 전략
- OPT (OPTimal replacement, 최적교체)
  > 가장 오랫동안 사용되지 않을 페이지를 교체
- FIFO (First In First Out)
  > 가장 먼저 들어와서 오래 있었던 페이지를 교체
- LRU (Least Recently Used)
  > 가장 오랫동안 참조되지 않은 페이지를 교체
- LFU (Least Frequently Used)
  > 사용 빈도가 가장 적은 패이지를 교체
- NUR (Not Used Recently)
  > 최근에 사용하지 않은 페이지를 교체
- MRU (Most Recently Used)
  > 사용 빈도가 가장 많은 페이지를 교체
