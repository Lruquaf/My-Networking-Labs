# My Networking Labs

CCNA çalışmalarım sırasında Cisco Packet Tracer ile gerçekleştirdiğim networking labları ve lab sonrası tuttuğum teknik notlar.

Bu repoda ağ cihazlarını tanıma, doğru kablolama, paketlerin katmanlar boyunca taşınması, Ethernet switching, IPv4 adresleme, VLAN, STP, EtherChannel ve yönlendirme konularında yaptığım uygulamaları topluyorum. Çalışmalarımda [Jeremy's IT Lab CCNA 200-301](https://courses.jeremysitlab.com/p/ccna) kursunu takip ediyorum.

[Lab kataloğu](#lab-kataloğu) · [İlk lab raporu](docs/labs/day-01-packet-tracer-introduction.md) · [Çalışma notlarım](Lab%20Notlar%C4%B1%20Part%201.pdf)

## Lablar ve notlar

Her `.pkt` dosyası bir labın kayıtlı topolojisini ve cihaz ayarlarını içeriyor. İlgili Markdown notlarında labın amacını, gerçek bağlantıları, adresleme ve konfigürasyon ayrıntılarını, karşılaştığım sorunları ve öğrendiklerimi açıklıyorum.

Repoda **26 Packet Tracer labı** bulunuyor. İlk beş labın raporları aşağıdaki katalogdan okunabilir. Gün numaraları kurs sırasını koruyor; Day 04'ten sonraki mevcut dosya Day 06. Aynı güne ait farklı çalışmalar ayrı satırlarda listeleniyor.

## Lab kataloğu

| Gün | Lab dosyası | Konu | Rapor |
| --- | --- | --- | --- |
| 01 | [Packet Tracer Introduction](Day%2001%20Lab%20-%20Packet%20Tracer%20Introduction.pkt) | Packet Tracer arayüzü ve ağ cihazlarına giriş | [Raporu oku](docs/labs/day-01-packet-tracer-introduction.md) |
| 02 | [Connecting Devices](Day%2002%20Lab%20-%20Connecting%20Devices.pkt) | Cihazlar, portlar ve kablo bağlantıları | [Raporu oku](docs/labs/day-02-connecting-devices.md) |
| 03 | [OSI Model](Day%2003%20Lab%20-%20OSI%20Model.pkt) | OSI modeli ve katmanların ağ iletişimindeki rolü | [Raporu oku](docs/labs/day-03-osi-model.md) |
| 04 | [Basic Device Security](Day%2004%20Lab%20-%20Basic%20Device%20Security.pkt) | Temel cihaz erişimi ve güvenlik ayarları | [Raporu oku](docs/labs/day-04-basic-device-security.md) |
| 06 | [Ethernet LAN Switching](Day%2006%20Lab%20-%20Ethernet%20LAN%20Switching.pkt) | Ethernet LAN switching | [Raporu oku](docs/labs/day-06-ethernet-lan-switching.md) |
| 08 | [IPv4 Addresses](Day%2008%20Lab%20-%20IPv4%20Addresses.pkt) | IPv4 adresleme | — |
| 09 | [Interface Configuration](Day%2009%20Lab%20-%20Interface%20Configuration.pkt) | Arayüz yapılandırması | — |
| 11 | [Configuring Static Routes](Day%2011%20Lab%20-%20Configuring%20Static%20Routes.pkt) | Statik yönlendirme yapılandırması | — |
| 11 | [Troubleshooting Static Routes](Day%2011%20Lab%20-%20Troubleshooting%20Static%20Routes.pkt) | Statik yönlendirme ve hata giderme | — |
| 12 | [Life of a Packet](Day%2012%20Lab%20-%20Life%20of%20a%20Packet.pkt) | Paketin ağ boyunca izlediği yol | — |
| 15 | [VLSM](Day%2015%20Lab%20-%20VLSM.pkt) | VLSM ile subnet planlama | — |
| 16 | [VLANs (Part 1)](Day%2016%20Lab%20-%20VLANs%20%28Part%201%29.pkt) | VLAN temelleri | — |
| 17 | [VLANs (Part 2)](Day%2017%20Lab%20-%20VLANs%20%28Part%202%29.pkt) | VLAN yapılandırmasına devam | — |
| 18 | [Multilayer Switching](Day%2018%20Lab%20-%20Multilayer%20Switching.pkt) | Multilayer switching | — |
| 19 | [DTP & VTP](Day%2019%20Lab%20-%20DTP%20%26%20VTP.pkt) | DTP ve VTP | — |
| 20 | [Analyzing STP](Day%2020%20Lab%20-%20Analyzing%20STP.pkt) | Spanning Tree analizi | — |
| 21 | [Configuring Spanning Tree](Day%2021%20Lab%20-%20Configuring%20Spanning%20Tree.pkt) | Spanning Tree yapılandırması | — |
| 22 | [Rapid STP](Day%2022%20Lab%20-%20Rapid%20STP.pkt) | Rapid Spanning Tree | — |
| 23 | [EtherChannel](Day%2023%20Lab%20-%20EtherChannel.pkt) | EtherChannel | — |
| 24 | [Floating Static Routes](Day%2024%20Lab%20-%20Floating%20Static%20Routes.pkt) | Floating static routes | — |
| 25 | [EIGRP Configuration](Day%2025%20Lab%20-%20EIGRP%20Configuration.pkt) | EIGRP yapılandırması | — |
| 26 | [OSPF (Part 1)](Day%2026%20Lab%20-%20OSPF%20%28Part%201%29.pkt) | OSPF — bölüm 1 | — |
| 27 | [OSPF (Part 2)](Day%2027%20Lab%20-%20OSPF%20%28Part%202%29.pkt) | OSPF — bölüm 2 | — |
| 28 | [OSPF (Part 3)](Day%2028%20Lab%20-%20OSPF%20%28Part%203%29.pkt) | OSPF — bölüm 3 | — |
| 29 | [HSRP Configuration](Day%2029%20Lab%20-%20HSRP%20Configuration.pkt) | HSRP yapılandırması | — |
| 31 | [IPv6 Configuration (Part 1)](Day%2031%20Lab%20-%20IPv6%20Configuration%20%28Part%201%29.pkt) | IPv6 yapılandırması — bölüm 1 | — |

## Labları açma

1. Repoyu klonla veya ZIP olarak indir:

   ```bash
   git clone https://github.com/Lruquaf/My-Networking-Labs.git
   ```

2. İlgili `.pkt` dosyasını Cisco Packet Tracer ile aç.
3. Topoloji üzerindeki görevleri ve varsa lab raporunu birlikte incele.
4. Kendi denemelerin için dosyanın bir kopyasında çalış.

Mevcut lab dosyaları **Packet Tracer 9.0.1** ile kaydedilmiş. Cisco Packet Tracer'a [Cisco Networking Academy](https://www.netacad.com/) üzerinden ulaşılabilir.

## Çalışma notlarım

[Ağları Katman Katman Anlamak — Lab Notları Part 1](Lab%20Notlar%C4%B1%20Part%201.pdf), Ethernet, katmanlama, MAC/IP, ARP, routing, VLAN, STP ve OSPF üzerine çalıştığım kavramları bir araya getiriyor. Lab raporları belirli bir uygulamaya; bu notlar ise konular arasındaki ilişkilere odaklanıyor.

## Kaynaklar

- [Jeremy's IT Lab — CCNA 200-301](https://courses.jeremysitlab.com/p/ccna)
- [Cisco Networking Academy](https://www.netacad.com/)
- [Cisco teknik dokümantasyonu](https://www.cisco.com/c/en/us/support/index.html)

Bu repo kişisel uygulamalarımı ve notlarımı içerir. Kursun özgün görev ve materyalleri ilgili üreticilere aittir.
