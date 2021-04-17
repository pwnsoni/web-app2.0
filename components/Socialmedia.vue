<template>
  <div>
      <body >
        <nav class = "social">  
            <div>
            <ul>
                <li><a href="https://www.linkedin.com/in/pwnsoni/" target="_blank">  <i> <font-awesome-icon :icon="['fab', 'linkedin']"/></i></a></li>
                
                <li><a href="https://github.com/pwnsoni" target="_blank">  <i><font-awesome-icon :icon="['fab', 'github']"/></i></a></li>
                <li><a href="https://www.facebook.com/pwnsni" target="_blank">  <i><font-awesome-icon :icon="['fab', 'facebook']"/></i></a></li>
                
            </ul>
            </div>
        </nav>
        
      </body>
      <div class="vl"></div>
  </div>
</template>

<style type="text/css">
.vl {
  border-left: solid rgba(253, 251, 251, 0.36);
  height: 80px;
  position: fixed;
  left: 59.0px;
  /* left: calc(29.35px + (68.49 - 29.35) * ((100vw - 300px) / (1600 - 300))); */
  bottom: 0px;
  padding: 10px;
}
a {
  color: rgba(253, 251, 251, 0.36);
  text-decoration: none;
}
i {
     /* font-size: 30px; */
     font-size: 23px;
}

.me p,
.me h1 {
  text-transform: uppercase;
  letter-spacing: 3px;
  text-align: center;
}
.me p {
  font-weight: 200;
}
.me span {
  font-weight: bold;
}
.social {
  position: fixed;
  left: 11px;
  bottom: 55px;
  
}
.social ul {
  padding: 10px;
  
}
.social ul li {
  background: rgba(0, 0, 0, 0);
  padding: 10px;
}

.social ul li:hover a {
  color: #fff;
}

body {
  background: rgb(16, 2, 32);
  color: rgb(16, 2, 32);
  font-family: 'Raleway', sans-serif;
}

</style>