🌍 [English](README.md) | [Türkçe](README.tr.md)

# 🤖 Codex CLI — Topluluk Rehberi

> Terminal üzerinden yazılım geliştirmede OpenAI Codex CLI kullanımı için pratik ve bağımsız bir rehber.

<div align="center">

![Rehber Lisansı](https://img.shields.io/badge/rehber%20lisansı-MIT-green)
![Codex](https://img.shields.io/badge/Codex-CLI-black)
![Platform](https://img.shields.io/badge/platform-Terminal-blue)

**Codex ile yerel çalışma alanınızdaki kodu anlayın, düzenleyin, çalıştırın ve doğrulayın.**

</div>

---

## Codex CLI Nedir?

**Codex CLI**, OpenAI tarafından geliştirilen ve bilgisayarınızda yerel olarak çalışan açık kaynaklı bir kodlama ajanıdır. Projeyi inceleyebilir, dosyaları düzenleyebilir, komutları çalıştırabilir ve değişiklikleri doğrulamanıza yardımcı olabilir.

Bu depo **bağımsız bir topluluk rehberidir**. OpenAI'ın resmi Codex deposu değildir ve OpenAI tarafından desteklendiği veya onaylandığı anlamına gelmez.

## Kurulum

### macOS / Linux

```bash
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

### Windows PowerShell

```powershell
powershell -ExecutionPolicy ByPass -c "irm https://chatgpt.com/codex/install.ps1 | iex"
```

### npm

```bash
npm install -g @openai/codex
```

### Homebrew

```bash
brew install --cask codex
```

Ardından Codex'i başlatın:

```bash
codex
```

## Hızlı Başlangıç

Terminali proje klasörünüzde açıp şu komutu çalıştırın:

```bash
codex
```

İstediğiniz sonucu doğal dille açıklayın. Örneğin:

```text
Bu projedeki kimlik doğrulama akışını açıkla.
Parser için testler ekle ve çalıştır.
Bu modülü dış API'sini değiştirmeden yeniden düzenle.
Son git diff'ini incele ve olası hataları belirt.
```

Codex proje bağlamını okuyabilir, düzenlemeler önerebilir veya uygulayabilir, yerel komutlar çalıştırabilir ve sonucu raporlayabilir.

## Kullanışlı Çalışma Şekilleri

### Bilmediğiniz bir projeyi anlamak

```text
Bu deponun mimarisini açıkla ve ana giriş noktalarını belirt.
```

### Odaklı bir değişiklik yapmak

```text
Kayıt formuna doğrulama ekle. Mevcut arayüzü koru ve ilgili testleri çalıştır.
```

### Değişiklikleri inceletmek

```text
Mevcut git diff'imi hata, güvenlik sorunu ve eksik testler açısından incele.
```

### Tek seferlik komut

```bash
codex "Son git commitindeki değişiklikleri açıkla"
```

## Kimlik Doğrulama

`codex` komutunu çalıştırıp giriş adımlarını izleyin. Codex, ChatGPT ile oturum açmayı destekler; ayrıca ek yapılandırmayla API anahtarı kullanımı da mümkündür.

## Güvenli Kullanım İpuçları

- Anlamadığınız komutları çalıştırmadan önce inceleyin.
- Gizli anahtarları ve üretim parolalarını repolarda tutmayın.
- Değişiklikleri görebilmek ve geri alabilmek için sürüm kontrolü kullanın.
- Düzenlemelerden sonra testleri ve lint kontrollerini çalıştırın.
- Bilmediğiniz projelerde geniş değişikliklerden önce yalnızca analiz isteyin.

## Resmi Kaynaklar

- Resmi depo: https://github.com/openai/codex
- Resmi Codex dokümantasyonu: https://developers.openai.com/codex
- Codex web deneyimi: https://chatgpt.com/codex

## Lisans

Bu **rehberin içeriği** [MIT Lisansı](LICENSE) ile sunulmaktadır.

Codex CLI, OpenAI tarafından sürdürülür ve kendi lisans şartları altında dağıtılır. Güncel proje lisansı ve koşulları için resmi Codex deposuna bakın.

---

Bu rehberi faydalı buluyorsanız repoya yıldız vermeniz diğer geliştiricilerin de keşfetmesine yardımcı olur.
