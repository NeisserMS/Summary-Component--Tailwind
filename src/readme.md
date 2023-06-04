https://www.youtube.com/watch?v=Pxs2WKdvBRU

Para crear el archivo package.son: npm init -y
Para instalar TailWind: npm install -D tailwindcss
Para crear el archivo de configuracion (necesario para personalizar Tailwind ): npx tailwindcss init
Comando para ejecutar el script del archivo q mapeamos en el package.json (esto para que pueda crear el archivo estilos.css) : npm run tailDev


  // aquí le diremos que observe a estos archivos, observará las clase que se añada al html y al js y al final generar un archivo con todos esos estilos de las clases de utilidad
  content: ["./src/**/*.{html, js}"],
