- python -m venv venv : 가상환경 생성
- source venv/Scripts/activate : 가상환경 활성화
- pip install <module_name> : 모듈 설치
- pip freeze >> requirements.txt : 현재 설치된 모듈 리스트 저장
- pip install -r requirements.txt : requirements.txt 기준으로 모듈 설치

-  git rm -r --cached data/ : 원격저장소 → git에 push 된 내용 (data) 폴더를 지워주세요.