PICでUSBホストやりたい(#7)アドレスを指定する<br>
https://youtu.be/VVB31gXAM1Q<br>
<br>
「IchigoJamでUSBキーボードを使いたい」ってのがUSBを始めたきっかけ。<br>
C言語分からないので、数年がかりでなんとかなりました。<br>
そんな素人の覚書でございます。間違ってるところもあるでしょうが大目に見てください。<br>
今回は「アドレス設定」です。<br>
USBデバイスはHUBを経由して、複数のデバイスと通信できます。<br>
その場合「アドレス」が重要必要になりますが、これはホスト側から指定するので、<br>
その辺の処理をやっていこうと思います。<br>
