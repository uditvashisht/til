# How to use Postgresql Database in Development in Django on MacOS

1. Download the app from [here](https://postgresapp.com)

2. Configure the path by adding this code :

```
sudo mkdir -p /etc/paths.d &&
echo /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp

```
3. Install postgres on MacOs using `brew install postgres`

4. Open PostgreSQL and start the server.

5. Double click on the database or type `psql` in terminal.



