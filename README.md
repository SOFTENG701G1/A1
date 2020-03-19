# Split
![split](https://user-images.githubusercontent.com/8885794/77110524-91a8a080-6a8a-11ea-9ad0-950b17ac6c93.png)

When on a trip or vacation, or even just going to a restaurant, it's very likely that one person will front the bill for the group.

It is an impossible task to keep all expenses accounted for. Hence, our team decided to make a web application which keeps track of all payments. In the end, the aim is to calculate and display what each member owes based on how much they have spent during the trip and on what things.

The current functionality only supports splitting a bill where a single person makes the payment on behalf of the group (for example, at a dinner reservation). All other members present have to then owe the person who paid the entire bill.

Future work includes extending the web app to allow budgeting and scenarios where multiple pay on an entire trip. It would also be nice to split the bill in different ways, such as by percentage or randomly instead of just evenly.

# Getting Started

## Requirements
* npm for running the web app
* CherryPy for running the server
* Python 3

## Running the app locally

### Web-app
1. Navigate to `A1/split-webapp/split` in your terminal
2. Run `npm i` to install all the dependancies
3. Run `npm start`

The web app is built in [React](https://reactjs.org/) and uses [Material-UI](https://material-ui.com/).

### Server
1. Navigate to `A1/server/src`
2. Make sure CherryPy is installed. You can install it with `pip install CherryPy` or `pip3 install CherryPy`
3. Run `main.py` with Python3 e.g. `./main.py` or `python3 main.py`

The back-end is built in Python and uses [CherryPy](https://cherrypy.org/) and [SQLite](https://www.sqlite.org/index.html).

# Contributing
To learn how to contribute, please read [CONTRIBUTING.md](https://github.com/SOFTENG701G1/A1/blob/master/CONTRIBUTING.md).

# Authors
See [List of Contributors](https://github.com/SOFTENG701G1/A1/wiki/List-of-contributors) to see who worked on this project. Remember to add yourself to this file if you also worked on it :blush:    

# License
This project is licensed under GNU General Public License v3.0. See [LICENSE.md](https://github.com/SOFTENG701G1/A1/blob/master/LICENSE.md) for more details

# Acknowledgements
* Special thanks to Kelly Blincoe
