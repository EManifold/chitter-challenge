# Chitter

## Description

This is a web app that allows the user to sign up by entering their preferred username, email and password, and once this is done they are able to post a peep (similar to a tweet). The user is able to see all peeps on the homepage, in reverse choronological order.

## Installation

- Install PostgreSQL, setup your user and create a database called chitter.
- Open the db with command ```psql chitter```
- Create the two tables using the commands in db/migrations/01_create_peeps_table.sql and db/migrations/02_create_users_table.sql
- Run bundle install
- Run rspec to see tests
- Run ``` ruby app.rb ``` to use Chitter

## Usage
The app opens on the homepage displaying all the peeps.
<img width="1279" alt="Screenshot 2019-12-29 at 11 00 05" src="https://user-images.githubusercontent.com/53044792/71556001-92e9a480-2a2a-11ea-8022-b934cc3cd428.png">

From the homepage the user can sign up.
<img width="1274" alt="Screenshot 2019-12-29 at 11 00 18" src="https://user-images.githubusercontent.com/53044792/71556009-b14fa000-2a2a-11ea-9895-8092650a2bbb.png">

Once signed up, the user can post their own peep.  
<img width="1275" alt="Screenshot 2019-12-29 at 11 01 07" src="https://user-images.githubusercontent.com/53044792/71556012-ba407180-2a2a-11ea-8d8f-28301c04e45d.png">

Then the user will be redirected back to the homepage, where their new peep is displayed.
<img width="1277" alt="Screenshot 2019-12-29 at 11 01 19" src="https://user-images.githubusercontent.com/53044792/71556020-d5ab7c80-2a2a-11ea-8c47-d500478b6769.png">

## Technology used

- Ruby
- Sinatra
- PostgreSQL
- Capybara
- Bootstrap
- HTML
- CSS
- RSpec

## Project Status

Project is fully functioning but can be expanded to include a login system for users, deleting, updating and editable commenting on peeps. App also needs styling.
