# Git을 씁시다

Git은 짱짱맨 리누스 토발즈가 처음 만든 분산 버전 관리 시스템입니다. Git을 사용하면 코드를 작성하다가도 이전으로 쉽게 돌릴 수 있고, '분산' 버전 관리이기 때문에 여러 사람과 공동 작업을 정말로, 정말로 수월하게 해 줍니다. 물론, 코드를 왕창 날려먹거나 하는 대참사를 미연에 방지할 수도 있구요.

수없이 많은 프로젝트를 진행하고, 짱짱 쩌는 알고리즘도 짜는데 아직도 Git을 사용하지 않으신다구요? 그러면 어느 날 코드가 왕창 날아간다거나. 한창 기능을 개발하다 이전 코드를 보고싶다면 어떻게 하실 거죠?

뭐, 아무튼. 그래서 Git과 Github에 대한 세미나를 하려고 합니다! 정말 짱짱 좋고 여러분의 정신 건강을 책임질 좋은 녀석이니 아직 Git을 사용해 본 적이 없거나, 사용할 줄 모른다면 꼭 오셔서 배워가시면 좋겠습니다!

# 세미나 일시

## 일시

2017년 5월 26일, 29일 오후 6시 30분 (두 세미나의 내용은 같습니다)

## 장소

부경대학교 향파관 302호

# 준비물

실습 계획이 있기 때문에 준비물이 꼭 필요합니다.

1. 노트북 - 운영체제는 macOS, Windows, Linux, 다 상관 없습니다
    - 최신 Java Development Kit 설치해오기 (환경 변수 세팅 포함)
    - Git 설치해오기
2. 부경대학교 이메일 계정(@pukyong.ac.kr)
3. Github 계정
4. 부경대학교 이메일로 Github에서 Student Developer Pack 수령해놓기
5. 기초적인 Java 지식

## 준비물에 대한 부가 자료
1. Java Development Kit 다운로드 : http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html
2. Git 다운로드 : https://git-scm.com/
3. 부경대학교 이메일 생성 : http://mail.pukyong.ac.kr/main/main.jsp
4. Github 회원가입 : https://github.com/
5. Github Student Developer Pack : https://education.github.com/

## Java 사전 지식

실습을 하긴 할 텐데, Git이 우선이고 코드는 아주 기초적인 부분만 작성할 것이기 때문에

```
public class Heisenberg {

    private String name = "";

    public Heisenberg(){  //생성자
        //Making meth...
        this.name = "Heisenberg";
    }

    public void sayMyName(){ //메소드
        System.out.println(this.name); //콘솔 출력
    }

}

public class HelloGit { //클래스 정의

    public static void main(String[] args){ //진입점
        Heisenberg walterWhite = new Heisenberg(); //객체 생성
        walterWhite.sayMyName(); //메소드 호출
    }

}
```

이정도 코드만 이해하시고, 작성하실 수 있으면 됩니다. 만약 이 정도도 버거우시다면 제게 개인 톡을 주시거나 왑 잡담방에 알려주시면 성심성의껏 알려드리겠습니다!

그리고 아직 Java를 배우지 않은 신입생 여러분들도 정말 이틀만 보면 기본정도는 하기 때문에 꼭 한번 해보셨으면 합니다!
