# "Atom Fizikasi" Mobil Ilovasi (Android APK & Web SPA)

Universitetlar va oliy ta'lim muassasalari uchun "Atom fizikasi" fani bo'yicha to'liq interfaol o'quv dasturi, virtual laboratoriyalar, modulli nazorat testlari, shaxsiy kabinet va yakuniy sertifikat tizimi.

---

## 📌 Ilova Tarkibi va Arxitekturasi

1. **8 ta O'quv Moduli va 15 ta Ilmiy-Nazariy Mavzu**:
   - Har bir mavzu 1000+ belgidan iborat akademik matn, formulalar, LaTeX ko'rinishidagi tenglamalar, interfaol SVG grafiklar va animatsiyalar bilan ta'minlangan.
   - Mavzular bosqichma-bosqich ochiladi (Linear Progression).

2. **Modul Oxiridagi Interfaol Nazorat Testlari (100% Sharti)**:
   - **1-Modul Testi**: 2-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 2-modul ochiladi.
   - **2-Modul Testi**: 4-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 3-modul ochiladi.
   - **3-Modul Testi**: 6-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 4-modul ochiladi.
   - **4-Modul Testi**: 9-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 5-modul ochiladi.
   - **5-Modul Testi**: 11-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 6-modul ochiladi.
   - **6-Modul Testi**: 13-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 7-modul ochiladi.
   - **7-Modul Testi**: 15-mavzudan so'ng joylashgan (5 ta savol). 100% natija bilan 8-modul ochiladi.
   - **8-Modul Testi**: O'quv-tadqiqot loyihalari yakunida joylashgan (5 ta savol). 100% natija bilan Yakuniy Nazorat Testi ochiladi.

3. **Yakuniy Nazorat Testi (15 ta Savol)**:
   - Barcha 8 ta modul 100% muvaffaqiyatli topshirilgandan so'ng ochiladi.
   - 100% natija qayd etilganda foydalanuvchiga rasmiy raqamli Akademik Sertifikat beriladi.

4. **Foydalanuvchi Shaxsiy Kabineti**:
   - Talaba anketasi: Ism, Familiya, OTM/Universitet, Fakultet/Guruh, Talaba ID kodi.
   - Dinamik progress indikatori (0% - 100%, 9 ta bosqich).
   - Har bir modulning joriy holati va test natijalari monitoringi.
   - Ma'lumotlarni xotirada (`localStorage`) avtomatik saqlash va sinov rejimida progressni tozalash funksiyasi.

5. **Akademik Sertifikat (Certificate of Academic Excellence)**:
   - Talabaning to'liq ismi-sharifi, OTM va fakulteti ko'rsatilgan rasmiy sertifikat.
   - QR-kod, elektron imzo, noyob seriya raqami (`AF-2026-XXXXX`) va oltin muhr bilan tasdiqlangan.
   - "Chop etish / PDF formatda saqlash" (`window.print()`) hamda "PNG formatida yuklab olish" (Canvas rendering) imkoniyati.

6. **12 ta Virtual Laboratoriya Simulyatsiyasi**:
   - Plank doimiysini aniqlash, Bote tajribasi, Fotoeffekt qonunlari, Frank va Gers tajribasi, Balmer seriyasi, Shtern-Gerlax tajribasi, Mozli qonuni, Zeeman effekti va b.

---

## 🚀 GitHub Actions orqali APK Yaratish Qadamlari

1. GitHub-da yangi shaxsiy yoki ochiq repozitoriy yarating (masalan: `atom-fizikasi-app`).
2. `atom_fizikasi_github_apk.zip` arxivini ochib, barcha fayllarni repozitoriyga yuklang (`git push`).
3. Repozitoriyda `.github/workflows/main.yml` avtomatik ishga tushadi.
4. "Actions" bo'limida bir necha daqiqada tayyor Android APK fayli hosil bo'ladi va yuklab olish uchun taqdim etiladi.
