# Kards - Simple Kanban Board

<img alt="HTML5" src="https://img.shields.io/badge/html5%20-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS" src="https://img.shields.io/badge/css3%20-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white"/> <img alt="JavaScript" src="https://img.shields.io/badge/javascript%20-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/>

A simple cards-based kanban board web app heavily inspired by Trello, the UI is also pretty similar to that of Trello. You can create many different kanban boards with different names, which holds cards. Each card can hold an unlimited number of items/tasks each. All items support drag and drop between cards as well as within the same card to reorder. All data is stored locally on the computer by the browser. This whole project was written by [waterrmalann](https://github.com/waterrmalann) in HTML, CSS, and pure vanilla JavaScript with no external dependencies.

### Product roadmap

![Screenshot](screenshot.JPG)

### Prerequisites

In order to set up and run the application on your machine, you will need to have the [npm](https://www.npmjs.com/) package manager installed.

To check whether you have npm installed, run the following command your terminal:

```
npm -v
```

If the output contains some sort of version number, then everything is okay.

If you see some variation of `command not found: npm`, try running `brew install node` to install NodeJS and its supporting commands, and then repeat the above command.

### Setup

To run this application from within a terminal on your machine:

1. Clone the repository.
```
git clone https://github.com/makersacademy/sample-trello-clone.git
```

2. Change directory into the folder which you just cloned.
```
cd sample-trello-clone
```  

4. Install the dependencies.
```
npm install
```

4. Run the server. 
```
npm run serve
```

If the server starts successfully, you should see a message like this in your terminal:

```
Serving "/Users/your_username/dev/sample-trello-clone" at http://127.0.0.1:8080
```

Take the URL at the end of this message (expressed in the form of an IP address, and the port number which it is running on) and load in a web browser - you should now see the Kards interface, and you're ready to go.

If you're unable to get the application running locally, a live version of the web app is available on the author's GitHub Pages: [https://waterrmalann.github.io/kards/](https://waterrmalann.github.io/kards/).

---

License
----

MIT License, see [LICENSE](LICENSE)
