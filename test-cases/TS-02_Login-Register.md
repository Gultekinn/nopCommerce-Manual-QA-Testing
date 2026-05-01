# TS-02 | Login & Register

**Test Scope:** nopcommerce.com  
**TC Sayı:** 7 (TC_008 – TC_014)  
**Status:** ✅ Hamısı PASS

---

## TC_008 — Profil İkonu Hover — "Log in" və "Register" Görünməsi

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və istifadəçi qeydiyyatdan keçməyib |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Sağ yuxarı küncdəki Profil ikonunun üzərinə mausu gətir
2. Açılan "Login" və "Register" seçimlərini yoxla

**Expected Result:** İkonun altında dropdown açılmalı, "Log in" və "Register" görünməli, hover #40bdd7 olmalıdır  
**Actual Result:** Menyu uğurla açıldı, hər iki seçim nizamlı əks olundu, hover effekti düzgün işləyir ✅

---

## TC_009 — Yeni İstifadəçi Qeydiyyatı, Email Təsdiqi və Login

| | |
|---|---|
| **Pre-condition** | İstifadəçinin aktiv email ünvanı var və "Register" səhifəsindədir |
| **Test Data** | Email: gultkinzizova93@gmail.com / Password: ********* |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Bütün məcburi sahələri düzgün doldur
2. "Country" siyahısından ölkə seç
3. "REGISTER" düyməsinə kliklə
4. Təsdiq emailini aç və linkə klik et
5. "Log in" linkə kliklə, məlumatları daxil et
6. "LOG IN" düyməsinə kliklə

**Expected Result:** Qeydiyyatdan sonra email təsdiqi mesajı görünməlidir; login olduqdan sonra "My account" və "Log out" görünməlidir  
**Actual Result:** İstifadəçi qeydiyyatdan keçdi, email vasitəsilə hesabını təsdiqlədi və profilinə uğurla giriş etdi ✅

---

## TC_010 — "Log out" Funksionallığı

| | |
|---|---|
| **Pre-condition** | İstifadəçi ana səhifədədir |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Profil ikonunun üzərinə kliklə
2. "Log out" yazısına kliklə
3. Header-in sağ küncünə nəzər yetir

**Expected Result:** İstifadəçi sistemdən çıxmalı, "My account" və "Log out" yerinə "Log in" və "Register" gəlməlidir  
**Actual Result:** Hesabdan dərhal çıxış olundu, header ilkin halına (Login/Register) qayıtdı ✅

---

## TC_011 — Boş Sahələrlə Login Cəhdi

| | |
|---|---|
| **Pre-condition** | İstifadəçi "Login" səhifəsindədir |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Username" və "Password" sahələrini boş burax
2. "LOG IN" düyməsinə kliklə

**Expected Result:** Sistem girişi bloklamalı, "Login was unsuccessful. No customer account found" xəta mesajı görünməlidir  
**Actual Result:** Sistem girişi blokladı, password sahəsi avtomatik sıfırlandı, xəta mesajı çıxdı ✅

---

## TC_012 — Mövcud Olmayan Məlumatlarla Login Cəhdi

| | |
|---|---|
| **Pre-condition** | İstifadəçi "Login" səhifəsindədir |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Username" sahəsinə yanlış ad yaz (məs: user465674)
2. "Password" sahəsinə düzgün şifrə yaz
3. "LOG IN" düyməsinə kliklə

**Expected Result:** Sistem girişi bloklamalı, "Login was unsuccessful. No customer account found" xəta mesajı görünməlidir  
**Actual Result:** Sistem girişi blokladı, password sahəsi avtomatik sıfırlandı, xəta mesajı çıxdı ✅

---

## TC_013 — Düzgün Username, Yanlış Şifrə ilə Login Cəhdi

| | |
|---|---|
| **Pre-condition** | İstifadəçi "Login" səhifəsindədir |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Username" sahəsinə düzgün ad yaz
2. "Password" sahəsinə yanlış şifrə yaz
3. "LOG IN" düyməsinə kliklə

**Expected Result:** Sistem girişi bloklamalı, "Login was unsuccessful. No customer account found" xəta mesajı görünməlidir  
**Actual Result:** Sistem girişi blokladı, password sahəsi sıfırlanmadı, xəta mesajı çıxdı ✅

---

## TC_014 — "Forgot Username or Password?" Funksionallığı

| | |
|---|---|
| **Pre-condition** | İstifadəçinin qeydiyyatdan keçmiş aktiv hesabı var |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Forgot username or password?" linkinə kliklə
2. Email daxil et və "RECOVER" düyməsinə kliklə
3. Emaildəki linkə keçid et
4. Yeni şifrəni daxil et və təsdiqlə
5. Yeni şifrə ilə login et

**Expected Result:** Şifrə yeniləmə linki emailə gəlməlidir; dəyişdirildikdən sonra "Your password has been changed" mesajı görünməlidir; yeni şifrə ilə giriş uğurlu olmalıdır  
**Actual Result:** Email vasitəsilə şifrə yeniləndi və yeni şifrə ilə hesaba uğurlu giriş təmin olundu ✅
