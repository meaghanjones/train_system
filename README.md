# Train System
### Meaghan Jones and Caleb Stokka

### Description 

We created an app to meet the following user stories:

* As a train system operator, I want to create, read, update, delete and list trains, so that I can track all of the trains in my system.

* As a train system operator, I want to create, read, update, delete and list cities where my trains will stop, so that I can manage where all of the trains will go.

* As a train rider, I want to view a train, so that I can see the cities where it stops.

* As a train rider, I want to view a city, so that I can see which trains come to it.

* As a train rider, I want to see a timetable that shows what time each train stops in each city.

* As a train rider, I want to purchase a ticket in a particular city for a particular train so that I can get on and off in any city that train travels. (This can work like a MAX ticket where you are able to purchase the ticket independent of the destination).



Installation
------------

Install *Dealerships* by cloning the repository.  
```
$ git clone https://github.com/meaghanjones/train_system
```

Install required gems:
```
$ bundle install
```

```
In PSQL:
CREATE DATABASE hair_salon;
CREATE TABLE clients (id serial PRIMARY KEY, name varchar, phone varchar, stylist_id int);
CREATE TABLE stylists (id serial PRIMARY KEY, name varchar, phone varchar, specialty varchar);
```

Start the Sinatra webserver:
```
$ ruby app.rb
```

Navigate to `localhost:4567` in your browser of choice.

License
-------
_This software is licensed under the MIT license._<br>
Copyright (c) 2016 **Meaghan Jones**
