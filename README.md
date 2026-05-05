# RA6_AEE_Actividad_individual_13-Bolet-n_Diagramas_de_Casos_de_Uso_3

Para la actividad, se pedía que elaborásemos un diagrama con el siguiente enunciado:
Al crearse, la descarga empieza en estado Iniciando.
Pasa automáticamente a Descargando.
Desde Descargando, el usuario puede Pausar (pasa a Pausado) o Cancelar (pasa al estado final).
Si ocurre un ErrorRed mientras descarga, debe intentar reanudarse automáticamente solo si el número de reintentos es < 3. Si llega a 3, pasa a Error Crítico.
Cuando el progreso llega al 100%, pasa a Verificando Integridad.
Si la verificación es correcta, pasa a Finalizado. Si falla, vuelve a Iniciando.
