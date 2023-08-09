# CPPPP CUAKS 

```cpp
#include <iostream>
using namespace std;

int main(){
    // artimatika di c++ 
    /*
    + - * / % ++ -- 
    */

    // deklarasi variabel
    int nilaipertama, nilaikedua, tambah, kurang, kali, bagi, modulus, increment, decrement;
    
    // isi variabel
    nilaipertama = 10;
    nilaikedua = 5;
    
    // coba operator
    tambah = nilaipertama + nilaikedua; 
    kurang = nilaipertama - nilaikedua;
    kali = nilaipertama * nilaikedua;
    bagi = nilaipertama / nilaikedua;
    modulus = nilaipertama % nilaikedua;
    
    //output
    cout << "Nilai pertama : " << nilaipertama << endl;
    cout << "Nilai kedua : " <<nilaikedua << endl;

    cout << "tambah : " << tambah << endl;
    cout << "kurang : " << kurang << endl;
    cout << "kali : " << kali << endl;
    cout << "bagi : " << bagi << endl;
    cout << "modulus : " << modulus << endl;
    cout << "increment : " << ++nilaipertama << endl; 
    cout << "decrement : " << --nilaikedua << endl; 

}

output :
PS D:\sinau> c++ .\coba.cpp -o hasilcoba
PS D:\sinau> .\hasilcoba.exe
Nilai pertama : 10
Nilai kedua : 5
tambah : 15
kurang : 5
kali : 50
bagi : 2
modulus : 0
increment : 11
decrement : 4

```


# getlinee 

```cpp
#include <iostream>
using namespace std;

int main(){
    
   string nama; 
   cout << "Masukkan nama anda : ";
   getline(cin, nama); 

   // string ngambil variabel dan terpisah dari spasi
   cout << "Nama anda adalah : " << nama;  
}

output :
PS D:\sinau> .\hasilcoba.exe
Masukkan nama anda : Muhammad Falah Abdurrohman
Nama anda adalah : Muhammad Falah Abdurrohman

```

kalo gamake getline

```cpp
#include <iostream>
using namespace std;

int main(){
    
   string nama; 
   cout << "Masukkan nama anda : ";
   cin >> nama; 

   // string ngambil variabel dan terpisah dari spasi
   cout << "Nama anda adalah : " << nama;  
}

output :
PS D:\sinau> c++ .\coba.cpp -o hasilcoba
PS D:\sinau> .\hasilcoba.exe
Masukkan nama anda : Muhammad Falah A
Nama anda adalah : Muhammad

```
