## Story: As a developer I can create an animal model in the database. An animal has the following information: common name, latin name, kingdom (mammal, insect, etc.).

(DONE)

## Story: As the consumer of the API I can see all the animals in the database.
Hint: Make a few animals using Rails Console

(DONE)

## Story: As the consumer of the API I can update an animal in the database.

(DONE)

## Story: As the consumer of the API I can destroy an animal in the database.

NEED MORE RESEARCH 
(DONE)

## Story: As the consumer of the API I can create a new animal in the database.

(DONE)

## Story: As the consumer of the API I can create a sighting of an animal with date (use the datetime datatype), a latitude, and a longitude.
Hint: An animal has_many sightings. (rails g resource Sighting animal_id:integer ...)
Hint: Datetime is written in Rails as “year-month-day hr:min:sec" (“2022-01-28 05:40:30")

(DONE)

animal has_many
    use animal id
    

sightings belongs_to





## Story: As the consumer of the API I can update an animal sighting in the database.



## Story: As the consumer of the API I can destroy an animal sighting in the database.
## Story: As the consumer of the API, when I view a specific animal, I can also see a list sightings of that animal.
Hint: Checkout the Ruby on Rails API docs on how to include associations.
## Story: As the consumer of the API, I can run a report to list all sightings during a given time period.
Hint: Your controller can look like this: