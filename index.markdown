---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---


<!DOCTYPE html>

<html>
    <head>
        <style>
            #cf3 {
    position:relative;
    height:448px;
    width:400px;
    margin:0 auto;

  }

div {
    display: block;
    margin: 5px;
}

#content {
    margin: 1%;
    position: relative;
    top: 10px;
}

#caption {
    text-align: center;
    position: relative;

}

#byline {
    text-align: center;
    text-decoration: bold;
    font-size: 1.5em;
}

h1 {
    text-align: center;
}
  
#cf3 img {
    max-width: 400px;

    margin-bottom: -500px;

    position:absolute;
    left:0;

    z-index: -1;
  }

  

  @keyframes cf3FadeInOut {
    0% {
      opacity:1;
    }
    17% {
      opacity:1;
    }
    25% {
      opacity:0;
    }
    92% {
      opacity:0;
    }
    100% {
      opacity:1;
    }
  }



  #cf3 img.top {
    animation-name: cf3FadeInOut;
    animation-timing-function: ease-in-out;
    animation-iteration-count: infinite;
    animation-duration: 12s;
    animation-direction: normal;
    }


  
  #cf3 img:nth-of-type(1) {
    animation-delay: 6s;
  }
  #cf3 img:nth-of-type(2) {
    animation-delay: 4s;
  }
  #cf3 img:nth-of-type(3) {
    animation-delay: 2s;
  }
  #cf3 img:nth-of-type(4) {
    animation-delay: 0;
  }
        </style>
    </head>
    <body>
        <h1>Why are we so paranoid?</h1>
        <div id="byline">A recording of a classroom dialogue featuring Roy Kiyooka</div>
            <div id="cf3">
                <img class="top" src="https://user-images.githubusercontent.com/119261903/228941767-3755d1ed-9591-4043-bb5e-76e417ed5e36.jpeg" />
                <img class="top" src="https://user-images.githubusercontent.com/119261903/228941765-e05b996a-2266-4e0c-8887-22bb1d8ffe7f.jpeg" />
                <img class="top" src="https://user-images.githubusercontent.com/119261903/228941763-278f122d-3bd0-4800-b4b8-ffab9fbf72cd.jpeg" />
                <img class="top" src="https://user-images.githubusercontent.com/119261903/228941756-cd97d268-24ce-4131-87e7-47c5e2f57614.jpeg" />
            </div>
            <div id="caption">
                <h3>Jaques Lacan's <i>Schema-L</i> and Gilles Deleuze and Felix Guattari's connective synthesis of production</h3>
            </div>
            <div id="content">
            <tr>
            <p>
        This recording demonstrates how paranoia 'blots out' or restricts libidinal relationships. 
            </p>
            </div>
        </body>
</html>
