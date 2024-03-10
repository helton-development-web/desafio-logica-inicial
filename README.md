<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classificador de Nível de Herói</title>
</head>
<body>
    <script>
        let nome = prompt("Digite o nome do Herói!")
        let qtdeXp = prompt("Digite a quantidade de experiência do seu Herói!");

        if (qtdeXp <= 1000){
            document.write("O Herói de nome " + nome + "está no nível de Ferro!");
        }
        else if (qtdeXp >= 1001 && qtdeXp <=2000){
            document.write("O Herói de nome " + nome + "está no nível de Bronze!");
        }
        else if (qtdeXp >= 2001 && qtdeXp <=5000){
            document.write("O Herói de nome " + nome + "está no nível de Prata!");
        }
        else if (qtdeXp >= 5001 && qtdeXp <=7000){
            document.write("O Herói de nome " + nome + "está no nível de Ouro!");
        }
        else if (qtdeXp >= 7001 && qtdeXp <=8000){
            document.write("O Herói de nome " + nome + "está no nível de Platina!");
        }
        else if (qtdeXp >= 8001 && qtdeXp <=9000){
            document.write("O Herói de nome " + nome + "está no nível de Ascendente!");
        }
        else if (qtdeXp >= 9001 && qtdeXp <=10000){
            document.write("O Herói de nome " + nome + "está no nível de Imortal!");
        }
        else if (qtdeXp >= 10001){
            document.write("O Herói de nome " + nome + "está no nível de Radiante!");
        }
    </script>
    
</body>
</html>
