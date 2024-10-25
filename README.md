# IT-230-Software-Development

### Briefly summarize the requirements and goals of the application you developed. What user needs was this application designed to address?

 This application allows a user to register for courses and view which courses they have already registered for. The requirements were that it must allow the user to select a course from a dropdown list and click a button to register. The application must respond to a button press by validating the choice and either displaying an error message or adding the course's name to a list of registered courses. The application needed to ensure the user could not register for more than 9 credit hours or register for the same course twice.


### What did you do particularly well in developing this application?

 I think my code for button_Click() was very neat and straightforward. It is easy to understand and, in my opinion, as efficient as possible.


### Compare and contrast the Console and WPF application designs. What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

 The Console version of the application was much more tedious for users, as they have to confirm whether they want to register for another program after every registration attempt. Several times during testing I absentmindedly put something other than 'Y' as my input and the program would close, which was frustrating. The WPF application is much more user-friendly as it is visually easier to understand and runs until the user chooses to close it. Another benefit of the WPF application is that it does not take text input from the user, allowing for better control of the user's input and greater protection against input-related errors.
 The UI for both applications may look different, but contain the same basic components: a list of courses to choose from, space to input a course choice, and an updating display with all currently registered courses. Both applications also feature similar feedback for the user when registration has been successful or an error occurred. 
 Both applications' UI supported users by providing clear instructions on how to register and giving feedback when the user selection was invalid. Users remain updated which courses they have registered for and, in the WPF application, how many credit hours they have remaining.


### How did you approach the process of debugging and coding your application? What techniques or strategies did you use? How could you use those techniques or strategies in the future? 

 The main tool that helped me through the debugging process was Visual Studio. It alerted me to typos and errors, and even helped me write my code faster with its suggestions. I also tested my program by running it and attempting several different inputs to ensure it responded properly. Lucky for me, it had few problems.
 In the future, I know I will be using Visual Studio much more. Its debugging tools are probably my favorite of all the IDEs I've tried, and its layout is easy to navigate.
 One technique I used that I really liked was string interpolation. It's one of those things that just didn't click with me no matter how much I saw it in other coursework. I suppose what I really needed was to experiment with it a little more. Now I am very comfortable with how it works and will be using it much more frequently in my programs!


### Where did you have to be innovative to overcome a challenge in the full application development process?

If I'm being honest, I do not think there was a time during the development process that I needed to be innovative to overcome a challenge. It all went pretty smoothly and the only problems I encountered were basic syntax errors.
