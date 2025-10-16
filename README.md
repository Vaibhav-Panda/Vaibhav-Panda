<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vaibhav Panda | Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap" rel="stylesheet">
    <!-- Chosen Palette: "Warm Neutral" - A calming palette with a light off-white background (#f8f7f4), dark slate-gray text, and a muted teal accent color for links and highlights. -->
    <!-- Application Structure Plan: A single-page, top-to-bottom scrolling portfolio. The structure includes a hero/header, about section, tech stack showcase, and a contact/connect section. This linear flow is the most intuitive way to present a personal profile, guiding the user through the information logically from introduction to skills to contact. It's simple, effective, and highly usable on all devices. -->
    <!-- Visualization & Content Choices: Report Info: Tech Stack -> Goal: Showcase skills visually -> Presentation Method: Grid of images (from skillicons.dev) -> Interaction: None needed, purely visual -> Justification: Icons are more engaging and quicker to scan than a text list. Using an external image service is efficient. Report Info: Connect Links -> Goal: Provide contact points -> Presentation Method: Styled anchor tags with logos (from img.shields.io) -> Interaction: Click to open link in a new tab, hover effect for feedback -> Justification: Badges are visually appealing and provide clear calls to action. -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8f7f4;
            color: #334155;
        }
        .section-card {
            background-color: #ffffff;
            border: 1px solid #e2e8f0;
        }
    </style>
</head>
<body class="antialiased">
    <div class="container mx-auto px-4 py-8 md:py-16 max-w-4xl">

        <header class="text-center mb-12 md:mb-16">
            <h1 class="text-4xl md:text-5xl font-bold text-slate-800">👋 Hi, I'm Vaibhav Panda</h1>
            <div class="mt-4 text-slate-600 flex flex-wrap justify-center items-center gap-x-4 gap-y-2 text-sm md:text-base">
                <span class="inline-block">🎓 Student at IIT (ISM) Dhanbad</span>
                <span class="hidden md:inline-block text-slate-400">&bull;</span>
                <span class="inline-block">📘 B.Tech in ECE</span>
                <span class="hidden md:inline-block text-slate-400">&bull;</span>
                <span class="inline-block">💻 Full Stack Developer</span>
            </div>
        </header>

        <main class="space-y-10">
            <section id="about" class="section-card rounded-xl p-6 md:p-8 shadow-sm">
                <h2 class="text-2xl font-bold text-slate-700 mb-4">🧠 About Me</h2>
                <div class="space-y-4 text-slate-600">
                    <p>
                        I'm passionate about building efficient, scalable, and user-friendly applications.
                    </p>
                    <p>
                        I love exploring how algorithms meet real-world software design — from frontend interactions to backend logic.
                    </p>
                </div>
            </section>

            <section id="tech-stack" class="section-card rounded-xl p-6 md:p-8 shadow-sm">
                <h2 class="text-2xl font-bold text-slate-700 mb-6">🛠️ Tech Stack</h2>
                <div class="flex justify-center items-center flex-wrap gap-4">
                     <img src="https://skillicons.dev/icons?i=cpp,c,js,react,css,tailwind,nodejs,matlab&perline=4" alt="Tech Stack Icons" />
                </div>
            </section>

            <section id="connect" class="section-card rounded-xl p-6 md:p-8 shadow-sm">
                <h2 class="text-2xl font-bold text-slate-700 mb-6">🌐 Connect With Me</h2>
                <div class="flex justify-center items-center flex-wrap gap-3">
                    <a href="https://your-portfolio-link-here.com" target="_blank" class="transition-transform hover:scale-105">
                        <img src="https://img.shields.io/badge/Portfolio-255E63?style=for-the-badge&logo=hugo&logoColor=white" alt="Portfolio Badge">
                    </a>
                    <a href="https://linkedin.com/in/your-link-here" target="_blank" class="transition-transform hover:scale-105">
                        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
                    </a>
                    <a href="https://github.com/your-username-here" target="_blank" class="transition-transform hover:scale-105">
                        <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
                    </a>
                    <a href="mailto:your-email-here@example.com" target="_blank" class="transition-transform hover:scale-105">
                        <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Badge">
                    </a>
                </div>
            </section>
        </main>

        <footer class="text-center mt-12 md:mt-16 text-slate-500 text-sm">
            <p>&copy; 2025 Vaibhav Panda. All Rights Reserved.</p>
        </footer>
    </div>
</body>
</html>
