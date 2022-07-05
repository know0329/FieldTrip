# Readme 작성법을 읽히기 위해 작성된 Readme 입니다.

```JAVA
import java.util.*

public class ReadmeTest{
  public static void main(){
    System.out.println("Test용 입니다.");
  }
}
```

[Github 링크](https://github.com/)


* 목차
  * Readme 목적
  * Rademe 작성법
  * 좋은 Readme 조건

## Readme 작성 목적

프로젝트에 대한 간단한 설명을 기술하여 프로젝트 진행의 편리함을 강조하기위해

## Readme 작성법

1. '#' 제목 작성하기

    '#'기호는 보통 제목을 작성할 때 사용하며 '#'의 개수가 많아질수록 글자 폰트 크기가 작아진다.

2. '`'기호를 이용해 pseudo 코드나 간단한 코드를 작성할 수 있다.

    '```' 후 자신의 코드에 사용된 언어를 적고 코드를 작성한다.

3. 링크 삽입하기

    '[]'를 이용하여 링크의 제목을 적고 '()'안에 제목에 삽입될 링크를 작성한다.

4. 순서없는 목록 작성

    '\*'기호를 이용하여 목차를 표현하며 '\*'기호 이후에는 공백이 하나 존재해야 한다.

5. 인용문구 작성하기

    '>'를 이용하면 인용문구를 작성할 수 있다.

6. 테이블 만들기

    '|'와 '---'를 이용하여 테이블을 표현할 수 있다.
    
    월 | 일 | 시간
    ---|---|---|
    7월|5일|10시
    

7. 강조표시

    '\*'기호 두개를 문자 양 옆에 사용하면 문자를 **강조**할 수 있다.
    
8. 이미지 삽입
    github의 issue탭에서 new issue를 누른 후 삽입을 원하는 이미지를 중앙에 드래그하면 링크가 만들어진다. 그 링크를 복사하여 readme에 붙여넣기를 하면 이미지가 삽입된다.
9. 아이콘 삽입
    아이콘 삽입을 위한 사이트 : https://shields.io/   https://simpleicons.org/
    ![javascript](https://user-images.githubusercontent.com/49915643/177232875-d2aee029-87ab-4adc-b3ad-f1f1826e2477.svg)
## 좋은 Readme 작성법 (포함되어야할 내용)
* 프로젝트의 목적 및 용도
  * 이 프로젝트는 무엇을 위한 것인가
  * 어떤 문제를 해결할 수 있는가
  * 왜 이 프로젝트가 유용한가
  * 어떤 사람들이 이 프로젝트를 사용하면 좋은가
  * 이 프로젝트는 어떻게 작동하는가
* 프로젝트를 시작하는 방법
  * 프로젝트를 설치, 사용하기 위해 필요한 전제조건이 있는가
  * 어떻게 설치, 사용, 테스트하는가
  * 설치 가이드 문서는 어디에 있는가
* 저작권, 라이선스 정보

