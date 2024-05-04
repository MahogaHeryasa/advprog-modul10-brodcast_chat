# advprog-modul10-timer

# Mahoga Aribowo Heryasa

# 2206025230

### 2.1. Original code of broadcast chat

![2.1. Original code of broadcast chat](assets/images/2.1.png)

Untuk menjalankan satu *server* saya menjalankan `cargo run --bin server` pada satu terminal. Kemudian untuk menjalankan tiga *client*, saya membuka tiga terminal dan menjalankan `cargo run --bin client`. Kemudian saya mencoba memasukkan input pada tiga *client* yang dijalankan. Karena setiap *client* terhubung pada satu *server*, ketika saya memasukkan input pada salah satu *client*, maka yang terjadi adalah input tersebut terlihat pada seluruh terminal *client* setelah input masuk ke server dan dikirimkan kembali ke seluruh client.  