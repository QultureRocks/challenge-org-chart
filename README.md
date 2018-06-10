# Qulture.rocks Challenge - Company Org-chart

This is the basic setup for your project. 
We provided a simple db (file: db.json) that represents the companies structure.

Each company has many users.
Each user relates to many tags through taggings, i.e., if "John" has the tag "Engineer", there should be a row on the taggings table with john's id and that tag id.

## Project setup

1. Run `npm-install`
2. To start the server run `json-server --watch db.json`. 
3. Access `http://localhost:3003/` and make sure it's working.

ref: https://github.com/typicode/json-server