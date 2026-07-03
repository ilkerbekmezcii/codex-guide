🌍 [English](README.md) | [Türkçe](README.tr.md) | [Español](README.es.md)

# 🤖 Codex CLI — Genel Kullanım Kılavuzu

> **OpenAI tarafından geliştirilen ve yerel kabuğunuzda çalışan terminal tabanlı yapay zeka kodlama yardımcısı.**

<div align="center">

![Sürüm](https://img.shields.io/badge/version-latest-blue)
![Lisans](https://img.shields.io/badge/license-Proprietary-red)

</div>

---

## 📚 İçindekiler

- [Codex CLI Nedir?](#codex-cli-nedir)
- [Kurulum](#kurulum)
- [Hızlı Başlangıç](#hızlı-başlangıç)
- [Etkileşimli Mod (TUI)](#etkileşimli-mod-tui)
- [Yapılandırma](#yapılandırma)
- [Slash Komutları](#slash-komutları)
- [Temel Kısayollar](#temel-kısayollar)
- [İpuçları ve Hileler](#ipuçları-ve-hileler)
- [Kaynaklar](#kaynaklar)
- [Hızlı Başvuru Kartı](#hızlı-başvuru-kartı)

---

## Codex CLI Nedir?

**Codex CLI**, OpenAI tarafından geliştirilen terminal tabanlı bir yapay zeka kodlama asistanıdır. Dosyaları okuma, kod yazma, düzenleme ve yerel testleri çalıştırma işlemlerini terminal üzerinden yönetmenizi sağlar.

---

## Kurulum

### 🪟 Windows (WinGet)
```powershell
winget install OpenAI.Codex
```

### Global Kurulum (npm)
```bash
npm install -g @openai/codex
```

### 🍎 macOS / 🐧 Linux (Install Script)
```bash
curl -fsSL https://chatgpt.com/codex/install.sh | sh
```

---

## Hızlı Başvuru Kartı

```
┌──────────────────────────────────────────────────────────┐
│                 🤖 Codex Hızlı Başvuru                   │
├──────────────────────────────────────────────────────────┤
│                                                          │
│  BAŞLAT                    YÖNET                         │
│  codex           .......  TUI Başlat      /new           │
│  codex "prompt"  .......  Prompt ile      /clear         │
│                                           /quit          │
│                                                          │
│  EDİTÖR                    KISAYOL TUŞLARI               │
│  @dosya          .......  Dosya ekle      Ctrl+C         │
│  !komut          .......  Shell çalıştır  Ctrl+D         │
│  Shift+Enter     .......  Yeni satır      Ctrl+O         │
│                                           Ctrl+L         │
│                                                          │
│  AYARLAR                   BAĞLAM                        │
│  /config         .......  Ayarlar Paneli  /ide           │
│  /model          .......  Modeli değiştir /status        │
│  /permissions    .......  Yetkileri yönet /agent         │
│  /approve        .......  Onay ayarları   /vim           │
│                                                          │
└──────────────────────────────────────────────────────────┘
```
