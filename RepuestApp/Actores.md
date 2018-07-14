<<<<<<< Updated upstream
Hola RequestApp... Probando push desde el curso de Fedesoft

usuario(
Nombre varchar (30),
Apellido  varchar (30),
TipoIdentifcacion varchar (30),
NroIdentificacio varchar(30),
DireccionResidencia varchar(50)
=======
administrador
(
Aid int identity,
Alogin varchar(50),
Acontrasena varchar(50),
ANombre varchar(30),
AApellidos varchar(30),
AFecha_Creacion datetime
)

usuario
(
Uidusuario int identity,
UNombre varchar (100),
UDireccion  varchar (50),
UHorarios datetime,
UNIT varchar(30),
UTelefono varchar(50),
UFecha_Creacion datetime
)


locales
(
Lidlocal int identity,
Uidusuario int ,
LNombre varchar (100),
LDireccion  varchar (50),
LHorarios datetime,
LNIT varchar(30),
LTelefono varchar(50) ,
LFecha_Creacion datetime,
LEstado int
)

localDetalle
(
LDidlocalDetalle int identity,
Lidlocal int,
LDtipoVehiculo int,
LDFecha_Creacion datetime
)

commtipoVehiculo
(
ctvidtipoVehiculo int identity,
LDtipoVehiculo int,
ctvDescripcion varchar(50),
ctvEstado int
)

DetalleRepuestos 
(
DrIdRepuesto int identity,
ctvidtipoVehiculo int,
LDidlocalDetalle int ,
DrDesRepuesto varchar (100),
DrValorRepuesto int ,
DrEstado int
)




















>>>>>>> Stashed changes

)