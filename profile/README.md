# 💚 أهلاً بكم في فريق عطاء الذكي | Welcome to Ataa Smart Charity Ecosystem

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:047857&height=180&section=header&text=Ataa%20Charity%20Ecosystem&fontSize=40&fontColor=ffffff&fontFamily=Outfit" width="100%" />
</div>

فريق **عطاء** يعمل على بناء وإتاحة حلول برمجية متكاملة ومفتوحة المصدر لدعم وإدارة المؤسسات الخيرية وحملات التبرع، وتسهيل تتبع التدفقات المالية وتقارير المستفيدين إلكترونياً.

**Ataa Smart Charity Ecosystem** provides comprehensive open-source digital solutions to support and scale charitable organizations, campaign funding operations, donor engagements, and transparent audit telemetry.

---

## 🧬 بنية النظام وتكامل الخدمات | Ecosystem Architecture

تتصل الواجهات المتعددة بالخادم الخلفي لتسهيل وتنظيم عمليات التبرع:

```mermaid
graph TD
    FlutterClient[Ataa-Care-Flutter<br/>Mobile Donor Client] -->|REST Queries| API[Ataa-Charity-Platform-API<br/>Node.js REST API Backend]
    WebClient[Ataa-Smart-Charity-Platform<br/>Static Web Portal] -->|Campaign Registry| API
    API --> DB[(MySQL/MongoDB Database)]
```

---

## 📂 مستودعات النظام (Our Repositories)

| المستودع (Repository) | النوع | الوصف (Description) | الشارات التقنية (Tech Badges) |
| :--- | :--- | :--- | :--- |
| 📱 **[Ataa-Care-Flutter](https://github.com/Ataa-Charity-Viewer-Team/Ataa-Care-Flutter)** | Mobile | تطبيق الهاتف الذكي الموجه للمتبرعين لمتابعة واستكشاف الحملات الخيرية الفعالة والتبرع الفوري. | <img src="https://img.shields.io/badge/Flutter-v3-blue?logo=flutter&style=flat-square" alt="Flutter" /> <img src="https://img.shields.io/badge/Dart-v3-blue?logo=dart&style=flat-square" alt="Dart" /> |
| ⚙️ **[Ataa-Charity-Platform-API](https://github.com/Ataa-Charity-Viewer-Team/Ataa-Charity-Platform-API)** | Backend | خادم البرمجة الخلفي لإدارة الحملات وتوثيق المتبرعين والجمعيات الشريكة والتحقق من المعاملات. | <img src="https://img.shields.io/badge/Node.js-v18-green?logo=nodedotjs&style=flat-square" alt="Node.js" /> <img src="https://img.shields.io/badge/Express.js-v4-black?logo=express&style=flat-square" alt="Express.js" /> |

---
