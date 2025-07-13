<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Malla Curricular Interactiva</title>
  <style>
    body{font-family:Arial,Helvetica,sans-serif;margin:0 auto;max-width:900px;padding:24px;background:#f7fbff}
    h1{color:#0b6eb6;margin-bottom:32px;text-align:center}
    .ciclo{border:1px solid #d0e3ff;border-radius:10px;margin-bottom:18px;background:#fff;box-shadow:0 2px 4px rgba(0,0,0,.06)}
    .ciclo-header{padding:14px 18px;font-size:1.1rem;font-weight:700;color:#0b6eb6;cursor:pointer;display:flex;justify-content:space-between;align-items:center}
    .cursos{display:none;padding:0 18px 14px}
    .curso{margin:6px 0;padding:6px 10px;border-radius:6px;background:#e8f3ff}
    .rotate{transform:rotate(90deg);transition:.2s}
    .rotate.open{transform:rotate(270deg)}
  </style>
</head>
<body>

<h1>Malla Curricular Interactiva</h1>

<!-- ======== Ciclos ======== -->
<div class="ciclo">
  <div class="ciclo-header" onclick="toggle(this)">
    1.er CICLO <span class="rotate">▶️</span>
  </div>
  <div class="cursos">
    <div class="curso">Desarrollo Humano y Social</div>
    <div class="curso">Inglés I</div>
    <div class="curso">Introducción a la Ética</div>
    <div class="curso">Matemática</div>
    <div class="curso">Introducción a la Administración</div>
  </div>
</div>

<div class="ciclo">
  <div class="ciclo-header" onclick="toggle(this)">
    2.º CICLO <span class="rotate">▶️</span>
  </div>
  <div class="cursos">
    <div class="curso">Estilo de Vida, Salud y Medio Ambiente</div>
    <div class="curso">Inglés II</div>
    <div class="curso">Estadística</div>
    <div class="curso">Informática para los Negocios</div>
    <div class="curso">Diseño Organizacional</div>
  </div>
</div>

<!-- …repite la misma estructura para los ciclos 3 al 10 … -->
<div class="ciclo">
  <div class="ciclo-header" onclick="toggle(this)">3.er CICLO <span class="rotate">▶️</span></div>
  <div class="cursos">
    <div class="curso">Comportamiento Organizacional</div><div class="curso">Inglés III</div>
    <div class="curso">Contabilidad General</div><div class="curso">Gestión de Stakeholders</div>
    <div class="curso">Creatividad e Innovación Empresarial</div>
  </div>
</div>

<div class="ciclo">
  <div class="ciclo-header" onclick="toggle(this)">4.º CICLO <span class="rotate">▶️</span></div>
  <div class="cursos">
    <div class="curso">Comunicación de Alto Impacto</div><div class="curso">Inglés IV</div>
    <div class="curso">Contabilidad Avanzada</div><div class="curso">Matemática Financiera</div>
    <div class="curso">Microeconomía</div>
  </div>
</div>

<!-- 5°–10° omitidos por brevedad; copia tu lista de cursos aquí siguiendo el mismo patrón -->

<script>
function toggle(header){
  const cursos=header.nextElementSibling;
  const icon=header.querySelector('.rotate');
  const abierto=cursos.style.display==='block';
  cursos.style.display=abierto?'none':'block';
  icon.classList.toggle('open',!abierto);
}
</script>

</body>
</html>
