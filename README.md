# Beginner-at-Javascript
<!DOCTYPE html>
<html>
	<head>
		<title>Exercício proposto</title>
		<meta chatset="UTF-8">
	</head>
	<body>
		<script>
			var n1 = parseInt(prompt("Digite um número para o jogador 1:"));
			var n2 = parseInt(prompt("Digite um número para o jogador 2:"));
			var sorteio = parseInt(Math.random()*2);
			alert("Número sorteado é: " + sorteio);

			if((sorteio === 0 && n1 < n2) || (sorteio === 1 && n1 > n2)){
				alert("Jogador número 1 ganhou.");
			}
			else
			{
				alert("Jogador número 2 ganhou.");
			}
		
		</script>
	</body>
</html>
