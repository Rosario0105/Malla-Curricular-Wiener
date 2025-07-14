
    }

    .curso {
      margin: 8px 0;
      padding: 10px 14px;
      border-radius: 8px;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
      font-size: 1.1rem;
    }

    .humanidades { background-color: #4e91d9; }
    .finanzas { background-color: #57c785; }
    .gestion { background-color: #f4b942; color: #000; }
    .tecnologia { background-color: #9b59b6; }

    .creditos {
      background: rgba(255,255,255,0.3);
      padding: 4px 8px;
      border-radius: 5px;
      font-size: 0.85rem;
    }
  </style>
</head>
<body>

  <h1>Malla Curricular Interactiva</h1>

  <div class="filtro">
    <label for="selector-ciclo"><strong>Filtrar por ciclo:</strong></label>
    <select id="selector-ciclo" onchange="filtrarCiclo()">
      <option value="todos">Todos</option>
      <option value="ciclo1">1.º Ciclo</option>
      <option value="ciclo2">2.º Ciclo</option>
      <option value="ciclo3">3.º Ciclo</option>
      <option value="ciclo4">4.º Ciclo</option>
      <option value="ciclo5">5.º Ciclo</option>
      <option value="ciclo6">6.º Ciclo</option>
      <option value="ciclo7">7.º Ciclo</option>
      <option value="ciclo8">8.º Ciclo</option>
      <option value="ciclo9">9.º Ciclo</option>
      <option value="ciclo10">10.º Ciclo</option>
    </select>
  </div>
<!-- CICLO 1 -->
<div class="ciclo ciclo1 active">
  <div class="titulo-ciclo">1.º Ciclo</div>
  <div class="curso humanidades">Desarrollo Humano y Social <span class="creditos">3 créditos</span></div>
  <div class="curso humanidades">Inglés I <span class="creditos">2 créditos</span></div>
  <div class="curso humanidades">Introducción a la Ética <span class="creditos">2 créditos</span></div>
  <div class="curso finanzas">Matemática <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Introducción a la Administración <span class="creditos">4 créditos</span></div>
</div>

  <div class="curso finanzas">Estadística <span class="creditos">3 créditos</span></div>
  <div class="curso tecnologia">Informática para los Negocios <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Diseño Organizacional <span class="creditos">3 créditos</span></div>
</div>

<!-- CICLO 3 -->
<div class="ciclo ciclo3 active">
  <div class="titulo-ciclo">3.º Ciclo</div>
  <div class="curso gestion">Comportamiento Organizacional <span class="creditos">3 créditos</span></div>
  <div class="curso humanidades">Inglés III <span class="creditos">2 créditos</span></div>
  <div class="curso finanzas">Contabilidad General <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Gestión de Stakeholders <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Creatividad e Innovación Empresarial <span class="creditos">2 créditos</span></div>
</div>

<!-- CICLO 4 -->
<div class="ciclo ciclo4 active">
  <div class="titulo-ciclo">4.º Ciclo</div>
  <div class="curso gestion">Comunicación de Alto Impacto <span class="creditos">2 créditos</span></div>
  <div class="curso humanidades">Inglés IV <span class="creditos">2 créditos</span></div>
  <div class="curso finanzas">Contabilidad Avanzada <span class="creditos">3 créditos</span></div>
  <div class="curso finanzas">Matemática Financiera <span class="creditos">3 créditos</span></div>
  <div class="curso finanzas">Microeconomía <span class="creditos">3 créditos</span></div>
</div>

<!-- CICLO 5 -->
<div class="ciclo ciclo5 active">
  <div class="titulo-ciclo">5.º Ciclo</div>
  <div class="curso gestion">Liderazgo <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Innovación en la Sociedad <span class="creditos">2 créditos</span></div>
  <div class="curso finanzas">Macroeconomía <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Fundamentos del Marketing <span class="creditos">3 créditos</span></div>
  <div class="curso finanzas">Finanzas <span class="creditos">3 créditos</span></div>
</div>

<!-- CICLO 6 -->
<div class="ciclo ciclo6 active">
  <div class="titulo-ciclo">6.º Ciclo</div>
  <div class="curso gestion">Investigación e Innovación <span class="creditos">2 créditos</span></div>
  <div class="curso gestion">Derecho Empresarial <span class="creditos">2 créditos</span></div>
  <div class="curso finanzas">Costos y Presupuestos <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Innovación y Liderazgo Organizacional <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Investigación de Mercados <span class="creditos">3 créditos</span></div>
</div>

<!-- CICLO 7 -->
<div class="ciclo ciclo7 active">
  <div class="titulo-ciclo">7.º Ciclo</div>
  <div class="curso gestion">Prácticas Preprofesionales <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Gestión del Talento <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Gestión de la Cadena de Suministros <span class="creditos">3 créditos</span></div>
  <div class="curso finanzas">Análisis Contable y Financieros <span class="creditos">3 créditos</span></div>
  <div class="curso humanidades">Ética Empresarial <span class="creditos">2 créditos</span></div>
</div>

<!-- CICLO 8 -->
<div class="ciclo ciclo8 active">
  <div class="titulo-ciclo">8.º Ciclo</div>
  <div class="curso gestion">Gestión de Riesgos Globales <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Gestión de Procesos de Negocios <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Derecho Laboral <span class="creditos">2 créditos</span></div>
  <div class="curso gestion">Emprendimiento de Negocios Sostenibles <span class="creditos">3 créditos</span></div>
  <div class="curso tecnologia">Big Data en la Economía Global <span class="creditos">3 créditos</span></div>
</div>

<!-- CICLO 9 -->
<div class="ciclo ciclo9 active">
  <div class="titulo-ciclo">9.º Ciclo</div>
  <div class="curso gestion">Seminario de Investigación <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Comercio Internacional <span class="creditos">3 créditos</span></div>
  <div class="curso finanzas">Gestión desde la Contabilidad Global <span class="creditos">3 créditos</span></div>
  <div class="curso tecnologia">Análisis de Datos y Transformación Digital <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Negociación en Entornos Globales <span class="creditos">2 créditos</span></div>
</div>

<!-- CICLO 10 -->
<div class="ciclo ciclo10 active">
  <div class="titulo-ciclo">10.º Ciclo</div>
  <div class="curso gestion">Trabajo de Investigación <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Liderazgo y Desarrollo Personal <span class="creditos">2 créditos</span></div>
  <div class="curso gestion">Marketing Digital para Mercados Globales <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Dirección Estratégica <span class="creditos">3 créditos</span></div>
  <div class="curso gestion">Electivo <span class="creditos">2 créditos</span></div>
</div>
<script>
    function filtrarCiclo() {
      const valor = document.getElementById('selector-ciclo').value;
      const ciclos = document.querySelectorAll('.ciclo');
      ciclos.forEach(ciclo => {
        if (valor === 'todos') {
          ciclo.classList.add('active');
        } else {
          ciclo.classList.remove('active');
          if (ciclo.classList.contains(valor)) {
            ciclo.classList.add('active');
          }
        }
      });
    }
  </script>
  </body>
</html>
