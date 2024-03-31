# sintony


## run tests
sudo docker compose run --rm app sh -c "python manage.py test"

## run lint
sudo docker compose run --rm app sh -c "flake8"

## run test + lint 
sudo docker compose run --rm app sh -c "python manage.py test && flake8"

