# Resturent-menu-Screeens-manager

- Manage different menu screens for the different resturents 
- user gets the list of resutrents from the firestore cloud database
- user can go to specific resutrent and see previously uploaded images on the screens
- user can upload new images to the screens. which is stored in the firebase storage. 
- user gets the uploaded image image url.


## Required :

1. Firebase cloud database linked to the site.
2. Firebase Storage linked to the site.
3. Firebase should have public access to read and write data to firebase.


## Data structure in firebase cloud:

Data collection : GobieStore

Data Document :  (string) ("SID"+ random) 

SID1213 :  {

      id :"SID2123" (string)
      name : "KFC"  
      screen1 : "IMG_0003.JPEG" (string)
      screen2 : "UID1418.jpg" (string)
      screen3 : "UID1212.jpg" (string)
      }
      
## Image storage :

images/imagename

ie. 'images/'+ Imagename

  
  
