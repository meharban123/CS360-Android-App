# CS360-Android-App

## Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The app was designed to allow users to manage inventory items (as a chosen example) with the capability of user authentication. The primary goals were:

User login and signup functionality.
CRUD operations on inventory items.
SMS notifications based on specific triggers.
The app addressed the need for users to securely manage and monitor their inventory, and get notified (via SMS) when certain conditions are met.

## What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The Key Screens were:

Login/Signup screen: For user authentication.

Main Inventory screen: To display, add, update, or delete items.
The UI was designed to be straightforward and intuitive, keeping the principle of least surprise in mind. Actions were kept simple with clearly labeled buttons. The success of the design hinges on its simplicity and directness, making the user's journey through the app smooth and logical.

## How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

The coding process was approached in a modular and iterative manner. Each functionality (authentication, CRUD operations, SMS notifications) was developed in isolation before integrating them. Techniques used included:

Modularization: Breaking down tasks into smaller, more manageable chunks.

Iterative Development: Building and testing each module one at a time.

These strategies are universally applicable and can be used in future projects to ensure code clarity, ease of debugging, and systematic progression.

## How did you test to ensure your code was functional? Why is this process important and what did it reveal?

Testing was conducted using the Android Emulator in Android Studio. Each module was tested after its development to ensure functionality. The importance of this process is manifold:

Identify and rectify bugs early in the development process.

Ensure the app behaves as expected across different scenarios.

The testing revealed the app's behavior under various conditions and ensured that edge cases were handled appropriately.

## Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

One of the challenges faced was handling SMS permissions. To address this, we innovated by ensuring the app remained functional even if the user denied SMS permissions, thus enhancing user experience and trust.

## In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

The user authentication module, which involved creating a secure login/signup mechanism and integrating it with a SQLite database, was particularly significant. It demonstrated a proficient understanding of user data handling, database operations, and security considerations.
