| 제목 Title | 제목 Title  | 제목 Title                                                                        | 제목 Title  | 내용입니다. |
| ---------- | ----------- | --------------------------------------------------------------------------------- | ----------- | ----------- |
| 제목 Title | 내용입니다. | 내용입니다.                                                                       | 내용입니다. | 내용입니다. |
| 제목 Title | 내용입니다. | 내용입니다.                                                                       | 내용입니다. | 내용입니다. |
| 제목 Title | 내용입니다. | 내용입니다내용입니다내용입니다내용입니다내용입니다내용입니다내용입니다내용입니다. | 내용입니다. | 내용입니다. |

# h1 스타일링 테스트

## h2 스타일링 테스트

### h3 스타일링 테스트

#### h4 스타일링 테스트

##### h5 스타일링 테스트

###### h6 스타일링 테스트

> block quote
> 제안된 헌법개정안은 대통령이 20일 이상의 기간 이를 공고하여야 한다. **대통령후보자가** 1인일 때에는 그 득표수가 선거권자 총수의 3분의 1 이상이 아니면 대통령으로 당선될 수 없다.

위원은 정~~당에 가입하~~거나 정치에 관여할 수 없다. 각급 *선거관리위원회*는 선거인명부의 작성등 선거사무와 국민투표사무에 관하여 관계 행정기관에 필요한 지시를 할 수 있다.

![
 귀여운 위니브 프렌즈   
](https://cdn.inflearn.com/public/files/posts/8d4983fa-7dd4-4322-9a56-83df1c8d26bc/%EC%9C%84%EB%8B%88%EB%B8%8C%EC%A6%88.png)

https://world.weniv.co.kr/

1. 1번 항목
2. 2번 항목
3. 3번 항목
    1. 뎁스1
        1. 뎁스2
            1. 뎁스3
                1. 뎁스4

-   항목 1
-   항목 2
    -   뎁스 2
        -   뎁스 3
            -   뎁스 4

아래는 여러 프로그래밍 언어를 사용하여 Markdown 양식으로 만든 코드 블록 예시입니다. 이 예시들은 Python 이외의 다양한 언어를 포함하고 있으며, 각 언어에 대해 간단한 코드 스니펫을 제공합니다.

코드 블럭 테스트

Python 코드:
```python
for i in range(10):
    print('Hello, Python!')

def hello(one, two, three):
    print(f'Hello, {one} {two} {three}!')
    return 'Hello, Python!'
```

HTML 코드:
```html
<!DOCTYPE html>
<html>
<head>
    <title>Hello, HTML!</title>
</head>
<body>
    <p>Hello, World!</p>
</body>
</html>
```

CSS 코드:
```css
body {
    background-color: lightblue;
}
p {
    color: navy;
    font-size: 20px;
}
```

JavaScript 코드:
```javascript
for (let i = 0; i < 10; i++) {
    console.log('Hello, JavaScript!');
}
```

Java 코드:
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Java!");
    }
}
```

C 코드:
```c
#include <stdio.h>

int main() {
    printf("Hello, C!\n");
    return 0;
}
```

C++ 코드:
```cpp
#include <iostream>

int main() {
    std::cout << "Hello, C++!" << std::endl;
    return 0;
}
```

C# 코드:
```csharp
using System;

class HelloWorld {
    static void Main() {
        Console.WriteLine("Hello, C#!");
    }
}
```

SQL 코드:
```sql
FROM hello SELECT world;
```

Go 코드:
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, Go!")
}
```

이 코드들을 Markdown 파일에 붙여넣으면, 지원하는 Markdown 렌더러나 에디터에서 각 언어에 맞는 하이라이트를 적용하여 보여줄 것입니다. `highlight.js`나 다른 코드 하이라이트 라이브러리를 사용하는 웹 페이지에서도 유사한 결과를 얻을 수 있습니다.

`inline codeblock print('hello world')`

제안된 헌법개정안은 대통령이 20일 이상의 기간 이를 공고하여야 한다. 대통령후보자가 1인일 때에는 그 득표수가 선거권자 총수의 3분의 1 이상이 아니면 대통령으로 당선될 수 없다.

위원은 정당에 가입하거나 정치에 관여할 수 없다. 각급 선거관리위원회는 선거인명부의 작성등 선거사무와 국민투표사무에 관하여 관계 행정기관에 필요한 지시를 할 수 있다.




#### 0. Git 설치 및 환경설정 🔍
Git 설치 https://git-scm.com/
- 설치 완료 후 Git bash 열어 환경설정
**git config --global user.name "your_name"**: 유저 이름 설정
**git config --global user.email "your_email"**: GitHub 가입 시 사용한 이메일
**git config --list**: 정보 확인
#### 1. 초기화 및 기본 설정
**git init**: 새 깃 저장소를 초기화
**git branch**: 현재 브랜치 확인 및 브랜치 설정 방법
**git checkout main**: main으로 브랜치 변경
**git branch main**: main 브랜치 생성
#### 2. 변경 사항 추가 및 커밋
**git status**: 현재 작업 상태 및 변경된 파일을 확인
**git add src/index/index.html**: 특정 파일을 스테이지에 추가
**git add .**: 또는 변경된 모든 파일을 추가
**git status**: 상태 확인 (선택사항)
**git commit -m "추가사항"**: 커밋을 수행하고 메시지를 추가
#### 3. 원격 저장소와 연결 및 푸시
**git remote add origin (Codee URL 복붙)**: 원격 저장소 추가
**git remote -v**: 원격 저장소 확인 (추가한 원격 저장소의 URL이 든다면 성공)
**git remote set-url origin (Codee URL 복붙)**: 원격 저장소 URL을 설정 (URL 변경 시 사용)
**git push origin main**: main 브랜치로 원격 저장소에 푸시
#### 4. 동기화 및 기록 확인
**git pull origin main**:원격 저장소(GitHub)의 최신 변경사항을 로컬 저장소(내 컴퓨터)에 반영
ex. 다른 사람이 원격 저장소에 커밋을 했다면, git pull 명령어를 통해 그 변경사항을 내 로컬 저장소로 가져올 수 있음
즉, git fetch(원격 저장소에서 변경사항을 가져오는)와 git merge(가져온 변경사항을 내 로컬 브랜치에 합치는) 작업을 동시에 수행하는 명령어
= 원격 저장소와 내 로컬 저장소를 동기화하는 명령어
**git log**: 커밋 기록 확인
#### 5. 파일 및 폴더 목록 확인 (Windows 명령어)
**dir**: 현재 디렉토리 내의 파일 및 폴더 목록을 표시