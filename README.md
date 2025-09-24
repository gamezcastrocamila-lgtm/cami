# cami
Rol del empleado
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>SURA - El Rol del Empleado</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://fonts.googleapis.com/css2?family=Barlow:wght@500;700&family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      background-color: #0033A0; /* Color Pantone 286C */
      font-family: 'Roboto', sans-serif;
    }
    .title-font {
      font-family: 'Barlow', sans-serif;
      font-weight: 700;
    }
    .back-button {
      background-color: #00C2D6; /* Color Pantone 3125C */
      color: white;
      font-weight: bold;
      text-align: center;
      padding: 0.75rem 1.5rem;
      border-radius: 0.5rem;
      transition: transform 0.2s, box-shadow 0.2s;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      text-decoration: none;
      display: inline-block;
    }
    .back-button:hover {
      transform: translateY(-2px);
      box-shadow: 0 6px 8px rgba(0, 0, 0, 0.2);
    }
    .content-card h2 {
      color: #0033A0;
      font-family: 'Barlow', sans-serif;
      font-weight: 700;
      font-size: 1.75rem;
      margin-bottom: 1rem;
      text-align: center;
    }
    .content-card p, .content-card li {
      color: #333;
      line-height: 1.7;
    }
    .expandable-header {
      cursor: pointer;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 1rem;
      background-color: #e6f7ff;
      border-radius: 0.5rem;
      transition: background-color 0.2s;
    }
    .expandable-header:hover {
      background-color: #cceeff;
    }
    .expandable-content {
      display: none;
      padding: 1rem;
      border-left: 3px solid #00C2D6;
      background-color: #f7faff;
      margin-top: 0.5rem;
    }
    .expandable-content.active {
      display: block;
    }
    .arrow {
      transition: transform 0.3s;
    }
    .arrow.rotate {
      transform: rotate(180deg);
    }
  </style>
