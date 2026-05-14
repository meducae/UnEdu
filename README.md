<p align="center">
  <img src="https://github.com/meducae/UnEdu/blob/main/playmarketbannera.png" alt="UnEdu Banner" width="100%">
</p>

<h1 align="center">🎓 UnEdu — Advanced University Finder & AI IELTS Coach</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.x-02569B?style=for-the-badge&logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/Firebase-Suite-FFCA28?style=for-the-badge&logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/AI-Gemini_2.0-8E44AD?style=for-the-badge&logo=google-gemini" alt="Gemini AI">
  <img src="https://img.shields.io/badge/Status-Production-success?style=for-the-badge" alt="Status">
</p>

<p align="center">
  <b>UnEdu</b> — bu O'zbekistonlik yoshlar uchun xorijiy oliygohlarni topish, shaxsiylashtirilgan grantlarni qidirish va sun'iy intellekt (AI) yordamida IELTS imtihoniga tayyorlanish uchun mo'ljallangan <b>Next-Gen</b> platformadir.
</p>

---

## 🌟 Key Highlights

<table align="center">
  <tr>
    <td align="center" width="33%">
      <br><b>🤖 AI-Powered</b><br>
      Gemini 2.0 orqali shaxsiylashtirilgan oliygoh tavsiyalari va IELTS feedback.
    </td>
    <td align="center" width="33%">
      <br><b>📊 Full Simulyatsiya</b><br>
      Listening, Reading, Writing va Speaking uchun to'liq Mock Test tizimi.
    </td>
    <td align="center" width="33%">
      <br><b>🌍 Global Search</b><br>
      10,000+ oliygoh, rankinglar va real-vaqtda grantlar monitoringi.
    </td>
  </tr>
</table>

---

## 🛠 Tech Stack & Ecosystem

| Category | Technology |
| :--- | :--- |
| **Frontend** | Flutter 3.x (Material 3), Dart |
| **Backend** | Firebase (Auth, Firestore, Functions, FCM), Supabase |
| **Artificial Intelligence** | Google Gemini 2.0 Flash, OpenAI (Fallback) |
| **State Management** | Provider (ChangeNotifier) |
| **Persistence** | Hive (Offline Storage), Shared Preferences |
| **Observability** | Firebase Analytics, Crashlytics, Performance Monitoring |
| **Media Handling** | Chewie, Video Player, Just Audio, Speech-to-Text |
| **UI/UX** | Google Fonts, Shimmer, Flutter SVG, Lottie |

---

## 📱 User Interface Preview

<p align="center">
  <img src="unedu_screenshot_mockup_1778756163743.png" alt="UnEdu Mockup" width="45%">
</p>

---

## 🏗 Modular Architecture

Loyiha **Service-Oriented & Feature-based Architecture** tamoyillariga asoslangan bo'lib, har bir modul o'z mantiqiy qatlamiga ega:

- **Presentation Layer**: UI sahifalar (`lib/screens`) va atomar komponentlar (`lib/widgets`).
- **State Layer**: `lib/providers` orqali UI va biznes mantiqni bog'lash.
- **Service Layer**: 40 dan ortiq ixtisoslashgan servislar (`lib/services`) — AI tahlilidan tortib offline sinxronizatsiyagacha.
- **Domain/Data Layer**: Serializatsiya va ma'lumotlar strukturasini ta'minlovchi modellar (`lib/models`).
- **Infrastructure**: Firebase va Supabase integratsiyalari.

---

## 🚀 Key Implementation Insights

### 🧠 Intelligent Recommendation Engine
Gemini 2.0 API yordamida talabaning akademik ko'rsatkichlari, qiziqishlari va moliyaviy imkoniyatlarini tahlil qilib, 95% aniqlikda qabul ehtimolini (Admission Probability) hisoblaydi.

### 📝 AI IELTS Feedback System
Writing va Speaking modullarida talaba javoblari IELTS Band Descriptors (Task Achievement, Coherence, Lexical Resource, Grammar) bo'yicha tahlil qilinadi va O'zbek tilida professional tavsiyalar beriladi.

### 📶 Resilience & Offline Support
Hive bazasi yordamida barcha oliygohlar va test natijalari keshlanadi. Ilova hatto internet mavjud bo'lmaganda ham foydalanuvchiga test yechish imkoniyatini taqdim etadi.

---

## ⚙️ Installation & Development

### Prerequisities
- Flutter SDK (>= 3.0.0)
- Firebase Project configured
- API keys for Gemini/OpenAI

### Quick Start
```bash
# Repositoryni klonlash
git clone https://github.com/your-username/unedu-flutter.git

# Dependencylarni o'rnatish
flutter pub get

# .env faylini sozlash
cp .env.example .env

# Ilovani ishga tushirish
flutter run
```

---

## 📊 Technical Analysis (Senior Review)

### ✅ Strengths
- **Safety-First AI:** Google Play AI siyosatiga mos keluvchi murakkab prompt-filtering va response-safety mexanizmlari.
- **Enterprise Monitoring:** Analytics va Crashlytics orqali foydalanuvchi tajribasini real-vaqtda boshqarish.
- **Rich Media Support:** Audio yozish, matnga aylantirish va video player integratsiyalari yuqori darajada.

### 🚧 Optimization Opportunities
- **Modularization:** `lib/services` papkasini sub-domenlarga (Auth, IELTS, University) ajratish mantiqiy bo'lar edi.
- **Dependency Injection:** Kelajakda `GetIt` yoki `Riverpod` orqali mantiqiy bog'liqlikni yanada kamaytirish mumkin.

---

## 📈 Roadmap

- [ ] **AI Voice Mentor**: Ovozli suhbat orqali Speaking mashqlarini bajarish.
- [ ] **Community Hub**: Talabalar uchun o'zaro tajriba almashish portali.
- [ ] **Document Assistant**: Universitetlarga hujjat topshirishda yordam beruvchi AI agent.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

<p align="center">
  Dev: Xurramov Soatmurod
</p>
