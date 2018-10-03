# **NoteAppBackend-firebaseFunctionsHosting**

This is backend for using firebase functions and hosting using firebase admin sdk.

### **Steps for using this project**

- clone project
- run **npm install** to install required dependencies
- create a **firebase project**
- download admin sdk service key and rename is to **'service-key.json'**
- add **service-key.json** file in functions folder
- use **firebase serve --only functions,hosting** to host locally
- use **firebase deploy** for hosting to firebase

**url** give by firebase deploy command is your base url