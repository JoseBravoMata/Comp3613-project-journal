# Comp3613-project-journal

## Week 3
### 1. I helped work on the project initiation document, updating the description and project objectives. I had suggested the idea for the covid news and educational material provider. I added some extra lines to the project description and objectives and fixed some grammatical errors.

## Week 4
### 1. I helped work on project requirements, specifying implementations for contacting tutors and handling help desk services. I specified that tutors should have a page which displays their information.
### 2. I was declared the product owner.

## Week 5
### 1. I set up the github site and firebase site for the project(2 hrs)
### 2. 15/10/2020 I elected to do the use case and sequence diagrams(suggested by Dharian).
### 3. 16/10/2020- I worked on creating use case diagrams(6 hrs).
### 4. 17/10/2020- I worked on creating use cases.

## Week 6
### 1. 19/10/2020- I finished working on the use cases. I created the diagrams for login related functions, handling documents, help desk/tutor services and the covid nees functions.(2 1/2hrs)
### 2. 19/10/2020- I finished working on use case diagrams.
### 3. 20/10/2020- I finished work on the sequence diagram for the post covid news case.(1hr).

## Week 7
### 1. 28/10/2020- I started to work on the product backlog(user stories)(<1hr).
### 2. 30/10/2020- I worked on the product backlog(user stores)(<1hr).

## Week 8
### 1. 03/11/2020- I started work on the login page and I commited the login page to github. I applied the firebase scripts for starting firebase and also for authentication. I reused code from another project outside UWI for firebase functions.(1hr)
### 2. 04/11/2020- I integrated Jasmine(javascript tesing framework) for testing and tested the functions (createUser() and signIn()) from authentication.js. I implemented tests for registerUser and registerTutor and wrote up the functions. I integrated the login to the Home.html page that Dharian made. I uploaded version(0.0.2) of the app to the github(this version contains the log in). I updated the Trello board that firebase was integrated. (6 hrs total)
### 3. 05/11/2020- I integrated the firebase database.I applied tests for and added the functions setUpUserDoc and setUpTutorDoc to the register page, I fixed and refactored all code for the register page until all tests had a pass. I partially fixed the UI for the log in and register pages. I linked the Home.html page to the index and register pages. After everything was finished I uploaded the app as the version 0.0.2 to the github. I updated thd Trello board to show the login and register pages were completed for this sprint.(4 hrs)

## Week 9
### 1. 10/11/2020- I worked on the gantt chart and burndown chart for the 2nd sprint. I added all the current work to the gantt chart and to the burndown chart. I noticed that we may be proceeding at a good pace for the project based on the burndown chart. (4hrs)
### 2. 11/11/2020- I completed the gantt chart fot sprint one and worked on the burndown chsrts for sprints 1 and 2. I completed the gantt chart for sprint two and the burndown chart for sprint two. I posted the charts in the whatsapp group. I compiled the work from sprint 1 into the gantt chart for sprint two to get the total view.(4 hrs)
### 3. 12/11/2020- I edited the sprint one gantt chart and completed the sprint one burndown chart. I submitted both charts to the sprint 1 Trello board and the sprint 2 charts to the sprint 2 Trello board.
### 4. 13/11/2020- I created the body and tests(using jasmine) for the functions getUser(), getUserDoc() and checkIfTutor(). I also created the body for enableTutorOptions() but left it for Darren to complete. I created the branch for version 0.0.3 of the app on github. I ran tests on all functions until they had all passed. (2 hrs)

## Week 10
### 1. 16/11/2020- I worked on fixing the tests from jasmine(I made the tests correctly run randomized). I added getUserCallback() which now retrieves a user via observer in order to fix an error with enableTutorOptions(). Two tests( for setUpUserDoc & setUpTutorDoc) still give issues but the functions work when ran from the web page. I added the relevant sources to the service worker and merged the work Dharian and I had done. I uploaded the app as version-0.3.4-Jose to Github.(5hrs)
### 2. 17/11/2020- I managed to fix the tests for the previously mentioned functions. I also added a test for getUserCallback() which passed.I then worked on adding the functionality to retrieve tutors from the firebase database and display them on the tutor page. I created tests for and implemented the functions getTutors(), createTutor(), addTutors() and storeName(). After all tests passed I uploaded the app as version-0.3.5-Jose to Github.I also fixed the pointers for the tutor page's book tutor buttons. (6 hrs)
### 3. 18/11/2020- I commented on every peice of code contained in the javascript file of the app. I updated the firebase scripts to version-8.0.2. I uploaded the app to Github as version-0.3.5-Jose.

## Week 11
### 1. 23/11/2020- I added the github repository to Travis CI(continous integration) on behalf of Dharian and deleted the license for the repository.
### 2. 24/11/2020- I started work on the educational metarials page. I copied the tutorpage to reuse it for making the page. I added the list of educational material level options(primsry, seconday & tertiary) to the ui using materialize and fixed the links of the other pages to go to the educational material page.(1hr)
### 3. 26/11/2020- I added tests and implemented the functions showMaterial(), back(), createMaterialLink() and getMaterial(). I modified the ui stylings(using materialize) of the header for the material list, I ran all tests and they all passed. I found free educational material online to link to using the educational material page. I set up the collection for educational material on firebase and also stored some material in fieebase storage. Once I had finished I pushed all the files to branch "version-0.4.3-Jose" of the Github repository. I also had an issue where I accidently deleted all the work I had done for this version before I could upload, but I was able to rewrite the essential changes. 
### 4. 27/11/2020- I fixed the links of all the html pages to go to the educational materials page and updated the functionality to sign out by only displaying the option when the user is signed in. I fixed and merged the code(ViewBookings page along with its javascript file and tests) taken from my teammates' versions of the app and also applied the changes made to the home page. The changes applied also included updates to the Bookings page and its javascript file. I ran the tests cases for the app and created a test for signout(). I also changed the tests cases for the register page javascript to remove unnecessary code. I ran all tests and as all passed, I uploaded the app as version-0.4.4 to Github.(3hrs)







