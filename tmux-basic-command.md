# TMUX

Terminal MUltipleXer

## Intro

터미널 다중화 장치  
터미널 Session 관리와 Window를 Pane으로 다중 분할하여 병렬적 처리에 도움을 준다.

Prefix

```bash
Ctrl + b
```

모든 tmux 명령어 앞에 해당 `Ctrl + b` prefix를 붙인다. (tmux 명령어 임을 선언한다)


## Session

tmux를 이루는 가장 큰 단위 여러 윈도우로 구성


### 명령어

Session

```bash
# 생성
$ tmux new-session -s ${session name}

# Detached
d

# Attached
$ tmux a -t ${session name}

a
```

목록

```bash
$ tmux list-sessions
$ tmux ls

s 
```

이름 변경

```bash
$
```

제거

```bash
Session상에 존재하는 모든 Window 제거

$ tmux kill-session -t ${session name}
```

## Window

사용자에게 보여지는 한 터미널 화면  
다중 Pane을 가지며 Session에 종속된다


### 명령어

생성

```bash
c
```

이름 변경

```bash
,
```

이동

```bash
# Next
n

# Previous
p

# Window Number
0
```

제거

```bash
# 해당 윈도우의 Pane을 모두 제거
```


## Pane 

하나의 윈도우에서 분할된 화면  
각 틀은 독립적인 하나의 터미널


### 명령어

분할

```bash
# 수평 분할
%

# 수직 분할
"

# 사이즈 크기 조절
# (prefix 입력시 Ctrl을 유지)
Ctrl + 방향키
```

제거

```bash
x
```

확대 Zoom in/out

```bash
z
```
