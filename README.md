# VSC-File-Proyek

Template Program untuk mengukur tingkat indeks Ruffier dengan meminta user/pengguna untuk melakukan aktifitas olahraga dan mengukur denyut nadi

# Software used:
Algo VS Code - Algorithmics Visual Studio Code

# Instructions
Software sudah siap untuk digunakan, yang Anda perlukan hanyalah untuk mengisi file untuk window ke-3, di file final_win

## Untuk file final_win
  * Importing
  
  ```
   from PyQt5.QtCore import Qt, QTimer, QTime, QLocale
   from PyQt5.QtGui import QDoubleValidator, QIntValidator, QFont # checking the types of input values
   from PyQt5.QtWidgets import (
        QApplication, QWidget, 
        QHBoxLayout, QVBoxLayout, QGridLayout, 
        QGroupBox, QRadioButton,
        QPushButton, QLabel, QListWidget, QLineEdit)

   from instr import *
```
  import saja apa yang dibutuhkan

  * class
  ```
  class MainWin(QWidget):
    def __init__(self):
        ''' the window which the greeting is located in '''
        super().__init__()

        # creating and configuring graphic elements:
        self.initUI()

        #sets the window appearance (label, size, location)
        self.set_appear()

        # start:
        self.show()

    def initUI(self):
        ''' creates graphic elements '''

    def calculation(self):
        ''' index calculation '''


    ''' sets what the window will look like (label, size, location) '''
    def set_appear(self):
        self.setWindowTitle(txt_title)
        self.resize(win_width, win_height)
        self.move(win_x, win_y)

  ```
  Ini adalah template dasarnya, anda masih harus melengkapi template ini sendiri
  Catatan: pada kelas ini diambil properti exp dari file second_win

# Catatan

Untuk detail lebih lanjut check di:
.........

# License

.......
Lihat `licence.txt` untuk informasi lebih lanjut

# Contact
HansenHansen - expertsanituration48@gmail.com
Project Link: https://learn.algorithmics.asia/lesson?lesson=30208&level=1&module=7&task=70440

# Lainnya
.....
