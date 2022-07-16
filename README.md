# Action Cable Examples

A collection of examples showcasing the capabilities of Action Cable.

## Starting the servers

1. Run `docker-compose up -d` to start the Redis container
2. Run `./bin/setup`
3. Run `./bin/cable`
4. Open up a separate terminal and run: `./bin/rails server`
5. One more terminal to run redis server: `redis-server`
6. Visit `http://localhost:3000`

## Live comments example

1. Open two browsers with separate cookie spaces (like a regular session and an incognito session). 
2. Login as different people in each browser. 
3. Go to the same message.
4. Add comments in either browser and see them appear real-time on the counterpart screen.

![Live comments example](/example.gif?raw=true "Live comments example")
