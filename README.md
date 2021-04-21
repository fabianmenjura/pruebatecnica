# pruebatecnica
OPCIÓN 2 crear, eliminar, editar y recuperar tickets. Que se pueda recuperar todos o filtrar por uno específico. Los ticket tienen un id, un usuario, una fecha de creación, una fecha de actualización y un estatus (abierto/cerrado). Debes usar C# (Netocore) o Golang.

Para usarla en Local se debe modificar la conexion de la base de datos con el siguiente codigo
Esta se encuenta en el archivo "appsettings.json" y luego en "appsettings.Development.json"

{
  "ConnectionStrings": {
    "DefaultConnection": "Server=NombreDelServidor;Database=BDTicket;Trusted_Connection=True;MultipleActiveResultSets=true"
  },
  Cambiar el nombre del servidor que se modifica en SQLServer
  
  Abrir la consola de Administrador de paquetes y ejecutar el siguiente comando:  add-migration MigracionInicial
  seguido de:  add-migration MigracionInicial.
