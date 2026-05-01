# TS-03 | Sayta Giriş Axını (nopcommerce.com → VIEW DEMO → Frontend)

**Test Scope:** nopcommerce.com → demo.nopcommerce.com  
**TC Sayı:** 3 (TC_015 – TC_017)  
**Status:** ✅ Hamısı PASS

---

## TC_015 — "View Demo" Düyməsinə Klik

| | |
|---|---|
| **Pre-condition** | nopcommerce.com/en ana səhifəsi açıqdır |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Ana səhifədə "VIEW DEMO" düyməsini tap
2. "VIEW DEMO" düyməsinə klik et
3. Yeni səhifənin yüklənməsini gözlə

**Expected Result:** nopcommerce.com/en/demo səhifəsi açılmalıdır; "nopCommerce Store Demo" başlığı görünməlidir; Admin area və Frontend seçimləri mövcud olmalıdır  
**Actual Result:** nopcommerce.com/en/demo səhifəsi açıldı, başlıq görünür, Admin area və Frontend seçimləri mövcuddur ✅

---

## TC_016 — Demo Səhifəsindən "Frontend" Seçimi

| | |
|---|---|
| **Pre-condition** | nopcommerce.com/en/demo səhifəsi açıqdır; Admin area və Frontend kartları görünür |
| **Test Data** | https://demo.nopcommerce.com/ |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Frontend" kartını tap
2. "Frontend" linkə klik et
3. Yeni tabda açılmasını gözlə

**Expected Result:** demo.nopcommerce.com açılmalıdır; header-də valyuta seçimi, Register, Log in, Wishlist, Shopping cart görünməlidir; 7 kateqoriya menyusu mövcud olmalıdır  
**Actual Result:** Səhifə uğurla açıldı, bütün header elementləri aktivdir, 7 kateqoriya menyusu tam görünür ✅

---

## TC_017 — Frontend Ana Səhifə Elementlərinin Müşahidəsi

| | |
|---|---|
| **Pre-condition** | https://demo.nopcommerce.com/ ana səhifəsi açıqdır |
| **Test Data** | https://demo.nopcommerce.com/ |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Səhifənin yuxarı hissəsini müşahidə et (header)
2. Naviqasiya menyusunu müşahidə et
3. Banner/slider bölümünü müşahidə et
4. Featured products bölümünü müşahidə et
5. News bölümünü müşahidə et
6. Footer bölümünü müşahidə et

**Expected Result:** Header: Register, Log in, Wishlist, Shopping cart; Menyu: 7 kateqoriya; Banner: Galaxy S24 slayderi; Featured products, News, Community poll və Footer bölümləri görünməlidir  
**Actual Result:** Gözlənilən nəticələrə uyğundur ✅
