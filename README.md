# Ameyadar
ツイッターアカウント名に，京都大学上空の予想降水量に応じた絵文字を貼付する。

Yahoo! Open Local Platform(YOLP)の[気象情報API](https://developer.yahoo.co.jp/webapi/map/openlocalplatform/v1/weather.html)を使ってます。  
こういう無料の気象系APIは，精度が悪かったり(海外産)二次利用不可だったり(日本産)するのだが，これは非商用目的なら使える([商用目的でも問い合わせれば使えるかも](https://www.yahoo-help.jp/app/answers/detail/p/537/a_id/43405))ので有難い。1時間先までの降水量しか分からないけど日常生活ではそれで充分だよね。  


herokuにデプロイして，heroku schedulerで10分間に1回起動するようにしたら便利。  
詳細は暇な時にQiitaにでも書こうかな。

## License
MIT
