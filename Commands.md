### Check database

```shell
mysqladmin ping -h 127.0.0.1 -u root -p
bjit1234
```
### Run Project
```shell
uvicorn main:app --host 0.0.0.0 --port 8000 > app.log 2>&1 &
# or
python main.py runserver 0.0.0.0:<port_number>
```