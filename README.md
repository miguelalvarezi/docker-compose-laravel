# docker-compose-laravel
Laravel development environment based on Docker Compose.

## How to use

* Clone this repository and change into it's directory.

* Download your Laravel project to a newly created _laravel_ directory. For example:

`# git clone git@github.com:you/your-repo.git laravel`

* Start containers:

`# docker-compose up -d`

* Now your Laravel project should be running on [http://locahost:8000/](http://locahost:8000/). Install it and/or configure it however you prefer, using the following configuration parameters for the database:
  * Host: db
  * Name: laravel
  * User: docker
  * Password: docker
