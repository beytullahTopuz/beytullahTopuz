### Hi 👋 my I'm Beytullah


<hr/>

<!--
**beytullahTopuz/beytullahTopuz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

  <div class="container">
    <h1>Skill Set</h1>
    <div class="bar learning" data-skill="TDD"></div>
    <div class="bar back basic" data-skill="Python"></div>
    <div class="bar back intermediate" data-skill="C#"></div>
    <div class="bar front advanced" data-skill="CSS3"></div>
    <div class="bar front expert" data-skill="HTML5"></div>

  body{
  font-family: Helvetica, Arial, sans-serif;
}
.container{
  width: 50%;
  margin: 0 auto;
}
@keyframes load{
  from {
    width: 0%
  }
}
@-webkit-keyframes load{
  from {
    width: 0%
  }
}
@-moz-keyframes load{
  from {
    width: 0%
  }
}
@-o-keyframes load{
  from {
    width: 0%
  }
}

.bar{
  background-color: #EEE;
  padding: 2px;
  border-radius: 15px;
  margin-bottom: 5px;
  font-size: 14px;
  color: #FFF;
  font-weight: bold;
  text-shadow: 1px 1px 1px rgba(0,0,0,0.5);
}
.bar::before{
  content:  attr(data-skill);
  background-color: #f3b0ff;
  display: inline-block;
  padding: 5px 0 5px 10px;
  border-radius: inherit;
  animation: load 2s 0s;
  -webkit-animation: load 2s 0s;
  -moz-animation: load 2s 0s;
  -o-animation: load 2s 0s;
}

.bar.front::before{
  background-color: #ffcc33;
}
.bar.back::before{
  background-color: #a6cfe3;
}

.bar.learning::before{
  width: calc(20% - 10px);
}
.bar.basic::before{
  width: calc(40% - 10px);
}
.bar.intermediate::before{
  width: calc(60% - 10px);
}
.bar.advanced::before{
  width: calc(80% - 10px);
}
.bar.expert::before{
  width: calc(100% - 10px);
}

  </div>
