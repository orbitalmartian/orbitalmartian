<!-- This is an HTML file for your GitHub profile -->

<!-- Use a heading to display your username -->
<h1 id="username"> orbitalmartian </h1>

<!-- Add an image to make your profile more visually appealing -->
<img src="your-image-source" alt="Profile image" id="profile-image" />

<!-- Use a paragraph to add a short bio or description about yourself -->
<p id="bio">
  Hi, I'm orbitalmartian! I'm a software developer and open source enthusiast. I enjoy contributing to projects and learning new technologies.
</p>

<!-- Use a list to display your interests and skills -->
<ul id="interests-skills">
  <li>Interests:</li>
    <ul>
      <li>Web development</li>
      <li>Machine learning</li>
      <li>Cloud computing</li>
    </ul>
  <li>Skills:</li>
    <ul>
      <li>JavaScript</li>
      <li>Python</li>
      <li>HTML/CSS</li>
    </ul>
</ul>

<!-- Use a link to your website or social media profile -->
<a href="your-website-or-social-media-link" id="connect">Connect with me!</a>

<!-- Add the CSS styles using foreignObject -->
<foreignObject>
  <style>
    /* Add a background color to the body element */
    body {
      background-color: #333333;
    }

    /* Style the username heading */
    #username {
      color: white;
      font-family: 'Product Sans', sans-serif;
      text-align: center;
    }

    /* Style the profile image */
    #profile-image {
      border-radius: 50%; /* Add rounded edges to the image */
      width: 200px;
      height: 200px;
    }

    /* Style the bio paragraph */
    #bio {
      color: white;
      font-family: 'Product Sans', sans-serif;
      text-align: center;
      font-size: 18px;
    }

    /* Style the interests and skills list */
    #interests-skills {
      color: white;
      font-family: 'Product Sans', sans-serif;
      list-style-type: none; /* Remove bullet points from the list */
    }

    /* Style the "Connect with me!" link */
    #connect {
      color: white;
      font-family: 'Product Sans', sans-serif;
      text-decoration: none; /* Remove underline from the link */
      font-size: 18px;
    }

    /* Style the link when it is hovered over */
    #connect:hover {
      color: #00bcd4;
    }
  </style>
</foreignObject>
