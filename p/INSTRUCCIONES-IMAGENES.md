# Instrucciones para subir imágenes reales

## 📸 **Cómo agregar imágenes al sitio web de Pablo Esmoris**

### **Paso 1: Preparar las imágenes**

#### **Imágenes principales necesarias:**

1. **`logo.png`** (200x200px)
   - Logo del negocio o iniciales "PE"
   - Fondo transparente
   - Formato PNG

2. **`hero-image.jpg`** (1200x800px)
   - Imagen principal del sitio
   - Pablo trabajando o herramientas profesionales
   - Formato JPG, máximo 500KB

3. **`about-pablo.jpg`** (600x600px)
   - Foto profesional de Pablo
   - Bien iluminada y clara
   - Formato JPG, máximo 300KB

#### **Imágenes de servicios** (300x200px cada una):
- `servicios/instalacion-gas.jpg` - Instalación de artefactos
- `servicios/reparaciones.jpg` - Herramientas o reparación
- `servicios/certificaciones.jpg` - Certificado o documentos
- `servicios/plomeria.jpg` - Trabajo de plomería
- `servicios/mantenimiento.jpg` - Mantenimiento preventivo
- `servicios/emergencias.jpg` - Servicio de emergencia

#### **Galería de trabajos** (400x300px cada una):
- `galeria/trabajo1.jpg` - Instalación de termotanque
- `galeria/trabajo2.jpg` - Reparación de calefón
- `galeria/trabajo3.jpg` - Instalación de cocina
- `galeria/trabajo4.jpg` - Certificación de gas
- `galeria/trabajo5.jpg` - Reparación de plomería
- `galeria/trabajo6.jpg` - Mantenimiento preventivo

### **Paso 2: Optimizar las imágenes**

#### **Herramientas recomendadas para optimizar:**
- **TinyPNG** (https://tinypng.com/) - Comprimir sin perder calidad
- **Squoosh** (https://squoosh.app/) - Editor online de Google
- **GIMP** o **Photoshop** - Para redimensionar

#### **Configuraciones recomendadas:**
- **Calidad JPG:** 80-85%
- **Formato PNG:** Solo para logos con transparencia
- **Tamaño máximo:** Como se especifica arriba

### **Paso 3: Subir las imágenes**

#### **Opción A: Via VS Code (recomendada)**
1. Abre VS Code en tu workspace
2. Navega a la carpeta `/p/images/`
3. Arrastra y suelta las imágenes desde tu computadora
4. Respeta exactamente los nombres de archivo especificados

#### **Opción B: Via GitHub Web**
1. Ve a https://github.com/runeimport/KoriWeb
2. Navega a la carpeta `p/images/`
3. Haz clic en "Add file" > "Upload files"
4. Arrastra las imágenes o selecciónalas
5. Haz commit de los cambios

#### **Opción C: Via Git Command Line**
```bash
cd /workspaces/KoriWeb/p/images/
# Copia tus imágenes aquí
git add .
git commit -m "Agregar imágenes reales al sitio"
git push origin main
```

### **Paso 4: Verificar el resultado**

Una vez subidas las imágenes:
1. El sitio se actualizará automáticamente en GitHub Pages
2. Visita: https://runeimport.github.io/KoriWeb/p/
3. Las imágenes reemplazarán automáticamente los iconos

### **🔄 Fallback automático**

Si una imagen no se encuentra o no carga:
- Se mostrará automáticamente el icono correspondiente
- El sitio seguirá funcionando perfectamente
- Puedes subir las imágenes gradualmente

### **📱 Compatibilidad**

Las imágenes están optimizadas para:
- ✅ Desktop
- ✅ Tablet  
- ✅ Mobile
- ✅ Retina displays

### **⚡ Rendimiento**

El código incluye:
- Lazy loading automático
- Compresión de imágenes
- Formatos optimizados
- Fallbacks instantáneos

### **❓ Problemas comunes**

**Si una imagen no aparece:**
1. Verifica el nombre exacto del archivo
2. Asegúrate de que esté en la carpeta correcta
3. Comprueba que el formato sea correcto (JPG/PNG)
4. Refresca la página con Ctrl+F5

**Si el sitio se ve lento:**
1. Comprime más las imágenes
2. Reduce el tamaño si es necesario
3. Usa formato WebP si es posible

### **✅ Lista de verificación**

- [ ] Logo subido (`logo.png`)
- [ ] Imagen principal subida (`hero-image.jpg`)
- [ ] Foto de Pablo subida (`about-pablo.jpg`)
- [ ] 6 imágenes de servicios subidas
- [ ] Al menos 3 imágenes de galería subidas
- [ ] Todas las imágenes optimizadas
- [ ] Sitio verificado en móvil y desktop

Una vez completado, ¡tu sitio tendrá un aspecto completamente profesional con imágenes reales!
