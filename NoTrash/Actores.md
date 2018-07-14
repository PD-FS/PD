# Solicitud servicio
* Alias de usuario
* Ubicación material: Dirección, punto GPS
* Tipo de material
* Cantidad aproximada de material
* Ubicación de reciclador
* Tiempo de atención
* Identificación del reciclador 
* Contacto de usuario
* Contacto de reciclador



# Actores:

1. Usuarios
2. Recicladores
3. Administradores


# Entidades:

1. Servicio:
	* id (char)
	* usuarioId (char)
	* ubicacionMaterialDireccion (char)
	* ubicacionMaterialGpsX (double)
	* ubicacionMaterialGpsY (double)
	* tipoMaterialId (char)
	* ubicacionRecicladorGpsX (double)
	* ubicacionRecicladorGpsY (double)
	* tiempoAtencion (char)
	* recicladorId
	* estadoServicio (char)

2. Usuario:
	* id (char)
	* nombres (char)
	* apellidos (char)
	* alias
	* tipoIdentificacion (char)
	* numeroIdentificacion (char)
	* email (char)
	* numeroTelefonico (char)
	* calificacion (int)

3. Reciclador:
	* id (char)
	* nombres (char)
	* apellidos (char)
	* tipoIdentificacion (char)
	* numeroIdentificacion (char)
	* email (char)
	* numeroTelefonico (char)
	* foto (char)
	* calificacion (int)

4. Tipos de material:
	* id (char)
	* nombreTipoMaterial (char)
 