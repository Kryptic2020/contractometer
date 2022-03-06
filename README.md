# README

**new
## https://www.youtube.com/watch?v=YOiEAAac5Co

**old
## https://www.youtube.com/watch?v=mVRBuEAHkDE



rails new contractometer -d postgresql --skip-test --skip-bundle --skip-turbolinks       

bundle add turbo-rails 

rails webpacker:install   

rails turbo:install     

yarn add @hotwired/turbo-rails  

bundle add stimulus-rails   

rails stimulus:install  

rails turbo:install:redis   

yarn add bootstrap jquery @popperjs/core  

javascript.js/packs/application.js include:
```js
import Rails from "@rails/ujs"
import "@hotwired/turbo-rails"
import * as ActiveStorage from "@rails/activestorage"
import "channels"
Rails.start()
ActiveStorage.start()
import "controllers"
import "bootstrap"
import '../stylesheets/application'
```
add javascript.js/packs/stylesheets/application folder
add application.scss like:
```js
 @import "~bootstrap/scss/bootstrap"; 
 ```


bundle

rails g scaffold time_tracker topic rate_per_hour:numeric started_at:datetime ended_at:datetime status

rake db:create db:migrate  

yarn add @fortawesome/fontawesome-free
javascript.js/packs/application.js include:
```js
import '@fortawesome/fontawesome-free/css/all'
```

