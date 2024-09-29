**CogSeeker** es un buscador cognitivo para la resolución de dudas a través de preguntas en lenguaje natural
La aplicación dispone de funcionalidades distintas en función del status de cada tipo de usuario.

En CogSeeker hay tres tipos de usuarios o roles: user, admin y superadmin.
Hay tres tipos de usuario o roles:
  1. user:
      1.1 Sólo tiene acceso a la pantalla del asistente virtual.
      1.2 Solo dispone de visibilidad de las colecciones que le haya asignado un superadmin para
          realizar consultas.
      1.3 Su feedback positivo o negativo sobre respuestas recibidas ha de ser validado por un superadmin.
  2. admin:
      2.1 Tiene acceso al panel de usuarios. Allí puede añadir y eliminar usuarios de los proyectos.
      2.2 Puede cambiar el status de cualquier usuario.
      2.3 Puede cambiar las colecciones que tiene disponibles.
      2.4 Su feedback positivo no debe ser validado por nadie, ni siquiera el superadmin.
      2.5 Su feedback negativo ha de ser validado por el superadmin.
      2.6 No posee acceso al panel de administración.
  3. superadmin:
      3.1 Posee acceso a todas las funcionalidades de la aplicación Cogseeker.
      3.2 Es el encargado de gestionar el acceso al proyecto al cual está asignado.
