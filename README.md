[index.html](https://github.com/user-attachments/files/35310515/index.html)
<!doctype html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#121b25">
<meta name="description" content="Motosierra MS381 a $450.000. Pide contra entrega con envío gratis en Colombia.">
<title>Motosierra MS381 | Pedido contra entrega</title>
<style>
:root{
  --ink:#192330; --muted:#566273; --bg:#f6f7f9; --card:#fff; --line:#e5e9ef;
  --navy:#121b25; --orange:#f26722; --orange-dark:#ee631e; --green:#14753c;
  font-family:Inter,system-ui,-apple-system,"Segoe UI",sans-serif;
  color:var(--ink); background:var(--bg);
}
*{box-sizing:border-box}
body{margin:0}
p{line-height:1.6;color:var(--muted)}
[hidden]{display:none!important}

/* Cabecera */
.site-header{background:var(--navy);color:#fff;padding:15px 5%;display:flex;justify-content:space-between;align-items:center;gap:12px}
.logo{font-size:20px;letter-spacing:.3px}
.logo em{font-style:normal;color:var(--orange)}
.site-header span{font-size:12px;color:#cbd5e1}
.banner{background:var(--orange);color:#fff;text-align:center;font-weight:800;padding:10px 14px;font-size:13px}

/* Estructura */
main{max-width:1160px;margin:auto;padding:30px 20px 70px}
.layout{display:grid;grid-template-columns:1.12fr .88fr;gap:36px;align-items:start}

/* Galería */
.gallery{background:var(--card);border:1px solid var(--line);border-radius:18px;overflow:hidden}
.gallery>img{width:100%;aspect-ratio:1.3;max-height:520px;object-fit:contain;display:block}
.thumbs{display:grid;grid-template-columns:repeat(4,1fr);gap:9px;padding:12px}
.thumb{border:2px solid transparent;border-radius:10px;overflow:hidden;background:#f5f5f5;padding:0;cursor:pointer}
.thumb.active{border-color:var(--orange)}
.thumb img{width:100%;height:78px;object-fit:cover;display:block}
.thumb:focus-visible,.submit:focus-visible{outline:3px solid #b94e0f;outline-offset:3px}

/* Información del producto */
.eyebrow{color:#dc5715;font-weight:800;font-size:12px;letter-spacing:1.3px;text-transform:uppercase}
h1{font-size:clamp(29px,4vw,43px);line-height:1.12;margin:12px 0}
.price{font-size:42px;font-weight:900;letter-spacing:-1px;margin:14px 0 5px}
.price small{font-size:16px;font-weight:600;color:#718096}
.chips{display:flex;gap:8px;flex-wrap:wrap;margin:16px 0 20px}
.chip{background:#e9f6ee;color:var(--green);border-radius:40px;font-size:12px;font-weight:800;padding:8px 12px}
.chip.alt{background:#fff0e6;color:#b94e0f}
.features{display:grid;gap:12px;margin:24px 0;padding:0;list-style:none}
.features li{display:flex;gap:11px;align-items:flex-start;color:#435063;font-size:14px}
.features li::before{content:"✓";color:var(--orange);font-weight:700}

/* Formulario */
.order{background:var(--card);border:1px solid var(--line);border-radius:18px;padding:23px;box-shadow:0 12px 30px #1c29350a;position:sticky;top:20px}
.order h2{margin:0 0 8px;font-size:23px}
.order>p{font-size:13px;margin:0 0 18px}
.field{margin-bottom:14px}
label{font-size:13px;font-weight:700;display:block;margin-bottom:6px}
input,select{font:inherit;width:100%;border:1px solid #ccd3dd;border-radius:10px;padding:13px 12px;background:#fff;color:#1a2736;outline:none}
input:focus,select:focus{border-color:var(--orange);box-shadow:0 0 0 3px #f2672222}
.choice{display:grid;grid-template-columns:1fr 1fr;gap:9px}
.choice label{border:1px solid #d9dfe7;padding:12px;border-radius:10px;cursor:pointer;display:flex;align-items:flex-start;gap:8px;font-size:12px;margin:0}
.choice input{width:auto;margin:1px 0}
.summary{background:#f5f7fa;padding:14px;border-radius:10px;margin:18px 0;font-size:14px}
.summary div{display:flex;justify-content:space-between;margin:6px 0}
.summary strong{font-size:18px}
.summary hr{border:0;border-top:1px solid #e2e6eb}
.free{color:var(--green)}
.submit{background:var(--orange-dark);border:0;border-radius:11px;padding:16px 12px;color:#fff;font-size:16px;font-weight:800;width:100%;cursor:pointer}
.submit:disabled{opacity:.6;cursor:wait}
.status{font-size:13px;border-radius:10px;padding:12px;margin-top:12px;display:none}
.status.error{display:block;background:#fff1f1;color:#a31b1b}
.status.success{display:block;background:#e7f8ed;color:#176c36}
.note{text-align:center;font-size:11px!important;margin:12px 0 0!important}
.privacy{font-size:11px;color:#64748b;margin-top:12px}
.privacy a{color:#a84714}
.trap{display:none}

/* Bloques de detalle */
.details{background:var(--card);border-radius:18px;margin-top:30px;padding:25px;border:1px solid var(--line)}
.details h2{margin-top:0}
.details h3{font-size:18px;margin:24px 0 8px;color:#1a2736}
.details ul{padding-left:21px}
.details li{padding:5px 0;color:#4d5b6b}
.usegrid{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin:14px 0}
.usegrid>div{background:var(--bg);border-radius:12px;padding:14px}
.usegrid p{font-size:13px;margin:7px 0 0}
.steps{display:grid;gap:16px}
.steps>div{display:flex;gap:13px;align-items:flex-start;color:#536171;font-size:14px;line-height:1.5}
.steps b{background:var(--orange);color:#fff;border-radius:50%;width:28px;height:28px;flex-shrink:0;display:grid;place-items:center}
.steps strong{color:var(--ink)}

.footer{text-align:center;color:#64748b;font-size:12px;margin-top:30px}

@media(max-width:800px){
  main{padding:16px 12px 45px}
  .layout{grid-template-columns:1fr;gap:22px}
  .gallery>img{aspect-ratio:1.22;max-height:440px}
  .thumb img{height:62px}
  .order{padding:18px;position:static}
  .price{font-size:38px}
  .usegrid{grid-template-columns:1fr}
  .details{padding:19px}
}
@media(max-width:370px){.choice{grid-template-columns:1fr}}
</style>

<!-- PÍXEL DE META: reemplaza 28245206778490984 por tu ID numérico real para activarlo. -->
<script>
var META_PIXEL_ID = '28245206778490984';
if (/^\d{8,20}$/.test(META_PIXEL_ID)) {
  !function(f,b,e,v,n,t,s){if(f.fbq)return;n=f.fbq=function(){n.callMethod?n.callMethod.apply(n,arguments):n.queue.push(arguments)};if(!f._fbq)f._fbq=n;n.push=n;n.loaded=!0;n.version='2.0';n.queue=[];t=b.createElement(e);t.async=!0;t.src=v;s=b.getElementsByTagName(e)[0];s.parentNode.insertBefore(t,s)}(window,document,'script','https://connect.facebook.net/en_US/fbevents.js');
  fbq('init', META_PIXEL_ID);
  fbq('track', 'PageView');
}
</script>
</head>

<body>
<header class="site-header">
  <strong class="logo">CAMPO<em>PRO</em></strong>
  <span>Herramientas para trabajo de campo</span>
</header>
<div class="banner">🚚 ENVÍO GRATIS · 💵 PAGAS CUANDO RECIBES</div>

<main>
<div class="layout">

  <!-- Columna izquierda -->
  <section>
    <div class="gallery">
      <img id="mainPhoto" src="assets/foto1.jpg" alt="Motosierra MS381, fotografía principal" width="1200" height="657">
      <div class="thumbs">
        <button class="thumb active" type="button" aria-label="Ver foto 1" data-photo="1"><img src="assets/foto1.jpg" alt="Vista lateral" loading="lazy"></button>
        <button class="thumb" type="button" aria-label="Ver foto 2" data-photo="2"><img src="assets/foto2.jpg" alt="Vista en césped" loading="lazy"></button>
        <button class="thumb" type="button" aria-label="Ver foto 3" data-photo="3"><img src="assets/foto3.jpg" alt="Vista superior" loading="lazy"></button>
        <button class="thumb" type="button" aria-label="Ver foto 4" data-photo="4"><img src="assets/foto4.jpg" alt="Vista sobre cajas" loading="lazy"></button>
      </div>
    </div>

    <div class="details">
      <h2>Conoce la motosierra MS381</h2>
      <p>Una opción para quienes necesitan una motosierra de gasolina para labores de corte de madera en fincas, parcelas y trabajos rurales. Consulta las fotografías de la unidad ofrecida antes de hacer tu pedido.</p>

      <h3>Características de la unidad anunciada</h3>
      <ul>
        <li><strong>Modelo:</strong> MS381, según la identificación del producto en las fotos.</li>
        <li><strong>Tipo de equipo:</strong> motosierra a gasolina, de manejo manual.</li>
        <li><strong>Espada ofrecida:</strong> 70 cm, sujeta a confirmación de la unidad despachada.</li>
        <li><strong>Uso previsto:</strong> corte de troncos y madera, de acuerdo con la capacidad del equipo y la técnica de operación.</li>
        <li><strong>Precio anunciado:</strong> $450.000 COP.</li>
        <li><strong>Modalidad de pago:</strong> contra entrega, según cobertura del transportador.</li>
      </ul>

      <h3>¿Para qué trabajos puede servir?</h3>
      <div class="usegrid">
        <div><strong>🌳 Trabajos de finca</strong><p>Corte de madera y mantenimiento de áreas rurales, con las precauciones correspondientes.</p></div>
        <div><strong>🪵 Preparación de leña</strong><p>Troceado de madera dentro de las capacidades y recomendaciones de operación.</p></div>
        <div><strong>🔧 Labores de campo</strong><p>Una herramienta para tareas donde se necesita un equipo de corte portátil.</p></div>
      </div>

      <h3>Antes de comprar</h3>
      <p>Confirma con el vendedor la cilindrada, potencia, accesorios incluidos, garantía, estado del producto y longitud real de la espada. Las fotografías muestran unidades con etiquetas MS381 y MS382; el modelo exacto que recibirás debe verificarse antes del despacho.</p>

      <h3>Consejos de uso seguro</h3>
      <p>Utiliza casco, protección ocular y auditiva, guantes, pantalón anticorte y botas apropiadas. Revisa la tensión de la cadena y el freno antes de operar. No uses la motosierra sin capacitación.</p>
    </div>

    <div class="details">
      <h2>¿Cómo recibes tu pedido?</h2>
      <div class="steps">
        <div><b>1</b><span><strong>Completa tus datos</strong><br>Nombre, teléfono, departamento y municipio.</span></div>
        <div><b>2</b><span><strong>Escoge la entrega</strong><br>A domicilio o retiro en oficina de Inter Rapidísimo, sujeto a cobertura.</span></div>
        <div><b>3</b><span><strong>Confirma por teléfono</strong><br>Te contactamos para validar el pedido y la disponibilidad.</span></div>
        <div><b>4</b><span><strong>Paga al recibir</strong><br>El cobro contra entrega depende de la disponibilidad del servicio en tu destino.</span></div>
      </div>
    </div>
  </section>

  <!-- Columna derecha -->
  <section>
    <div class="eyebrow">Motosierra para trabajo de campo</div>
    <h1>Motosierra STIHL MS381</h1>
    <p>Motosierra de gasolina para labores de corte de madera y trabajo rural. Mira las fotos, conoce las características anunciadas y solicita tu pedido sin pagar por adelantado.</p>

    <div class="price">$450.000 <small>COP</small></div>

    <div class="chips">
      <span class="chip">✓ Pago contra entrega</span>
      <span class="chip">✓ Envío gratis</span>
      <span class="chip alt">✓ Pedido fácil</span>
    </div>

    <ul class="features">
      <li>Espada anunciada de 70 cm; verifica la medida y el modelo antes del despacho.</li>
      <li>Ideal para consultar si necesitas un equipo para corte de madera y labores de finca.</li>
      <li>Llena tus datos en menos de un minuto.</li>
      <li>Elige domicilio o recogida en oficina de Inter Rapidísimo.</li>
      <li>Te contactaremos para confirmar disponibilidad y cobertura.</li>
    </ul>

    <div class="order" id="pedido">
      <h2>Haz tu pedido ahora</h2>
      <p>Completa tus datos para solicitar tu motosierra contra entrega.</p>

      <form name="pedido-motosierra" id="orderForm" method="POST" data-netlify="true" netlify-honeypot="bot-field">
        <input type="hidden" name="form-name" value="pedido-motosierra">
        <p class="trap"><label>No llenar <input name="bot-field"></label></p>
        <input type="hidden" name="producto" value="Motosierra MS381">
        <input type="hidden" name="precio" value="450000">

        <div class="field">
          <label for="nombre">Nombre completo *</label>
          <input id="nombre" name="nombre" autocomplete="name" required maxlength="100" placeholder="Escribe tu nombre completo">
        </div>

        <div class="field">
          <label for="telefono">Número de teléfono *</label>
          <input id="telefono" name="telefono" type="tel" autocomplete="tel" required minlength="10" maxlength="15" pattern="[0-9+() \-]{10,15}" placeholder="Ej. 3001234567">
        </div>

        <div class="field">
          <label for="departamento">Departamento *</label>
          <select id="departamento" name="departamento" required>
            <option value="">Selecciona tu departamento</option>
          </select>
        </div>

        <div class="field">
          <label for="municipio">Municipio *</label>
          <input id="municipio" name="municipio" required maxlength="80" placeholder="Escribe tu municipio">
        </div>

        <div class="field">
          <label>¿Cómo deseas recibir tu pedido? *</label>
          <div class="choice">
            <label><input type="radio" name="entrega" value="Domicilio" required checked> A domicilio</label>
            <label><input type="radio" name="entrega" value="Oficina Inter Rapidísimo" required> Oficina Inter Rapidísimo</label>
          </div>
        </div>

        <div class="field" id="direccionField">
          <label for="direccion">Dirección de entrega *</label>
          <input id="direccion" name="direccion" maxlength="180" required placeholder="Barrio, calle, carrera, número o indicaciones">
        </div>

        <div class="summary">
          <div><span>Motosierra MS381</span><span>$450.000</span></div>
          <div><span>Envío</span><span class="free">GRATIS</span></div>
          <hr>
          <div><b>Total contra entrega</b><strong>$450.000</strong></div>
        </div>

        <button class="submit" id="send" type="submit">CONFIRMAR MI PEDIDO →</button>
        <div class="status" id="status" role="status" aria-live="polite"></div>
        <p class="note">🔒 No pagas en esta página. El pedido queda sujeto a confirmación.</p>
        <div class="privacy">Al enviar tus datos aceptas que se utilicen para contactarte y gestionar tu pedido. Consulta la <a href="privacidad.html" target="_blank" rel="noopener">política de privacidad</a>.</div>
      </form>
    </div>
  </section>

</div>
<div class="footer">CAMPOPRO · Pedidos sujetos a confirmación · Colombia</div>
</main>

<script>
(function () {
  var PRICE = 450000;
  var track = function (name, data) { if (typeof fbq === 'function') fbq('track', name, data); };

  // Galería
  var mainPhoto = document.getElementById('mainPhoto');
  var thumbs = document.querySelectorAll('.thumb');
  thumbs.forEach(function (t) {
    t.addEventListener('click', function () {
      mainPhoto.src = 'assets/foto' + t.dataset.photo + '.jpg';
      thumbs.forEach(function (x) { x.classList.remove('active'); });
      t.classList.add('active');
    });
  });

  // Evento de vista de producto
  track('ViewContent', { content_name: 'Motosierra MS381', content_type: 'product', content_ids: ['MS381'], value: PRICE, currency: 'COP' });

  // Departamentos
  var departments = ['Amazonas','Antioquia','Arauca','Atlántico','Bogotá D.C.','Bolívar','Boyacá','Caldas','Caquetá','Casanare','Cauca','Cesar','Chocó','Córdoba','Cundinamarca','Guainía','Guaviare','Huila','La Guajira','Magdalena','Meta','Nariño','Norte de Santander','Putumayo','Quindío','Risaralda','San Andrés y Providencia','Santander','Sucre','Tolima','Valle del Cauca','Vaupés','Vichada'];
  var depSelect = document.getElementById('departamento');
  departments.forEach(function (d) {
    var o = document.createElement('option');
    o.value = d; o.textContent = d;
    depSelect.appendChild(o);
  });

  // Dirección solo si es a domicilio
  var address = document.getElementById('direccion');
  var addressField = document.getElementById('direccionField');
  function updateDelivery() {
    var office = document.querySelector('input[name="entrega"]:checked').value === 'Oficina Inter Rapidísimo';
    addressField.hidden = office;
    address.required = !office;
    if (office) address.value = '';
  }
  document.querySelectorAll('input[name="entrega"]').forEach(function (r) { r.addEventListener('change', updateDelivery); });
  updateDelivery();

  // Inicio de checkout (una sola vez)
  var form = document.getElementById('orderForm');
  var started = false;
  form.addEventListener('focusin', function () {
    if (started) return;
    started = true;
    track('InitiateCheckout', { value: PRICE, currency: 'COP', content_ids: ['MS381'], content_type: 'product' });
  });

  // Envío del pedido
  form.addEventListener('submit', async function (e) {
    e.preventDefault();
    if (!form.reportValidity()) return;

    var btn = document.getElementById('send');
    var status = document.getElementById('status');
    btn.disabled = true;
    btn.textContent = 'ENVIANDO PEDIDO...';
    status.className = 'status';
    status.textContent = '';

    try {
      var body = new URLSearchParams(new FormData(form)).toString();
      var res = await fetch('/', {
        method: 'POST',
        headers: { 'Content-Type': 'application/x-www-form-urlencoded' },
        body: body
      });
      if (!res.ok) throw new Error('No se pudo guardar el pedido');

      // Ojo: esto marca el pedido registrado, no un cobro ni una entrega.
      track('Purchase', { value: PRICE, currency: 'COP', content_ids: ['MS381'], content_type: 'product', num_items: 1 });

      form.reset();
      updateDelivery();
      status.className = 'status success';
      status.textContent = '¡Solicitud recibida! Te contactaremos para confirmar el pedido y la cobertura del envío.';
      btn.textContent = 'PEDIDO REGISTRADO';
    } catch (err) {
      status.className = 'status error';
      status.textContent = 'No se pudo registrar tu pedido. Inténtalo de nuevo. Asegúrate de que la página esté publicada en Netlify y el formulario esté habilitado.';
      btn.disabled = false;
      btn.textContent = 'VOLVER A INTENTAR';
    }
  });
})();
</script>
</body>
</html>
