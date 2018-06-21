# Telegram ChatBot

- telegram 로그인

- `BotFather` 검색, 친구 추가

- `/start` 입력 => `/newbot` 입력

- 이름과 유저 이름 작성  ex) woody / choi_woody_bot

- https://api.telegram.org/+ bot [token] + 명령어

  ```
  url ="https://api.telegram.org/bot"
  token = "553100469:AAHzizz9NnrpNYkE5rRtYPR52EJyiswT_i0"
  
  id = "560545727"
  msg = URI.encode("안녕하세요")
  url + token+"/sendMessage?chat_id=#{id}&text=#{msg}"
  ```

  

### Telegram ChatBot 명령어

- `getMe` : 내 정보
- `getUpdates` :내 봇의 상태 업데이트
- `sendMessage` : 메세지 보내기