# Dijkstra 알고리즘

## Time Complexity

- 우선 모든 노드를 한 번 쭉 돌면서 edge를 통해 인접 노드 정보를 업데이트 => `O(V)`

- 모든 edge를 탐색하면서 (=`O(E)`) heap 자료구조를 사용하는 priority queue에 의해 가중치를 업데이트 (=`O(logV)`)

> O(E) = O(VN)
>
> - V: vertices 수
> - N: 하나의 노드에 연결된 최대 edge 개수

- 따라서 시간복잡도는 `O(V + ElogV)`이다.
