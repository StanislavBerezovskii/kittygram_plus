### Launching the project:

Clone the repository and switch to it on the command line:

```
git clone https://github.com/yandex-praktikum/kittygram_plus.git
```

```
cd kittygram_plus
```

Create and activate a virtual environment:

```
python3 -m venv env
```

```
source env/bin/activate
```

Install dependencies from the requirements.txt file:

```
python3 -m pip install --upgrade pip
```

```
pip install -r requirements.txt
```

Run migrations:

```
python3 manage.py migrate
```

Run the project:

```
python3 manage.py runserver
```
