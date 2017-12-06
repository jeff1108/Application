
---
---

@import "{{ site.theme }}";
.box {
  border-style: solid;
  border-color: black;
  border-width: 2px;
  text-align: left;
}

body {
  margin: 60px;
  background-color: white;
  background-position: center;
  background-repeat: no-repeat;
  background-attachment: fixed;
 
}

.main-field {
  background-color: #D1D0CE;
  border-radius: 5px;
  padding-top: 20px;
}

.background {
  background-color: #860038;
}

.white-text {
  color: white;
  font-family: "Open Sans Condensed";
  text-align: center;
}

.thin-border {
  border-color: white;
  border-width: 2px;
  border-style: solid;
}

.black-text {
  color: black;
  font-family: "Open Sans Condensed";
  text-align: center;
}

.thin-white-border {
  border-color: white;
  border-width: 5px;
  border-style: dashed;
}

.thin-black-border {
  border-color: black;
  border-width: 10px;
  border-style: solid;
  border-radius: 10px;
}

.injected-text {
  margin-bottom: -15px;
  text-align: center;
  font-family: 'Timmana', sans-serif;
  color: white; 
}

.brown-box {
  background-color: #860038;
  padding: 5px;
  margin: 10px;
}

.white-box {
  background-color: white;
  padding-top: 10px;
  padding-right: 20px;
  padding-bottom: 15px;
  padding-left: 40px;
  margin: 10px;
}


h1 {
  font-size: 70px;
  font-family: "Open Sans Condensed";
}

.larger-image {
  width: 500px;
}

p {
  font-size: 25px;
  font-family: "Open Sans Condensed";
}


#myDIV {
  background: black;
  -webkit-animation: mymove 5s infinite;
  animation: mymove 5s infinite;
}

@-webkit-keyframes mymove {
  50% {background-color: #D1D0CE;}
}

@keyframes mymove {
  50% {background-color: #860038;}
}


#question {
  background-color: #860038;
  width: 900px;
  margin-left: 200px;
  margin-right: 150px;
  padding-bottom: 4px;
  
}
