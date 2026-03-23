# Test Cases - Login Funksionallığı

| ID | Başlıq | Addımlar | Gözlənilən Nəticə | Status |
|----|--------|----------|-------------------|--------|
| TC01 | Uğurlu Giriş | 1. Saytı aç <br> 2. 'standard_user' yaz <br> 3. 'secret_sauce' yaz <br> 4. Login sıx | Ana səhifə (Products) açılmalıdır | Pass |
| TC02 | Səhv şifrə | 1. Saytı aç <br> 2. 'standard_user' yaz <br> 3. '12345' yaz <br> 4. Login sıx | "Username and password do not match" xətası | Pass |
| TC03 | Boş istifadəçi adı | 1. Saytı aç <br> 2. Şifrəni yaz <br> 3. Login sıx | "Username is required" xətası | Pass |
