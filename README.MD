## Now run the following command from the dockerize_laravel folder to start all the 3 services
docker-compose up --build
docker-compose up --build -d
## Now open up a new terminal tab and cd into the dockerize_laravel folder from there run the following commands to do a composer install in the container
docker-compose exec php sh
cd /var/www/html
composer install

## Run the following command to generate the application key in the .env file
php artisan key:generate
## Your beautiful Laravel application is up and running on localhost:8080

## docker 
ocker login -u YOUR-USER-NAME
docker login
docker tag 91b53e2624b4 nyhasinas/91b53e2624b4
docker push nyhasinas/6a9f904606f5
docker push nyhasinas/2f6c46b8567b
docker push nyhasinas/91b53e2624b4

## Githug
git config --global user.name "Ny Hasina"
git config --global user.email nyhasinas@yahoo.fr