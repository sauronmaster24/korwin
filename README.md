# "Generator Korwinizmów"
by Piotr Jaworski & Waldemar Wojna

## Jak  to odpalić?

```bash
Stwórz w jakimś miejscu folder o dowolnej nazwie np. na pulpicie.
Wejdź w cmd , a następnie wpisz:
cd sciezka_do_twojego_folderu
```

```bash
Następnie wpisz:
git clone https://github.com/sauronmaster24/korwin.git
```

```bash
Przejdź do folderu projektu:
cd korwin
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

```bash
python manage.py runserver
```



#A jeśli Ci wyskoczy błąd:
Git fatal: protocol 'https' is not supported


Use right-click paste, instead of crtl+V (see [this answer](https://stackoverflow.com/a/55985462/8877692)).
