# Picagram

> An Instagram clone for the Makers week 8 weekend challenge

User can:
- Sign up
    - Interaction is limited unless an account is created
    - Every detail is encrypted and securly stored

- Log in
    - Main page functionality is unlocked
    - Profile page is accessable

- Edit profile
    - Able to edit user details
    - Able to delete pictures
    - Able to change avatar

- Post pictures
    - Able to post a picture. Shows up on profile and main pages.
    - Currently limited to 3 per user

Live site can be found [here](https://pic-a-gram.herokuapp.com/)

## To install

`git clone -github repo-`  
`cd 10monkeys`  
`bundle install`  
`/bin/rails db:create`  
`/bin/rails db:migrate`  
`rails server`

Open up a browser and point to `localhost:3000`

### Technology/frameworks used

- Ruby 
    - Rails
    - Devise
    - Activestorage

- Web
    - Bootstrap
    - Jquery

- Postgres  

- AWS  

## TODOs

- Log out ability
- Time stamps
- Abil to see details on posts
- Enable 'like' system
- Users can interact with other users
- 'Filters' for pictures
- Enable tagging system
- Full range of code quality checks ie. Travis, Codeclimate, Hound.


