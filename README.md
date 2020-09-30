# PHOSPHORUS Software Engineer Take-home test
## requirements
- Linux or MacOS
- Docker

### Docker container build sequence
1. build the docker containers with `docker-compose build`
2. run the rake task to build database in another docker container with `docker-compose run web rake db:create`
3. boot up the app with `docker-compose up`


### NOTE
App runs on port 3000 by default
PostgreSQL DB runs on port 5432 by default


### Instructions
- If you're here for a takehome follow the build sequence above.
- Once complete, you may start building the app.
- As instructed, you will be building a UI for the elevator problem you tackled in the previous Interview.
- In this stage, you are free to build the app however you please.
- You can build it in Rails or with other front-end frameworks if you please (React, Vue, Angular, etc.)
- If you choose to use a front-end framework, the setup will fall on you to complete.
- You have 72 hours to complete this project.
- When you are complete, you will follow the below instructions to export it to a zip file.

### Zipping project when complete
1. Run the following command `git archive --format zip --output /path/to/zipfile.zip HEAD`
2. You can choose another branch, but `HEAD` will archive the current working branch.
3. Once you've zipped the file, send it over to an engineer and schedule a time to go over the project you've created.

# Have fun :)
