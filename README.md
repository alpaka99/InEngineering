# esm201441-2019-team6

### InEngineering : 공과대학 복수전공생들을 위한 정보제공 사이트

프로젝트 인원: 5명

프로젝트 기간: 2019.11 ~ 2019.12

실행 방법

1. git clone 
2. pip install -r requirements.txt
3. python manage.py migrate --run-syncdb
   - syncdb라는 것은 settings.py의 Installed apss에 추가된 앱에 대한 테이블을 처음 db에 만들어주는 command
4. python manage.py runserver