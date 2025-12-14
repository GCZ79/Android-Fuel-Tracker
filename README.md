# Android-Fuel-Tracker
Mobile app to help users record and monitor their vehicle's fuel usage

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

### The goal of this project was to design and develop a functional mobile application that follows mobile development best practices while prioritizing user-centered design. The app was created to address a practical user need: tracking fuel usage and efficiency over time in a simple, intuitive way. Users are able to create an account, configure personal preferences such as currency, preferred fuel brands, and MPG alert thresholds, and then log fuel refills or import historical data via CSV. The overall requirement was not only to build a working app, but to demonstrate thoughtful planning, usability, and maintainable code.
--------------------------------
## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

<img width="180" height="360" alt="01 Login" src="https://github.com/user-attachments/assets/30860501-f936-4ea6-8625-c2c651891891" />
<img width="180" height="360" alt="02 Settings" src="https://github.com/user-attachments/assets/f5ec3f5d-e5af-4c38-b598-6550c2efb7f7" />
<img width="180" height="360" alt="03 Fuel Refill" src="https://github.com/user-attachments/assets/b60ecb60-5e93-4ea6-82d8-f3a4f968a540" />
<img width="180" height="360" alt="04 Database" src="https://github.com/user-attachments/assets/42f4b0bb-c6a1-4fe4-ad53-5c7ba5db0f1b" />
<img width="180" height="360" alt="05 Statistics" src="https://github.com/user-attachments/assets/7b1c0eea-a2bf-42c6-a86b-939c5800dd32" />

### The app has been designed to offer a seamless user experience, and all the pages and various elements have been built with this in mind. All users are initially required to register a username and password to enable session persistence and data saving. From the "Login/Registration" page, first-time users are redirected to the "Preferences" page, where they can pick their favorite gas station brands, set their currency, and decide whether to activate SMS alerts for MPG values below or above a user-defined threshold. To reduce the needed steps to get to the core of the app, any subsequent login will redirect returning users straight to the "Fuel Refill" page, where they can quickly save the data of their fuel refill sessions. A "Database" page allows them to Create, Read, Update, and Delete their records, and even to upload historical refill data in CSV format. Finally, a "Statistics" page provides insights into the collected data, organizing and showing it with charts and numerical values. To optimize the available screen space, the various pages can be navigated through the small menu button in the top-right corner. While minimal, the menu button offers a simple and effective navigation.
### I believe that all the above decisions show clearly how user experience was central in the design of the app, and that the simple yet effective interface should allow any user a smooth and error-free experience.
--------------------------------
## How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?

### I started building my app following a top-down, iterative development approach, beginning with its skeleton. I had clear ideas regarding the number of pages/fragments that would have constituted its structures, so I used my prototype as a blueprint to create them right away. I coded a way to navigate among them, then I added to those pages their various text fields, buttons, and images. I styled elements as soon as I placed them, leaving the exact adjustments in matters of size and colors' shades for last. Once I had recreated on screen my prototype, I started adding functionalities, breaking the various blocks of the pages into smaller components to separate concerns and make testing and reusability easier. During this phase, I added detailed commenting to my code to keep things organized and clear, enriching it further in a second moment when performing a final review of the whole code. My strategy of defining UI elements cleanly and implementing logic in a way that supported an easy adaptation, for example, from using mock data to implement an actual database, can be transferred directly to future projects, making scalability, debugging, and maintainability easier to achieve.
--------------------------------
## How did you test to ensure your code was functional? Why is this process important, and what did it reveal?

### Testing for usability and security played a fundamental role in making sure that the app functioned as intended. I used both virtual and physical devices to try to recreate any actions users could perform, from rotating the screen during a refill session to entering wrong credentials, invalid numerical input, or even going back or to the home screen with the phone buttons. I also validated and sanitized user inputs, making sure to handle all the edge cases to help me identify logical errors and UI inconsistencies. Testing was very important because it allowed me to confirm that the app worked as intended, and showed me where to put safeguards to prevent any negative outcomes like crashes, accepting wrong data, or circumventing the security of the data and sessions.
--------------------------------
## Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?

### text
--------------------------------
## In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

### text
--------------------------------
