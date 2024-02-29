### Opis aplikacji

## 1. Wymagania

- python 3.10+
- django min.5.0
- paczka Pillow
- silnik bazy sqlite3

## 2. Uruchomienie projektu

Wykonanie polecenia
Dla Windows

```sh
python -m venv venv
```

Dla Unix

```sh
python3 -m venv venv
```

Uruchomienie wirtualnej zmiennej środowiskowej (venv)
Dla Windows

```sh
PowerShell
.\venv\Scripts\activate
lub (GIT bash)
source venv/Scripts/active
```

Instalacja Django

```sh
pip install django
```

Instalacja Pillow

```sh
pip install Pillow
```

(Opcjonalnie jeżeli jest pusta baza to)

```sh
python manage.py migrate
```

oraz stworzenie superusera

```sh
python manage.py create superuser
```

W przypadku używania silnika sqlite 3 z repo dane do logowania

```sh
login: costam
password: jakiestam
```

Uruchomienie serwera

```sh
python manage.py runserver
```
