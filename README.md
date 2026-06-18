## Steps

Steps to set up the frontend and start the backend servers.

---

### Step 1: Install Dependencies

Run this command in the **root directory** of the project to install the required calendar package:

```bash
npm install react-native-calendars@1.1302.0
```

### Step 2: Navigate to the Server Folder
Run this command to move our terminal into the directory where the backend server files are located:
```bash
cd Server
```

### Step 3: Run the Main Server
Execute this command to start the core Express API backend server:
```bash
node server.js
```

### Step 4: Run the WebSocket Server
Open a new, separate terminal window, navigate back into the Server folder and run this command to start the WebSocket server:
```bash
cd Server
node websocketServer.js
```

### Step 5: Launch the Android App
Open another terminal window, make sure its in the root project directory (not inside the Server folder) and run this command to build and launch the application on your Android emulator or physical device:
```bash
npm run android
```
