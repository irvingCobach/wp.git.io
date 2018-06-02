<html><head>
		<title>Menu Desplegable</title>
		<body background="http://www.colores.org.es/imagenes_colores/rosa-bebe.jpg"> 
		<style type="text/css">
		
		.container {
      width: 210px;
      height: 140px;
      position: relative;
      margin: 0 auto 40px;
      border: 1px solid #CCC;
      -webkit-perspective: 1100px;
         -moz-perspective: 1100px;
              perspective: 1100px;

    }

    #carousel {
	width: 100%;
	height: 100%;
	position: absolute;
	-webkit-transform: translateZ( -288px );
	-moz-transform: translateZ( -288px );
	transform: translateZ( -288px );
	-webkit-transform-style: preserve-3d;
	-moz-transform-style: preserve-3d;
	transform-style: preserve-3d;
	-webkit-transition: -webkit-transform 1s;
	-moz-transition: -moz-transform 1s;
	transition: transform 1s;
	-webkit-animation: rotateInY 10s infinite linear;
	-moz-animation: rotateInY 10s infinite linear;
	animation: rotateInY 10s infinite linear;
	left: 14px;
	top: 59px;
    }

    #carousel figure {
      display: block;
      position: absolute;
      width: 90%;
      height: 100%;
      left: 10px;
      top: 300px;
      border: 2px solid rgba(   0, 0, 0, 0.8 );
      line-height: 116px;
      font-size: 80px;
      font-weight: bold;
      color: white;
      text-align: center;
      margin: 0;
    }

    #carousel figure:nth-child(1) { background: hsla(   0, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(2) { background: hsla(  40, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(3) { background: hsla(  80, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(4) { background: hsla( 120, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(5) { background: hsla( 160, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(6) { background: hsla( 200, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(7) { background: hsla( 240, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(8) { background: hsla( 280, 100%, 50%, 0.8 ); }
    #carousel figure:nth-child(9) { background: hsla( 320, 100%, 50%, 0.8 ); }

    #carousel figure:nth-child(1) {
      -webkit-transform: rotateY(   0deg ) translateZ( 288px );
         -moz-transform: rotateY(   0deg ) translateZ( 288px );
              transform: rotateY(   0deg ) translateZ( 288px );
			  
    }
    #carousel figure:nth-child(2) {
      -webkit-transform: rotateY(  40deg ) translateZ( 288px );
         -moz-transform: rotateY(  40deg ) translateZ( 288px );
              transform: rotateY(  40deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(3) {
      -webkit-transform: rotateY(  80deg ) translateZ( 288px );
         -moz-transform: rotateY(  80deg ) translateZ( 288px );
              transform: rotateY(  80deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(4) {
      -webkit-transform: rotateY( 120deg ) translateZ( 288px );
         -moz-transform: rotateY( 120deg ) translateZ( 288px );
              transform: rotateY( 120deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(5) {
      -webkit-transform: rotateY( 160deg ) translateZ( 288px );
         -moz-transform: rotateY( 160deg ) translateZ( 288px );
              transform: rotateY( 160deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(6) {
      -webkit-transform: rotateY( 200deg ) translateZ( 288px );
         -moz-transform: rotateY( 200deg ) translateZ( 288px );
              transform: rotateY( 200deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(7) {
      -webkit-transform: rotateY( 240deg ) translateZ( 288px );
         -moz-transform: rotateY( 240deg ) translateZ( 288px );
              transform: rotateY( 240deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(8) {
      -webkit-transform: rotateY( 280deg ) translateZ( 288px );
         -moz-transform: rotateY( 280deg ) translateZ( 288px );
              transform: rotateY( 280deg ) translateZ( 288px );
    }
    #carousel figure:nth-child(9) {
      -webkit-transform: rotateY( 320deg ) translateZ( 288px );
         -moz-transform: rotateY( 320deg ) translateZ( 288px );
              transform: rotateY( 320deg ) translateZ( 288px );
    }

    @keyframes rotateInY {
	0%   { transform: translateZ(-288px) rotateY(0deg);   }
	100% { transform: translateZ(-288px) rotateY(360deg);    }
    }

    @-webkit-keyframes rotateInY {
	0%   { -webkit-transform: -webkit-translateZ(-288px) rotateY(0deg);   }
	100% { -webkit-transform: -webkit-translateZ(-288px) rotateY(360deg);    }
    }

    @-moz-keyframes rotateInY {
	0%   { -moz-transform: -moz-translateZ(-288px) rotateY(0deg);   }
	100% { -moz-transform: -moz-translateZ(-288px) rotateY(360deg);    }
    }
			
			* {
				margin:0px;
				padding:0px;
			}
			
			#header {
			float:left;
				margin:auto;
				width:500px;
				font-family:Arial, Helvetica, sans-serif;
			}
			
			ul, ol {
				list-style:none;
			}
			
			.nav > li {
				float:left;
			}
			
			.nav li a {
				background-color:#000;
				color:#fff;
				text-decoration:none;
				padding:10px 12px;
				display:block;
			}
			
			.nav li a:hover {
				background-color:#43FF43;
			}
			
			.nav li ul {
				display:none;
				position:absolute;
				min-width:140px;
			}
			
			.nav li:hover > ul {
				display:block;
			}
			
			.nav li ul li {
				position:relative;
			}
			
			.nav li ul li ul {
				right:-140px;
				top:0px;
			}
			
		</style>
	</head>
<body>
    
<div id="header">
			<ul class="nav">
				<li><a href="file:///E|/trabajo de la pagina 5.html" tabindex="i" title="Inicio" accesskey="I" target="_parent">Inicio</a></li>
				
<li><a href="file:///E|/paginaaisha.html">Menú</a></li>
		  <li><a href="file:///E|/trabajo de la pagina 1.html">Galerìa</a>
					<ul>
						<li><a href="">Pastel</a></li>
					  <li><a href="">Malteada</a></li>
					</ul>
			  </li>
				<li><a href="file:///E|/contactosUntitled-2.html">Contacto</a></li>
			</ul>
</div>
	
    <div id="body">
    <p></p>
    <p></p>
    <p></p>
    <p></p>
    <p><img src="file:///E|/yoamocupcakes.png" width="525" height="255"></p>
    <p></p>
      <figure>
<div align="right"><img src="file:///E|/img carrusel/33965590_1700103296745537_8279473748592033792_n
    <p align="center"	>
   
    Body for HTML page
    </p>
</div>
   
    <div align="center"></div>

    
    <section class="container">
    <div id="carousel">
      <figure>
        <div align="center"><img src="file:///E|/img carrusel/1.jpg" alt="afuera" longdesc="img carrusel/1.jpg" widht="200" height="240" border="0"></a></div>

      </figure>
      <figure>
<div align="right">
<img src="file:///E|/img carrusel/2.jpg" alt="red" width="190" height="232" border="0" longdesc="img carrusel/2.jpg" widht="200"></a>
<div>
      </figure>
      <figure>
        <div align="right"><img src="file:///E|/img carrusel/3.jpg" alt="3" width="185" height="231" border="0" longdesc="img carrusel/3.jpg"widht="200"></a></div>
  </figure>
      <figure>
        <div align="right"><img src="file:///E|/img carrusel/4.jpg" alt="4" width="193" height="239" border="0" longdesc="img carrusel/4.jpg"widht="200"></a></div>
  </figure>
      <figure>
      <div align="right"><img src="file:///E|/img carrusel/5.jpg" alt="5" longdesc="img carrusel/5.jpg"widht="200" height="240" border="0"></a></div>
  </figure>
      <figure>
        <div align="right"><img src="file:///E|/img carrusel/6.jpg" alt="6" longdesc="img carrusel/6.jpg"widht="200" height="240" border="0"></a></div>
  </figure>
      <figure>
        <div align="right"><img src="file:///E|/img carrusel/7.jpg" alt="7" longdesc="img carrusel/7.jpg"widht="200" height="240" border="0"></a></div>
  </figure>
      <figure>
        <div align="right"><img src="file:///E|/img carrusel/8.jpg" alt="8" width="164" height="235" border="0" longdesc="img carrusel/8.jpg"widht="200"></a></div>
  </figure>
</div>
  </section>
   
</body>
</html>
