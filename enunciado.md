## Enunciado

<p>
  Se desea diseñar una base de datos para una empresa desarrolla de videojuegos. La empresa crea y administra varios títulos, y para cada uno de ellos se debe almacenar información específica dependiendo del género del videojuego. Además, se gestionará información sobre las sedes de la empresa, los desarrolladores que trabajan en ella, los juagdores que participan en los videojuegos, las partidas que se juegan, los personajes, las skins, los campeones y los torneos asociados.
</p>
<p>
  La base de datos debe registrar la información general de la empresa, incluyendo su CIFy dirección. Cada videojuego que desarrolla la empresa tendrá asociado un presupuesto, el número de horas de desarrollo y un código único que lo identifique. Los videojuegos se clasifican en tres tipos: Shooter, Cartas y Moba. Los videojuegos de tipo Shooter incluirán información adicional sobre los mapas utilizados, mientras que los juegos de tipo Carta y Moba no tienen atributos adicionales específicos.
</p>
<p>
  La empresa cuenta con varias sedes, las cuales sólo pertenecen a esa empresa. De cada sede, se quiere guardar su código único, la sección del videojuego que desarrolla, el país donde se encuentra y su dirección.
</p>
<p>
  Dentro de cada sede trabajan desarrolladores. De cada desarrollador se almacenará su DNI, nombre, apellidos y dirección. Los desarrolladores no pueden trabajar en más de una sede a la vez. De los desarrolladores, hay un desarrollador que es jefe y supervisa al resto de desarrolladores. No puede haber más de un desarrollador jefe en cada sede.
</p>
<p>
  En cuanto al contenido de los videojuegos, se desea registrar información adicional dependiendo del tipo de videojuego. En el videojuego de tipo Carta, cada jugador tendrá que escoger una baraja de cartas, y de cada baraja se desea guardar el nombre de las cartas que lo componen, un identificador único de baraja, el tipo de carta que es y las habilidades. Un juagdor tiene que escoger una baraja, pero el jugador contrario también puede tener esa misma baraja configurada.
</p>
<p>
  En los videojuegos de tipo Shooter y Moba, los jugadores pueden seleccionar cualquier campeón, pero éste se bloquea para el resto de jugadores de esa partida si es seleccionado, por lo que un campeón sólo puede seleccionarse una vez por partida. De cada campeón se quiere guardar información sobre el nombre (único), sus habilidades, daño base, vida base y fecha de lanzamiento.
</p>
<p>
  En lo que respecta a los jugadores, cada jugador debe registrarse proporcionando su email (único para cada jugador), dirección y elo. Los jugadores se dividen en tres tipos: Profesional, Casual y Streamer. Del jugador profesional se guardará el equipo al que pertenece y el número de horas que juega al día. Del juagdor casual, se registrará las compras realizadas, mientras que de un streamer se incluirá la información sobre la plataforma donde transmite y el nombre de su canal.
</p>
<p>
  Las partidas también serán gestionadas en la base de datos. Los videojuegos de tipo Carta cuentan con partidas de uno contra uno. Las partidas de Moba y Shooter son de cinco contra cinco. De cada partida se guardará su código único, la fecha de realización, la duración  y el tipo de partida que es.
</p>
<p>
  Los jugadores pueden comprar skins (aspectos) de los campeones que utilicen. Pueden comprar tantas skins como quieran y las skins pueden ser compradas por múltiples jugadores. Nos interesa guardar la fecha de cuando un jugador compra una skin. De cada skin se guardará su nombre, tipo y precio. Indicar también que cada campeón puede tener muchas skins, pero las skins solo pertenecen a un campeón.
</p>
<p>
  Por último, se registrarán los torneos donde los jugadores profesionales y streamer pueden participar, sólo uno a la vez. Cada torneo tendrá un único código, un presupuesto, un premio, una dirección y una fecha. Los torneos pueden ser regional o mundial, pero existen otros tipos de torneos. De los torneos regionales se quiere guardar el paíl y de los mundiales se queire conocer el nombre del equipo ganador.
</p>
