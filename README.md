1.  what is amqp?

AMQP adalah singkatan dari Advanced Message Queuing Protocol. Ini adalah protokol lapisan aplikasi standar terbuka untuk middleware yang berorientasi pesan, yang dirancang untuk bertukar pesan antara aplikasi atau layanan dalam sistem terdistribusi. AMQP memungkinkan komunikasi antara sistem yang dapat terpisah, fleksibel, dan dapat diskalakan.

2. what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second guest, and what is localhost:5672 is for? 

"guest" adalah nama pengguna.
"guest" (sekali lagi) adalah kata sandi.
"localhost:5672" mengacu pada nama host dan nomor port.

Dalam konfigurasi ini:

- "guest" adalah nama pengguna dan kata sandi default yang sering digunakan untuk tujuan pengujian atau pengaturan awal pada broker AMQP seperti RabbitMQ.

- "localhost" mengacu pada mesin lokal, menunjukkan bahwa broker AMQP berjalan pada mesin yang sama dengan klien.

- "5672" adalah nomor port default untuk komunikasi AMQP.

Jadi, "guest:guest@localhost:5672" mewakili kredensial (nama pengguna dan kata sandi) yang digunakan untuk terhubung ke broker AMQP lokal yang berjalan pada port 5672.