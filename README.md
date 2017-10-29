# Rails Lite

This rack app uses Ruby's unique metapogramming capability to create logic and functionality for request routing, base controllers, and base models.

## Setup & Dependencies

1. Clone the repo
2. Run `bundle install` to install necessary Ruby gems
3. Run `bundle exec ruby bin/__SERVER_FILENAME__` to start the server
4. In your browser, navigate to `http://localhost:3000`

## MVC Functionality

**ActiveRecord Lite ORM**

My lite version of  `ActiveRecord::Base` with methods including  `::all`, `::find`, `#insert`, `#update`, and `#save` can be found [here](https://github.com/vutpham/activerecord_lite).

**Controller, Router and Session**

Logic and functionality for request routing, base controllers, and session can be found in the `.lib` folder.

## Testing

Project was developed in TDD. Rspec files live in the `./spec` folder
