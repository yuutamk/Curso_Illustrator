# **Práctica de Diseño: Creando una Cancha de Baloncesto con Perspectiva Realista en Illustrator y Photoshop**

En esta práctica, aprenderás a diseñar una cancha de baloncesto profesional utilizando Illustrator para crear los elementos vectoriales y Photoshop para aplicar efectos de perspectiva y textura. Desarrollarás habilidades en diseño deportivo, composición vectorial y trabajo entre aplicaciones.

---

#### **Paso 1: Configuración del Documento en Illustrator**

1. Abre Adobe Illustrator y crea un nuevo documento
2. Establece las dimensiones: **1080 x 1920 píxeles**
![](../src/cancha/01_nuevo_archivo.png)
1. Nombra el archivo como "Cancha_Baloncesto"



---

#### **Paso 2: Crear el Contorno de la Cancha**

1. Selecciona la **Herramienta Rectángulo**
![](../src/cancha/02_herramienta_rectangulo_sin_relleno_borde_negro.png)
2. Dibuja un rectángulo que cubra la mayor parte de la mesa de trabajo
3. En el panel **Propiedades**:
   - Quita el relleno (establécelo en "Ninguno")
   - Establece el color del trazado en negro
   - Define el grosor del trazado en **5 puntos**
   ![](../src/cancha/03_rectangulo_5pt.png)


---

#### **Paso 3: Dibujar el Círculo Central**

1. Mantén presionada la **Herramienta Rectángulo** y selecciona **Herramienta Elipse**
   ![](../src/cancha/04_seleccionar_herramienta_elipse.png)
2. Dibuja un círculo en el centro de la cancha
![](../src/cancha/05_dibuja_elipse.png)
3. Selecciona ambos objetos (rectángulo y círculo)
4. En el panel **Alinear**, selecciona "Alinear a la mesa de trabajo"
5. Alinea ambos objetos al centro vertical y horizontalmente

![Círculo central](../src/cancha/06_alineacion_al_centro.png)

---

#### **Paso 4: Trazar la Línea Central**

1. Selecciona la **Herramienta Pluma**
![](../src/cancha/07_trazo_recta_pluma.png)
2. Haz clic en un punto del lado izquierdo del rectángulo
3. Haz clic en el punto correspondiente del lado derecho, creando una línea horizontal que pase por el centro del círculo
4. Establece el grosor del trazado en **5 puntos**
![](../src/cancha/07_trazo_recta_pluma.png)


---

#### **Paso 5: Crear las Áreas de la Cancha**

1. **Clonar el círculo central**:
   - Selecciona el círculo
   - Presiona **Alt + arrastrar** para crear una copia
   - Coloca la copia en la parte inferior de la cancha
![](../src/cancha/08_clonar_circulo_central.png)

2. **Convertir en semicírculo**:
   - Selecciona la **Herramienta Selección Directa**
   - Haz clic en el nodo inferior del círculo clonado
   ![](../src/cancha/09_seleccionar%20nodo_inferior.png)
   - Presiona **Supr** para eliminarlo, creando un semicírculo
   ![](../src/cancha/10_suprimir_nodo.png)

3. **Crear el rectángulo del área**:
   - Dibuja un rectángulo pequeño debajo del semicírculo
   - Ajusta su tamaño para formar el área de la cancha
   ![](../src/cancha/11_rectangulo_inferior.png)


---

#### **Paso 6: Escalar y Ajustar el Semicírculo**

1. Clona el semicírculo con **Alt + arrastrar**
![](../src/cancha/12_conamos_semicirculo.png)
2. Escala el nuevo semicírculo manteniendo presionada **Shift** para proporción
![](../src/cancha/13_shif_escalar_semicirculo.png)
3. Usa la **Herramienta Pluma** para añadir nodos donde el semicírculo intersecta con el borde
![](../src/cancha/14_herramienta_pluma_colocar_nodo.png)
4. Elimina los nodos sobrantes con **Selección Directa + Supr**
![](../src/cancha/16_seleccionar_nodo_eliminar.png)
![](../src/cancha/15_eliminamos_nodo.png)
- Resultado
![](../src/cancha/17_resultado_eliminar_nodos.png)


---

#### **Paso 7: Crear el Espejo del Área Superior**

1. Selecciona todos los elementos del área inferior (**Shift + clic**)
![](../src/cancha/18_selecciona_elementos.png)
2. Clona el grupo con **Alt + arrastrar**
![](../src/cancha/19_clonamos_elementos.png)
3. Con el grupo seleccionado, con transformar rotamos los objetos 180° para quedar volteados verticalmente
![](../src/cancha/20_rotar_elementos.png)
![](../src/cancha/21_resultado_rotar.png)
![](../src/cancha/22_resultado_cancha_sin_color.png)

---

#### **Paso 8: Aplicar Colores de la Paleta**

