# CampZone


![Image 1](https://github.com/arnabde319/CampZone/blob/main/screenshots/image1.png)

![Image 2](https://github.com/arnabde319/CampZone/blob/main/screenshots/image2.png)

![Image 3](https://github.com/arnabde319/CampZone/blob/main/screenshots/image3.png)

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account.  

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove campgrounds
* Users can review campgrounds once, and edit or remove their review
* Map shows the location of the campground
* A cluster map shows all the campgrounds present all over the world

## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an cloudinary key and cloudinary code
3. Create a google developer account and get a app id and app secret code
4. Create a mapbox account and get an access token
```
git clone https://github.com/arnabde319/CampZone.git
cd CampZone
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
CLOUDINARY_CLOUD_NAME=<name>
CLOUDINARY_KEY=<key>
CLOUDINARY_SECRET=<secret>
MAPBOX_TOKEN=<token>
APP_ID=<id>
APP_SECRET=<secret>
DB_URL=<url>
SECRET=<secret>
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

Check [MapBox docs](https://docs.mapbox.com/) for configuring the cluster map.


