# [BBC Microbot](https://twitter.com/bbcmicrobot) Sketches

+ https://twitter.com/bbcmicrobot/status/1320200939916218369
  ```basic
  1 MODE 2
  2 T=0
  3 REPEAT
  4 T=T+1
  5 A=0
  6 B=512
  7 C=1279
  8 D=512
  9 GCOL 0,RND(7)
  10 MOVE A,B+SIN(T/15)*350
  11 DRAW C,D-SIN(T/15)*350
  12 PRINT TAB(RND(18),31)
  13 UNTIL0
  ```
+ https://twitter.com/bbcmicrobot/status/1320204070163042304
  ```basic
  1 MODE 0
  2 T=0
  3 REPEAT
  4 T=T+1
  5 A=0
  6 B=350
  7 C=1279
  8 D=500
  10 MOVE A,B+SIN(T/2)*150
  11 DRAW C,D-SIN(T/2)*350
  12 PRINT TAB(RND(18),31)
  13 UNTIL0
  ```
