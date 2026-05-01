# TS-08 | İstək Siyahısı (Wishlist)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 3 (TC_031 – TC_033)  
**Status:** ✅ Hamısı PASS

---

## TC_031 — Ana Səhifədən Wishlist-ə Əlavə Etmək

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır |
| **Test Data** | Məhsul: Apple MacBook Pro |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Featured products" bölümündə ♡ (heart) ikonuna klik et

**Expected Result:** "The product has been added to your wishlist" mesajı görünməlidir; "Wishlist (0)" → "Wishlist (1)" olmalıdır  
**Actual Result:** Uğur mesajı göründü, "Wishlist (1)" oldu ✅

---

## TC_032 — Wishlist-dən Səbətə Köçürmək

| | |
|---|---|
| **Pre-condition** | Wishlist-də ən az 1 məhsul var |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Wishlist (1)" linkə klik et
2. Məhsulun "Add to cart" düyməsinə kliklə

**Expected Result:** Məhsul cart-a keçirilməlidir və wishlist boşalmalıdır  
**Actual Result:** Məhsul cart-a keçirildi, wishlist boşaldı ✅

---

## TC_033 — Wishlist-dən Məhsulu Silmək

| | |
|---|---|
| **Pre-condition** | Wishlist-də ən az 1 məhsul var |
| **Severity** | Low |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Wishlist" linkə klik et
2. "Remove" düyməsinə bas

**Expected Result:** Məhsul wishlist-dən silinməlidir; "Wishlist is empty" görünməlidir  
**Actual Result:** Məhsul silindi, "Wishlist is empty" göründü ✅
