<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jornada Universitária - Conteúdos Digitais para Universitários</title>
    <meta name="description" content="E-books, podcasts, artigos e lives para ajudar universitários a otimizar seus estudos e vida acadêmica">
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8f9fa;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #2c3e50 0%, #3498db 100%);
        }
        .transition-all {
            transition: all 0.3s ease;
        }
        .hover-scale:hover {
            transform: scale(1.03);
        }
        .hero-section {
            background: url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/feffda66-d768-454f-ad1c-bcd6065699c0.png') no-repeat center center;
            background-size: cover;
            position: relative;
        }
        .hero-overlay {
            background: rgba(0, 0, 0, 0.6);
        }
    </style>
</head>
<body class="antialiased">
    <!-- WhatsApp Float Button -->
    <a href="https://wa.me/5511999999999" target="_blank" class="fixed bottom-6 right-6 bg-green-500 text-white p-3 rounded-full shadow-lg hover:bg-green-600 transition-all z-50">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="currentColor">
            <path d="M.057 24l1.687-6.163c-1.041-1.804-1.588-3.849-1.587-5.946.003-6.556 5.338-11.891 11.893-11.891 3.181.001 6.167 1.24 8.413 3.488 2.245 2.248 3.481 5.236 3.48 8.414-.003 6.557-5.338 11.892-11.893 11.892-1.99-.001-3.951-.5-5.688-1.448l-6.305 1.654zm6.597-3.807c1.676.995 3.276 1.591 5.392 1.592 5.448 0 9.886-4.434 9.889-9.885.002-5.462-4.415-9.89-9.881-9.892-5.452 0-9.887 4.434-9.889 9.884-.001 2.225.651 3.891 1.746 5.634l-.999 3.648 3.742-.981zm11.387-5.464c-.074-.124-.272-.198-.57-.347-.297-.149-1.758-.868-2.031-.967-.272-.099-.47-.149-.669.149-.198.297-.768.967-.941 1.165-.173.198-.347.223-.644.074-.297-.149-1.255-.462-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.297-.347.446-.521.151-.172.2-.296.3-.495.099-.198.05-.372-.025-.521-.075-.148-.669-1.611-.916-2.206-.242-.579-.487-.501-.669-.51l-.57-.01c-.198 0-.52.074-.792.372s-1.04 1.016-1.04 2.479 1.065 2.876 1.213 3.074c.149.198 2.095 3.2 5.076 4.487.709.306 1.263.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.695.248-1.29.173-1.414z"/>
        </svg>
    </a>

    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-40">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/303b3182-54b1-4a3e-87bf-041aea35363f.png" alt="Logo Jornada Universitária - Livro aberto com capa azul e detalhes dourados" class="h-8 w-auto">
                        <span class="ml-2 text-xl font-bold text-gray-800">Jornada Universitária</span>
                    </div>
                    <div class="hidden sm:ml-6 sm:flex sm:space-x-8">
                        <a href="#" class="text-blue-600 border-blue-500 px-3 py-2 text-sm font-medium">Home</a>
                        <a href="#" class="text-gray-500 hover:border-gray-300 hover:text-gray-700 px-3 py-2 text-sm font-medium">E-books</a>
                        <a href="#" class="text-gray-500 hover:border-gray-300 hover:text-gray-700 px-3 py-2 text-sm font-medium">Podcast</a>
                        <a href="#" class="text-gray-500 hover:border-gray-300 hover:text-gray-700 px-3 py-2 text-sm font-medium">Blog</a>
                        <a href="#" class="text-gray-500 hover:border-gray-300 hover:text-gray-700 px-3 py-2 text-sm font-medium">Lives</a>
                        <a href="#" class="text-gray-500 hover:border-gray-300 hover:text-gray-700 px-3 py-2 text-sm font-medium">Sobre</a>
                    </div>
                </div>
                <div class="hidden sm:ml-6 sm:flex sm:items-center">
                    <button class="bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-md text-sm font-medium transition-all hover-scale">
                        Área do Aluno
                    </button>
                </div>
                <div class="-mr-2 flex items-center sm:hidden">
                    <!-- Mobile menu button -->
                    <button id="mobile-menu-button" type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-gray-500 hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-inset focus:ring-blue-500">
                        <svg class="block h-6 w-6" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
                        </svg>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden sm:hidden bg-white border-t border-gray-200">
            <div class="pt-2 pb-3 space-y-1">
                <a href="#" class="bg-blue-50 border-blue-500 text-blue-700 block px-3 py-2 text-base font-medium">Home</a>
                <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block px-3 py-2 text-base font-medium">E-books</a>
                <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block px-3 py-2 text-base font-medium">Podcast</a>
                <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block px-3 py-2 text-base font-medium">Blog</a>
                <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block px-3 py-2 text-base font-medium">Lives</a>
                <a href="#" class="border-transparent text-gray-500 hover:bg-gray-50 hover:border-gray-300 hover:text-gray-700 block px-3 py-2 text-base font-medium">Sobre</a>
                <div class="px-3 py-2">
                    <button class="w-full bg-blue-600 hover:bg-blue-700 text-white px-4 py-2 rounded-md text-sm font-medium transition-all">
                        Área do Aluno
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <div class="hero-section relative h-96 md:h-screen max-h-screen">
        <div class="hero-overlay absolute inset-0 flex items-center">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-4xl md:text-6xl font-bold text-white mb-4">
                    Estuda com quem vive a correria da faculdade
                </h1>
                <p class="text-xl md:text-2xl text-gray-200 mb-8">
                    Conteúdos digitais para universitários que querem se destacar
                </p>
                <div class="flex flex-col sm:flex-row justify-center gap-4">
                    <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white px-8 py-4 rounded-lg text-lg font-semibold transition-all hover-scale">
                        Conheça nossos e-books
                    </a>
                    <a href="#" class="bg-transparent hover:bg-white text-white hover:text-gray-800 border-2 border-white px-8 py-4 rounded-lg text-lg font-semibold transition-all hover-scale">
                        Comece grátis
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Lead Capture Form -->
    <div class="bg-gray-100 py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-4xl mx-auto bg-white rounded-xl shadow-md overflow-hidden p-6 md:p-8">
            <div class="md:flex">
                <div class="md:w-1/3 bg-blue-600 p-6 flex flex-col justify-center items-center text-center text-white rounded-lg">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" />
                    </svg>
                    <h3 class="text-xl font-bold mb-2">Guia Gratuito</h3>
                    <p class="text-blue-100">"5 Hábitos para um Semestre Produtivo"</p>
                </div>
                <div class="md:w-2/3 p-6">
                    <h2 class="text-2xl font-bold text-gray-800 mb-4">Receba nosso e-book grátis!</h2>
                    <form class="space-y-4">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700">Nome completo</label>
                            <input type="text" id="name" name="name" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700">E-mail</label>
                            <input type="email" id="email" name="email" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                        </div>
                        <div>
                            <label for="course" class="block text-sm font-medium text-gray-700">Seu curso</label>
                            <select id="course" name="course" class="mt-1 block w-full border border-gray-300 rounded-md shadow-sm py-2 px-3 focus:outline-none focus:ring-blue-500 focus:border-blue-500">
                          
