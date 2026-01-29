# Investigación de Stack Tecnológico: Supabase

## 1. Entorno de Edición (IDE)
* **Herramienta:** VS Code.
* **Justificación:** Es el estándar de la industria por su ligereza. Utilizan extensiones como **ESLint** y **Prettier** para automatizar la corrección de errores de sintaxis y mantener un estilo de código uniforme en todo su repositorio abierto.

## 2. Ecosistema de Navegación
* **Herramientas:** Google Chrome y Firefox.
* **Justificación:** Al desarrollar herramientas para desarrolladores, necesitan asegurar que su consola de administración funcione perfectamente en motores Chromium y Gecko, que son los más usados por programadores.

## 3. Gestión de Versiones
* **Herramientas:** Git y GitHub.
* **Justificación:** Como proyecto Open Source, GitHub es esencial para recibir colaboraciones de miles de desarrolladores externos de forma organizada mediante Pull Requests.

## 4. Diseño UI/UX
* **Herramienta:** Figma.
* **Justificación:** Permite la colaboración en tiempo real entre diseñadores y desarrolladores, facilitando el paso de componentes visuales a código de React/Tailwind de forma precisa.

## 5. Lenguajes y Herramientas Base
* **Lenguajes:** TypeScript, HTML5, CSS3.
* **Herramienta Moderna Detectada:** **Tailwind CSS**.
* **Justificación:** Utilizan Tailwind para el diseño de su interfaz porque permite iterar estilos rápidamente sin salir del archivo de código, lo que acelera el desarrollo de su dashboard.

## 6. Fuentes de Investigación
Para validar la información de este reporte, se consultaron las siguientes fuentes oficiales y herramientas de análisis técnico:

* **Repositorio Oficial de Supabase:** [github.com/supabase/supabase](https://github.com/supabase/supabase) - Consulta de lenguajes base (TypeScript) y herramientas de configuración (ESLint/Prettier).
* **StackShare - Perfil de Supabase:** [stackshare.io/supabase/supabase](https://stackshare.io/supabase/supabase) - Identificación del stack de frontend (React, Next.js) y diseño (Figma).
* **Wappalyzer:** Análisis en tiempo real de la arquitectura web de [supabase.com](https://supabase.com).
* **Supabase Engineering Blog:** [supabase.com/blog](https://supabase.com/blog) - Revisión de artículos técnicos sobre su infraestructura y uso de Next.js.
## Evidencias
### Captura 1: Stack tecnológico en StackShare
<img width="1299" height="872" alt="image" src="https://github.com/user-attachments/assets/8f3274b4-7309-4126-b294-8b908a2c05c8" />

### Captura 2: Repositorio oficial y lenguajes en GitHub
<img width="825" height="395" alt="image" src="https://github.com/user-attachments/assets/8976b665-3619-453e-9125-912048ff788b" />

### Captura 3: Análisis de tecnologías con Wappalyzer
<img width="498" height="545" alt="image" src="https://github.com/user-attachments/assets/68bfa02e-153b-41bf-91e7-ef7a9d6565a9" />

### captura 4. Entorno de Edición (IDE)
<img width="1889" height="870" alt="Screenshot 2026-01-29 091536" src="https://github.com/user-attachments/assets/1e0270a3-8272-4c60-9152-b2c4384adbf9" />

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mapa Conceptual: Ruta de Desarrollo Web Profesional</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            background: radial-gradient(circle at center, #1e293b 0%, #0f172a 100%);
            color: #f1f5f9;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            min-height: 100vh;
        }
        .node {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            background: rgba(30, 41, 59, 0.7);
            backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .node:hover {
            transform: translateY(-8px);
            border-color: rgba(255, 255, 255, 0.3);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3);
        }
        .category-title {
            font-weight: 800;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            font-size: 0.85rem;
        }
    </style>
</head>
<body class="p-6 md:p-12">
    <div class="max-w-7xl mx-auto">
        <header class="text-center mb-16">
            <h1 class="text-4xl md:text-6xl font-black text-transparent bg-clip-text bg-gradient-to-r from-blue-400 via-cyan-400 to-emerald-400 mb-4">
                Ecosistema del Desarrollador Web
            </h1>
            <p class="text-slate-400 text-lg max-w-3xl mx-auto font-light">
                Una visión integral de las tecnologías, metodologías y habilidades necesarias para dominar la web profesional en 2026.
            </p>
        </header>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Bloque 1: Fundamentos Técnicos -->
            <div class="node p-8 rounded-3xl border-t-4 border-orange-500 shadow-2xl">
                <h2 class="category-title text-orange-500 mb-6 flex items-center">
                    <span class="text-2xl mr-3">🚀</span> 1. Fundamentos Base
                </h2>
                <div class="space-y-4 text-sm leading-relaxed">
                    <p><strong class="text-orange-300">HTML5:</strong> No es programación, es la semántica. Define qué es un título, un párrafo o un formulario.</p>
                    <p><strong class="text-blue-300">CSS3:</strong> Maquetación avanzada. Uso de <strong>Flexbox</strong> y <strong>Grid</strong> para diseños complejos y <strong>Media Queries</strong> para adaptabilidad móvil.</p>
                    <p><strong class="text-yellow-300">JavaScript (ES6+):</strong> El motor. Maneja la lógica asíncrona mediante <strong>Promesas</strong> y <strong>Async/Await</strong>.</p>
                    <div class="pt-4 border-t border-slate-700">
                        <span class="text-xs text-slate-500 uppercase font-bold">Extensiones Críticas:</span>
                        <ul class="list-disc list-inside mt-2 text-slate-400">
                            <li>Sass / PostCSS (Estilos)</li>
                            <li>TypeScript (Seguridad de tipos)</li>
                            <li>DOM Manipulation (Interactividad)</li>
                        </ul>
                    </div>
                </div>
            </div>

            <!-- Bloque 2: Roles y Arquitectura -->
            <div class="node p-8 rounded-3xl border-t-4 border-emerald-500 shadow-2xl">
                <h2 class="category-title text-emerald-500 mb-6 flex items-center">
                    <span class="text-2xl mr-3">🏗️</span> 2. Especialización
                </h2>
                <div class="space-y-6">
                    <div class="p-4 bg-slate-900/40 rounded-xl border border-emerald-900/30">
                        <h3 class="font-bold text-emerald-300 mb-2">Frontend</h3>
                        <p class="text-xs text-slate-300">Interfaz de usuario (UI) y experiencia (UX). Dominio de Frameworks como <strong>React, Vue o Angular</strong>.</p>
                    </div>
                    <div class="p-4 bg-slate-900/40 rounded-xl border border-emerald-900/30">
                        <h3 class="font-bold text-emerald-300 mb-2">Backend</h3>
                        <p class="text-xs text-slate-300">Lógica de servidor, APIs (REST/GraphQL) y Bases de Datos (SQL/NoSQL). Seguridad y escalabilidad.</p>
                    </div>
                    <div class="p-4 bg-slate-900/40 rounded-xl border border-emerald-900/30">
                        <h3 class="font-bold text-emerald-300 mb-2 text-center italic">Fullstack Developer</h3>
                        <p class="text-[10px] text-center text-slate-500 mt-1">El perfil híbrido que domina ambos mundos.</p>
                    </div>
                </div>
            </div>

            <!-- Bloque 3: Herramientas del Entorno -->
            <div class="node p-8 rounded-3xl border-t-4 border-purple-500 shadow-2xl">
                <h2 class="category-title text-purple-500 mb-6 flex items-center">
                    <span class="text-2xl mr-3">🛠️</span> 3. Entorno de Trabajo
                </h2>
                <ul class="space-y-4 text-sm">
                    <li class="flex items-start">
                        <span class="text-purple-400 mr-2">💻</span>
                        <span><strong>Terminal:</strong> Indispensable para automatizar tareas, usar SSH y ejecutar comandos de Node.js.</span>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 mr-2">🌿</span>
                        <span><strong>Git / GitHub:</strong> No es solo guardar archivos, es gestionar el historial y colaborar mediante Pull Requests.</span>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 mr-2">☁️</span>
                        <span><strong>Cloud & CI/CD:</strong> Despliegue automático en Vercel, Netlify o AWS. Pruebas automáticas antes de producción.</span>
                    </li>
                    <li class="flex items-start">
                        <span class="text-purple-400 mr-2">📦</span>
                        <span><strong>NPM / Yarn:</strong> Gestión de dependencias y librerías externas.</span>
                    </li>
                </ul>
            </div>

            <!-- Bloque 4: Calidad y Principios -->
            <div class="node p-8 rounded-3xl border-t-4 border-rose-500 shadow-2xl lg:col-span-2">
                <h2 class="category-title text-rose-500 mb-6 flex items-center">
                    <span class="text-2xl mr-3">💎</span> 4. Filosofía y Buenas Prácticas
                </h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="space-y-4">
                        <div class="bg-rose-900/10 p-4 rounded-xl">
                            <h4 class="font-bold text-rose-300 text-sm">Legibilidad del Código</h4>
                            <p class="text-xs text-slate-400 mt-1">El código se lee mucho más de lo que se escribe. Usa nombres de variables claros y evita la complejidad innecesaria.</p>
                        </div>
                        <div class="bg-rose-900/10 p-4 rounded-xl">
                            <h4 class="font-bold text-rose-300 text-sm">Accesibilidad (A11y)</h4>
                            <p class="text-xs text-slate-400 mt-1">Programar para todos. Uso de etiquetas ARIA y contraste adecuado para usuarios con discapacidades.</p>
                        </div>
                    </div>
                    <div class="space-y-4">
                        <div class="bg-rose-900/10 p-4 rounded-xl">
                            <h4 class="font-bold text-rose-300 text-sm">Rendimiento (Performance)</h4>
                            <p class="text-xs text-slate-400 mt-1">Optimización de imágenes, carga asíncrona y reducción del bundle de JavaScript para webs rápidas.</p>
                        </div>
                        <div class="bg-rose-900/10 p-4 rounded-xl">
                            <h4 class="font-bold text-rose-300 text-sm">SEO Técnico</h4>
                            <p class="text-xs text-slate-400 mt-1">Estructura de datos y etiquetas Meta para que Google entienda y posicione tu sitio web.</p>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Bloque 5: El Futuro (IA) -->
            <div class="node p-8 rounded-3xl border-t-4 border-cyan-500 shadow-2xl">
                <h2 class="category-title text-cyan-500 mb-6 flex items-center">
                    <span class="text-2xl mr-3">🤖</span> 5. El Factor IA
                </h2>
                <p class="text-sm text-slate-300 mb-4">
                    La IA no reemplaza al programador, pero el programador que usa IA reemplaza al que no.
                </p>
                <ul class="text-xs space-y-2 text-slate-400">
                    <li>• GitHub Copilot / Cursor como copilotos.</li>
                    <li>• Generación de pruebas unitarias.</li>
                    <li>• Optimización de algoritmos complejos.</li>
                    <li>• Depuración rápida de errores.</li>
                </ul>
            </div>

        </div>

        <footer class="mt-20 py-8 border-t border-slate-800 text-center text-slate-500">
            <p class="text-sm">Ruta inspirada en el análisis de Freddy Vega (Platzi) sobre el mercado laboral tecnológico.</p>
            <div class="mt-4 flex justify-center gap-6">
                <span class="flex items-center"><span class="w-2 h-2 bg-orange-500 rounded-full mr-2"></span> Estructura</span>
                <span class="flex items-center"><span class="w-2 h-2 bg-emerald-500 rounded-full mr-2"></span> Lógica</span>
                <span class="flex items-center"><span class="w-2 h-2 bg-purple-500 rounded-full mr-2"></span> Herramientas</span>
            </div>
        </footer>
    </div>
</body>
</html>

### captura 5. Diseño UI/UX
<img width="1903" height="989" alt="image" src="https://github.com/user-attachments/assets/7796e079-2831-4bef-9157-c3a2fc99cd34" />

