# Create Simple Webpage using HTML & CSS

### Here's Wireframe of WebPage
![Frontend Web Development.png](https://github.com/KartikZCoding/HTML-CSS-Basics/blob/ecf0014fcddecbdf34e7fb636e32d701fdf999d8/Frontend%20Web%20Development.png)

### HTML Code
```HTML
<!DOCTYPE html>
<html>

<head>
    <title>JOb's OP</title>
    <link rel="icon" href="./Images/job-logo.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Header -->
    <header>
        <div id="navbar">
            <img src="./Images/job-logo.png" alt="logo" height="40px">
            <span id="logo-name">Job's Op</span>
        </div>
    </header>

    <!-- Banner Image -->
    <div id="banner-image">
        <img id="banner" src="./Images/banner.jpg" alt="Banner Image" height="360">
    </div>

    <!-- About -->
    <h1 id="about-head">
        About Job's
    </h1>
    <div id="about">
        <div id="description">
            <p style="margin-top: 0;">
                Jobs are evolving with technology and globalization, creating diverseopportunities in remote work, gig
                economy, and automation. Continuous learning, inclusivity, and jobsatisfaction are crucial for thriving
                in the dynamic labor market. Adaptability is key.</p>
            <p>
                We also offer 2 industry-focused bootcamp:
            <ol>
                <li>
                    <a target="_blank" href="#">FullStack Developer Bootcamp</a>
                </li>
                <li>
                    <a target="_blank" href="#">Data Science Bootcamp</a>
                </li>
            </ol>
            </p>
        </div>
        <div id="team">
            <img id="team-image" src="./Images/team.jpg" alt="Team Working Image">
        </div>
    </div>

    <!-- Jobs Opportunities -->
    <h2>Job Opportunities</h2>
    <div id="jobs">
        <div>
            <a href="#" class="apply">Apply</a>
            <h3 class="job-role">Frontend Developer</h3>
            <div class="location">Banglore, India</div>
        </div>
        <div>
            <a href="#" class="apply">Apply</a>
            <h3 class="job-role">Back end Developer</h3>
            <div class="location">Remote</div>
        </div>
        <div>
            <a href="#" class="apply">Apply</a>
            <h3 class="job-role">Data Scientist</h3>
            <div class="location">Mumbai, India</div>
        </div>
    </div>

    <!-- Footer -->
    <div id="footer">
        <ul id="footer-links">
            <li>
                <a target="_blank" href="#">Cources</a>
            </li>
            <li>
                <a target="_blank" href="#">Programs</a>
            </li>
            <li>
                <a target="_blank" href="#">Youtube</a>
            </li>
        </ul>
        <span id="copyright">© 2024, Job's Op</span>
    </div>

</body>

</html>
```
### CSS Code
```CSS
body {
  margin: 0;
  padding: 0;
  font-family: sans-serif;
}
a {
  text-decoration: none;
}

/* Header */
#navbar {
  display: flex;
  align-items: center;
  max-width: 900px;
  margin: 5px auto;
  gap: 8px;
}
#logo-name {
  font-weight: bold;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 22px;
}

/* Banner Image */
#banner-image {
  max-width: 900px;
  margin: 0 auto;
}
#banner {
  width: 100%;
  object-fit: cover;
}

/* About */
#about-head {
  text-align: center;
}
#about {
  display: flex;
  max-width: 900px;
  margin: 0 auto;
  padding: 8px;
}
#description {
  width: 50%;
  padding-right: 8px;
}
#team {
  width: 50%;
}
#team-image {
  border-radius: 5px;
  width: 100%;
}

/* Job Opportunities */
h2 {
  text-align: center;
}
#jobs {
  max-width: 900px;
  margin: 0 auto;
  padding: 0 8px;
}
.apply {
  float: right;
}
.job-role {
  margin-bottom: 0;
  margin-top: 0;
}
.location {
  color: gray;
  margin-bottom: 16px;
}

/* Footer */
#footer {
  background-color: ghostwhite;
  padding: 8px;
  padding-bottom: 20px;
  margin-top: 35px;
  text-align: center;
}
#footer-links {
  list-style: none;
}
#footer-links li {
  display: inline-block;
  margin: 0 16px;
}
#copyright {
  color: gray;
}
```
### Here's all Images
<a href="https://github.com/KartikZCoding/HTML-CSS-Basics/tree/9b038920de42b6d8702c11aaa62836f33de917ba/Images">
    <img src="https://github.com/KartikZCoding/Other-Files/blob/29c62f9aa8abe0470d9e2d75c809940a786cf035/image-logo.png" alt="Image Icon" height="90px">
</a>
