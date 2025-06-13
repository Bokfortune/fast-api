"# fast-api" 
# install 
```
pip install fastapi uvicorn sqlalchemy
```

# Fast API 실행 -main.py가 있는 api 폴더에서 진행
```
cd api
uvicorn main:app --reload
```

# API 테스트
```
http://localhost:8000/docs
http://127.0.0.1:8000/docs


# Flasks 설정
```
pip install flask
```

# Flasks 실행
```
새 터미널 cd frontend
python app.py
```

```
# 주요 에러
```
CROS
pydentic으로 API 서버에서 데이터 정의를 했기 때문에 타입에 맞게 데이터를 넘겨줘야 함