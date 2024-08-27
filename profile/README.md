## 👊 Lucky

### 팀원
| 이름 | 이메일 | 깃허브 |
| --- | --- | --- |
| 유하진 | qwertygoov@naver.com | [Hajin74](https://github.com/Hajin74) |
| 김성은 | jinna0319@gmail.com | [sung-silver](https://github.com/sung-silver) |
| 김연희 | kyh03179@gmail.com | [yony-k](https://github.com/yony-k) |
| 안소나 | objet_an@naver.com | [sonaanweb](https://github.com/sonaanweb) |
| 유서정 | bbwest0709@gmail.com | [bbwest0709](https://github.com/bbwest0709) |


### 팀 문화
- 매일 스크럼 진행
    - 오전 - AM 9:00
    - 오후 - PM 6:00
- 우리팀은 수평적인 문화 (상호존대)
- 상황 공유 적극적으로 하기

</br>

## 컨벤션

### 커밋 메시지

```
- [CHORE]: 내부 파일 수정
- [FEAT] : 새로운 기능 구현
- [ADD] : FEAT 이외의 부수적인 코드 추가, 라이브러리 추가, 새로운 파일 생성 시
- [FIX] : 코드 수정, 버그, 오류 해결
- [DEL] : 쓸모없는 코드 삭제
- [DOCS] : README나 WIKI 등의 문서 개정
- [MOVE] : 프로젝트 내 파일이나 코드의 이동
- [RENAME] : 파일 이름의 변경
- [MERGE]: 다른 브렌치를 merge하는 경우
- [STYLE] : 코드가 아닌 스타일 변경을 하는 경우
- [INIT] : Initial commit을 하는 경우
- [REFACTOR] : 로직은 변경 없는 클린 코드를 위한 코드 수정

ex) [FEAT] 목표 대학 리스트 조회 API 개발
ex) [FIX] 내가 작성하지 않은 리뷰 볼 수 있는 버그 해결
```

### Branch
  - 전략
    | Branch Type | Description |
    | --- | --- |
    | `dev` | 주요 개발 branch, `main`으로 merge 전 거치는 branch |
    | `feature` | 각자 개발할 branch, 기능 단위로 생성하기, 할 일 issue 등록 후 branch 생성 및 작업 |

  - 네이밍
    - `{header}/#{issue number}`
    - 예) `feat/#1`

### PR

- 규칙
  - branch 작업 완료 후 PR 보내기
  - 항상 local에서 충돌 해결 후 remote에 올리기
  - PR 후 디스코드에 공유하기
  - 당일 PR은 당일에 리뷰하기
  - 최소 2명 이상의 동의를 받으면 merge하기
  - review 반영 후, 본인이 merge
    ```bash
    > [MERGE] 브랜치이름/#이슈번호
    ex) [MERGE] setting/#1
    ```
### TEMPLATE

- Issue Template
    
    ```markdown
    📱 Description
    <!-- 진행할 작업을 설명해주세요 -->
    
    📱 To-do
    <!-- 작업을 수행하기 위해 해야할 태스크를 작성해주세요 -->
    - [ ] todo1
    
    📱 ETC
    <!-- 특이사항 및 예정 개발 일정을 작성해주세요 -->
    
    ```
    
- PR Template

  ```markdown
    📱 Issue Number
    <!-- 작업한 이슈 번호를 명시해주세요 -->
    
    📱 Description
    <!-- 작업 내용에 대한 설명을 적어주세요 -->
    
    📱 Test Result
    <!-- local에서 postman으로 요청한 결과를 첨부합니다 -->
    
    📱 To Reviewer
    <!-- 리뷰 받고 싶은 포인트를 작성합니다 -->

    ```
