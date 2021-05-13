# 네이밍 규칙

## Git
### PR
- `#<이슈번호> 한 일` 형식으로 짓습니다
`ex) #12 I killed KSH`
  - 만약 이슈를 처리한 PR이라면 이슈 링크를 위해서 본문에
`Fixed #<이슈번호>`
를 꼭 넣어줍시다. `ex) Fixed #12`

- 이슈를 해결하는 PR이 아니라면`한 일` 형식으로 짓습니다
`ex) I killed KSH`
### Commit
- [자세한 내용은 커밋 메세지 규칙 문서](https://github.com/Doran-Doran-development/DoranDoran-Sehttps://github.com/hanbin8269/project-rule-template/blob/master/commit-message-rule.md)를 참고하십시오
### Branch
- 브랜치 전략 문서를 참고하십시오

## In Develop
### Primary Key
- db 칼럼의 이름과 model field의 이름을 동일하게 합니다.

`ex) user_id = models.IntergerField(primary_key=True, db_column='user_id')`
