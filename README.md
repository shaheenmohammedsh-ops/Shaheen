<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shaheen Mohammed | AI & Data Science Portfolio</title>
    <meta name="description" content="Portfolio of Shaheen Mohammed - AI Student specializing in Machine Learning, Optimization, and Data Science.">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0ea5e9', // Sky blue
                            600: '#0284c7',
                            900: '#0c4a6e',
                        },
                        dark: {
                            bg: '#0f172a', // Slate 900
                            card: '#1e293b', // Slate 800
                            border: '#334155', // Slate 700
                        }
                    }
                }
            }
        }
    </script>
    <style>
        body {
            background-color: #0f172a;
            color: #e2e8f0;
        }
        .gradient-text {
            background: linear-gradient(to right, #38bdf8, #818cf8);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .nav-link {
            position: relative;
        }
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -4px;
            left: 0;
            background-color: #38bdf8;
            transition: width 0.3s ease;
        }
        .nav-link:hover::after {
            width: 100%;
        }
        .card-hover {
            transition: all 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px -10px rgba(56, 189, 248, 0.2);
            border-color: #38bdf8;
        }
    </style>
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 bg-slate-900/90 backdrop-blur-sm border-b border-slate-800">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex-shrink-0 font-bold text-xl tracking-wider text-white">
                    SHAHEEN<span class="text-sky-400">.AI</span>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#home" class="nav-link text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Home</a>
                        <a href="#about" class="nav-link text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">About</a>
                        <a href="#skills" class="nav-link text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Skills</a>
                        <a href="#projects" class="nav-link text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Projects</a>
                        <a href="#education" class="nav-link text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Education</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <!-- Mobile menu button placeholder -->
                    <button class="text-gray-300 hover:text-white focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="min-h-screen flex items-center justify-center pt-16">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="inline-block px-4 py-1.5 mb-6 rounded-full border border-sky-500/30 bg-sky-500/10 text-sky-300 text-sm font-medium tracking-wide">
                Available for Hire & Internships
            </div>
            <h1 class="text-5xl md:text-7xl font-bold tracking-tight mb-6 text-white">
                Hi, I'm <span class="gradient-text">Shaheen Mohammed</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-400 mb-8 max-w-2xl mx-auto leading-relaxed">
                Artificial Intelligence Student specializing in <span class="text-white">Machine Learning</span>, <span class="text-white">Data Science</span>, and <span class="text-white">Optimization Algorithms</span>.
            </p>
            <div class="flex justify-center space-x-4">
                <a href="#contact" class="px-8 py-3 rounded-lg bg-sky-600 hover:bg-sky-500 text-white font-semibold transition-colors shadow-lg shadow-sky-500/20">
                    Contact Me
                </a>
                <a href="https://github.com/shaheen-ai" target="_blank" class="px-8 py-3 rounded-lg border border-slate-600 hover:border-sky-400 text-gray-300 hover:text-white transition-colors flex items-center gap-2">
                    <!-- GitHub Icon -->
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/></svg>
                    GitHub
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-slate-900/50">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-8 text-center text-white">About Me</h2>
            <div class="bg-slate-800 rounded-2xl p-8 border border-slate-700 shadow-xl">
                <p class="text-gray-300 leading-relaxed text-lg mb-6">
                    I am an <strong class="text-sky-400">Artificial Intelligence student</strong> at the Faculty of Computers and Data Science, Alexandria University, with a strong academic background in mathematics, algorithms, and data-driven problem solving.
                </p>
                <p class="text-gray-300 leading-relaxed text-lg">
                    My interests lie in machine learning, data science, and optimization algorithms, with a focus on research-oriented applications and practical implementations. I am actively seeking opportunities for internships, research projects, and collaborative AI development to solve real-world problems.
                </p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-12 text-center text-white">Technical Arsenal</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Skill Group 1 -->
                <div class="bg-slate-800 rounded-xl p-6 border border-slate-700 hover:border-sky-500/50 transition-colors">
                    <h3 class="text-xl font-semibold mb-4 text-sky-400 flex items-center gap-2">
                        <!-- Code Icon -->
                        <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"/></svg>
                        Languages
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Python</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Java</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">SQL</span>
                    </div>
                </div>

                <!-- Skill Group 2 -->
                <div class="bg-slate-800 rounded-xl p-6 border border-slate-700 hover:border-sky-500/50 transition-colors">
                    <h3 class="text-xl font-semibold mb-4 text-sky-400 flex items-center gap-2">
                        <!-- Brain Icon -->
                        <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9.663 17h4.673M12 3v1m6.364 1.636l-.707.707M21 12h-1M4 12H3m3.343-5.657l-.707-.707m2.828 9.9a5 5 0 117.072 0l-.548.547A3.374 3.374 0 0014 18.469V19a2 2 0 11-4 0v-.531c0-.895-.356-1.754-.988-2.386l-.548-.547z"/></svg>
                        AI & Machine Learning
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Neural Networks</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Data Mining</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Pattern Recognition</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Feature Engineering</span>
                    </div>
                </div>

                <!-- Skill Group 3 -->
                <div class="bg-slate-800 rounded-xl p-6 border border-slate-700 hover:border-sky-500/50 transition-colors">
                    <h3 class="text-xl font-semibold mb-4 text-sky-400 flex items-center gap-2">
                        <!-- Tools Icon -->
                        <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/></svg>
                        Libraries & Tools
                    </h3>
                    <div class="flex flex-wrap gap-2">
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">TensorFlow</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Scikit-learn</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Pandas</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">NumPy</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Git/GitHub</span>
                        <span class="px-3 py-1 bg-slate-700 rounded-full text-sm text-gray-200">Flask</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 bg-slate-900/50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-3xl font-bold mb-12 text-center text-white">Featured Projects</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                
                <!-- Project 1 -->
                <div class="bg-slate-800 rounded-xl overflow-hidden border border-slate-700 card-hover flex flex-col">
                    <div class="p-6 flex-1">
                        <div class="flex justify-between items-start mb-4">
                            <h3 class="text-xl font-bold text-white">Ant Colony Optimization in Smart Contracts</h3>
                            <span class="bg-purple-900/50 text-purple-300 text-xs px-2 py-1 rounded border border-purple-700/50">Research</span>
                        </div>
                        <p class="text-gray-400 mb-6 text-sm leading-relaxed">
                            A research-focused project applying Ant Colony Optimization (ACO) to improve efficiency and security in blockchain smart contracts. Conducted comparative analysis with Simulated Annealing to evaluate performance.
                        </p>
                        <div class="flex flex-wrap gap-2 mt-auto">
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Heuristic Algorithms</span>
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Optimization</span>
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Python</span>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="bg-slate-800 rounded-xl overflow-hidden border border-slate-700 card-hover flex flex-col">
                    <div class="p-6 flex-1">
                         <div class="flex justify-between items-start mb-4">
                            <h3 class="text-xl font-bold text-white">University Course Registration System</h3>
                            <span class="bg-blue-900/50 text-blue-300 text-xs px-2 py-1 rounded border border-blue-700/50">System Dev</span>
                        </div>
                        <p class="text-gray-400 mb-6 text-sm leading-relaxed">
                            Developed an efficient course registration system using Java and linked data structures. Implemented sorting mechanisms, and Undo/Redo operations using stack-based logic, emphasizing space efficiency.
                        </p>
                        <div class="flex flex-wrap gap-2 mt-auto">
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Java</span>
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Data Structures</span>
                            <span class="text-xs font-mono text-sky-400 border border-sky-900 bg-sky-900/20 px-2 py-1 rounded">Algorithms</span>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Education & Soft Skills -->
    <section id="education" class="py-20">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                
                <!-- Education Column -->
                <div>
                    <h2 class="text-2xl font-bold mb-8 text-white flex items-center gap-2">
                        <svg class="w-6 h-6 text-sky-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path d="M12 14l9-5-9-5-9 5 9 5z"/><path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"/><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"/></svg>
                        Education
                    </h2>
                    <div class="border-l-2 border-slate-700 pl-8 ml-3 space-y-8">
                        <div class="relative">
                            <div class="absolute -left-[39px] bg-slate-900 border-2 border-sky-500 w-5 h-5 rounded-full"></div>
                            <h3 class="text-xl font-bold text-white">Bachelor of Artificial Intelligence</h3>
                            <p class="text-sky-400">Faculty of Computers and Data Science, Alexandria University</p>
                            <p class="text-gray-500 text-sm mt-1">Expected Graduation: 2028</p>
                        </div>
                        
                        <div>
                            <h4 class="text-lg font-semibold text-gray-200 mb-2">Key Coursework</h4>
                            <ul class="grid grid-cols-2 gap-2 text-sm text-gray-400">
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Linear Algebra</li>
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Calculus</li>
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Probability & Statistics</li>
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Data Structures</li>
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Neural Networks</li>
                                <li class="flex items-center gap-2"><div class="w-1.5 h-1.5 bg-sky-500 rounded-full"></div>Operations Research</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Soft Skills Column -->
                <div>
                    <h2 class="text-2xl font-bold mb-8 text-white flex items-center gap-2">
                         <svg class="w-6 h-6 text-sky-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"/></svg>
                        Soft Skills
                    </h2>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                        <div class="bg-slate-800/50 p-4 rounded-lg border border-slate-700">
                            <h4 class="font-semibold text-white">Analytical Thinking</h4>
                            <p class="text-sm text-gray-500 mt-1">Breaking down complex problems.</p>
                        </div>
                        <div class="bg-slate-800/50 p-4 rounded-lg border border-slate-700">
                            <h4 class="font-semibold text-white">Problem Solving</h4>
                            <p class="text-sm text-gray-500 mt-1">Finding optimal solutions.</p>
                        </div>
                        <div class="bg-slate-800/50 p-4 rounded-lg border border-slate-700">
                            <h4 class="font-semibold text-white">Research Skills</h4>
                            <p class="text-sm text-gray-500 mt-1">Academic & technical research.</p>
                        </div>
                        <div class="bg-slate-800/50 p-4 rounded-lg border border-slate-700">
                            <h4 class="font-semibold text-white">Continuous Learning</h4>
                            <p class="text-sm text-gray-500 mt-1">Adapting to new AI trends.</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer / Contact -->
    <footer id="contact" class="bg-slate-950 py-12 border-t border-slate-800">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-2xl font-bold text-white mb-6">Let's Connect</h2>
            <p class="text-gray-400 mb-8">
                I'm currently looking for internships and new opportunities. 
                Whether you have a question or just want to say hi, I'll try my best to get back to you!
            </p>
            
            <div class="flex flex-col md:flex-row justify-center items-center gap-6 mb-12">
                <a href="mailto:shaheenmohammedsh@gmail.com" class="flex items-center gap-2 text-gray-300 hover:text-sky-400 transition-colors">
                    <svg class="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>
                    shaheenmohammedsh@gmail.com
                </a>
                <a href="https://www.linkedin.com/in/shaheen-mohammed-a2355036a" target="_blank" class="flex items-center gap-2 text-gray-300 hover:text-sky-400 transition-colors">
                    <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M19 0h-14c-2.761 0-5 2.239-5 5v14c0 2.761 2.239 5 5 5h14c2.762 0 5-2.239 5-5v-14c0-2.761-2.238-5-5-5zm-11 19h-3v-11h3v11zm-1.5-12.268c-.966 0-1.75-.79-1.75-1.764s.784-1.764 1.75-1.764 1.75.79 1.75 1.764-.783 1.764-1.75 1.764zm13.5 12.268h-3v-5.604c0-3.368-4-3.113-4 0v5.604h-3v-11h3v1.765c1.396-2.586 7-2.777 7 2.476v6.759z"/></svg>
                    LinkedIn Profile
                </a>
            </div>

            <p class="text-slate-600 text-sm">
                &copy; 2025 Shaheen Mohammed. All rights reserved.
            </p>
        </div>
    </footer>

</body>
</html>  
