# 새로운 폴더 생성
# vscode에서 오픈
# 터미널접속
# conda create -n 가상환경이름 python
# ctrl+shift+p --> 인터프리터를 가상환경이름으로 선택
# 터미널 접속

# isntall
```
pip install fastapi uvicorn sqlalchemy flask
```
# Fast API 실행 - main.py가 있는 api폴더에서 진행
```
cd api
uvicorn main:app --reload  
```
# API 테스트
```
http://localhost:8000/docs
http://127.0.0.1:8000/docs
```

# Flask 실행
```
새 터미널 - cd frontend 
python app.py
```
# 주요 에러
```
CROS
pydantic으로 API서버에서 데이터정의를 했기때문에 타입에 맞게 데이터를 넘겨줘야함
```

# JQUERY 
```
DOM Traversal and Manipulation
Get the <button> element with the class 'continue' and change its HTML to 'Next Step...'

$( "button.continue" ).html( "Next Step..." )
```
```
Event Handling
Show the #banner-message element that is hidden with display:none in its CSS when any button in #button-container is clicked.

var hiddenBox = $( "#banner-message" );
$( "#button-container button" ).on( "click", function( event ) {
  hiddenBox.show();
});
```
```
Ajax
Call a local script on the server /api/getWeather with the query parameter zipcode=97201 and replace the element #weather-temp's html with the returned text.

$.ajax({
  url: "/api/getWeather",
  data: {
    zipcode: 97201
  },
  success: function( result ) {
    $( "#weather-temp" ).html( "<strong>" + result + "</strong> degrees" );
  }
});
```