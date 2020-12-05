# 코딩 꿀팁 #


1. 이진 탐색 문제는 입력 데이터가 많거나, 탐색 범위가 매우 넓은 편이다. => 데이터의 크기가 1000만개 이상이거나 탐색 범위의 크기가 1000억 이상리면 이진 탐색 알고리즘을 의심하자.
- input()으로 받으면 동작 속도가 느리므로 sys라이브러리를 이용하자

import sys 

input_data = sys.stdin.readline().rstrip()

print(input_data)
