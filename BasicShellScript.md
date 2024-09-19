# **Basic Bash Script**
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
### Get CurrentDate
#### (Wed Sep  4 15:05:32 WIB 2024)
```
date
```
#### YYYY-MM-DD (2024-09-04)
```
date +%F
```
#### Format HH:MM:SS (12:34:56)
```
date +%T
```
#### Format YYYY-MM-DD HH:MM:SS (2024-09-04 15:15:43)
```
date "+%Y-%m-%d %H:%M:%S"
```
#### Format DayOfWeek Month Day HH:MM:SS Year (Wed Sep 04 15:16:35 2024)
```
date +"%a %b %d %H:%M:%S %Y"
```
#### Format MM-DD-YYYY (09-04-2024)
```
date +%m-%d-%Y
```
#### Tanggal dalam Format DayOfWeek, Month Day, Year (Wednesday, September 04, 2024)
```
date +"%A, %B %d, %Y"
```
#### Format MMM-YYYY (SEP 2024)
```
date +"%b %Y" | tr '[:lower:]' '[:upper:]'
```
- date +"%b %Y" : Menampilkan bulan dalam format singkat dan tahun (misalnya, Sep 2024).
- tr '[:lower:]' '[:upper:]' : Mengubah semua huruf kecil menjadi huruf besar.
#### Killing Oracle Process
```
ps -ef | grep LOCAL=NO | awk '{print$2}' | xargs kill -9
```

***

