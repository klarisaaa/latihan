

#include <iostream>
using namespace std;
int main() {
int tipe_rumah1, tipe_rumah2, tipe_rumah3, jumlah1, jumlah2, jumlah3, konfirmasi, hasil1, hasil2, totalhasil;
cout << "Perhitungan penjualan rumah PT Nuri Real Estate (NRE)" << endl; cout << "\nMasukan tipe rumah yang terjual ( 45 / 54 / 70 ): ";
cin >> tipe_rumah1;
cout << "Masukan jumlah rumah yang terjual : ";
cin >> jumlah1;
//penghitungan if(tipe_rumah1 == 45) {
cout << "Ada tipe yang terjual lagi selain 45? (1) Ya | (2) Tidak : "; cin >> konfirmasi;
if(konfirmasi == 1) {
cout << "\nMasukan tipe rumah yang terjual ( 54 / 70 ): "; cin >> tipe_rumah2;
cout << "Masukan jumlah rumah yang terjual : ";
cin >> jumlah2;
if(tipe_rumah2 == 54) { if(jumlah1 <= 5) {
hasil1 = jumlah1*250000; if(jumlah2 <= 5){
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*500000; if(jumlah2 <= 5){
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;

} }
} else if(tipe_rumah2 == 70) { if(jumlah1 <= 5) {
hasil1 = jumlah1*250000; if(jumlah2 <= 5){
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*500000; if(jumlah2 <= 5){
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} }
}
} else {
if(jumlah1 <= 5) {
hasil1 = jumlah1*250000;
cout << "Bonus yang diterima : " << hasil1; } else if(jumlah1 > 5) {
hasil1 = jumlah1*500000;
cout << "Bonus yang diterima : " << hasil1;
} }
} else if(tipe_rumah1 == 54) {
cout << "Ada tipe yang terjual lagi selain 54? (1) Ya | (2) Tidak : "; cin >> konfirmasi;
if(konfirmasi == 1) {
cout << "\nMasukan tipe rumah yang terjual ( 45 / 70 ): "; cin >> tipe_rumah2;
cout << "Masukan jumlah rumah yang terjual : ";
cin >> jumlah2;

if(tipe_rumah2 == 45) { if(jumlah1 <= 5) {
hasil1 = jumlah1*500000; if(jumlah2 <= 5){
hasil2 = jumlah2*250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*1000000; if(jumlah2 <= 5){
hasil2 = jumlah2*250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} }
} else if(tipe_rumah2 == 70) { if(jumlah1 <= 5) {
hasil1 = jumlah1*500000; if(jumlah2 <= 5){
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*1000000; if(jumlah2 <= 5){
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1250000;

totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil; }
} }
} else {
if(jumlah1 <= 5) {
hasil1 = jumlah1*500000;
cout << "Bonus yang diterima : " << hasil1;
} else if(jumlah1 > 5) {
hasil1 = jumlah1*1000000;
cout << "Bonus yang diterima : " << hasil1; }
}
} else if(tipe_rumah1 == 70) {
cout << "Ada tipe yang terjual lagi selain 70? (1) Ya | (2) Tidak : "; cin >> konfirmasi;
if(konfirmasi == 1) {
cout << "\nMasukan tipe rumah yang terjual ( 45 / 54 ): "; cin >> tipe_rumah2;
cout << "Masukan jumlah rumah yang terjual : ";
cin >> jumlah2;
if(tipe_rumah2 == 45) { if(jumlah1 <= 5) {
hasil1 = jumlah1*1000000; if(jumlah2 <= 5){
hasil2 = jumlah2*250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*1250000; if(jumlah2 <= 5){
hasil2 = jumlah2*250000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;

} }
} else if(tipe_rumah2 == 54) { if(jumlah1 <= 5) {
hasil1 = jumlah1*1000000; if(jumlah2 <= 5){
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
}
} else if(jumlah1 > 5) {
hasil1 = jumlah1*1250000; if(jumlah2 <= 5){
hasil2 = jumlah2*500000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} else if(jumlah2 > 5) {
hasil2 = jumlah2*1000000;
totalhasil = hasil1 + hasil2;
cout << "Bonus yang diterima : " << totalhasil;
} }
}
} else {
if(jumlah1 <= 5) {
hasil1 = jumlah1*1000000;
cout << "Bonus yang diterima : " << hasil1; } else if(jumlah1 > 5) {
hasil1 = jumlah1*1250000;
cout << "Bonus yang diterima : " << hasil1;
} }
} else {
cout << "Tipe yang dimasukkan salah" << endl;
} }
Terakhir diubah: 10:11
