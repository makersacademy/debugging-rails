# sos-fixit-rails-api

## Quick start

```bash
rake db:create
rake db:migrate RAILS_ENV=test
rspec
```

##Overview of Application
This application is to enable users with issues to be able to link with those
can help solve those same issues. e.g. As a user with an electrical problem, I
can find an expert on the platform who has ratings, whom I can request to fix my
issue.


##Job Spec:

Each job has the following properties:
```
Name
Recipient id -> has one user (User with current issue)
Fixer id -> has one user (User able to help with issue)
Created at
Updated at
Active -> default: false (Job is active)
Review (Review of fixer)
Rating (Rating of fixer)
Is active -> default: false (Fixer is working on job)
Recipient username
Fixer username
```


## User Stories:

###User Story 1:
```
As a helpful individual,
so that I can make myself available to help,
I would like to sign up and make a profile.
```

###User Story 2:
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

### User Story 7:
```
As a user,
So that I can find help with a current issue,
I can post a job
```
