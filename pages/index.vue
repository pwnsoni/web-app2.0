<template>
  <div class="container">
    <div>

      <h2 class="subtitle">
        Hi, I am 
      </h2>
      <br/>
      <h1 class="title">
        Pawan Soni.
      </h1>
      <br/>
      <h3 class="subtitle2" id="projects">
        <!-- A swift-learner, web developer -->
        A swift-learner, developer, coder, Final year undergraduate 
        <br/>
        Open to Full time job opportunities or Freelance projects. <br/><br/>
        Proficient in JavaScript and Java.
      </h3>

      <br/><br/><br/><br/><br/>

      <div>

      <h1 class="heads"> Projects </h1>
      <br/>
      <h2 class="subHeads"> Pharma-Chain (Based on Blockchain) </h2>
      <br/>
      <p>
      A Project for Supply Chain Management based on blockchain technology for pharmacy products. It's goal is
      to provide real-time tracebility information to consumers with just a click.
      <br/>
      I have also developed a nuxt web app, which will serve as client for the network, meaning it will be used to
       transact over the network by the users. 
       <br/>
      <strong> This project got selected for prototype funding as well by CST, UP. (2019-20)</strong>
      <br/>
      <br/>
      Technology Used : Hyperledger Fabric, JavaScript, Nodejs, Nuxt, IBM Blockchain Platform Extension 
      </p>

      <div class="links">
        <a
          href="https://github.com/pwnsoni/pharmaceutical-supply-chain"
          target="_blank"
          class="button--green"
        >
          Github Repo Link
        </a>
      </div>

      <br/> <br/>
   
      <h2 class="subHeads"> Fruit-Chain (Based on Blockchain) </h2>
      <br/>
      <p>
      A Project (Chain code or Smart Contracts) for Supply Chain Management based on blockchain technology for Fruits. It's goal is
      to provide real-time tracebility information to consumers with just a click.
      <br/>
      <strong> This project only contains the chain code for all the transactions required.</strong>
      <br/>
      <br/>
      Technology Used : Hyperledger Fabric, JavaScript, IBM Blockchain Platform Extension 
      </p>
   
      
      
      <div class="links">
        <a
          href="https://github.com/pwnsoni/fruit-chain"
          target="_blank"
          class="button--green"
        >
          Github Repo Link
        </a>

      </div>
      <br/><br/><br/><br/><br/>
      </div>
    <div id="internExperience" >

      <h1 class="heads" > Internship Experiences </h1>
      <br/>
      <h2 class="subHeads"> Lesspod (Serverless Internet) </h2>
      <br/>
      <p>
      This was my first internship experience remotely, I have a learnt alot in that period. I contributed to a blogging
      web-app in both sides, i.e., client side and server side. It was based on stack MEVN.
      <br/>
      <strong> I also deloyed this project to AWS lambda using serverless framework.</strong><br/>
      <strong> Duration : Apr 2019 to Jun 2019</strong>
      <br/>
      <br/>
      Technology Used : Nuxt, Nodejs, Mongodb, JavaScript, git and github
      </p>
      <div class="links">
        <a
          href="https://github.com/lesspod/lesspod-2.0"
          target="_blank"
          class="button--green"
        >
          Github Repo Link
        </a>
      </div>

<br/> <br/>
      <h2 class="subHeads"> CSDC India </h2>
      <br/>
      <p>
      This was my first in office internship experience , In this learning period, I contributed to a building 
      registration app for Dehradun government, I made my contributions in front end. Then I learnt some things about
      SQL, I was given a big database to play with, I also learnt about Java in this learning period.
      <br/>
      <strong> Duration : Aug 2019 to Sep 2019</strong>
      <br/>
      <br/>
      Technology Used : Angular, SQL JavaScript, svn
      </p>

      <br/> <br/><br/> <br/>
      </div>


      <div>
        <h1 class="heads" id="ping"> Get In Touch </h1>
        <br/>
      <p>
      I am currently looking for full-time opportunities and freelance projects based on my expertise,
      Feel free to contact me whether it is for opportunities, community gatherings or just to say hello.
      </p>
      <br/>
      <div class="links">
          <a
            href="mailto:pawansoni76@gmail.com"
            target="_blank"
            class="button--green"
          >
            Say Hello
          </a>
      </div>
      
      </div>
    </div>
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'
import Socialmedia from '~/components/Socialmedia.vue'
import Navbar from '~/components/Navbar.vue'

export default {
  components: {
    Logo,
    Socialmedia,
    Navbar
  }
}
</script>

<style>

.cards{
  background: rgb(16, 2, 32);
  color: #526488;
  font-size: 30px;
}

.container {
  margin: 20% 20% 22% 22%;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: left;
  background:rgb(16, 2, 32);
  width: 60%;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 70px;
  color: rgb(233, 201, 229);
  letter-spacing: 1px;
  animation: 1s appear;
}

.heads {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 50px;
  text-align: center;
  color: rgb(233, 201, 229);
  letter-spacing: 1px;
  animation: 2s appear;
  
}

.subHeads {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 35px;
  color: rgb(233, 201, 229);
  letter-spacing: 1px;
}

p {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 18px;
  color: #526488;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 35px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 1px;
}

.subtitle2 {
  font-weight: 300;
  font-size: 27px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 1px;
}

.links {
  padding-top: 15px;
  text-align: center;
}
</style>
