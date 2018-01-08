# Rails 5.1 & Vue.js 2 CRUD

This repo implements CRUD operations using Webpack. Check out [live demo](https://evening-brook-15906.herokuapp.com).

### Requirements:
- Ruby 2.2.2 or newer
- Node 6.4 or newer

### Things to do
```
$ git clone git@github.com:ecmelkytz/rails_vuejs_crud.git
$ cd rails_vuejs_crud
```

Open gemfile and change the ruby version
ruby '2.4.2'

```
$ stt gemfile

source 'https://rubygems.org'
ruby '2.4.2'
```
Then ...

```
$ bundle
$ yarn install
$ rails db:create
$ rails db:migrate
$ rails db:seed
$ rails s
$ ./bin/webpack-dev-server
```
