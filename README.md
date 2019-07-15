# RasaBot

Introduction:

Rasa Core and Rasa NLU is the RASA function to build a chatbot

Rasa NLU adalah library dari rasa yang berperan sebagai mulut, untuk mengerti bahasa alami manusia(inggris, indonesia, dll).
Rasa Core adalah library dari rasa yang berperan sebagai otak dari mesin tersebut, tugasnya untuk
menentukan keputusan berdasarkan pengetahuan yang diberikan.


# RASA NLU
Sebelum mempelajari rasa NLU, ada beberapa pengertian yang harus dipahami:

Contoh kalimat: " Pesenin meja di bang dul ntar malem "
1. Intent : Pemesananan Meja
2. Entity : Tempat, Waktu
3. Stories: Interaksi sederhana antara bot dengan users
4. Action : Operasi yang dilakukan bot, seperti bertanya dengan detail untuk mendapatkan entity,
atau integrasi dengan 3rd party API, bisa juga untuk query database untuk mendapatkan/menyimpan informasi.

# RASA CORE
Di dalam RASA core ada yang namanya DIALOG MANAGEMENT, ada beberapa hal yang wajib diketahui sblm masuk kedalam
dialog management karena dialog management biasanya mengandung beberapa file dibawah ini

1. domain.yml -> domain yml biasanya untuk mendifinisikan intent,entities,slots,action, templates
2. policy.yml -> menentukan aksi apa dari setiap teks yang diambil
3. stories.md -> menentukan jalan cerita dari bot yang diinginkan
4. custom action(action.py) -> untuk menentukan aksi dari chatbot yang akan dijalankan

# Read More tutorial on rasa 
<https://rasa.com/docs/rasa/user-guide/rasa-tutorial/>

#For example:
First you need to install rasa there, and spacy
1. Clone this repository
2. Run rasa shell to test your chatbot
3. type rasa run to test on backend

additional command:

if you have more data you can specify it in nlu.md

and run
4. Rasa train, to train the model so it can be used to rasa shell/run after


That's all...