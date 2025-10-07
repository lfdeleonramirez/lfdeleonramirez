<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luis Fernando de León Ramírez | Cloud Architect</title>
    <!-- Carga de Tailwind CSS para estilos modernos y responsivos -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Fuente global e interacciones */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body { font-family: 'Inter', sans-serif; }
        .hover-lift:hover { transform: translateY(-5px); box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05); }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 p-4 sm:p-8">

    <!-- HEADER & BIENVENIDA -->
    <header class="mb-10">
        <h1 class="text-4xl sm:text-5xl font-extrabold text-blue-800 flex items-center mb-2">
            <span class="mr-3 text-5xl sm:text-6xl">☁️</span> Luis Fernando de León Ramírez
        </h1>
        <h2 class="text-xl sm:text-2xl font-semibold text-gray-600 border-b-4 border-yellow-400 inline-block pb-1">
            Cloud Architect & GitOps Transformer
        </h2>
        
        <!-- Contador de Vistas (Alineado al centro como badge) -->
        <div class="mt-4 flex justify-center">
            <img class="rounded-lg shadow-md" src="https://komarev.com/ghpvc/?username=YOUR_GITHUB_USERNAME&style=for-the-badge&color=blue" alt="Profile views" />
        </div>

        <p class="mt-6 text-lg">
            👋 ¡Hola! Soy un Arquitecto e Ingeniero Cloud con una base sólida en Seguridad Informática (Maestría, 2022). Mi misión es transformar la infraestructura tradicional en 
            <span class="font-bold text-blue-700">ecosistemas de nube automatizados, seguros y con despliegues continuos</span>. Especializado en la creación de soluciones 
            <span class="font-semibold text-blue-600">Cloud-Native en AWS</span>, llevando la arquitectura de contenedores (**Kubernetes/EKS**) a su máximo potencial mediante la filosofía **GitOps (ArgoCD)**.
        </p>
    </header>

    <!-- STACK DE ESPECIALIZACIÓN (Usando Grid y Tarjetas) -->
    <section class="mb-12">
        <h3 class="text-3xl font-bold text-gray-700 mb-6 border-l-4 border-yellow-500 pl-3">🧠 Mi Stack de Especialización</h3>
        
        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            
            <!-- Tarjeta 1: Nube & Infraestructura -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-blue-500 hover-lift transition duration-300">
                <h4 class="text-xl font-bold text-blue-600 mb-3">Nube & Infraestructura</h4>
                <ul class="list-disc list-inside space-y-1 text-sm">
                    <li>**AWS** (EKS, EC2, VPC, **EFS**, S3, IAM, CloudFormation)</li>
                    <li>**IAC:** Terraform / CloudFormation</li>
                    <li>**Middleware:** SQS, SNS, RDS, ElastiCache</li>
                </ul>
            </div>

            <!-- Tarjeta 2: Contenedores & Orquestación -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-green-500 hover-lift transition duration-300">
                <h4 class="text-xl font-bold text-green-600 mb-3">Contenedores & Orquestación</h4>
                <ul class="list-disc list-inside space-y-1 text-sm">
                    <li>**Kubernetes** (EKS, MicroK8s, Networking)</li>
                    <li>**GitOps:** ArgoCD / Gestión declarativa</li>
                    <li>**Monitoreo:** AWS CloudWatch, Prometheus (Conceptual)</li>
                </ul>
            </div>

            <!-- Tarjeta 3: Desarrollo & Servicios -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-yellow-500 hover-lift transition duration-300">
                <h4 class="text-xl font-bold text-yellow-600 mb-3">Desarrollo & Servicios</h4>
                <ul class="list-disc list-inside space-y-1 text-sm">
                    <li>Java / Spring / Microservicios</li>
                    <li>**Frontend:** Angular / TypeScript</li>
                    <li>**Seguridad:** OAuth2, JWT, IAM Roles</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- PROYECTOS CLAVE -->
    <section class="mb-12">
        <h3 class="text-3xl font-bold text-gray-700 mb-6 border-l-4 border-yellow-500 pl-3">🛠️ Proyectos de Arquitectura Clave</h3>
        
        <div class="space-y-8">
            <!-- Proyecto 1 -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-l-8 border-indigo-500">
                <h4 class="text-2xl font-semibold text-indigo-700 mb-2">1. 🛡️ Implementación de Arquitectura de Microservicios Seguros</h4>
                <p class="mb-3 text-gray-600">
                    Transformación de aplicaciones monolíticas a una arquitectura distribuida y escalable.
                </p>
                <p class="text-sm font-medium">
                    <span class="text-indigo-500">Valor Añadido:</span> Desarrollé la integración de **autenticación OAuth2** con tokens JWT, asegurando la comunicación entre servicios.
                </p>
            </div>

            <!-- Proyecto 2 -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-l-8 border-indigo-500">
                <h4 class="text-2xl font-semibold text-indigo-700 mb-2">2. 🚀 De la Laptop a la Nube: Flujos GitOps con ArgoCD</h4>
                <p class="mb-3 text-gray-600">
                    Apliqué la filosofía GitOps para automatizar la promoción de código a producción, minimizando errores humanos.
                </p>
                <p class="text-sm font-medium">
                    <span class="text-indigo-500">Clave:</span> Uso de **`ApplicationSet`** y mi experiencia se centra en el **traslado inmediato de aplicaciones a producción** (`20/09/2024 - Actual`).
                </p>
            </div>

            <!-- Proyecto 3 -->
            <div class="bg-white p-6 rounded-xl shadow-lg border-l-8 border-indigo-500">
                <h4 class="text-2xl font-semibold text-indigo-700 mb-2">3. 🌐 Despliegue de Aplicaciones en Entornos Híbridos (AWS & On-Premises)</h4>
                <p class="mb-3 text-gray-600">
                    Administración de la plataforma de nube que incluye despliegues a la nube pública y a entornos de clústeres on-premises (**Tanzu**).
                </p>
                <p class="text-sm font-medium">
                    <span class="text-indigo-500">Enfoque:</span> Diseño de **infraestructura como código (IaC)** para garantizar la paridad de configuración y la resiliencia.
                </p>
            </div>
        </div>
    </section>

    <!-- ACTIVIDAD Y CONTACTO (Grid inferior) -->
    <section class="mb-12 grid grid-cols-1 lg:grid-cols-2 gap-8">
        
        <!-- Columna 1: Actividad Técnica (Estadísticas) -->
        <div class="bg-white p-6 rounded-xl shadow-lg">
            <h3 class="text-2xl font-bold text-gray-700 mb-4 flex items-center">
                📈 Mi Actividad Técnica
            </h3>
            <div class="flex flex-col space-y-4">
                <a href="https://github.com/YOUR_GITHUB_USERNAME">
                    <img class="w-full rounded-lg" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=buefy&hide_rank=true" alt="Estadísticas de GitHub" />
                </a>
                <a href="https://github.com/YOUR_GITHUB_USERNAME">
                    <img class="w-full rounded-lg" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=buefy" alt="Lenguajes más usados" />
                </a>
                <p class="text-xs text-center text-gray-500 mt-2">
                    *(Recuerda reemplazar YOUR_GITHUB_USERNAME en los enlaces para que funcionen)*
                </p>
            </div>
        </div>

        <!-- Columna 2: Conectemos -->
        <div class="bg-white p-6 rounded-xl shadow-lg border-t-4 border-red-500">
            <h3 class="text-2xl font-bold text-gray-700 mb-4 flex items-center">
                🤝 Conectemos
            </h3>
            <p class="mb-4 text-gray-600">
                Siempre estoy disponible para discutir retos de arquitectura en AWS, optimización de clústeres de EKS, o soluciones de integración de autenticación.
            </p>
            
            <div class="flex flex-col space-y-4">
                <!-- Email -->
                <a href="mailto:luisdeleonramirez@outlook.com" class="flex items-center text-lg text-gray-700 hover:text-blue-600 font-medium transition duration-200">
                    <span class="mr-3 text-xl">📧</span> luisdeleonramirez@outlook.com
                </a>
                <!-- LinkedIn -->
                <a href="https://www.linkedin.com/in/luis-fernando-de-leon-ramirez-a00a2a17a" target="_blank" class="flex items-center text-lg text-gray-700 hover:text-blue-600 font-medium transition duration-200">
                    <img class="mr-3" src="https://img.shields.io/badge/-LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn Badge" />
                    Perfil de LinkedIn
                </a>
            </div>

            <!-- Frase de cierre -->
            <p class="mt-8 text-sm text-gray-500 italic text-right">
                Infraestructura como código, código como arte.
            </p>
        </div>

    </section>

</body>
</html>
