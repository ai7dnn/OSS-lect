## Git 설정 파일을 직접 수정하는 방법

#### 다음 파일을 편집해서 샘플파일 내용을 복사 후 저장, 다시 git bash 실행
```
$ git config --global core.editor 'code --wait'
$ code ~/.gitconfig
```

## Git bash에서 설정하는 방법

#### 사용자 설정
```bash
$ git config --global user.name "User name"
$ git config --global user.email "himanshudubey481@gmail.com"
```

#### 편집기 설정
```bash
$ git config --global core.editor 'code --wait'
```

#### 축약 별칭 명령어
- $ git config --global alias.<단축_명령어> <실제_명령어>
```bash
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
$ git config --global alias.sts 'status -s'
$ git config --global alias.sh show
$ git config --global alias.lg log
$ git config --global alias.lg1 'log --oneline'
$ git config --global alias.lgg 'log --graph'
$ git config --global alias.lgg1 'log --graph --oneline '
$ git config --global alias.lga log --all
$ git config --global alias.lg1a 'log --oneline --all'
$ git config --global alias.lgga 'log --graph --all'
$ git config --global alias.lgg1a 'log --graph --oneline --all'

```

#### CR(Carriage-Return)과 LF(Line Feed) 문자
Windows에서 개발하는 동료와 함께 일하면 라인 바꿈(New Line) 문자에 문제가 생긴다. Windows는 라인 바꿈 문자로 CR(Carriage-Return)과 LF(Line Feed) 문자를 둘 다 사용하지만, Mac과 Linux는 LF 문자만 사용한다. Git은 커밋할 때 자동으로 CRLF를 LF로 변환해주고 반대로 Checkout 할 때 LF를 CRLF로 변환해 주는 기능이 있다. core.autocrlf 설정으로 이 기능을 켤 수 있다. Windows에서 이 값을 true로 설정하면 Checkout 할 때 LF 문자가 CRLF 문자로 변환된다. 이 설정을 이용하면 Windows에서는 CRLF를 사용하고 Mac, Linux, 저장소에서는 LF를 사용할 수 있다.
```bash
$ git config --global core.autocrlf true  #window
$ git config --global core.autocrlf input #mac
$ git config --global core.safecrlf false
```

#### 설정 취소
```bash
$ git config --global --unset <이름>
```

#### 설정 보기
```bash
$ git config --global -list
```

