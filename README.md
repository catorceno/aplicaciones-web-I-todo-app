# aplicaciones-web-I-todo-app

https://claude.ai/share/0d9808e0-16b2-485c-8f6a-e210425f8f39

1. Analice la salida respecto a su UI/UX. Que opina del diseno en general? Haga un analisis rapido de heuristicas.
El diseño en general es claro, sencillo y funcional. Cumple con lo básico y necesario, sin embargo no tiene constancia de los datos por sesión, aunque si utiliza local storage. Con respecto a las heurísticas,no cumple en su totalidad con "visbilidad del estado" del sistema por el emoji, ya que permanece igual independientemente del apartado donde se este de pendiente, completado o todas. No tiene nada de ayuda ni documentación. Si tiene buena prevención de errores deshabilitando el botón de "Agregar". También cumple bien con un diseño estético y minimalista

2. Analice el codigo generado por la IA. Que errores encuentra? Puede identificar alguna mejora? Cuales? Justifique
Alguno de los erroes son los comentarios innecesarios en la parte del script y también el código css, html y js en un solo documento no permite una escalabilidad sencilla al código de la app. La mejora que le haría sería aplicar modularidad.
