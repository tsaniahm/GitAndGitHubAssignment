1. Fork repository GitHub https://github.com/impactbyte/tech4impact-students-bio.git menggunakan akun Github kamu

  ![no 5 1](https://user-images.githubusercontent.com/71321557/134212334-e0520852-02b1-4a63-9c7f-939dc6251f25.JPG)

2. Clone remote repository dari hasil fork tersebut. Jangan clone dari repository originalnya.

  **git clone https://github.com/tsaniahm/tech4impact-students-bio.git**
  
3. Buatlah branch baru dengan nama lengkap kamu. Misalnya david-winalda. Jangan melakukan perubahan pada branch master.

  **git branch TsaniahMunfidah**
 
4. Checkout ke dalam branch tersebut yang telah kamu buat

  **git checkout TsaniahMunfidah**
  
5. Buatlah 1 file format .md dengan nama lengkap kamu. Contoh davidwinalda.md

  **touch Tsaniah.md**
  
6. Isi file tersebut davidwinalda.md dengan konten di bawah ini:

  ![no 6](https://user-images.githubusercontent.com/71321557/134213299-d6b4a304-4518-42ab-979a-a3c003aa5e60.JPG)
  
7. Masukkan file .md tersebut ke dalam staging area

  **git add Tsaniah.md**
  
8. Commit dengan memberikan pesan nama file .md kamu
  
  **git commit -m "Tsaniah.md"**
  
9. Merge branch yang telah kamu buat ke dalam branch master

  **git checkout master**
  
  **git merge TsaniahMunfidah**
  
10. Push ke dalam branch master

  **git push -u origin master**
  
11. Lakukan pull request dari GitHub Repository yang telah kamu fork untuk digabungkan ke dalam branch master pada GitHub Repository aslinya.

  ![no 11 bener2](https://user-images.githubusercontent.com/71321557/134213850-ecbb2703-4092-4000-8fcb-6ea5463bf13e.JPG)



