# ad-practice-6-assignment
자율주행 Perception 6기 수강생들을 위한 과제 전용 Private Repository 입니다.

<div align="center">
<h1>🚗 자율주행 데브코스 6기 실습, 과제용 저장소</h1>
</div>

> 상세한 가이드는 [노션 GitHub 사용법 문서](https://www.notion.so/prgrms/GitHub-dc35bfa1fb4e43cb81f0e6b5bc826b77)를 참고해보세요.

## ⭐ 실습, 과제코드 리뷰 요청하는 법

### 초기 설정 방법 (처음 1번만 진행)

1. [**실습 저장소**](https://github.com/prgrms-ad-devcourse/ad-practice-6-assignment)를 자신의 컴퓨터(로컬)로 clone합니다.
2. clone한 저장소에 새로운 디렉터리를 생성합니다.
   - 디렉터리 이름은 **본인 이름**으로 생성합니다.
   - e.g.
     > ```shell
     > .
     > +-- 홍길동/
     > +-- README.md
     > ```

### 실습 풀이 제출 방법

1. 브랜치 네이밍 규칙에 따라 새로운 브랜치를 생성합니다.
   - 브랜치 이름 형식은 `주차-일자/깃허브 유저네임`입니다.
   - e.g. `week2-2/austin`, `week2-3/austin`
   - 깃 버전에 따라 한글명 브랜치 생성이 안될 수 있으니 팀명 영작하시는 센스! 부탁드립니다.
2. 과제 파일을 생성하고 진행합니다.
   - 파일 이름은 과제(스쿨페이지 제목) 이름으로 생성합니다.
   - e.g. `[과제]3.ROS 처리 지연 문제.py`, `[과제]1.노드간 동기화 문제 해결.py`, `[실습]터틀심 8자 주행.py`
3. 풀이를 완료한 파일을 `commit`, `push`합니다.
4. 문제를 풀이한 브랜치에서 `Pull Request`를 생성합니다.
   - `Compare & pull request` 버튼이 보이지 않는다면 `Pull requests` 탭에서 `New pull request` 버튼을 클릭합니다.
   - `base`는 `main`으로, `compare`는 위 1번 과정에서 생성한 과제 브랜치로 지정합니다.
5. 멘토의 피드백을 받았다면 PR을 본인이 직접 `close`합니다.
