Reverse Engineering Assignment Week 12
Nama: Hafizh Kusuma Abdillah
NIM: H1A023044

1.	Is an encounter part of a visit, or is a visit part of an encounter?
	Berdasarkan Entity Relationship Diagram (ERD) yang telah dibuat, hubungan antara tabel visit dan encounter terbentuk melalui sebuah Foreign Key (Kunci Tamu). Tabel encounter memiliki kolom visit_visit_id, yang merujuk pada tabel visit.
	Dalam logika perancangan basis data, tabel yang menampung Foreign Key mewakili sisi "Many" (banyak) atau sisi anak (child) dari hubungan tersebut. Hal ini menunjukkan hubungan One-to-Many, di mana satu Visit (Kunjungan) dapat memuat banyak Encounter (Tindakan). Oleh karena itu, secara struktural dan logis, Encounter adalah komponen yang berada di dalam lingkup sebuah Visit.

2.	How is provider linked to person?
	Meskipun tabel person tidak divisualisasikan secara eksplisit dalam diagram tugas ini, jika kita menelaah balik (reverse engineer) konsep basis data medis pada umumnya, provider hanyalah sebuah peran (role), sedangkan person adalah entitas yang memuat identitas manusianya.
	Dalam skema basis data layanan kesehatan standar (seperti OpenMRS), tabel provider biasanya akan memiliki kolom Foreign Key (sering kali bernama person_id) yang menghubungkannya ke tabel utama person. Mekanisme ini memisahkan data demografis individu (yang disimpan di person) dari data peran profesional mereka (yang disimpan di provider).

