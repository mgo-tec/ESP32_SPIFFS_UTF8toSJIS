# ESP32_SPIFFS_UTF8toSJIS

これは Arduino core for the ESP32 ( ESP-WROOM-32 )の Arduino IDE ライブラリです。 
SPIFFS ファイルシステム専用です。  
Version 1.2  
  
UTF8 to Shift_JIS 変換テーブルファイル "Utf8Sjis.tbl" を予めSPIFFSフラッシュにコピーしておく必要があります。  
UTF-8コードのString文字列をShift_JIS文字列コードに変換できます。  
変換テーブルファイルURL--> https://github.com/mgo-tec/UTF8_to_Shift_JIS  
  
JIS第一水準、第二水準、１３区、半角カナが変換可能  
  
【更新履歴】  
(1.2)  
フォントアドレスの計算式を見直しました。  
  
(1.1)  
軽微な修正  
  
(1.0)  
ESP32 SPIFFS用リリース  
  
参照ブログ https://www.mgo-tec.com  
  
The MIT license  
Copyright (c) 2017 Mgo-tec  