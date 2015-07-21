@dalinamum 왈
```irc가 slack을 백업하는 용도로만 쓰고 있다.``` 는 말에 영감을 얻고 레포를 생성.

##구현환경
- [Google Appengine + Go](https://cloud.google.com/appengine/docs/go/)

##목적
- Slack이 무료로 사용하는 경우 10,000 line까지만 저장되고 있어 이후에 대해서는 검색이나
조회가 안되는 부분이 불편해서 심심풀이로 만들어보려함. ~~돈내고 써야하지만 뭐 재미있자나?~~
- 개인적인 [Go language](http://golang.org) 연습
- 서버쪽 구현을 완성한 이후에는 [Electron](http://electron.atom.io)을 이용하여 client를 구현 (역시 이것도 Electron 공부를 위함.)

##개발목표
- Slack Outgoing Hook을 받아 GAE Datastore에 저장하는 API 생성.
- 각 채널별 조회기능 API 생성
- 검색 기능(? - datastore이기 때문에 힘들 듯.)

This project is for the private purpose to study Go. So I don't have any plan to translate the description to english yet. Sorry :( . 
However you can read the code. :-)
