# include <iostream>
# include <iomanip>
using namespace std;

int main(){
    const int n = 5;
    int ar[n];

    cout << '\n';
    cout << " contoh array 1 dimensi " << endl;
    cout << " ---------------------- " << endl;
    cout << '\n';

    //menginputkan nilai array
    for (int i = 0; i < n; i++){
        cout << " Masukan nilai ke-" << i << " : "; cin >> ar[i];
    }

    cout << '\n';
    cout << " Menampilkan nilai yang diinputkan " << endl;
    cout << " --------------------------------- " << endl;
    cout << '\n';
    for (int i = 0; i < n; i++){
        cout << " Ar [" << i << "]" << " : " << ar[i] << endl;
    }

    cout << '\n';
    cout << " Terima Kasih " << endl;
    cout << " ------------ " << endl;
    cout << '\n'; 
}
