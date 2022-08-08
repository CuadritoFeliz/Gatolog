# OSDev
Creado por OSdevelop
*¿Cansado de ocupar , console.log , console.error, etc?* **Aca te traemos osdev, logea LO QUE SEA con tan solo este simple comando gatolog(argumento) | Puede llegar a ser util para ti , aparte que es un comando MUY  simple**
# Util en discord.js
`¿Haces un bot en discord.js?`
`
Tambien puedes logear cosas
`
```
client.on('ready', ()  {
    gatolog(`${client.username} esta encendido`)
}
```
<img src="https://cdn.discordapp.com/attachments/978408141312098327/1005226296428732426/unknown.png">
Un pequeño ejemplo multiplicar
gatolog(2 * 2) // Multiplicacion , Y TODO LO QUE PUEDE HACER CONSOLE LOG PERO UN POCO MAS SIMPLE

<img src="https://cdn.discordapp.com/attachments/978408141312098327/1005226762348798054/unknown.png">
# Ejemplos principales

`Un primer ejemplo puede ser este`
```
METODO: catch(e)
❌  console.error(e)
✅  gatolog(e)
```
`Un segundo y no importante ejemplo puede ser este`
```
METODO: Hacer log a un texto
✅  gatolog('texto')
```
**o**
```
const texto = 'texto simple'
gatolog(texto) o gatolog(`Aca un texto: ${texto}`)
```
**OSDev puede ser ocupado para _LOGEAR_ cosas**
`¡Un tercer ejemplo es este!`
```
const gatolog = require('osdev')
function cargado() {
    gatolog('[OSDEV] todo cargado con exito')
}
  try{

 cargado();

  }catch(e){
    gatolog(`[OSDEV]: Ha ocurrido un error: ${e}`)
  }
  
