taro file github.com di lokasi di bawah ini
C:\Program Files\Go\src
C:\Program Files\Go\src\vendor

taro file christhoper_50420309_pert3
C:\Program Files\Go\src

buka xampp run administrator
centang mysql dan apache
dan buka 
localhost/phpmyadmin

buka vscode dengan run administrator karna bakal eror dan ngak bisa save

kalo ganti nama folder ganti juga isi di dalem nya
"nama_npm_pert3/model"

dan juga untuk isi di dalem nya di ganti untuk nama database dan pass database nya
	username = "root"
	password = ""
	host = "localhost"
	namaDB = "nama_npm_pert3"
	defaultDB = "mysql"

cd test
go test -run TestDatabase

go test -run TestDatabase
go test -run TestMahasiswa
go test -run TestMatkul
go test -run TestNilai