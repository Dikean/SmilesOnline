- Correr la web

//todos son metodos POST
//paso uno - registar un usuario

ruta:
 http://127.0.0.1:8000/api/auth/register
 
 //paso dos- iniciar sesion un usuario

ruta:
 http://127.0.0.1:8000/api/auth/login
 
 //paso tres - copiar el token que da el inicio de session

ruta:
 http://127.0.0.1:8000/api/auth/me
 
 Authorizacion - Bearer Token - pegamos el token
  y nos debebe de regresar los datos del usuario



