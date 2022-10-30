# PROPOSAL PROJECT
* __a-Weather__

## Permasalahan
* dalam keseharian, ketika kita ingin mengetahui kondisi cuaca di tempat-tempat tertentu, kadang kita hanya bisa mengetahui dari perkiraan saja. Apakah hari itu, di tempat tersebut, dalam kondisi cerah atau akan turun hujan. Fitur yang disediakan di beberapa jenis telepon genggam juga hanya memberi keterangan suhu udara sekitar dan keterangan singkatnya. Pada beberapa keadaan, kita ingin mengetahui secara lebih detail mengenai info cuaca di tempat-tempat tertentu.

## Rencana Solusi
* Aplikasi a-Weather di dalamnya memberikan kemudahan bagi user ketika ingin mencari tahu detail cuaca di tempat-tempat yang mereka ingin ketahui.

## Use Case
* User dapat melakukan pencarian cuaca berdasarkan kota
* User dapat melihat informasi hasil pencarian

## Struktur Data
* reweather

| Atribut  | Tipe Data | Contoh    |
| -------- | --------- | --------  |
| id       | int       | 1111      |
| city     | string    | Jakarta   |
| country  | string    | Indonesia |

* result

| Atribut      | Tipe Data | Contoh             |
| ------------ | --------- | -----------        |
| id           | int       | 1109               |
| location     | string    | Jakarta, Indonesia |
| date         | date      | 2012, 30/1         | 
| temperature  | string    | 21                 | 

* details

| Atribut      | Tipe Data | Contoh         |
| ------------ | --------- | ------         |
| id           | int       | 110            |
| high/low     | string    | 20/21          |
| kelembapan   | string    | 89%            | 
| tekanan      | string    | 1011 hPa       |
| jarakpandang | string    | 10 km          |
| angin        | string    | 1 km/hr        |
| terbit       | string    | 05.22          |
| terbenam     | string    | 17.43          |
| arahangin    | string    | 46 deg         |

* city

| Atribut  | Tipe Data | Contoh    |
| -------- | --------- | --------  |
| id       | string    | JKT       |
| city     | string    | Jakarta   |

* country

| Atribut  | Tipe Data | Contoh    |
| -------- | --------- | --------  |
| id       | string    | IDN       |
| country  | string    | Indonesia |


## UX Wireframe

![IMG_20221030_201321lll](https://user-images.githubusercontent.com/75475592/198882291-3c741765-1771-49cc-8f47-4972c3a8592b.jpg)

