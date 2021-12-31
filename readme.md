testar
https://stream.hullerseguranca.com.br/
Interface/Cameras/GetJPEGStream?AuthUser=admin&AuthPass=1582&ResponseFormat=JSON&Profile=Custom&CustomProfile=HighResolution&Width=720&Height=480&KeepAspectRatio=TRUE&FPS=6&Camera=0163%2005%20BASE%20PAPEIS

mjpeg > dash
  sem suporte para ios
  apenas hls tem e webrtc
  https://cdn.dashjs.org/latest/jsdoc/index.html
  https://flowplayer.com/developers/tools/stream-tester?custom=http%3A%2F%2F127.0.0.1%3A8080%2Flive.m3u8

mjpeg > hls
  npm install http-server -g
  http-server -c-1 data
  http://127.0.0.1:8080/live.m3u8
  mt latencia depende dos segments
  nao atualiza direito
  testar com jwplayer (jwplayer esta com problema de cors e dai nao acha o endereco local)
  verificar no arquivo live.m3u8 se ele esta sendo atualizado (nao pode ter cache) no dev-tools
  delay 30-60 webrtc tem menor latencia
  (player - ligar cors)
  https://flowplayer.com/developers/tools/stream-tester?custom=http%3A%2F%2F127.0.0.1%3A8080%2Flive.m3u8

mjpeg > webrtc





