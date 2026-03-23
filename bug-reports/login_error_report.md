# Bug Report: Login Səhifəsində Xəta Mesajı Görünmür

**ID:** BUG001
**Severity:** High
**Priority:** Medium

## Təsvir (Description)
İstifadəçi login sahəsini boş qoyub düyməni sıxdıqda xəta mesajı qırmızı rəngdə deyil, şəffaf görünür.

## Addımlar (Steps to Reproduce)
1. https://www.saucedemo.com saytına daxil ol.
2. Username və Password sahələrini boş saxla.
3. 'Login' düyməsinə kliklə.

## Gözlənilən Nəticə (Expected Result)
Qırmızı fonda "Epic sadface: Username is required" mesajı çıxmalıdır.

## Vizual Sübut (Screenshot)
![Bug Evidence](./screenshoot.png)

## Faktiki Nəticə (Actual Result)
Xəta sahəsi yaranır, amma mətn görünmür (invisible).

## Mühit (Environment)
- Browser: Chrome v120
- OS: Windows 11
