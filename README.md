## Photo Upload with React and Multer

`cd api`

`npm install`

`npm run dev`

Go to http://localhost:3001/ and you should see `{ app: "photato" }`

---

`cd web`

`yarn install`

`yarn start`

Go to http://localhost:3000

Open the developer's tool and go to the Network tab.

Click the Upload Photo button and select an image file from your local folders.

See a new POST request being sent to http://localhost:3001/photos and a json response coming back.

To verify that the upload worked, go into the api/uploads directory and you should see a file there.
