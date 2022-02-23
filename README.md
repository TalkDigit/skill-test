## What is talkpanel?
TalkPanel is a pretty content management system developed for building corporate websites.

## Demo
Although it is still under development, you can see the admin panel using the following details.

- https://domain.com/admin
- john@doe.com
- password

<img src="https://user-images.githubusercontent.com/8471647/120819300-55f0de00-c54b-11eb-80ae-dfe49c000eb6.png" width="500" alt="talkpanel admin panel">


## Tech Stack
- Laravel 8
- Vue & Vuex
- TailwindCSS
- Jest
- ESLint
- JWT Auth
- REST API
- Airbnb JS Style Guide

## Installation
- Change document root from public_html to public_html/public
- Create a database and an user
- Rename the .env.example file as .env and edit
- Run the commands in order
    - ```git clone https://github.com/TalkDigit/skill-test.git .```
    - ```chgrp 99 public (as root user)```
    - ```chmod 750 public```
    - ```composer install --optimize-autoloader --no-dev```
    - ```php artisan key:generate```
    - ```php artisan jwt:secret```
    - ```php artisan migration:fresh --seed```
    - ```npm install```
    - ```npm run dev```
    - ```make sure you're connected to a valid database```


## License
[MIT](https://choosealicense.com/licenses/mit/)

