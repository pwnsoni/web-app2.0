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
  border-left: 2px solid rgba(253, 251, 251, 0.36);
  height: 15.7%;
  position: fixed;
  margin-left: -3px;
  left: 5.15%;
  bottom: 0px;
}
a {
  color: rgba(253, 251, 251, 0.36);
  text-decoration: none;
}
i {
     font-size: 30px;
}
.me {
  width: 300px;
  margin: 90px auto;
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
  left: 6.4%;
  bottom: 10%;
  
}
.social ul {
  padding: 10px;
  -webkit-transform: translate(-270px, 0);
  -moz-transform: translate(-270px, 0);
  -ms-transform: translate(-270px, 0);
  -o-transform: translate(-270px, 0);
  transform: translate(-270px, 0);
}
.social ul li {
  display: block;
  margin: -5px;
  background: rgba(0, 0, 0, 0);
  width: 270px;
  text-align: right;
  padding: 10px;
  -webkit-border-radius: 0 30px 30px 0;
  -moz-border-radius: 0 30px 30px 0;
  border-radius: 0 30px 30px 0;
  -webkit-transition: all 1s;
  -moz-transition: all 1s;
  -ms-transition: all 1s;
  -o-transition: all 1s;
  transition: all 1s;
}

.social ul li:hover a {
  color: #fff;
}

body {
  background: rgb(16, 2, 32);
  color: #00f;
  font-family: 'Raleway', sans-serif;
}

</style>