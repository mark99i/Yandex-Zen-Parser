# Yandex-Zen-Parser
Python 3 script to copy all publications of one author to .docx file. Script writing and tested on Python 3.7 version.

You must install the packages before you can use them:
  1) grab (pip3 install grab) 
  2) lxml (pip3 install lxml)
  3) PySocks (pip3 install PySocks)
  4) urllib3 (pip3 install urllib3)
  5) python-docx (pip3 install python-docx)

Instructions for use:
  1) Open and scroll to the end of the author's entire channel to download all publications. It won't take long.
  2) Right click on the page -> save page as. As a result, you should get the html file of the page.
  3) Open the downloaded script zen-parser.py in a text editor, specify the full path to the html file (main_html_file_path) and the channel name (channel_name)
  4) [optional] You can also specify where to save the docx file (docx_filename)
  5) Run script
  
Инструкция по использованию:
  1) Откройте канал автора и пролистайте его до конца, чтобы загрузились все публикации. Обычно это не займет много времени.
  2) Нажмите ПКМ -> сохранить страницу как. В результате вы должны получить html файл страницы (остальные файлы не нужны).
  3) Откройте скаченный скрипт zen-parser.py в текстовом редакторе, укажите в переменной (main_html_file_path) путь до html файла и в переменной (channel_name) имя канала
  4) [необязательно] Вы можете указать путь до создаваемого docx файла в переменной (docx_filename)
  5) Запустите скрипт
