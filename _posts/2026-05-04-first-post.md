---
title: 마크다운 사용해보기
date: 2026-05-04 20:55:00 +0900
last_modified_at: 2026-05-05 21:47:00 +0900
categories: [마크다운, 공부]
tags: [markdown]
---

## 마크다운 문법 사용해보기

### # 헤더
- 1부터 6까지만 지원
- 앞에 #을 붙여서 사용
- ex) # This is a H1

# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6

<br>

### # 강조

기울임(이텔릭체)는 *별 기호(Asterisks)* `*기울임*` 혹은 _언더바 기호(Underscore)_ `_기울임_` 를 사용

굵게는 **별 기호(asterisks)** `**굵게**` 혹은 __언더바 기호(underscore)__ `__굵게__` 를 2번씩 사용

__*이텔릭체*와 두껍게__ 를 혼용 가능 `__* *__`

취소선은 ~~물결 기호(tilde)~~ `~~취소선~~` 를 사용

<u>밑줄</u>은 마크다운에서 지원하지 않기에, 직접 `<u></u>` 태그를 사용

<br>

### # 목록
#### 순서 있는 목록
숫자와 점 `1. ~`을 사용

1. 첫번째
2. 두번째
3. 세번째

첫번째 숫자를 기준으로 무조건 내림차순으로 정의됨

#### 순서 없는 목록
`-`를 사용 (`- 테스트`)

- 테스트1
- 테스트2

<br>

### # 체크박스
대괄호`[ ]` 안에 `공백`이나 `x(체크)`를 입력

- [x] x를 넣었을 경우
- [ ] 공백으로 둘 경우

<br>

### # 링크
`[이름](링크주소)`

`예시: [구글](https://google.com)`

[구글](https://google.com)

`[이름](링크주소 "설명") [설명은 링크 위에 마우스 커서를 올리면 보임]`

`예시: [Google](https://google.com) "구글의 사이트로 이동"`

[Google](https://google.com "구글의 사이트로 이동")

참조 링크를 그대로 사용하고 싶은 경우

URL을 그대로 붙여넣거나 URL을 < > 안에 감싸서 사용

구글 홈페이지: <https://google.com>

`[이름][참조]`

`예시: [구글][google link]`

`[참조]: 링크`

`[google link]: https://google.com (다음과 같은 참조를 추가함)`

[구글][google link]

[google link]: https://google.com

<br>

### # 이미지
링크와 마찬가지로 참조 형태로도 사용 가능

`![이미지 설명 텍스트](이미지 주소)`

`예시: ![예시 이미지](/assets/img/example.jpg)`

![예시 이미지](/assets/img/example.jpg){: .normal }

`![이미지 설명 텍스트](이미지 주소) "설명"`

`예시: ![예시 이미지](/assets/img/example.jpg "샘플 이미지입니다.")`

![예시 이미지](/assets/img/example.jpg "샘플 이미지입니다."){: .normal }

#### 크기 조절을 하고 싶은 경우
`![이미지 설명 텍스트](이미지 주소){: width="" height=""}`

&#8251; Chirpy에서는 width = w, height = h로 약어로 사용 가능

`예시: ![예시 이미지](/assets/img/example.jpg){: width="100" height="150" }`

![예시 이미지](/assets/img/example.jpg){: width="100" height="150" .normal }

<br>

##### 참고 문서
<https://www.heropy.dev/p/B74sNE>

<https://gist.github.com/ihoneymon/652be052a0727ad59601>

<https://chirpy.cotes.page/posts/write-a-new-post/>