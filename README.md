# sos-fixit-rails-api

## Quick start

Please note: you will need to install ruby 2.2.3 in order to run the app. Following this, you will need to reinstall bundler and all the gems. To do this, run:

```bash
rvm install ruby-2.2.3
rvm use 2.2.3
gem install bundler
bundle
```

Then, you can run tests by running:

```bash
rake db:create
rake db:migrate RAILS_ENV=test
rspec
```

## User Stories:

### User Story 1:
```
As a user,
so that I can make myself available to help,
I would like to sign up and make a profile.
```

### User Story 2:
```
As a user,
So that other users can see what I can offer them,
I would like to list the skills on my profile.
```

### User Story 3:
```
As a user,
So that I can find people near me to help with a current issue,
I would like to be able to search by skill.
```

### User Story 4:
```
As a user,
So that I can safely leave the web app,
I would like to be able to sign out.
```

---

## Bonus User Stories

### User Story 5:
```
As a user,
So that I can get in touch with other users to use their skills,
I would like to view other users profiles and view their contact details.
```

### User Story 6:
```
As a user,
So that future users can see the quality of services provided,
I would like to be able to leave reviews for other users.
```
