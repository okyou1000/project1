# Project 1



## (1) 다음과 같은 배열을 만들어라.

```python
array([[   0.,    0.,    0.,    1.,    1.],
       [   0.,    0.,    0.,    1.,    1.],
       [   0.,    0.,    0.,    1.,    1.],
       [  10.,   20.,   30.,   40.,   50.],
       [  60.,   70.,   80.,   90.,  100.],
       [ 110.,  120.,  130.,  140.,  150.],
       [   0.,    0.,    0.,    1.,    1.],
       [   0.,    0.,    0.,    1.,    1.],
       [   0.,    0.,    0.,    1.,    1.],
       [  10.,   20.,   30.,   40.,   50.],
       [  60.,   70.,   80.,   90.,  100.],
       [ 110.,  120.,  130.,  140.,  150.]])
```



## (2) 다중 인덱스 참조 연습

```python
Cidx1	A	              B
Cidx2	C1	C2	C1	C2
0	1.76	0.40	0.98	2.24
1	1.87	-0.98	0.95	-0.15
2	-0.10	0.41	0.14	1.45
3	0.76	0.12	0.44	0.33
4	1.49	-0.21	0.31	-0.85
```

- 위와 같은 구조의 데이터프레임을 제작하시오.
- B, C1 참조하시오.
- 0번 행,  B,C1  값을 참조하시오.
- 0번행 B, C1 값을 100으로 변경하시오.



## (3) 연관규칙 연습 데이터셋

```python
dataset =
1         계란, 우유
2         계란, 기저귀, 맥주, 사과
3         우유, 기저귀, 맥주, 콜라
4         계란, 우유, 맥주, 기저귀 
5         계란, 우유, 맥주, 콜라
```

위 데이터를 저장하고,  X={계란, 맥주}, Y={기저귀} 인 경우에 대해 다음을 구하시오.

- 지지도 계산
- 신뢰도 계산
- 향상도 계산