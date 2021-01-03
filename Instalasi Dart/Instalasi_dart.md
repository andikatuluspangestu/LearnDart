# Instalasi Dart
  Cara instalasi Dart SDK di Linux, Windows dan MacOS
  
______  
  
##### Linux
    - Buka Terminal, dan ketikan perintah berikut perbaris
      > sudo apt-get update
      > sudo apt-get install apt-transport-https
      > sudo sh -c 'curl https://dl-ssl.google.com/linux/linux_signing_key.pub | apt-key add -'
      > sudo sh -c 'curl https://storage.googleapis.com/download.dartlang.org/linux/debian/dart_stable.list > 
        /etc/apt/sources.list.d/dart_stable.list'
      
    - Setelah itu mari kita memulai Install Dart SDK
      > sudo apt-get update
      > sudo apt-get install dart
    
___    
    
##### Windows ( Via Chocolatey )
    - Buka CMD
      > choco install dart-sdk

___

##### MacOS
    - Buka Terminal
      > brew tap dart-lang/dart
      > brew install dart
      
___      
      
##### Cek instalasi atau Versi
      > dart --version
      > Dart SDK version: 2.10.4 (stable) (Unknown timestamp) on "linux_x64"
    
___    

> Cara yang digunakan merupakan cara yang sering dipakai, mudah dan cepat. Untuk platform lain bisa kunjungi cara instalasi nya di website resmi [Dart Dev](https://dart.dev/get-dart)
