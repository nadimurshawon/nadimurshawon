<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nadimur Rahman Shawon | Software Engineer</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Base Dark Theme & Font */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #010409; /* Deep GitHub Dark */
            color: #f0f6f9;
        }
        /* Main Professional Card */
        .main-card {
            border: 1px solid #30363d;
            background-color: #0d1117;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
        }
        .main-card:hover {
            border-color: #58a6ff; /* Subtle blue highlight on hover */
        }
        /* Skill/Tech Card Effects */
        .skill-card {
            border: 1px solid #21262d;
            background-color: #161b22;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .skill-card:hover {
            transform: translateY(-4px);
            background-color: #1f252c;
            border-color: #3b82f6; /* Blue highlight */
            box-shadow: 0 8px 15px -3px rgba(59, 130, 246, 0.15);
        }
    </style>
</head>
<body class="p-4 md:p-10">

    <div class="max-w-6xl mx-auto space-y-12">

        <!-- 1. HERO AND PROFESSIONAL SUMMARY -->
        <div class="main-card p-6 md:p-10 rounded-2xl text-center">

            <!-- Profile Image -->
            <div class="inline-block p-1 rounded-full bg-gradient-to-r from-blue-500 to-cyan-500 mb-6">
                <!-- Fetching your GitHub Profile Picture -->
                <img src="https://github.com/nadimurshawon.png"
                     onerror="this.onerror=null;this.src='https://placehold.co/128x128/0d1117/ffffff?text=NS';"
                     alt="Nadimur Shawon Profile Picture"
                     class="w-32 h-32 rounded-full object-cover border-4 border-[#0d1117]">
            </div>

            <h1 class="text-4xl md:text-5xl font-extrabold text-white mb-2">
                Nadimur Shawon
            </h1>
            <p class="text-xl text-cyan-400 font-medium mb-4">
                Full-Stack Software Engineer | Next.js & TypeScript Specialist
            </p>

            <p class="text-md max-w-4xl mx-auto text-gray-400 leading-relaxed">
                A dedicated engineer focused on building highly scalable and performance-optimized full-stack applications. I specialize in modern JavaScript ecosystems, delivering clean code and robust architecture in every project.
            </p>

            <!-- Social/Contact Buttons -->
            <div class="mt-8 flex flex-col sm:flex-row justify-center items-center space-y-4 sm:space-y-0 sm:space-x-6">
                <a href="https://www.linkedin.com/in/nadimurshawon" target="_blank" class="inline-flex items-center justify-center px-8 py-3 text-base font-medium rounded-xl text-white bg-blue-600 hover:bg-blue-700 transition duration-300 w-full sm:w-auto">
                    <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path d="M4.98 3.5c0 1.381-1.11 2.5-2.48 2.5S0 4.881 0 3.5C0 2.12 1.11 1 2.5 1S4.98 2.12 4.98 3.5zm-2.48 4h4.96v14H2.5zm11.5 0h4.96V10c0-1.84 0-3.98-2.5-3.98s-2.5 2.14-2.5 3.98v11H9.98V7.5h4.02v1.78h.07c.56-.99 1.93-2.5 4.38-2.5 4.67 0 5.54 3.08 5.54 7.08V21h-4.98v-8.8c0-2.12-.5-3.66-2.85-3.66-1.55 0-2.31 1.05-2.69 2.07v10.39H9.98z"></path></svg>
                    View LinkedIn
                </a>
                <a href="mailto:your.professional.email@example.com" class="inline-flex items-center justify-center px-8 py-3 border border-gray-600 text-base font-medium rounded-xl text-gray-300 hover:text-white hover:bg-[#161b22] transition duration-300 w-full sm:w-auto">
                    <svg class="w-5 h-5 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8m-8 13h5.75A2.25 2.25 0 0021 18.75V6.25A2.25 2.25 0 0018.75 4H5.25A2.25 2.25 0 003 6.25v12.5A2.25 2.25 0 005.25 21H11"></path></svg>
                    Contact Me
                </a>
            </div>
        </div>

        <!-- 2. CORE COMPETENCIES / TECH STACK -->
        <section class="mt-12">
            <h2 class="text-3xl font-bold text-center text-white mb-6">🛠️ Core Competencies</h2>
            <div class="grid grid-cols-3 sm:grid-cols-4 lg:grid-cols-8 gap-4">

                <!-- Skill Cards using SkillIcons.dev for professional look -->
                <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">TypeScript</p>
                </div>
                 <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">Next.js</p>
                </div>
                 <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=react" alt="React" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">React</p>
                </div>
                 <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">Node.js</p>
                </div>
                 <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">MongoDB</p>
                </div>
                 <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=tailwind" alt="Tailwind CSS" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">Tailwind</p>
                </div>
                <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=docker" alt="Docker" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">Docker</p>
                </div>
                <div class="skill-card p-4 rounded-xl text-center flex flex-col items-center justify-center">
                    <img src="https://skillicons.dev/icons?i=aws" alt="AWS" class="w-10 h-10 mb-2">
                    <p class="text-sm font-medium text-gray-300">AWS</p>
                </div>
            </div>
        </section>


        <!-- 3. CONTRIBUTION GRID / DOTS (As Requested) -->
        <section class="mt-12">
            <h2 class="text-3xl font-bold text-center text-white mb-6">🗓️ Weekly Contribution Activity</h2>
            <!--
                IMPORTANT: This section explicitly shows the contribution grid (dots) as requested by the user.
                It uses the GitHub README Streak tool for a clean visualization.
            -->
            <div class="main-card p-6 rounded-2xl flex justify-center">
                 <img src="https://github-readme-streak-stats.herokuapp.com/?user=nadimurshawon&theme=dark&hide_border=true&border_radius=10&date_format=j%20M%5B%20Y%5D&ring=58a6ff&fire=58a6ff&stroke=0d1117&currStreakNum=f0f6f9&currStreakLabel=8b949e"
                     alt="GitHub Streak"
                     class="w-full h-auto rounded-lg mx-auto" style="max-width: 700px;">
            </div>
        </section>

        <!-- 4. GENERAL STATS & LANGUAGE USE -->
         <section class="mt-12">
            <h2 class="text-3xl font-bold text-center text-white mb-6">📊 GitHub Performance Overview</h2>
            <!-- Displays general statistics and top languages used -->
            <div class="flex flex-wrap justify-center gap-6">
                <!-- GitHub Stats Card -->
                <div class="main-card p-4 rounded-2xl flex-1 min-w-[300px] max-w-lg">
                    <img src="https://github-readme-stats.vercel.app/api?username=nadimurshawon&show_icons=true&theme=dark&include_all_commits=true&count_private=true&hide_border=true&border_radius=10&title_color=3b82f6&icon_color=3b82f6&text_color=f0f6f9&bg_color=0d1117"
                        alt="Nadimur Shawon GitHub Stats"
                        class="w-full h-auto rounded-lg">
                </div>
                <!-- Top Languages Card -->
                 <div class="main-card p-4 rounded-2xl flex-1 min-w-[300px] max-w-lg">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=nadimurshawon&layout=compact&theme=dark&langs_count=6&hide_border=true&border_radius=10&title_color=06b6d4&icon_color=06b6d4&text_color=f0f6f9&bg_color=0d1117"
                        alt="Nadimur Shawon Top Languages"
                        class="w-full h-auto rounded-lg">
                </div>
            </div>
        </section>

        <!-- 5. FOOTER & QUOTE -->
        <footer class="text-center py-8 border-t border-gray-800 mt-12">
            <p class="text-gray-500 text-lg mb-2 italic">
                "The only way to do great work is to love what you do."
            </p>
            <p class="text-sm text-gray-600 mt-4">
                Designed and Coded with passion.
            </p>
        </footer>

    </div>
</body>
</html>
