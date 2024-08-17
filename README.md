# Hang Man Game


>**Note:**
>* git 사용에 익숙해 지기 위해 간단한 코드를 만들어 업로드하게되었습니다.
>* "Hang man"은 글자수를 제시하면 10번의 기회안에 그 글자를 맞추는 게임입니다.

## Overview

![Hang_man](https://github.com/shj96227/Hang_man/assets/155954077/2db823a4-d496-4512-931d-a9affaef9ffc)


## Dependencies

[python3](https://phoenixnap.com/kb/how-to-install-python-3-ubuntu) 를 사용하며 운영 체제는 Ubuntu이다.

## Getting Started
### 1. Clone

이 repository를 clone 한다.
([How to "git clone" including submodules?](https://stackoverflow.com/questions/3796927/how-to-git-clone-including-submodules))

```sh
cd .
mkdir hang_man
cd hang_man
git clone https://github.com/shj96227/Hang_man.git
```

### 2. Run file

행맨 파일을 실행한다.
```sh
python3 Hang_man.py
```

### 3. Input the word

제시된 글자 수와 힌트를 보고 10번의 기회 안에 글자를 맞추면 된다.

## 기타
resource 폴더의 word_list.csv 파일에서 추가할 수 있다.

windows를 사용할 경우 Hang_man.py에서 사운드를 winsound로 수정하면 사용할 수 있다.