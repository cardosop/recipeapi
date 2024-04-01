# sintony


## run tests
docker compose run --rm app sh -c "python manage.py test"

## run lint
docker compose run --rm app sh -c "flake8"

## run test + lint 
docker compose run --rm app sh -c "python manage.py test && flake8"

Token 65124577f0a21ff0e93838edfe5e570a87728c6