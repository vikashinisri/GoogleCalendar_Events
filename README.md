

### Google API Key

1. Goto [Google Cloud Platform Console](https://console.cloud.google.com/cloud-resource-manager) and create a new project.
2. Get inside **APIs** section and click **Library** Tab.
3. Under the Library, search for **Google Calendar API** and click **ENABLE**.
4. Under Credentials Tab, click **Create Credentials** button and select API Key on dropdown list.
5. A popup will open, which will give you the **API Key** (GOOGLE_API_KEY).
6. Now Create your web client with following settings. (Give your own desired port number and urls for your app).

### Google Calendar Configuartion

1.  Goto [Google Calendar](https://calendar.google.com "Google Calendar") and create a new calendar.
2.  Under _Access Permissions_ section, just enable the **Make available to public** checkbox. And in the right side dropdown, make sure **See all event details** option is selected.
3.  Grab the **Calendar ID** (CALENDAR_ID) from _Integrate Calendar_ section.
4.  And also add few events to our newly created calendar, so that you will have some data to see while developing.

### Local Setup

1.  Clone the repository using `git clone https://github.com/vikashinisri/GoogleCalendar_Events.git`.
2.  Enter into the project folder and install all dependencies using `npm install`
3.  Now open the file `config.js` inside _src_ folder and update the **GOOGLE_API_KEY** and **CALENDAR_ID** which you have got from above steps.
4.  Now start the app by `npm start`, the project will load in the browser at `http://localhost:8016/`

### Production

Just run the code below, all your build files will be generated inside docs folder.

```
npm run build
```


