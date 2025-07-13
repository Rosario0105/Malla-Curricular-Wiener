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
