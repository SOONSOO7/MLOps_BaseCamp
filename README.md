# MLOps_BaseCamp
mlops practice solo

# 도커 빌드
> docker build .
> docker-compose build

# 장고 세팅
> docker-compose run --rm app sh -c "django-admin startproject app ."
> docker-compose up

# flake8 실행 명령어
> docker-compose run --rm app sh -c "flake8"

# admin 계정 생성
> docker-compose run --rm app sh -c "python manage.py migrate"
> docker-compose run --rm app sh -c "python manage.py createsuperuser"

# git push
> git add .
> git commit -m "Django settings & workflow floder name update"
> git push -u origin main