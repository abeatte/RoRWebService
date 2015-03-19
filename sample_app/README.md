== README


*Notes*
Run tests: $ bundle exec rake test
Run server: $ rails s
Build: $ bundle install --without production
	   $ bundle update
Creating new models: $ rails generate model modName fieldName:type fieldName:type
Creating new controllers: $ rails generate controller contName [methodNames]
Update db fields: $ rails generate migration migName fieldName:fieldType
				  $ bundle exec rake db:migrate

Adding the line "debugger" to code allows for console debugging of state
To release debugger press "control + d"


This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Please feel free to use a different markup language if you do not plan to run
<tt>rake doc:app</tt>.
