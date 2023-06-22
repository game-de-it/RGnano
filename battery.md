# RG nano AnbernicONとFunkeyOSでバッテリー残量(%)を表示させるスクリプト  


## ●概要  
このスクリプトを実行するとRG nanoのステータス表示でバッテリー残量を％で見ることができるようになります。  
※自己責任にてお願いいたします  

## ●手順  
  
1. ここのguihubのTOPページから 「battery_capacity」　と　「system_stats」 ファイルをダウンロードします  
(拡張子に.txtがついてしまう場合は、ダウンロード後に .txtを削除してください)
  <img src="/asset/sc2.png" width="800">  
  <img src="/asset/sc3.png" width="800">  


2. PCとRG nanoをUSBケーブルで接続し、本体側面にある電源ボタンを1回押して 「MOUNT USB」 を選択して実行します  
  <img src="/asset/IMG_2218.jpeg" width="800">  

3. PCからRG nanoのUSBドライブを開いて、ルートフォルダに 「usbnet」 というファイルを作成します  
(usbnetは新規作成の　テキストドキュメント　でOKです)  
  <img src="/asset/sc4.png" width="800">  
  <img src="/asset/sc5.png" width="800">  

4. AnbernicOSの場合は 「Anbernic」 フォルダ内に 「battery_capacity」 と 「system_stats」 ファイルをコピーします  
FunkeyOSの場合は 「FunKey」 フォルダ内に 「battery_capacity」　と　「system_stats」 ファイルをコピーします  
  <img src="/asset/sc7.png" width="800">  
 
5. RG nanoで 「EJECT USB」　を実行してPCから切断して、RG nanoをシャットダウンしてからもう一度起動させます
  <img src="/asset/IMG_2219.jpeg" width="800">  

6. RG nanoが起動したらLRボタンを押して 「applications」 から 「Explorer」 を起動します
  <img src="/asset/IMG_2220.jpeg" width="800">  

7. AnbernicOSの場合は 「Anbernic」 フォルダでAボタン押します  
FunkeyOSの場合は 「FunKey」 フォルダでAボタン押します  
  <img src="/asset/sc6.png" width="800">  

8. 「battery_capacity」 ファイルを選択してAボタンを押します  
**__※注意※「system_stats」 ファイルは実行しないでください__**  
画面が戻ったらスタートボタンを何回か押してメインメニューに戻ります  
  <img src="/asset/IMG_2242.JPG" width="800">  
  
9. RG nanoをシャットダウンします  

10. RG nanoが起動したら 「セレクト＋R＋L」 を押してステータスを表示させるとバッテリー残量が確認できます  
ステータス表示を消す場合は再度 「セレクト＋R＋L」 を押してください


(冒頭で作成した usbnet ファイルは、削除してもしなくても構いません)  

以上  



