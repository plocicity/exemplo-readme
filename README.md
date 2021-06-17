# exemplo-readme
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		
		<title>TutsUP - Layout Responsivo</title>
		
		<style>
		body, html{
			margin:0;
			padding:0;
		}
		.main{
			max-width:1200px;
			margin:0 auto;
			overflow:hidden;
			background:lightgray;
		}
		.content{
			float:left;
			width:100%;
			margin-right:-210px;
		}
		.content-inner{
			margin-right:210px;
		}
		.sidebar{
			background:red;
			float:right;
			width:200px;
		}
		.menu{
			width:100%;
			background:blue;
		}
		.menu ul{
			margin:0; 
			padding:0;
		}
		.menu ul li{
			display:inline-block;
			*display:inline;
			zoom:1;
			margin:0; 
			padding:0;
		}
		.menu ul li a{
			display:block;
			padding:20px;
			color:#fff;
		}
		.footer{
			width:100%;
			background:yellow;
			text-align:center;
		}
		
		@media screen and (max-width: 700px) {
			.sidebar, .content-inner, .content{
				float: none;
				width: 100%;
				margin-right:0;


                
                
			}
		}
		</style>
		</head>
	<body>
		<div class="main">
			<div class="menu">
				<ul>
					
                    <a href="https://www.bahianoticias.com.br/"><button>noticias </button></a>
					
				</ul>
			</div>
			<div class="content">
			
                <a href="https://www.bahianoticias.com.br/curtas-e-venenosas.html"><button>informacoes </button></a>
					
				
			</div>
			<div class="sidebar">
			 noticias de hoje
			</div>
			
			<br style="clear:both">
			
			<div class="footer">
			<a href="https://www.bahianoticias.com.br/	">forum</a>
			</div>
		</div>
        <img src="download.png" alt="download.png">>
        <img src="cropped-LOGO-NOTCIAS-DE-SALVADOR-3.png" alt="logo">
           
        
        <style>
            body{
                background-color: burlywood;
               
            }
        </style>
	</body>
</html>
