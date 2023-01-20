# Samarth - Himachal Pradesh
Samarth - Himachal Pradesh is a program to make delivery of education easier and better in the state of Himachal Pradesh, India.

## Technical Elements
* e-Samwaad Android Application
* Shiksha Saathi Android Application
* Samarth Admin console
* BE services

### e-Samwaad Android Application
The [e-Samwaad Android Application](https://play.google.com/store/apps/details?id=com.himachal.android.eSamwad) makes it easier for teachers to manage their students. It contains the following features: 
* Student registration
* Student promotion & release
* Sending updates to parents of students via SMS.
* Undertaking student assessments
* etc..

The application is predominently written in Java with newer elements in Kotlin. The app extensively uses a modified version of ODK to collect data. The app uses Hasura for easier access and storage of some of our data elements. The app talks to our backend service to send the updates to parents. 

Repository: https://github.com/Samarth-HP/eSamwad-app

### Shiksha Saathi Android Application
The [Shiksha Saathi Android Application](https://play.google.com/store/apps/details?id=com.samagra.shikshaSaathi) makes it easier for mentors to audit schools under their purview. 

The application is predominently written in Java with newer elements in Kotlin. The app extensively uses a modified version of ODK to collect data. The app uses Hasura for easier access and storage of some of our data elements.

Repository: https://github.com/Samarth-HP/shiksha-saathi-app

### Samarth Admin console
The Samarth Admin console makes it easier for stakeholders in the education department to manage e-Samwaad & Shiksha Saathi Android applications. With the console, admins can:
* Add users to both the apps.
* Map users to schools.
* Map schools to districts, blocks and clusters.
* Map mentors to schools
* Manage other aspects of the apps. 

Repository: https://github.com/Samarth-HP/admin-ts

### BE services
TBA

Repository: https://github.com/Samarth-HP/esamwad-backend