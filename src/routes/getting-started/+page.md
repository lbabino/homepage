

# Intro
> ¡Bienvenidos a ***NuestroServer***! Aquí podrán acceder y disfrutar de una amplia gama de servicios en línea de manera conveniente y **privada**.
Nuestra motivación es tomar el control de **nuestros datos** y servicios en el mundo digital. Confiar en grandes empresas y proveedores de servicios en la nube puede ser una opción viable, pero también significa renunciar a parte de nuestra **privacidad y control** sobre nuestros propios datos. Con ***NuestroServer***, podemos garantizar la confidencialidad de nuestros y sus archivos personales, así como mantener el control total sobre los servicios que ofrecemos.

# Instalación

## ZeroTier

Para poder conectarnos a la red privada de NuestroServer, necesitamos instalar y configurar [ZeroTier](https://www.zerotier.com/) en nuestro dispositivo

ZeroTier es una aplicación disponible en la mayoría de las plataformas que nos permite crear redes privadas y seguras a través de internet con el objetivo de compartir recursos y servicios con otros usuarios sin la necesidad de exponernos a redes públicas. Para más información, dirigirse a la [web oficial de ZeroTier](https://www.zerotier.com/)

### Windows
1. [Descargue](https://www.zerotier.com/download/)
2. Inicie el programa

![](./Pasted%20image%2020230614000557.png)

3. Busque el ícono en la esquina del reloj, presione _botón derecho_ y seleccione "_Unirse a una nueva red_" 

![](./Pasted%20image%2020230614000749.png)

5. Ingrese el ID provisto por la _Administración_, y presione "_Unirse_"
6. Debería ([troubleshooting?](#troubleshooting)) aparecer el siguiente cartel, acepte.

![](./Pasted%20image%2020230614000929.png)
<br>

7. Luego de unirse a la red, informe a la _Administración_ (el ingreso de nuevos usuarios debe ser evaluado y aprobado manualmente por nuestros especialistas de ciberseguridad).
8. Al recibir confirmación de parte de la _Administración_, ya se encuentra en posición de disfrutar de [nuestros servicios](#services), ¡Felicitaciones!

Ante cualquier problema o consulta, referirse a la sección de [resolución de problemas](#troubleshooting) o comunicarse con la _Administración_



### Android

1. [Descargue](https://www.zerotier.com/download/)
2. Abra la aplicación 
3. Dirijase a "ADD NETWORK"
4. Complete el campo ***Network ID*** con el valor provisto por la administración (el resto de los campos no se deben modificar)
6. Presione ***Add***
7. Conéctese a la red con el interruptor de la derecha
8. Luego de unirse a la red, informe a la _Administración_ (el ingreso de nuevos usuarios debe ser evaluado y aprobado manualmente por nuestros especialistas de ciberseguridad)
9. Al recibir confirmación de parte de la _Administración_, ya se encuentra en posición de disfrutar de [nuestros servicios](#services), ¡Felicitaciones!

<h1 id="services">Servicios</h1>

## [Jellyfin ](http://10.0.0.10:8096)🎞📽🍿

Jellyfin es un servicio de streaming de contenido multimedia, similar a Netflix, con la diferencia de que el contenido es provisto por la _Administración_ y la comunidad, no por un tercero. Esto nos permite tener un control total sobre el contenido y la calidad del mismo, manteniendo la privacidad de nuestros usuarios.

### Inicio de sesión
Si es tu primer ingreso, se deberá solicitar la creación de un usuario a la administración. Se te asignará una contraseña ar bitraria que luego podrás modificar por una de tu preferencia.

### Selección de idioma

### Subtítulos

### Listas de reproducción

### Pedidos de contenido



<h1 id="troubleshooting">Resolución de problemas</h1>

_Próximamente..._

## Testear con ping al servidor

## Testear conexión a puertos

## Testear con ping a otros dispositivos de la red


<style>
	img{
		height:500px;
	}
	a{
		color: white;
		text-decoration: underline;
	}
	p{
		margin-top: 2em;
		margin-bottom: 2em;
	}

	h1,h2,h3,h4,h5,h6{
		margin-top: 2em;
		margin-bottom: 2em;
	}
	h1{
		font-size:2.8em;
	}
	h2{
		font-size:1.8em;
	}
	h3{
		font-size:1.6em;
	}
	h4{
		font-size:1.3em;
	}
	h5{
		font-size:1.1em;
	}
	ol{
		list-style: decimal;
	} 
	#troubleshooting{
		margin-bottom:1em;
	}
</style>