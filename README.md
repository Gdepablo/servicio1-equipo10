# servicio1-equipo10
Servicio 1 del Equipo 10 de la materia Diseño de Sistemas UTN.BA

# URL

Url de Acceso: http://localhost:8080/swagger#/

# BODY Valido para Fusion de Comunidades (el de Swagger está mal)

{
    "comunidadesAFusionar": [{
        "id":3, 
        "miembros":[1,2,3], 
        "gradoConfianza" : 1,
        "prestacionesDeServicio": [{"id": 1, 
                                    "servicio":4, 
                                    "establecimiento":6}]
        },
        {
        "id":4, 
        "miembros":[1,2,3], 
        "gradoConfianza" : 1,
        "prestacionesDeServicio": [{"id": 1, 
                                    "servicio":4, 
                                    "establecimiento":6}]
        }
        ],
    "propuestasAExcluir":[[4,5]]
}
