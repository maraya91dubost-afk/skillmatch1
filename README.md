# skillmatch1<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>SkillMatch Escuela de Conductores de Maquinaria Pesada</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #e6ecf5;
            color: #1a1a1a;
        }
        header {
            background: #1f3b73;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background: #162b52;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .section {
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.2);
        }
        h2 {
            color: #1f3b73;
        }
        .image-placeholder {
            width: 100%;
            height: 200px;
            background: #cdd4e0;
            border-radius: 10px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 18px;
            color: #445;
            margin-bottom: 20px;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            background: #1f3b73;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background: #284d99;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo-skillmatch.png" alt="Logo SkillMatch" style="height:80px;margin-bottom:10px;" />
        <h1>SkillMatch - Escuela de Conductores de Maquinaria Pesada</h1>
        <p>Formación profesional con simuladores virtuales de alta tecnología</p>
    </header>

    <nav>
        <a href="#cursos">Cursos</a>
        <a href="#simuladores">Simuladores</a>
        <a href="#beneficios">Beneficios</a>
        <a href="#inscripcion">Inscripción</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="cursos" class="section">
        <h2>Cursos Disponibles</h2>
        <div class="image-placeholder">Imagen de curso (mockup)</div>
        <ul>
            <li>Operador de Grúa Horquilla</li>
            <li>Operador de Excavadora</li>
            <li>Operador de Retroexcavadora</li>
            <li>Operador de Bulldozer</li>
            <li>Operador de Cargador Frontal</li>
            <li>Manejo seguro y normativa vigente</li>
        </ul>
    </section>

    <section id="simuladores" class="section">
        <h2>Simuladores Virtuales</h2>
        <div class="image-placeholder">Imagen del simulador virtual</div>
        <p>Nuestros simuladores ofrecen una experiencia realista con escenarios dinámicos, controles fieles a la maquinaria original y análisis automático de desempeño.</p>
        <h3>Demo en video</h3>
        <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:10px;">
            <iframe src="https://www.youtube.com/embed/9Qe5hsj375o" style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allowfullscreen></iframe>
        </div>
    </section>

    <section id="beneficios" class="section">
        <h2>Beneficios del Entrenamiento Virtual</h2>
        <ul>
            <li>Entrenamiento seguro sin riesgos en terreno</li>
            <li>Reducción de costos operacionales</li>
            <li>Corrección de errores en tiempo real</li>
            <li>Mejora de técnicas y precisión operativa</li>
            <li>Preparación antes de operar maquinaria real</li>
        </ul>
    </section>

    <section id="mision" class="section">
        <h2>Misión</h2>
        <p>Formar operadores de maquinaria pesada altamente competentes mediante tecnología de simulación avanzada, promoviendo la seguridad, eficiencia y profesionalismo.</p>

        <h2>Visión</h2>
        <p>Ser la institución líder en formación técnica virtual en maquinaria pesada, reconocida por la excelencia académica y la innovación tecnológica.</p>

        <h2>Valores</h2>
        <ul>
            <li>Seguridad</li>
            <li>Responsabilidad</li>
            <li>Innovación</li>
            <li>Profesionalismo</li>
            <li>Respeto</li>
        </ul>
    </section>

    <section id="inscripcion" class="section">
        <h2>Formulario de Inscripción</h2>
        <form>
            <input type="text" placeholder="Nombre completo" required />
            <input type="email" placeholder="Correo electrónico" required />
            <input type="tel" placeholder="Número de teléfono" />
            <textarea placeholder="Escribe tu consulta aquí..." rows="4"></textarea>
            <button type="submit">Enviar</button>
        </form>

        <h3>Certificados Descargables</h3>
        <p>Puedes descargar un ejemplo de certificado haciendo clic abajo:</p>
        <a href="certificado-ejemplo.pdf" download style="color:#1f3b73;font-weight:bold;">Descargar Certificado</a>
    </section>

    <section id="galeria" class="section">
        <h2>Galería de Fotos</h2>
        <div class="image-placeholder" style="height:150px;">Excavadora</div>
        <div class="image-placeholder" style="height:150px;">Retroexcavadora</div>
        <div class="image-placeholder" style="height:150px;">Bulldozer</div>
        <div class="image-placeholder" style="height:150px;">Cargador Frontal</div>
        <div class="image-placeholder" style="height:150px;">Grúa Horquilla</div>
    </section>

    <section id="instructores" class="section">
        <h2>Perfiles de Instructores</h2>
        <ul>
            <li><strong>Carlos Muñoz:</strong> 15 años de experiencia operando excavadoras y bulldozers. Certificado internacional.</li>
            <li><strong>María López:</strong> Especialista en retroexcavadoras y cargadores frontales. Instructora senior.</li>
            <li><strong>Jorge Silva:</strong> Supervisor de operaciones mineras con amplia experiencia en formación técnica.</li>
        </ul>
    </section>

    <section id="contacto" class="section">
        <h2>Contacto</h2>
        <p><strong>Dirección:</strong> Av. Formación 2500, Antofagasta</p>
        <p><strong>Teléfono:</strong> +56 9 1234 5678</p>
        <p><strong>Correo:</strong> contacto@skillmatch.cl</p>
    </section>

    <script>
        // Pequeña animación suave al hacer scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>

</body>
</html>
