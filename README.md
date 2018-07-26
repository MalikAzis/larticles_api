# larticles_api

## migrate database:

php artisan migrate

## insert seed:

php artisan db:seed

# Endpoints Api

## List All Articles
GET api/articles

## Get single Article
GET api/article/{id}

## Delete 
DELETE api/article/{id}

## Insert new Article
POST api/article
    'title', 'body'

## Update 

PUT api/article
    'article_id', 'title', 'body'
