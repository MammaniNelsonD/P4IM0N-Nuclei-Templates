![42e1c8a8-cb8e-481f-959c-c086598abd6a](https://github.com/user-attachments/assets/607a4b40-3330-4114-8a84-24198c021a5d)


# 🔍 Nuclei-Templates para Laboratorios de PortSwigger y más 🚀

## 📌 Descripción:
Este repositorio contiene **templates personalizados de Nuclei** para la explotación automatizada de más de **250 vulnerabilidades** presentes en los laboratorios de **PortSwigger Web Security Academy**. 💥  

Cada template ha sido diseñado para demostrar **cómo Nuclei puede ser utilizado para detectar y explotar vulnerabilidades en entornos controlados**, ayudando a entender mejor su funcionamiento y automatizar su detección. ✅  

🌍PROJECTDISCOVERY LOS CREADORES DE NUCLEI:
- **[https://projectdiscovery.io](https://projectdiscovery.io)**

---

## 📜 ¿Qué encontrarás en este repositorio?
🔹 **Templates para Nuclei** adaptados a cada laboratorio de PortSwigger.  
🔹 **Explicaciones detalladas** de cada vulnerabilidad explotada.  
🔹 **Ejemplos prácticos** para aprender a utilizar Nuclei en entornos reales.  
🔹 **Automatización de pruebas de seguridad web** para mejorar la eficiencia.  

---

## ⚡ Requisitos

### 🔧 Herramientas necesarias:

- **[Nuclei](https://github.com/projectdiscovery/nuclei)** - Descarga aquí.  
- **[Acceso a los laboratorios de PortSwigger](https://portswigger.net/web-security)**  

### 📂 Instalación de Nuclei:
```bash
# Instalar Nuclei (si no lo tienes)
go install -v github.com/projectdiscovery/nuclei/v3/cmd/nuclei@latest

# Verificar instalación
nuclei -version
```

---

## 🔥 Cómo usar los templates

### 1️⃣ Clona este repositorio:
```bash
git clone https://github.com/tuusuario/nuclei-portswigger.git
cd nuclei-portswigger
```

### 2️⃣ Ejecuta un template específico:
```bash
nuclei -t templates/sql-injection.yaml -u http://victima.com
```

### 3️⃣ O ejecuta todos los templates contra un objetivo:
```bash
nuclei -t templates/ -u http://victima.com
```

---

## 📌 Lista de templates que estarán disponibles gradualmente
✔️ **SQL Injection**  
✔️ **XSS (Cross-Site Scripting)**  
✔️ **CSRF (Cross-Site Request Forgery)**  
✔️ **XXE (XML External Entity Injection)**  
✔️ **SSTI (Server-Side Template Injection)**  
✔️ **Prototype Pollution**  
✔️ **SSRF (Server-Side Request Forgery)**  
✔️ **Deserialización Insegura**  
✔️ **IDOR (Insecure Direct Object Reference)**  
✔️ **Y muchas más...** 🔥  

---

## 📌 Cada template incluirá:
✅ **Descripción de la vulnerabilidad**  
✅ **Explicación del laboratorio en PortSwigger**  
✅ **Ejemplo del ataque**  
✅ **Cómo explotarlo con Nuclei**  

---

## 💡 Contribuciones
🔄 **¡Este repositorio está en construcción y en constante evolución!**  
Si deseas mejorar algún template o agregar nuevas vulnerabilidades, **haz un fork y envía tu PR**. 🚀  

---

## 📢 Contacto  
📧 **Desarrollador:** Mamani Nelson (P4IM0N)  
🐦 **YouTube:** [@P4IM0N-Hacking](https://www.youtube.com/@P4IM0N-Hacking)  
🔗 **GitHub:** [github.com/MammaniNelsonD](https://github.com/MammaniNelsonD)  
☕ **DONACIÓN (alias Mercado Pago, se agradece 😁):** hackisnotacrime20  

---

⚠️ **Disclaimer:** Este repositorio es solo con fines educativos y de investigación. **No me hago responsable del mal uso de esta información.**  

🔥 **¡Happy Hacking!** 🔥  

