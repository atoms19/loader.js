# loader.js
Loading made easy

<!DOCTYPE html>

<html>

    <head>

        <title>Page Title</title>

         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet"></link>

<script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>

<script src="https://rawcdn.githack.com/atoms19/loader.js/fb74704034a53a023445ac9514940ee0fd6c001f/Mainloader.js">

    

</script>

 <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.15.8/styles/tomorrow-night.min.css">

     <!--Syntax Highliter JS Link-->

<script src="https://cdnjs.cloudflare.com/ajax/libs/highlight.js/9.15.8/highlight.min.js"></script>

<style>

    body {

    

}

code{

    border-radius:5px;

    font-size:16px;

    text-align:left;

}

</style>

<script>

    function lop(){

    lod=new Loader("red",15,"white")

    

    lod.activate()

    lod.animation="ease-out"

    lod.time=1

    document.getElementById("try").style.display ="none"

    lod.closeCountDown(3000)

}

/*built by atomic wave

copying this  code might get you arrested because i have copyrighted the content in terms

-for public use

*/

</script>

    </head>

    <body>

     

    <script>

         

    </script>   

        <nav class="nav-wrapper black"><div class="container">

           <a class="brand-logo purple-text text-lighten-4 ">loader.js</a> </div>

        </nav>

        <img src="https://media.istockphoto.com/photos/loading-icon-rolling-on-video-in-an-online-movie-streaming-service-picture-id873384592?k=6&m=873384592&s=612x612&w=0&h=hYi25qEWpQKjUFzKWiwZZh18bQ9sbSpvWLouO32pws0=" alt="‏‏‎ ‎" width="100%">

        <h1 class="container">loading made easier </h1>

        <p class=container>loader.js is a simple js library that can let you make your own loading screen and implement it easily

        

        <button class="btn purple accent-4 waves-effect waves-light pulse" onclick="lop()" id="try">try it out</button></p>

        

    <div class="container">

    <div class="divider"></div>

    <h3>getting the library</h3>

    <p>you can get the library by copying and pasting this inside the script tag as the source(src)</p>

    <pre class=>

        <code>

"https://rawcdn.githack.com/atoms19/loader.js/fb74704034a53a023445ac9514940ee0fd6c001f/Mainloader.js"

        </code>

    </pre>

    

    <div class="divider"></div>

    

    <h3>how to use</h3>  

    <p>first make a new loader object call the activate method and done loader is ready</p> 

        <pre>

            <code>

var lod=new Loader("red",5,"white")

lod.activate() 

            </code>

        </pre>

        after doing all this code we get a proper working loader 

        with red color 5px  thickness and white backdrop 

        <strong class="red-text">but there is a problem loader never stops</strong>

        <div class=divider></div>

        <h4>stopping the loader</h4>

        <p>to stop the loader all we need to do is call this method

         </p>

         <pre>

             <code>

lod.closeWhenDone()

             </code>

         </pre>

        this will automatically close the loader after the page is fully loaded<br>

        <b class="orange-text text-darken-3">note:dont use this method for short codes it must be used for codes that takes some time to load like a canvas or a 3d code</b>

<h5>closeCountDown</h5>

<p>closeCountDown is another method that can be used to stop the loader it stops the loader after a specified amount of time .It takes in one parametere that is the time in milliseconds</p>

<pre>

    <code>

lod.closeCountDown(5000)

    </code>

</pre> 

<p>this code above will  stop the loader after 5 seconds(1 sec=1000ms)<br>

<b class="green-text accent-3">note:this method can be used in codes with shorter loading time too</b>

</p>       

        

        <div class="divider"></div>

        <h4>more controls</h4>

        <p>you can control the speed of the loader by changing the time property you can also change the animation from linear to ease-in/ease-out by changing the animation property and also you can change the size property to change the size of the loader</p>

        <pre>

            <code>

lod.time=5               

lod.animation="ease-in"

lod.size=180

            </code>

        </pre>

        <div class="divider"></div>

        <h4>example codes</h4>

        <p>here are some examples for the loader.js</p>    

         <ul class="collection">

            <li class="collection-item"><i class="material-icons left blue-text">link</i><a href="https://code.sololearn.com/WHjdK84g0jn8/?ref=app">example code 1</a></li> 

             <li class="collection-item"><i class="material-icons left blue-text">link</i><a href="https://code.sololearn.com/W3mOYEqu5KIq/?ref=app">example code 2</a></li> 

 

 <li class="collection-item"><i class="material-icons left blue-text">link</i><a href="https://code.sololearn.com/WoB4lGeMk5JI/?ref=app">example code 3</a></li>  

              

             

         </ul>   

            

            

            

        </div>

        <footer class="page-footer purple accent-4">

            <div class=footer-copyrights>

        <div class="container"> © 2020 Copyright Text <a class="grey-text text-lighten-4 right" href="https://www.sololearn.com/Profile/15464694/?ref=app">follow me?</a> </div>

            </div>

        </footer>

        

        

        <script>

           hljs.initHighlightingOnLoad(); 

        </script>

    </body>

</html>
