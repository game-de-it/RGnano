# RG nano USB-DAC認識頻度を調整して全体的な負荷を下げるスクリプト


## ●概要  
AnbernicOSではUSB-DACを認識するために必要なプログラムが動作しており、USB-DACの確認頻度が0.1秒間隔で実施しされてます。  
V3sのCPUではこの処理が高負荷となっており、全体的なパフォーマンス悪化に繋がっています。  
このスクリプトを使うことで確認頻度を1秒に変更し、全体的な負荷を大幅に下げることができます。  
例えばSFCの動作ではとCPU使用率が約10%ほど下がります。  
※自己責任にてお願いします
<img src="/asset/20230629-101536.jpg" width="800">  

## ●手順  
  
1.  「[usb-dac_recognition](https://github.com/game-de-it/RGnano/blob/main/usb-dac_recognition)」　ファイルをダウンロードします  
(拡張子に.txtがついてしまう場合は、ダウンロード後に .txtを削除してください)
  <img src="/asset/sc2.png" width="800">  
  <img src="/asset/sc3.png" width="800">  


2. PCとRG nanoをUSBケーブルで接続し、本体側面にある電源ボタンを1回押して 「MOUNT USB」 を選択して実行します  
  <img src="/asset/IMG_2218.jpeg" width="800">  

3. PCからRG nanoのUSBドライブを開いて、ルートフォルダに 「usbnet」 というファイルを作成します  
(usbnetは新規作成の　テキストドキュメント　でOKです)  
  <img src="/asset/sc4.png" width="800">  
  <img src="/asset/sc5.png" width="800">  

4. AnbernicOSの場合は 「Anbernic」 フォルダ内に 「usb-dac_recognition」 ファイルをコピーします  
  <img src="/asset/sc10.png" width="800">  
 
5. RG nanoで 「EJECT USB」　を実行してPCから切断して、RG nanoをシャットダウンしてからもう一度起動させます
  <img src="/asset/IMG_2219.jpeg" width="800">  

6. RG nanoが起動したらLRボタンを押して 「applications」 から 「Explorer」 を起動します
  <img src="/asset/IMG_2220.jpeg" width="800">  

7. AnbernicOSの場合は 「Anbernic」 フォルダでAボタン押します  
  <img src="/asset/IMG_2221.jpeg" width="800">  

8. 「usb-dac_recognition」 ファイルを選択してAボタンを押します  
画面が戻ったらスタートボタンを何回か押してメインメニューに戻ります  
  
9. RG nanoをシャットダウンします  

以上  




