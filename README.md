# Tarea 8: Máquinas Virtuales
Para esta tarea, primero definamos como se crean las máquinas virtuales utilizando QEMU.\
Primero, después de toda la previa instalación de QEMU, debemos crear una nueva máquina virtual:\
<img width="548" height="178" alt="image" src="https://github.com/user-attachments/assets/0eba4528-40f6-4115-a63a-2c731e73b77c" />\
Aparecerá lo siguiente y se selecciona la primer opción para crear la MV con nuestra imagen ISO.\
<img width="450" height="455" alt="image" src="https://github.com/user-attachments/assets/6b0dcf97-6b23-4388-ae6e-d2ca221becb6" />\
Ahora, se debe escoger la imagen descargada previamente. El sistema detecta automáticamente el sistema operativo que se va a instalar\
<img width="744" height="451" alt="image" src="https://github.com/user-attachments/assets/9034f1b5-d923-42e1-b675-c89278a208f0" />\
Se escoge cuanta capacidad de memoria RAM y ROM y cuántos núcleos del procesador se utilizarán para correr la máquina virtual.\
<img width="450" height="442" alt="image" src="https://github.com/user-attachments/assets/e015b743-56dd-4b34-8fc4-6827cbe6b765" />
<img width="450" height="442" alt="image" src="https://github.com/user-attachments/assets/875d3a39-0026-4084-8ef9-ad0a1abe9916" />\
Y finalmente se crea exitosamente la MV.\
<img width="487" height="447" alt="image" src="https://github.com/user-attachments/assets/a78a9dfe-3651-4d17-b276-af52e674b3bb" />

### 1. Crear máquina virtual de Rocky Linux:
Se instala la imagen ISO de Rocky, se encuentra en el siguiente link: [Rocky Linux](https://rockylinux.org/sr-SP/download)\
Después de seguir los pasos, se verá lo siguiente:\
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/9c9d8d1d-b10b-42af-abae-8fbef811421a" />\
También se pide la creación de un usuario y que se escoja donde se almacenará lo que se instale dentro de la máquina virtual, pero es un paso bastante intuitivo.\
Ya dentro de la MV se ve esto:\
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6df4001b-0e01-41b5-9bca-01d5554b53d7" />\
Consola de Rocky Linux:\
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/1b5899cd-7492-4201-8e7c-d804ed89c610" />
### 2. Crear máquina virtual de Kali Linux:
### 3. Crear máquina virtual de Windows:
### 4. Se debe probar que todas las máquinas virtuales se comuniquen entre sí:\
Para este punto, primero comprobamos cuál es la dirección IP de cada máquina virtual con el comando\
`hostname -I`
en Linux\
`ipconfig`
en Windows\
Aca se observa que las 3 máquinas virtuales se están ejecutando:\
<img width="602" height="639" alt="image" src="https://github.com/user-attachments/assets/7d98259e-f15c-4efc-b1b0-33c85dee4b70" />\
Y en estas imágenes observamos las direcciones IP de cada una:\
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/9a4447e2-e3fa-4a96-98fd-a8c83222a0f3" />
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/603a5ca2-be2e-4970-9802-3348eca733f6" />
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/f828da73-e861-4a9a-88fe-cf3d0f87213f" />
Por último, comprobamos que se comunican entre sí con el comando `ping 192.168.122.xx` 

Ping de Windows a Kali\
<img width="430" height="212" alt="image" src="https://github.com/user-attachments/assets/62d25d0a-8783-410e-bed1-fa9cd46f0011" />\
Ping de Windows a Rocky\
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/69462432-80b0-4f3a-a9d2-03f931efcf44" />\
Ping de Kali a Rocky\
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/d60608ec-81aa-46d8-b0f7-927d2cec5dca" />\
Ping de Kali a Windows\
<img width="420" height="227" alt="image" src="https://github.com/user-attachments/assets/7122418d-8d13-4a0f-9841-c18b2f4ec933" />\
Ping de Rocky a Kali\
<img width="1300" height="736" alt="image" src="https://github.com/user-attachments/assets/bf22dc46-1363-4929-b93b-4d5571a28602" />\
Ping de Rocky a Windows\
<img width="420" height="227" alt="image" src="https://github.com/user-attachments/assets/1b92c960-61b3-407c-a53c-fa118dbb9e7b" />\




