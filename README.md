# ContactBook JS App + RESTful API

The JS app "Contact Book" holds a searcheable list of contacts. It supports the following operations:
 - List all contact: `/contacts`
 - View single contact (by id): `/contacts/:id`
 - Search for contact: `/contacts/search/:keyword`
 - Add a new contact (first name + last name + email + phone + comments): `/contacts/create`

## App Details

The app is based on Node.js + Express.js + Pug.
 - It has **no database** and app data is not persistent!

Demo:
 - Web app live demo: https://contactbook.nakov.repl.co
 - RESTful API live demo: https://contactbook.nakov.repl.co/api
 - Play with the code at: https://repl.it/@nakov/contactbook

## RESTful API

The following endpoints are supported:
 - `GET /api` - list all API endpoints
 - `GET /api/contacts` - list all contacts
 - `GET /api/contact/:id` - returns a contact by given `id`
 - `GET /api/contacts/search/:keyword` - list all contacts matching given keyword
 - `POST /api/contacts` - create a new contact (post a JSON objects in the request body, e.g. `{"firstName":"Marie", "lastName":"Curie", "email":"marie67@gmail.com", "phone":"+1 800 200 300", "comments":"Old friend"}`

## Screenshots

TODO
