<template>
  <div id="app">
    <div class="hero">
           <div class="navbar">
               <div class="newlinks">
                   <ul>
                       <li><router-link to="/"><i class="fa fa-home"></i> Home</router-link></li>
                       <li><router-link to="/courses"><i class="fa fa-university"></i> Courses</router-link></li>
                       <li><router-link to="/faq"><i class="fa fa-quora"></i> FAQ</router-link></li>
                       <li><router-link to="/about"><i class="fa fa-user"></i> About Us</router-link></li>
                       <li><router-link to="/contact"><i class="fa fa-phone"></i> Contact Us</router-link></li>
                       <li><button>Sign In</button></li>
                   </ul>
               </div>  
           </div>
    </div>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #333;
    color: white;
    padding: 10px 20px;
}

.newlinks {
    margin-left: auto;
}

.newlinks ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.newlinks ul li {
    display: inline;
    margin-right: 10px;
}

.newlinks ul li a {
    text-decoration: none;
    color: white;
}

.newlinks ul li button {
    background-color: #4CAF50;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

.newlinks ul li button:hover {
    background-color: #a04554;
}

</style>
