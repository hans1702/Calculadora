# Calculadora
Clase-05-07
<!DOCTYPE html>
<head>
    <link href="calcu.css" rel="stylesheet"/>
</head>
<body>
<div>
    <div class="page">
        <div class="calculator">
        <div class="display">
            <label>224 + 11=</label>
            <h2>235</h2>
        </div>
        <div class="m-buttons">
            <button>MC</button>
            <button>MR</button>
            <button>M+</button>
            <button>M-</button>
            <button>MS</button>
            <button>M&downarrow;</button>
        </div>
        <div class="keyboard">
            <button>%</button>
            <button>CE</button>
            <button>C</button>
            <button>&larr;</button>
            <button>1/x</button>
            <button>x<sup>2</sup></button>
            <button><sup>2</sup>&Sqrt;x</button>
            <button>&#247;</button>
            <button>7</button>
            <button>8</button>
            <button>9</button>
            <button>&times;</button>
            <button>4</button>
            <button>5</button>
            <button>6</button>
            <button>&minus;</button>
            <button>1</button>
            <button>2</button>
            <button>3</button>
            <button>&plus;</button>
            <button>&plus;/&minus;</button>
            <button>0</button>
            <button>.</button>
            <button id="igual">=</button>
        </div>
        </div>
    </div>
</div>
</body>

////////////////Estilos CSS////////////////////////////////
*{
    box-sizing: border-box;
}

.m-buttons{
    display: grid;
    grid-template-columns: repeat(6,1fr);

}
.keyboard{
    display: grid;
    grid-template-columns: repeat(4,1fr);
}
.display{
    border: 1px solid black;
    text-align: right;

}
.page{
    display: flex;
    justify-content:right;
    align-items: center;
    padding-top: 2rem;
    padding-bottom: 2rem;
    padding-left: 2rem;
    padding-right: 2rem;
}

#igual{
    background-color: blue;
    border: none;
}
button{
    border: 1px solid black;
}
