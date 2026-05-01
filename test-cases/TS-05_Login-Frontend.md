# TS-05 | Frontend (Login)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 3 (TC_022 – TC_024)  
**Status:** ✅ Hamısı PASS

---

## TC_022 — Düzgün Məlumatlarla Daxil Olma

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır; istifadəçi qeydiyyatdan keçib |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Yuxarı sağdakı "Log in" linkə klik et
2. E-mail və şifrəni daxil et
3. "Log in" düyməsinə kliklə

**Expected Result:** İstifadəçi uğurla daxil olmalıdır; "Log in" əvəzinə "My account" və "Log out" görünməlidir  
**Actual Result:** İstifadəçi uğurla daxil oldu, "My account" və "Log out" göründü ✅

---

## TC_023 — Yanlış Şifrə ilə Daxil Olma

| | |
|---|---|
| **Pre-condition** | Login səhifəsi açıqdır |
| **Test Data** | Email: gultkinzizova93@mail.com / Şifrə: yanlis123 |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Log in" linkə klik et
2. Düzgün e-mail, yanlış şifrə daxil et
3. "Log in" düyməsinə kliklə

**Expected Result:** "Login was unsuccessful. Please correct the errors and try again. The credentials provided are incorrect." xəta mesajı görünməlidir  
**Actual Result:** "Login was unsuccessful. The credentials provided are incorrect." xəta mesajı göründü ✅

---

## TC_024 — Boş Sahələrlə Daxil Olma

| | |
|---|---|
| **Pre-condition** | Login səhifəsi açıqdır |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Sahələri boş burax
2. "Log in" düyməsinə kliklə

**Expected Result:** Xəta mesajları göstərilməlidir; daxil olunmamalıdır  
**Actual Result:** Xəta mesajları göstərildi, daxil olunmadı ✅
