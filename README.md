## Local Setup
1. Install homebrew

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
2. Install Node & Yarn

```
brew install node
brew install yarn
```

3. Install dependencies

```
cd <Project Directory>
yarn
```

4. Install nodemon 

```
npm install nodemon -g
```

5. Run local server

```
nodemon server.js
```

# Push Changes to Repo

```
git status
```

Read the list of files and make sure youre not adding something weird.

```
git commit -am "<What your commit has done>"
git push origin main
```
