---
marp: true
theme: autocrypt
paginate: true
author: Jinwoo Lee
header: AutoCrypt V2X.platform 그룹 | 리더 가이드
math: katex
---

# Marp template

Hello world!

---

# I am a genius, my program is:

```c++
#include <iostream>

int main()
{
    return 0;
}
```

---

# Marp 기초 문법 (1/2)

<style scoped>
ul {
	font-size: 25px;
}
</style>

- 오리지널 마크다운 문법을 지원함(Mermaid 등 익스텐션은 미지원)
- themes를 통해 css 스타일 변경 가능
- itemize:
	- '*' 사용시 한 페이지당 하나씩 출력됨. 한번에 출력하려면 '-'
- Emoji: :satellite:
- Strikethrough: ~~strike~~
- Equation: $a = \frac{b}{c}$
- Code: `#include <iostream>`
- Code blocks:
```c++
#include <iostream>

void main;
```

---

# Marp 기초 문법 (2/2)
- images:
![w:300 center](assets/img_06.jpg)

- Tables:

| foo | bar |
| --- | --- |
| baz | bim |