1. Descarga el archivo de vectores con la paleta de colores NBA en el repositorio 👉👉 [vectores NBA](./vectores%20NBA.ai) 👈👈
2. Abre el proyecto en illustrator
![](../src/cancha/23_abrir_vectores.png)
2. Copia los elementos (**Ctrl + C**) y pégalos en tu documento (**Ctrl + V**)
![](../src/cancha/24_seleccionar_vectores.png)
![](../src/cancha/25_cambiar_al_proyecto.png)
![](../src/cancha/26_pegar_vectores.png)
3. Usa la **Herramienta Cuentagotas** para aplicar colores:
   - Selecciona cada elemento de la cancha
   ![](../src/cancha/27_selecciona_objeto.png)
   - Usa el cuentagotas sobre los colores de la paleta
   ![](../src/cancha/28_cuentagotas.png)
   - Repite hasta colorear todos los elementos de la cancha
   ![](../src/cancha/29_resultado_cancha_color.png)

4. **Aplicar color blanco**:
   - Selecciona el contorno, círculo central y línea divisoria
   ![](../src/cancha/30_selecciona_cancha.png)
   - Establece el color del trazado en blanco
   ![](../src/cancha/31_borde_blanco.png)



---

#### **Paso 9: Exportar a Photoshop para Perspectiva**

1. En Illustrator, selecciona todos los elementos de la cancha (**Ctrl + A**)
2. Copia la selección (**Ctrl + C**)
3. Abre Photoshop y crea un nuevo documento **1080 x 1920 píxeles**
![](../src/cancha/32_nuevo_photoshop.png)
4. Pega los elementos (**Ctrl + V**) y selecciona "Objeto Inteligente"
![](../src/cancha/33_pegar_objeto_inteligente.png)
![](../src/cancha/34_pegado_photoshop.png)
5. Convierte la capa a Objeto Inteligente (clic derecho > Convertir en objeto inteligente)
![](../src/cancha/35_selecciona_capa.png)
![](../src/cancha/36_convertir_inteligente.png)

---

#### **Paso 10: Aplicar Perspectiva Realista**

1. Selecciona la capa del objeto inteligente
2. Presiona **Ctrl + T** para transformar
![](../src/cancha/37_ctrl_T.png)
3. Mantén presionada **Ctrl** y arrastra los puntos de esquina para crear perspectiva
4. Ajusta hasta lograr un ángulo realista
![](../src/cancha/38_genera_perspectiva.png)

---

#### **Paso 11: Añadir Elementos de Diseño**

1. **Fondo**:
   - Usa la **Herramienta Cuentagotas** para seleccionar un color de la composición
![](../src/cancha/39_selecciona_color_cuentagotas.png)
   - Rellena la capa de fondo con **Alt + Supr**
   ![](../src/cancha/40_rellena_color_fondo.png)

2. **Logo y balón**:
   - Copia el logo NBA y el balón desde Illustrator
   ![](../src/cancha/41_selecciona_vector_illustrator.png)
   ![](../src/cancha/43_seleccionar_balon.png)
   - Pega como objetos inteligentes en Photoshop
   - Posiciona estratégicamente en la composición
   ![](../src/cancha/42_colocamos_logo.png)



---

#### **Paso 12: Crear Sombra del Balón**

1. Crea una nueva capa entre el balón y la cancha
   ![](../src/cancha/44_añadir_capa.png)
2. Nombra la capa "Sombra balón"
3. Usa la **Herramienta Elipse** para seleccionar el área de sombra
![](../src/cancha/45_seleccionar_elipse.png)
4. Rellena con un color oscuro de la paleta
5. Ajusta la opacidad si es necesario
![](../src/cancha/46_color_sombra.png)



---

#### **Paso 13: Unificar y Aplicar Textura**

1. Selecciona todas las capas visibles manteniendo **Shift**
2. Ve a **Capa > Combinar visibles** (mantén **Alt** para preservar originales)
![](../src/cancha/47_combinar_capa.png)
3. Oculta las capas originales
![](../src/cancha/48_ocultamos_capas.png)
4. Aplica textura: **Filtro > Ruido > Añadir ruido**
![](../src/cancha/49_filtro_ruido.png)
5. Establece la cantidad en **8%**
![](../src/cancha/50_ruido_8pt.png)

![](../src/cancha/51_resultado_ruido.png)

---

#### **Paso 14: Guardar el Resultado Final**

1. Ve a **Archivo > Guardar como**
2. Elige formato JPEG o PNG
3. Nombra el archivo "Cancha_Baloncesto_Final"

---

### **Resultado Final**

![Resultado final](../src/cancha/52_cancha_terminada.png)

### **Consejos Adicionales**

- **Organización de capas**: Nombra cada capa claramente para fácil edición
- **Objetos inteligentes**: Mantén elementos como objetos inteligentes para escalado sin pérdida
- **Experimenta con colores**: Prueba diferentes paletas para variaciones del diseño
- **Añade elementos**: Jugadores, marcadores o gradas para mayor realismo

¡Has creado una cancha de baloncesto profesional con perspectiva realista! Esta práctica te ha enseñado flujo de trabajo entre Illustrator y Photoshop, técnicas de perspectiva y diseño deportivo.