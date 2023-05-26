Lo primero es descargar el programa sobre el cual vamos a trabajar  Deberemos pegar el link en el buscador y la descarga se iniciara de forma automática t

![image](https://github.com/Lem151/Flask/assets/114771568/988f5eb1-81d8-4fff-907b-adb9ba3b0f37)

Luego lo extraemos en nuestro directorio de trabajo y ejecutamos app.py con VS 

![image](https://github.com/Lem151/Flask/assets/114771568/b004858b-3618-4805-9ae2-499cffb0ea2b)

Ahora debemos hacer la cuerry que nos permite ver todos los cumpleaños y para eso agregamos esto al codigo aproximadamente en la línea 36 a parte en la segunda linea añadiremos esto: birthdays=birthdays para que el return nos de el resultado de la querry

![image](https://github.com/Lem151/Flask/assets/114771568/70ccf5ce-ac5e-4662-80ea-213d31d34e5a)

Luego nos movemos a la carpeta templates y el archivo index donde deberemos rellenar el <tbody> con el siguiente codigo 
  
![image](https://github.com/Lem151/Flask/assets/114771568/ea360558-03fb-4f59-9064-7a7b9149575d)

Ahora veremos cómo hacer que los usuarios puedan colocar sus propios cumpleaños, para esto colocaremos en All Birthdays este código que crea un formulario para los usuarios
  
![image](https://github.com/Lem151/Flask/assets/114771568/60b33801-bd83-48ce-9afd-5619e44e41c6)

Es la hora de conectarlo todo, para esto deberemos hacer las siguientes acciones  Debemos volver a nuestro archivo principal app.py una vez alli localizamos nuestra funcion index () cuando la hayamos localizado debemos colocar un codigo en el if  este if verifica que estemos haciendo un “POST” cuando lo hagamos llenaremos las variables name, month y day del formulario de antes usando la funcion form.get 
  
![image](https://github.com/Lem151/Flask/assets/114771568/a3be4f41-52a0-4c11-86af-d27738d48ca7)

Con esto ya estaría 
  


