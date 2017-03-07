---
title:  "Python Proje Paketleme"
date:   2017-03-03 00:15:26
categories: [python,setuptools]
tags: [paketleme]
---

Python kullanarak bir uygulama geliştirdiniz ve bunun geliştirme aracınızda bir yazılım projesi olarak kalmasını istemiyorsunuz. Bir proje nasıl paketlenir? Bağımlılıkları nasıl yönetilir? Ne ile dağıtılır? Setuptools ile bu sorulara cevap bulabilirsiniz.

* Setuptools nedir?
* Setuptools özellikleri nelerdir?
* Setuptools ile paketleme örneği

Setuptools nedir?
-------------------
Setuptools; geliştiricilerin Python projelerini (özellikle diğer paketlere bağımlılığı olan),  kolayca paketlemelerini ve dağıtmalarını sağlayan bir kütüphanedir. Kısacası projenizin paketlenip, dağıtılması safhasında ihtiyacınız olan şey.

Setuptools Özellikleri
-------------------

* HTTP, FTP, Subversion, GitHub ve SourceForge üzerinden indirmeyi destekleyen EasyInstall aracını kullanarak kurulum zamanında bağımlılıkları otomatik olarak bulur / indirir / yükler / yükseltir ve indirme bağlantılarını bulmak için PyPI'den bağlantı verilen web sayfalarını otomatik olarak tarar.

*  Sıkıştırılmış tek bir dosyadan kullanılabilir dağıtım biçimi olan Python Egg dosyası oluşturur.

* Paketleri otomatik olarak setup.py içinde listelemeksizin kaynak ağacınıza otomatik olarak dahil eder

* Bir MANIFEST.in dosyası oluşturmak zorunda kalmadan ve kaynak ağacınız değiştiğinde MANIFEST dosyasının yenilenmesini zorlamadan kaynak dosyalarınıza otomatik olarak tüm ilgili dosyaları ekler.

* Otomatik olarak wrapper script ya da exe oluşturabilirsiniz.(py2exe yerine geçmez)

* PyPI desteği sayesinde dağıtımlarınızı ve Egg dosyalarınızı PyPI'ye yükleyebilirsiniz.

Setuptools İlk Örnek
-------------------

{% gist volkansahin/eddb59a20ba789612b54d07c70b738ec setup0.py %}

**Kaynak**
* [setuptools.readthedocs.io](http://setuptools.readthedocs.io/en/latest/setuptools.html)
