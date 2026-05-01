# TS-04 | Frontend (Register)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 4 (TC_018 – TC_021)  
**Status:** ✅ Hamısı PASS

---

## TC_018 — Uğurlu Qeydiyyat

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır; istifadəçi qeydiyyatdan keçməyib |
| **Test Data** | Ad: Gultekin / Soyad: Azizova / Email: gultkinzizova93@gmail.com / Şifrə: Test1234! |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. nopcommerce.com/en/demo → Frontend yolu ilə sayta gir
2. Yuxarı sağdakı "Register" linkə klik et
3. Ad, soyad, e-mail, şifrə daxil et
4. "Register" düyməsinə kliklə

**Expected Result:** "Your registration completed" mesajı görünməlidir; istifadəçi avtomatik daxil edilməlidir  
**Actual Result:** "Your registration completed" mesajı göründü, istifadəçi avtomatik daxil edildi ✅

---

## TC_019 — Artıq Mövcud E-mail ilə Qeydiyyat

| | |
|---|---|
| **Pre-condition** | Həmin e-mail artıq sistemdə var |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Register" linkə klik et
2. Mövcud e-mail daxil et
3. "Register" düyməsinə kliklə

**Expected Result:** "The specified email already exists" xəta mesajı görünməlidir  
**Actual Result:** "The specified email already exists" xəta mesajı göründü ✅

---

## TC_020 — Boş Sahələrlə Qeydiyyat

| | |
|---|---|
| **Pre-condition** | Register səhifəsi açıqdır |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Bütün sahələri boş saxla
2. "Register" düyməsinə kliklə

**Expected Result:** Bütün məcburi sahələr üçün xəta mesajları görünməlidir  
**Actual Result:** Bütün məcburi sahələr üçün xəta mesajları göründü ✅

---

## TC_021 — Yanlış E-mail Formatı

| | |
|---|---|
| **Pre-condition** | Register səhifəsi açıqdır |
| **Test Data** | mail: gultinzizova |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. E-mail sahəsinə yanlış məlumat daxil et
2. "Register" düyməsinə kliklə

**Expected Result:** "Please enter a valid email address." xəta mesajı görünməlidir  
**Actual Result:** "Please enter a valid email address." xəta mesajı göründü ✅
