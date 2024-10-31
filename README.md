# Tangara - PressKit

Basado en componente https://dopresskit.com pero implementado por componente NPM https://www.npmjs.com/package/milou

# ¿Cómo funciona?

Para ajustar el contenido, hay que modificar los archivos `./data.yml` del estudio y `./{proyecto}/data.yml` para especificar el contenido de los proyectos.

Para construir la web estática, ejecutar:

```bash
milou build .
```

Para testear la web estática en local:

```bash
cd build
npx serve
```

Para probar, acceder a http://localhost:3000