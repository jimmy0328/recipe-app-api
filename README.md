
## run build

```
docker-compose build
```

## run test

```
docker-compose run app sh -c "python manage.py test"
```

## run test with flake8
```
docker-compose run app sh -c "python manage.py test && flake8"
```