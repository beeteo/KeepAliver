## KeepAliver ━	Flask
KeepAliver is a python library using Flask to keep scripts running 24/7 using flask, created primarily for use on replit

---

```
$ pip install KeepAliver
```

---

## Run application

```py
from KeepAliver import KeepCreate

app = KeepCreate()

if __name__ == '__main__':
    app.run(logs=True)
```

## Docs

- ` app.run(logs=False) -> logs ` : `logs=True`: dont show console logs > `logs=False` : show all console logs
- ` app.run(runmsg='helloworld') -> runmsg ` : Description > custom message to start keep alive


> this library was created in 3 minutes lol
