# Guide Guides Template
Importing Guru Guides template into Contentful for users to add their own guidelines to the Guru Guides plugin.


**Login via the terminal**
- Open the Terminal and paste the command into the blank terminal window.
- It will prompt you to login into Contentful using your email and password.

```
contentful login
```

**Select Space**
- Copy this next command paste into the window.
- Replace `YOUR_SPACE_ID` with your Contentful Space ID.

```
contentful space use --space-id YOUR_SPACE_ID
```

**Import Guru Guides template**
- Copy the next command below and paste into the terminal.
- This will begin importing the templates from the Guru Github.

```
contentful space import --content-file https://raw.githubusercontent.com/guru-app-team/content-model/6ab1f664e38fe39bf5fcadc2d1bf85650d7005be/guru-template.json
```
