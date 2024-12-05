# Practice your web testing skills

This is a fork of group meetings scheduling app prepared for practicing web testing skills. __Do not use it in production environment__. 

## How to run it with Docker
You need to have Docker and Docker Compose installed. 
Clone this repo and change directory to the root of the repository.
```
git clone https://github.com/Testelka/rallly-selfhosted.git
cd rallly-selfhosted
```
Do not change the name of the "rallly-selfhosted" folder. If you do, you need to first change SMTP_HOST (rallly-selfhosted-mailhog-1) in config.env file before running a server.

Then start the server by running:
```
docker compose up -d
```

It might take a while. Your web app will be available at http://localhost:3000. You can use Mailhog to test emails at http://localhost:8025.

## Documentation

Check how the app works here: https://support.rallly.co/.
