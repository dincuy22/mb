**aplikasi hanya berisi:**
- 1 model post
- test untuk model post

**Heroku Config**
1. install gunicorn==19.9.0
2. add a Procfile -> web: gunicorn config.wsgi --log-file -
3. update ALLOWED_HOSTS -> .herokuapp.com, localhost, 127.0.0.1