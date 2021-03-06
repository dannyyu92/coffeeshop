Visit the [Coffeeshop](http://doingnow.herokuapp.com/)
======================================================

[![Code Climate](https://codeclimate.com/github/mrap/coffeeshop.png)](https://codeclimate.com/github/mrap/coffeeshop)
[![Build Status](https://travis-ci.org/mrap/coffeeshop.png)](https://travis-ci.org/mrap/coffeeshop)

Doing work alone sucks.  It's much more enjoyable when there are other productive people are around.

Kind of like working at a coffeeshop?  *Exactly* like working in a coffeeshop. (Without the public wifi or the coffee itself.)

### Want to Contribute?

Submit a pull request! Check the **TODO List** for the top priority features and fixes.

  * Please be descriptive with your commit messages.
  * Passing TDD/BDD code is heavily preferred, unless explicitly required.

Please message me if you have any questions!

### TODO List

#### High Priority

  * Prevent user from spamming the chat room excessively.

#### branch `add-feature-requests`

  * Feature Requests can have many comments.

#### Everything Else

  * Usernames should not have whitespace.  URL friendly like `gorgeous-sharpie`.
  * Display the current number of chatters.
    * Example: "You and 5 others are now at the coffeeshop."
    * Make specs in `add-chatters-count` branch pass
  * When a user posts, everyone gets a sound notification.
    * Should be able to be silenced.
  * Add video background of cafe movement
  * Positions new message field near chat messages.
    * New message and message list should be in the same area.

#### Icebox
  * Older versions of Firefox may need an OGG version of the audio.

### Develooment Environment

#### Prereqs

* Ruby version specified in .ruby-version
* Mongodb

#### Starting Development Server

1. `bundle` to ensure you've got everything installed.
2. `bundle exec foreman start --procfile=Procfile.dev` to start the application and the realtime private pub server.
3. You can access the application at http://localhost:5000/.

