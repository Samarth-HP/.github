# Samarth - Himachal Pradesh
Samarth - Himachal Pradesh is a program to facilitate education in the state of Himachal Pradesh, India in a decentralized manner. Decentralization is key to empower teacher and state officials at various levels i.e, state, district, block and cluster. 

## Technical Elements
* e-Samwad Android Application
* Shiksha Saathi Android Application
* Admin Management console
* BE services

### e-Samwad Android Application
The [e-Samwad Android Application](https://play.google.com/store/apps/details?id=com.himachal.android.eSamwad) is a teacher facing intervention. Which helps teacher in
* Student Management (Add, Remove, Promote)
* Recurring school activities (Attendance Marking, Mark Collection, Homework Sharing
* Communication with Parents (Meeting Announcements, Results Sharing, Holiday announcements)
* Outcome based learning (Nipun lakshya abhyaas)

The application is predominantly written in Java with newer elements in Kotlin. The app extensively uses a modified version of ODK to collect data. The app uses Hasura for easier access and storage of some of our data elements. The app talks to our backend service to send the updates to parents. 

Repository: https://github.com/Samarth-HP/eSamwad-app

### Shiksha Saathi Android Application
The [Shiksha Saathi Android Application](https://play.google.com/store/apps/details?id=com.samagra.shikshaSaathi) is a mentor facing intervention. At its core its a data collection application to facilitate the state to track school needs and check progress on various state mandates.

The application is predominantly written in Java with newer elements in Kotlin. The app extensively uses a modified version of ODK to collect data. The app uses Hasura for easier access and storage of some of our data elements.

Repository: https://github.com/Samarth-HP/shiksha-saathi-app

### Admin Management console
The Samarth Admin Management console is an administration tool for state education officials at various levels. The core features are as follows:
* User Management of students, teachers and mentors(create, edit, delete, approve, transfer)
* Entity Management of school and locations( Add, update, delete)
* Work flow management (Configure and Assessments)

Repository: https://github.com/Samarth-HP/admin-ts

### BE services
TBA

Repository: https://github.com/Samarth-HP/esamwad-backend
