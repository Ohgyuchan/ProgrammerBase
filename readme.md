# Programmer Base

# GBC (Ghost Base Camp) 1주차 과정

한동대학교 컴퓨터보안 동아리 **GHOST** 에서 신입기수를 대상으로 진행하는 **GBC** 의 `1` 번째 과정을 진행하기 위한 내용을 담은 레포지토리입니다. 

## inspired by

이 프로젝트는 **MIT** 의 **[Missing Semetser](https://missing.csail.mit.edu/)** 에서 영감을 받아서 만들어졌습니다. **Missing Semeter** 의 서문은 다음과 같이 프로그래머들이 컴퓨터 공학적 지식을 배우는데에는 많은 배움을 얻을 수 있지만, 정작 그들이 수많은 시간을 쏟게 되는 툴과 툴을 효율적으로 사용할 수 있는 방법에 대한 적절한 리드를 받을 수 없었던 상황을 지적합니다. 

> Classes teach you all about advanced topics within CS, from operating systems to machine learning, but **there’s one critical subject that’s rarely covered, and is instead left to students to figure out on their own: proficiency with their tools.** We’ll teach you how to master the command-line, use a powerful text editor, use fancy features of version control systems, and much more!

> Students spend hundreds of hours using these tools over the course of their education (and thousands over their career), so **it makes sense to make the experience as fluid and frictionless as possible.** Mastering these tools not only enables you to spend less time on figuring out how to bend your tools to your will, but it also lets you solve problems that would previously seem impossibly complex.

하지만 기존 GBC 의 진행과정인 **Linux** 의 내용을 어느정도 담고 있어야 하고 **5일** 이라는 제한된 시간 조건도 고려해야 했기 때문에 이 레포지토리는 _"프로그래머의 기본"_ 이라는 거창한 이름을 달고 있는 것과 달리 **부족한 제가 주관적으로 선정한** 프로그래밍을 할 때 필요한 여러가지 내용들을 담고 있습니다. 

## Notice 

- 모든 내용은 출처를 명시하였습니다. 

- 잘못된 내용에 대한 지적은 항상 환영합니다. 

- 본 내용들은 누구나 자유롭게 무료로 학습할 수 있습니다. 한동대 컴퓨터보안 동아리 고스트원이 아니라도 본 내용들이 도움이 된다면 누구나 자유롭게 학습하고 즐겨주시면 됩니다. 

- 본문에서 말하는 "교재" 란 

  <div align="center">
  
  [<img src="https://bookthumb-phinf.pstatic.net/cover/077/993/07799304.jpg" width="30%" height="auto">](https://book.naver.com/bookdb/book_detail.nhn?bid=7799304)

  </div>

  를 뜻합니다. 

### 읽는 법

- **N 번째** 날에는 **Day N** 을 **정독** 하면 됩니다. 

- 다음의 표시가 있는 코드 부분은 실제로 직접 실행해보면 실습하면 됩니다. 

  ##### **<div align="center"> ⬇ EXECUTE! ⬇ </div>**

  ```shell
  $ (execute-me)
  ```

### 읽지 않는 법 

- 맥락에서 약간 벗어나지만 나름대로 필요한 내용은 

  > (맥락에서 약간 벗어나지만 나름대로 필요한 내용)

  으로 표시했습니다. 이 부분은 시간절약을 위해 아예 안봐도 됩니다.

- 몇몇 파트에서 **요약**을 하면 편리하겠다 싶은 부분을 요약정리를 했는데

  자신에게 필요없다 싶으면 시간절약을 위하여  넘겨도 됩니다.

- 만약

  ##### **<div align="center"> ⬇ EXECUTE! ⬇ </div>**

  가 없는 코드 부분은 굳이 실행하지 않아도 되고 실행해도 됩니다. 시간 절약을 위하여 넘겨도 됩니다. 

## Contents

### [Day 1](01-Day1/readme.md)

- [Docker](https://github.com/ccss17/ProgrammerBase/tree/master/01-Day1#docker)

- [도커 요약](https://github.com/ccss17/ProgrammerBase/tree/master/01-Day1#%EB%8F%84%EC%BB%A4-%EC%9A%94%EC%95%BD)
  
- [리눅스 교재](https://github.com/ccss17/ProgrammerBase/tree/master/01-Day1#%EB%A6%AC%EB%88%85%EC%8A%A4-%EA%B5%90%EC%9E%AC)


### [Day 2](02-Day2/readme.md)

- [리눅스 교재 ](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#%EB%A6%AC%EB%88%85%EC%8A%A4-%EA%B5%90%EC%9E%AC)

- [Stackoverflow Survey](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#stackoverflow-survey)

- [Git](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#git)

- [Github](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#github)

- [VSCode](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#vscode)

- [Markdown ](https://github.com/ccss17/ProgrammerBase/tree/master/02-Day2#markdown)

### [Day 3](03-Day3/readme.md)

- [리눅스 교재](https://github.com/ccss17/ProgrammerBase/tree/master/03-Day3#%EB%A6%AC%EB%88%85%EC%8A%A4-%EA%B5%90%EC%9E%AC)

- [vim](https://github.com/ccss17/ProgrammerBase/tree/master/03-Day3#vim)

- [tmux](https://github.com/ccss17/ProgrammerBase/tree/master/03-Day3#tmux)

### [Day 4](04-Day4/readme.md)

- [CLI](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#cli)

- [CLI 업그레이드하기](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#cli-%EC%97%85%EA%B7%B8%EB%A0%88%EC%9D%B4%EB%93%9C%ED%95%98%EA%B8%B0)

- [더 빨라진 git](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#%EB%8D%94-%EB%B9%A8%EB%9D%BC%EC%A7%84-git)

- [`bash` ➜ `zsh` - 더 빨라진 쉘](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#bash--zsh---%EB%8D%94-%EB%B9%A8%EB%9D%BC%EC%A7%84-%EC%89%98)

- [더 빨라진 tmux](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#%EB%8D%94-%EB%B9%A8%EB%9D%BC%EC%A7%84-tmux)

- [더 빨라진 vim](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#%EB%8D%94-%EB%B9%A8%EB%9D%BC%EC%A7%84-vim)

- [VSCode 업그레이드 ](https://github.com/ccss17/ProgrammerBase/tree/master/04-Day4#vscode-%EC%97%85%EA%B7%B8%EB%A0%88%EC%9D%B4%EB%93%9C)

### [Day 5](05-Day5/readme.md)

- [Git 과 Github 못다한 이야기](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#git-%EA%B3%BC-github-%EB%AA%BB%EB%8B%A4%ED%95%9C-%EC%9D%B4%EC%95%BC%EA%B8%B0)

  - [Git Branching](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#git-branching)

  - [user.github.io](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#usergithubio)

  - [gist](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#gist)

  - [Pull Request](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#pull-request)

- [좋은 정보 얻기](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#%EC%A2%8B%EC%9D%80-%EC%A0%95%EB%B3%B4-%EC%96%BB%EA%B8%B0)

  - [Awesome Repository](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#awesome-repository)

  - [Hacker News](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#hacker-news)

  - [Reddit ](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#reddit)

  - [Github trending](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#github-trending)

  - [Stackoverflow Survey]()

  - [검색](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#%EA%B2%80%EC%83%89)

- [리눅스 교재](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#%EB%A6%AC%EB%88%85%EC%8A%A4-%EA%B5%90%EC%9E%AC)

- [Funny CLI ](https://github.com/ccss17/ProgrammerBase/tree/master/05-Day5#funny-cli)

## Rule

GBC 참여자들은 **PASS** 와 **FAIL** 에 관련된 내용이니 다음의 룰을 꼭 확인해주세요. 

- **PASS** 기준(작성중)

  - 과제 

  - 지각과 결석 

  - 발표 

- 발표자 랜덤 선정 

- 지각/결석 규칙(작성중)

  - 코로나 때문에 화상회의로 할건데 어떠케 할까

## Rule

GBC 참여자들은 **PASS** 와 **FAIL** 에 관련된 내용이니 다음의 룰을 꼭 확인해주세요. 

- **PASS** 기준(작성중)

  - 과제 

  - 지각과 결석 

  - 발표 

- 발표자 랜덤 선정 

- 지각/결석 규칙(작성중)

  - 코로나 때문에 화상회의로 할건데 어떠케 할까
