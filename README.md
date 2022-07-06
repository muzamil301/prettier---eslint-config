# Setting up eslinting and Prettier (code formatting and better static testing)  
**Copy config files palced in repo in your project's root directory then follow given beelow steps**
## 1-Dev Dependencies 

Add these packges to **devDependencies** sesction in **package,json** file 
```
"devDependencies": {
    "@typescript-eslint/eslint-plugin": "^5.30.0",
    "@typescript-eslint/parser": "^5.30.0",
    "eslint": "^8.18.0",
    "eslint-config-prettier": "^8.5.0",
    "eslint-plugin-prettier": "^4.1.0",
    "eslint-plugin-react": "^7.30.1",
    "prettier": "2.7.1"
  }
```

**Then Run **
```npm install```
## Npm Scripts
Add following comamnds in scripts section of **package.json** file
```
    "lint": "eslint ./ --ext .ts,.tsx .",
    "lint:fix": "npm run lint -- --fix",
    "format:check": "prettier --check .",
    "format:fix": "prettier --write .",
```
**Thanks**
