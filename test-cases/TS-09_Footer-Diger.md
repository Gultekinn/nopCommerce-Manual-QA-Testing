# TS-09 | Ümumi Funksiyalar (Footer & Digər)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 3 (TC_034 – TC_036)  
**Status:** ✅ Hamısı PASS

---

## TC_034 — Community Poll-da Səsvermə

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır; poll bölümü görünür |
| **Test Data** | Seçim: Excellent |
| **Severity** | Low |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Ana səhifəni aşağı sürüşdür
2. "Community poll – DO YOU LIKE NOPCOMMERCE?" bölümünü tap
3. "Excellent" seçimini işarələ
4. "VOTE" düyməsinə kliklə

**Expected Result:** Səs qeydə alınmalıdır; nəticələr faiz şəklində göstərilməlidir  
**Actual Result:** Səs qeydə alındı, nəticələr faiz şəklində göstərildi ✅

---

## TC_035 — Footer Linklərinin İşləməsi

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Footer bölümünə get
2. "Shipping & returns" linkə klik et
3. Geri qayıt
4. "Contact us" linkə klik et

**Expected Result:** Hər link öz səhifəsini açmalıdır; səhifə düzgün yüklənməlidir  
**Actual Result:** Hər link öz səhifəsini açdı, səhifələr düzgün yükləndi ✅

---

## TC_036 — Hesab Məlumatlarını Yeniləmək

| | |
|---|---|
| **Pre-condition** | İstifadəçi daxil olmuşdur |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Yuxarıda adına klik et → "My account" seç
2. "Customer info" seç
3. Ad/soyad dəyiş
4. "Save" düyməsinə bas

**Expected Result:** Məlumatlar yenilənməlidir; "The customer info has been updated successfully." uğur mesajı görünməlidir  
**Actual Result:** Məlumatlar yeniləndi, uğur mesajı göründü ✅
