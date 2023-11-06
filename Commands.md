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

```shell
python main.py runserver
streamlit run post_app/app1.py --server.port=30110 > post_app/app.log 2>&1 &
streamlit run music_app/app2.py --server.port=30120 > music_app/app.log 2>&1 &
streamlit run document_app/app3.py --server.port=30130 > document_app/app.log 2>&1 &
```