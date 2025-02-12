# Miku Miku Beam 💥⚡ (Ağ Stres Test Canavarı)

**Anime kızı Miku'yla hack dünyasına gir!** Proxy'lerini yükle, hedefini seç ve arka planda çalan hareketli J-pop şarkısı eşliğinde saldırıya geç! 🎮🔥

![Ekran Görüntüsü](docs/screenshot.png)

## Neler Var? 🚀

- 🐳 **Docker'da 1-Tık**: `docker-compose up` yaz, gerisini o halleder!
- 🌐 **Canlı İzleme Paneli**: Paketleri otur ve izle, "oha 15k istek gitmiş" de!
- 🎶 **Waifu Tasarım**: Pembe tema, sevimli Miku ikonları - gözlerin bayram etsin!
- 🧑💻 **Kolay Kurulum**: "data/proxies.txt"ye proxy'lerini doldur, gerisi çorap söküğü!
- 📊 **Gerçek Zamanlı Rapor**: " 500 error aldık abi ya:(" diye panik yapma, görürsün!
- 💣 **Saldırı Menüsü**:
  - `HTTP Flood` ➡️ Spam gibi HTTP at
  - `Bypass Mode` ➡️ Güvenlik duvarını atla (Çerezlerle falan oyna)
  - `Slowloris` ➡️ Bağlantıları sömür likeçi gibi
  - `Minecraft Vur` ➡️ Sunucunun MOTD'sini s*keyim
  - `TCP Kasırgası` ➡️ TCP paketlerini tükür!

## Kurulum Rehberi 🛠️

### Önceden Yüklemen Gerekenler 📦

- **Node.js** (v14+ yüklü olsun)
- **npm** (Node'la geliyor zaten)


### Geliştirici Modu (Kod Karalama Zamanı) 💻

1. Depoyu indir:
   ```bash
   git clone https://github.com/BenEmin55/MikuMikuBeam-Turkish
   cd mikumikubeam
   ```

2. Kütüphaneleri yükle:
   ```bash
   npm install
   ```

3. **Önemli Dosyalar**:
   - `data/proxies.txt` ➡️ Her satıra 1 proxy (Format: ip:port)
   - `data/uas.txt` ➡️ Sahte tarayıcı listesi (Chrome, Firefox vs.)

4. Başlat babuş:
   ```bash
   npm run dev
   ```
   - **Frontend**: `http://localhost:5173`
   - **Backend**: `http://localhost:3000`

### Canlı Mod (Gerçek Saldırı Zamanı) 💣

1. Projeyi derle:
   ```bash
   npm run build
   ```

2. Nuke'la:
   ```bash
   npm run start
   ```
   - Hepsi `http://localhost:3000`de toplanır!

## Nasıl Kullanılır? 🎮

1. **Hedef Seç**: "Target URL"ye saldıracağın siteyi yaz (Örn: `http://kurban.com`)

2. **Metodu Seç**: 
   - "HTTP Flood" ➡️ Klasik spam
   - "Bypass" ➡️ Akıllı saldırı (Bot olduğunu belli etmez)
   
3. **Önerilen Ayarlar**
   - ⏱️ Süre: 60 saniye ideal
   - 📦 Paket Boyutu: 512 byte tatlı kaçar
   - 🐢 Gecikme: 500ms (DDoS'tan kaçınmak için)

4. **BAŞLAT!** 🚀
	   - "Beam" butonuna bas ve Miku'nun şarkısı eşliğinde ddosu izle!

## Proxy Eklemek İçin 🕵️♂️

Sağ üstteki 📋 butonuna bas:
- Proxy formatları:
  - `ip:port`
  - `kullanici:parola@ip:port`
  - `socks5://ip:port` 

## İpuçları 💡

- 💣 **Minecraft Saldırısı**: Sunucu IP'sini yaz, "Minecraft Ping" seç - oyuncular giremesin!
- 🐢 **Slowloris**: Küçük paketlerle uzun süreli işkence yap!
- 🔥 **TCP Flood**: Hedefin portlarını balık istifi yaptır!


## SSS ❓

**S: Proxy ekledim ama çalışmıyor?**  
C: Ölü proxy koymuşsun, https://proxy6.net'ten taze proxyler al!

**S: "Concurrently hatası" alıyorum?**  
C: CMD'yi yönetici olarak aç veya iki ayrı terminalde `npm run dev:client` ve `npm run dev:server` çalıştır.

**S: Saldırı başlatınca bilgisayarım kasıyor?**  
C: 1000 thread açıp "oha" deme! Ayarlardan thread sayısını düşür.

## Uyarı ⚠️

⚠️ **BU ARACı OKUL SUNUCUSUNDA DENEME!**  
⚠️ **"SADECE EĞİTİM İÇİN" DE HER YERE YAZ!**

---

**LICENSE**: MIT (Yani "istediğini yap ama beni suçlama" lisansı )

---
