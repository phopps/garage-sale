# Garage Sale

## Description

Garage Sale is a website where a user can upload, price, categorize and sell personal products. Buy and sell your items online with a virtual garage sale! Clear out the clutter in your garage, or shop around online to see what other users are selling!

<!-- **Heroku deployment:**
<https://garage-sale-heroku.herokuapp.com/> -->

**GitHub repository:**
<https://github.com/phopps/garage-sale>

## Motivation

<!-- TODO: Why build it? What problems does it solve? What has been learned while working on it? -->

To create a secure website to personally post and sell items of value.

## User Story

```text
AS A user,
I WANT a website,
SO THAT I can buy/sell my personal belongings.
```

## Table of Contents

- [Garage Sale](#garage-sale)
  - [Description](#description)
  - [Motivation](#motivation)
  - [User Story](#user-story)
  - [Table of Contents](#table-of-contents)
  - [Technologies](#technologies)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Contributing](#contributing)
  - [Tests](#tests)
  - [Screenshots](#screenshots)
  - [Credits](#credits)
  - [Roadmap](#roadmap)
  - [License](#license)
  - [Badges](#badges)
  - [Contributions](#contributions)
  - [Testing](#testing)

## Technologies

- React/Router/DOM
- Apollo Client/Server Express
- Bcrypt
- Express.js
- GraphQL
- JWT
- Mongoose
- MongoDB

## Installation

Clone the repository with HTTPS:

```bash
git clone https://github.com/phopps/garage-sale.git
```

or SSH:

```bash
git clone git@github.com:phopps/garage-sale.git
```

In a separate terminal, start the MongoDB database:

```bash
mongod
```

Navigate to the root of your project directory and install the node packages:

```bash
npm run install
```

Seed the database:

```bash
npm run seed
```

## Usage

Run the application normally:

```bash
npm run start
```

Run the application in development mode:

```bash
npm run develop
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Tests

Tests will be updated and included here in future developments.

## Screenshots

![Garage Sale banner](/client/public/images/garage-sale-banner.PNG)

## Credits

[Isaac Andrade](https://github.com/Isaaccna)

[Preston Foote](https://github.com/pwfoote)

[Patrick Hopps](https://github.com/phopps)

## Roadmap

Future developments include:

- Users can upload profile picture images
- Users can upload product images
- Seller page containing all of their products for sale
- User friend lists
- Star ratings for products
- Integrated Stripe payment platform

## License

MIT

## Badges

<!-- TODO: Add badges displaying repository information -->

## Contributions

<!-- TODO: How to contribute? -->

## Testing

<!-- TODO: Setup unit tests -->

The Jest testing framework is used alongside the concept of test-driven development.

Install Jest by running `npm install jest --save-dev` or `npm i jest -D`.

Once Jest is installed, open the `package.json` file, go the the `scripts` property, and update the value of the `"test"` property to `jest`.

Running `npm test` will run all tests in the `__test__` folder, or `npm test <filename>` can be used to specify a specific test to run by replacing `<filename>` with the name of the test file.

Test suite files use the `<filename>.test.js` naming convention by replacing `<filename>` with the name of the file being tested.
