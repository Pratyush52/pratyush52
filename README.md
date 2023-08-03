### Hi there 👋

<!--
**Pratyush52/pratyush52** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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

<style>
  :root{
  --g1: #006400;
  --g2: #009600;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  background: #000;
  display: flex;
  flex-direction: column;
  gap: 5rem;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
button{
  cursor: pointer;
  padding: 0.5rem 1rem;
}
.container{
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  animation: flower 2s infinite;
  border-radius: 50%;
  box-shadow: 0 0 120px rgba(0, 255, 0, 0.4);
  transition: all 0.6s;
}
.container:hover{
  box-shadow: none;
}
.curve{
  height: 5rem;
  width: 5rem;
  border-radius: 50%;
  border: 1rem solid green;
  animation: flow 2s infinite;
}
.c1{
  border-top-left-radius: 0%;
  border-bottom-right-radius: 0%;
  border-right: 1rem solid var(--g1);
  border-left: 1rem solid var(--g2);
}
.c2{
  border-top-right-radius: 0%;
  border-bottom-left-radius: 0%;
  border-bottom: 1rem solid var(--g1);
  border-top: 1rem solid var(--g2);
}
.c3{
  border-bottom-left-radius: 0%;
  border-top-right-radius: 0%;
  border-top: 1rem solid var(--g1);
  border-bottom: 1rem solid var(--g2);
}
.c4{
  border-bottom-right-radius: 0%;
  border-top-left-radius: 0%;
  border-left: 1rem solid var(--g1);
  border-right: 1rem solid var(--g2);
}
@keyframes flow{
  0%{
    transform: rotate(0deg);
  }
  100%{
    transform: rotate(360deg);
  }
}
@keyframes flower{
  0%{
    transform: rotate(0deg);
  }
  100%{
    transform: rotate(360deg);
  }
}
</style>

<div class="container">
  <div class="curve c1"></div>
  <div class="curve c2"></div>
  <div class="curve c3"></div>
  <div class="curve c4"></div>
</div>
