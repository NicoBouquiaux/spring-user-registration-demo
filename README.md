# Registration & Login Backend (side-project | WIP)


This is a side-project that I undertook to build a registration & login backend. 
It is not a part of an actual project, but this was interesting for me because I had never tried to work with Spring Boot before.

## Technical Overview

During this development adventure, I managed to implement these technologies into the backend:

- [x] Spring Boot  
- [x] Spring Security
- [x] Java Mail
- [x] Email verification with expiry (using MailDev as the mailserver) --> [check it out](https://github.com/maildev/maildev)

However, this is not a finished project, so for now i'm labeling it as a WIP-project, because I'll be using this demo-form application to extend the functionality of the backend.


## Roadmap

- [ ] Implement JWT-authentication as confirmation of registration
- [ ] Optimize error-handling by implementing constants for error-messages
- [ ] create an engine for templating emails (using Velocity)
- [ ] generating hashed unique identifier for each user (to prevent easy exploitation of the database)  


## Reference Documentation

- [MailDev](https://github.com/maildev/maildev)
