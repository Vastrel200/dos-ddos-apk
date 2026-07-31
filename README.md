# WebPentestTool

Python ile geliştirilmiş, web uygulamalarında güvenlik açıklarını tespit etmeye yönelik **etik hacking / pentest** aracı. Yalnızca **izin verilen** hedeflerde, yetkili güvenlik testleri (yasal sözleşme kapsamında / kendi test ortamınızda) için tasarlanmıştır.

## ⚠️ Yasal Uyarı

Bu araç yalnızca eğitim amaçlı ve **açık yazılı izin** aldığınız sistemlerde kullanılmak üzere geliştirilmiştir. İzinsiz sistemlere yönelik kullanım birçok ülkede suç teşkil eder (örn. Türkiye'de TCK 243-245 maddeleri). Aracı kullanarak doğacak her türlü sorumluluk kullanıcıya aittir; geliştirici(ler) hiçbir kötüye kullanımdan sorumlu tutulamaz.

## Özellikler

- [ ] Özellik 1 (ör. ip veya url desteği)
- [ ] Özellik 2 (ör. ip ile daha iyi çalışmasıvb.)
- [ ] Özellik 3 (ör. HTTP başlık/güvenlik yapılandırma analizi)
- [ ] Özellik 4 (ör. raporlama — JSON/HTML çıktısı)

> Yukarıdaki listeyi aracının gerçek modüllerine göre güncelleyin.

## Gereksinimler

- Python 3.9+: bu yoksa cık sayfadan
- pip: bu olmadan olmaz amk
- socket: Ağ bağlantılarını ve TCP soketlerini oluşturmak için.
- random: Rastgele kullanıcı aracı (User-Agent) ve sayılar üretmek için.
- sys: Terminal çıktılarını anlık olarak ekrana basmak (sys.stdout.flush) için.
- argparse: Kodun içinde tanımlı olan ancak menü yapısında aktif kullanılmayan argüman yönetimi için.
- time: İstekler arasına bekleme süresi koymak (time.sleep) için.concurrent.
- futures (ThreadPoolExecutor): Eşzamanlı olarak birden fazla bağlantı (multi-threading) açabilmek için.
- os: Menü ekranını temizleme komutu (clear veya cls) için.
## Kurulum

```bash
git clone https://github.com/Vastrel200/dos-ddos-apk.git
cd vastrel
pip install requests colorama(bunları yüklemessenizde olur)

```

## Kullanım

```bash
python dos.py
```

> Gerçek parametrelerinizi buraya güncelleyin.

## Örnek Çıktı

```
[+] attack ip:
[+] -623876
[!] sik
[+] Rapor kaydedildi: report.html
```

## Sorumlu Kullanım (Kapsam Dışı Kullanım Yasaktır)

- Yalnızca yazılı izniniz olan hedeflerde kullanın.
- Bug bounty programlarında ilgili platformun kurallarına uyun.
- Bulduğunuz zafiyetleri sorumlu ifşa (responsible disclosure) ilkeleriyle bildirin.

## Katkıda Bulunma

Pull request'ler memnuniyetle karşılanır. Büyük değişiklikler için önce bir issue açarak neyi değiştirmek istediğinizi tartışın.

## Lisans

[MIT](LICENSE)
