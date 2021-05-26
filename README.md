
<html>
<style>
.head{
  font-size: 30px;
  font-weight: bold;
  display: block;
  text-align: center;
color: gray;
}

.container{

  display: flex;
  align-items: center;
  justify-content:center;
  padding: 5px;
}

.card{
  border: 1px solid #eee;
padding: 10px;
cursor: pointer;
margin:15px;
border-radius: 10px;
box-shadow: 1px 2px 2px gray;
transition: all 0.3s ease-in;
}

.card:hover{
  transform: scale(1.1);
}

.card li{
  display: block;
}

#mail{
  color: blue;
  cursor: pointer;
}

#mail:active{
  transform: scale(0.9);
}

.figma{
  border: 1px solid #eee;
  cursor: pointer;
  display: inline-block;
  padding: 8px;
  border-radius: 8px;
  width: 110px;
  white-space: nowrap;
  overflow: hidden;
transition: width 0.5s ease;
}

.figma:hover{
  width: 300px;
}

@media (max-width:990px){
  .container{
    flex-direction: column;
  }
}
</style>
<body>

<p class="info">
<li>👋 Hi, I’m Gautam!</li>
<li>👀 I’m interested in anything that is interesting.</li>
<li>🌱 I’m currently learning a lot of management.</li>
<li>📫 How to reach me? But wait, why do you want to reach me?
Anyway mail: <span id="mail">devgautam1231@gmail.com</span>  </li>
<li>🌱 I’m currently learning a lot of management.</li>
</p>


<em class="head">My Skillset</em>
<div class="container">

<div class="card">
<h4>Web Development</h4>
<li>React.js</li>
<li>Next.js</li>
<li>HTML,CSS,ES6</li>
</div>
<div class="card">
<h4>Web Development</h4>
<li>React.js</li>
<li>Next.js</li>
<li>HTML,CSS,ES6</li>
</div>
<div class="card">
<h4>Web Development</h4>
<li>React.js</li>
<li>Next.js</li>
<li>HTML,CSS,ES6</li>
</div>

</div>

<h5 class="figma">Figma Handle: <a href="https://www.figma.com/@devgautam">figma.com/@devgautam</a></h5>
</body>
</html>
<!---
DevGautam2000/DevGautam2000 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
