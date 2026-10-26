# 🧬 Sudoku Genético

Una versión web interactiva y gamificada del **Sudoku Genético** basada en el Dogma Central de la Biología Molecular y las Leyes de Chargaff. Diseñada para su aplicación pedagógica en Educación Secundaria (4º de ESO) y Bachillerato.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 🎯 Objetivo Didáctico

El alumnado debe completar las casillas vacías de una cuadrícula molecular deduciendo las bases nitrogenadas y aminoácidos faltantes mediante:

1. **Complementariedad de Bases (Reglas de Chargaff):**
   - En ADN bicatenario: $A = T$ y $C \equiv G$.
   - Hebra codificante ($5' \rightarrow 3'$) vs. Hebra molde ($3' \rightarrow 5'$).
2. **Transcripción ($3' \rightarrow 5'$ a $5' \rightarrow 3'$):**
   - La ARN polimerasa transcribe la hebra molde de ADN a ARNm sustituyendo la Timina por **Uracilo ($U$)**.
     - $A \rightarrow U$
     - $T \rightarrow A$
     - $C \rightarrow G$
     - $G \rightarrow C$
3. **Traducción del Código Genético:**
   - Cada triplete (codón de ARNm en sentido $5' \rightarrow 3'$) se traduce en su aminoácido correspondiente según el código genético universal.
4. **Anticodón de ARNt ($3' \rightarrow 5'$):**
   - Tripletes complementarios y antiparalelos al codón de ARNm.

---

## ✨ Características

- 🎨 **Diseño con Colores Suaves:** Paleta cromática pastel adaptada para educación (violeta suave para Adenina, melocotón suave para Uracilo, azul cielo para Citosina, amarillo suave para Timina y verde menta para Guanina).
- 🔄 **Generador Procedural de Nuevas Partidas:** Cada vez que se pulsa *Reiniciar*, se genera un fragmento de ADN intermedio biológicamente coherente con pistas distribuidas lógicamente.
- 📊 **Marcador en Tiempo Real:** Contador de aciertos ($X / \text{Total}$), porcentaje de precisión y partidas completadas.
- ✓ **Comprobación Inmediata con Feedback:** Resalta casillas correctas en verde esmeralda e incorrectas en rojo carmesí con animación de aviso.
- 📖 **Tabla del Código Genético Integrada:** Modal con buscador en tiempo real por codón o aminoácido.
- 📱 **Totalmente Autónomo y Responsive:** Funciona en ordenadores, pizarras digitales, tabletas y móviles sin dependencias externas ni conexión a internet.

---

## 🚀 Despliegue en GitHub Pages (en 1 minuto)

Para que tus alumnos puedan jugar directamente desde cualquier navegador:

1. Crea un nuevo repositorio en GitHub (por ejemplo, `sudoku-genetico`).
2. Sube el archivo `index.html` (y este `README.md`).
3. Ve a **Settings** > **Pages** en tu repositorio.
4. En **Branch**, selecciona `main` (o `master`) y guarda.
5. ¡Listo! En unos segundos tendrás tu enlace público: `https://<tu-usuario>.github.io/sudoku-genetico/`

---

## 📄 Créditos y Licencia

Inspirado en la dinámica original de *@eneko-fc* y adaptado didácticamente para su libre uso en las aulas.
Licencia MIT: libre para uso, modificación y distribución educativa.
