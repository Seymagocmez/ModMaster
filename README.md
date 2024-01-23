# ModMaster

<img src="assets/icons/app_icon.png" width="250">

ModMaster, Modbus TCP/IP protokolünü kullanan cihazlardan veri okuma ve yazma işlemleri gerçekleştiren Flutter tabanlı bir mobil uygulamadır.


![Flutter](https://img.shields.io/badge/flutter-%2302569B?style=plastic&logo=flutter&logoColor=white) <img src="https://img.shields.io/badge/api-21+-red?style=plastic&logo=android" alt="language"> <img src="https://img.shields.io/badge/architecture-mvvm-yellow?style=plastic" alt="language">


Modbus TCP client, geliştirdiğimiz mobil uygulama üzerinden endüstriyel otomasyon sistemleriyle etkileşimde bulunan bir yazılım parçasıdır. ModMaster, kullanıcıya bu protokol üzerinden cihazlarla etkileşim kurma imkanı sunar. Ana sayfa, modbus register'ları görüntüler ve yeni veri eklemeye izin verir. Profil sayfasında Firebase Authentication entegrasyonu bulunurken, Settings sayfasında modbus bağlantı ayarları ve uygulama tercihleri düzenlenir. Chart sayfası, seçilen register'ın geçmiş verilerini grafikle gösterir. Kullanıcılar, endüstriyel otomasyonu kolayca mobil cihazları üzerinden yönetebilir ve uygulama aracılığıyla cihazlarla etkileşimde bulunabilir. Bu özellikler, README dosyasının kullanım kılavuzunda detaylı olarak açıklanmıştır.

Modbus TCP client, geliştirdiğimiz mobil uygulama üzerinden endüstriyel otomasyon sistemleriyle etkileşimde bulunan bir yazılım parçasıdır. Mobil uygulamamız, kullanıcıya Modbus TCP protokolü üzerinden cihazlarla iletişim kurma yeteneği sunar. Kullanıcı, uygulama aracılığıyla modbus cihazına bağlanabilir, bu cihazdan veri okuyabilir veya veri yazabilir. Uygulama içindeki ana sayfa, kullanıcının kayıtlı modbus register'larını görüntülemesine olanak tanır. Bu register'lar, endüstriyel tesislerdeki sensörler veya kontrol cihazları tarafından okunan veya yazılan değerleri temsil eder. Ayrıca, kullanıcılar yeni veri ekleyebilir ve seçtikleri bir register'ın detaylarına ulaşabilirler. Profil sayfasında Firebase Authentication entegrasyonu, kullanıcıların hesap bilgilerini güncellemelerini ve güvenli bir şekilde yönetmelerini sağlar. Settings sayfasında, kullanıcılar modbus cihazının bağlantı ayarlarını yapılandırabilir, uygulama dilini seçebilir ve temayı özelleştirebilirler. Chart sayfası, seçilen register'ın geçmiş veri noktalarının grafiksel olarak gösterilmesine imkan tanır. Bu şekilde, mobil uygulamamız, endüstriyel otomasyon alanında kullanılan Modbus TCP protokolünü kullanarak cihazlarla etkileşimde bulunmayı kolaylaştırır ve kontrolü mobil cihazlara taşır.

## What is Modbus TCP Client ?

Modbus TCP client, endüstriyel otomasyon sistemlerinde kullanılan bir iletişim protokolünü uygulayan yazılım veya cihazdır. Temel görevi, endüstriyel cihazlar arasında veri transferi gerçekleştirmek ve kontrol sistemleri ile bu cihazlar arasında etkileşim sağlamaktır. Bu sayede Modbus TCP client, sensör değerlerini okuma, kontrol komutları gönderme, uzaktaki cihazları izleme ve kontrol etme gibi işlevleri yerine getirir. Ayrıca, endüstriyel otomasyon tesislerinde, fabrikalarda ve enerji sistemlerinde Modbus TCP protokolünü destekleyen cihazlarla iletişim kurarak uzaktan izleme, kontrol, veri toplama ve analiz görevlerini yerine getirir. Bu protokol ayrıca SCADA sistemleri tarafından da yaygın olarak kullanılır, bu da Modbus TCP client'ın SCADA ile endüstriyel tesislerdeki cihazlar arasında etkili bir bağlantı sağlamasını mümkün kılar.

