# Here we go drop zone for maintaining YouZan store Apps.

2016/04/13: 
  1. As YouZan is providing with the Node supporting API, therefore I've decide to proceed with Node Express; initiate build will be hosted temporarily at https://youzanstore-songlin81.c9users.io/
  2. YouZan SDK installed as local dependency (npm install youzan-sdk --save)

2016/04/14
  1. Change C9 server from UTC to Beijing time zone; YouZan API is mandatory to use Beijing TimeZone to take request, otherwise giving error code 40003
  songlin81:~/workspace $ sudo dpkg-reconfigure tzdata
    Current default time zone: 'Etc/GMT+8'
    Local time is now:      Wed Apr 13 19:32:01 GMT+8 2016.
    Universal Time is now:  Thu Apr 14 03:32:01 UTC 2016.
