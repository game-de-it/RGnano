# RG nano　起動時の時計アプリを止める＆元に戻すスクリプト  
2023-06-22 21:00 手順修正  
2023-06-22 02:48 手順修正  

## ●概要  
このスクリプトを実行するとRG nanoを起動時に自動的に実行される時計アプリを停止させることができ、時計アプリを元に戻すことができます。  
※自己責任にてお願いいたします  

## ●手順  
  
1. ここのguihubのTOPページから 「exclude_clocks」　と　「turnback_clocks」 ファイルをダウンロードします  
(拡張子に.txtがついてしまう場合は、ダウンロード後に .txtを削除してください)
  ![s2](/asset/sc2.png)
  ![s2](/asset/sc3.png)

2. PCとRG nanoをUSBケーブルで接続し、本体側面にある電源ボタンを1回押して 「MOUNT USB」 を選択して実行します  
  ![s1](/asset/IMG_2218.jpeg)

3. PCからRG nanoのUSBドライブを開いて、ルートフォルダに 「usbnet」 というファイルを作成します  
(usbnetは新規作成の　テキストドキュメント　でOKです)  
  ![s2](/asset/sc4.png)  
  ![s2](/asset/sc5.png)  

4.「Anbernic」　フォルダ内に　「exclude_clocks」　と　「turnback_clocks」 ファイルをコピーします  
  ![s2](/asset/sc1.png)  
 
5. RG nanoで「EJECT USB」　を実行してPCから切断して、RG nanoをシャットダウンしてからもう一度起動させます
  ![s3](/asset/IMG_2219.jpeg)

6. RG nanoが起動したらLRボタンを押して 「applications」　から 「Explorer」　を起動します
  ![s4](/asset/IMG_2220.jpeg)

7. 「Anbernic」 フォルダでAボタン押します
  ![s5](/asset/IMG_2221.jpeg)

8.時計を停止させる場合は「exclude_clocks」 ファイルを選択してAボタンを押します  
または時計を元に戻す場合は「turnback_clocks」 ファイルを選択してAボタンを押します  
画面が戻ったらスタートボタンを何回か押してメインメニューに戻ります  
  ![s6](/asset/IMG_2222.jpeg)    
  
9. RG nanoをシャットダウンしたら作業は完了です  
(冒頭で作成した usbnet ファイルは、削除してもしなくても構いません)  

以上  

```
Special thanks - debugger
[ Twitter : ぱりぱりうめ @paripariume_PPU ]
[ Twitter : じゅんたろう @GameboyJuntaro ]
```

