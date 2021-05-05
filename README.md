<! DOCTYPE html >
< html >
< cabeza >
    < meta  conjunto de caracteres = ' utf-8 ' >
    < meta  http-equiv = ' X-UA-Compatible ' content = ' IE = edge ' >
    < título > Hola </ título >
    < meta  name = ' viewport ' content = ' width = device-width, initial-scale = 1 ' >
    < estilo >
        cuerpo {
            color de fondo : coral;
        }
    </ estilo >
    < guión >
        function  accionParaCuandoEllaDigaQueSi ( ) {
            alert ( 'Es broma amor, pero si quieres no es broma <3 Solo queria decirte lo mucho que te amo y que hoy cumplimos 3 meses, eres lo mejor que me paso en mi corta y miserable vida, tambien te pido perdón perd por ser tan yo, osea quien puede aguantarme tanto tiempo? Creo que solo tu por eso te amo y no me gustaria que cambies nunca sabes que me enamore de tu forma especial de ser, yo se que a veces te sientes miserable al igual que yo, bueno en ? Este mundo, quien no es El Punto Que Siempre estare para ti Nunca lo olvides Perdón si esperabas otra cosa Pero lo unico Que se me ocurrio FUE ESTO: c'. ) ;
        }

        function  mueveElBoton ( ) {
            ancho  =  ventana . innerWidth ;
            altura  =  ventana . innerHeight ;

            newWidth  =  ( Matemáticas . aleatorio ( )  *  ancho ) ;
            newHeight  =  ( Matemáticas . aleatorio ( )  *  altura ) ;

            documento . getElementById ( 'btnNo' ) . estilo . posición  =  "absoluta" ;
            documento . getElementById ( 'btnNo' ) . estilo . left  =  newWidth  +  "px" ;
            documento . getElementById ( 'btnNo' ) . estilo . top  =  newHeight  +  "px" ;
            

        }
    </ script >
</ cabeza >
< cuerpo >
    < h1 > ¿ Puedes sentarte en mi cara? </ h1 >
    < input  type = " button " onclick = " accionParaCuandoEllaDigaQueSi () " id = " btnSi " value = " Si " />
    < input  type = " button " id = " btnNo " onmouseover = " mueveElBoton () " value = " No " />
    < h4 > < img  src = " finn.jpg " > </ h4 >
</ cuerpo >
</ html >
