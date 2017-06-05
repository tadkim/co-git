# co-git 입니다.
충돌을 수정한 후 push

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
git status
```
변경후 입력한 `git status`의 결과는 다음과 같다.
```
Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   readme.md
```
stage에 변경된 사항이 추가가 되었다. 또한, commit 할 준비가 다 되었다고나온다.

```
git commit -m "first commit"
```
`git commit -m "입력내용"`을 통해 변경사항에 대한 간단한 요약설명을 적어준다. 


```
git push origin master
```
이건 이후에 branch 생성 후에 이렇게도 쓸 수 있다.

```
git push origin [push할 브런치명]
git push origin develop
git push origin feature
```


