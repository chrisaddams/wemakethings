# KeystoneJs running in docker containers

This configuration uses docker-compose to standup seperate app and db containers that communicate with each other via tcp.

==setup instructions
clone the repo: $git clone
run: $npm install
run: $docker-compose build
run: $docker-compose up

Your site should now be running using two docker containers and will refresh following changes in development using nodemon

--remember that you'll need to update the details in the .env file
