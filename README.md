# MacBook git test
git 설치 </br>
```
brew install git
```

<br> GitHub 계정 설정
```
git config --global user.name "이름"
git config --global user.email "이메일"
```

---
### SSH key 생성하기
SSH key 생성
```
ssh-keygen
```

<br> SSH key 복사하기
```
cat ~/.ssh/파일명.pub
```

### GitHub에 SSH key 등록하기
Settings -> SSH and GPG keys -> New SSH key -> Key에 SSH key 붙여넣기 -> Add SSH key <br>
___
### Git
git 저장소 생성
```
git init
```

<br> 원격 저장소 연결
```
git remote add <원격 저장소 이름> git@github.com:<깃허브 이름>/<깃허브 레포지토리 이름>.git
예시) git remote add origin git@github.com:kim/MacBook.git
```

<br> README.md 파일 생성
```
touch README.md
```

<br> Staging area에 README.md 파일 추가
```
git add README.md
```

<br> commit
```
git commit -m "메시지"
```

<br> push
```
git push <원격 저장소 이름> <브랜치 이름>
예시) git push origin main
```

___
### Tip
원격 저장소 이름 확인
```
git remote
```

<br> 원격 저장소와 연결된 url 확인하기
```
git remote -v
```
