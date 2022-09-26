# Shell command Arrangement  
## List
- pwd / cd / ls
- Long Format
- clear
- cp / mv / rm / mkdir
- tip
### pwd / cd / ls
**pwd**: shows the current path in a hierarchical directory  
**cd**: change directory  
**ls**: show list files and directories  
>> **arguments**
>> - '/': root
>> - '.': current directory
>> - '..': upper-level directory
>> - '~': home of current user
>> - '/[directory name]': absolute path  
>> - './[directory name]': relative path  
>> - '../[dierectory name]': relative path
## Long Format
- File Permissions: -로 시작 => file d로 시작 => directory
- Owner: 여러 사람이 접속해서 사용할 수 있으므로 권한 설정이 중요함
- Group
- Size(in bytes)
- Modification Time
- File Name
## Clear  
Shell command에 clear입력시 여태 작성한 Shell command 초기화
## cp / mv / rm / mkdir
**cp**: copy files and directories  
**mv**: move files and directories or rename them  
**rm**: delete files and directories ***permantely and irreversevely*** (휴지통 복구 불가능)  
**mkdir**: make a new directory  
>> **아직 연습단계이므로 복사본 또는 잡파일 생성 후 연습해보기**
## Tip
1. Autocompletion: 파일 또는 디렉토리 첫글자 혹은 두세글자 입력후 ***Tap***키 입력시 자동완성
2. Past commands: 직전 명령 불러오기 => 윗방향키
3. Use rm: rm커맨드 사용하기 전에 ls로 적용되는 파일 먼저 불러오기. (ls로 나오는 파일이 rm커맨드 사용할 때 지워지는 파일)
