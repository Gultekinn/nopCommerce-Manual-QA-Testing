# TS-06 | Məhsul Axtarışı (Search)

**Test Scope:** demo.nopcommerce.com  
**TC Sayı:** 3 (TC_025 – TC_027)  
**Status:** ✅ Hamısı PASS

---

## TC_025 — Mövcud Məhsul Axtarışı

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır |
| **Test Data** | Axtarış: Apple |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Yuxarı sağdakı "Search store" sahəsinə klik et
2. Məhsul adı daxil et
3. "SEARCH" düyməsinə kliklə

**Expected Result:** Apple ilə bağlı məhsullar (Apple MacBook Pro və s.) siyahıda görünməlidir  
**Actual Result:** Apple ilə bağlı məhsullar siyahıda göründü ✅

---

## TC_026 — Mövcud Olmayan Məhsul Axtarışı

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır |
| **Test Data** | Axtarış: kskdjd |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Axtarış sahəsinə mövcud olmayan söz daxil et
2. "SEARCH" düyməsinə kliklə

**Expected Result:** "No products were found that matched your criteria." mesajı görünməlidir  
**Actual Result:** "No products were found that matched your criteria." mesajı göründü ✅

---

## TC_027 — Boş Axtarış

| | |
|---|---|
| **Pre-condition** | demo.nopcommerce.com açıqdır |
| **Severity** | Low |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Axtarış sahəsini boş burax
2. "SEARCH" düyməsinə kliklə

**Expected Result:** "Please enter some search keyword" xəbərdarlıq mesajı göstərilməlidir; axtarış nəticəsi yüklənməməlidir  
**Actual Result:** Xəbərdarlıq mesajı göstərildi, axtarış nəticəsi yüklənmədi ✅
