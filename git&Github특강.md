# git & github 특강

## 깃이 없다면
 * 작업을 되돌리기 어려움
 * 내역 확인이 어려움
 * 협력 하기 어려움
## git
 * 변경관리 (버전) 관리 용이
 * 버전
   + 유의미한 변화가 결과물로 나온 것

## 하나의 버전이 만들어지는 과정
  (작업 디렉터리) - add - (스테이지) - commit - (저장소)
## 실습해보기.

. 현재 디렉토리 
git add . 
다 추가됨

## 브랜치 관리
   버전의 분기
   최초의 브랜치 master 브랜치
 * 분기 관리
   + 브랜치 나눈다
   + 각자의 브랜치에서 작업
   + 필요하다면 합친다
 * Head
   + 현재 작업중인 브랜치
 * 체크아웃
   + 작업환경 바꿈 다른 브랜치의 최신
 * 브랜치 병합
   + merge
 * 충돌(conflict)
   + 같은 부분 다르게 수정 후 병합
   + 해결방법 직접 선별, 수정 후 재 커밋
 
 ## git hub 
 * 저장소
 * push
   + 로컬 저장소의 변경사항을 원격저장소에 밀어넣는것
     일종의 업로드
     변경사항(커밋)을 업로드
     remote를 add
     git push
 * pull
 * clone
