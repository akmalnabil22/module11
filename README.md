# module11

## Reflection on Hello Minikube
1. Before exposed  
    ![](./img/before-exposed.png)  
    After exposed  
    ![](./img/after-exposed.png)  
    After several run  
    ![](./img/after-several-run.png)  
    Sebelum exposed, logs hanya menampilkan informasi bahwa service telah berjalan pada port yang diberikan. Setelah exposed dan dijalankan, logs menampilkan informasi tambahan bahwa service menerima request GET. Setelah dijalankan berkali-kali, logs mendapat tambahan informasi request GET setiap kali service dijalankan.  


2. `-n` digunakan untuk menentukan namespace tempat perintah dijalankan. Jika tidak ditulis, maka namespace = default. Pada pemanggilan dengan `-n kube-system`, perintah get tidak menampilkan service yang sudah saya buat karena service tersebut berada di namespace default sedangkan pemanggilan get ini untuk service yang berada di namespace `kube-system`.  
