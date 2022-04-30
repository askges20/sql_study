# SQL Plus 명령어
- `sqlplus` : 접속
- `exit` : 종료
<br/>

- `host` : OS 명령 프롬프트로 나감
- `help` : 명령어의 사용법 출력
- `conn 아이디/비밀번호` : 사용자 변경

## spool
- `spool 파일명` : 화면에 출력되는 결과 저장 (ex. `spool file.sql`)
- `spool off` : 저장 종료

## show
- `show all` : SQL Plus의 설정값 확인
- `show user` : 현재 접속된 사용자 표시
- `show 옵션` : 해당 옵션의 현재 값

## set
- `set autocommit` : DML 수행 후 자동으로 commit함
- `set feedback` : 결과가 몇 건인지 보여줌
- `set heading on/off` : 결과 컬럼 이름을 보여줌/숨김
- `set linesize n` : 한 줄에 보여줄 수 있는 글자 수 설정
- `set pause on/off` : 결과를 화면 단위로 멈추는지 여부 설정 (기본값은 off)
- `set time on/off` : 프롬프트에 시간 출력 여부 (기본값은 off)
- `set timing on/off` : 실행시간 출력

## Buffer 편집
- `r(un)` : Buffer에 있는 문장 실행 (`/`와 같다)
- `l(ist)` : 전체 문장 출력
- `ed(it)` : Buffer에 있는 문장을 파일로 부름 (afiedt.buf)
- `c(hange)/old/new` : old를 찾아서 new로 변경
- `del n` : n번째 라인을 지운다
- `n` : n번째 라인 전체를 text로 변경
- `a(ppend)` : text line 끝에 text 추가
- `i(nput)` : text 다음 line에 text 추가
- `save 파일명` : Buffer 내용을 파일명.sql에 저장
- `get 파일명` : 파일명.sql에 있는 내용을 Buffer로 가져옴
- `start 파일명 (또는 @파일명)` : 파일명.sql 실행
