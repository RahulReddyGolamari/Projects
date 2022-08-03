## This task is about to create an Online_CertificationDetails_Storing_Form means where a user can add or delete certifications to the website.
Below are the requirements that we have mainly focused on the task to be implement into the website and also the technology that we have used inorder to complete the task based on the given requirements.

                           Requirement Specifications
                   
Business Case 1: Users should be able to register their Certification details in
the Web application and post registration they should be able to search their
details.

Business Case 2: Web Application should use appropriate cost-effective Data
Bases/Storages for implementing the above BC1.

Business Case 3: Valid Users should be able to login to the Web Application,
Invalid Users should get an error message.

Business Case 4: Post registration, Users should get notification over mail.

Use Case 1: To login the Web app, User should be able to register their details.

Use Case 2: Authorized user with official mail id's (use Gmail for this
implementation) should be able to login to the Web Application, Un Authorized
users should get an error message.
(Make use of Token service in the above use case)

Use Case 3: User should be able to store their Certification details in
appropriate Databases/ Storages post successful registration.

User Case 4: Users should be able to search their multiple certifications with
search option in the Web Application.

User Case 5: Appropriate notifications should be sent to registered Mail-ID,
when an addition or deletion of certification is made in the portal.

Function Case 1: User should have Submit/Cancel button at the registration
page.

Function Case 2: Successful registration confirmation should be shown to user
after submitting the registration form.

Function Case 3: Registered Users when recording their Certification details,
parameters to be considered are: Employee Name, CSP) AWS/Azure/GCP),
Certification level, Certification Name, Certification ID (unique), Date of
Certification, Expiry Date of Certification, Validity.


                             Technology Used For Task
                             
Here are the few things to understand about the language and services we have
used for the Task1
                       
Front- End:
                           
HTML is the standard markup language for documents designed to be displayed
in a web browser. It can be assisted by technologies such as Cascading Style
Sheet (CSS) and scripting language such as JavaScript.

CSS stands for Cascading Style Sheets and is used by web pages to help keep
information in the proper display format. The major purpose of css is for
describing the presentation of web pages, inluding colors, layout, and fonts that
allows adapting the presentation to different types of devices, such as large
screens, small screens, or printers.

JS is a scripting programming language that allows you to implement complex
features on web pages. It enables you to create dynamically updating content,
control multimedia, animate images , and pretty much everything else.

                               Back End:
Firebase

1) Firebase Authentication (Authenticating using password and google
accounts).
Firebase Authentication provides backend services, easy-to-use SDKs, and
ready-made UI libraries to authenticate users to your app. It supports
authentication using passwords, phone numbers, popular federated identity
providers like Google, Facebook and Twitter, and more.

2) Cloud function (for sending mails).
cloud Functions is a Google Cloud feature that allows functions to run in the
cloud. In this article I’ll show you the use of Cloud Functions in Firebase, creating
an e-mail sending function that will work through web requests.

3) Cloud Firestore (for storing the certificate details).
Cloud Firestore is a flexible, scalable database for mobile, web, and server
development from Firebase and Google Cloud. Like Firebase Realtime Database,
it keeps your data in sync across client apps through Realtime listeners and
offers offline support for mobile and web so you can build responsive apps that
work regardless of network latency or Internet connectivity. Cloud Firestore also
offers seamless integration with other Firebase and Google Cloud products,
including Cloud Functions.

4) Firebase storage (for storing pdf or jpg format of the certificate).
Cloud Storage for Firebase lets you upload and share user generated content,
such as images and video, which allows you to build rich media content into your
apps. Your data is stored in a Google Cloud Storage bucket — an exabyte scale
object storage solution with high availability and global redundancy. Cloud
Storage for Firebase lets you securely upload these files directly from mobile
devices and web browsers, handling spotty networks with ease.



                                      Hosting the website into the GCP
                                      
                                      
GCP was used to host web app, used services are Compute Engine, Cloud
Storage, Cloud Firestore and Cloud Functions.


