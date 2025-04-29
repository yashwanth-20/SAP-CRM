<h1 align="center">
  React SAP CRM
</h1>

This react demo is built on the top of my customized React boilerplate with Storybook. 

If you want to build something simpler from scratch, you can follow the README to build your own app step by step.




### Screenshots

![Screenshot1](screenshots/react-demo-v6-screen1.png)

![Screenshot2](screenshots/react-demo-v6-screen2.png)

![Screenshot3](screenshots/react-demo-v6-screen3.png)

![Screenshot4](screenshots/react-demo-v6-screen4.png)

<!-- ![Screenshot4](screenshots/screenshot-4.jpg) -->

----


## Getting Start

```bash
# Clone project
git clone https://github.com/harryho/react-demo.git


# install the packages with npm
cd react-demo

# development
yarn dev

# build
yarn build

```




  New master doesn't rely on Json-Server as fake API. It will only have Readonly fake API. It means any new or updated data will be stored to any physical file. All test data will be rolled back after system restart.

- May 2018 -  Create an archived branch json-server

  This branch was the master which used Json-Server as fake API. Considering the hiccup of setting Json-Server up and maintenance, it will be replaced by fake service ( Readonly fake API). You still can find clone this branch by branch name **json-server**, but it will be no longer updated. It is an archived branch.
