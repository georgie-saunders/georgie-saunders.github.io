<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Georgie Saunders</title>
    <style>
      body {
        background-color: #ede6db;
      }
      h1 {
        color: #ede6db;
        font-size: 48px;
        text-align: left;
        font-weight: 500;
        font-family: monospace;
        background-color: #1a3c40;
        padding: 50px;
      }
      h2 {
        color: #1a3c40;
        text-align: left;
        font-weight: normal;
        font-family: monospace;
        font-size: 34px;
        margin: 20px;
        text-decoration: none;
      }
      h3 {
        text-align: left;
        color: #1d5c63;
        font-size: 20px;
        font-weight: normal;
        font-family: verdana;
      }
      h4 {
        font-weight: normal;
      }
      ul {
        list-style-type: circle;
        margin: 20px;
      }
      li {
        transition: all 200ms ease-in-out;
        border-radius: 4px;
        max-width: 800px;
        padding: 1px;
      }
      li:hover {
        background-color: #b4c1c0;
        padding: 5px;
      }
      a {
        text-decoration: none;
        color: black;
        margin: 20px;
      }
      a:hover {
        text-decoration: underline
      }
      p {
        font-family: Verdana;
        font-size: 15px;
      }
      .skills {
        background-color: #b4c1c0;
        padding: 10px 10px;
        display: inline-table;
        border-radius: 6px;
        margin: 10px 5px 5px 20px;
        width: 235px;
        min-height: 430px;
      }
      .contact {
        background: #b4c1c0;
        padding: 10px 20px;
      }
      .menu {
        text-align: center;
        text-transform: capitalize;
        font-size: 20px;
        font-family: monospace;
      }
      .about {
        margin: 40px;
        font-size: 15px;
      } 
      .contrainer {
        min-width: 800px;
        max-width: 800px;
        margin: 0 auto;
        padding: 15px 60px;
      }
</style>

  </head>
  <body>
  <div class=contrainer>
    <h1>GEORGIE SAUNDERS</h1>
    <div class="menu">
      <h4>
        <a href="#1">KEY SKILLS</a> - <a href="#2">QUALIFICATIONS</a> -
        <a href="#3">CONTACT</a>
      </h4>
    </div>
    <hr />
    <div class="about">
      <p>Hey there, I'm Georgie 👋</p>
      <p>
        I'm a content designer/user research. I'm also a web developer in the
        making (watch this space, <em>literally</em>).
      </p>
      <p>
        As designers, our work only matters if it works for you, the user! I'm
        all about making technology and content accesible for everyone. I'm here
        to advocate for users until my heart is, and their needs are, content.
        Excuse the pun.
      </p>
      <p>
        Here you will find a little bit about me, my skills and some cool things
        I've done.
      </p>
      <p>Thanks for stopping by!</p>
    </div>
    <hr />
    <h2><a id="1" name="1">KEY SKILLS</a></h2>
    <hr />
    <div class="skills">
      <h3>CONTENT DESIGN AND DEVELOPMENT</h3>
      <p>
        Experienced in writing and structuring complex information in line with
        user needs.
      </p>
      <p>
        Knowledge of best practice principles for writing for the web and
        ability to apply these to varying contexts/topics
      </p>
      <p>
        Experience managing content review, approval and publishing processes
        with key stakeholders.
      </p>
      <p>
        Increased scale and reach of messages through engaging, relevant and
        timely content.
      </p>
    </div>
    <div class="skills">
      <h3>USER RESEARCH</h3>
      <p>Conducts research with users applying a range of methodologies.</p>
      <p>
        Identifies and extracts key opportunities to develop high impact designs
        and recommendations.
      </p>
      <p>
        Develops user personas, journey maps, conceptual models, and optimised
        processes articulated through user research and service design
        blueprints.
      </p>
      <p>Prepares and presents findings in a compelling and meaningful way.</p>
    </div>
    <div class="skills">
      <h3>TECHNICAL SKILLS AND TOOLS</h3>
      <p>
        Extensive experience in a range of platforms when developing content and
        managing workflows, such as Confluence, GatherContent, Hemmingway and
        Figma.
      </p>
      <p>
        Data analysis, finding insights and recommendations from tools such as
        Google Analytics.
      </p>
      <p>Strong HTML and CSS coding knowledge.</p>
      <p>Other tools: miro, typeform, azure, atlassian suite.</p>
    </div>
    <div class="skills">
      <h3>AGILE DELIVERY</h3>
      <p>
        Apply agile principles, values, techniques and tools in service delivery
        and product development.
      </p>
      <p>Experience in using agile tools such as Jira and Azure.</p>
    </div>
    <hr />
    <h2><a id="2" name="2">QUALIFICATIONS AND TRAINING</a></h2>
    <hr />
    <ul>
      <li>
        <p>
          BACHELOR OF COMMUNICATION IN MEDIA AND PUBLIC AFFAIRS (2014 – 2019)
        </p>
        <p><em>University of Canberra</em></p>
      </li>
      <li>
        <p>WEB DEVELOPMENT PRO (2022)</p>
        <p><em>SheCodes</em></p>
      </li>
      <li>
        <p>TRANSFORM DATA INTO ACTIONABLE INSIGHTS (2022)</p>
        <p><em>Propel Design</em></p>
      </li>
      <li>
        <p>CONTENT DESIGN: 2 DAY COURSE (2021)</p>
        <p><em>Content Design London</em></p>
      </li>
      <li>
        <p>UX DESIGN FUNDAMENTALS (2019)</p>
        <p><em>Academy Xi</em></p>
      </li>
    </ul>
    <hr />
    <div class="contact">
      <h3><a id="3" name="3">CONTACT</a></h3>
      <p><a href="tel:0411821279">0411 821 279</a></p>
      <p>
        <a href="mailto:georgie.saunders2@gmail.com"
          >georgie.saunders2@gmail.com</a
        >
      </p>
    </div>
    <hr />
    </div>
  </body>
  <script>
      let name = prompt("Hey there! What is your name?");
      {
        alert(
          "Hey " +
            name +
            ", welcome to my website! This is where I'm practicing everything I've learnt in my dev course."
        );
      }
    </script>
</html>
