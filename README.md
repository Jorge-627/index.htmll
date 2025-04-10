# index.htmll<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 2px solid black;
            padding: 10px;
            text-align: center;
        }
        .capa1 {
            background-color: pink;
            padding: 20px;
            margin: 10px;
        }
        .capa2 {
            background-color: yellow;
            padding: 20px;
            margin: 10px;
        }
        .capa3 {
            background-color: cyan;
            padding: 20px;
            margin: 10px;
        }
    </style>
</head>
<body>

    <h1>Ejemplo de Tabla en HTML</h1>
    
    <table>
        <tr>
            <th>Encabezado 1</th>
            <th>Encabezado 2</th>
            <th>Encabezado 3</th>
        </tr>
        <tr>
            <td>Celda 1</td>
            <td>Celda 2</td>
            <td>Celda 3</td>
        </tr>
        <tr>
            <td>Celda 4</td>
            <td>Celda 5</td>
            <td>Celda 6</td>
        </tr>
    </table>

    <h2>Ejemplo de Capas (`div`) con Colores</h2>
    
    <div class="capa1">Esta es una capa con fondo rosado.</div>
    <div class="capa2">Esta es una capa con fondo amarillo.</div>
    <div class="capa3">Esta es una capa con fondo cian.</div>

</body>
</html>
