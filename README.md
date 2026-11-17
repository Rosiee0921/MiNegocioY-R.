# Mi Negocio — proyecto Android

Aplicación Android sencilla para administrar ventas de productos en CUP y trabajar sin Internet.

## Funciones incluidas
- Inventario de productos: nombre, precio de venta, costo y existencias.
- Registro de ventas y descuento automático del inventario.
- Historial reciente de ventas.
- Registro de gastos adicionales.
- Cálculo de costo de mercancía vendida, ganancia bruta y ganancia neta estimada.
- Porcentaje de ganancia bruta y neta sobre el total vendido.
- Base de datos SQLite guardada localmente en el teléfono.
- No solicita permiso de Internet.

## Cómo abrir y generar la APK
1. Instala Android Studio en una computadora.
2. Descomprime este proyecto.
3. En Android Studio, selecciona **Open** y elige la carpeta `MiNegocioAndroid`.
4. Espera a que Gradle sincronice el proyecto (necesitarás Internet para descargar las herramientas la primera vez).
5. Ve a **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Android Studio generará el APK de prueba. Desde la notificación de compilación puedes abrir la ubicación del archivo.

## Importante
- El proyecto contiene el código fuente, no un APK ya compilado.
- Una vez instalada, la aplicación funciona sin Internet.
- Los datos se guardan únicamente en ese teléfono. Desinstalar la aplicación o borrar sus datos puede eliminar el registro local.
- La ganancia neta se calcula como: ganancia bruta menos gastos adicionales registrados.
- Las estadísticas son acumuladas; no hay todavía filtros por fechas ni exportación.
- Para compilar se recomienda Android Studio reciente con JDK 17.
