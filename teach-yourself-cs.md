# Belajar Informatika secara Otodidak

> Artikel ini adalah terjemahan bahasa indonesia dari [TeachYourselfCS](https://teachyourselfcs.com), ditulis oleh [Ozan Onay](https://twitter.com/oznova_) dan [Myles Byrne](https://twitter.com/quackingduck).

Note: Panduan ini dirombak pada bulan Mei 2020. Untuk versi sebelumnya dapat dilihat di [sini](https://teachyourselfcs.com/2016/).


Jika anda adalah engineer yang belajar otodidak dan lulusan bootcamp, anda sebaiknya belajar mengenai dasar informatika. Untungnya, anda bisa belajar informatika standar dunia tanpa harus investasi dalam jangka waktu yang panjang dan juga membayar mahal kuliah di universitas.

Banyak sekali sumber belajar di internet tapi tidak semua sama baiknya. Anda tidak perlu belajar "300+ Free Online Courses" yang membuat pusing. Anda hanya butuh menjawab pertanyaan berikut. 

- Apa **bidang** yang harus dipelajari dan apa alasannya?
- Apa **buku dan video terbaik** untuk setiap bidang?

Panduan ini merupakan respon kami terhadap pertanyaan diatas. 

TL;DR:
------------------

Pelajari keseluruhan 9 bidang berikut, secara berurutan, dengan menggunakan textbook ataupun video seri, lebih baik keduanya. Targetkan 100-200 jam untuk mempelajari setiap topik, dan review berulang sepanjang karir anda.

| Topik | Kenapa penting? | Buku | Video |
| --- | --- | --- | --- |
| **[Pemrograman](#pemrograman)** | Jangan sampai anda menjadi orang yang tidak paham dengan konsep rekursif | *Structure and Interpretation of Computer Programs* | Berkeley CS 61A di Brian Harvey |
| **[Arsitektur Komputer](#arsitektur-komputer)** | Jika anda tidak paham mengenai bagaimana komputer sebenarnya bekerja, abstraksi tingkat tinggi yang anda punyai tidak mendalam atau kokoh. | *Computer Systems: A Programmer's Perspective* | Berkeley CS 61C |
| **[Algoritma dan Struktur Data](#algoritma-dan-struktur-data)** | Jika anda tidak mengetahui struktur data standar seperti tumpukan, antrian, pohon, dan graf, anda tidak akan bisa menyelesaikan masalah yang lebih menantang. | *The Algorithm Design Manual* | Le lezioni di Steven Skiena |
| **[Matematika Informatika](#matematika-informatika)** | Informatika pada dasarnya merupakan cabang dari ilmu matematika aplikatif, sehingga dengan mempelajari matematika anda akan mendapatkan keuntungan yang kompetitif. | *Mathematics for Computer Science* | MIT 6.042J di Tom Leighton |
| **[Sistem Operasi](#sistem-operasi)** | Mayoritas kode yang kita tulis akan dijalankan oleh sistem operasi, sehingga anda harus tahu bagaimana interaksinya. | *Operating Systems: Three Easy Pieces* | Berkeley CS 162 |
| **[Jaringan Komputer](#jaringan-komputer)** | Internet merupakan hal yang sangat signifikan, pelajari cara kerjanya untuk maksimalkan potensinya. | *Computer Networking: A Top-Down Approach* | Stanford CS 144 |
| **[Basis Data](#basis-data)** | Data adalah bagian utama dari program yang cukup signifikan tapi hanya sedikit yang paham mengenai bagaimana sebenarnya cara kerja basis data tersebut. | *Readings in Database Systems* | Berkeley CS 186 di Joe Hellerstein |
| **[Bahasa dan Kompilator](#bahasa-kompilator)** | Jika anda mengetahui bagaimana bahasa pemrograman dan cara kompiler bekerja, maka anda dapat menulis kode yang lebih baik dan mudah mempelajari bahasa baru. | *Crafting Interpreters* | Il corso di Alex Aiken su edX |
| **[Sistem Terdistribusi](#sistem-terdistribusi)** | Semua sistem pada jaman sekarang merupakan sistem terdistribusi. | *Designing Data-Intensive Applications* di Martin Kleppmann | MIT 6.824 |

Terlalu banyak?
--------------

Jika menurut anda mempelajari 9 topik selama beberapa tahun cukup mengerikan, kami sarankan untuk fokus hanya kedua buku berikut.

1. Computer Systems: A Programmer's Perspective
2. Designing Data-Intensive Application

Menurut pengalaman kami, dua buku tersebut memberikan keuntungan yang cukup tinggi dibandingkan dengan waktu yang digunakan, terutama untuk engineer yang otodidak dan lulusan bootcamp dan pelatihan yang bekerja pada aplikasi terdistribusi. Buku ini akan menjadi pintu masuk untuk topik lain yang telah dibuat di atas. 

Mengapa belajar informatika?
------------------------------

Ada 2 tipe software engineer: engineer yang mengerti informatika sehingga dapat menyelesaikan masalah yang menantang, membuat inovasi dan programmer yang hanya bisa bekerja karena bisa menggunakan tools atau framework high level dalam bahasa atau platform tertentu. 

Keduanya mengaku software engineer, dan keduanya cenderung mempunyai gaji yang sama pada awal karir. Tapi engineer tipe 1 akan mengarah ke karir yang tingkatan nya lebih tinggi dan gaji yang lebih tinggi seiring berjalan nya waktu, apakah dalam sektor software untuk komersial atau project open source, technical leader atau high-quality individual contributor. 

Tipe 1 engineers akan memepelajari informatika dengan dalam, apakah dari kuliah atau bangku pendidikan formal atau dengan belajar tanpa henti sepanjang karirnya. Tipe 2 engineers biasanya hanya akan berhenti di level dasar, mempelajari tools dan teknologi yang spesifik tanpa ingin belajar fundamental, fondasi dan konsep yang mendasarinya. Hanya ingin mempelajari skill baru ketika teknologi baru datang atau trend berubah. 

Sekarang, jumlah orang yang masuk ke industri kita meningkat cepat, sedangkan jumlah lulusan informatika cenderung stabil. Hal ini menyebabkan tipe 2 engineers banyak dan mengurangi kesempatan mereka untuk mendapatkan pekerjaan dan menutup kesempatan mereka untuk menempuh karir yang lebih menantang. Terlepas anda ingin menjadi software engineer tipe 1 atau hanya menjaga karir anda, hanya dengan belajar dasar informatika anda dapat mencapainya.

[![](https://teachyourselfcs.com/bilotta-tweet.png)](https://twitter.com/jenna/status/838161631662092289)

Panduan Belajar
---------------

### Pemrograman

Kebanyakan mahasiswa informatika akan belajar dengan dasar pemrograman komputer. Versi terbaik dari course ini bukan hanya ditujukan buat pemula, tapi juga untuk programmer yang mungkin melewatkan pengetahuan terhadap konsep dasar ketika belajar pemrograman untuk pertama kalinya. 

Rekomendasi kami untuk konten ini adalah *Structure and Interpretation of Computer Programs*, yang tersedia online gratis [dalam bentuk buku](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html), dan juga [MIT Video Lectures](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/). Meskipun video tersebut sangat baik, tapi kami lebih menyarankan [Kuliah SICP dari Brian Harvey](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (untuk kuliah 61A di Berkeley). Versi ini lebih baik dan cocok untuk pelajar baru dibandingkan dengan kuliah MIT.

Kami menyarankan untuk membaca paling sedikit 3 bab dari SCIP dan mengerjakan latihannya [exercism]. Sebagai tambahan latihan, kerjakan soal programming seperti yang terdapat di [exercism](http://exercism.io/).

Semenjak panduan ini dipublikasikan pertama kalinya pada tahun 2016, salah satu pertanyaan yang sering muncul adalah apakah kami menyarakan versi terbaru dari 61A yang diajarkan John DeNero dan juga buku yang digunakannya *[Composing Programs](https://composingprograms.com/)*, yang juga memiliki "tradisi SCIP" tapi mengunakan Python. Kami menilai bahwa konten dari DeNero juga sangat balik dan beberapa siswa lebih memilihnya, tapi kami tetap menyarankan SCIP, Scheme dan juga Brain Harvey's lecturers sebagai materi belajar yang pertama dicoba.

Kenapa? Karena SCIP mempunyai keunikan dalam mengubah paradigma fundamental tentang komputasi dan pemrograman. Tidak semua akan berpikir hal yang sama tentang ini. Beberapa orang tidak menyukai buku ini, ada juga yang tidak bisa menyelesaikan halaman pertama. Tapi potensi keuntungan yang didapat membuatnya sangat sangat layak dicoba. 

Jika anda tidak menykai SCIP,cobalah *Composing Programs*. Jika tidak cocok juga, cobalah *[How to Design Programs](http://www.htdp.org/)*. Jika semuanya tetap tidak begitu bermanfaat menurut anda, mungkin ini pertanda anda harus fokus mempelajari topik lain untuk sementara, dan mencoba kembali konten ini dalam waktu setahun atau dua tahun berikutnya.

Akhirnya, perlu ditekankan: panduan ini TIDAK di buat untuk orang yang sama sekali baru terhadap dunia pemrograman. Kami beranggapan bahwa anda adalah programmer yang kompeten tanpa latar belakang informatika, tetapi ingin memperkuat dasar dan fundamental. Kami menyertakan bagian programming menandakan bahwa masih banyak lagi yang dapat dipelajari. Untuk orang yang masih belum pernah programming, tapi ingin belajar, kamu mungkin lebih cocok panduan [ini](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started).

[![Structure and Interpretation of Computer Programs](https://teachyourselfcs.com/sicp.jpg)](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)

### Arsitektur Komputer

Arsitektur Komputer - kadang disebut "sistem komputer" atau "organisasi komputer" - merupakan sudut pandang informatika dibawah level dari bagaimana software bekerja. Menurut pengalaman kami, hal ini bagian yang paling sering dilewatkan oleh software engineer yang belajar otodidak atau lulusan dari pelatihan. 

Buku favourite kami adalah *[Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html)*, dan kebanyakan kuliah pengantar arsitektur komputer menggunakan buku ini [mencakup](http://csapp.cs.cmu.edu/3e/courses.html) bab 1 s/d 6

Kami suka CS:APP untuk pendekatan praktikal dan berorientasi pada programming. Meskipun masih banyak hal lain mengenai arsitektur komputer selain dari yang ada di buku itu, tapi tetap saja buku tersebut cukup baik untuk pijakan awal bagi orang yang ingin memahami arsitektur komputer agar dapat menulis software yang cepat dan efisien serta reliable. 

Untuk orang yang lebih memilih pendekatan yang lebih ringan untuk topik ini dan juga pendekatan terhadap hardware dan software secara seimbang, kami menyarankan **The Elements of Computing Systems** dikenal juga dengan **Nand2Tetris**. Buku ini cukup dalam untuk menjelaskan secara lengkap tentang pemahaman mengenai bagaimana semua hal di dalam komputer bekerja. Untuk setiap bab anda akan membangun bagian-bagian kecil dari keseluruhan sistem, dari menulis gerbang logika di HDL, sampai ke CPU dan juga assembler, sampai ke level software yaitu game Tetris. 

Kami merekomendasikan membaca semua 6 bab pertama dan menyelesaikan projectnya. Dengan demikian pemahaman anda akan terbentuk mengenai hubungan arsitektur mesin dan juga software yang berjalan di atasnya.

Setengah bagian pertama dari buku dan semua projectnya tersedia di website [Nand2Tetris](http://www.nand2tetris.org/). Juga tersedia sebagai kuliah di [Coursera dengan konten video](https://www.coursera.org/learn/build-a-computer)

Dengan mengutamakan materi yang dibuat sederhana tapi lengkap, Nand2Tetris tidak terlalu dalam. Terutama mengenai 2 konsep yang paling penting di dalam arsitektur komputer yaitu pipelinein dan hirarki memory, keduanya tidak ada pada buku tersebut.

Setelah anda paham dengan konten dari Nand2Tetris, kami berharap anda melanjutkan kembali dengan CS:APP atau mencoba buku dari Patterson dan Hennessy *[Computer Organization and Design](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269)* yang merupakan buku klasik yang sangat bagus. Tidak semua bab buku tersebut merupakan bagian esensial, akmi menyarankan mengikuti [kursus CS61C]((http://inst.eecs.berkeley.edu/~cs61c/sp15/)) dari Berkeley "Great Ideas in Computer Architecture" untuk bacaan khusus. Catatan perkuliahan dan juga praktikum tersedia online, dan kuliah versi sebelum ada di [Internet Archive](https://archive.org/details/ucberkeley-webcast-PL-XXv-cvA_iCl2-D-FS5mk0jFF6cYSJs_).

[![Computer Systems: A Programmer's Perspective](https://teachyourselfcs.com/csapp.jpg)](http://csapp.cs.cmu.edu/3e/home.html)

> Hardware adalah platform

*-- Mike Acton, Engine Director presso Insomniac Games\
([Tonton presentasinya](https://www.youtube.com/watch?v=rX0ItVEVjHc))*

### Algoritma dan Struktur Data

Kami setuju bahwa pengetahuan terhadap algoritma dan struktur data standard merupakan salah satu inti penting dari semua pengajaan informatika. Topik ini merupakan cara yang paling ampuh untuk melatih kemampuan problem solving, yang akan sangat dibutuhkan disetiap bagian dari bidang studi apapun.

Banyak sekali buku yang tersedia, tapi favorit kami adalah *[The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/)* dari Steven Skiena. Steven jelas sangat menyukai problem solving dan dapat menularkan antusiasme nya kepada mahasiswanya dan juga pembacanya. Menurut kami, dua buku lain yang sering di sarankan (CLRS dan Sedgewick) terlalu fokus pada pembuktian secara matematis untuk orang yang hanya ingin belajar tentang praktek pemecahan masalah. 

Untuk orang yang lebih suka menonton video [Skiena berbaik hati memberikan kuliahnya secara online](https://www3.cs.stonybrook.edu/~skiena/373/videos/). Kami juga sangat menyukai kuliah dari Tim Roughgarden yang tersedia di [Coursera](https://www.coursera.org/specializations/algorithms) [wesbitenya](http://timroughgarden.org/videos.html). Pemilihan pendekatan mengajar yang anda suka apakah itu dari dari Skiena ataupun Roughgarden, hal itu tergantung pada pilihan anda.


Untuk latihan, kami menyarankan mengerjakan soal di [Leetcode](https://leetcode.com/). Problem solving di leetcode cukup menantang dan mempunyai penjelasan solusi dan diskusi yang membantu. Hal ini juga membantu mempersiapkan anda untuk mengerjakan soal yang sering digunakan pada interview teknikal di perusahaan besar dalam bidang software. Kami sarankan untuk menyelesaikan 100 soal di leetcode secara random sebagai latihan pada pembelajaran ini. 


Terakhir, kami sangat menyarankan *[How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)* sebagai panduan yang unik dan bagus untuk pendekatan menyelesaikan permasalahan; cocok digunakan untuk informatika selain matematika.

[![The Algorithm Design Manual](https://teachyourselfcs.com/skiena.jpg)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![How to Solve It](https://teachyourselfcs.com/polya.jpg)](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)

> Aku hanya punya satu cara yang selalu kurekomendasikan - berpikir sebelum menulis. 

*— Richard Hamming*

### Matematika Informatika

Pada dasarnya, informatika lahir dari cabang matematika aplikasi. Meskipun banyak software engineer mencoba(ada yang sukses) menghindari topik ini, kami menganjurkan untuk tetap dipelajari. Jika anda sukses maka skill tersebut akan memberikan nilai jual tinggi dalam berkompetisi dengan orang yang tidak belajar matematika. 

Matematika yang paling relevan dengan informatika adalah "Matematika Diskret", dimana "diskret" merupakan lawan kata dari "continuous". Matematika Diskret merupakan kumpulan topik dari matematika yang tidak dicakup di dalam kalkulus. Tentu saja definis yang ambigu tidak mengharuskan anda mempelajari semua cabang dari "matematika diskret". Target yang realistis adalah membangun pemahaman terhaedap logika, kominatorik/probability, teori himpunan, teori graf dan sedikit teori bilangan yang digunakan dalam kriptografi. Aljabar Linear adalah satu tambahan yang penting juga dipelajari, karena sangat dibutuhkan pada machine learning. 




Saran kami adalah mulailah belajar dari [catatan kuliah dari László Lovász](http://www.cs.elte.hu/~lovasz/dmbook.ps). Professor Lovász dengan sangat baik membuat materi menjadi mudah dipahami dan intuitif, sehingga cocok digunakan untuk awal dibanding dengan buku formal.

Untuk pendalaman, kami menyarankan *[Mathematics for Computer Science](https://web.archive.org/web/20210504123148/https://courses.csail.mit.edu/6.042/spring17/mcs.pdf)*, buku yang dibuat dari catatan kuiah dari MIT. Video dari kuliah tersebut [gratis dibagikan](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/), dan juga kami rekomendasikan untuk belajar matematika diskret.

Untuk aljabar linear, kami menyarankan mulai belajar dari video kuliah dari [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab), disambung dengan [buku](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/) karya Gilbert dan [video kuliahnya](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/).

> Jika orang tidak percaya bahwa matematika itu sederhana, hanya karena mereka tidak sadar betapa rumit hidup ini. 

*— John von Neumann*

### Sistem Operasi

*[Operating System Concepts](https://www.amazon.com/dp/1118063333/)* ("buku dinosaurus") e *[Modern Operating Systems](https://www.amazon.com/dp/013359162X/)* merupakan buku "klasik" sistem operasi. Keduanya di kritik karena dianggap berat, kurang jelas dan tidak mudah dipahami mahasisw.

*Operating Systems: Three Easy Pieces* merupakan alternatif bagus [tersedia gratis online](http://pages.cs.wisc.edu/~remzi/OSTEP/). Kami menyukai struktur dan mudah dipahami dan merasa bahwa latihan yang ada cukup bermanfaat untuk dikerjakan.

Setelah OSTEP, kami menyarankan untuk mendalami tentang desain dari sistem operasi, dengan buku yang berbau "OS internals" , seperti  *[Lions' Commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/)*, *[The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/)* dan *[MAC OS X Internals](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)*. Untuk Linux, kami sarankan yang sangat baik [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468) di Robert Love.

Cara terbaik untuk menguatkan pemahaman dari sistem oeprasi adalah dengan membaca kode dari kernel sistem operasi yang kecil. Salah satunya adalah [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html), porting dari Unix V6 ke ANSI C dan x86, yang dibuat untuk kuliah MIT. OSTEP mempunyai appendix [praktikum xv6](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) yang penuh dengan ide yang sangat bagus untuk pengembangan project berikutnya.

[![Operating Systems: Three Easy Pieces](https://teachyourselfcs.com/ostep.jpeg)](http://pages.cs.wisc.edu/~remzi/OSTEP/)

### Jaringan Komputer

Karena kebanyakan software engineering berhubungan dengan web server dan clilent, salah satu bidang informatika yang jelas terlihat langsung manfaatnya adalah jaringan komputer. Siswa kami yang belajar otodidak, dengan mempelajari konsep networking dengan benar akhirnya memahami terminology, konsep dan protokol yang selama ini ada disekeliling mereka. 

Buku favorite kami adalah *[Computer Networking: A Top-Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)*. Projek kecil dan latihan yang ada di buku tersebut sangat bermanfaat untuk dikerjakan, terlebih bagian "Wireshark Labs" yang paling kami sukai. Mereka memberikan nya [online](http://www-net.cs.umass.edu/wireshark-labs/).

Untuk yang lebih memilih rekaman kuliah, kami menyarankan buku dari Standford dengan judul *[Introduction to Computer Networking](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z)* dulu tersedia di Stanford MOOC Lagunita tapi sekarang tersedia di youtube sebagai playlist tidak resmi. 

> Kamu tidak bisa melihat bola kristal dan melihat masa depan. Masa depan internet ditentukan oleh pembuatnya.

*— Bob Kahn*

[![Computer Networking: A Top-Down Approach](https://teachyourselfcs.com/top-down.jpg)](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/)

### Database

Ci vuole più lavoro per imparare da soli sui sistemi di database rispetto alla maggior parte degli altri argomenti. È un campo di studi relativamente nuovo (cioè dopo gli anni '70) con forti incentivi commerciali affinché le idee rimangano a porte chiuse. Inoltre, molti autori di libri di testo potenzialmente eccellenti hanno preferito unirsi o avviare aziende.

Date le circostanze, incoraggiamo gli autodidatti a evitare generalmente i libri di testo e iniziare con [registrazioni di CS 186](https://www.youtube.com/user/CS186Berkeley/videos), il corso sui database di Joe Hellerstein a Berkeley e progredire per poi leggere gli articoli.

Un documento particolarmente degno di nota per i nuovi studenti è "[Architecture of a Database System](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf)", che fornisce in modo univoco una visione di alto livello di come funzionano i sistemi di gestione di database relazionali (RDBMS). Questo servirà come base utile per ulteriori studi.

*Readings in Database Systems*, meglio conosciuto come [il "Libro Rosso" dei database](http://www.redbook.io/), è una raccolta di articoli compilati e modificati da Peter Bailis, Joe Hellerstein e Michael Stonebraker. Per coloro che sono andati oltre il livello del contenuto CS 186, il Libro Rosso dovrebbe essere la prossima tappa.

Se sei irremovibile sull'utilizzo di un libro di testo introduttivo, ti suggeriamo *[Database Management Systems](https://smile.amazon.com/Database-Management-Systems-Raghu-Ramakrishnan/dp/0072465638/)* di Ramakrishnan e Gehrke. Per gli studenti più avanzati, il classico di Jim Gray *[Transaction Processing: Concepts and Techniques](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902)* è utile, ma non t incoraggiare l'uso di questo come prima risorsa.

Infine, la modellazione dei dati è un aspetto trascurato e poco insegnato del lavoro con i database. Il nostro libro suggerito sull'argomento è *[Data and Reality: A Timeless Perspective on Perceiving and Managing Information in Our Imprecise World](https://www.amazon.com/Data-Reality-Perspective-Perceptive-Information/dp/1935504215)*.

[![Readings in Database Systems](https://teachyourselfcs.com/redbook.jpg)](http://www.redbook.io/) [![Data and Reality](https://teachyourselfcs.com/data-reality.jpg)](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215)

### Linguaggi e Compilatori

La maggior parte dei programmatori imparano i linguaggi, mentre la maggior parte degli scienziati informatici imparano *a proposito* dei linguaggi. Questo dà allo scienziato informatico un netto vantaggio rispetto al programmatore, anche nel campo della programmazione! La loro conoscenza si generalizza; sono in grado di comprendere il funzionamento di un nuovo linguaggio in modo più profondo e rapido di coloro che hanno semplicemente appreso linguaggi specifici.

Il nostro testo introduttivo suggerito è l'eccellente *[Crafting Interpreters](https://craftinginterpreters.com/contents.html)* di Bob Nystrom, disponibile gratuitamente online. È ben organizzato, molto divertente e adatto a coloro il cui obiettivo principale è semplicemente comprendere meglio i propri linguaggi e dei relativi strumenti. Ti suggeriamo di dedicare del tempo alla lettura dell'intero libro, tentando qualsiasi delle "sfide" che sostengano il tuo interesse.

Una raccomandazione più tradizionale è *[Compilers: Principles, Techniques, and Tools](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)*, comunemente chiamato "Il libro del Drago". Sfortunatamente, non è progettato per lo studio autonomo, ma piuttosto per gli istruttori che scelgono 1-2 semestri di argomenti per i loro corsi.

Se scegli di utilizzare il libro del Drago, è quasi essenziale scegliere accuratamente gli argomenti, idealmente con l'aiuto di un mentore. In effetti, il nostro modo suggerito per utilizzare il libro del Drago, se lo desideri, è come riferimento supplementare per una serie di conferenze video. Il nostro consigliato è di [Alex Aiken, su edX](https://www.edx.org/course/compilers).

[![Compilers: Principles, Techniques, and Tools](https://teachyourselfcs.com/dragon.jpg)](https://smile.amazon.com/Compilers-Principles-Techniques-Tools-2nd/dp/0321486811)

> Non essere un programmatore standard. Invece, crea strumenti per utenti e altri programmatori. Prendi nota storica delle industrie tessili e siderurgiche: vuoi costruire macchine e strumenti o vuoi far funzionare quelle macchine?

*— Ras Bodik all'inizio del suo corso di compilatori*

### Sistemi Distribuiti

Poiché i computer sono aumentati di numero, si sono anche *diffusi*. Mentre in precedenza le aziende acquistavano mainframe sempre più grandi, ora è tipico che anche applicazioni molto piccole vengano eseguite su più macchine. I sistemi distribuiti è lo studio di come ragionare sui compromessi della loro implementazione.

Il nostro libro suggerito per l'autoapprendimento è *[Designing Data-Intensive Applications](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)* di Martin Kleppmann. Molto meglio di un libro di testo tradizionale, DDIA è un libro altamente leggibile progettato per i professionisti, che in qualche modo evita di sacrificare profondità o rigore.

Per coloro che cercano un testo più tradizionale o che preferirebbero uno disponibile gratuitamente online, suggeriamo *[Distributed Systems, 3a edizione](https://www.distributed-systems.net/index.php/books/ds3/)* di Maarten van Steen e Andrew Tanenbaum.

Per chi preferisce il video, un ottimo corso con video disponibili online è [MIT's 6.824](https://www.youtube.com/watch?v=cQP8WApzIQQ&list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB), un corso di laurea tenuto da Robert Morris con letture disponibili [qui](https://pdos.csail.mit.edu/6.824/schedule.html).

Indipendentemente dalla scelta del libro di testo o di altre risorse secondarie, lo studio dei sistemi distribuiti impone assolutamente la lettura di articoli. Una buona lista è [qui](http://dsrg.pdos.csail.mit.edu/papers/), e raccomandiamo vivamente di partecipare al gruppo nella tua zona di [Papers We Love](http://paperswelove.org/).

[![Designing Data-Intensive Applications](https://teachyourselfcs.com/ddia.jpg)](https://smile.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable-ebook/dp/B06XPJML5D/)

Domande frequenti
-----------------

#### Chi è il pubblico ideale di questa guida?

Abbiamo in mente che sei un ingegnere del software autodidatta, un diplomato in un bootcamp o uno studente di liceo precoce, o uno studente universitario che cerca di integrare la sua istruzione formale con uno studio autonomo. La domanda su quando intraprendere questo viaggio è del tutto personale, ma la maggior parte delle persone tende a trarre vantaggio dall'avere una certa esperienza professionale prima di immergersi troppo in profondità nella teoria dell'Informatica. Ad esempio, notiamo che gli studenti *adorano* conoscere i sistemi di database se hanno già lavorato con i database a livello professionale, o le reti di computer se hanno lavorato su uno o due progetti web.

#### Che dire di AI/grafica/tema-alla-moda-X?

Abbiamo cercato di limitare la nostra lista agli argomenti di informatica che riteniamo *ogni ingegnere del software professionista* dovrebbe conoscere, indipendentemente dalla specializzazione o dal settore, ma con un focus sui sistemi. Nella nostra esperienza, questi saranno gli argomenti con il ROI (ritorno di investimento) più elevato per la stragrande maggioranza degli ingegneri autodidatti e dei diplomati in un bootcamp e forniranno una solida base per ulteriori studi. Successivamente, sarai in una posizione molto migliore per prendere libri di testo o articoli e apprendere i concetti fondamentali senza molto aiuto. Ecco i nostri punti di partenza suggeriti per un paio di "corsi a scelta" comuni:

- Per l'Intelligenza Artificiale: fai [L'introduzione di Berkeley al corso di Intelligenza Artificiale](http://ai.berkeley.edu/) guardando i video e completando gli eccellenti progetti Pacman. Come libro di testo, usa *Intelligenza artificiale: un Approccio Moderno* di Russell e Norvig.
-   Per il Machine Learning: segui il corso Coursera di Andrew Ng. Sii paziente e assicurati di aver compreso i fondamenti prima di precipitarti su nuovi brillanti argomenti come il deep learning.
- Per la Computer Grafica: esamina il materiale [Berkeley's CS 184](http://inst.eecs.berkeley.edu/~cs184/fa12/onlinelectures.html) e utilizza [Computer Grafica: Principi e Pratica](https://www.amazon.com/Computer-Graphics-Principles-Practice-3rd/dp/0321399528) come libro di testo.

#### Quanto è rigorosa la sequenza suggerita?

Realisticamente, tutti questi argomenti hanno una notevole quantità di sovrapposizioni e si riferiscono ciclicamente l'uno all'altro. Prendiamo ad esempio la relazione tra matematica discreta e algoritmi: imparare prima la matematica ti aiuterebbe ad analizzare e comprendere i tuoi algoritmi in modo più approfondito, ma imparare prima gli algoritmi fornirebbe maggiore motivazione e contesto per la matematica discreta. Idealmente, tornerai su questi argomenti molte volte durante la tua carriera.

In quanto tale, la nostra sequenza suggerita è principalmente lì per aiutarti *solo per iniziare*... se hai una ragione convincente per preferire una sequenza diversa, allora fallo. I "prerequisiti" più significativi a nostro avviso sono: l'architettura del computer prima dei sistemi operativi o dei database e il networking e i sistemi operativi prima dei sistemi distribuiti.

#### Come si paragona con i corsi di Open Source Society o freeCodeCamp?

Quando questa guida è stata scritta per la prima volta nel 2016, la [guida OSS](https://github.com/open-source-society/computer-science) aveva troppi argomenti, suggeriva risorse inferiori per molti di essi e non forniva alcuna motivazione o indicazioni sul perché o su quali aspetti di particolari corsi sono preziosi. Ci siamo sforzati nel limitare il nostro elenco di corsi a quelli che *davvero dovresti conoscere* come ingegnere del software, indipendentemente dalla tua specialità, e per aiutarti a capire perché ogni corso è stato incluso. Negli anni successivi, la guida OSS è migliorata, ma continuiamo a pensare che questa fornisca un percorso più chiaro e coeso.

freeCodeCamp si concentra principalmente sulla programmazione, non sull'informatica. Per sapere perché potresti voler imparare l'informatica, vedi [sopra](#perch%C3%A9-imparare-linformatica). Se non conosci la programmazione, ti suggeriamo di dare la priorità a questa e di tornare a questa guida tra un anno o due.

#### E il linguaggio X?

L'apprendimento di un particolare linguaggio di programmazione è su un piano completamente diverso dall'apprendimento di un'area dell'informatica—l'apprendimento di un linguaggio è molto *più facile* e molto *meno prezioso*. Se conosci già un paio di linguaggi, ti consigliamo vivamente di seguire semplicemente la nostra guida e di adattare l'acquisizione del linguaggio negli spazi vuoti o di lasciarla per dopo. Se hai imparato bene la programmazione (ad esempio attraverso *Struttura e Interpretazione dei Programmi per Computer*), e soprattutto se hai imparato i compilatori, dovresti impiegare poco più di un fine settimana per imparare gli elementi essenziali di un nuovo linguaggio, dopodiché può conoscere le librerie/gli strumenti/l'ecosistema sul lavoro.

#### E la tecnologia di tendenza X?

Nessuna singola tecnologia è così importante che imparare a usarla dovrebbe essere una parte fondamentale della tua formazione. D'altra parte, è fantastico che tu sia entusiasta di conoscere questa cosa. Il trucco è lavorare a ritroso dalla particolare tecnologia al campo o concetto sottostante e impararlo in profondità prima di vedere come la tua tecnologia alla moda si inserisce nel quadro più ampio.

#### Perché stai ancora consigliando SICP?

Provala. Alcune persone trovano il SICP strabiliante, una caratteristica condivisa da pochissimi altri libri. Se non ti piace, puoi sempre provare qualcos'altro e magari tornare a SICP più tardi.

#### Perché stai ancora raccomandando il libro del Drago?

Il libro del Drago è ancora la risorsa singola più completa per i compilatori. Ha un po' di cattiva reputazione, in genere per enfatizzare eccessivamente determinati argomenti che sono meno di moda da trattare in dettaglio in questi giorni, come l'analisi. Il fatto è che il libro non è mai stato concepito per essere studiato dall'inizio alla fine, solo per fornire materiale sufficiente a un istruttore per mettere insieme un corso. Allo stesso modo, un autodidatta può scegliere la propria avventura attraverso il libro, o meglio ancora seguire i suggerimenti che i docenti dei corsi pubblici hanno dato nei loro schemi di corso.

#### Come posso ottenere libri di testo a buon mercato?

Molti dei libri di testo che proponiamo sono disponibili gratuitamente online, grazie alla generosità dei loro autori. Per coloro che non lo sono, suggeriamo di acquistare copie usate di edizioni precedenti. Come regola generale, se ci sono state più di un paio di edizioni di un libro di testo, è molto probabile che un'edizione precedente sia perfettamente adeguata. È certamente improbabile che la versione più recente sia 10 volte migliore di una precedente, anche se questa è la differenza di prezzo!

#### Chi ha scritto questa guida?

Questa guida è stata originariamente scritta da [Oz Nova](https://twitter.com/oznova_) e [Myles Byrne](https://twitter.com/quackingduck), con gli aggiornamenti del 2020 di Oz. Si basa sulla nostra esperienza nell'insegnamento dell'informatica di base a oltre 1000 ingegneri per lo più autodidatti e diplomati in un bootcamp in piccoli gruppi a San Francisco e dal vivo online. Grazie a tutti i nostri studenti per il vostro continuo feedback sulle risorse di autoapprendimento.

Siamo molto fiduciosi che tu possa imparare tutto quanto riportato sopra, supponendo che ci sia abbastanza tempo e motivazione. Ma se preferisci un programma intensivo, strutturato e guidato da un istruttore, potresti essere interessato al nostro [Intensivo di Informatica](https://bradfieldcs.com/csi/). Noi [NON](https://ozwrites.com/masters/) suggeriamo di ottenere un master.

Per aggiornamenti a questa guida e notizie e risorse di informatica generale, potresti anche iscriverti alla mailing list di Bradfield nella pagina di [teachyourselfcs](https://teachyourselfcs.com/#field_0).

#### Chi ha tradotto questa guida?

La versione Italiana di questa guida è stata tradotta da [Fabio Cicerchia](https://fabiocicerchia.it), per renderla disponibile a tutti coloro che ne hanno bisogno. Spero di essere stato utile a chi sta leggendo.

Sentiti libero di contattarmi per suggerimenti, correzioni o qualsiasi motivo.

Buono Studio!
