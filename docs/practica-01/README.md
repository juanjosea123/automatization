# Mi Estación de Automatización de Redes

## 1. Datos del Equipo
* **Integrantes:** 
  * Juan Jose Avilés Gutiérrez
  * Emilio Adrian Estrada Arenas
  * Angel Emiliano Castillo Carreón
  * Victor yael lazcano zuñiga
  * Fernando Alejandro Hernandez Martinez

* (Nombres de tus compañeros de equipo)
  * **Grupo:** 3IRI3V
  * **Asignatura:** Automatización de Infraestructura Digital I
  * **Fecha:** 17 de septiembre de 2026

---

## 2. Propósito de la Práctica
El objetivo principal de esta práctica es desplegar e integrar un entorno de trabajo colaborativo y un laboratorio virtual completo[cite: 1]. Esto nos permite desarrollar, probar y desplegar scripts de automatización sobre topologías de red simuladas de forma segura y aislada antes de llevarlos a entornos de producción reales[cite: 1].

---

## 3. Herramientas Instaladas
Para construir nuestra estación de automatización, instalamos y validamos la siguiente pila de software:

* **Desarrollo y Lenguaje:** Python 3 (con extensiones de VS Code) y Visual Studio Code como IDE principal[cite: 1].
* **Control de Versiones y Gestión:** Git Bash y GitHub para el seguimiento de cambios y trabajo colaborativo[cite: 1].
* **Pruebas de API y Red:** Postman para peticiones REST y OpenConnect para clientes de acceso remoto[cite: 1].
* **Contenedores y Virtualización:** Docker Desktop para servicios aislados, junto con VMware Workstation Pro para soporte de hipervisor[cite: 1].
* **Simulación de Topologías:** GNS3 GUI conectado a la máquina virtual GNS3 VM[cite: 1].

---

## 4. Configuración Realizada
Durante la preparación del entorno llevamos a cabo los siguientes ajustes clave:

1. **Aislamiento de Dependencias:** Creamos y activamos un entorno virtual (`venv`) en Python para gestionar paquetes sin interferir con el sistema base[cite: 1].
2. **Identidad en Git:** Vinculamos nuestro usuario y correo institucional en la configuración global de Git para firmar cada contribución[cite: 1].
3. **Enlace Remoto:** Inicializamos el repositorio local y lo vinculamos directamente con nuestro espacio en GitHub[cite: 1].
4. **Integración del Hipervisor:** Habilitamos el motor virtual de GNS3 VM dentro de VMware Workstation y lo enlazamos con la interfaz de GNS3 GUI mediante el panel de preferencias[cite: 1, 2].

---

## 5. Verificación del Entorno
Confirmamos que toda la infraestructura quedó lista y funcional mediante las siguientes comprobaciones:

* Ejecutamos comandos de consulta de versión (`--version`) en la terminal para confirmar la presencia de Python, Git, Docker y OpenConnect[cite: 1].
* Corrimos con éxito el programa inicial `hola_mundo.py` desde el entorno virtual activado en VS Code[cite: 1].
* Ejecutamos el contenedor de prueba `hello-world` en Docker Desktop[cite: 1].
* Verificamos que el indicador de estado de la GNS3 VM se mostrara en verde 🟢 dentro del panel de servidores de GNS3 GUI[cite: 2].

---

## 6. Estructura del Repositorio
Organizamos los archivos y las evidencias fotográficas de la siguiente manera[cite: 1]:

```text
automatizacion-redes/
├── data/
├── docs/
│   ├── 01-python.png
│   ├── 02-vscode.png
│   ├── 03-python-vscode.png
│   ├── 04-entorno-virtual.png
│   ├── 05-hola-mundo.png
│   ├── 06-git.png
│   ├── 07-git-identidad.png
│   ├── 08-github.png
│   ├── 09-postman.png
│   ├── 10-openconnect.png
│   ├── 11-docker.png
│   ├── 12-gns3.png
│   ├── 13-gns3-vm.png
│   ├── 14-vmware.png
│   ├── 15-importacion-gns3-vm.png
│   └── 16-integracion-gns3.png
├── src/
│   └── hola_mundo.py
├── tests/
├── requirements.txt
└── README.md