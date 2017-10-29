<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>NEVER GIVE UP</h2>

 
    
    <div class = "cat">
        <table align = "centre">
            <thead>
                <tr>
                    <th>Cat</th>
                    <th>useless column</th>
                    <th>Cuteness Score</th>
                </tr>
            </thead>
          


        <tbody>
            <tr>
            <td>Cat 1</td>
                <td>meow</td>
                <td>99</td>
            </tr><tr>
            <td>Cat 2</td>
                <td>woof</td>
                <td>89</td>
            </tr><tr>
            <td>Cat 3</td>
                <td>Massage me human</td>
                <td>100</td>
            </tr><tr>
            <td>Cat 4</td>
                <td>Silence</td>
                <td>70</td>
            </tr><tr>
            
            
            
            
            
            </tr>
            
            
            </tbody>
            </table>
        </div >

    
         
       
     
    
    <ul>
      <li><a href="https://wall.alphacoders.com/big.php?i=20658" target="_blank">Click this and you will die</a><li>
     <!--
      <li><a href="https://vuejs.org" target="_blank">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank">Twitter</a></li>
     --> 
      <br>
     
      <li><a href="http://vuejs-templates.github.io/webpack/" target="_blank">Docs for This Template</a></li>
     
    </ul>
    <h2>(ﾐⓛᆽⓛﾐ)✧</h2>
    <!--
    <ul>
    
      <li><a href="http://router.vuejs.org/" target="_blank">vue-router</a></li>
      <li><a href="http://vuex.vuejs.org/" target="_blank">vuex</a></li>
      <li><a href="http://vue-loader.vuejs.org/" target="_blank">vue-loader</a></li>
      <li><a href="https://github.com/vuejs/awesome-vue" target="_blank">awesome-vue</a></li>
    </ul>
    -->

    <h1 class = "happy">HelloWorld</h1>
    <ul>
        <li>Give in to my Cuteness</li>
        <li>This is an order</li>
        <li> I am your master</li>
    </ul>
  </div>

 


</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'KoolKitten'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: heavy;
  font-size: 40px;
  
}

ul {
  list-style-type: none;
  padding: 12px;
}
happy {
  color: #FFFF00;

}

li {
  display: inline-block;
  margin: 0 100px;
}

a {
  color: #FF0000;
}

table{
  font-family: comic-sans, sans-serif;
    border-collapse: collapse;
    width: 100%;
}
td, th {
    border: 1px solid #FF1493;
    text-align: centre;
    padding: 8px;
}
tr:nth-child(even) {
    background-color: #87CEFA;
}

</style>
