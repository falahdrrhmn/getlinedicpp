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


```
