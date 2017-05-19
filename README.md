# AndroidBeginners_PedroMarco
This app allows to manage study flashcards (questions and answers), where the use can add/delete flashcards and store them in diferent folders. Includes a widget that displays random questions for the selected folder. Also the user can set up study reminders (notifications) with the desired frequency.

HOW TO INSTALL:
- Just download the rar file, extract it and open the project folder with Android Studio. The app shold work in any API after 15 (included) except for the study reminders that are using JobScheduler which is only available after API 21 (LOLLIPOP).

HOW TO USE THE APP:
- Once the app is installed and open, a example folder with some example flashcards are displayed, read them to ensure you understand the basics of the app. After that, you can create new folder in the navigation drawer menu opening formt he left of the screen. Then you can add flashcards with the action button displayed in the bottom right. When inside a question, you can flip from question to answer and backwards by pressing the action button. You can also remove flashcards/folders in the options menu located in the top rigth while the folder/question is open. 
- To set up study reminders (notifications) open the navigation drawer and select "Settings" in the header, inside you can set the desired frequency for the notifications anfter activating it. 
- Finally, the app includes a widget that displays random questions for the selected folder. To set a folder for the widget, open the app and open the options menu (top right) while the desired folder is open and select "Set folder in widget". The widget updates automatically every hour, but the user can interact with it to display next question qhenever he wants.
