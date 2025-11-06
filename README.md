<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Perfil Profesional - Oscar García</title>
    <style>
        :root {
            --bg-color: #0d1117;
            --text-color: #c9d1d9;
            --accent-color: #2f81f7;
            --card-bg: #161b22;
        }

        body {
            font-family: 'Segoe UI', Roboto, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            text-align: center;
            padding: 3rem 1rem 2rem;
        }

        header img {
            width: 150px;
            border-radius: 50%;
            border: 3px solid var(--accent-color);
        }

        h1 {
            font-size: 2.2rem;
            margin: 1rem 0 0.3rem;
        }

        h2 {
            color: var(--accent-color);
            margin-top: 2rem;
            text-align: center;
        }

        p {
            max-width: 700px;
            margin: 0.5rem auto;
            text-align: center;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            gap: 1.5rem;
            justify-items: center;
            margin: 2rem auto;
            max-width: 800px;
        }

        .tech-item {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 1rem;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .tech-item:hover {
            transform: translateY(-5px);
            box-shadow: 0 4px 12px rgba(47, 129, 247, 0.3);
        }

        .tech-item img {
            width: 50px;
            height: 50px;
            object-fit: contain;
        }

        .tech-item span {
            display: block;
            margin-top: 0.5rem;
            font-size: 0.9rem;
        }

        .cert-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 1.5rem;
            justify-items: center;
            margin: 2rem auto;
            max-width: 800px;
        }

        .cert-item {
            background: var(--card-bg);
            border-radius: 12px;
            padding: 1rem;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            width: 180px;
        }

        .cert-item img {
            width: 60px;
            height: 60px;
            object-fit: contain;
        }

        .cert-item span {
            display: block;
            margin-top: 0.5rem;
            font-size: 0.95rem;
            font-weight: 500;
            color: var(--text-color);
        }

        .cert-item:hover {
            transform: translateY(-7px);
            box-shadow: 0 6px 20px rgba(47, 129, 247, 0.4);
        }

            footer {
                text-align: center;
                margin-top: 2rem;
                padding: 1rem 0;
                border-top: 1px solid #30363d;
                font-size: 0.9rem;
            }

            a {
                color: var(--accent-color);
                text-decoration: none;
            }

            a:hover {
                text-decoration: underline;
            }
        </style>
</head>

<body>
    <header>
        <img src="https://avatars.githubusercontent.com/u/90071190?v=4" alt="Foto de perfil" />
        <h1>Oscar García</h1>
        <p>Administrador Certificado de Salesforce | Desarrollador en Sistemática Internacional</p>
        <p>Especialista en proyectos Salesforce, integración de APIs y desarrollo con Apex. Actualmente estudiando para
            obtener las certificaciones Platform App Builder y Salesforce Developer.</p>
    </header>

    <section>
        <h2>Tecnologías que manejo</h2>
        <div class="tech-grid">
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/salesforce/salesforce-original.svg"
                    alt="Salesforce" />
                <span>Salesforce</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apex/apex-original.svg" alt="Apex" />
                <span>Apex</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" />
                <span>HTML5</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
                <span>CSS3</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"
                    alt="JavaScript" />
                <span>JavaScript</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" />
                <span>C#</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" />
                <span>Java</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="SQL" />
                <span>SQL</span>
            </div>
            <div class="tech-item">
                <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" alt="GitHub" />
                <span>Git / GitHub</span>
            </div>
        </div>
    </section>

    <!-- Certificaciones -->
    <section class="section">
        <h2>Certificaciones</h2>
        <div class="cert-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(180px, 1fr)); gap: 1.5rem; justify-items: center; margin: 2rem auto; max-width: 800px;">
            <div class="cert-item" style="background: var(--card-bg); border-radius: 12px; padding: 1rem; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease;">
                <img src="https://drm.my.salesforce.com/servlet/servlet.ImageServer?id=015Rf00000MAGlB&oid=00DF0000000gZsu&lastMod=17467806380000" alt="Salesforce Admin" style="width:50px; height:50px; object-fit:contain;">
                <span style="display:block; margin-top:0.5rem; font-size:0.95rem;">Salesforce Certified Administrator</span>
            </div>
            <div class="cert-item" style="background: var(--card-bg); border-radius: 12px; padding: 1rem; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease;">
                <img src="https://tse3.mm.bing.net/th/id/OIP.6rwIg0G17RXjPZyn-ZIk0QHaEc?rs=1&pid=ImgDetMain&o=7&rm=3" alt="Platform App Builder" style="width:50px; height:50px; object-fit:contain;">
                <span style="display:block; margin-top:0.5rem; font-size:0.95rem;">CS50 Certified</span>
            </div>
        </div>
    </section>

    <footer>
        <p>© 2025 Oscar García | <a href="https://github.com/Oscaregg">GitHub</a> | <a
                href="https://www.salesforce.com/trailblazer/ob3m0p1uue8op5nfas">Trailhead</a></p>
    </footer>
</body>

</html>
