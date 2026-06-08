Privacy Policy for Stop the Bus
Effective Date: June 8, 2026

This Privacy Policy describes how your information is collected, used, and handled when you use the "Stop the Bus" mobile application (the "App").

We believe in data minimization. The App is designed to let you play a multiplayer word game with your friends with the absolute minimum amount of data necessary to make the game function.

1. Information We Collect and How We Use It
We do NOT require, collect, or store Personally Identifiable Information (PII) such as your real name, email address, physical address, or phone number. You do not need to create an account to play the App.

To make the multiplayer gameplay function, we process the following temporary data:

Nicknames: When you join a game, you choose a display name (Nickname). This name is shared with other players in your specific game room. This data is stored temporarily in our active server memory (Redis) and is completely erased shortly after the game room is closed.

Game State Data: The answers you submit during a round are processed by our servers to calculate scores and validate words against our dictionary. This data is ephemeral and is not permanently stored or tied to a historical user profile.

Technical Network Data: Because the App relies on real-time server connections (WebSockets/Socket.io) to sync gameplay between players, our servers temporarily process standard routing information, including your device's IP address. This is strictly used to maintain the active connection during gameplay and is not logged, tracked, or used for analytical profiling.

2. Device Access and Permissions
The App does not request access to your device's camera, microphone, contacts, location (GPS), or photo gallery.

3. Third-Party Services
While we do not collect personal data, the App is built using third-party platforms that may collect standard device and usage data (such as crash logs or performance diagnostics) in accordance with their own privacy policies:

Expo / React Native: The framework used to build the App.

Apple (App Store) & Google (Google Play): The platforms used to distribute the App, which may collect generalized, anonymous usage metrics and crash reports depending on your device's opt-in settings.

4. Data Storage and Security
Your gameplay data is processed on secure servers. Because we utilize an ephemeral data structure (in-memory caching), your room data, nicknames, and scores are automatically purged from our systems when the game session concludes or the room becomes inactive. Our primary database (game.db) is strictly read-only and is only used to retrieve categories and validate words.

5. Children’s Privacy
The App is a family-friendly game. Because we do not collect personally identifiable information, we do not knowingly collect personal data from children under the age of 13 (or the applicable age in your jurisdiction). If you are a parent or guardian and believe your child has provided us with personal information, please contact us so we can take necessary actions.

6. Changes to This Privacy Policy
We may update this Privacy Policy from time to time to reflect changes in our app or legal requirements. We will notify users of any material changes by updating the "Effective Date" at the top of this document.

7. Contact Us
If you have any questions or concerns regarding this Privacy Policy or the data practices of the App, please contact us at:

Email: suhael_akhtar@hotmail.com
Website: https://suhael.github.io/stop-the-bus-public/
