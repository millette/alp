# Readme

Install it:
```
git clone https://github.com/millette/alp.git
cd alp
npm install
```

Create and edit ```.env``` file with:
```
TEMPLATE_CACHE=false
DBUSER=whatever
DBPW=whatever
DBURL=http://localhost:5984/
```

In production, it would be
```
TEMPLATE_CACHE=true
```

but during development, we want to edit templates without having to restart the server.

DBUSER, DBPW and DBURL aren't currently used but are necessary in the .env file.

Start it:
```
npm start
```
