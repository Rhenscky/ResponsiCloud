# ResponsiCloud

ambil data dari github : 
      
        git clone https://github.com/Rhenscky/ResponsiCloud.git
        
ambil image dari docker hub :

        docker pull rhenscky/195410003:latest

lalu masuk ke dalam direktori ResponsiCloud :

        cd ResponsiCloud


jalankan perintah berikut untuk menjalankan imagenya :

        docker run -d -p 8080:80 --name webserver rhenscky/195410003


lalu masuk ke port 8080.
