**PYTHON PROJECT**
	Ini merupakan project membangun self-service cashier sederhana menggunakan python.
	
**REQUIREMENTS**
Project ini dibangun menggunakan google colab, alasan menggunakan platfrom tersebut supaya project ini mudah diakses dimanapun dan kapanpun.

**FLOWCHART**












 ![image](https://user-images.githubusercontent.com/8916321/231964799-70638622-a0b7-4588-9f86-bd31aab92d03.png)

**FUNCTIONS AND ATTRIBUTES**





![image](https://user-images.githubusercontent.com/8916321/231965079-25d54a7f-7c7c-4144-96ad-2d6424100f75.png)


Data.append berfungsi untuk menambahkan nilai array yang diinputkan, casefold untuk  mengubah input menjadi huruf kecil. Hal ini berguna untuk menghindari error karena case sensitive character.
Terdapat pengulangan untuk proses input array, pengulangan akan berhenti Ketika user menginput nilai n pada choice.
![image](https://user-images.githubusercontent.com/8916321/231966578-986dbf19-788a-4dcf-a847-34fad59e03cf.png)
Selanjutnya Next_todo, untuk menentukan action selanjutnya. Jika user memilih update, makan fungsi update akan dijalankan, begitu juga dengan fungsi delete dan selesai. Jika selesai, program akan langsung melakukan summary transaksi, menghitung diskon jika total harga berada pada rentang diskon dan mencetak transaksi.

**DEMONSTRATION**

TEST 1: INPUT
•	Nama Item: Ayam Goreng, QTY: 2, Price: 20000
•	Nama Item: Pasta Gigi, QTY: 3, Price: 15000
      OUTPUT:
 ![image](https://user-images.githubusercontent.com/8916321/231966780-5d1330ea-949e-4ef6-943e-2a9ed8403810.png)
 
TEST 2: Hapus Salah satu Item, Yang dihapus Pasta Gigi
OUTPUT:












 ![image](https://user-images.githubusercontent.com/8916321/231966906-9020ee35-07e2-4d75-be38-850f03917b97.png)
 
TEST 3: RESET Semua Transaksi
OUTPUT:






![image](https://user-images.githubusercontent.com/8916321/231966999-db73e269-8b24-4830-9673-fee4f2b64406.png)

TEST 4: Total Price yang dibayarkan
OUTPUT:
![image](https://user-images.githubusercontent.com/8916321/231967089-0064b200-7fd8-42a2-898f-cb4307a7f353.png)

**Contoh Program kalau dijalankan dari input Barang**
![image](https://user-images.githubusercontent.com/8916321/231967222-f116bba7-efa3-4d3f-99a9-556623cc9e45.png)
