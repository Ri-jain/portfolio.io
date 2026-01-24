<style>
  /* This targets the left sidebar area specifically in the 'orderedlist' theme */
  @media screen and (min-width: 1024px) {
    .project-nav {
      position: fixed;
      left: 40px; /* Adjust based on your profile photo alignment */
      top: 450px; /* Positions it below your profile picture */
      width: 200px;
      text-align: left;
      font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
    }
    .project-nav ul {
      list-style: none;
      padding: 0;
    }
    .project-nav li {
      margin-bottom: 12px;
      font-size: 14px;
    }
    .project-nav a {
      color: #39c; /* Matches the theme's default blue */
      text-decoration: none;
      transition: color 0.2s;
    }
    .project-nav a:hover {
      color: #222;
      font-weight: bold;
    }
  }
  /* Hide sidebar on mobile to avoid clutter */
  @media screen and (max-width: 1023px) {
    .project-nav { display: none; }
  }
</style>

<div class="project-nav">
  <p style="font-weight: bold; color: #222; margin-bottom: 10px;">PROJECT INDEX</p>
  <ul>
    <li><a href="#tennis">🎾 Sport Analytics</a></li>
    <li><a href="#mobility">🚆 MBTA Optimization</a></li>
    <li><a href="#aviation">✈️ Aviation Trends</a></li>
    <li><a href="#healthcare">🏥 Healthcare Analytics</a></li>
  </ul>
</div>




## Sport Analytics {#tennis}
...
## Mobility Optimization & Analysis {#mobility}
...
## European Air Traffic Trends {#aviation}
...
## Healthcare Analytics {#healthcare}
