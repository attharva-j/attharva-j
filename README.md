<style>
  .me {
  display: block;
  margin: 2em auto;
  margin-bottom: 3em;
  width: 150px;
  height: 150px;
  border-radius: 50%;
  position: relative;
  z-index: 2;
}

.social {
  text-align: center;
  font-size: 2.5em;
  color: #555;
  overflow: hidden;

  a {
    color: inherit;
    text-decoration: none;
  }
  
  i {
    margin: .3em;
    cursor: pointer;
    transition: color 300ms ease, margin-top 300ms ease;
    transform: translateZ(0);
    
    &:hover {
      margin-top: -1px;
    }
    
    &#twitter:hover {
      color: #77DDF6;
    }

    &#github:hover {
      color: black;
    }

    &#linkedin:hover {
      color: #0177B5;
    }

    &#code:hover {
      color: #29A329;
    }

    &#stack:hover {
      color: #ED780E;
    }

    &#plus:hover {
      color: #D43402;
    }

    &#mail:hover {
      color: #F7B401;
    }
  }
}
</style>

<script>
  $(document).ready(function() {
  $('i').hide();
})

$(window).load(function() {
  $('i').show();

  var twitterPos = $('#twitter').position();
  var githubPos = $('#github').position();
  var stackPos = $('#stack').position();
  var linkedinPos = $('#linkedin').position();
  var codePos = $('#code').position();
  var plusPos = $('#plus').position();
  var mailPos = $('#mail').position();
  var imgPos = $('.me').position();
  
  $('i').css({
    position: 'absolute',
    zIndex: '1',
    top: imgPos.top + 100,
    left: '47%'
  });
  
  setTimeout(function() {
    $('#twitter').animate({
      top: twitterPos.top + 10,
      left: twitterPos.left - 10
    }, 500);
  }, 250);
  
  setTimeout(function() {
    $('#twitter').animate({
      top: twitterPos.top,
      left: twitterPos.left
    }, 250);
    
    $('#github').animate({
      top: githubPos.top + 10,
      left: githubPos.left - 6
    }, 500);
  }, 500);
  
  setTimeout(function() {
    $('#github').animate({
      top: githubPos.top,
      left: githubPos.left
    }, 250);
    
    $('#stack').animate({
      top: stackPos.top + 10,
      left: stackPos.left - 3
    }, 500);
  }, 750);
  
  setTimeout(function() {
    $('#stack').animate({
      top: stackPos.top,
      left: stackPos.left
    }, 250);
    
    $('#linkedin').animate({
      top: linkedinPos.top + 10,
      left: linkedinPos.left
    }, 500);
  }, 1000);
  
  setTimeout(function() {
    $('#linkedin').animate({
      top: linkedinPos.top,
      left: linkedinPos.left
    }, 250);
    
    $('#code').animate({
      top: codePos.top + 10,
      left: codePos.left + 3
    }, 500);
  }, 1250);
  
  setTimeout(function() {
    $('#code').animate({
      top: codePos.top,
      left: codePos.left
    }, 250);
    
    $('#plus').animate({
      top: plusPos.top + 10,
      left: plusPos.left + 6
    }, 500);
  }, 1500);
  
  setTimeout(function() {
    $('#plus').animate({
      top: plusPos.top,
      left: plusPos.left
    }, 250);
    
    $('#mail').animate({
      top: mailPos.top + 10,
      left: mailPos.left + 10
    }, 500);
  }, 1750);
  
  setTimeout(function() {
    $('#mail').animate({
      top: mailPos.top,
      left: mailPos.left
    }, 250);
  }, 2000);
  
})
</script>

<h2 align='center'>Hi there 👋</h2>
<p align='center'>Welcome to my GitHub page. I am a data science professional 3 years of experience and a passion to solve problems in a data-driven manner.</p>

<div id="header" align="center">
  <!-- <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/> -->
  <img class="me" src="http://gravatar.com/avatar/25b1fc64ba12614875c1e467d7e4c86e?s=512" alt="" />
</div>

<div class="social">
  <a href="https://twitter.com/bphillips201"><i id="twitter" class="icon-twitter"></i></a>
  <i id="github" class="icon-github"></i>
  <i id="stack" class="icon-stackexchange"></i>
  <i id="linkedin" class="icon-linkedin-sign"></i>
  <i id="code" class="icon-code"></i>
  <i id="plus" class="icon-google-plus-sign"></i>
  <i id="mail" class="icon-envelope"></i> 
</div>
<!--
**attharva-j/attharva-j** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
