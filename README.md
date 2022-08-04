# Find-place-2.0

Challenge writeup 


<img align='center' src='https://i.postimg.cc/253Zr2Wc/IMG-20220804-023234.jpg' width='200"'>

Challenge এ একটি Hint text এবং Google drive file এ একটি zip file দেয়া আছে। সর্ব ১ম আমাদের কাজ হলো Hint text টি Decode করা। Hint text টি Base64 formate এ encode করা চলুন সেটি Decode করে  নেয়া যাক  

<img align='center' src='https://i.postimg.cc/nL6CZZpr/IMG-20220804-204315.jpg' width='200"'>

 Decoded Hint text টি হলো :

Try password Night Driver album Singer name and the last half of the password is hermoini add two part

Use lower case

এখানে বলা হয়েছে Night Driver song এর Singer খুজে বের করতে এবং password last half দেয়া আছে যা হলো hermoini

মূলত drive এ যে zip file টি আছে তা খোলার জন্য এই password টি প্রয়োজন। 

উল্লেখ্য যে password  খুজে বের করার পর সব word গুলো lower case এ ব্যবহার করতে বলা হয়েছে। 

চলুন Night driver song এর Singer কে খুজে বের করা যাক 

এর জন্য Google লে একটু search করলেই হবে। নিচের ছবির মতো

<img align='center' src='https://i.postimg.cc/YCPSfk4R/IMG-20220804-204341.jpg' width='200"'>

Singer name হলো Eida 

so Zip file এর password হলো eidahermoini[use lower case]

অর্ধেক কাজ আমাদের complete. 

Zip file open করলে এরকম একটি ছবি পাওয়া যায়। আর আমাদের কাজ মানে flag হলো এই  ছবির জায়গায় নাম। 

<img align='center' src='https://postimg.cc/Cd9QvC7p' width='200"'>

ছবির জায়গায় নাম খুজতে Google image search অথবা yandex image search করলেই হবে। 

<img align='center' src='https://postimg.cc/1nXLn2wH' width='200"'>

so finali আমরা জায়গার নাম পেলাম

Ratatgul Swamp Forest

flag format অনুযায়ী  flag হবে

CTFBD{Ratatgul_Swamp_Forest}
