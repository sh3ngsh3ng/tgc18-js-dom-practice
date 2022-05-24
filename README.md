# JavaScript DOM Execrises

## 1. Getting Started

You can use either repl.it, Gitpod or Visual Studio Code for this execrise. Fork
this Github repo. Once done, at the terminal, type in:

```
yarn install
yarn add jest
yarn add jest-environment-jsdom
```

## 2. Doing the questions

Each question is in a folder by itself. The question description and what's expected
will be in the `readme.md` file. Each question will have an `index.html` file
and `script.js` file. Follow the instructions carefully in the `readme.md` file. 
**Do not change** the `script.js` file unnecessarily (there are special code at the
end of the `script.js` file, don't touch it!)

## 3. Testing the question

You can check if you done the question correctly by typing the following in the
terminal:

```
npm test <folder name>
```

For example, if you wish to test if you get q1 correct, you will type in

```
npm test q1
```

If you just want to check all your answers, just type in the terminal:

```
npm test
```

# 4. Getting new questions

To get new questions, open a **NEW** terminal and type in the terminal:

```
git fetch upstream
git merge upstream/main
```

If there are conflicts in `script.js` files, just use your original copies.
