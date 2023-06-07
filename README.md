# starter_project

## Got Started

This project was initialized with the following commands:

```bash
rvm install 3.2.2
nvm install 18.16.0
rvm use 3.2.2
nvm use 18.16.0
...
npm install --global yarn
rails new starter_project --database=postgresql --skip-test --css=sass --javascript=importmap
cd starter_project
echo "18.16.0" > .nvmrc
```

## Setup

```bash
rails db:setup
rails db:migrate
```


### Provided

* SASS
* Devise
