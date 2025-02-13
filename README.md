# Guide Guides Template
Importing Guru Guides template into Contentful for users to add their own guidelines to the Guru Guides plugin.


**Login via the terminal**
- Open the Terminal and paste the command into the blank terminal window.
- It will prompt you to login into Contentful using your email and password to gain an access token.

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
- Download [Raw Template File](https://github.com/guru-app-team/guru-guides-template/blob/main/guru-guides-template.json) from the Toolbar and this should save to your downloads folder on your machine.
- Copy the command below and paste it into the terminal.
- This will begin importing the templates from the Guru Github.
- If your download location varies from what is described in the script below, please adjust accordingly.


```
contentful space import --content-file ~/Downloads/guru-guides-template.json
```

