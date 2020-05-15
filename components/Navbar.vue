<template>
    <div class="nb">
    <b-navbar toggleable="lg" type="dark"  >
        <b-navbar-brand href="/" class="home"> <i> <font-awesome-icon :icon="['fas', 'home']"/></i></b-navbar-brand>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

            
        

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">
            <b-navbar-nav class="rt">
                <b-nav-item href="#projects">Projects</b-nav-item>
                <b-nav-item href="#internExperience">Internships</b-nav-item>
                <b-nav-item href="#ping" >Ping</b-nav-item>
                <b-nav-item href="https://github.com/pwnsoni" target="_blank" class="l">Github</b-nav-item>
                
            </b-navbar-nav>
        </b-navbar-nav>
        </b-collapse>
    </b-navbar>
    </div>
</template>


<style type="text/css">
    .rt{
        font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
        text-align: right;
        font-size: 20px;
    }
    .nb {
        position: fixed;
        width: 100%;
        top: 0px;
    }

    i{
        width: px;
        margin: 00% 0% 0% 80%;
        
    }
    .l{
        border: 0.1px solid #3b8070;
        padding: 0px;
    }
</style>