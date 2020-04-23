# How to use

First we need to install all the dependencies:

```
npm run install
```

Second install appium globally

```
npm install -g appium
```

On the installation folder of your selenium grid server run:

```
java -jar selenium-server-standalone.jar -role hub
```

Finally

- Open a terminal in this project
- Run command:

```
appium --nodeconfig AppiumNode.json --port 4723
```
