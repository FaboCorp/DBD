<h1 align="center"> 💿 Diseño de Base de Datos</h1>

<p><img width="250" align='right' src="https://media.giphy.com/media/xUA7aQfR9hhgU78KDC/giphy.gif"></p>

- [Condiciones de aprobación](/Documentos/condiciones.md)
- [Modelo conceptual](#modelo-conceptual)
  - [Entidad](#entidad)
  - [Relación](#relación)
  - [Relación reculsiva](#relación-reculsiva)
  - [Atributo](#atributo)
  - [Atributo compuesto](#atributo-compuesto)
  - [Identificador](#identificador)
  - [Cardinalidades en los atributos](#cardinalidades-en-los-atributos)
  - [Cardinalidades en las relaciones](#cardinalidades-en-las-relaciones)
  - [Identificador compuesto](#identificador-compuesto)
  - [Identificador externo](#identificador-externo)


# Modelo conceptual
### Entidad


<p><img width="200" align='right' src="./Img/Diagramas/Entidad.png"></p>

Es un elemento u objeto del mundo real que queremos representar. Partimos de un problema/dominio, este va a tener distintos elementos/objetos a representar y los representamos en el modelo conceptual a partir de una entidad.

### Relación

Nos representan las dependencias que tenemos entre dos o mas entidades, si una relacion une dos entidades, hablamos de una relacion binaria. Si une tres entidades, hablamos de una relacion ternaria y asi sucesivamente. El nombre descriptivo en la relacion **R1** no es una buena practica ya que podemos representar distintas dependencias con una misma relación (y genera ambigüedad)

<p><img src="./Img/Diagramas/Relacion.png"></p>

### Relación reculsiva
Relacion que une dos entidades particulares del mismo conjunto. En este caso, materias esta relacionada con si misma. Por ejemplo R1 = 'es correlativa de', estariamos diciendo que una materia es correlativa de otra materia.

<p><img width="400"  src="./Img/Diagramas/Recursiva.png"></p>

### Atributo

<p><img align='right' width="200"   src="./Img/Diagramas/Atributo.png"></p>

Un atributo representa una propiedad basica de una entidad o relacion. Un atributo es equivalente a un campo de un registro

### Atributo compuesto

<p><img align='right' width="300"   src="./Img/Diagramas/Atributo Compuesto.png"></p>

Un atributo compuesto representa a un atributo generado a partir de una combinacion de varios atributos simples 

<br>
<br>

### Identificador
<p><img align='right' width="200"   src="./Img/Diagramas/identificador.png"></p>


Un identificador es un atributo o un conjunto de atributos que permite reconocer o distinguir a una entidad de matenar univoca dentro del conjunto de entidades.

### Cardinalidades en los atributos
### Cardinalidades en las relaciones
### Identificador compuesto
### Identificador externo