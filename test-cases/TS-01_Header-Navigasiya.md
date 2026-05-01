# TS-01 | Header & Naviqasiya

**Test Scope:** nopcommerce.com  
**TC Sayı:** 7 (TC_001 – TC_007)  
**Status:** ✅ Hamısı PASS

---

## TC_001 — Logo Funksionallığı

| | |
|---|---|
| **Pre-condition** | İstifadəçi nopcommerce.com saytını açmışdır |
| **Test Data** | https://www.nopcommerce.com/ |
| **Severity** | Low |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Mausu sol yuxarı küncdəki "nopCommerce" loqosunun üzərinə gətir
2. Loqonun üzərinə kliklə

**Expected Result:** When the logo is clicked, the homepage should reload  
**Actual Result:** When the logo is clicked, the homepage reloads successfully ✅

---

## TC_002 — Əsas Menyuların Görünməsi və Aktivliyi

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və nopcommerce.com ana səhifəsi yüklənib |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Loqonun sağ tərəfindəki "Product", "Downloads", "Support & services" və "Partners" yazılarını vizual olaraq yoxla
2. Hər bir menyu bəndinin üzərinə mausu gətirərək hover rəngini yoxla

**Expected Result:** All menu items should be visible on the right side of the logo, clickable, and display a blue (#40bdd7) hover effect  
**Actual Result:** Menus are correctly aligned and the blue hover effect (#40bdd7) is active ✅

---

## TC_003 — "Product" → "Industries" Alt Menyusu

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və nopcommerce.com ana səhifəsi yüklənib |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Mausu "Product" menyusunun üzərinə gətir
2. Birinci səviyyəli siyahının açıldığını yoxla
3. Mausu "Industries" bəndinin üzərinə gətir
4. Yana açılan ikinci səviyyəli menyunu vizual olaraq yoxla

**Expected Result:** First-level menu should open on hover; "Industries" should reveal a second-level side menu; all items should display #40bdd7 hover effect  
**Actual Result:** Both menu levels open correctly and hover effect works as expected ✅

---

## TC_004 — "Downloads" Menyusunda Alt Menyular

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və nopcommerce.com ana səhifəsi yüklənib |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Mausu "Downloads" menyusunun üzərinə gətir
2. Alt menyuların (Download nopCommerce, Marketplace, Translations, Copyright removal key, Mobile application, Web API, Microsoft Dynamics 365) göründüyünü yoxla
3. Hover rəngini yoxla

**Expected Result:** Dropdown should open correctly and all items should display #40bdd7 hover effect  
**Actual Result:** Dropdown opened immediately and hover effect displayed correctly in #40bdd7 ✅

---

## TC_005 — "Support & Services" Menyusunda Alt Menyular

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və nopcommerce.com ana səhifəsi yüklənib |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Mausu "SUPPORT & SERVICES" menyusunun üzərinə gətir
2. Alt menyuların (Training, Documentation, Community forums, Premium support services, Request a quote, Contact us) göründüyünü yoxla
3. Hover rəngini yoxla

**Expected Result:** Dropdown should open correctly and all items should display #40bdd7 hover effect  
**Actual Result:** Dropdown opened immediately and hover effect displayed correctly in #40bdd7 ✅

---

## TC_006 — Dil Seçim Menyusu

| | |
|---|---|
| **Pre-condition** | Brauzer açıqdır və nopcommerce.com ana səhifəsi yüklənib |
| **Severity** | Medium |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Sağ yuxarı küncdə "English" yazısının üzərinə kliklə
2. Açılan siyahıda bütün dil seçimlərini yoxla
3. Hover rəngini müşahidə et
4. Siyahıdan "Italiano" yazısına kliklə

**Expected Result:** A vertical list of 11 languages should appear; hover should show #40bdd7; selecting "Italiano" should reload the page with URL .../it and Italian menu labels  
**Actual Result:** 11-language list appeared, hover worked correctly, site language changed to Italian successfully ✅

---

## TC_007 — "GET STARTED" Düyməsi

| | |
|---|---|
| **Pre-condition** | İstifadəçi nopcommerce.com/en/get-started saytını açmışdır |
| **Test Data** | https://www.nopcommerce.com/en/get-started |
| **Severity** | High |
| **Status** | ✅ PASS |

**Test Addımları:**
1. Sağ yuxarı küncdəki "GET STARTED" düyməsini vizual olaraq yoxla
2. Mausu düymənin üzərinə gətirərək hover rəngini müşahidə et
3. "GET STARTED" düyməsinə kliklə

**Expected Result:** Button should have rounded corners with white centered text; hover should change background to #363e4e; click should redirect to .../get-started page with "Get started" heading  
**Actual Result:** Button design is clean, hover effect works correctly, page redirected to get-started with "Install nopCommerce yourself" and "Create your store with experts" sections ✅
