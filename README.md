![alt text](image-3.png)
di atas merupakan hasil dar menciptakan user baru 
![alt text](image.png)
di atas adalah token yang telah di dapatkan setelh login
![alt text](image-1.png)
pada gambar di atas merupakan hasil dari memasukan token yang telah di dapatkan,
dan hasil nya adalah     "message": "Unauthorized\naccess" mungkin karena pada yang saya masukan 
pada di dalam postman itu role nya user seperti yang terlihat pada localhost php myadmin
![alt text](image-2.png)
seperti yang di lihat di atas role nya user
![alt text](image-5.png)
![alt text](image-6.png)
![alt text](image-4.png)
dan untuk membutikan nya saya mengubah sedikit coding nya supaya nanti bisa membedakan login user atau admin 
dan tercipta lah admin dan tabel pada mysql nya terdapat di bawah

<h1> PRAKTIKUM </h1>

PENGUBAHAN PROFILE ADMIN

![alt text](image-7.png)
sebelum
![alt text](image-8.png)
waktu di ubah
![alt text](image-9.png)
sesudah di ubah
![alt text](image-10.png)
code
![alt text](image-11.png)
route api

Implementasikan sistem untuk menghapus pengguna dengan otorisasi admin.
![alt text](image-12.png)
id yang dihapus
![alt text](image-13.png)
sebelum
![sesudah](image-14.png)
sesudah
![alt text](image-15.png)
code nya
![alt text](image-16.png)
route api

Buat API untuk mengambil daftar semua pengguna (hanya bisa diakses oleh admin)
![alt text](image-17.png)
perubahan url untuk meng get semua users(menampilkan semua users)
![alt text](image-18.png)
code menampilkn semua users
![alt text](image-19.png)
route api select all
{
    "users": [
        {
            "id": 1,
            "name": "Test User",
            "email": "test@example.com",
            "role": "user",
            "email_verified_at": null,
            "created_at": "2024-11-01T03:44:32.000000Z",
            "updated_at": "2024-11-01T03:44:32.000000Z"
        },
        {
            "id": 4,
            "name": "Users Name",
            "email": "tesstname@example.com",
            "role": "user",
            "email_verified_at": null,
            "created_at": "2024-11-03T05:06:24.000000Z",
            "updated_at": "2024-11-03T05:06:24.000000Z"
        },
        {
            "id": 5,
            "name": "User Name",
            "email": "user@example.com",
            "role": "admin",
            "email_verified_at": null,
            "created_at": "2024-11-03T05:19:19.000000Z",
            "updated_at": "2024-11-03T05:19:19.000000Z"
        },
        {
            "id": 6,
            "name": "Roys",
            "email": "Roys.updated@example.com",
            "role": "admin",
            "email_verified_at": null,
            "created_at": "2024-11-03T05:49:04.000000Z",
            "updated_at": "2024-11-03T05:49:04.000000Z"
        }
    ]
}
![alt text](image-20.png)
<h3>hasil dari memanggil all users</h3>


