## Excluded Directories and Files:

- node_modules/ _commonly excluded directory in node applications_
- sounds/ _excluded due to size_
- sprites/ _excluded due to size_
- game.js _excluded build file_

## Installations Steps:

1. Install dependencies, you will also need python 3.x for http.server
```
npm install
```
2. Run game build step.
```
npm run start
```
  This should create a file `game.js`  
3. Enter following in root folder to serve the development environment.
```
python3 -m http.server
```