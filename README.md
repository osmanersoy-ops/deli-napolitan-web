# 🍕 Deli Napolitan — Resmi Web Sitesi (Vercel Dağıtımı)

Bu klasör, Deli Napolitan'ın ana web sitesi (`delinapolitan.com`) için hazırlanan ultra hafif, yüksek hızlı ve minimalist editoryal landing portalıdır.

---

## 📁 Klasör İçeriği
- `index.html`: Vercel'de yayına girecek optimize edilmiş ana sayfa.
- `preview_homepage.html`: Yerel tarayıcı önizleme dosyası.
- `assets/logo.png`: Yüksek çözünürlüklü marka logosu.
- `vercel.json`: Güvenlik başlıkları ve önbellek yapılandırması.

---

## 🚀 Vercel Kurulum Adımları (3 Dakika)

### 1. Adım: GitHub Deposu Açma
1. [GitHub](https://github.com/new) hesabınıza (`osmanersoy-ops`) giriş yapın.
2. Yeni bir repo oluşturun:
   - Repository name: `deli-napolitan-web`
   - Public veya Private seçin.
3. Terminal'de bu klasördeyken şu komutları çalıştırarak dosyaları gönderin:

```bash
git remote add origin https://github.com/osmanersoy-ops/deli-napolitan-web.git
git branch -M main
git push -u origin main
```

---

### 2. Adım: Vercel Projesini Başlatma
1. [vercel.com](https://vercel.com) paneline gidin.
2. Sağ üstten **"Add New..."** > **"Project"** seçin.
3. GitHub listenizden **`deli-napolitan-web`** reposunu seçip **"Import"** butonuna basın.
4. Framework Preset olarak **"Other"** kalabilir.
5. Mavi **"Deploy"** butonuna tıklayın. Saniyeler içinde siteniz hazır!

---

### 3. Adım: Alan Adını (`delinapolitan.com`) Vercel'e Bağlama
1. Vercel'de projenizin **Settings** > **Domains** sekmesine gidin.
2. `delinapolitan.com` ve `www.delinapolitan.com` alan adlarını yazıp ekleyin.
3. Vercel'in size vereceği DNS kayıtlarını (A Record ve CNAME) alan adı yönetim panelinizden (Squarespace Domains veya registrar) güncelleyin:
   - **Tip: A** | Ad: `@` | Değer: `76.76.21.21`
   - **Tip: CNAME** | Ad: `www` | Değer: `cname.vercel-dns.com`
