# flexbox
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exercícios de Flexbox</title>
    <style>
        /* Estilo para o Layout Básico (Exercício 1) */
        .container-layout {
            display: flex;
            flex-direction: row;
            justify-content: space-between;
            margin: 20px;
        }

        .column {
            flex: 1;
            background-color: lightblue;
            margin: 5px;
            padding: 20px;
            text-align: center;
            border: 1px solid #007BFF;
        }

        /* Estilo para o Alinhamento Vertical (Exercício 2) */
        .container-alinhamento {
            display: flex;
            height: 300px;
            align-items: center;
            margin: 20px;
            border: 1px solid #007BFF;
        }

        .item {
            flex: 1;
            background-color: lightcoral;
            margin: 5px;
            padding: 20px;
            text-align: center;
            border: 1px solid #FF4500;
        }

        .item.altura-alta {
            height: 100px;
        }

        .item.altura-media {
            height: 150px;
        }

        .item.altura-baixa {
            height: 50px;
        }
    </style>
</head>
<body>

    <h2>Exercício 1: Layout Básico</h2>
    <div class="container-layout">
        <div class="column">Coluna 1</div>
        <div class="column">Coluna 2</div>
        <div class="column">Coluna 3</div>
    </div>

    <h2>Exercício 2: Alinhamento Vertical</h2>
    <div class="container-alinhamento">
        <div class="item altura-alta">Item 1</div>
        <div class="item altura-media">Item 2</div>
        <div class="item altura-baixa">Item 3</div>
    </div>

</body>
</html>
