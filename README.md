# Opcion2_Parcial_Mejorado  (Día 28/01/22).

## **Formación con ADF en AYI Group.**

Profesor:
**Paliza, Martin.**  

Integrante: **Gatica , Emmanuel David.**

**Proyecto desarrollado en Jdeveloper 12.2.1.4**

#### **Aplicación Utilizada : ADF Fusion Web Application.**



#### Mejoras : 
- Incorporación de LOV (lista de valores) en las view objects y restricciones de atributos a nivel entity.
- Se incorporaron mejoras visuales a las páginas.
- Botones para optimizar acciones dentro de las mismas.
- Nueva página para agregar materias.
- Incorporación de autoincremental en ID cursos y materias, evitando así incorporar los Id manualmente - Atributo utilizado DBSequence.
- Incorporación de Task Flow , con fragmento de páginas.
- Utilización de componentes "train y train  button bar" para generar un paso a paso , para el usuario.
- Capa seguridad a nivel de usuario, contraseña empleada : ayi . 

Procedimientos: 

1) Definimos la capa de Model y ViewController , por separado.
2) Definimos las entity objects , view objects y app module "Cursos" por separado.
3) Establecimos view criterias en Materias, y definimos el app module.
4) Diseñamos páginas (MateriasPorCursos , NuevoCurso y NuevaMAterias,Presentacion).
5) Se trabajo sobre las mejoras visuales.
6) Incorporación de Task Flow, fragmento de páginas, capa seguridad a nivel usuario.



Se solicito:

1) Crear dos entities, una para tabla CURSOS y otra para tabla MATERIAS.
2) Crear una viewObjt para ambas entidades.
3) Aplicar una viewCriteria a la entidad de Materias para listar todas las materias por curso.
4) Crear un AppModule que haga uso de la viewObject de Materias con la viewcriteria del punto 3.
5) Crear un AppModule que haga uso de la viewObject de CURSOS.
6) En ViewController, crear una página que liste las Materias por Curso.
7) En ViewController, crear una página que liste los Curos y permita agregar uno nuevo.


