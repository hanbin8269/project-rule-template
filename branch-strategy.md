## 브랜치 전략

### `master`
- 서비스로 배포되는 브랜치입니다.

### `develop`
- 개발된 기능들이 병합되는 브랜치입니다.

### `feature`
- 단위 기능을 개발하는 브랜치입니다.
- `feature/#<이슈번호>-<한 일>`형식으로 작명합니다
`ex) feature/#12-make-user-schema`
### `release`
- 배포를 위한 단계를 수행하는 브랜치입니다
- `release/<배포버전>`형식으로 작성합니다
`ex) release/1.0.1`

### `hotfix`
- `master`로부터 버그가 검출되었을 때 생성하는 브랜치입니다
- `hotfix/<에러가 검출된 버전>` 형식으로 작명합니다
'ex) hotfix/1.0.1`

## 전체 흐름
1. `develop`은 `master`로부터 생성된다.
2. `feature`는 `develop`으로부터 생성된다.
3. `release`는 `develop`으로부터 생성된다.
4. `master`에서 버그가 검출되면 `hotfix`를 생성한다