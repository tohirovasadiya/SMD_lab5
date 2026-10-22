Exercise 1 

Funksiyalar lambda oddiy bilan yuqorisini qabul qilganda shu funksiyalarimizi ichida obyekni chaqirish bilan bogliqligi uchun qoshimcha harajatlar bo’ladi Yozgan funksiyamiz takror chaqirilsa xato kop bolib ketadi  inline kopilator qoshb qoyse ayrim  bosha harajatlarniyam kamaytiradi 

Conclusion:  lambda qabul qiluvchi funksiya inline tez tez chqirilsa foydali boladi lekin ishlash samaradorligini oshirish uchun kerak bolganda foydalanish kerak deb oyleman

Exercise 2

Notogri xabar chiqarib tekshiruvni toxtatish maqsadida for bilan breakdan foydalanardim sms jonatishda telfon nomerlarga bolsa notogri nomerlarni continue bilan o’tkazar edim 

Conclusion: Kodni ishlashi uchun togri farqini tushunish uchun return continue break kutilgande ishga tushishi uchun ishlashiga yordam beradi.Men kod tushunarli oson saqlash uchun  vaziyatga qarab foreach for siklda foydalanardim.

Exerscise 3

lampda funksiya inline kotlinda joylashtiriladi Obeyk kabi saqlab  keyin qayta ishlatib bomasligi uchun  funksiya ichidagi ma’lum bir lambda parametrini noinline bilan inline oddiy lamb boladi.o‘zgaruvchida saqlash va keyinroq ishlatish mumkin Boshqa lambda inline parametrlariga saqlanadi.

Conclusion     inline  faqat keyinroq ishlatish yoki saqlash kerak bo‘lgan lambda uchun foydali. Uni to‘g‘ri tanlash kodning ishlashini va qayta urinish mexanizmini to‘g‘ri tashkil etishga yordam beradi. 

Exerscise 4

Crosslinedan foydalanardim oddiy narsalarni obeyk sifatida saqlab ishlatishga imkon beradi keyin crossline tolov amalini takroriy buyurtma  yaratishdan oldin debounce vaqtini tekshirish mumkin.

Conclusion

  lambda ichidagi crossline   return non-local ni taqiqlaydi, ammo inline optimallashtirish imkoniyatini saqlaydi.  lambdagi non local oddiy obyekt sifatida ishlatish imkonini beradi. 

Exercise 5 

Men Android loyihalarimda yordamchi reified  funksiyalaridan foydalanardim, chunki ular kodni qisqartiradi va o‘qishni osonlashtiradi. Masalan, Activity ochish yoki JSON ma’lumotlarini kerakli modelga aylantirishda bu juda qulay. Lekin murakkab holatlarda turning klassini alohida parametr sifatida uzatish ham foydali bo‘lishi mumkin.

Xulosa: Aniq turidan foydalanishga yordam beradi reified  generic . Uni inline birga qo‘llash kodni soddalashtiradi va keraksiz klass parametrlarini kamaytiradi.

 

