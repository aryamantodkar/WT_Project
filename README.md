#### `How to run locally?`

```bash
git clone
cd BookStore-App
npm install
cd frontend
npm install
# To run server you must have .env file in root project directory
# see below .env file structure and replace with your values
npm run dev
# project starts

```

#### `.env File Structure`

```bash
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'xxxxx'
PAYPAL_CLIENT_ID = your paypal client id

```
