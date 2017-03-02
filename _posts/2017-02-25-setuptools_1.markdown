---
title:  "Proje Paketleme 1"
date:   2016-01-08 15:04:23
categories: [python,setuptools]
tags: [paketleme]
---
* Setuptools nedir?
* Setuptools özellikleri nelerdir?
* Setuptools ile paketleme örneği

Setuptools nedir?
==================
Setuptools; geliştiricilerin Python projelerini (özellikle diğer paketlere bağımlılığı olan),  kolayca paketlemelerini ve dağıtmalarını sağlayan bir kütüphanedir. Kısacası projenizin paketlenip, dağıtılması safhasında ihtiyacınız olan şey.

Genel özellikleri:

* HTTP, FTP, Subversion, GitHub ve SourceForge üzerinden indirmeyi destekleyen EasyInstall aracını kullanarak kurulum zamanında bağımlılıkları otomatik olarak bulur / indirir / yükler / yükseltir ve indirme bağlantılarını bulmak için PyPI'den bağlantı verilen web sayfalarını otomatik olarak tarar.

*  Sıkıştırılmış tek bir dosyadan kullanılabilir dağıtım biçimi olan Python Egg dosyası oluşturur.

* Paketleri otomatik olarak setup.py içinde listelemeksizin kaynak ağacınıza otomatik olarak dahil eder

* Bir MANIFEST.in dosyası oluşturmak zorunda kalmadan ve kaynak ağacınız değiştiğinde MANIFEST dosyasının yenilenmesini zorlamadan kaynak dosyalarınıza otomatik olarak tüm ilgili dosyaları ekler.

* Otomatik olarak wrapper script ya da exe oluşturabilirsiniz.(py2exe yerine geçmez)

* PyPI desteği sayesinde dağıtımlarınızı ve Egg dosyalarınızı PyPI'ye yükleyebilirsiniz.

{% gist volkansahin/eddb59a20ba789612b54d07c70b738ec setup0.py %}

**Kaynak**
* [setuptools.readthedocs.io](http://setuptools.readthedocs.io/en/latest/setuptools.html)

