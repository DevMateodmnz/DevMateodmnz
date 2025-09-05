<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Habilidades Técnicas - Especializaciones Meta</title>
    <style>
        :root {
            --primary: #2563eb;
            --secondary: #4f46e5;
            --accent: #8b5cf6;
            --light: #f3f4f6;
            --dark: #1f2937;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9fafb;
            margin: 0;
            padding: 20px;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: white;
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            padding: 30px;
        }
        
        h1 {
            text-align: center;
            color: var(--dark);
            margin-bottom: 30px;
            font-size: 2.5rem;
            font-weight: 700;
        }
        
        .skills-table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
        }
        
        .skills-table th {
            background: linear-gradient(to right, var(--primary), var(--secondary));
            color: white;
            padding: 16px;
            text-align: left;
            font-size: 1.2rem;
        }
        
        .skills-table td {
            padding: 14px 16px;
            border-bottom: 1px solid #e5e7eb;
            vertical-align: top;
        }
        
        .skills-table tr:nth-child(even) {
            background-color: #f8fafc;
        }
        
        .skills-table tr:hover {
            background-color: #eff6ff;
        }
        
        .skill-category {
            font-weight: 600;
            color: var(--dark);
            width: 18%;
        }
        
        .skill-items {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill-item {
            background: var(--light);
            padding: 8px 14px;
            border-radius: 20px;
            font-size: 0.9rem;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
            display: inline-block;
            margin: 4px;
            transition: all 0.2s ease;
        }
        
        .skill-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            background: #e0e7ff;
        }
        
        .new-skill {
            background: #dcfce7;
            border-left: 4px solid #22c55e;
        }
        
        .legend {
            display: flex;
            justify-content: flex-end;
            align-items: center;
            margin-top: 20px;
            font-size: 0.9rem;
        }
        
        .legend-item {
            display: flex;
            align-items: center;
            margin-left: 20px;
        }
        
        .legend-color {
            width: 16px;
            height: 16px;
            border-radius: 4px;
            margin-right: 8px;
        }
        
        .new-color {
            background: #dcfce7;
        }
        
        .original-color {
            background: var(--light);
        }
        
        @media (max-width: 768px) {
            .skills-table {
                display: block;
                overflow-x: auto;
            }
            
            .skill-category {
                width: 25%;
            }
            
            .container {
                padding: 15px;
            }
            
            h1 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Habilidades Técnicas - Especializaciones Meta</h1>
        
        <table class="skills-table">
            <thead>
                <tr>
                    <th>Categoría</th>
                    <th>Tecnologías y Herramientas</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td class="skill-category">Lenguajes & Core</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">JAVASCRIPT</span>
                            <span class="skill-item">NODE.JS</span>
                            <span class="skill-item">HTML5</span>
                            <span class="skill-item">CSS3</span>
                            <span class="skill-item">TAILWIND CSS</span>
                            <span class="skill-item">MATERIAL UI</span>
                            <span class="skill-item new-skill">PYTHON</span>
                            <span class="skill-item new-skill">TYPESCRIPT</span>
                            <span class="skill-item new-skill">PHP</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">Frameworks & Librerías</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">REACT</span>
                            <span class="skill-item">REACT NATIVE</span>
                            <span class="skill-item">NEXT.JS</span>
                            <span class="skill-item">EXPRESS.JS</span>
                            <span class="skill-item new-skill">DJANGO</span>
                            <span class="skill-item new-skill">DJANGO REST</span>
                            <span class="skill-item new-skill">REDUX</span>
                            <span class="skill-item new-skill">APOLLO CLIENT</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">Bases de Datos</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">MONGODB</span>
                            <span class="skill-item new-skill">POSTGRESQL</span>
                            <span class="skill-item new-skill">MYSQL</span>
                            <span class="skill-item new-skill">SQLite</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">APIs & Herramientas</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">REST</span>
                            <span class="skill-item">GRAPHQL</span>
                            <span class="skill-item">POSTMAN</span>
                            <span class="skill-item">JWT</span>
                            <span class="skill-item">SOCKET.IO</span>
                            <span class="skill-item new-skill">APOLLO SERVER</span>
                            <span class="skill-item new-skill">OAUTH</span>
                            <span class="skill-item new-skill">WEBPACK</span>
                            <span class="skill-item new-skill">BABEL</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">Infra & Control de Versiones</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">GIT</span>
                            <span class="skill-item">GITHUB</span>
                            <span class="skill-item">AWS</span>
                            <span class="skill-item">NPM</span>
                            <span class="skill-item new-skill">DOCKER</span>
                            <span class="skill-item new-skill">KUBERNETES</span>
                            <span class="skill-item new-skill">CI/CD</span>
                            <span class="skill-item new-skill">HEROKU</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">Testing & QA</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item new-skill">JEST</span>
                            <span class="skill-item new-skill">REACT TESTING LIBRARY</span>
                            <span class="skill-item new-skill">CYPRESS</span>
                            <span class="skill-item new-skill">UNIT TESTING</span>
                            <span class="skill-item new-skill">INTEGRATION TESTING</span>
                        </div>
                    </td>
                </tr>
                <tr>
                    <td class="skill-category">Desarrollo Móvil</td>
                    <td>
                        <div class="skill-items">
                            <span class="skill-item">REACT NATIVE</span>
                            <span class="skill-item new-skill">EXPO</span>
                            <span class="skill-item new-skill">ANDROID STUDIO</span>
                            <span class="skill-item new-skill">XCODE</span>
                            <span class="skill-item new-skill">MOBILE UI/UX</span>
                        </div>
                    </td>
                </tr>
            </tbody>
        </table>
        
        <div class="legend">
            <div class="legend-item">
                <div class="legend-color original-color"></div>
                <span>Habilidades originales</span>
            </div>
            <div class="legend-item">
                <div class="legend-color new-color"></div>
                <span>Nuevas habilidades sugeridas</span>
            </div>
        </div>
    </div>
</body>
</html>
