TO RUN THIS API:
***cmd:  "npm start"
----------------
PACKAGES NEEDED:
----------------
1)express [npm i express]
2)nodemon [npm i --save-devnodemon]
3)morgan [npm i morgan]
4)winston [npm i winston]
5)mongoDB(database connection) [npm i mongodb]
6)bson [npm i bson]
7)http-error [npm i http-error]
8)joi [npm i @hapi/joi]
9)bcryptjs [npm i bcryptjs]
10)json web token [npm i jsonwebtoken]
11)dotenv [npm i dotenv]
12)mail [npm i @sendgrid/mail]
--------------------------------------------------------------------
****before running this API create private.key file****
--------------------------------------------------------------------
private.key will contain:
MONGODB_URI=[url from mongodb server]
PORT=[port no]
SENDGRID_API_KEY=[api key generated from sendgrid]
FROM=[id from sendgrid]