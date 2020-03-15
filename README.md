# project8

Problem & Related Work (P1)
Many Northwestern students often find themselves taking classes where they know nobody in the class. Having friends in a class provides a support network for homework help, test studying, or clearing up general questions. If students had a simple, easy, and judgement-free way to connect with other students interested in finding study partners, this would likely lead to an increased feeling of security and increased academic performance.
While there have been attempts at solving this problem, past solutions have failed to address the anxiety aspect of this problem. For example, Piazza can be very useful, as it allows students to anonymously post specific questions for their peers or professors to answer. While allowing for student anonymity does help reduce the anxiety, this only works for single, specific problems, and is unhelpful for studying, as well as late night and last minute problems. Another feature of Piazza is a tool that attempts to match together study partners. However, this tool has the students post about themselves in a public forum, which may dissuade people fearing judgement from using it.
User Research (P2 & P3)
We hoped to learn how students have found study partners previously (if they have), what kind of difficulty students have had with finding people to study with, how they interact with other students in lecture, how/if they were ever able to overcome this problem of not having people to study with, and what kind of classes are more conducive to such an application. We all conducted interviews to try to gather the answers to these questions. 
We learned that users have different needs/preferences for different classes. Also, in person, there is a lot of anxiety talking to unfamiliar classmates due to face-to-face confrontation and fear of rejection. Therefore, although we envision all Northwestern student personas to use our app, we need to make especially appeal to a shy or introverted user so that they feel comfortable. Finally, we wanted to account for scheduling, class goals, and study preferences so less chance of rejection. 

Paper Prototyping (P4)

Overall, our design was received well by users. We made our design pretty simple so that users could follow the sequence of signing up, adding classes, viewing matches and chatting with matches. Despite the general success of our paper prototyping, we did have some usability problems. First, users weren’t sure which fields in the sign up form were optional. Also, they weren’t sure if some of the check box fields were select one or check all that apply. There was some confusion of whether users should type the whole class department or the CAESAR abbreviation. Another issue was that users didn’t know their section numbers and weren’t sure if they could proceed without adding their section. Lastly, we forgot a few essential functionalities for some features such as back buttons on all screens and having a send button for the chat screen. 
First, we added the essential features such as back buttons on all pages and a send button for chat. We also made sure to implement the API for classes so that when users started typing a department or class, it auto-filled so they didn’t have to worry about whether to type the full name or the abbreviation. Finally, we made sure to put stars next to required fields and tried to eliminate any fields that were unnecessary. Overall, paper prototyping significantly helped the design process and the user feedback was extremely valuable. 
High-Fidelity Prototyping (P5, P6, & P7)


Creating a profile: this task involves entering basic personal information such as name, email and password, and also then choosing study preferences.
Data collection form: we used this component to make sign up pages. We included at least five fields and different types of form components such as drop downs and free responses. 
Adding classes: this task allows users to use the API to add the classes in which they are looking for study partners. 
Add classes: this was a component that we got approved which used the API to retrieve department and class information. It allows the user to search departments and class numbers to add to their profile. 
View/filter matches: this task allows users to filter by preferences such as grade and availability. Then, they can look through the matching profiles.
Filter: we used a filter so that users can filter their matches by different study preferences. The filter iterates through the profiles and only displays the ones that match the given criteria. 
Chat: this task lets users communicate with someone who is in their class and matches their study preferences. 
Social interaction: we used a chat screen for our social interaction component. Once a user selects a match, they can chat with them privately. 
Reflection
We managed to create interfaces for creating a user, adding classes, viewing matches and chatting with a match. If we had more time, there are some improvements that we would make to this app. First, we would add even more to the CSS to make the app more professional looking. We would also create a logo to further improve our branding. We would also add an algorithm to order matches based on how well your preferences align, instead of just having a list of all of the users who are enrolled in the classes that you choose.  Overall, we are happy with what we were able to accomplish but there are definitely things that we would add to our app. 
Links
Repository: https://github.com/StudyPartners330/StudyPartnersProgram
Working prototype: https://studypartners330.github.io/StudyPartnersProgram/index.html
Should view with mobile view on Chrome
