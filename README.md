# My Networking Labs

CCNA çalışmalarım sırasında Cisco Packet Tracer ile gerçekleştirdiğim networking labları ve lab sonrası tuttuğum teknik notlar.

Bu repoda ağ cihazlarını tanıma, doğru kablolama, paketlerin katmanlar boyunca taşınması, Ethernet switching, IPv4/IPv6 adresleme, VLAN, STP, EtherChannel, statik yönlendirme, EIGRP, OSPF ve HSRP konularında yaptığım uygulamaları topluyorum. Çalışmalarımda [Jeremy's IT Lab CCNA 200-301](https://courses.jeremysitlab.com/p/ccna) kursunu takip ediyorum.

[Lab dosyaları](labs/) · [Lab kataloğu](#lab-kataloğu) · [İlk lab raporu](docs/labs/day-01-packet-tracer-introduction.md) · [Çalışma notlarım](Lab%20Notlar%C4%B1%20Part%201.pdf)

## Lablar ve notlar

Her `.pkt` dosyası bir labın kayıtlı topolojisini ve cihaz ayarlarını içeriyor. İlgili Markdown notlarında labın amacını, gerçek bağlantıları, adresleme ve konfigürasyon ayrıntılarını, karşılaştığım sorunları ve öğrendiklerimi açıklıyorum.

Repoda **26 Packet Tracer labı** bulunuyor. 26 labın tamamına ait raporlara aşağıdaki katalogdan ulaşılabilir. Gün numaraları kurs sırasını koruyor; Day 04'ten sonraki mevcut dosya Day 06. Aynı güne ait farklı çalışmalar ayrı satırlarda listeleniyor.

## Repo düzeni

| Konum | İçerik |
| --- | --- |
| `labs/` | Packet Tracer lab dosyaları (`.pkt`) |
| `docs/labs/` | Her lab için teknik rapor |
| `docs/assets/` | Raporlardaki topoloji çizimleri |
| `Lab Notları Part 1.pdf` | Kavramsal çalışma notlarım |

## Lab kataloğu

| Gün | Lab dosyası | Konu | Rapor |
| --- | --- | --- | --- |
| 01 | [Packet Tracer Introduction](labs/Day%2001%20Lab%20-%20Packet%20Tracer%20Introduction.pkt) | Packet Tracer arayüzü ve ağ cihazlarına giriş | [Raporu oku](docs/labs/day-01-packet-tracer-introduction.md) |
| 02 | [Connecting Devices](labs/Day%2002%20Lab%20-%20Connecting%20Devices.pkt) | Cihazlar, portlar ve kablo bağlantıları | [Raporu oku](docs/labs/day-02-connecting-devices.md) |
| 03 | [OSI Model](labs/Day%2003%20Lab%20-%20OSI%20Model.pkt) | OSI modeli ve katmanların ağ iletişimindeki rolü | [Raporu oku](docs/labs/day-03-osi-model.md) |
| 04 | [Basic Device Security](labs/Day%2004%20Lab%20-%20Basic%20Device%20Security.pkt) | Temel cihaz erişimi ve güvenlik ayarları | [Raporu oku](docs/labs/day-04-basic-device-security.md) |
| 06 | [Ethernet LAN Switching](labs/Day%2006%20Lab%20-%20Ethernet%20LAN%20Switching.pkt) | Ethernet LAN switching | [Raporu oku](docs/labs/day-06-ethernet-lan-switching.md) |
| 08 | [IPv4 Addresses](labs/Day%2008%20Lab%20-%20IPv4%20Addresses.pkt) | IPv4 adresleme | [Raporu oku](docs/labs/day-08-ipv4-addresses.md) |
| 09 | [Interface Configuration](labs/Day%2009%20Lab%20-%20Interface%20Configuration.pkt) | Arayüz yapılandırması | [Raporu oku](docs/labs/day-09-interface-configuration.md) |
| 11 | [Configuring Static Routes](labs/Day%2011%20Lab%20-%20Configuring%20Static%20Routes.pkt) | Statik yönlendirme yapılandırması | [Raporu oku](docs/labs/day-11-configuring-static-routes.md) |
| 11 | [Troubleshooting Static Routes](labs/Day%2011%20Lab%20-%20Troubleshooting%20Static%20Routes.pkt) | Statik yönlendirme ve hata giderme | [Raporu oku](docs/labs/day-11-troubleshooting-static-routes.md) |
| 12 | [Life of a Packet](labs/Day%2012%20Lab%20-%20Life%20of%20a%20Packet.pkt) | Paketin ağ boyunca izlediği yol | [Raporu oku](docs/labs/day-12-life-of-a-packet.md) |
| 15 | [VLSM](labs/Day%2015%20Lab%20-%20VLSM.pkt) | VLSM ile subnet planlama | [Raporu oku](docs/labs/day-15-vlsm.md) |
| 16 | [VLANs (Part 1)](labs/Day%2016%20Lab%20-%20VLANs%20%28Part%201%29.pkt) | VLAN temelleri | [Raporu oku](docs/labs/day-16-vlans-part-1.md) |
| 17 | [VLANs (Part 2)](labs/Day%2017%20Lab%20-%20VLANs%20%28Part%202%29.pkt) | VLAN yapılandırmasına devam | [Raporu oku](docs/labs/day-17-vlans-part-2.md) |
| 18 | [Multilayer Switching](labs/Day%2018%20Lab%20-%20Multilayer%20Switching.pkt) | Multilayer switching | [Raporu oku](docs/labs/day-18-multilayer-switching.md) |
| 19 | [DTP & VTP](labs/Day%2019%20Lab%20-%20DTP%20%26%20VTP.pkt) | DTP ve VTP | [Raporu oku](docs/labs/day-19-dtp-vtp.md) |
| 20 | [Analyzing STP](labs/Day%2020%20Lab%20-%20Analyzing%20STP.pkt) | Spanning Tree analizi | [Raporu oku](docs/labs/day-20-analyzing-stp.md) |
| 21 | [Configuring Spanning Tree](labs/Day%2021%20Lab%20-%20Configuring%20Spanning%20Tree.pkt) | Spanning Tree yapılandırması | [Raporu oku](docs/labs/day-21-configuring-spanning-tree.md) |
| 22 | [Rapid STP](labs/Day%2022%20Lab%20-%20Rapid%20STP.pkt) | Rapid Spanning Tree | [Raporu oku](docs/labs/day-22-rapid-stp.md) |
| 23 | [EtherChannel](labs/Day%2023%20Lab%20-%20EtherChannel.pkt) | EtherChannel | [Raporu oku](docs/labs/day-23-etherchannel.md) |
| 24 | [Floating Static Routes](labs/Day%2024%20Lab%20-%20Floating%20Static%20Routes.pkt) | Floating static routes | [Raporu oku](docs/labs/day-24-floating-static-routes.md) |
| 25 | [EIGRP Configuration](labs/Day%2025%20Lab%20-%20EIGRP%20Configuration.pkt) | EIGRP, passive interface ve unequal-cost yol seçimi | [Raporu oku](docs/labs/day-25-eigrp-configuration.md) |
| 26 | [OSPF (Part 1)](labs/Day%2026%20Lab%20-%20OSPF%20%28Part%201%29.pkt) | OSPF area 0 ve default route ilanı | [Raporu oku](docs/labs/day-26-ospf-part-1.md) |
| 27 | [OSPF (Part 2)](labs/Day%2027%20Lab%20-%20OSPF%20%28Part%202%29.pkt) | OSPF maliyetleri, referans bant genişliği ve Hello | [Raporu oku](docs/labs/day-27-ospf-part-2.md) |
| 28 | [OSPF (Part 3)](labs/Day%2028%20Lab%20-%20OSPF%20%28Part%203%29.pkt) | OSPF sorun giderme, serial bağlantı ve LSDB | [Raporu oku](docs/labs/day-28-ospf-part-3.md) |
| 29 | [HSRP Configuration](labs/Day%2029%20Lab%20-%20HSRP%20Configuration.pkt) | HSRPv2 ile yedekli default gateway | [Raporu oku](docs/labs/day-29-hsrp-configuration.md) |
| 31 | [IPv6 Configuration (Part 1)](labs/Day%2031%20Lab%20-%20IPv6%20Configuration%20%28Part%201%29.pkt) | IPv4/IPv6 dual-stack yapılandırması | [Raporu oku](docs/labs/day-31-ipv6-configuration-part-1.md) |

## Labları açma

1. Repoyu klonla veya ZIP olarak indir:

   ```bash
   git clone https://github.com/Lruquaf/My-Networking-Labs.git
   ```

2. `labs/` klasöründeki ilgili `.pkt` dosyasını Cisco Packet Tracer ile aç.
3. Topoloji üzerindeki görevleri ve ilgili lab raporunu birlikte incele.
4. Kendi denemelerin için dosyanın bir kopyasında çalış.

Mevcut lab dosyaları **Packet Tracer 9.0.1** ile kaydedilmiş. Cisco Packet Tracer'a [Cisco Networking Academy](https://www.netacad.com/) üzerinden ulaşılabilir.

## Çalışma notlarım

[Ağları Katman Katman Anlamak — Lab Notları Part 1](Lab%20Notlar%C4%B1%20Part%201.pdf), Ethernet, katmanlama, MAC/IP, ARP, routing, VLAN, STP ve OSPF üzerine çalıştığım kavramları bir araya getiriyor. Lab raporları belirli bir uygulamaya; bu notlar ise konular arasındaki ilişkilere odaklanıyor.

## Kaynaklar

- [Jeremy's IT Lab — CCNA 200-301](https://courses.jeremysitlab.com/p/ccna)
- [Cisco Networking Academy](https://www.netacad.com/)
- [Cisco teknik dokümantasyonu](https://www.cisco.com/c/en/us/support/index.html)

Bu repo kişisel uygulamalarımı ve notlarımı içerir. Kursun özgün görev ve materyalleri ilgili üreticilere aittir.
