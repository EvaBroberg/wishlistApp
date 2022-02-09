# FReMP Stack (Flask, ReactJS, MongoDB, Python)

Client: ReactJS<br/>
Rest API: Python, Flask
Server: MongoDB

## Install requirements

When using mac follow these steps otherwise please specify installation depending on your os

1. Install homeBrew: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
2. Install python3: brew install python3
3. Install flask: sudo -H pip3 install flask
4. Install nodeJS: brew install nodej
6. Install NPX: sudo npm install -g npx
7. Install mongoDB: brew tap mongodb/brew, brew install mongodb-community@5.0

# File structure

- wishlist-app holds both frontens and backend of the application
- frontend hold react app
- backend hold all API and DB code

# Backend

1. CD into backend directory
2. Install virtual env: pip3 install virtualenv
3. Create virtual env: virtualenv venv
4. Activate virtual env: source venv/bin/activate
5. Install requirements: pip3 install -r requirements.txt



# Frontend

## Run front end

CD into frontent and run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.
