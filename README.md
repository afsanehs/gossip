# How to run the file :

* `bundle install`
* `shotgun -p 4567`
* Go to http://localhost:4567/ 

# Files explanations : 

## Gemfile
I'm using ruby V.2.5.1, gems sinatra & shotgun

## config.ru 
Contains necessary infos in order to launch the server

## gossip.csv 
This file is located in the "db" folder & contains the data entered on the forms 

## controller.rb
This file is located in the "lib" folder & contains the code which handles the http requests

## gossip.rb 
This file is located in the "lib" folder & defines a model, which reads and writes data

## index.erb 
This file is located in the "views" folder & contains the front-end code of the welcome page 

## new_gossip.erb
This file is located in the "views" folder & contains the front-end code of the page for creating a new gossip 

## show.erb 
This file is located in the "views" folder & contains the front-end code of each individual gossip page 
