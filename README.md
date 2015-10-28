# RailsCasts Episode #403: Dynamic Forms (pro)

[![Join the chat at https://gitter.im/joaoribeirost/403-dynamic-forms](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/joaoribeirost/403-dynamic-forms?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

http://railscasts.com/episodes/403-dynamic-forms

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
rails g scaffold ProductType name --skip-stylesheets
rails g model ProductField name field_type required:boolean product_type:belongs_to
rails g migration add_type_to_products product_type_id:integer properties:text
rake db:migrate
```
