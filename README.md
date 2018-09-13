[![Build Status](https://travis-ci.com/dnamsons/Hiking-App.svg?token=sr4VzKTwwG8My2xETy12&branch=master)](https://travis-ci.com/dnamsons/Hiking-App)

# README
* Heroku
https://hiking-appa.herokuapp.com/
* Ruby version
2.5.1
* System dependencies

* Configuration

* Database creation

```
su - postgres
create role hikingapp with createdb login password 'welcome1';
```

* Database initialization
rails db:create

* How to run the test suite
`rspec`
* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* VS Code Extensions

  * Ruby Haml - vayan
  * Haml Lint - aki77
  * Ruby - Peng Lv
  * TODO Highlight - Wayou Liu
  * Live Share - Microsoft
  * scss-lint - Adam Walzer

* VS Code settings.json
```javascript
// indentation
"[haml]": {
    "editor.tabSize": 2,
    "editor.insertSpaces": true
},
"[coffeescript]": {
    "editor.tabSize": 2,
    "editor.insertSpaces": true
},
"[ruby]": {
    "editor.tabSize": 2,
    "editor.insertSpaces": true
},

// Autoformatting
"files.insertFinalNewline": true,
"files.trimFinalNewlines": true,
"files.trimTrailingWhitespace": true,

// Linting & intellisense
"ruby.lint": {
    "rubocop": {
        "lint": true,
        "rails": true
    }
},
"ruby.codeCompletion": "rcodetools",
"ruby.intellisense": "rubyLocate",
```
