# yyy
Microsoft Windows [Version 10.0.22621.2715]
(c) Microsoft Corporation. All rights reserved.

C:\Users\unpri>D:

D:\>mkdir "TI 4 Pagi A 2024 Tahap 2"

D:\>dir
 Volume in drive D is Data
 Volume Serial Number is 3665-B330

 Directory of D:\

28/10/2024  19:21    <DIR>          3MalamB
04/11/2024  11:10    <DIR>          3PagiB
20/01/2025  11:57    <DIR>          3pagiC
06/03/2025  19:58    <DIR>          3pagicc
22/10/2024  18:48    <DIR>          4malamA
15/10/2024  09:20    <DIR>          software
07/03/2025  12:03    <DIR>          TI 4 Pagi A 2024 Tahap 2
18/11/2024  11:04    <DIR>          TIpagiB
               0 File(s)              0 bytes
               8 Dir(s)  451.324.665.856 bytes free

D:\>cd "TI 4 Pagi A 2024 Tahap 2"

D:\TI 4 Pagi A 2024 Tahap 2>cd..

D:\>cd "TI 4 Pagi A 2024 Tahap 2"

D:\TI 4 Pagi A 2024 Tahap 2>
D:\TI 4 Pagi A 2024 Tahap 2>
D:\TI 4 Pagi A 2024 Tahap 2>mkdir latihan_00

D:\TI 4 Pagi A 2024 Tahap 2>cd latihan_00

D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>py -m venv env

D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>env\Scripts\activate

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>dir
 Volume in drive D is Data
 Volume Serial Number is 3665-B330

 Directory of D:\TI 4 Pagi A 2024 Tahap 2\latihan_00

07/03/2025  12:11    <DIR>          .
07/03/2025  12:07    <DIR>          ..
07/03/2025  12:11    <DIR>          env
               0 File(s)              0 bytes
               3 Dir(s)  451.298.484.224 bytes free

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip instal Django
ERROR: unknown command "instal" - maybe you meant "install"

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip install Django
Collecting Django
  Downloading Django-5.1.7-py3-none-any.whl (8.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 8.3/8.3 MB 18.2 MB/s eta 0:00:00
Collecting asgiref<4,>=3.8.1 (from Django)
  Using cached asgiref-3.8.1-py3-none-any.whl (23 kB)
Collecting sqlparse>=0.3.1 (from Django)
  Downloading sqlparse-0.5.3-py3-none-any.whl (44 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 44.4/44.4 kB ? eta 0:00:00
Collecting tzdata (from Django)
  Downloading tzdata-2025.1-py2.py3-none-any.whl (346 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 346.8/346.8 kB 22.4 MB/s eta 0:00:00
Installing collected packages: tzdata, sqlparse, asgiref, Django
Successfully installed Django-5.1.7 asgiref-3.8.1 sqlparse-0.5.3 tzdata-2025.1

[notice] A new release of pip is available: 23.1.2 -> 25.0.1
[notice] To update, run: python.exe -m pip install --upgrade pip

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip freeze
asgiref==3.8.1
Django==5.1.7
sqlparse==0.5.3
tzdata==2025.1

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip freeze requiements.txt
asgiref==3.8.1
Django==5.1.7
sqlparse==0.5.3
tzdata==2025.1

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip freeze > requiements.txt

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>pip freeze > requirements.txt

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>dir
 Volume in drive D is Data
 Volume Serial Number is 3665-B330

 Directory of D:\TI 4 Pagi A 2024 Tahap 2\latihan_00

07/03/2025  12:28    <DIR>          .
07/03/2025  12:07    <DIR>          ..
07/03/2025  12:11    <DIR>          env
07/03/2025  12:27                64 requiements.txt
07/03/2025  12:28                64 requirements.txt
               2 File(s)            128 bytes
               3 Dir(s)  451.256.750.080 bytes free

(env) D:\TI 4 Pagi A 2024 Tahap 2\latihan_00>
