                              #Authentication-Security
Why authentication ?
Too log-in system and our data keep safetly on system and db. We use cryptography such as hashing,salting,authorisation etc.
**Level 1 Security ** : Creating email&pass and storing it on mongoDb via Mongoose.
**Level2 Security** : Encrypte database passwords via npm module and encrypt keys via *dotenv* npm package.
**Level 3 Security** : Hashing db passwords via *md5* npm package.
  Hashing is the process of converting a given key into another value. A hash function is used to generate the new value according to a mathematical algorithm.
**Level 4 Security** : Salting and hashing passwords via bcrypt.
**Level 5 Security ** : Cookies & Sessions via Passport.js. When you entered a website they track you down. For example a basic e-commerce website,
you added your basket something and you forgot to buy them. When you came back, you will see that it still wait for your. That's a basic cookies and session example.
**Level 6 Security** : Third party Authorisation via OAUTH2.0.
By using OAuth, we are able to access pieces of information on these third party websites such as their friends,emails,or their contact on Gmail.For instance entering an app via 
Facebook,gmail or github.

Requirements: 
```
npm install express ejs body-parser mongoose express-session passport passport-local-mongoose
```

I am familiar with authentication and data encryption,authorisation. I am familiar with passport.js and passport-local-mongoose.
