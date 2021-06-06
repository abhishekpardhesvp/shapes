<html>

<head>

<title>Shape</title>

<style>

#s {

         width: 250px;

         height: 250px;

         background: linear-gradient( to left,#ff0066 50%,#00ccff 100%);

         } 

#r {

         width: 350px;

         height: 150px;

         background: linear-gradient( to left,#ff0066 50%,#00ccff 100%);

         } 

#r1 {

         width: 150px;

         height: 350px;

         background: linear-gradient( to left,#ff0066 50%,#00ccff 100%);

         } 

#c {

         width: 250px;

         height: 250px;

         border-radius: 50%;

         background: linear-gradient( to left,#ff0066 50%,#00ccff 100%);

         } 

#ut {

         width: 0px;

         height: 0px;

         border-left: 150px solid transparent;

         border-right: 150px solid transparent;

         border-bottom: 150px solid pink;

         }

#dt {

         width: 0px;

         height: 0px;

         border-left: 150px solid transparent;

         border-right: 150px solid transparent;

         border-top: 150px solid pink;

         }

#rt {

         width: 0px;

         height: 0px;

         border-left: 200px solid transparent;

         border-top: 200px solid transparent;

         border-right: 200px solid pink;

         } 

#lt {

         width: 0px;

         height: 0px;

         border-right: 200px solid transparent;

         border-top: 200px solid transparent;

         border-left: 200px solid pink;

         }

#st {

         width: 0px;

         height: 0px;

         border-left: 150px solid transparent;

         border-right: 150px solid transparent;

         border-bottom: 150px solid pink;

         position: absolute;

         }

#st:after {

                width: 0px;

                height: 0px;

                border-left: 150px solid transparent;

                border-right: 150px solid transparent;

               border-top: 150px solid pink;

               position: absolute;

               top: 50px;

               content: " ";

               left: -150px;

               }

#h {

       width: 100px;

       height: 100px;

       position: relative;

       transform: rotate(-35deg);

      }

#h:before,#h:after { 

                                 width: 50px;

                                 height: 80px;

                                 background: linear-gradient( to left,#ff0066 50%,#00ccff 100%);

                                 transfor:rotate(60deg);

                                 transform-origin: 0 100%;

                                 transform:radius: 90px 90px 0 0;

                                 border-radius:50px 50px 0 0;

                                 position: absolute;

                                 top: 380px;

                                 content: " ";

                                 left: 80px;    

                                 }

#h:after {

                transform: rotate(90deg);

                transform-origin: 0% 38%;

                left: 130px ;

                }

</style>

</head>

<body>

<div id="s"></div></br>

<div id="r"></div></br>

<div id="r1"></div></br>

<div id="c"></div></br>

<div id="ut"></div></br>

<div id="dt"></div></br>

<div id="rt"></div></br>

<div id="lt"></div></br>

<div id="st"></div></br>

<div id="h"></div></br>

</body

</html>
