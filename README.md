# QA-practise-sayt-yoxlan-
QA practise saytında pozitiv və neqativ yoxlamalar aparmaq
Səbət yoxlaşı
Title : Məhsulun səbətə əlavə edilməsi
Description : Seçilmiş hər hansısa bir məhsulu səbətə əlavə etmək , məhsulun səbətdə görsənməsi.
Pre-condition : Sistem aktivdir. 	İstifadəçi sayta daxil olub.
Prioroty : High
Steps : 
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4.Səbət əlavə et

Excepted result : Məhsul səbətdə görsənməlidir.
Actual result : Səbətə əlavə edilən məhsul səbətdə görsənir.



Title : Məhsulun səbətdən silinməsi
Description : Seçilmiş hər hansısa bir məhsulu səbətə əlavə etmək , məhsulun səbətdə görsənməsi.
Səbətdən məhsulu uğurlu şəkildə silmək
Pre-condition : Sistem aktivdir. 	İstifadəçi sayta daxil olub. Əlavə edilmiş məhsul səbətdə görsənir.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4.Səbətə əlavə et
5.Əlavə edilmiş məhsulu səbətdən sil , ( remove ) buttonunu kliklə

Excepted result : Səbətdəki məhsul uğurlu şəkildə silinməlidir.
Actual result : Məhsul remove buttonunu kliklədikdə uğurlu şəkildə silinir.






Title : Səbətdəki məhsulun artırılması və azaldılması
Description :  Seçilmiş məhsulun sayının  səbətdə artırılması və azaldılması
Pre-condition : Sistem aktivdir .Məhsullar görsənir. İstifadəçi sayta daxil olub. Səbətə məhsul əlavə edilib.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4. Məhsulu səbətə əlavə et
5.Yuxarı küncdə səbət işarəsinə kliklə 
6.Açılan səhifədə məhsulun sayını artır və ya azalt
Excepted result :  Səbətdəki məhsulun sayını artırmaq və ya azaltmaq mümkün olmalıdır.
Actual result : Səbətdəki məhsulun sayını artırmaq və ya azaltmaq button aktivdir və işlək vəziyətdədir.Məhsulu sayını azaltmaq və artırmaq olur.
Title : Kupondan istifadə etmək.
Description : Səbətdəki məhsula endirim olunması üçün kupon istafədə etmək.
Pre-condition : Sistem aktivdir .Məhsullar görsənir. İstifadəçi sayta daxil olub. Səbətə məhsul əlavə edilib.
Prioroty : Medium
Steps :
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4. Məhsulu səbətə əlavə et
5.Yuxarı küncdə səbət işarəsinə kliklə 
6.Açılan səhifədə  sağ tərəfdə order summary hissəsində cupon code bölməsinə cupon əlavə et
7.Apply buttonunu kliklə
Excepted result : Əlavə edilmiş kuppon koduna uyğun olaraq endirim əldə edilməlidir.
Actual result : Kupona uyğun olaraq endirim əldə edilir.

 Negative Title : Seçilmiş məhsul üçün ödəniş edilməsi
Description : Hər hansısa bir məhsulu əldə etmək üçün ödənişin ödənməsi.
Pre-condition : : Sistem aktivdir .Məhsullar görsənir. İstifadəçi sayta daxil olub. Səbətə məhsul əlavə edilib.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4. Məhsulu səbətə əlavə et
5.Yuxarı küncdə səbət işarəsinə kliklə 
6.Açılan səhifədə  sağ tərəfdə order summary bölməsində qiymətlərin düzgünlüyünü yoxla.
Excepted result :   Sonda məhsulun qiymətinə , tax və çatdırılma ödəninə uyğun qiymət görsənməlidir. Check out kliklədikdə ödəniş üçün səhifə açılmalıdır.
Actual result : Ödəniş üçün hazır olan məhsulunda qiymətlər düzgün qeyd edilməyib.Gərəyindən artıq qiymət göstərir. Checkout kliklədikdə ödəniş səhifəsi açılmır , əsas ekrana geri qayıdır.Order placed yazısı görsənir.

Title : Məhsulu wishlistə əlavə etmə
Description :  Seçilmiş məhsulu istək siyahısına əlavə etmək və silmək.
Pre-condition : Sistem aktivdir .Məhsullar görsənir. İstifadəçi sayta daxil olub.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Hər hansısa bir məhsul seç
3.Məhsulun üzərinə kliklə
4. Wishlist buttonuna kliklə 

Excepted result : Seçilmiş  məhsul uğulu şəkildə istək siyahısına daxil edilməlidir.
Actual result : Sistemdə dəyişiklik olmur. Wishlist bölməsi görsənmir.


