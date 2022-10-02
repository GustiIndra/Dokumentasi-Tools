# Dokumentasi-Tools
1. Pertama kita install wsl terlebih dahulu dengan comand " wsl --install " di powershell admin
![wsl install](https://user-images.githubusercontent.com/113918395/193439896-7e0d9059-6e2a-4f89-b7fa-4f69ee4cb755.png)

2. Setelah itu kita install ubuntu dengan comand " wsl --install -d Ubuntu-20.04 "

![Install ubuntu](https://user-images.githubusercontent.com/113918395/193439928-4b51aabf-7ac0-4c15-a16b-e323aab05d05.png)

3. Setelah selesai mendownload ubuntu, ketik comand Ubuntu2004 config --default-user root 

![Ubuntu config](https://user-images.githubusercontent.com/113918395/193439998-4cdf1937-4503-4584-a27d-9a3e3316b685.png)

4. Kita lanjut dengan masuk terminal lalu ke setting dan pilih Ubuntu 20.04

![startup](https://user-images.githubusercontent.com/113918395/193440049-e8932273-9de0-413e-bd01-6d96f1ade7c0.png)

5. Setelah itu jika sudah masuk ke ubuntu ketik comand apt update 

![apt update new](https://user-images.githubusercontent.com/113918395/193440799-2efd9be3-820d-46db-8bf0-c4b661fab4d2.png)

6. jika sudah selesai dengan tahap di atas selanjutnya kita menuju web https://github.com/ohmyzsh/ohmyzsh untuk mencari comand ZSH

![ohmy](https://user-images.githubusercontent.com/113918395/193440918-0049c2b6-6a9b-40e4-9abe-fdab5bb94c95.png)

7 selanjutnya kita akan install ZSH dengan ketik comand " install zsh " pada terminal ubuntu

![zsh install](https://user-images.githubusercontent.com/113918395/193440977-9048177c-59ef-4bb7-98fd-526214740493.png)

8 Tahap berikutnya ketik comand pada terminal seperti ini sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)" 
jika, kalian belum install curl dan git silakan install terlebih dahulu karena tidak bisa jalankan comand diatas jika belum install

>apt install curl ( tunggu sampai selesai )
>apt install git  ( tunggu sampai selesai )

![selesai zsh](https://user-images.githubusercontent.com/113918395/193441880-babfe245-826a-4acb-bf85-377ada98f525.png)

9 Tahap berikutnya kita ketik comand nano /root/.zshrc , setelah itu rubah bagian ZSH_THEME="robbrussel" menjadi ZSH_THEME="agnoster" 
pilih linenya dengan tombol arah

![agnoster](https://user-images.githubusercontent.com/113918395/193442344-960d4c91-3436-4f90-a101-10f7ae4d7a8e.png)

10 Tahap berikutnya ketik comand sebagai berikut pada terminal, setelah itu masuk kembali ke nano /root/.zshrc kalian ke bagian bawah dengan menekan tombol arah dan kalian cari plugins dan kalian ganti seperti pada gambar berikut

git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting

git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions

![plugins](https://user-images.githubusercontent.com/113918395/193443047-91831b98-8085-42fe-8086-06a122162a29.png)
