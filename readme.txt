# Para publicar la aplicacion se requiren 3 archivos
# requirements.txt
#      este archivo se obtine con pip freeze > ../.. /requiremenets.txt
# runtime.txt
#      este archivo lleva la version de python que estamos usando
#      esta informacion es util para el sitio donde se va asubir
#      le indica que version de python debe usar para deplegar
# procfile
#     se pone este contenido (web: gunicorn login:app)
#     esta informacoion indica que el sitio web usa gunicorn para desplegarse y el nombre 
#     de la aplicacion indicandole que es app (aplicacion) 
# 