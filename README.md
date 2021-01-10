### Crafts Storefront
Storefront component of full-stack project, extending and customising the [Saleor](https://github.com/mirumee/saleor) (2.11) eCommerce platform.

### Installing and Running on Linux:
First, you must have the API running, and the API_URI noted down, as you will need it to wire up the storefront with the backend.
Initial setup of machine:
```
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt-get update
sudo apt-get -y upgrade
```

Node and Node Version Manager:
```
sudo apt install npm

curl https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash

source ~/.profile 
source ~/.bashrc
nvm install v12
```
Navigate to where you want to install and:
```
git clone https://github.com/Luka-Abey/ruthfully-storefront.git
cd ruthfully-storefront
```
Now to install dependencies:
```
npm i
```
And to run:
```
npm start
```

### Built With

- [Apollo Client](https://www.apollographql.com/client), [React](https://reactjs.org/) and [Typescript](https://www.typescriptlang.org/)
- GraphQL API integration
- [Braintree Payment Gateway](https://www.braintreepayments.com/) integration

By [Mirumee](https://github.com/mirumee) and Luka-Abey