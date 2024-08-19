## MyBible - Flutter Application

MyBible is a Flutter application designed to for users to access bible verses,get daily gospel music and recommendations and also verses of the day.

### Getting Started

To get started with the MyBible app, follow the instructions below to set up your environment and run the application.

### Prerequisites

Before you can run the app, ensure you have the following installed on your machine:

- [Flutter](https://flutter.dev/docs/get-started/install) SDK
- [Dart](https://dart.dev/get-dart)
- A suitable code editor (e.g., [Visual Studio Code](https://code.visualstudio.com/))

### Setting Up the Environment

To securely store sensitive information like your `CLIENTID` and `CLIENTSECRET`, you'll need to create an environment file in the project's main folder.

1. **Create the Environment File:**

   In the root directory of the project, create a file named `secret.env`.

   ```bash
   touch secret.env
   
2. **Add the following lines to `secret.env`:**

   ```env
   CLIENTID = your-spotify-client-id
   CLIENTSECRET = your-spotify-client-secret
   
Replace your-spotify-client-id and your-spotify-client-secret with your actual credentials from the Spotify API.
### Running the Application

With the environment set up, you can now run the application:

1. **Ensure all dependencies are installed:**

   ```bash
   flutter pub get
   flutter run
