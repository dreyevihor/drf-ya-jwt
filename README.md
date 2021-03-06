# Yet Another JWT for Django Rest Framework
###### Inspired by [django-rest-framework-jwt](https://github.com/GetBlimp/django-rest-framework-jwt)


### Benefits
1. You can store tokens in redis instead of database
2. `drf-ya-jwt.extras` provides opportunity to prevent access some objects (instances of models, or another python-objects)


### How to install
```bash
python -m pip install git+https://github.com/TihonV/drf-ya-jwt.git
```

### Roadmap
1. Implement auth-middleware
2. Implement possibility to use redis as token storage
3. Implement lock/unlock methods for objects to prevent access from other user
4. Implement admin-pane for manage session and resolve locks
