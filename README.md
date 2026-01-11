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
<body class="antialiased"
