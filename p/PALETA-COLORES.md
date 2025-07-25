# 🎨 Paleta de Colores - Pablo Esmoris

## Nueva Identidad Visual: Negro + Violeta Neón

### **🎯 Concepto de Diseño**
Paleta moderna y profesional que combina la elegancia del negro con la innovación del violeta neón, creando una identidad visual única para un gasista plomero de vanguardia.

## 🎨 **Variables CSS Principales**

### **Colores Base:**
```css
--primary-black: #1a1a1a        /* Negro principal - fondos */
--secondary-black: #2d2d2d      /* Negro secundario - tarjetas */
--neon-violet: #8b5cf6          /* Violeta neón principal */
--neon-violet-bright: #a855f7   /* Violeta neón brillante - hover */
--neon-violet-dark: #7c3aed     /* Violeta neón oscuro - sombras */
```

### **Colores de Acento:**
```css
--accent-gold: #ffd700          /* Dorado - elementos destacados */
--accent-gold-light: #ffed4e    /* Dorado claro - gradientes */
--blue-primary: #2a5298         /* Azul corporativo - respaldo */
--blue-secondary: #1e3c72       /* Azul oscuro - respaldo */
```

### **Colores de Texto:**
```css
--text-white: #ffffff           /* Texto principal */
--text-light: #f8f9fa          /* Texto secundario */
--text-gray: #666666           /* Texto deshabilitado */
--bg-light: #f8f9fa            /* Fondo claro alternativo */
```

### **Efectos Especiales:**
```css
--shadow-neon: rgba(139, 92, 246, 0.3)  /* Sombra violeta neón */
```

## 🌈 **Gradientes Principales**

### **Gradiente Principal (Header/Nav):**
```css
--gradient-main: linear-gradient(135deg, 
    var(--primary-black) 0%, 
    var(--neon-violet) 50%, 
    var(--secondary-black) 100%);
```

### **Gradiente Hero:**
```css
--gradient-hero: linear-gradient(135deg, 
    var(--neon-violet) 0%, 
    var(--primary-black) 50%, 
    var(--neon-violet-dark) 100%);
```

### **Gradiente Tarjetas:**
```css
--gradient-card: linear-gradient(145deg, 
    var(--secondary-black) 0%, 
    var(--primary-black) 100%);
```

## ✨ **Efectos Especiales Implementados**

### **1. Glow Effects (Resplandor):**
- Texto del logo con resplandor neón
- Botones con sombras de colores
- Iconos con filtros de resplandor
- Bordes que brillan al hover

### **2. Animaciones:**
```css
@keyframes glow {
    from { text-shadow: 0 0 15px var(--accent-gold); }
    to { text-shadow: 0 0 25px var(--accent-gold), 0 0 35px var(--accent-gold); }
}
```

### **3. Efectos de Hover:**
- Transformaciones 3D
- Cambios de color suaves
- Sombras animadas
- Resplandor en elementos interactivos

### **4. Backdrop Effects:**
- Blur en elementos superpuestos
- Gradientes radiales de fondo
- Efectos de profundidad

## 🎯 **Aplicación por Secciones**

### **Header/Navegación:**
- Fondo: Gradiente principal
- Texto: Blanco con resplandor
- Hover: Violeta neón + dorado
- Sombra: Resplandor violeta

### **Hero Section:**
- Fondo: Gradiente hero + efectos radiales
- Títulos: Gradiente de texto blanco a dorado
- Subtítulo: Dorado con animación glow
- Botones: Dorado primario / Violeta secundario

### **Servicios:**
- Fondo: Negro secundario
- Tarjetas: Gradiente negro + borde violeta
- Hover: Resplandor violeta + elevación
- Iconos: Violeta con resplandor

### **Galería:**
- Items: Borde violeta + sombra negra
- Hover: Resplandor violeta brillante
- Placeholder: Gradiente de tarjeta

### **Footer:**
- Fondo: Negro principal
- Borde superior: Gradiente violeta-dorado-violeta
- Acentos: Dorado con resplandor

## 🚀 **Beneficios del Diseño**

### **✅ Profesionalismo:**
- Negro transmite elegancia y confianza
- Violeta neón añade modernidad e innovación
- Dorado aporta calidez y calidad premium

### **✅ Legibilidad:**
- Alto contraste entre texto y fondo
- Jerarquía visual clara
- Elementos destacados fáciles de identificar

### **✅ Modernidad:**
- Efectos neón que siguen tendencias actuales
- Gradientes suaves y profesionales
- Animaciones sutiles que mejoran UX

### **✅ Coherencia:**
- Sistema de variables CSS consistente
- Colores aplicados uniformemente
- Efectos coordinados en toda la aplicación

## 🔧 **Personalización Fácil**

Para cambiar los colores principales, solo modifica las variables en `:root`:

```css
:root {
    --neon-violet: #tu-nuevo-color;
    --accent-gold: #tu-dorado-personalizado;
    --primary-black: #tu-negro-preferido;
}
```

## 📊 **Accesibilidad**

- ✅ Contraste WCAG AA cumplido
- ✅ Texto legible en todos los fondos
- ✅ Elementos interactivos claramente identificables
- ✅ Estados de hover y focus visibles

---

**¡La nueva paleta de colores da al sitio de Pablo Esmoris una identidad visual única, moderna y profesional que lo diferencia de la competencia!**