Sing up - Profile
Title : Yeni istifadəçi sistemə daxil olması
Description : Sistemdə mövcud olmamış yeni istifadəçinin hesab yaratması
Pre-condition : Sistem aktivdir. Sing up button işləyir
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Yuxarı sağ küncdə sing in button kliklə
3.Aşılan səhifədə aşağı hissədə olan No account? Create one bölməsinə kliklə.
4.Açılan pəncərdə zəruri məlumatları  doğru şəkildə əlavə et.
5.Create buttonunu kliklə
Excepted result : İstifadəçi sistemə əlavə edilməlidir və yeni səhifə açılmalıdır.
Actual result : İstifadəçi uğurlu şəkildə sistemə əlavə edildi. Əsas səhifə istifadəçinin adı altında görsəndi.


Title : İstifadəçi məlumatlarının dəyişdirilməsi
Description : Sistemdə qeydiyyatdan keçmiş istifadəçinin məlumatlarını dəyişmək.
Pre-condition : Səhifə aktivdir. İstifadəçinin məlumatları sistemdə görsənir.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Yuxarı sağ küncdə  istifadəçi adının üzərinə kliklə
3.Açılan səhifədə  istifadəçinin məlumatları görsənir.
4.Lazım olan hissədə  məlumatları yenisi ilə əvəz et
5.Save changes buttonunu kliklə.
Excepted result : Uğurlu şəkildə istifadəçinin məlumatları yenilənməlidir.
Actual result : İstifadə məlumatları dəyiçdirilir və yenisi ilə əvəz olunur.
 Negative Title : Logout prosesinin düzgün işləməsinin yoxlanması
Description : İstifadəçi sistemi uğurlu şəkilədə tərk edə bilirmi yoxlanışı
Pre-condition : Səhifə aktivdir. İstifadəçinin məlumatları sistemdə görsənir.Logout button görsənir
Prioroty :High
Steps :
1.QA practice səhifəsinə daxil ol
2.Yuxarı sağ küncdə  istifadəçi adının üzərinə kliklə
3.Açılan səhifədə  istifadəçinin məlumatları görsənir.
4.Yuxarı küncdə logout buttonuna kliklə
Excepted result : User uğurlu şəkildə sistemi tərk etməli idi və əsas səhifədə userin adı görsənməməli idi.
Actual result : Logout buttonuna kliklədikdə səhifə yenilənir və əsas səhifə açılır.

Login 
Title : Uğurlu şəkildə sistemə daxil olmaq
Description : İstifadəçi məlumatlarını daxil edərək sistemə daxil olmaq
Pre-condition : Səhifə aktivdir və sing in button görsənir(aktivdir)
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Yuxarı küncdə sing in buttonunu kliklə
3.Boş xanaları doldur.
4.Sistemə daxil ol 
Excepted result : İstifadəçi uğurlu şəkildə sayta daxil olmalıdır və əsas səhifə açılmalıdır.
Actual result : Əsas səhiçə açıldı və  istıfadəçinin səhifəsi açıldı.

Qeyd : negativ mümkün deyil  , çünki  sistemə nə yazılsa qəbul edir)).




Əsas səhifə
Title : Kateqoriya yoxlanışı
Description : Kateqoriyalara kliklədikdə uyğun  məhsulların görsənməsi 
Pre-condition : Səhifə aktivdir. Kateqoriyalar görsənir.
Prioroty : High
Steps :
1.QA practice səhifəsinə daxil ol
2.Açılan səhifədə kateqoriyalar görsənir
3.Hər hansısa bir kateqoriyaya kliklə
Excepted result : Kateqoriyalar uöurlu şəkildə açılmalıdır və məhsullar görsənməlidir.
Actual result : Kateqoriyalara kliklədikdə uyğun olaraq məhsullar görsənir.


 Negative Title : Axtarış buttonunun yoxlanması
Description : Axtarılan məhsulu  search hissəsinə əlavə edib yoxlamaq
Pre-condition : Səhifə aktivdir. Kateqoriyalar görsənir. Search hissəsi görsənir .
Prioroty : High
Steps : 
1.QA practice səhifəsinə daxil ol
2.Search hissəsində hər hansısa bir məhsul adı yaz
Excepted result : Axtarılan məhsulu uyğun olaraq məhsullae ekranda görsənməlidir.
Actual result : Search button işləmir və axtarılan məhsul görsənmir.


Title : Məhsul qiymətinin kiçikdən böyüyə yoxlanması
Description : Məhsulların qiymətinin kiçikdən böyüyə qiymətləndirilməsini yoxlamaq
Pre-condition : Səfifə aktivdir.İstifadəçi sayta daxil olub. Məhsulun qiymət dəyişimini seçmək olur.
Prioroty : Medium
Steps :
1.QA practice səhifəsinə daxil ol
2.Features hissəsində qitməti kiçikdın böyeyə seç
3.Açılan səhifədə məhsulların qiymətini nəzərdən keçir.
Excepted result : Məhsulların qiyməti kiçikdən böyüyə olaraq sıralanmalı idi.
Actual result : Səhifə yeniləndi və məhsullar qiymət baxımından qarışıq görsəndi.



