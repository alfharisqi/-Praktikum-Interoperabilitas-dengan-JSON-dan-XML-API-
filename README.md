NAMA : ALFHA RISQI WICAKSONO
NIM : 362358302145

Bagian 1: Membuat API dengan JSON menggunakan Node.js

Server	Express.js
![Screenshot 2024-10-15 141849](https://github.com/user-attachments/assets/13e6cf08-af97-47f4-8499-4ad549263ad6)

GET	http://localhost:3000/person
![image](https://github.com/user-attachments/assets/392cdbd5-7939-4332-a5ea-fbcf0d625abb)

POST	http://localhost:3000/person
![image](https://github.com/user-attachments/assets/ec04a911-5811-4564-a500-668ff35e33c3)

`DELETE	http://localhost:3000/person/:id
![image](https://github.com/user-attachments/assets/d343dfa5-bc78-4a8e-b657-18f053638c89)

Bagian 2: Membuat API dengan JSON menggunakan PHP

File	API
![image](https://github.com/user-attachments/assets/2b4b95b6-4bb4-41a9-86d2-24ec7f50c71e)

-	**GET**:	Mengambil	semua	data	persons	
curl -X GET http://localhost/api.php
![Screenshot 2024-10-15 140701](https://github.com/user-attachments/assets/7f56548f-058d-4c96-b407-748c7402e07b)


-	**POST**:	Menambahkan	data	baru	
curl -X POST http://localhost/api.php -d '{"nama": "Alice", "umur": 28, 
"alamat": {"jalan": "Jalan GHI", "kota": "Surabaya"}, "hobi": ["memasak", 
"menari"]}' -H "Content-Type: application/json"
![Screenshot 2024-10-15 140739](https://github.com/user-attachments/assets/44041260-0ed4-4683-9210-2de3a2f54270)

-	**DELETE**:	Menghapus	data	berdasarkan	ID	
curl -X DELETE http://localhost/api.php/1
![Screenshot 2024-10-15 140804](https://github.com/user-attachments/assets/94f70991-70c8-4e1a-8c8b-af2b11e3fcca)

Bagian 3: Membuat API dengan XML menggunakan PHP

Pastikan	server	web	Anda	berjalan,	lalu	akses	`http://localhost/person.php`.
![Screenshot 2024-10-15 134001](https://github.com/user-attachments/assets/e54c5ad7-f0c1-47fe-bbd8-dd78714e197c)

Gunakan	Postman	atau	browser	untuk	mengakses	`http://localhost/person.php`.	
![Screenshot 2024-10-15 134311](https://github.com/user-attachments/assets/587a2e8d-600e-4360-a13f-e3e940807254)