</head>
<body class="text-gray-800">

  <!-- Main container -->
  <div class="container mx-auto px-4 py-8 max-w-5xl">
    
    <!-- Header -->
    <header class="text-center mb-12">
      <h1 class="text-white text-4xl md:text-5xl font-extrabold tracking-tight title-font">El Rol del Empleado</h1>
    </header>

    <!-- Main Content Section -->
    <main class="bg-white p-8 md:p-12 rounded-lg shadow-xl content-card">
      
      <!-- Logo SURA -->
      <div class="flex justify-center mb-8">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/58/Grupo_Sura_logo.svg/2560px-Grupo_Sura_logo.svg.png" alt="Logo de SURA" class="w-64 h-auto rounded-lg" />
      </div>
      
      <h2>Nuestros Empleados: El Corazón de SURA</h2>
      
      <p class="mb-6 text-justify">
        En SURA, entendemos que nuestro equipo humano es el pilar fundamental para inspirar confianza y construir un futuro sostenible. Cada empleado es un embajador de nuestra marca y un agente de cambio que, con su talento y compromiso, materializa nuestro propósito de acompañar a las personas y empresas en cada etapa de sus vidas. El rol del empleado en SURA trasciende las responsabilidades diarias; se trata de vivir nuestra cultura, valores y principios en cada interacción.
      </p>

      <!-- Image 1 -->
      <div class="flex justify-center my-10">
        <img src="https://images.unsplash.com/photo-1556761175-5973dc0f32e7?q=80&w=1932&auto=format&fit=crop" alt="Equipo de profesionales colaborando en una oficina moderna" class="w-full h-auto rounded-lg shadow-md max-w-2xl">
      </div>

      <h2 class="mt-8">Pilares del Empleado SURA</h2>

      <div class="grid md:grid-cols-2 gap-8 text-left mt-6">
        <div>
          <h3 class="font-bold text-lg mb-2 text-[#0033A0]">1. Foco en el Cliente</h3>
          <p>Nuestra prioridad es entender y atender las necesidades de nuestros clientes. Un empleado SURA es empático, proactivo y busca constantemente ofrecer soluciones que agreguen valor real, generando relaciones de confianza a largo plazo.</p>
        </div>
        <div>
          <h3 class="font-bold text-lg mb-2 text-[#0033A0]">2. Integridad y Transparencia</h3>
          <p>Actuamos con ética y coherencia. La honestidad y la transparencia son la base de todas nuestras acciones, garantizando que tanto clientes como compañeros puedan confiar plenamente en nosotros y en la compañía.</p>
        </div>
        <div>
          <h3 class="font-bold text-lg mb-2 text-[#0033A0]">3. Innovación y Adaptabilidad</h3>
          <p>Vivimos en un mundo en constante cambio. Fomentamos la curiosidad, el aprendizaje continuo y la capacidad de adaptarnos para innovar en nuestros procesos y servicios, anticipándonos a las necesidades del futuro.</p>
        </div>
        <div>
          <h3 class="font-bold text-lg mb-2 text-[#0033A0]">4. Colaboración y Respeto</h3>
          <p>Creemos en el poder del trabajo en equipo. Valoramos la diversidad de opiniones y promovemos un ambiente de respeto y colaboración donde todos podemos crecer juntos y alcanzar metas extraordinarias.</p>
        </div>
      </div>

      <!-- New Content Section -->
      <div class="mt-12 border-t pt-10">
        <h2 class="mt-8">Nuestro Compromiso con el Talento</h2>

        <!-- Formación y Desarrollo -->
        <div class="mt-10 md:flex items-center gap-8">
          <div class="md:w-1/2">
            <img src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?q=80&w=2070&auto=format&fit=crop" alt="Empleados en una sesión de formación" class="w-full h-auto rounded-lg shadow-md">
          </div>
          <div class="md:w-1/2 mt-6 md:mt-0">
            <h3 class="font-bold text-xl mb-3 text-[#0033A0]">Formación y Desarrollo</h3>
            <p class="text-justify">Las personas, con sus talentos, ideas y comportamientos, son las que hacen que las empresas puedan sostenerse en el tiempo, cumplan sus propósitos y aporten al desarrollo de la sociedad. El 100% de los empleados de Grupo SURA y sus compañías tienen acceso a programas de formación técnica y de desarrollo de competencias, lo cual garantiza igualdad de oportunidades y promueve una cultura de aprendizaje continuo para todos.</p>
          </div>
        </div>

        <!-- Liderazgo Inspirador -->
        <div class="mt-12 md:flex items-center gap-8 flex-row-reverse">
          <div class="md:w-1/2">
            <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?q=80&w=2070&auto=format&fit=crop" alt="Líder inspirando a su equipo" class="w-full h-auto rounded-lg shadow-md">
          </div>
          <div class="md:w-1/2 mt-6 md:mt-0">
            <h3 class="font-bold text-xl mb-3 text-[#0033A0]">Liderazgo Inspirador</h3>
            <p class="text-justify">Creemos en el liderazgo que promueve conversaciones abiertas y escucha constante; pues sólo a través de estas se construyen relaciones de confianza.</p>
          </div>
        </div>

        <!-- Bienestar Integral -->
        <div class="mt-12 md:flex items-center gap-8">
          <div class="md:w-1/2">
            <img src="https://images.unsplash.com/photo-1543269865-cbf427effbad?q=80&w=2070&auto=format&fit=crop" alt="Equipo de trabajo colaborando en un ambiente positivo" class="w-full h-auto rounded-lg shadow-md">
          </div>
          <div class="md:w-1/2 mt-6 md:mt-0">
            <h3 class="font-bold text-xl mb-3 text-[#0033A0]">Bienestar y Calidad de Vida</h3>
            <p class="text-justify">Para cuidar la salud física, emocional, mental y financiera de nuestros empleados implementamos políticas que contribuyen con el bienestar y el desarrollo de cada uno. La encuesta de bienestar recoge la percepción de más de 17 mil empleados, y en 2023 el puntaje total fue de 92 sobre 100, reflejando el orgullo, disfrute y satisfacción en el trabajo.</p>
          </div>
        </div>

        <!-- Diversidad, Equidad e Inclusión -->
        <div class="mt-12 md:flex items-center gap-8 flex-row-reverse">
          <div class="md:w-1/2">
            <img src="https://images.unsplash.com/photo-1521791136064-7986c2920216?q=80&w=2070&auto=format&fit=crop" alt="Diversidad en el equipo de trabajo" class="w-full h-auto rounded-lg shadow-md">
          </div>
          <div class="md:w-1/2 mt-6 md:mt-0">
            <h3 class="font-bold text-xl mb-3 text-[#0033A0]">Diversidad, Equidad e Inclusión</h3>
            <p class="text-justify">En el Grupo empresarial SURA contamos con diferentes políticas, procedimientos y medios para la prevención y atención de casos de discriminación y acoso, promoviendo un ambiente seguro e incluyente para todos.</p>
          </div>
        </div>
      </div>
      
      <div class="mt-10 border-t pt-8">
        <h2>Entendemos al ser humano como centro de nuestra estrategia</h2>
        <p class="mt-4 text-justify">
          Reconocemos al ser humano como el centro de nuestra organización, desde su identidad y cultura, buscando potenciar su desarrollo y su relación con el entorno para contribuir a una sociedad armónica.
        </p>
        <!-- Image 2 -->
        <div class="flex justify-center mt-8">
            <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=2070&auto=format&fit=crop" alt="Tres empleados de SURA colaborando con sus portátiles" class="w-full h-auto rounded-lg shadow-md max-w-2xl" onerror="this.onerror=null;this.src='https://placehold.co/1200x800/e2e8f0/64748b?text=Imagen+no+disponible';">
        </div>
      </div>

      <!-- New Interactive Section -->
      <div class="mt-12 border-t pt-10">
        <h2 class="mb-6">Beneficios Adicionales para Empleados</h2>
        
        <div class="space-y-4">
          <!-- Beneficio 1 -->
          <div class="border border-gray-200 rounded-lg">
            <div class="expandable-header" data-target="content-1">
              <h3 class="font-semibold text-lg text-[#0033A0]">Seguro de Salud Premium</h3>
              <span class="arrow">&#9660;</span>
            </div>
            <div id="content-1" class="expandable-content">
              <p class="text-justify">Ofrecemos un seguro de salud completo que cubre una amplia gama de servicios médicos, hospitalarios y de especialidades, asegurando el bienestar físico de nuestros empleados y sus familias.</p>
            </div>
          </div>
          
          <!-- Beneficio 2 -->
          <div class="border border-gray-200 rounded-lg">
            <div class="expandable-header" data-target="content-2">
              <h3 class="font-semibold text-lg text-[#0033A0]">Plan de Pensiones y Ahorro</h3>
              <span class="arrow">&#9660;</span>
            </div>
            <div id="content-2" class="expandable-content">
              <p class="text-justify">Invertimos en el futuro financiero de nuestros empleados con un robusto plan de pensiones, que incluye aportes de la empresa para garantizar una jubilación segura y tranquila.</p>
            </div>
          </div>

          <!-- Beneficio 3 -->
          <div class="border border-gray-200 rounded-lg">
            <div class="expandable-header" data-target="content-3">
              <h3 class="font-semibold text-lg text-[#0033A0]">Horario Laboral Flexible</h3>
              <span class="arrow">&#9660;</span>
            </div>
            <div id="content-3" class="expandable-content">
              <p class="text-justify">Promovemos un equilibrio entre la vida laboral y personal. Nuestro esquema de horario flexible permite a los empleados gestionar su tiempo de manera eficiente, lo que se traduce en mayor productividad y bienestar general.</p>
            </div>
          </div>
        </div>
      </div>

      <!-- Back Button Section -->
      <div class="mt-12 text-center">
        <a href="#" onclick="return false;" class="back-button">Volver a la Página Principal</a>
      </div>

    </main>
    
    <!-- Footer -->
    <footer class="mt-8 text-center text-white text-sm">
      <p>&copy; 2024 SURA. Todos los derechos reservados.</p>
    </footer>
  </div>

<script>
  document.addEventListener('DOMContentLoaded', () => {
    const headers = document.querySelectorAll('.expandable-header');
    headers.forEach(header => {
      header.addEventListener('click', () => {
        const targetId = header.dataset.target;
        const content = document.getElementById(targetId);
        const arrow = header.querySelector('.arrow');

        const isExpanded = content.classList.contains('active');
        
        // Hide all other active sections
        document.querySelectorAll('.expandable-content.active').forEach(item => {
          if (item !== content) {
            item.classList.remove('active');
            item.previousElementSibling.querySelector('.arrow').classList.remove('rotate');
          }
        });

        // Toggle the clicked section
        content.classList.toggle('active');
        arrow.classList.toggle('rotate');
      });
    });
  });
</script>

</body>
</html>
