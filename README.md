# Movies_List

|  Anggota Kelompok  |
|----------------|
|Muhammad Rizqi Maulana (312210360)|
|Afrizal Fajrianto Anggara (312210449)|
|Sandy Ramadhan (312210633)|
||

Membangun aplikasi web Sistem Rekomendasi Film menggunakan framework Django dan teknik rekomendasi yang disebut Collaborative Filtering - Algoritma Matrix Factorization.

### Demo Tampilan

https://github.com/rizqimaulana04/Movies_List/assets/115638135/5f4809e3-b1dc-42c4-a559-afaba2845cbe

### Technologies Used
#### Web Technologies
- Python
- HTML 
- CSS
- JavaScript
- Bootstrap 

#### Python Packages 
- Django
- Numpy
- Pandas 
- Scipy

#### Database
SQLite

##### Requirements
```
python 3.12
pip3
virtualenv
```

##### Setup to run

- Download zip file to your local machine
- Extract the zip file
- Open terminal/cmd promt
- Goto that Path

Example

```
cd ~/Users/Asus/Movies-List
```

Create a new virtual environment in that directory
```
python3.6 -m pip install virtualenv
virtualenv venv -p python3.6
```

Activate virtual environment
```
source venv/bin/activate
```

Then
```
cd ../Movies_List
```

Command line to run your program
```
python manage.py migrate
python manage.py runserver
```

Now open your browser and go to this address
```
http://127.0.0.1:8000
```
