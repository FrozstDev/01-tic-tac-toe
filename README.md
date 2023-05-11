### TIC TAC TOE

Aprender spread y rest operator

NOTA:
Importante - La actualizacion de los estados en React son ASINCRONOS - Todos los hooks(STATES) NO deben estar dentro de un IF, deben estar en el cuerpo del componente. NO DEBEN ESTAR EN UN IF, WHILE ...ETC - Mejor forma de recuperacion del local storage es inyectar una funcion inicializadora para el useState useState(() => {})
Leer el localstorage desde el componente es LENTO, ademas renderiza una app por muchas veces MALA PRACTICA - || => esto mira si el elemnto es false
?? => esto mira si el elemnto es null or undefined - Buena practica : Es mejor el item identificado del LOCALSTORAGE, que todos con el comando clean() - Segundo hook mas importate de React es UseEffect => Es un hook que nos permite ejecutar codigo arbitrario (cualquier codigo) cuando el COMPONENTE se monta en el DOM y cada vez que se cambia las dependencias que nosotros le digamos
Se ejecuta dentro del cuerpo del componente

NOTA: No hacer pruebas tecnicas sin linter (IMPORTANTE)
Usaremos Standard js
npm install standard -D
Configuramos el pakage.json
"eslintConfig": {
"extends": "./node_modules/standard/eslintrc.json"
}
