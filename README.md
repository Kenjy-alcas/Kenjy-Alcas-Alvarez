<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Infográfico | Kenjy Alcas - Especialista en Marketing Digital</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #F8F9FA;
            color: #212529;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 320px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
        .brand-text-yellow { color: #F9D423; }
        .brand-text-orange { color: #FC913A; }
        .brand-text-red { color: #FF4E50; }
        .brand-bg-yellow { background-color: #F9D423; }
        .brand-bg-orange { background-color: #FC913A; }
        .brand-bg-red { background-color: #FF4E50; }
        .brand-bg-light-yellow { background-color: #EDE574; }
        .brand-bg-pale-green { background-color: #E1F5C4; }
        .flowchart-node {
            border: 2px solid #FC913A;
            background-color: white;
            padding: 1rem;
            border-radius: 0.5rem;
            text-align: center;
            font-weight: bold;
            color: #212529;
            flex-grow: 1;
            min-width: 150px;
        }
        .flowchart-arrow {
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
            color: #FC913A;
            margin: 0 0.5rem;
        }
    </style>
</head>
<body class="antialiased">

    <main class="container mx-auto p-4 md:p-8">

        <header class="text-center my-12 md:my-20">
            <h1 class="text-4xl md:text-6xl font-black uppercase">Kenjy Alcas</h1>
            <p class="text-xl md:text-2xl font-bold brand-text-orange mt-2">Especialista en Marketing Digital y Redes Sociales</p>
            <p class="max-w-3xl mx-auto mt-4 text-gray-600">
                Como especialista en marketing digital, combino estrategias de comunicación con soluciones basadas en inteligencia artificial para mejorar la eficiencia y los resultados. He trabajado en la creación de contenidos, automatización de campañas y desarrollo de agentes de IA para atención al cliente. Utilizo herramientas como Make.com, ElevenLabs, ChatGPT y sistemas de automatización para optimizar tareas y facilitar la gestión documental, siempre con un enfoque creativo, tecnológico y orientado a objetivos.
            </p>
        </header>

        <section id="profile-image" class="my-16 flex justify-center">
            <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753352066/IMG-20231213-WA0024_u1csoa.jpg" alt="" class="rounded-full w-64 h-64 md:w-80 md:h-80 object-cover shadow-lg border-4 border-white brand-bg-orange">
        </section>

        <section id="formacion" class="my-16">
            <h2 class="text-3xl font-bold text-center mb-4">Formación</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Mi trayectoria educativa me ha proporcionado una base sólida en marketing digital, inteligencia artificial y diseño, permitiéndome abordar proyectos desde una perspectiva integral y tecnológica.</p>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Técnico Especialista en Soluciones Administrativas con Inteligencia Artificial</h3>
                <p class="text-gray-700 mb-1">Tándem Do AutoGen – Fundación ONCE</p>
                <p class="text-gray-600 text-sm">Automatización de procesos, creación de agentes de IA y desarrollo de flujos inteligentes con herramientas como Make.com, flowise y elevenlabs.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Máster en Marketing Digital y Comunicación Digital</h3>
                <p class="text-gray-700 mb-1">ESIC Business & Marketing School – Por Talento Digital (Fundación ONCE)</p>
                <p class="text-gray-600 text-sm">Estrategias SEO, SEM, redes sociales, analítica digital y automatización aplicada al marketing.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Diseño Gráfico Avanzado (Adobe Photoshop, Illustrator, InDesign)</h3>
                <p class="text-gray-700 mb-1">Por Talento Digital – Fundación ONCE</p>
                <p class="text-gray-600 text-sm">Diseño de piezas visuales para redes sociales, campañas y presentaciones profesionales.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Itinerario de Edición y Postproducción Audiovisual</h3>
                <p class="text-gray-700 mb-1">Por Talento Digital – Fundación ONCE</p>
                <p class="text-gray-600 text-sm">Creación y edición de contenido multimedia para proyectos digitales.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Curso de Emprendimiento</h3>
                <p class="text-gray-700 mb-1">ESADE – Fundación Prevent</p>
                <p class="text-gray-600 text-sm">Desarrollo de ideas de negocio y competencias emprendedoras.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-6">
                <h3 class="text-xl font-bold brand-text-red mb-2">Curso de Contabilidad y Nóminas</h3>
                <p class="text-gray-700 mb-1">Academia Colón</p>
                <p class="text-gray-600 text-sm">Fundamentos de gestión contable y administrativa.</p>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8">
                <h3 class="text-xl font-bold brand-text-red mb-2">FP en Auxiliar Administrativo</h3>
                <p class="text-gray-700 mb-1">IES Ciudad de Jaén</p>
                <p class="text-gray-600 text-sm">Formación técnica en gestión documental, atención al cliente y tareas administrativas.</p>
            </div>
        </section>

        <section id="sobre-mi" class="my-16">
            <h2 class="text-3xl font-bold text-center mb-4">Sobre Mí</h2>
            <p class="text-center text-gray-600 max-w-3xl mx-auto">
                Soy Kenjy Alcas, un profesional apasionado por el marketing digital, la automatización y la inteligencia artificial. Combino mi formación en administración con conocimientos en comunicación digital, diseño gráfico y herramientas tecnológicas para crear soluciones que mejoran la eficiencia y el impacto de los proyectos. Me especializo en desarrollar agentes inteligentes, automatizar procesos con plataformas como Make.com y diseñar estrategias que conecten con las personas. Creativo, organizado y en constante aprendizaje, me gusta trabajar con propósito, aportando valor a cada equipo con el que colaboro.
            </p>
        </section>

        <section id="projects-realizados" class="my-16">
            <h2 class="text-3xl font-bold text-center mb-4">Proyectos Realizados</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-12">Aquí puedes ver algunos de los proyectos más destacados en los que he trabajado, demostrando mi enfoque creativo, tecnológico y orientado a objetivos.</p>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h3 class="text-2xl font-bold brand-text-red mb-4">Proyecto 1: Barbershop Fuencarral</h3>
                <p class="text-gray-600 mt-2 mb-8">Para Barbershop Fuencarral, desarrollé una estrategia de contenido visual y campañas en redes sociales para aumentar la visibilidad de la marca y atraer nuevos clientes. El enfoque se centró en la creación de publicaciones atractivas que destacaran los servicios y el ambiente único de la barbería.</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345936/White_and_Beige_Aesthetic_Modern_Hairdresser_Salon_Price_List_Instagram_Post_1_ujtr5s.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345936/Post_de_Instagram_Peluquer%C3%ADa_Moderno_Verde_2_vplkta.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345936/Post_para_Instagram_Barber%C3%ADa_o_Peluquer%C3%ADa_Vintage_Dorado_y_Negro_1_fxh1eo.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h3 class="text-2xl font-bold brand-text-red mb-4">Proyecto 2: Restaurante Sal y Azucar</h3>
                <p class="text-gray-600 mt-2 mb-8">Para el Restaurante Sal y Azucar, implementé una estrategia de marketing digital centrada en la promoción de su oferta gastronómica y eventos especiales. Se crearon contenidos visuales atractivos para redes sociales y campañas de email marketing para fomentar la reserva de mesas y el servicio a domicilio.</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345935/publicacion_insta_23_pk2dxa.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345935/Brown_Gold_Modern_Restaurant_Gift_Voucher_zusxe0.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345935/Email_newsletter_sobre_comida_a_domicilio_estilo_org%C3%A1nico_mostaza_y_y_verde_ayll5f.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                </div>
            </div>

            <div class="bg-white rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h3 class="text-2xl font-bold brand-text-red mb-4">Proyecto 3: Diseños Diferentes</h3>
                <p class="text-gray-600 mt-2 mb-8">En este proyecto, muestro la versatilidad en el diseño gráfico y la creación de materiales visuales para diversas campañas. Desde tarjetas festivas hasta branding de productos y flyers promocionales, mi objetivo es crear piezas que comuniquen eficazmente y capturen la atención de la audiencia.</p>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753345935/Tarjeta_vertical_feliz_navidad_emotivo_navide%C3%B1o_rojo_od5un6.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753349593/2_Logos_y_Etiquetas_de_Arepas_Pinky_xacbu6.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                    <div class="rounded-lg overflow-hidden shadow-md">
                        <img src="https://res.cloudinary.com/dxotiuklm/image/upload/v1753349594/Flyer_Promoci%C3%B3n_Decoraci%C3%B3n_Del_Hogar_Elegante_Amarillo_ows3pi.png" alt="" class="w-full h-auto object-cover rounded-lg">
                    </div>
                </div>
            </div>
        </section>

        <section id="objetivo" class="my-16">
            <h2 class="text-3xl font-bold text-center mb-4">Objetivo</h2>
            <p class="text-center text-gray-600 max-w-3xl mx-auto">
                Ayudo a empresas y profesionales a mejorar su presencia digital y optimizar sus procesos mediante estrategias de marketing, automatización e inteligencia artificial. Si necesitas mejorar la gestión de tus redes sociales, crear contenido de valor, automatizar tareas repetitivas o implementar soluciones con herramientas como Make.com, ChatGPT o ElevenLabs, puedo ayudarte a hacerlo de forma eficiente, creativa y profesional.
            </p>
        </section>

        <section id="contact-quick" class="my-16 text-center">
            <h2 class="text-3xl font-bold text-center mb-4">Contacto Rápido</h2>
            <p class="text-center text-gray-600 max-w-2xl mx-auto mb-8">¿Listo para empezar un proyecto o tienes alguna pregunta? Contáctame directamente.</p>

            <div class="flex flex-col md:flex-row items-center justify-center space-y-4 md:space-y-0 md:space-x-8">
                <a href="https://wa.me/34658229859" target="_blank" class="flex items-center space-x-2 text-gray-800 hover:text-green-600 transition-colors">
                    <span style="font-size: 2.5rem;">&#x260E;</span>
                    <span class="text-xl font-semibold">658 229 859</span>
                </a>
                <a href="https://www.instagram.com/kenjy.sinlimites/?hl=es" target="_blank" class="inline-block brand-bg-orange text-white font-bold py-3 px-6 rounded-lg hover:brand-bg-red transition-colors">
                    Visita mi Instagram
                </a>
            </div>
        </section>

    </main>

    <script>
        const tooltipTitleCallback = (tooltipItems) => {
            const item = tooltipItems[0];
            let label = item.chart.data.labels[item.dataIndex];
            if (Array.isArray(label)) {
                return label.join(' ');
            }
            return label;
        };

        const defaultChartOptions = {
            responsive: true,
            maintainAspectRatio: false,
            plugins: {
                legend: {
                    position: 'bottom',
                },
                tooltip: {
                    callbacks: {
                        title: tooltipTitleCallback
                    }
                }
            },
            scales: {
                y: {
                    beginAtZero: true,
                    ticks: { color: '#4B5563' },
                    grid: { color: '#E5E7EB' }
                },
                x: {
                    ticks: { color: '#4B5563' },
                    grid: { display: false }
                }
            }
        };
        
        const wrapLabel = (label, maxWidth = 16) => {
            if (label.length <= maxWidth) return label;
            const words = label.split(' ');
            const lines = [];
            let currentLine = '';
            for (const word of words) {
                if ((currentLine + ' ' + word).trim().length > maxWidth) {
                    lines.push(currentLine.trim());
                    currentLine = word;
                } else {
                    currentLine = (currentLine + ' ' + word).trim();
                }
            }
            if (currentLine) lines.push(currentLine.trim());
            return lines;
        };

        // Charts data and options (these remain as they were, no longer used in the main content but kept in JS for completeness if needed elsewhere)
        // These charts are no longer displayed in the main content after removing sections below 'Contacto'
        /*
        new Chart(document.getElementById('salesGrowthChart'), {
            type: 'line',
            data: {
                labels: ['Enero', 'Febrero', 'Marzo'],
                datasets: [{
                    label: 'Ventas (en miles de €)',
                    data: [12, 19, 25],
                    fill: true,
                    borderColor: '#FF4E50',
                    backgroundColor: 'rgba(255, 78, 80, 0.2)',
                    tension: 0.4
                }]
            },
            options: defaultChartOptions
        });

        new Chart(document.getElementById('roasChart'), {
            type: 'doughnut',
            data: {
                labels: ['Inversión (€1)', 'Retorno (€4)'],
                datasets: [{
                    label: 'ROAS',
                    data: [1, 4],
                    backgroundColor: ['#FF4E50', '#E1F5C4'],
                    hoverOffset: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: { position: 'bottom' },
                    tooltip: { callbacks: { title: tooltipTitleCallback } }
                }
            }
        });

        new Chart(document.getElementById('leadGenChart'), {
            type: 'pie',
            data: {
                labels: ['LinkedIn Ads', 'Contenido Orgánico', 'Referidos'],
                datasets: [{
                    label: 'Fuente de Leads',
                    data: [110, 65, 25],
                    backgroundColor: ['#FF4E50', '#FC913A', '#F9D423'],
                    hoverOffset: 4
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: { position: 'bottom' },
                    tooltip: { callbacks: { title: tooltipTitleCallback } }
                }
            }
        });

        new Chart(document.getElementById('audienceGrowthChart'), {
            type: 'bar',
            data: {
                labels: ['Q1', 'Q2'],
                datasets: [{
                    label: 'Nuevos Seguidores',
                    data: [1200, 2800],
                    backgroundColor: ['#FC913A', '#FF4E50'],
                }]
            },
            options: defaultChartOptions
        });
        
        new Chart(document.getElementById('skillsRadarChart'), {
            type: 'radar',
            data: {
                labels: ['Análisis de Datos', 'Copywriting', 'SEO Social', wrapLabel('Estrategia de Contenido'), 'Publicidad de Pago', wrapLabel('Automatización con IA'), wrapLabel('Generación de Contenido con IA')],
                datasets: [{
                    label: 'Nivel de Competencia',
                    data: [90, 85, 80, 95, 88, 92, 90],
                    fill: true,
                    backgroundColor: 'rgba(255, 78, 80, 0.2)',
                    borderColor: '#FF4E50',
                    pointBackgroundColor: '#FF4E50',
                    pointBorderColor: '#fff',
                    pointHoverBackgroundColor: '#fff',
                    pointHoverBorderColor: '#FF4E50'
                }]
            },
            options: {
                responsive: true,
                maintainAspectRatio: false,
                plugins: {
                    legend: { display: false },
                    tooltip: { callbacks: { title: tooltipTitleCallback } }
                },
                scales: {
                    r: {
                        angleLines: { color: '#E5E7EB' },
                        grid: { color: '#E5E7EB' },
                        pointLabels: {
                            font: { size: 12 },
                            color: '#4B5563'
                        },
                        ticks: {
                            backdropColor: 'transparent',
                            color: '#4B5563'
                        }
                    }
                }
            }
        });

        new Chart(document.getElementById('platformExpertiseChart'), {
            type: 'bar',
            data: {
                labels: ['Instagram', 'LinkedIn', 'Facebook', 'TikTok', 'X (Twitter)'],
                datasets: [{
                    label: 'Nivel de Experiencia (%)',
                    data: [95, 90, 80, 75, 70],
                    backgroundColor: ['#FF4E50', '#FC913A', '#F9D423', '#EDE574', '#E1F5C4'],
                    borderColor: '#ffffff',
                    borderWidth: 2
                }]
            },
            options: { ...defaultChartOptions, indexAxis: 'y', plugins: { legend: { display: false }, tooltip: { callbacks: { title: tooltipTitleCallback } } } }
        });
        */
    </script>
</body>
</html>
