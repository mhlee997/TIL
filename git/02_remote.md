# 원격저장소(remote repository) 활용 기초

> 다양한 원격저장소 서비스 중에 Github을 기준으로 설명

## 준비사항

* Github에 비어있는 저장소(repository)를 만든다.

## 기초 명령어

### 1. 원격저장소 설정

```bash
$ git remote add origin __url__
```

* 깃, 원격저장소(remote)를 추가(add), origin이라는 이름으로 URL!
* 설정된 원격저장소를 확인하기 위해서는 아래의 명령어를 입력한다.

```bash
$ git remote -v
origin  https://github.com/mhlee997/practice.git (fetch)
origin  https://github.com/mhlee997/practice.git (push)
```







