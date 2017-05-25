# primeiro
Primeiro repositório para testar a plataforma!


<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<link rel="stylesheet" type="text/css" href="_css/estilo_mago.css"/>
<script type="text/javascript">
	function escolherMago() {
	var desafiante= document.getElementById("mago1");
	var desafiado= document.getElementById("mago2");
	}	
</script>

	<title>Duelo de Magos</title>
</head>
<body>

	<h1>DUELO DE MAGOS!!!</h1>


	<section id="selecao">
	<article id="intomagos">
		<header id="cabecalho">
			<hgroup>				
				<h2>Selecione seu Mago</h2>
				<h3 class="direita">Desenvolvido por MrldTecnology</h3>
			</hgroup>	
		</header>

	<p><h3>Veja na nossa galeria de Magos e suas várias características, todos eles podem usar magias de fogo, eletricidade, de cura e a mais letal das magias, a magia Negra! Esses grandes Magos estão impressionando o mundo inteiro. Basta passar o mouse sobre uma das fotos para ver uma versão ampliada e com uma breve descrição.</h3></p>
<form id="selecionamago" method="post"  action="duelo_mago.php" oninput="escolherMago();">
<ul id="album-fotos">
	<li id="m"><img name="mago1" src="./_imagens/m1.jpg" value="Eldron"><span>Eldron, O Mistico.</span></li>
	<li id="m"><img name="mago2" src="./_imagens/m2.jpg" value="Melina"><span>Melina, A Impiedosa.</span></li>
	<li id="m"><img name="mago3" src="./_imagens/m3.jpg" value="Saref"><span>Saref, O Alquimista.</span></li>
	<li id="m"><img name="mago4" src="./_imagens/m4.jpg" value="Lilah"><span>Lilah, A Encantadora.</span></li>
</ul>


	 <p><label for="mago1"><h1>Desafiante: </h1></label>
        <select name="magodesafiante" id="mago1">
            <option>Eldron, O Mistico</option>
            <option>Melina, A Impiedosa</option>
            <option>Saref, O Alquimista</option>
            <option>Lilah, A Encantadora</option>
        </select></p>
    <p><label for="mago2"><h1>Desafiado: </h1></label>
        <select name="magodesafiado" id="mago2">
            <option>Eldron, O Mistico</option>
            <option>Melina, A Impiedosa</option>
            <option>Saref, O Alquimista</option>
            <option>Lilah, A Encantadora</option>
        </select></p>

        <p><input type="submit" nome="escMago" value="iniciar" class="btn btnazul"/></p>

</form>
	</article>
</section>




</body>
</html>
