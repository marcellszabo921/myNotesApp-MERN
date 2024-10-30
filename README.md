# Notes App
Ez a Notes App egy full-stack webalkalmazás, amely lehetővé teszi a felhasználók számára jegyzetek létrehozását, 
szerkesztését és kezelését. Az alkalmazás Node.js backenddel és React frontenddel rendelkezik.
## Telepítés
Klónozza le a repository-t: 
```
git clone https://github.com/marcellszabo921/myNotesApp-MERN
cd notes-app
```

Telepítse a backend függőségeket:
```
cd backend
npm install
```

Telepítse a frontend függőségeket:
```
cd ../frontend/notes-app
npm install
```

## Konfiguráció
A backend mappában lévő .env fájlt módosítsa: 
```
ACCESS_TOKEN_SECRET="your_secret_key_here"
```
Cserélje ki a your_secret_key_here részt egy biztonságos, véletlenszerű karakterlánccal.

A backend/config.json fájlban állítsa be a MongoDB kapcsolati adatait:
```
{
  "connectionString": "your_mongodb_string"
}
```
## Az alkalmazás indítása:
Indítsa el a backend szervert:
```
cd backend
npm start
```
Új terminál ablakban indítsa el a frontend fejlesztői szervert:
```
cd frontend/notes-app
npm run dev
```
