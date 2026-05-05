Hack Film es un proyecto donde puede ver pelicula online este proyecto usa una lista de usario de forma remota y obtiene la pelicula de una lista m3u remota, aqui alguna vista del proyecto.


<img width="1348" height="603" alt="image" src="https://github.com/user-attachments/assets/88782318-1ec8-4008-832f-55e3621c7f63" />


<img width="1361" height="605" alt="image" src="https://github.com/user-attachments/assets/b0fcc7e7-e269-4725-af40-dd2fca237689" />


configuracion de el proyecto para que pueda usar:

paso 1:

para el login de subir un txt con lo usuario de la siguiente forma:

demo:demo
admin.admin
prueba:123456
julio:julio123

asi como el ejemplo un usuario por linea.

paso 2:

debe editar el index.html en la siguiente parte:

<img width="1081" height="276" alt="image" src="https://github.com/user-attachments/assets/da30cc5d-f1f4-4ada-a7e8-362b96fe2f99" />

en la linea 380 busca esta parte const USERS_LIST_URL = 'aqui va tu url con lo usuario con el  formato que explique en el paso 1';

paso 3:

edita el dashboard para que cargue tu lista de pelicula 

<img width="1089" height="265" alt="image" src="https://github.com/user-attachments/assets/ba83507d-3350-44c3-921d-6cc7e92645f1" />

en la linea 640 busca esto const M3U_MOVIES_URL = 'aqui tu url de la lista m3u con tu pelicula ';





