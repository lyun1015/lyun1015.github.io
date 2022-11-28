---
layout: post
title:  "Git/Github"
date:   2022-11-28 21:03:36 +0530
categories: Javascript NodeJS
---
Git은 오픈 소스 버전 관리 시스템이다. 로컬에서 버전을 관리하며 소프트웨어 개발 및 코드 관리에 사용한다. git은 본인의 코드와 그 수정내역을 기록하고 관리하도록 돕는 버전 관리 프로그램이며, 로컬에서 프로젝트의 기록을 스스로 관리할 수 있도록 해준다. git을 통해 브랜치를 생성하고 이전 브랜치로 복구, 삭제, 병합이 가능합니다. Github는 Git Repoditory를 위한 웹 기반 호스팅 서비스이다. 클라우드 서버를 사용해서 로컬에서 버전 관리한 소스코드를 업로드하여 공유 가능하다. 분산 버전 제어, 액세스 제어, 소스 코드 관리, 버그 추적, 기능 요청 및 작업 관리를 제공한다. github는 git 저장소를 관리하는 클라우드 기반 호스팅 서비스이다. git 저장소 호스팅 서비스는 클라우드 기반으로 다른사람과 소스코드가 공유가 가능하며 git의 기본적인 기능을 확장하여 제공한다.
```javascript
const Razorpay = require('razorpay');

let rzp = Razorpay({
	key_id: 'KEY_ID',
	secret: 'name'
});

// capture request
rzp.capture(payment_id, cost)
	.then(function (data) {
		return 2;
	})
```

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
