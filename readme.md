# Resume Materi Version Control and Branch Management (Git)

## Kegunaan Version Control System

Version Control System biasanya digunakan untuk melakukan versioning terhadap source code program yang telah dibuat. Pada Version Control System akan dapat disimpan dengan mudah dan praktis ketika riwayat dari perubahan yang dilakukan terhadap source code dari suatu program atau aplikasi tersebut dikerjakan oleh banyak orang. Jadi nantinya setiap orang yang berkontribusi dalam pembuatan suatu program tersebut dapat mnegetahui perubahan apa saja yang telah dilakukan oleh kolabolator lainnya, yaitu dengan lihat riwayat dari perubahan yang telah dilakukan. 

## Version Control System melalui Git

Git merupakan salah satu version control system yang banyak digunakan saat ini. Git diciptakan pada tahun 2005 oleh Linus Torvalds. Git merupakan version control system yang memiliki sifatnya distributed atau terdistribusi. sifat distributed ini artinya dimana program akan di host pada suatu git hosting service dan disebut sebagai sebuah repository. Kemudian terdapat riwayat perubahan kode program pada setiap repository yang disebut dengan commit. Sehingga setiap kolaborator pada suatu repository dapat membuat suatu commit yang kemudian akan di push ke github agar kolaborator lain dapat mengetahui perubahan yang dibuat dan diaplikasikan perubahannya ke local machine dari masing-masing kolaborator. 

## Penggunaan Suatu Git

Pada penggunaan suatu Git, langkah pertama dilakukan pembuatan repository baru pada github. setelah itu Kode Program di local machine yang sudah dibuat dapat di push ke github dengan melakukan commit. Kolabolator lain dapat melakukan pull untuk memperoleh data dari Kode Program yang telah disimpan pada repository git hosting service. Kemudian dilakukan branching pada repository tersebut agar pembuatan perubahan pada Kode Program lebih mudah. Pada branching dilakukan dengan memisahkan branch master dan develop serta membuat branch baru untuk setiap fitur yang sedang dikembangkan. Kemudian untuk setiap fitur tersebut akan dilakukan merge ke develop jika fitur tersebut sudah bekerja dengan maksimal. Lalu branch develop akan di merge ke branch master apabila proses pengembangan telah selesai, Hal ini bertujuan untuk meng-deploy fitur baru yang ditambahkan.