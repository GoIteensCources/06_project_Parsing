# Mini project: Parsing HTML

Написали невеличкий додаток, який складається з одного роуту "/info-url". Він приймає обов'язковим параметром URL веб-сторінки для парсингу. 
Валідує цей параметр, отримує HTML-код сторінки і витягає з нього __заголовок__ та __всі посилання__.


## Dependency
Встановлення залежностей 
```bash 
pip install -f requrements.txt
```


## Testing
Запуск тестування
```bash
pyest -v test.py
```

## Documentation

BeautifulSoup: https://www.crummy.com/software/BeautifulSoup/bs4/doc/
