# wordpress-docker-bedrock-starter
Docker Wordpress starter with bedrock where the goal is for you to be able to develop and use it eazy. Also works in a production enviornment.

# Requirements

  - Composer
  - Docker 
  - Docker compose


# Installation and local development

1. Open `/website/bedrock` and run `composer install`
2. Edit .env files in the folder `env` to match your information. 
  - If you are running this template locally for development is .env.dev already loaded in docker
3. Run `docker compose up`
4. Open `http://localhost:8080` in your browser

# Database
Locally you get a mariadb ready to be used for development but for deploying to the cloud .

If you deploy this template to the cloud for production do you need to create a `.env` file with information pointing to your database

