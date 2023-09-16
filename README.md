Cores : #f5c62f

Textos :     font-family: "Roboto", Sans-serif;
    font-size: 14px;
    font-weight: 600;
    text-transform: uppercase;

img relogio:
    width = 1300
    height 650
Header:
    z-index: 99;
    position: relative;
    display: block;
Navbar :
    color: #CB9C06;
    fill: #CB9C06;
    padding-left: 37px;
    padding-right: 37px;
    padding-top: 10px;
    padding-bottom: 10px;


relogio animado :
.container {
    display: block;
    align-items: center;
    justify-content: center;
    position: relative;
    width: 80%;/* Largura do campo */
    height: 650px; /* Altura do campo */
    overflow: hidden;
}

.animated-image {
    align-items: center;
    justify-content: center;
    display: inline-block;
    position: relative;
    width: 80%;
    z-index: 100;
    animation: moveUpDown 5s ;
    margin: 0 auto;
}
@keyframes moveUpDown {
    50% {
        transform: translateY(+50%);
    }
    100% {
        transform: translateY(-50%); /* Isso fará a imagem subir */
    }
}