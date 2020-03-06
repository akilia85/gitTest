# Dev-CAT

깃허브 테스트 클론 사용

## 기능 목록
1. 깃 add  -  수정된 파일을 커밋하기 위해 스테이지에 올림
2. 깃 commit  - 스테이지에 올라온 파일을 커밋 시킴 (수정점을 생성)
3. 깃 push - 커밋을 깃 사이트에 반영
4. 깃 pull - 깃 사이트에 반영된 것을 로컬 저장소에 받아옴

5. 깃 브랜치(branch) - 각 사용자마다 수정 내용이 겹칠 수 있으므로 각각의 브랜치(가지)로 분기를 함. 분기 이후 수정하는 내용은 각 브랜치별로 커밋이 진행 됨

6. 깃 머지(merge) - 기능별 브랜치 작업이 마무리 되면 해당 브랜치를 마스터 브랜치(또는 합치고 싶은 브랜치)와 병합시킴. 합칠 주체가 되는 브랜치로 이동(checkout) 한 후 머지를 실행

7. 깃 컨플릭트(conflict) - 동일한 부분을 여러 브랜치에서 수정후 머지(병합)하려는 경우 컨플릭트 (충돌)이 발생함