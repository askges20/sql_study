Windows에서 SQL Plus의 `ed` 명령어를 실행하면 기본적으로 메모장(Notepad++)에서 편집하도록 설정되어 있는데

이를 vi 편집기를 이용하도록 설정을 변경함

## 1. Vim 에디터 설치
설치 링크 : https://www.vim.org/download.php#pc

`vim82.exe` 찾아서 실행, 옵션 중에서 `Create .bat files` 체크

👉 Windows 폴더에 `vim.bat` 파일이 생성됨

## 2. SQL plus에서 설정
`define_editor = vim` 명령어 실행

👉 메모장 대신 vi 편집기에서 파일 내용을 수정할 수 있도록 함

`define` 명령어 입력해서 설정 확인 가능

<br/>
++

관리자 권한으로 cmd를 실행해서 `copy C:\WINDOWS\vim.bat C:\WINDOWS\vi.bat`를 입력하여 vi.bat 파일명으로 복사하면

vim 대신 vi라고 명령어를 입력해서 에디터를 실행할 수 있고, `define_editor = vi`로 설정할 수 있음
