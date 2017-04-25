=============================
 AWS IoT ハンズオン ~基本編~
=============================

.. toctree::
   :hidden:
   :maxdepth: 2
   :numbered:

   01
   02
   03
   04
   05
   06
   07
   08
   09

本書はAWS IoTおよびAWSの各サービスを利用してIoTの基本的なシステムを構築するためのハンズオン手順 について記述しております。

最新情報
========

-AWS IoTの説明資料を公開しました。 http://bit.ly/1SrHtGf



前提条件
========
* Intel Edison Kit for Arduino、GROVE Starter Kit、電源アダプタ、USBケーブル
* Wi-Fiでインターネットに接続できる環境 (WPA-PSK)
* 対象者として以下の方を想定
	* AWSアカウントをお持ちの方
	* IoTを活用したアプリケーション構築をご検討されているデベロッパーの方
	* AWSクラウドを活用したシステム・アプリケーション開発に従事されている方
	* UNIXの基本的なコマンドの利用経験がある方


注意事項
========
* 複数の参加者で1つのAWSアカウントを共用する場合は「参加者番号」を 01 〜 99 で定めて、各自で重複しないようにして下さい。一人で1つのAWSアカウントを利用する場合は「参加者番号」は 01 としてください。
* AWSアカウントは作成後1年間ご利用頂ける無料枠があります。本ハンズオンはその通り実施頂き、ハンズオン終了後に削除することで無料利用枠の範囲で収まるようになっております。無料枠を越えたAWSサービスのご利用料金は受講者の方にご負担いただきますよう、ご了承ください。
* 本番利用されているAWSアカウントでハンズオンを実施するのは避けて下さい。
* ハンズオンに必要な機材は貸出品となりますので、終了後は必ず返却をお願いします。


事前準備
========
EdisonにUSBでシリアル接続するのに必要なドライバを以下のURLからダウンロードし、インストールをお願いします。

**Windowsの場合**

* `Intel Edisonドライバのインストール <https://s3-ap-northeast-1.amazonaws.com/toshiake-iot-handson/classmethod-devday/tools/win/IntelEdisonDriverSetup1.2.1.exe>`_

* `Windows FTDI ドライバのインストール <http://www.ftdichip.com/Drivers/CDM/CDM%20v2.10.00%20WHQL%20Certified.exe>`_

Windowsの設定によっては、インストール出来ない場合があります。
その場合、インストーラーを"管理者として実行"してみて下さい。

**MacOSの場合**

* `MacOS FTDI ドライバのインストール <https://s3-ap-northeast-1.amazonaws.com/toshiake-iot-handson/classmethod-devday/tools/mac/FTDIUSBSerialDriver_v2_2_18.dmg>`_


サンプルプログラム
==================

本ハンズオンで利用するサンプルプログラムです。Edison上で利用します。


https://s3-ap-northeast-1.amazonaws.com/awsiot-handson-jp/awsiot-handson-fundamentals.zip


参考情報
=======
* `Intel Edison Board Software Downloads <https://software.intel.com/en-us/iot/hardware/edison/downloads>`
* Intel libmraa (Low Level Skeleton Library for Communication on GNU/Linux platforms)
* Intel UPM (Useful Packages & Modules) Sensor/Actuator repository for MRAA
* AWS IoT SDK for JavaScript
* AWS IoT Embedded-C SDK

よくあるトラブル
================

**AWS IoTのupdate shadow CLIを実行時にSSLエラーとなる**

python 2.7.10にアップデート、AWS CLIの再インストールでOK。


参考情報
========
* `インテル Edisonの初期化とファームアップデート(Win) <http://edison-lab.jp/flash/windows/>`_
* `インテル Edisonの初期化とファームアップデート(MacOS) <http://edison-lab.jp/flash/mac/>`_

ハッシュタグ
============
Twitterのハッシュタグはこちらになります。 **#AWS_IoT_JP**
