# TS-07 | Alış-veriş Səbəti (Shopping Cart)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 3 (TC_028 – TC_030)  
**Status:** ✅ Hamısı PASS

---

## TC_028 — Featured Məhsulu Səbətə Əlavə Etmək

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com ana səhifəsi açıqdır; Featured products bölümü görünür |
| **Test Data** | Məhsul: Apple MacBook Pro ($1,800.00) |
| **Severity** | Critical |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Featured products" bölümündə məhsulu tap
2. "ADD TO CART" düyməsinə kliklə
3. Detallar səhifəsindən seçimlərini et
4. "ADD TO CART" düyməsinə kliklə

**Expected Result:** "The product has been added to your shopping cart" mesajı görünməlidir; "Shopping cart (0)" → "Shopping cart (1)" olmalıdır  
**Actual Result:** Uğur mesajı göründü, "Shopping cart (1)" oldu ✅

---

## TC_029 — Səbətdəki Miqdarı Dəyişmək

| | |
|---|---|
| **Pre-condition** | Səbətdə ən az 1 məhsul var |
| **Test Data** | Qty: 3 |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Yuxarı sağdakı "Shopping cart (1)" linkə klik et
2. Qty sahəsinin dəyərini 3-ə dəyiş

**Expected Result:** Miqdar 3-ə yenilənməlidir; Sub-Total avtomatik dəyişməlidir  
**Actual Result:** Miqdar 3-ə yeniləndi, Sub-Total avtomatik yenidən hesablandı ✅

---

## TC_030 — Məhsulu Səbətdən Silmək

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com/cart açıqdır |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. "Shopping cart" səhifəsinə klik et
2. Məhsulun yanındakı "Remove" (x) düyməsinə bas

**Expected Result:** Məhsul silinməlidir; "Your Shopping Cart is empty!" mesajı görünməlidir  
**Actual Result:** Məhsul silindi, "Your Shopping Cart is empty!" mesajı göründü ✅
