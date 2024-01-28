# Typescript

Typescript javascriptning ma'lumot turlarini (data types, bu yog'iga type lar) tartiblangan holda o'qishga moslashtirilgan ko'rinishi. Katta loyihalarda bunday uslub yaxshi ish beradi.
TypeScriptda errorlar nisbatan kamroq chiqadi.

bunda type lar 
Simple type special type kabi turlarga bo'linadi.

# simple type lar

Simple type larga:
string - "Ali","Vali";
Number - 1,2,3;
Boolean - true,false;
lar kiradi.

Undan tashqari 
bigint
ham bor bu type o'z ichiga numberni yanada kattaroq va o;nli kasrlarini ham qo;shib qabul qiladi.

# Special type lar

Bularga
any - istalgan turdagi ma'lumot turi;
never - bu kam ishlatilsa ham kerakli joyi bor. E'lon qilinishi bilan error beradi.
unknown - any ning havfsizroq nusxasi desa ham bo'ladi. Bunda unknown type lar chiqishi oldini olinadi.
undefined va null - JS da nima vazifa bajargan bo'lsa o'sha.

# Array lar

Type scriptda arraylar ham oladigan type lari belgilangan holatda uchraydi. Bunda agar array number qabul qiladigan bo'lsa uning elementi sifatida string qabul qildirib bo'lmaydi.

# Tuple lar

Bular aralash typelar qabul qilishi mumkin bo'lgan arraylar. Bunda muhimi e'lon qilish jarayonida arrayning elementlari type lari qanday tartibda e'lon qilingan bo'lsa huddi shunday qiymat kiritishni talab qiladi. AKs holda Error chiqaradi.
