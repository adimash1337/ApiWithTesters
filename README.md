# ApiWithTesters

To launch the app you must clone repo and install all dependencies, also you need to create db and user to get access to it:
- $ createdb dbname
- #psql
- #ALTER USER username WITH ENCRYPTED PASSWORD 'password';
- #\q

The next is the edit the .env file.

to test all the testers:
- $ cd tests
- $ go test -v ./...
