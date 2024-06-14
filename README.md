## WordCount 실행 방법

### 1. 코드 복제
git clone 레포주소

### 2. 가상환경 생성
cd wordCount # 폴더로 이동
<br>
<br>
python -m venv myvenv #가상환경 생성하기 (윈도우)
<br>
python3 -m venv myvenv #가상환경 생성하기 (맥)
<br>
<br>
source myvenv/scripts/activate #가상환경 실행하기 (윈도우)
<br>
source myvenv/bin/activate #가상환경 실행하기 (맥)

### 3. 장고 설치
pip install django #장고 설치하기

### 4. 프로젝트 폴더로 이동
cd wordCount_Pro #프로젝트 폴더로 이동

### 5. 서버 돌리기
python manage.py runserver
