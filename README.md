# Service SOAP avec Apache CXF

Service SOAP en Java avec Apache CXF, JAX-WS, JAXB et WS-Security.

## Prérequis

- Java 17+
- Maven 3.6+

## Installation

```bash
mvn clean compile
```

## Utilisation

### Serveur standard

```bash
mvn exec:java -Dexec.mainClass="com.acme.cxf.Server"
```

WSDL: http://localhost:8080/services/hello?wsdl

### Client

```bash
mvn exec:java -Dexec.mainClass="com.acme.cxf.client.ClientDemo"
```

### Serveur sécurisé

```bash
mvn exec:java -Dexec.mainClass="com.acme.cxf.SecureServer"
```

WSDL: http://localhost:8080/services/hello-secure?wsdl

Credentials: `student` / `secret123`

## Demo
