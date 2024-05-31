# Gym Management Power App
This Power App is designed to facilitate equipment issue tracking.

## Getting Started:
Access Power Apps and sign in with your Microsoft account.
Import .msapp file into Power Apps (App_Phone for phone and App_Tablet for tablet version)
Publish the app to Power Apps for use on mobile devices and tablets.
For detailed instructions on customization and deployment, refer to the documentation provided within the Power App project.

## Technical Documentation:
Check the Documentation folder for technical documentation generated using PowerDocu. The documentation provides insights into the app's structure, functionality, and customization options.

## Features:
Report equipment issues: log equipment problems and track maintenance status.

The app starts with a Login screen

![Login](https://github.com/zepedromvramiao/Portfolio/assets/60276332/07ea605d-6d70-4279-b4e6-e17bcc73d451)

If the username is not valide (i.e. not available in the database), the borderline turns red

![Login_errado](https://github.com/zepedromvramiao/Portfolio/assets/60276332/f0bbbf18-7cb7-47b7-9261-44631dfea7d7)

If the username is valide (i.e. available in the database), the bordeline turns green

![Login_correcto](https://github.com/zepedromvramiao/Portfolio/assets/60276332/2e718360-c904-465c-91c4-67099d6bb5f8)

The user can also recover the passwrod, only if a valide username is inserted

![2 1_RecoverPassword](https://github.com/zepedromvramiao/Portfolio/assets/60276332/fb530e7f-2790-4240-8802-345bf7dbe2fe)

If a valid username and password are inserted, the user is directed to a welcome screen, with the username and current date

![3 1_Welcome](https://github.com/zepedromvramiao/Portfolio/assets/60276332/2c4f1937-d183-4600-9c44-18d0272d68e7)

The user has a navigate panel to select to the screen to which he/she wants to navigate

![4 1_Navigate](https://github.com/zepedromvramiao/Portfolio/assets/60276332/35634f37-7b1c-4669-8fab-34ab50bd5e69)

If a user/ employee wants to register an incident, he/she first needs to select the gym room where the incidents occurs

![5 1_Room](https://github.com/zepedromvramiao/Portfolio/assets/60276332/ae5bc38f-36d3-4818-82ae-fcc766cb9be6)

Once the room is selected, the employee is directed to a new screen where he/she can select the item with an incident. The items availble to take a photograph are only those available in the selected room

![6 1_Item](https://github.com/zepedromvramiao/Portfolio/assets/60276332/902ed190-3410-4cfc-b9cf-6a265abc20b4)

By selecting the camara icon, the user is directed to a new screen where he/she can take a photo to the item in the selected room that has an incident

![7 1_TakePhoto](https://github.com/zepedromvramiao/Portfolio/assets/60276332/b2c48cea-509b-44a8-95f1-5044d59cf7a0)

Once the photo is taken, the user can decide to register it or delete

![8 1_Register](https://github.com/zepedromvramiao/Portfolio/assets/60276332/93d7e765-b3d9-415b-aaf1-71f7eb6a19c0)

The items already registered turns red

![9 1_RegisteredItem](https://github.com/zepedromvramiao/Portfolio/assets/60276332/1bab5ca1-0c8d-4aab-97c6-1e8fbb8fc0bb)

The incidents registered are then available in another screen where the gym manager can check and change the status when the incident is solved. This feature is only availble on the tablet version of the app. It is assumed that the incident is recorded with a phone, while the manager check the incidents with a tablet

![10 1_Insidencias](https://github.com/zepedromvramiao/Portfolio/assets/60276332/8bf1821c-fdb4-4459-9da6-06748bf67e95)



