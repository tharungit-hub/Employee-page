# Employee-page

## AIM
Design a wesite for company employee page

# ALGORITHM
### STEP 1
create a simple html page using heading tag
### STEP 2
Add a div tag to create a container for employee details
### STEP 3
Add a css for color, style to make good user interaction and responsive
### STEP 4
Execute the program
# CODE
~~~
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
html {
  box-sizing: border-box;
}

*, *:before, *:after {
  box-sizing: inherit;
}

.column {
  float: left;
  width: 33.3%;
  margin-bottom: 16px;
  padding: 0 8px;
}

@media screen and (max-width: 650px) {
  .column {
    width: 100%;
    display: block;
  }
}

.card {
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
}

.container {
  padding: 0 16px;
}

.container::after, .row::after {
  content: "";
  clear: both;
  display: table;
}

.title {
  color: grey;
}

.button {
  border: none;
  outline: 0;
  display: inline-block;
  padding: 8px;
  color: white;
  background-color: #000;
  text-align: center;
  cursor: pointer;
  width: 100%;
}

.button:hover {
  background-color: #555;
}
</style>
</head>
<body>

<h2>Employee page</h2>

<br>

<div class="row">
  <div class="column">
    <div class="card">
      <img src="/w3images/team1.jpg" alt="Albert Gonzalez" style="width:100%">
      <div class="container">
        <h2>Albert Gonzalez</h2>
        <p class="title">CEO & Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
    <div class="column">
    <div class="card">
      <img src="/w3images/team2.jpg" alt="Mike" style="width:100%">
      <div class="container">
        <h2>Mike Ross</h2>
        <p class="title">Art Director</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
    <div class="column">
    <div class="card">
      <img src="/w3images/team3.jpg" alt="John" style="width:100%">
      <div class="container">
        <h2>John Doe</h2>
        <p class="title">Designer</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="row">
    <div class="column">
      <div class="card">
        <img src="/w3images/team1.jpg" alt="Jane" style="width:100%">
        <div class="container">
          <h2>Jane Doe</h2>
          <p class="title">CEO & Founder</p>
          <p>Some text that describes me lorem ipsum ipsum lorem.</p>
          <p>example@example.com</p>
          <p><button class="button">Contact</button></p>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="card">
        <img src="/w3images/team2.jpg" alt="Adrian Lamo" style="width:100%">
        <div class="container">
          <h2>Adrian Lamo</h2>
          <p class="title">Art Director</p>
          <p>Some text that describes me lorem ipsum ipsum lorem.</p>
          <p>example@example.com</p>
          <p><button class="button">Contact</button></p>
        </div>
      </div>
    </div>
    <div class="column">
      <div class="card">
        <img src="/w3images/team3.jpg" alt="Michael Calce" style="width:100%">
        <div class="container">
          <h2>Michael Calce</h2>
          <p class="title">Designer</p>
          <p>Some text that describes me lorem ipsum ipsum lorem.</p>
          <p>example@example.com</p>
          <p><button class="button">Contact</button></p>
        </div>
      </div>
    </div>

</body>
</html>

~~~
# OUPUT
![SEC](exp3.png)

# RESULT
wesite for company employee page was successfully executed.
