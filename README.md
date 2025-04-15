<script>
  const text = "Tom Alvarez";
  let i = 0;
  const speed = 150; // typing speed in ms
  
  function typeWriter() {
    if (i < text.length) {
      document.getElementById("typewriter").innerHTML += text.charAt(i);
      i++;
      setTimeout(typeWriter, speed);
    } else {
      // Once typing is complete, keep the cursor blinking
      document.querySelector('.cursor').style.animation = 'blink 1s infinite';
    }
  }
  
  // Start the typewriter effect when the page loads
  window.onload = function() {
    typeWriter();
  };
</script>

<!--
**brrrrdy/brrrrdy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
