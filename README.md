# 💻 Publisings Toy Project

- [홈페이지](https://kimnamkwang.github.io/Toy_project_Holy/HTMLs/index1.html)

## 소개

#### 피트니스 회원을 대상으로 실시하는 만족도 설문 조사 프로그램

## 사용 언어

#### HTML, CSS

## 프로젝트 진행 기간

#### 2022. 11. 10 ~ 2022. 11. 11

## 팀 멤버

### 🙋‍♂김남광

- [메인 화면](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/index.html)
- [기간별 통계 조회](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Statistics_by_period.html)
- [회원별 통계 조회](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Statistics_by_members.html)
- [설문조사완료](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Survey_submit.html)

### 🙋‍♀안지영

- [로그인](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Login.html)
- [설문조사](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Survey.html)
- [회원가입](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Join.html)
- [개인정보 이용 및 수집 동의](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Join_agree.html)
- [회원가입 완료](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/docs/HTMLs/Join_completion.html)

## 구성

- 📄 [요구사항정의서](https://docs.google.com/spreadsheets/d/123lKQAMeXs1e0xojYjV34sEz6893--HP/edit#gid=951428288)
- 📑 [화면정의서](https://github.com/KimNamKwang/Toy_project_Holy/blob/master/src/Images/Screen_definition_Holy.pdf)
- 📜 [페이지](https://kimnamkwang.github.io/Toy_project_Holy/)
- 📽 [페이지영상](https://www.youtube.com/watch?v=00qawzvbADU)

## 소감

- 김남광 : html과 css에 대해 잘 몰랐었는데 생각보다 훨씬 많은 기능이 있고 또 비슷한 화면이 나오더라도 여러가지 기능으로 만들 수 있어서 꽤나 어려운 작업이었습니다. 하지만 동시에 직접 테스트 해보면서 특히나 웹 서비스의 경우 사용자의 입장에서 기능을 잘 찾아볼 수 있고 사용하기 편리하게 만드는 것이 정말 중요하다는 것을 느꼈습니다.
- 안지영 : 작은 버튼 하나에도 많은 기능이 들어가고 사소한 부분 하나를 나타내기 위해 많은 고민을 하고 시도해보는 과정에서 여러가지를 배웠습니다. 평소 네이버나 구글같은 플랫폼 웹페이지를 별 생각 없이 썼었는데 이 과정을 거치면서 많은 웹 사이트를 찾아보고 또 살펴보았습니다. 대체적으로 화면이 어떻게 구성되는지, 어떤 곳에 어느 기능이 주로 위치하는지를 알 수 있었습니다. 마음처럼 안 되는 부분도 많았지만 조금은 즐기면서 했던 것 같습니다

## Made With Bootstrap

-[메인화면](https://kimnamkwang.github.io/Toy_project_Holy/)

#### 주요 코드

navigation bar에서 collapse와 dropdown을 활용하여 만든 부분

```
<a href="#collapseID" class="navbar-toggler" data-bs-toggle="collapse"
          ><span class="navbar-toggler-icon"></span
        ></a>
        <div class="navbar-nav">
          <div class="collapse navbar-collapse me-5" id="collapseID">
            <a href="./Survey.html" class="nav-link">설문하기</a>
            <div class="nav-item dropdown">
              <a
                href="#dropdownTarget"
                class="nav-link dropdown-toggle"
                data-bs-toggle="dropdown"
                >통계보기</a
              >
              <div id="dropdownTarget" class="dropdown-menu">
                <a
                  href="./Statistics_by_member.html"
                  class="dropdown-item nav-link text-dark"
                  >개인 설문 조회</a
                >
                <a
                  href="./Statistics_by_period.html"
                  class="dropdown-item nav-link text-dark"
                  >전체 설문 조회</a
                >
              </div>
            </div>
```
