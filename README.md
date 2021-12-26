# project-akhir
Alifan Renaldi_2017051044
Joy Hans Christabel Sinaga_2017051050
Muhammad Zulfikar_2017051052

Muhammad Zulfikar(database)
Joy Hans Christabel(controller)
Alifan Renaldi(implmentasi class diagram)

SISTEM KOPERASI SIMPAN PINJAM (UPDATE  3)
(JAVA CLASS)

Pada sistem koperasi, terdapat entitas nasabah, dimana nasabah  memiliki properti nama, noRekening, alamat dan saldo tabungan. Setelah departemen IT  memisahkan kelas Nasabah dengan Rekening, yang berasosiasi secara agregasi

Setelah berjalannya waktu, kopereasi tumbuh menjadi besar, sehingga nasabah koperasi tidak hanya individu akan tetapi juga perusahaan, untuk itu perlu penyesuaian sistem yang sudah ada, Direksi mengambil kebijakan pemisahan entitas nasabah individu dan perusahaan, dimana masing-masing entitas memiliki properti pembeda yaitu, untuk individu memiliki nik dan npwp sedangan untuk perusahaan memiliki nomor izin berusaha (nib), anda sebagai bagian departemen IT diminta untuk mengimplementasikan diagram class berikut:

Penjelasan Class Diagram: nasabah harus salah satu antara Individu atau Perusahaan sehingga class Nasabah harus dibuat abstrak agar tidak bisa diinstansiasi. Semua subclass dari kelas Nasabah harus menimplementasikan method print() yang berbeda dengan subclass lainnya, sehingga method print() ini harus dibuat abstract di class Nasabah.

Implementasi class sesuai diagram
Buat Konstruktor sesuai diagram
Buat method setter dan getter
Method tambahRekening di kelas nasabah digunakan untuk menambah data rekening
Method tambahSaldo di kelas Rekening digunakan untuk menambah saldo tabungan
Method tarikTunai  di kelas Rekening akan mengurangi saldo tabungan
Form Java FX halaman utama, yang bisa digunakan untuk mengakses fungsi-fungsi dalam sistem, sehingga sistem dapat
Diganakan untuk tambah data nasabah
Diganakan  untuk tambah rekening
Diganakan  untuk tambah saldo
Semua data disimpan di database, boleh menggunakan MySQL atau SQLITE.
Tulis nama anggota dan npmnya berserta pembagian tugasnya beserta deskripsi program di file README.md, letakan project di reposiroty github.
