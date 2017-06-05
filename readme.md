# co-git 입니다.


```
git clone https://github.com/tadkim/co-git.git
cd co-git
```

readme.md 파일의 제목을 에디터에서 수정해본다.

```
# co-git 입니다.
# co-git
```

```
git status
```
`git status`의 결과는 다음과 같다.
```
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        readme.md

nothing added to commit but untracked files present (use "git add" to track)
```

```
git add .
```
`git add .`는 수정한 파일을 모두 stage에 올려 놓는 명령어다.

```
git state
```