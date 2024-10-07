
| Run:<br>shell:startup                                                                                       | Mở thư mục start up trong window                      |
| ----------------------------------------------------------------------------------------------------------- | ----------------------------------------------------- |
| pyinstaller --add-data "Tenfile.ico;." --onefile --noconsole --windowed --icon="Tenfile.ico" Tenfile.py     | Tạo app python với icon                               |
| pyinstaller --add-data "Tenfile.ico;." --onedir --noconsole --windowed --icon="Tenfile.ico" Tenfile.py      | Cách này tạo app python với file exe nhẹ và nhanh hơn |
| python "I:\My Software\3.DIY Software\Ko share Source code\Ref-View\Ref-view.py" "D:\EXPERIMENT\pan.rw"<br> | Mở file pan.rw bằng file ref-view.py thông qua cmd    |
Khi cài python, muốn đổi icon xem file sau: [[Icon python.txt]]

python "I:\My Software\3.DIY Software\Ko share Source code\RefVideo\RefVideotusua.py" "D:\PROJECTS\Pan&Beri\1.Project Setup\Library\Animation demo\test.rwv"

pyinstaller --add-data "Ref-view.ico;." --onedir --noconsole --windowed --icon="Ref-view.ico" Referennces.py