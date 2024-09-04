<template>
  <div class="home">
    <div class="container">
          <h1>Open University of Sri Lanka</h1><br><br>
          <p><span>The Open University of Sri Lanka (OUSL)</span> is a national university in Sri Lanka. It is unique within the Sri Lankan national university system for being the only university to offer programs of study leading to Certificate, Diploma, Degrees and Postgraduate degrees up to PhD level through the <span>Open and Distance Mode of Learning(ODL).</span> 
        The degrees awarded by the university are treated as equivalent to degrees awarded by any other Sri Lankan University under the preview of the University Grants Commission.</p>
          <br>
          <h3>Courses offered</h3>
          <ol>
           <li>Software Engineering</li>
           <li>Computer Science</li>
           <li>Networking</li>
          </ol>
    </div>
  </div>
</template>

<script>
export default {
  name: 'home',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.container{
    margin-top: 20px;
    display: block;
}

h1{
    margin-top: 30px;
    margin-bottom: 10px;
    text-align: center;
    text-decoration: none;
    color: #4CAF50;
    font-family: Georgia, 'Times New Roman', Times, serif;
}

p{
    margin-top: 10px;
    margin-bottom: 10px;
    font-size: 22px;
    font-family: sans-serif;

}

h3{
    font-family: cursive;
    font-style: inherit;
    color: #a04554;
}

ol{
    font-size: 18px;
    color: rgb(61, 107, 55);
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    
}

span{
    font-weight: bold;
}
</style>
