
```python

within_range_criteria = [nodePositon[0] > (len(maze) - 1),
	nodePosition[0] < 0,
	nodePosition[1] > (len(maze[len(maze) - 1]) - 1),
	nodePosition[1] < 0,
	]

if any(within_range_criteria):
	continue
```
### 반복문 응용 
(반복문 사용 시 몇 번째 반복문인지 확인이 필요할 수 있습니다. 이때 사용합니다.
인덱스 번호와 컬렉션의 원소를 tuple형태로 반환합니다.
```python
t = [1, 5, 7, 33, 39, 52]
for p in enumerate(t):
...print(p)
... 
(0, 1)
(1, 5)
(2, 7)
(3, 33)
(4, 39)
(5, 52)

for i, v in enumerate(t):
...print("index : {}, value: {}".format(i,v))
... 
index : 0, value: 1
index : 1, value: 5
index : 2, value: 7
index : 3, value: 33
index : 4, value: 39
index : 5, value: 52
```

### 리스트활용
1. pop(x)는 리스트의 x번째 요소를 돌려주고 그 요소는 삭제한다. pop()은 리스트의 맨 마지막 요소를 돌려주고 그 요소는 삭제한다.
```python
a = [1,2,3]
>>> a.pop(1)
2
>>> a
[1, 3]
```
2. 리스트 역순으로 만들기
```python
t = [1,5,7,33,39,52]
reverse_t = t[::-1]
```
