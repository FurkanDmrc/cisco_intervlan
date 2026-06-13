
# 🔹 VLAN Segmentation & Inter-VLAN Routing Lab

Bu projede Cisco Packet Tracer kullanarak VLAN segmentasyonu ve VLAN'lar arası iletişim (Inter-VLAN Routing) yapılandırılmıştır.

---

## 📌 Proje Senaryosu

Aynı switch üzerinde çalışan farklı departmanların ağ trafiğini ayırmak ve güvenliği artırmak amacıyla VLAN yapısı kurulmuştur.

- VLAN 10 → Kullanıcılar
- VLAN 20 → Kullanıcılar
- VLAN 50 → Management

Router-on-a-Stick yöntemi kullanılarak VLAN’lar arası iletişim sağlanmıştır.

---

## 🧱 Kullanılan Teknolojiler

- Cisco Packet Tracer  
- VLAN (Virtual LAN)  
- Inter-VLAN Routing  
- Router-on-a-Stick  
- Trunk Port  
- Switch Virtual Interface (SVI)  

---

## ⚙️ Yapılandırma Özeti

### 🔹 Switch
- VLAN oluşturuldu (10, 20, 50)
- Port bazlı VLAN atamaları yapıldı
- Trunk port konfigüre edildi
- Management için VLAN 50 üzerinden IP verildi

### 🔹 Router
- Subinterface yapısı ile VLAN’lar tanımlandı
- Her VLAN için ayrı gateway IP verildi

---

## 🌐 IP Adresleme

| VLAN | Network        | Gateway        |
|------|---------------|----------------|
| 10   | 192.168.1.0   | 192.168.1.1    |
| 20   | 192.168.2.0   | 192.168.2.1    |
| 50   | 192.168.50.0  | 192.168.50.1   |

---

## 🧪 Testler

✅ Aynı VLAN içindeki cihazlar birbirini pingleyebiliyor  
✅ Farklı VLAN’lar router üzerinden haberleşebiliyor  
✅ Switch management IP adresine erişim sağlanabiliyor  

---

## 📸 Ekran Görüntüleri

Aşağıdaki çıktılar projede test edilmiştir:

- Topoloji görünümü  
- Ping testleri  
- `show vlan brief`  
- `show ip interface brief`  

---

## 💡 Kazanımlar

Bu proje ile:

- VLAN segmentasyonu mantığını anladım  
- Inter-VLAN Routing yapılandırmasını uyguladım  
- Gerçekçi bir ağ senaryosunu simüle ettim  

---


## 📂 Dosyalar

- `cisco_intervlan.pkt` → Packet Tracer proje dosyası  

---

## 🔗 İletişim

Bu proje öğrenme amaçlı hazırlanmıştır. Geri bildirimlere açığım 🚀
