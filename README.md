# ![GA Logo](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Auth Research Lab

---

Authentication is a complex and exciting topic that involves using many of the concepts we've already studied as well as several new ideas. 

An authentication system allows the registration / signup of new users and allows those users to sign in. It has to be able to identify each user and keep their information private and secure.

Being able to develop secure user login systems is in fact a whole career and life path in and of itself, but understanding the broad concepts of **Auth** is critically import for all developers. 

Describing auth flow and understanding key terms are very common **interview questions** for junior developers, so lets take some time to research and understand auth and the related concepts.

## Setup

Fork and clone this repository and answer the questions as you research directly in the README. You do not have to pull request and submit this lab, but you will want to have it on hand for reference in the future. 

## Auth Concepts Worksheet

#### Define the following

1. *Authentication*
2. *Authorization*
3. Explain how *authentication* and *authorization* are related but distinct concepts.
5. *Sessions vs Token based auth*
6. *json web token (also know as a jwt)*
7. *Encoding, encryption and hashing* along with the uses for and differences between the three
8. *oAuth* (pronounced oh-Auth)

#### Personal Answers
1.  The process of identifying and verifying a person or system. (the who)
2.  A process by which a server determines if the client has permission to use a resource or file. (the what)
3.  Authentication is determining who you are. Authorization is determining what you are allowed to do.
5.  Tokens are managed on the client. Sessions are managed on the server.
6.  When clients make an initial request, sending authentication data, the server may validate it. Instead of saving the user data, it send back a token. it is required that hte client send back that jwt token with each new request. 
7.  Encoding is easily reversable and used to ensure integrity and usability of data. It is not used to protext  or secure data because it is easy to reverse.
7.  Encryption involves the process of transforming data so that it is unreadable by anyone who does not have a decryption key. (disguise)
7.  Hashing cannot be reverse or decrypted. It is most often used to check two hashes for exact similarity. Recommended authentication process. salted passwords.
8.  Provides access to small amount of data from oauth sites to determine user credentials


#### Class answers
1. 

#### Explore and then describe the following npm packages:

1. [bcrypt](https://www.npmjs.com/package/bcrypt)
2. [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
3. [passport](https://www.npmjs.com/package/passport)
    * also describe what a *strategy* is in the context of this npm package


#### Personal Answers


#### Class answers
1. an npm package that provides a hashing function
2. an npm package that allows the creation of json web tokens. 
3. all in one package for authentication

---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
