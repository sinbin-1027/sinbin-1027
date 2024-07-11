# GIT 복습하기

## 1. 깃허브 레포지토리에 PUSH하기(코드 수정한 상태)   
   1. 바탕화면에 폴더 있는 상태
   2. 폴더 안에서 GIT BASH HERE 열기
   3. git init (branch이름이 master로)
   4. git add .
   5. git commit -m "first_practice"
   6. ##git log
   7. git remote add origin URL주소 (원격저장소 생성)
   8. ##git remote(원격 저장소 확인하기)
   9. ##git remote -v
   10. git push origin +master (원격에 업로드)

## 2. 각종 명령어
  - ~ : home directory
  - cd ~ : 홈 디렉터리로 이동
  - cd - : 뒤로 가기
  - cd .. : 상위 디렉터리로 이동
  - touch a.확장자 : 파일 생성
  - rm 파일명 : 파일 삭제
  - ls : 현재 디렉터리 안에 있는 파일 목록 출력
  - mkdir new_folder : 폴더 생성
  - rm -r new_folder : 폴더 삭제
  - git config --global user.name "이름"
  - git config --global user.email "이메일주소"
  - git clone URL주소 : 다른 장소에서 프젝 진행할 때 내려받음 (보통 바탕화면에서 bash here)
  - git pull origin master : 내 폴더에서 파일이 몇개 삭제되어도 pull쓰면 원격에 있는 파일 다시 내려받을 수 있음
  - start : 폴더 및 파일 오픈
  - 