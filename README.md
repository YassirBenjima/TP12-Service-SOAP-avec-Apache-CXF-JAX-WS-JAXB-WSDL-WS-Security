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

<img width="1917" height="1030" alt="Screenshot 2025-11-26 230714" src="https://github.com/user-attachments/assets/b2d055ce-294f-4ba3-bd5a-1810cb12dc96" />

<img width="1917" height="1031" alt="Screenshot 2025-11-26 230746" src="https://github.com/user-attachments/assets/f8127798-2c11-4025-a2da-10168f6800d8" />

<img width="1916" height="1030" alt="Screenshot 2025-11-26 231609" src="https://github.com/user-attachments/assets/c5307073-f8de-48ad-9a18-f0bd08aa5a55" />

