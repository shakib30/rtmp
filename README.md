# How to run
1. ` apt install Docker `
2. cd rtmp 
2. ` docker-compose build `
3. ` docker-compose up `
4. Open OBS and in settings set the server to `rtmp://localhost:1935/live` and the stream key to `test?key=supersecret`
5. IF YOU STREAM KEY IS DIFFERENT THAN "TEST" YOU WILL HAVE TO CHANGE THE Channel-1.HTML FILE SO THAT IT LOOKS FOR {other-stream-key}.m3u8} (line 107)
6. Open a browser and go to ` http://localhost:3000 ` to view your live stream!
if you file edit first need the server to stop "cltr-c" 1st  edit file, if complete edit use  ` docker-compose build `,  ` docker-compose up `

setup guide and code credit : https://youtu.be/yzh8vjYNdzk?si=8kmL8P_RB_YahZ47
