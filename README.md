# **Explicación del reto y observación de subcompetencias**

A continuación, se muestra la organización del documento **CNN**, que se encuentra en la carpeta de **RETO**. Se explicará brevemente lo realizado en cada parte:

---

![Explicación del reto](https://github.com/user-attachments/assets/0a96eeee-d891-4b3a-a95e-97a5a7bf4f33)

## **Parte 0 - Exploración de datos y segmentación**

En primer lugar, se realizó un análisis de los datos para comprender la problemática y definir los requisitos del proyecto. Como parte de este proceso, se segmentaron manualmente alrededor de 200 imágenes.

![Exploración de datos y segmentación](https://github.com/user-attachments/assets/8e249703-df6d-4748-a607-d6e897a0d0af)

---

## **Parte 1 - Filtros**

Se exploró una variedad de filtros para observar cómo reaccionaban las imágenes a ellos y determinar si era necesario su uso.

![Filtro 1](https://github.com/user-attachments/assets/8454e8e0-ba08-419c-8ae3-a55733cc6be3)  
![Filtro 2](https://github.com/user-attachments/assets/be5c38c0-a89f-4529-88e7-f167857bcb22)

---

## **Parte 2 - Redimensionamiento (Resize)**

Se aplicaron técnicas de redimensionamiento necesarias para la **CNN**.

![Resize](https://github.com/user-attachments/assets/f6eece40-f99d-406c-b074-1b135fb6327b)

---

## **Parte 3 - Data Augmentation y Comprobación**

Se implementaron técnicas de aumento de datos, incluyendo rotaciones de 90°, 180° y 270°.

![Aumento de datos 1](https://github.com/user-attachments/assets/2cfe9979-0b55-47fb-8cf0-9da1a60e6938)  
![Aumento de datos 2](https://github.com/user-attachments/assets/dc3ae658-2c1c-4918-9a7e-454937fef116)  
![Comprobación](https://github.com/user-attachments/assets/f0043382-afb1-4b98-a58d-d13619a2e86c)

---

## **Parte 4 - Entrenamiento de la CNN**

Se entrenó una **CNN - U-net** utilizando un total de **585 imágenes**. Fue evaluado con diferentes métricas tomando como principal la **precisión** Los resultados obtenidos fueron los siguientes:

![Resultados 1](https://github.com/user-attachments/assets/c8519d93-c0b8-40e4-9f34-645b158a91ae)  
![Resultados 2](https://github.com/user-attachments/assets/10e95305-6372-4a7d-b4e3-27005cb328e5)  


---

# **Manual de uso para utilizar el modelo**

En el siguiente link se encuentra un archivo llamado **MODEL.h5**, que corresponde al modelo entrenado. Este modelo será utilizado en el archivo **Time-lapse.ipynb**, ubicado en la carpeta del reto. Este código se divide en dos partes importantes:

[Enlace a la carpeta de Google Drive](https://drive.google.com/drive/folders/1w1J3HOnHG8MdVkKiX7Y2c0fCKckYTlaT?usp=drive_link)

![image](https://github.com/user-attachments/assets/a41be7d9-0013-44bb-b8ec-e147105d766a)


---

### **Primera parte: Predicción de imágenes**

La primera sección del código se encarga únicamente de generar la predicción de las imágenes.

![Predicción](https://github.com/user-attachments/assets/e404d16f-5cf5-4868-89c0-61d943cb0282)

---

### **Segunda parte: Creación de video**

La segunda sección combina las imágenes predichas y las convierte en un video. Puedes visualizar un ejemplo del resultado aquí:

[Video1 ](https://youtu.be/5XDVs9lTTvA)  
[Video2 ](https://youtu.be/5XDVs9lTTvA)

---

## **Investigación**

Si desea saber más acerca de cómo fue realizado el modelo, puede leer nuestra investigación que se encuentra en la carpeta del reto.

