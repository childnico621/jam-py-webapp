# Usa una imagen base de Python
FROM python:3.11

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia los archivos necesarios al contenedor
COPY . .

# Instala las dependencias
RUN pip install --no-cache-dir -r requirements.txt  
# Asegúrate de tener un requirements.txt con tus dependencias

# Expone el puerto en el que se ejecuta la aplicación
EXPOSE 8080

# Comando para ejecutar tu aplicación
CMD ["python", "server.py"]