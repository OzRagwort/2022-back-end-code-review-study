# 백엔드 코드 리뷰 공유 스터디 📚

## 1. 개요
- 프론트의 리뷰 스터디를 보고 좋아보여서 만들어봤어요 👍🏻
- 백엔드 리뷰 스터디는 미션 진행을 하며 받은 코드리뷰들을 공유하는 스터디입니다.
- 서로의 리뷰를 공유하며 "아~~이런 개발지식, 주의사항도 있구나~"라는 것을 느끼고 알아가자는 취지로 만들었습니다.
- 활동은 미션별로 자신이 받은 코드 리뷰들을 정리하여 git으로 공유하는 방식으로 진행하려합니다.
- 크루들끼리 리뷰를 공유하며 같이 성장해봐요🔥

>  리뷰 스터디는 다른 스터디와 다르게 화상회의는 별도로 진행하지 않고 Git PR을 통해 서로 리뷰 공유를 하고 궁금한 내용이 있으면 Comment를 통해 질의응답합니다.

## 2. 일정

- 스터디 운영기간
  - 로또 미션(최종 리뷰부터) ~ 레벨 1 종료까지
- 정리한 내용 PR 기한
  - 1단계 PR 제출일 기준으로 **3일 뒤까지 올리기**
  - ex) 금요일이 1차 PR 마감일일 경우, 월요일까지 PR올리기❗️
  - 피드백이 오지 않았어도 일단 PR은 올려두기❗️
- 코드 리뷰 스터디
  - 장소: SLiPP 게더
  - 월요일 저녁시간 이후 희망자에 한해서 자발적으로 모여 서로의 코드를 공유

## 3. 운영 방식
### 3.1. 스터디 인원
- 스터디 정원은 10명입니다.

### 3.2. 진행방식
1. 스터디 repository를 fork합니다.
2. 미션별로 디렉터리를 생성합니다. (ex. **미션2-로또**)
3. 미션 디렉터리 안에 각자 새로운 파일을 생성합니다. (ex. **[로또미션] 렉스 리뷰 정리**)
4. 정해진 기간까지 피드백 정리 후 PR (피드백 정리는 아래와 같은 형식이면 👍🏻)
5. 미션이 끝날 때까지 추가적으로 받은 피드백은 지속적으로 열려있는 PR에 추가해 줍니다. 
   - 리뷰는 1, 2단계 나누지 않고 하나의 PR에 통합하여 올립니다.
6. 미션이 최종적으로 merge 되면 미션 피드백도 merge 합니다

```bash
# 피드백 주제 (ex: 개행에는 System.lineSeparator();를 사용하자)
## 대분류(ex: 아키텍처, 함수/클래스, 컨벤션, 테스트 등)
- [해당 comment 링크]
- 상세 내용 정리
```

<hr>


|                                           |                                                                                                                                          로또 미션 리뷰                                                                                                                                           | 블랙잭 미션 리뷰 | 체스 미션 리뷰 |
|-------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------:|:--------:|
| [렉스](https://github.com/Seongwon97)       |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EB%A0%89%EC%8A%A4%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [이프](https://github.com/sinb57)           |       [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/tree/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EC%9D%B4%ED%94%84%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC)       |           |          |
| [알린](https://github.com/OzRagwort)        |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EC%95%8C%EB%A6%B0%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [마루](https://github.com/chawani)          |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EB%A7%88%EB%A3%A8%201%EB%8B%A8%EA%B3%84%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)     |           |          |
| [봄](https://github.com/JangBomi)          |          [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EB%B4%84%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)          |           |          |
| [슬로](https://github.com/hanull)           |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EC%8A%AC%EB%A1%9C%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [레넌](https://github.com/brorae)           |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EB%A0%88%EB%84%8C%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [기론](https://github.com/Gyuchool)         |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EA%B8%B0%EB%A1%A0%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [조시](https://github.com/hyunrrr)          |     [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%EC%A1%B0%EC%8B%9C%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md)      |           |          |
| [클레이](https://github.com/yangdongjue5510) | [🔗](https://github.com/woowacourse-study/2022-back-end-code-review-study/blob/main/%5BMission2%5D%20%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98/%5B%EB%A1%9C%EB%98%90%20%EB%AF%B8%EC%85%98%5D%20%ED%81%B4%EB%A0%88%EC%9D%B4%20%EC%B5%9C%EC%A2%85%20%EB%A6%AC%EB%B7%B0%20%EC%A0%95%EB%A6%AC.md) |           |          |

