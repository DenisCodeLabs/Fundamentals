# **Fundamentals** 
**Cosas que deberías saber iniciando en el área de Streaming (Backend Java)**
---
<br>

### 💻 Programar con IntelliJ IDEA
### 🌐 Dominar Git
### ⚙️ Comandos Maven
### 🐞 Errores (Bugs) Comunes
---
### 💻 Programar con IntelliJ IDEA
![Intellij](https://github.com/user-attachments/assets/4ed81a8c-86c8-4d71-88ff-f0118d2f199f)
### 🔍 SonarLint
SonarLint es un plugin que analiza tu código en tiempo real y te ayuda a detectar errores, vulnerabilidades y malas prácticas. <br>
Instalar el plugin:

  1. Ve a File → Settings → Plugins. <br>
  2. Busca "SonarLint" y haz clic en Install.<br>
  3. Reinicia IntelliJ.


### 📊 Compilación con Cobertura de Código
Es una métrica que indica qué porcentaje del código es ejecutado por pruebas unitarias. <br>
Corre los tests con cobertura:

  1. Haz clic derecho en una clase de prueba → Run with Coverage. <br>
  O usa Ctrl + Shift + F10 → Run with Coverage. <br>
  2. Se mostrará un informe con las líneas ejecutadas en verde y las no cubiertas en rojo.

### 📌 Alternativa con JaCoCo
Resumen general: porcentaje de líneas y ramas cubiertas. <br>
Clases y métodos: detalles de qué partes del código están cubiertas y cuáles no.

![jacoco](https://github.com/user-attachments/assets/930ebbeb-4980-4d46-9453-5f521be4fa12)

Colores en el código: <br>
  - Verde → Código cubierto por pruebas. <br>
  - Rojo → Código no ejecutado en las pruebas.

---
### 🌐 Dominar Git
![git](https://github.com/user-attachments/assets/77ed5acc-1a0b-428d-9b93-5099404e2308)

Si hiciste un commit con un mensaje incorrecto y aún no lo has hecho push, puedes corregirlo así:

```sh
git commit -m "Mensaje equivocado"
git commit --amend -m "Mensaje corregido"

```
Esto sobrescribe el mensaje del último commit sin crear uno nuevo. 
