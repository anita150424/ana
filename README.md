<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bai+Jamjuree:ital,wght@0,200;0,300;0,400;0,500;0,600;0,700;1,200;1,300;1,400;1,500;1,600;1,700&display=swap" rel="stylesheet">
    <title>O Espelho do Sotão</title>

<body>
    <main>
        <div class="passo ativo" id="passo-0">
            <img src="img/cenario-passo0.png" alt="">
            <p> Clara, uma jovem estudante de história, herda a casa antiga de sua avó que recentemente faleceu. Entre as coisas da avó, ela encontra um antigo espelho com uma moldura de madeira intricada. Ela decide colocá-lo no sótão para restaurar mais tarde.</p>
            <button class="btn-proximo" data-proximo="1"></button>
            <button class="btn-proximo" data-proximo="2">O primeiro Sinal</button>
        </div>
        <div class="passo" id="passo-1">
            <p>Durante a noite, Clara ouve um sussurro vindo do sótão. A voz é suave, quase como um lamento. Assustada, ela sobe para verificar, mas encontra apenas o espelho coberto por um lenço empoeirado e tudo parece normal. </p>
            <button class="btn-proximo" data-proximo="3">Mexer no espelho</button>
            <button class="btn-proximo" data-proximo="4">Desistir e voltar para baixo</button>
        </div>
        <div class="passo" id="passo-2">
            <p> No dia seguinte, Clara limpa o espelho e nota algo estranho. No vidro, há uma mensagem escrita com o que parece ser poeira ou sujeira: “A verdade está refletida.” Ela limpa o espelho, mas a mensagem desaparece. Intrigada, ela decide investigar.</p>
            <button class="btn-proximo" data-proximo="5">Investigar</button>
            <button class="btn-proximo" data-proximo="6"></button>
        </div>
        <div class="passo" id="passo-3">
            <p>Clara começa a ter pesadelos frequentes com o espelho. Em seus sonhos, o espelho reflete imagens de lugares e pessoas que ela nunca viu antes. Cada vez que ela acorda, sente uma presença inquietante em sua casa. </p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-4">
            <img src="img/cenario-passo4-voltar-casa.png" alt="imagem voltando para casa e desitindo da aventura">
            <p>Você decide que a aventura é grande demais e volta para casa, mas sempre se pergunta o que teria
                encontrado.</p>
        </div>

        <div class="passo" id="passo-5">
            <p>Nas igrejas de Olinda, você descobre um mapa antigo escondido atrás de um altar, apontando que a próxima
                pista está no Amazonas.</p>
            <button class="btn-proximo" data-proximo="7">Viajar para o Amazonas</button>
        </div>

        <div class="passo" id="passo-6">
            <p>Explorando as praias, você encontra uma caverna escondida, mas ela leva a um beco sem saída.</p>
            <button class="btn-proximo" data-proximo="8">Voltar e explorar as igrejas</button>
        </div>

        <div class="passo" id="passo-7">
            <p>No Amazonas, a busca pela cidade perdida se intensifica. Você se depara com um rio bifurcado.</p>
            <button class="btn-proximo" data-proximo="9">Seguir pelo rio à esquerda</button>
            <button class="btn-proximo" data-proximo="10">Seguir pelo rio à direita</button>
        </div>

        <div class="passo" id="passo-8">
            <p>De volta às igrejas, você finalmente encontra o mapa antigo. Agora, para o Amazonas!</p>
            <button class="btn-proximo" data-proximo="7">Seguir para o Amazonas</button>
        </div>

        <div class="passo" id="passo-9">
            <p>O rio à esquerda leva você a uma cachoeira escondida com inscrições antigas que revelam a entrada da
                cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>

        <div class="passo" id="passo-10">
            <p>O rio à direita termina em uma área pantanosa. Apesar de belas vistas, não há sinais da cidade perdida
                aqui.</p>
            <button class="btn-proximo" data-proximo="12">Retornar e tentar o outro rio</button>
        </div>

        <div class="passo" id="passo-11">
            <img src="img/cenario-passo11-cidade-perdida.png" alt="encontrando uma cidade maravilhosa perdida no Amazonas">
            <p>Dentro da cidade perdida, você descobre tesouros inimagináveis e decide se dedicar a estudar e preservar
                este lugar</p>
        </div>

        <div class="passo" id="passo-12">
            <p>Retornando e escolhendo o rio à esquerda, você finalmente encontra a cachoeira escondida e as inscrições
                que levam à cidade perdida.</p>
            <button class="btn-proximo" data-proximo="11">Explorar a cidade perdida</button>
        </div>
    </main>
    <script src="script.js"></script>
</body>
</html>
