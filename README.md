<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sustentabilidade na Agricultura</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Segoe UI', sans-serif;
}

body{
    background:#f4f8f4;
    color:#333;
}

header{
    background:linear-gradient(135deg,#2e7d32,#66bb6a);
    color:white;
    text-align:center;
    padding:40px 20px;
}

header h1{
    font-size:3rem;
    margin-bottom:10px;
}

header p{
    max-width:900px;
    margin:auto;
    line-height:1.6;
}

nav{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    background:#1b5e20;
}

nav button{
    border:none;
    background:none;
    color:white;
    padding:18px 25px;
    cursor:pointer;
    font-size:1rem;
    transition:.3s;
}

nav button:hover{
    background:#43a047;
}

.section{
    display:none;
    padding:50px;
    animation:fade .5s ease;
}

.section.active{
    display:block;
}

@keyframes fade{
    from{
        opacity:0;
        transform:translateY(20px);
    }
    to{
        opacity:1;
        transform:translateY(0);
    }
}

.hero-card{
    background:white;
    padding:30px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    margin-bottom:30px;
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 4px 12px rgba(0,0,0,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#2e7d32;
    margin-bottom:15px;
}

.highlight{
    color:#1b5e20;
    font-weight:bold;
}

footer{
    background:#1b5e20;
    color:white;
    text-align:center;
    padding:20px;
    margin-top:30px;
}

ul{
    padding-left:20px;
}

li{
    margin-bottom:8px;
}

@media(max-width:768px){
    .section{
        padding:25px;
    }

    header h1{
        font-size:2rem;
    }
}
</style>
</head>
<body>

<header>
    <h1>🌱 Sustentabilidade na Agricultura</h1>
    <p>
        A agricultura sustentável busca produzir alimentos de forma eficiente,
        preservando os recursos naturais para as futuras gerações. Ela combina
        tecnologia, conservação ambiental, bem-estar animal e gestão inteligente
        dos recursos hídricos.
    </p>
</header>

<nav>
    <button onclick="mostrarSecao('inicio')">Início</button>
    <button onclick="mostrarSecao('hidrica')">Rios e Recursos Hídricos</button>
    <button onclick="mostrarSecao('biomas')">Biomas e Meio Ambiente</button>
    <button onclick="mostrarSecao('animais')">Animais</button>
</nav>

<!-- INÍCIO -->
<section id="inicio" class="section active">

    <div class="hero-card">
        <h2>Visão Geral</h2>
        <br>
        <p>
            A sustentabilidade agrícola é fundamental para garantir a segurança
            alimentar mundial sem comprometer os recursos naturais.
            Atualmente, diversas técnicas permitem aumentar a produtividade
            reduzindo impactos ambientais.
        </p>
    </div>

    <div class="cards">
        <div class="card">
            <h3>💧 Gestão da Água</h3>
            <p>
                Uso racional dos recursos hídricos, irrigação eficiente e
                preservação das nascentes.
            </p>
        </div>

        <div class="card">
            <h3>🌳 Conservação Ambiental</h3>
            <p>
                Proteção dos solos, florestas e biomas naturais por meio de
                práticas agrícolas sustentáveis.
            </p>
        </div>

        <div class="card">
            <h3>🐄 Bem-Estar Animal</h3>
            <p>
                Criação responsável, redução do estresse e melhoria das
                condições de vida dos animais.
            </p>
        </div>
    </div>

</section>

<!-- HIDRICA -->
<section id="hidrica" class="section">

    <div class="hero-card">
        <h2>💧 Sustentabilidade dos Rios e Recursos Hídricos</h2>
        <br>
        <p>
            A água é um dos recursos mais importantes para a agricultura.
            A sustentabilidade hídrica busca garantir que rios, lagos,
            aquíferos e nascentes sejam preservados.
        </p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Irrigação Inteligente</h3>
            <ul>
                <li>Sensores de umidade do solo.</li>
                <li>Redução do desperdício de água.</li>
                <li>Monitoramento em tempo real.</li>
                <li>Maior produtividade agrícola.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Proteção de Nascentes</h3>
            <ul>
                <li>Recuperação de matas ciliares.</li>
                <li>Redução da erosão.</li>
                <li>Melhoria da qualidade da água.</li>
                <li>Preservação dos ecossistemas aquáticos.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Controle da Poluição</h3>
            <ul>
                <li>Menor uso de produtos químicos.</li>
                <li>Tratamento de resíduos agrícolas.</li>
                <li>Proteção dos rios contra contaminação.</li>
                <li>Redução do assoreamento.</li>
            </ul>
        </div>

    </div>

</section>

<!-- BIOMAS -->
<section id="biomas" class="section">

    <div class="hero-card">
        <h2>🌳 Sustentabilidade para Biomas e Meio Ambiente</h2>
        <br>
        <p>
            A agricultura moderna deve coexistir com os ecossistemas naturais,
            preservando a biodiversidade e reduzindo impactos ambientais.
        </p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Conservação do Solo</h3>
            <ul>
                <li>Plantio direto.</li>
                <li>Rotação de culturas.</li>
                <li>Redução da erosão.</li>
                <li>Maior fertilidade natural.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Preservação dos Biomas</h3>
            <ul>
                <li>Proteção de áreas nativas.</li>
                <li>Recuperação de vegetação degradada.</li>
                <li>Criação de corredores ecológicos.</li>
                <li>Conservação da biodiversidade.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Redução de Emissões</h3>
            <ul>
                <li>Uso eficiente de máquinas.</li>
                <li>Energias renováveis.</li>
                <li>Captura de carbono no solo.</li>
                <li>Menor impacto climático.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Agricultura de Precisão</h3>
            <ul>
                <li>Uso de drones.</li>
                <li>Mapeamento por satélite.</li>
                <li>Aplicação exata de insumos.</li>
                <li>Menos desperdício.</li>
            </ul>
        </div>

    </div>

</section>

<!-- ANIMAIS -->
<section id="animais" class="section">

    <div class="hero-card">
        <h2>🐄 Sustentabilidade para os Animais</h2>
        <br>
        <p>
            O bem-estar animal tornou-se uma prioridade na agricultura sustentável.
            Animais saudáveis produzem melhor e vivem em condições mais adequadas.
        </p>
    </div>

    <div class="cards">

        <div class="card">
            <h3>Bem-Estar Animal</h3>
            <ul>
                <li>Espaço adequado.</li>
                <li>Menor estresse.</li>
                <li>Alimentação balanceada.</li>
                <li>Ambiente confortável.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Saúde Preventiva</h3>
            <ul>
                <li>Monitoramento constante.</li>
                <li>Vacinação adequada.</li>
                <li>Menor incidência de doenças.</li>
                <li>Maior longevidade.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Sistemas Integrados</h3>
            <ul>
                <li>Integração lavoura-pecuária.</li>
                <li>Pastagens mais produtivas.</li>
                <li>Melhor aproveitamento da terra.</li>
                <li>Redução de impactos ambientais.</li>
            </ul>
        </div>

        <div class="card">
            <h3>Proteção da Fauna Silvestre</h3>
            <ul>
                <li>Preservação de habitats.</li>
                <li>Corredores ecológicos.</li>
                <li>Menor fragmentação ambiental.</li>
                <li>Conservação das espécies.</li>
            </ul>
        </div>

    </div>

</section>

<footer>
    <p>
        Sustentabilidade na Agricultura © 2026 |
        Produção responsável para um futuro sustentável.
    </p>
</footer>

<script>
function mostrarSecao(secao){

    const secoes = document.querySelectorAll('.section');

    secoes.forEach(item=>{
        item.classList.remove('active');
    });

    document.getElementById(secao).classList.add('active');
}
</script>

</body>
</html>
