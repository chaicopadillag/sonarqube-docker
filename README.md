# SonarQuBe en Docker

## Crear Estructura de Carpeta

```bash
mkdir -p ./sonarqube/data
mkdir -p ./sonarqube/extensions
mkdir -p ./sonarqube/logs
mkdir -p ./postgresql/conf
mkdir -p ./postgresql/data
```

## Ejecutar el comando para crear y hechar a handar las images.

```
docker-compose up -d
```

## Acceder el servidor de SonarQube en local

[http://localhost:9000](http://localhost:9000)

Credenciales por defecto:

- Username: `admin`
- Password: `admin`
