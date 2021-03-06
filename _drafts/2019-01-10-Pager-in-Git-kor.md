---
layout: post
categories: articles
title:  "Git"
excerpt: "Git 문서에 담겨있는 정체불명의 단어들"
tags: [git]
date: 2019-01-10 17:42:25
modified: 2019-01-10 17:42:25
image: 
  feature:
  credit:
  creditlink:
share: true
sitemap: false
---

깃의 공식 문서를 영문으로 읽다보면 사전을 봐도 도무지 이해가 안 되는 단어들이 가끔씩 나옵니다. 예를 들어 `git rev-parse` 명령어의 문서를 살짝 엿보면 다음과 같이 되어 있습니다.

> DESCRIPTION
> Many Git porcelainish commands take mixture of flags (i.e. parameters that begin with a dash -) and parameters meant for the underlying git rev-list command they use internally and flags and parameters for the other commands they use downstream of git rev-list. This command is used to distinguish between them.

```
porcelainish
```

...???

오늘은 사전에도 잘 나오지 않는 이 단어가 무엇인지 알아보겠습니다.

## Porcelain, Plumbing


## Reference

* [https://linux.die.net/man/1/git-config](https://linux.die.net/man/1/git-config)
* [https://wayhome25.github.io/git/2017/04/01/git-cat/](https://wayhome25.github.io/git/2017/04/01/git-cat/)
* [https://stackoverflow.com/questions/11868447/how-can-i-remove-an-entry-in-global-configuration-with-git-config](https://stackoverflow.com/questions/11868447/how-can-i-remove-an-entry-in-global-configuration-with-git-config)