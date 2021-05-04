# DeDémos Rails

## What is this?
This is a repository with my demos to showcase how to implement several features, mostly using Ruby on Rails.

[Check also my quick tips](https://github.com/andrerferrer/quickTips).

## The Repositories

### ActiveRecord
- [Rename References](https://github.com/andrerferrer/rename-references-demo#demo) - How to link a DB with more semantic namings.
- [Enum](https://github.com/andrerferrer/enum-demo#goal) - How to handle several status using [`ActiveRecord::Enum`](https://api.rubyonrails.org/v5.2.4.4/classes/ActiveRecord/Enum.html).
- [Nested models]() - How to work with a model and models nested to it.

### ActiveStorage
- [Attach a photo](https://github.com/andrerferrer/basic-photo-demo) - How to attach a file to a model in Rails.
- [Seed photo from local image](https://github.com/andrerferrer/seed-from-local-image-demo#goal) - How to attach a file to a model in Rails with a local picture.
- [Attach PDF](https://github.com/andrerferrer/attach-pdf-demo) - How to implement some PDF attaching to your Rails app.
- [Attach PDF and push to Cloudinary](https://github.com/andrerferrer/attach-pdf-with-cloudinary-demo) - How to implement some PDF attaching to your Rails app and push it to the cloud.

### AJAX in Rails
- [Simple Ajax](https://github.com/andrerferrer/ajax-rails-6-demo) - How to implement Ajax for creating and deleting using Rails 6 with turbolinks.
- [AJAX with Turbolinks](https://github.com/andrerferrer/turbolinks-ajax-demo#goal) - How to add the turbolinks gem to implement AJAX in Rails.
- [AJAX with Rails.ajax](https://github.com/andrerferrer/rails-ajax-demo#goal) - How to implement AJAX in Rails with a Javascript `fetch` using `Rails.ajax`.
- [AJAX with JS.ERB (DELETE)](https://github.com/andrerferrer/respond-to-ajax-demo#goal) - How to implement AJAX in Rails without Turbolinks on a DELETE request.
- [AJAX with JS.ERB and Rails.ajax (UPDATE)](https://github.com/andrerferrer/rails-js-erb-demo#goal) - How to implement AJAX on an UPDATE request with small changes from the previous ones.
- [AJAX with JSON and Rails.ajax (UPDATE)](https://github.com/andrerferrer/rails-json-erb-demo#goal) - How to implement the same AJAX on an UPDATE request using a `JSON` response from the controller.
- [AJAX with STIMULUS (DELETE)](https://github.com/andrerferrer/ajax-with-stimulus-delete-demo#goal) - How to implement AJAX in Rails without Turbolinks on a DELETE request.

### Background Jobs
- [Basics](https://github.com/andrerferrer/background-jobs-demo) - How to implement background jobs in the Model.
- [In the controller with Devise](https://github.com/andrerferrer/background-jobs-devise-demo) - How to implement background jobs in the Controller.

### Chats
- [Create a Chat](https://github.com/andrerferrer/chat-demo#goal) - How to create a chat in Rails 6.
- [Handle CSS on a Chat](https://github.com/andrerferrer/handle-css-on-chat-demo#goal) - How to handle the css in a chat.

### Dates (working with dates in general)
- [Time in Rails](https://github.com/andrerferrer/time-in-rails#goal) - How to work with time (_lato sensu_) in `Rails`.
- [Nice date](https://github.com/andrerferrer/nice-date-demo#goal) - How to implement an easy date picker in rails using the simple form gem.
- [Better date picker](https://github.com/andrerferrer/flatpickr-demo#goal) - How to implement an easy date picker in rails using the flatpickr plugin.
- [Booking Logic](https://github.com/andrerferrer/booking-logic-demo#goal) - How to implement booking logic according to the available dates.
- [Booking Logic Improved](https://github.com/andrerferrer/booking-logic-improved-demo#goal) - How to improve the previous demo with SQL.
- [Display Unavailabilities](https://github.com/andrerferrer/booking-display-unavailabilities-demo#goal) - How to implement the display of the unavailable dates with flatpickr.

### Devise
- [Devise basics](https://github.com/andrerferrer/devise-demo#goal) - How to implement the basics of Devise in a Rails app.
- [Login with Nickname](https://github.com/andrerferrer/username-not-email-devise-demo) - How to implement Devise in a Rails app to log in with something but the email.
- [Omni-authenticator (Facebook and Spotify Login)](https://github.com/andrerferrer/omni-auth-demo#goal) - How to implement Omni Authentication login (with Facebook, Spotify etc) in Rails using the [devise gem](https://github.com/heartcombo/devise).
- [User Edit on Modal](https://github.com/andrerferrer/user-edit-on-modal#goal) - How to implement a modal in another page to edit a User in Rails using the [devise gem](https://github.com/heartcombo/devise).
- [User new and another model](https://github.com/andrerferrer/devise-nested-model-demo#goal) - How to create a new user and a nested model in the same form.

### Geocoder gem
- [Geocoder basics](https://github.com/andrerferrer/geocoder-gem#goal) - How to implement the `geocoder` gem in a model, adding the coordinates according to the address.
- [Geocoder with two attributes](https://github.com/andrerferrer/geocoder-two-attributes#goal) - How to implement the `geocoder` gem in a model, adding the coordinates according to two attributes.
- [Geocoder Map](https://github.com/andrerferrer/geocoder-map#goal) - How to implement a map with `MapBox` and the `geocoder` gem.
- [Geocoder without address no create](https://github.com/andrerferrer/geocoder-without-address-no-create#goal) - How to geocode but with street, city and country as individual columns.
- [Geocoder without address create](https://github.com/andrerferrer/geocoder-without-address-create#goal) - How to geocode but with street, city and country as individual columns. This time, we will make the address be saved in the record after geocoding.
- [Display Map with Cards and Markers](https://github.com/andrerferrer/mapbox-cards-and-markers-demo#goal) - How to display a map with cards and markers (like airbnb).

### Pundit
- [Pundit with Devise](https://github.com/andrerferrer/pundit-demo) - How to implement Authorization with Pundit.
- [Policy on another model etc](https://github.com/andrerferrer/pundit-outsourcing-demo) - How to implement Pundit using another model as the parameter to check the Policy.

### QR Code
- [How to generate a QR code](https://github.com/andrerferrer/qr-code-demo#goal) - How to generate a QR code.
- [How to add a QR code reader to your app](https://github.com/andrerferrer/qr-code-reader-demo#goal) - How to generate a QR code reader.

### Searching and Filtering
- [Search-bar](https://github.com/andrerferrer/search-bar-demo) - How to create a simple searchbar.
- [Basic-filtering](https://github.com/andrerferrer/basic-filter-demo#goal) - How to create a simple filter mechanism.
- [PG Search](https://github.com/andrerferrer/pg-search-demo#goal) - How to do not so simple searching.

### Simple Form For
- [Associated Values](https://github.com/andrerferrer/nested-simple-form-demo) - How to implement a form with associated models.
- [Several models (same type)](https://github.com/andrerferrer/dynamic-form-demo#goal) - How to implement the creation of several models (of the same type) in a single form.
- [Several models (same type) dynamically](https://github.com/andrerferrer/dynamic-form-demo-with-js#goal) - How to implement the creation of several models (of the same type) in a single form dynamically.
- [Children as Checkboxes](https://github.com/andrerferrer/several-children-as-checkbox-demo#goal) - How to create a form for a model with checkboxes for another associated model .
- [Model and Nested Model](https://github.com/andrerferrer/create-model-and-nested-models-demo#goal) - How to create a model and a nested model (or many nested models) in the same form.
- [Keep Context Form](https://github.com/andrerferrer/keep-context-form-demo#goal) - How to make a form take you back to the same position on the page without scrolling after submit.
- [Input Switch Demo](https://github.com/andrerferrer/input-switch-demo#goal) - How to implement a cool and simple switch on a boolean (checkbox) input.
- [File Input Demo](https://github.com/andrerferrer/bootstrap-file-input#goal) - How to implement a cool and simple switch on a file input.
- [Display Uploaded Picture Demo](https://github.com/andrerferrer/display-uploaded-picture-demo#goal) - How to implement a display of the file input.
- [Input toggle all inputs](https://github.com/andrerferrer/select-all-demo#goal) - How to create an input to toggle all other inputs.


### Tags
- [Filter by Tags](https://github.com/andrerferrer/filter-by-tags-demo) - How to filter by tags.
- [Create a model with tags](https://github.com/andrerferrer/model-with-tags-demo#goal) - How to create a model with tags.
- [Create several tags at once](https://github.com/andrerferrer/create-multiple-tags-demo#goal) - How to create several tags at once.

### Testing
- [Simple Testing](https://github.com/andrerferrer/basic-testing-demo/#demo) - How to implement basic testing for features and models.

### *Others
- [Rails Helper](https://github.com/andrerferrer/rails-helper-demo) - How to implement a simple Rails helper.
- [Order by two cols](https://github.com/andrerferrer/order-by-two-attributes-demo#goal) - How to order a given Model using two columns as parameters.
- [Shopping Cart](https://github.com/andrerferrer/shopping-cart-demo#goal) - How to create and use a shopping cart.

### *Only Javascript
- [Select2-change-demo](https://github.com/andrerferrer/select2-change-demo#usage) - How to trigger a change on select2 with JS.

