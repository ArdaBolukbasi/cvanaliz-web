
<div align="center">

  <img src="favicon.png" alt="CV Analiz Logo" width="120" height="120" />

  # 🚀 CV Analiz AI - Web Wrapper
  
  **CV Analiz Uygulaması için SEO ve Domain Yönetim Katmanı**

  [![Live Demo](https://img.shields.io/badge/Canlı_Sürüm-cvanaliz.com.tr-3b82f6?style=for-the-badge&logo=googlechrome&logoColor=white)](https://cvanaliz.com.tr)
  [![Main Repo](https://img.shields.io/badge/Ana_Kaynak_Kodları-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ArdaBolukbasi/cvanaliz)
  [![Developer](https://img.shields.io/badge/Geliştirici-Arda_Bölükbaşı-10b981?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ardabolukbasi)

  <p align="center">
    <strong>⚠️ DİKKAT:</strong> Bu repo sadece web arayüzü ve domain yönlendirmesi içindir.<br>
    Asıl yapay zeka uygulamasının kaynak kodlarına ulaşmak için aşağıdaki bağlantıyı kullanın:<br>
    <br>
    👉 <strong><a href="https://github.com/ArdaBolukbasi/cvanaliz">ANA PROJE KAYNAK KODLARI (CVANALIZ)</a></strong> 👈
  </p>

</div>

---

## 🏗️ Mimari ve Teknoloji Tercihleri

Bu proje, karmaşık bir yapay zeka uygulamasını son kullanıcıya en hızlı ve maliyet etkin şekilde ulaştırmak için **Hibrit Yayım Modeli** kullanır. İşte kullanılan teknolojiler ve seçilme nedenleri:

### 1. Statik Web Katmanı (HTML5/CSS3)
*   **Neden Seçildi?** Google ve diğer arama motorları (SEO) için en iyi performansı saf HTML sayfaları verir.
*   **Amacı:** Kullanıcı siteye girdiğinde `cvanaliz.com.tr` domainini karşılamak, hızlı bir açılış sunmak ve arama motorlarına sitenin içeriğini (meta tagler, başlıklar) doğru bir şekilde bildirmek.

### 2. Iframe Entegrasyonu
*   **Neden Seçildi?** Hugging Face Spaces gibi platformlarda çalışan uygulamaları (Streamlit/Gradio) doğrudan bir domaine bağlamak bazen karmaşık veya maliyetli olabilir.
*   **Amacı:** Arka planda çalışan güçlü AI uygulamasını, sanki bu sitenin doğal bir parçasıymış gibi tam ekran olarak kullanıcıya sunmak. Bu sayede kullanıcı URL değiştirmeden uygulamayı kullanabilir.

### 3. Hugging Face Spaces (Backend)
*   **Neden Seçildi?** Büyük LLM (Gemini vb.) modellerini ve Python tabanlı backend kodlarını çalıştırmak için yüksek işlem gücü ve hazır altyapı sunar.
*   **Amacı:** Uygulamanın beyni burada çalışır. CV okuma, analiz etme ve puanlama işlemleri bu sunucuda gerçekleşir. Bu repo sadece o sunucuya açılan bir kapıdır.

## � Proje Yapısı

Bu yapı sayesinde:
1.  **SEO Avantajı:** Statik site sayesinde Google'da üst sıralarda çıkma şansı artar.
2.  **Yüksek Performans:** Arayüz katmanı çok hafif olduğu için anında yüklenir.
3.  **Kolay Yönetim:** Domain ayarları backend'den bağımsız olarak yönetilebilir.

## 🔗 Bağlantılar

*   **Web Sitesi:** [cvanaliz.com.tr](https://cvanaliz.com.tr)
*   **Asıl Proje (GitHub):** [github.com/ArdaBolukbasi/cvanaliz](https://github.com/ArdaBolukbasi/cvanaliz)
*   **Geliştirici:** Arda Bölükbaşı

---

<div align="center">
  <sub>© 2024 CV Analiz AI. Tüm hakları saklıdır.</sub>
</div>
