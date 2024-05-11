<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="tab-container">
    <button class="tablink" onclick="openTab('aboutMe')">About Me</button>
    <button class="tablink" onclick="openTab('softwareProjects')">My Software Applications Projects</button>
    <button class="tablink" onclick="openTab('dataAnalysisProjects')">My Data Analysis Projects</button>
  </div>
  
  <div id="aboutMe" class="tabcontent">
    <h2>About Me</h2>
    <p>Put your About Me content here.</p>
  </div>
  
  <div id="softwareProjects" class="tabcontent">
    <h2>My Software Applications Projects</h2>
    <p>Put your software projects content here.</p>
  </div>
  
  <div id="dataAnalysisProjects" class="tabcontent">
    <h2>My Data Analysis Projects</h2>
    <p>Put your data analysis projects content here.</p>
  </div>
  
  <script>
    function openTab(tabName) {
      var i, tabcontent, tablinks;
      tabcontent = document.getElementsByClassName("tabcontent");
      for (i = 0; i < tabcontent.length; i++) {
        tabcontent[i].style.display = "none";
      }
      tablinks = document.getElementsByClassName("tablink");
      for (i = 0; i < tablinks.length; i++) {
        tablinks[i].className = tablinks[i].className.replace(" active", "");
      }
      document.getElementById(tabName).style.display = "block";
      event.currentTarget.className += " active";
    }
  </script>
</body>
</html>



body {
  font-family: Arial, sans-serif;
}

.tab-container {
  overflow: hidden;
  border: 1px solid #ccc;
  background-color: #f1f1f1;
}

.tablink {
  background-color: #ddd;
  float: left;
  border: none;
  outline: none;
  cursor: pointer;
  padding: 10px 20px;
  transition: 0.3s;
}

.tablink:hover {
  background-color: #bbb;
}

.tabcontent {
  display: none;
  padding: 20px;
  border-top: none;
}

/* Style the active tab */
.tablink.active {
  background-color: #ccc;
}


# My Portfolio

<div class="tab-container">
  <button class="tablink" onclick="openTab('aboutMe')">About Me</button>
  <button class="tablink" onclick="openTab('softwareProjects')">My Software Applications Projects</button>
  <button class="tablink" onclick="openTab('dataAnalysisProjects')">My Data Analysis Projects</button>
</div>

<div id="aboutMe" class="tabcontent">
  <h2>About Me</h2>
  <p>Put your About Me content here.</p>
</div>

<div id="softwareProjects" class="tabcontent">
  <h2>My Software Applications Projects</h2>
  <p>Put your software projects content here.</p>
</div>

<div id="dataAnalysisProjects" class="tabcontent">
  <h2>My Data Analysis Projects</h2>
  <p>Put your data analysis projects content here.</p>
</div>

<script>
  function openTab(tabName) {
    var i, tabcontent, tablinks;
    tabcontent = document.getElementsByClassName("tabcontent");
    for (i = 0; i < tabcontent.length; i++) {
      tabcontent[i].style.display = "none";
    }
    tablinks = document.getElementsByClassName("tablink");
    for (i = 0; i < tablinks.length; i++) {
      tablinks[i].className = tablinks[i].className.replace(" active", "");
    }
    document.getElementById(tabName).style.display = "block";
    event.currentTarget.className += " active";
  }
</script>
