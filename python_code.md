
```python

within_range_criteria = [nodePositon[0] > (len(maze) - 1),
	nodePosition[0] < 0,
	nodePosition[1] > (len(maze[len(maze) - 1]) - 1),
	nodePosition[1] < 0,
	]

if any(within_range_criteria):
	continue
```
