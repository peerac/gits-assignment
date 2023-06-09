## Setup Step
### Requirement
- Make sure you have PostgreSQL installed on your machine.
- Create a database to hold the data.

### Running the app
1. Create .env file in root folder with the following content
```env
# DATABASE ENV
DB_HOST=<db host>
DB_USER=<db user>
DB_PASSWORD=<db password>
DB_PORT=<db port>
DB_NAME=<db name>

# Security
JWT_SECRET=<random string combination>
```
2. Open `terminal` or `command prompt`
3. Make sure you are in the root folder and then run `go run main.go`

## Note
### When the app run for the first time:

1. Table for the database will be automatically created. 
2. Some data will also be generated. 
3. A user also automatically generated with the following information. To be used for authentication.
```
 email:     admin@gits.com
 password:  123456
```
4. SQL script for database and POSTMAN collection can be found in folder "misc"
