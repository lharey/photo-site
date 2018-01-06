# What I want to achieve with this project

A Website for managing and dislaying my photographs

## Server - Perl API

GET /photos

GET /photo/album/:name

GET /photo/:id

PUT /photo/:id/metadata

POST /photo

## Client - React JS

Pages:
* Main page - 1 image and underneath a line of the latest 4 images uploaded
  * Menu items - Upload, Albums, About
* Upload - drag and drop multiple
* Portfolio - grid of 5 images, All, Unclassified, Favourites, Albums, Projects, 
  * Click one of the porfolio image, brings up paged list of photo thumbnails with view and edit icons
  * Click a photo - brings up lighbox view
  * Click Edit - brings up photo with editable metadata

Reading:
* https://blog.alexdevero.com/learn-react-practice-create-gallery/
* https://github.com/neptunian/react-photo-gallery

## Database - sqlite

### Tables

Images:
* id
* file path

Metadata:
* image_id
* title
* category
* date
* apertue
* shutterspeed
* iso
* favourite
* album

Albums:
* name
* description
* date

