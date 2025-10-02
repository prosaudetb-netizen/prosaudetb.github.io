<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Prosaúde TB - Produtos Naturais e Bem-Estar</title>
    <!-- Carregando Tailwind CSS para estilização moderna e responsiva -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configuração de fontes e cores personalizadas do Tailwind -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'pro-green': '#51A340', // Verde principal da marca
                        'pro-light': '#E9F5E6', // Verde claro para fundos
                        'pro-accent': '#FFD700', // Dourado ou amarelo para destaque (pode ser ajustado)
                        'pro-dark': '#386629', // Verde escuro para texto
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        /* Estilos adicionais para o design */
        .card-shadow {
            box-shadow: 0 10px 15px -3px rgba(81, 163, 64, 0.2), 0 4px 6px -2px rgba(81, 163, 64, 0.1);
        }
        .text-shadow {
            text-shadow: 1px 1px 3px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="bg-pro-light font-sans text-pro-dark antialiased">

    <!-- Cabeçalho (Header) Fixo -->
    <header class="sticky top-0 bg-white shadow-lg z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-3 flex justify-between items-center">
            <!-- Logo e Nome da Marca -->
            <div class="flex items-center space-x-2">
                <!-- Ícone da Prosaúde (Borboleta/Folha) em SVG -->
                <svg class="w-8 h-8 text-pro-green" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12 2C6.477 2 2 6.477 2 12C2 17.523 6.477 22 12 22C17.523 22 22 17.523 22 12C22 6.477 17.523 2 12 2ZM12 4C16.418 4 20 7.582 20 12C20 16.418 16.418 20 12 20C7.582 20 4 16.418 4 12C4 7.582 7.582 4 12 4ZM10 16L17 9L15.59 7.59L10 13.17L8.41 11.59L7 13L10 16Z" fill="currentColor"/>
                </svg>
                <h1 class="text-2xl font-bold text-pro-green">Prosaúde TB</h1>
            </div>
            
            <!-- Botão de Ação -->
            <a href="https://www.prosaudeprodutosnaturais.com.br/produtos/" target="_blank" class="px-4 py-2 bg-pro-green text-white font-semibold rounded-full hover:bg-pro-dark transition duration-300 shadow-md">
                Ver Catálogo Online
            </a>
        </div>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-10">

        <!-- Seção 1: Banner Principal e Introdução -->
        <section class="mb-16 bg-white rounded-xl overflow-hidden card-shadow">
            <div class="relative">
                <!-- Imagem da Fachada como Banner Principal -->
                <img ="/uploaded:WhatsApp Image 2025-10-01 at 10.42.53" 
                     alt="Fachada da Loja Prosaúde TB em Telêmaco Borba" 
                     class="w-full h-96 object-cover opacity-70">
                <div class="absolute inset-0 bg-pro-green bg-opacity-30 flex items-center justify-center">
                    <div class="text-center p-6 bg-white bg-opacity-90 rounded-lg shadow-2xl">
                        <h2 class="text-4xl sm:text-5xl font-extrabold text-pro-dark leading-tight text-shadow">
                            Seu Caminho para uma Vida Saudável
                        </h2>
                        <p class="mt-4 text-xl text-pro-green font-medium">
                            Produtos Naturais, Orgânicos e Alimentos Funcionais em Telêmaco Borba.
                        </p>
                    </div>
                </div>
            </div>
            
            <div class="p-8 sm:p-12">
                <h3 class="text-3xl font-bold text-pro-dark border-b-2 border-pro-green pb-3 mb-6">Nossa Missão</h3>
                <!-- Missão, Visão e Valores baseado na imagem "WhatsApp Image 2025-10-01 at 10.42.54 (2).jpeg" -->
                <div class="grid md:grid-cols-3 gap-8 text-center mt-6">
                    <div class="p-6 bg-pro-light rounded-lg border-2 border-pro-green">
                        <h4 class="font-bold text-xl mb-3 text-pro-green">MISSÃO</h4>
                        <p class="text-sm">Incentivar a prática de hábitos saudáveis que geram saúde, longevidade e auxiliem a prevenção de doenças através de recursos naturais.</p>
                    </div>
                    <div class="p-6 bg-pro-light rounded-lg border-2 border-pro-green">
                        <h4 class="font-bold text-xl mb-3 text-pro-green">VISÃO</h4>
                        <p class="text-sm">Tornar-se referência nacional em estilo de vida saudável e alimentação funcional que promovam vida integral.</p>
                    </div>
                    <div class="p-6 bg-pro-light rounded-lg border-2 border-pro-green">
                        <h4 class="font-bold text-xl mb-3 text-pro-green">VALORES</h4>
                        <p class="text-sm">Prover opção sólida, íntegra e comprometida com as melhores práticas de produção, de informação e de orientação capazes de promover um saúde integral com responsabilidade social e ambiental.</p>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- Seção 2: Os 3 Pilares da Marca -->
        <section class="mb-16">
            <h3 class="text-4xl font-extrabold text-center mb-10 text-pro-green text-shadow">A Marca Prosaúde e seus 3 Pilares</h3>
            <!-- Conteúdo baseado na imagem "WhatsApp Image 2025-10-01 at 10.42.55.jpeg" -->
            <div class="grid md:grid-cols-3 gap-6">
                
                <div class="bg-white p-8 rounded-xl card-shadow border-t-4 border-pro-green hover:scale-[1.02] transition duration-300">
                    <p class="text-4xl font-bold text-pro-green mb-3">1.</p>
                    <h4 class="text-2xl font-bold mb-3 text-pro-dark">CUIDAR PREVENTIVAMENTE</h4>
                    <p>Praticar uma alimentação saudável com produtos funcionais e orgânicos não é um luxo, é **investimento na saúde**.</p>
                </div>

                <div class="bg-white p-8 rounded-xl card-shadow border-t-4 border-pro-green hover:scale-[1.02] transition duration-300">
                    <p class="text-4xl font-bold text-pro-green mb-3">2.</p>
                    <h4 class="text-2xl font-bold mb-3 text-pro-dark">TRATAR NATURALMENTE</h4>
                    <p>A natureza é perfeita e nos dá tudo que precisamos para uma vida plena. Nossa proposta é conhecer profundamente o **poder da natureza e transformá-la em alternativa natural** para diversos tratamentos.</p>
                </div>
                
                <div class="bg-white p-8 rounded-xl card-shadow border-t-4 border-pro-green hover:scale-[1.02] transition duration-300">
                    <p class="text-4xl font-bold text-pro-green mb-3">3.</p>
                    <h4 class="text-2xl font-bold mb-3 text-pro-dark">VIVER INTENSAMENTE</h4>
                    <p>A medicina avança e aumenta nossa expectativa de vida. Nossa contribuição é garantir que você vá cada vez mais longe, porém, com a vitalidade necessária para ter uma **vida mais plena**.</p>
                </div>
            </div>
        </section>

        <!-- Seção 3: Galeria de Produtos (Imagens e Vídeos) -->
        <section class="mb-16">
            <h3 class="text-4xl font-extrabold text-center mb-10 text-pro-dark text-shadow">Conheça Nossos Produtos</h3>
            
            <div class="grid md:grid-cols-2 gap-8 mb-10">
                <!-- Vídeo 1: Visão Geral da Loja e Destaque -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow">
                    <video controls class="w-full h-80 object-cover" poster="/uploaded:WhatsApp Image 2025-10-01 at 10.42.54 (1).jpeg-3a4849e1-b55c-4b1d-b8e2-422e5f16447e">
                        <source src="/uploaded:WhatsApp Video 2025-10-01 at 10.42.56.mp4" type="video/mp4">
                        Seu navegador não suporta a tag de vídeo.
                    </video>
                    <div class="p-6">
                        <h4 class="text-xl font-bold text-pro-green">Nossos Destaques e Suplementos</h4>
                        <p class="text-sm mt-2">Um breve tour pela loja, mostrando alguns dos nossos produtos mais vendidos e as opções de suplementação para o seu dia a dia.</p>
                    </div>
                </div>

                <!-- Vídeo 2: Linha de Chás/Mates -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow">
                    <video controls class="w-full h-80 object-cover" poster="/uploaded:WhatsApp Image 2025-10-01 at 10.42.55 (1).jpeg-8831030e-754a-4c62-abef-ab921674bd4d">
                        <source src="/uploaded:WhatsApp Video 2025-10-01 at 10.42.56 (1).mp4" type="video/mp4">
                        Seu navegador não suporta a tag de vídeo.
                    </video>
                    <div class="p-6">
                        <h4 class="text-xl font-bold text-pro-green">Linha Fonte do Mate e Chás Especiais</h4>
                        <p class="text-sm mt-2">Apresentação dos nossos deliciosos e variados chás e mates funcionais, como o 'Morango, Valeriana, Anis, Funcho e Calêndula'.</p>
                    </div>
                </div>
            </div>

            <h4 class="text-3xl font-bold text-center mt-12 mb-6 text-pro-green">Mais de 2.000 Itens Naturais</h4>
            <p class="text-center text-lg mb-8 max-w-3xl mx-auto">Temos uma vasta seleção de produtos que cobrem diversas necessidades de saúde e bem-estar, desde emagrecimento até alimentos funcionais.</p>

            <!-- Galeria de Imagens de Produtos (simulando categorias) -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-4 gap-4">
                
                <div class="bg-white p-4 rounded-lg card-shadow">
                    <img src="/uploaded:WhatsApp Image 2025-10-01 at 10.42.54 (1).jpeg-3a4849e1-b55c-4b1d-b8e2-422e5f16447e" alt="Prateleiras internas com suplementos" class="w-full h-40 object-cover rounded-md mb-2">
                    <p class="text-sm font-semibold text-center">Suplementos e Vitaminas</p>
                </div>
                
                <div class="bg-white p-4 rounded-lg card-shadow">
                    <img src="/uploaded:WhatsApp Image 2025-10-01 at 10.42.54.jpeg-51d9fbb2-161a-4f2f-8d1f-a371d6a41800" alt="Exposição de produtos funcionais" class="w-full h-40 object-cover rounded-md mb-2">
                    <p class="text-sm font-semibold text-center">Alimentos Funcionais</p>
                </div>
                
                <div class="bg-white p-4 rounded-lg card-shadow">
                    <img src="/uploaded:WhatsApp Image 2025-10-01 at 10.17.02.jpeg-e2d324ad-464f-4117-8eea-e39fd16ab9a4" alt="Destaque de produtos para Emagrecimento, Diabéticos e Alergicos" class="w-full h-40 object-cover rounded-md mb-2">
                    <p class="text-sm font-semibold text-center">Linhas Especiais de Saúde</p>
                </div>

                <div class="bg-white p-4 rounded-lg card-shadow">
                    <img src="/uploaded:WhatsApp Image 2025-10-01 at 10.42.55 (1).jpeg-8831030e-754a-4c62-abef-ab921674bd4d" alt="Chás e erva mate especiais" class="w-full h-40 object-cover rounded-md mb-2">
                    <p class="text-sm font-semibold text-center">Ervas e Chás Artesanais</p>
                </div>

            </div>
            
            <!-- Botão de CTA para o Catálogo -->
            <div class="text-center mt-12">
                <a href="https://www.prosaudeprodutosnaturais.com.br/produtos/" target="_blank" class="inline-block px-8 py-4 bg-pro-dark text-white text-xl font-bold rounded-full hover:bg-pro-green transition duration-300 shadow-xl transform hover:scale-105">
                    Explore o Catálogo Completo (Mais de 2000 Produtos!)
                </a>
            </div>

        </section>
        
        <!-- Seção 4: Localização e Contato -->
        <section class="mb-10 p-8 bg-white rounded-xl card-shadow">
            <h3 class="text-3xl font-bold text-center mb-6 text-pro-dark">Onde nos Encontrar</h3>
            <div class="text-center text-lg">
                <p class="mb-2 font-medium">
                    <strong class="text-pro-green">Prosaúde TB - Telêmaco Borba</strong>
                </p>
                <p class="mb-4">
                    Av. Samuel Klabin, 474 - Centro<br>
                    Em frente à Praça da Bíblia.
                </p>
                <div class="space-y-2">
                    <!-- Link para o WhatsApp (Exemplo do número no vídeo) -->
                    <a href="https://wa.me/5542991311278" target="_blank" class="flex items-center justify-center text-pro-dark hover:text-pro-green transition duration-300">
                        <!-- Ícone do WhatsApp (usando SVG simples) -->
                        <svg class="w-6 h-6 mr-2" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg"><path d="M12.0031 2.00018C6.4801 2.00018 2.0031 6.47718 2.0031 12.0002C2.0031 14.7332 3.0901 17.2602 4.9081 19.1232L2.6101 22.1862L5.8081 21.6602C8.3611 22.8442 10.9761 22.9992 12.0031 22.0002C17.5261 22.0002 22.0031 17.5232 22.0031 12.0002C22.0031 6.47718 17.5261 2.00018 12.0031 2.00018ZM17.1521 15.9392C16.8901 16.4802 16.3271 16.4632 15.5311 16.2992C14.7361 16.1362 13.9211 15.8292 13.1971 15.3902C12.4571 14.9452 11.7581 14.3752 11.1341 13.6872C10.5131 12.9972 9.9761 12.2462 9.5391 11.4582C9.0981 10.6622 8.7891 9.8392 8.6251 9.0432C8.4601 8.2482 8.4411 7.6842 8.9831 7.4222C9.2561 7.2882 9.5701 7.1572 9.8841 7.1262C10.2011 7.0952 10.4571 7.0852 10.6551 7.4772C10.9251 8.0062 11.2371 8.6652 11.5831 9.3902C11.9331 10.1152 12.2981 10.7432 12.5931 11.1712C12.8901 11.5972 13.1091 11.8592 13.3661 12.1162C13.6261 12.3762 13.8881 12.5972 14.2801 12.8682C14.9921 13.4302 15.6881 14.1202 16.1821 14.6302C16.4381 14.8872 16.6341 15.1472 16.8901 15.3902C17.1521 15.6512 17.1521 15.7192 17.1521 15.9392Z" fill="currentColor"/></svg>
                        (42) 99131-1278 (WhatsApp)
                    </a>
                    <p class="text-base text-gray-600">
                        CNPJ: 33.719.213.0001-27
                    </p>
                </div>
            </div>
            
        </section>

    </main>

    <!-- Rodapé (Footer) -->
    <footer class="bg-pro-dark text-white py-6">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p>&copy; 2025 Prosaúde TB. Todos os direitos reservados. | Produtos Naturais, Orgânicos e Alimentos Funcionais.</p>
        </div>
    </footer>

</body>
</html>
