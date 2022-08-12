# belajar-sass

## Note:
1. SASS : Syntactically Awesome Style Sheets
2. WPU SASS| 2 Nesting -> 5:20 Preference Setting
3. File -> Preferences -> Settings -> cari live sass compiler, "savePath": "~/../css/" | CTRL + ,
4. ul>li*5>a{Link $} : shortcut buat elemet ul didalamnya ada 5 element li dibungkus a
5. Alt Shift bawah : copy element kebawah
6. File scss yang ada underscore itu merupakan module
Masalah :
1. Buat Folder CSS masih error Solver



Versi SASS :
1. Lite SASS : versi VS Code
2. Dart SASS : versi installl di komputer

import memiliki masalah jadi gunakan @use 
windows : 

Install Sass (Solusi Error npm - EPERM: operation not permitted on Windows):
1. Buka bash dari VS Code
2. npm config edit, akan buka notepad
3. Ubah prefix dari 
C:\Program Files\Git\usr\local
menjadi
prefix=C:\Users\User\AppData\Roaming\npm
4. https://stackoverflow.com/questions/34600932/npm-eperm-operation-not-permitted-on-windows
5. Daftarkan env varibel
    - C:\Program Files (x86)\Git\local
    - C:\Program Files\Git\bin;C:\Windows\system32
6. npm install -g sass
7. sass; jika muncul versi sass maka uda pake versi DART SASS
8. Ubah @import jadi pake @use. Cara jalankan :
```$ sass scss/main.scss css/main.css```
9. (Built-in Modules)[https://sass-lang.com/documentation/modules]
   - Color
      - adjust
      - complement
      - darken
      - lighten
      - saturate
      - desaturate
      - grayscale
      - mix
      - fade-in
      - fade-out
   - List
   - Map
   - Math
   - Meta
   - Selector
   - String


        
