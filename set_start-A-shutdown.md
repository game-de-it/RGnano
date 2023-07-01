# RG nano ゲーム中のスナップショットをサムネイル画像にするスクリプト


## ●概要  
AnbernicOSとFunkeyOSに対応  
このスクリプトによって「START+Aボタンでシャットダウン」機能が追加され、擬似的なハイバネーションが実現しました
再び電源オンにすると終了したところからゲームが再開されます
※自己責任にてお願いいたします  

## ●手順  
  
1. ここのguihubのTOPページから 「[set_start-A-shutdown](https://github.com/game-de-it/FunKeyOS-game_de_it/blob/main/set_start-A-shutdown)」と「[fkgpiod.conf](https://github.com/game-de-it/FunKeyOS-game_de_it/blob/main/fkgpiod.conf)」 ファイルをダウンロードします  
(拡張子に.txtがついてしまう場合は、ダウンロード後に .txtを削除してください)
  <img src="/asset/sc2.png" width="800">  
  <img src="/asset/sc3.png" width="800">  


2. PCとRG nanoをUSBケーブルで接続し、本体側面にある電源ボタンを1回押して「MOUNT USB」を選択して実行します  
  <img src="/asset/IMG_2218.jpeg" width="800">  

3. PCからRG nanoのUSBドライブを開いて、ルートフォルダに「usbnet」というファイルを作成します  
(usbnetは新規作成の　テキストドキュメント　でOKです)  
  <img src="/asset/sc4.png" width="800">  
  <img src="/asset/sc5.png" width="800">  

4. AnbernicOSの場合は「Anbernic」フォルダ内に「set_start-A-shutdown」と「fkgpiod.conf」ファイルをコピーします  
FunkeyOSの場合は 「FunKey」 フォルダ内に「set_start-A-shutdown」と「fkgpiod.conf」ファイルをコピーします  
  <img src="/asset/sc7.png" width="800">  
 
5. RG nanoで「EJECT USB」を実行してPCから切断して、RG nanoをシャットダウンしてからもう一度起動させます
  <img src="/asset/IMG_2219.jpeg" width="800">  

6. RG nanoが起動したらLRボタンを押して「applications」から「Explorer」を起動します
  <img src="/asset/IMG_2220.jpeg" width="800">  

7. AnbernicOSの場合は「Anbernic」フォルダでAボタン押します  
FunkeyOSの場合は「FunKey」フォルダでAボタン押します  
  <img src="/asset/sc6.png" width="800">  

8. 「set_start-A-shutdown」ファイルを選択してAボタンを押します  
画面が戻ったらスタートボタンを何回か押してメインメニューに戻ります  
  <img src="/asset/IMG_2254.jpg" width="800">  
  
9. RG nanoをシャットダウンします  

以上  

## ●キーマップの変更手順  
「fkgpiod.conf」ファイルをメモ帳で開き、該当箇所を変更します  
例えば「START+Xボタン」に変更したい場合はファイル内の「MAP START+A」を「MAP START+X」に書き換えて保存してください  
この機能自体を無効化したい場合は該当箇所の行を削除してください  
変更を適用させる場合は手順2から作業を実施してください  
  <img src="https://github.com/game-de-it/RGnano/blob/main/asset/sc11.png" width="800">  



(冒頭で作成した usbnet ファイルは、削除してもしなくても構いません)  

以上  
