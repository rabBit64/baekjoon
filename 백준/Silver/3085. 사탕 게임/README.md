##### 처음
완전탐색스러웠음. 50개니까   
행,열에서 연속된 갯수 세는게 처음에 약간 헷갈림   
현재위치,이전위치 같으면 누적합, 다르면 초기화   
맥스는 그때마다 저장해두고   
로우,콜 순서 바뀌면 가로부터 보는거에서 세로부터 볼수있음   
+그리고 이차원 배열 입력받는거
arr = [list(input()) for _ in range(N)] 깰끔

# [Silver III] 사탕 게임 - 3085 

[문제 링크](https://www.acmicpc.net/problem/3085) 

### 성능 요약

메모리: 30616 KB, 시간: 2628 ms

### 분류

브루트포스 알고리즘(bruteforcing), 구현(implementation)

### 문제 설명

<p>상근이는 어렸을 적에 "봄보니 (Bomboni)" 게임을 즐겨했다.</p>

<p>가장 처음에 N×N크기에 사탕을 채워 놓는다. 사탕의 색은 모두 같지 않을 수도 있다. 상근이는 사탕의 색이 다른 인접한 두 칸을 고른다. 그 다음 고른 칸에 들어있는 사탕을 서로 교환한다. 이제, 모두 같은 색으로 이루어져 있는 가장 긴 연속 부분(행 또는 열)을 고른 다음 그 사탕을 모두 먹는다.</p>

<p>사탕이 채워진 상태가 주어졌을 때, 상근이가 먹을 수 있는 사탕의 최대 개수를 구하는 프로그램을 작성하시오.</p>

### 입력 

 <p>첫째 줄에 보드의 크기 N이 주어진다. (3 ≤ N ≤ 50)</p>

<p>다음 N개 줄에는 보드에 채워져 있는 사탕의 색상이 주어진다. 빨간색은 C, 파란색은 P, 초록색은 Z, 노란색은 Y로 주어진다.</p>

<p>사탕의 색이 다른 인접한 두 칸이 존재하는 입력만 주어진다.</p>

### 출력 

 <p>첫째 줄에 상근이가 먹을 수 있는 사탕의 최대 개수를 출력한다.</p>

