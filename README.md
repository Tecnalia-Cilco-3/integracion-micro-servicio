# integracion-micro-servicio

El mirco servicio tendría como url `/api/evaluar` el METODO es `POST`

En los headers tendrá que tener un `Authorization` header con `Bearer ${TOKEN}`
Y será mandado mediante form data para poder aceptar de forma correcta el zip file.

Los parametros son los siguientes.
- zipfile : de tipo file y será el zip que manda el estudiante.
- activityid : Activity id que se debe mandar al webservice
- courseid : Course id que se debe mandar al webservice
- component : component que se debe mandar al webservice
- source : source que se debe mandar al webservice
- student_ids[] : Array de ids de los estudiantes se debe mandar como array dentro el form data. 


Hay un archivo de postman donde se puede ver como ejemplo el webservice a consumir.
