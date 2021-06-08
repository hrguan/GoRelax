# GoRelax 
![Home](https://res.cloudinary.com/dql5gkbx4/image/upload/v1623103018/homepage_cskksx.png)
![Places](https://res.cloudinary.com/dql5gkbx4/image/upload/v1623103010/allplaces_zzwinx.png)
![Details](https://res.cloudinary.com/dql5gkbx4/image/upload/v1623103010/detail_bgufgd.png)

GoRelax is a website where registered users can share relaxed places with others. Non-registered users are able to check all the places on this website. Registered users are able to create places and leave reviews! This project was part of Colt Steele's web development course on Udemy.

View Website: https://gorelax.azurewebsites.net/

## Features
* Registered users can create, edit, and remove places.
* Registered users can leave, edit, and remove reviews for places.
* Users can search places on the map.
* Users can check the photos and reviews of places.

## Run Locally
1. Create Cloudinary account
2. Create MongoDB account
3. Create Mapbox account
4. Create a .env file: 
(1)put the name, key, and secret of Cloudinary on the .env file
(2)put Mapbox token on the .env file
(3)put MongoDB connetion string on the .env file
```
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_KEY=
CLOUDINARY_SECRET=
MAPBOX_TOKEN=
PRIMARY_CONNECTION_STRING=
```
5. Install dependencies
```
npm install
```
7. Run MongoDB in one terminal
8. Run node app.js in another terminal
9. Then go to localhost
