# Login
|ID Test Case|Deskripsi|3|Input|Expected Result|
|---|---|---|---|---|
|TC - 001|Test Login Menggunakan Email Dan Password Yang Benar|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Email Address<br>3. Input Password<br> 4.Klik 'Login'        |Email : sizeliziogaming10@gmail.com <br> Password : Samarinda123|Login berhasil dan redirect ke halaman utama.|
| | | | | |
|TC - 002|Test Login Menggunakan Email Valid Dan Password Yang Salah|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br>2. Input Email Address<br>3. Input Password yang salah<br> 4.Klik 'Login'        |Email : sizeliziogaming10@gmail.com <br>Password : Samarinda321|Pesan Error : ' These credentials do not match our records.' |
| | | | | |
|TC - 003|Test Login Menggunakan Email salah Dan Password Yang Benar|1. Pergi Ke Website : https://qa-test.medifyapp.com/login <br>2. Input Email Address  yang salah <br>3. Input Password yang benar <br>4.Klik 'Login'        |Email : sizeliziogaming100@gmail.com <br>Password : Samarinda123|Pesan Error : ' These credentials do not match our records.' |
| | | | | |
|TC - 004|Test Login Menggunakan Email Kosong Dan Password Yang Benar|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Password<br> 3.Klik 'Login'        |Email : <br> Password : Samarinda123|Pesan Error : ' Please fill out this field.' |
| | | | | |
|TC - 005|Test Login Menggunakan Email Valid Dan Password Yang Kosong|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Email Address <br> 3.Klik 'Login'        |Email : sizeliziogaming10@gmail.com<br> Password : |Pesan Error : ' Please fill out this field.' |
| | | | | |
|TC - 006|Test Login Menggunakan Email tidak terdaftar Dan Password Yang Kosong|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Email Address <br> 3.Klik 'Login'        |Email : sizeliziogaming100@gmail.com<br> Password : |Pesan Error : ' These credentials do not match our records.' |
| | | | | |
|TC - 007|Test Login Menggunakan Format Email yang salah|1. Pergi Ke Website : https://qa-test.medifyapp.com/login <br>2. Input Email Address dengan format yang salah <br>3. Input Password<br>4. Klik 'Login'        |Email : sizeliziogaming10gmailcom <br>Password : Samarinda123|Pesan Error : ' Please include an '@' in the email address. 'sizeliziogaming10gmail.com' is missing an '@' ' |
| | | | | |
|TC - 008|Test Login Menggunakan Password yang sangat panjang|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Email Address <br> 3. Input Password sangat panjang<br> 4. Klik 'Login'        |Email : sizeliziogaming10@gmailcom <br>Password : Samarinda1234567891011121314151617181920|Pesan Error : ' These credentials do not match our records.' |
| | | | | |
|TC - 009|Test Login Menggunakan Karakter spesial di email|1. Pergi Ke Website : https://qa-test.medifyapp.com/login<br> 2. Input Email Address dengan karakter spesial <br>3. Input Password <br> 4. Klik 'Login'        |Email : sizeliziogaming10!@gmailcom <br>Password : Samarinda123|Pesan Error : ' These credentials do not match our records.' |
| | | | | |
|TC - 010|Test Login dengan field email dan password kosong|1. Pergi Ke Website : https://qa-test.medifyapp.com/login <br>2. Klik 'Login'        |Email : <br> Password : |Pesan Error : ' Please fill out this field.' |
