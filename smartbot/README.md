ng generate class models/message 1. 메세지 객체를 만든다.

ng generate component components/message-list 2. 메세지 목록을 만든다.

ng generate component components/message-item 3. 메세지를 표시하는 구성요소를 만든다.

ng generate component components/message-form 4. 메세지를 입력받고 보내는 양식을 만든다.

5. NLP 백엔드로 DialogFlow 사용한다. environment.ts 에 토큰값을 입력한다.

6. DialogFlow API 를 호출하고 응답을 검색하는 DigalogFlow 서비스를 생성한다.

7. ng generate service services/dialogflow (DialogFlow API 를 사용하여 자연어 를 텍스트 형식으로 처리한다. 각 API 요청에는 HTTP 헤더 에 Authorization 필드가 포합된다.)

8. MessageFormComponent 에서 sendMessage() 메소드를 작성한다.

#Run
ng serve
