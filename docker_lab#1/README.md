<div id="top"></div>
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h3 align="center">1. Docker. Task by Team#7</h3>

  <p align="center">
    Scaled Web App built by Team#7 members:
    <br />
    <br />
    <br />
    <a href="">Goncharuk Oleksandr</a>
    ·
    <a href="">Kyrychuk Dmytro</a>
    ·
    <a href="">Taras Trubaichuk</a>
  </p>
</div>


<!-- PROJECT Description -->
## Project Description

Web App built on nginx/react engine.

Lite-server backend model is used to process and validate POST requests with a new member data:
![Data in json format that is going to be POSTed to the lite-server backend model](new_entity.jpg?raw=true "new_entity")

If data is valid then lite-server redirects request to the json-server, where a new member data is going to be stored in db.json file.
![json file with stored member data](db_json.png?raw=true "db.json")

After data has been successfully stored in db.json, the React frontapp automatically makes a GET request to the json-server to get updated team members list:
![GET response data is rendered in the page](result.jpg?raw=true "result")



### Built With

* [Nginx](https://nextjs.org/)
* [React.js](https://reactjs.org/)
* [Json-server](https://vuejs.org/)
* [Lite-server](https://angular.io/)
