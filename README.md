‎
‎<!DOCTYPE html>
‎<html lang="pt-BR">
‎<head>
‎    <meta charset="UTF-8">
‎    <meta name="viewport" content="width=device-width, initial-scale=1.0">
‎    <title>Barbearia Estilo & Navalha</title>
‎    <!-- Tailwind CSS CDN para estilização rápida e moderna -->
‎    <script src="https://cdn.tailwindcss.com"></script>
‎    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
‎</head>
‎<body class="bg-zinc-900 text-zinc-100 font-sans">
‎
‎    <!-- Navegação -->
‎    <nav class="flex justify-between items-center px-8 py-5 border-b border-zinc-800 sticky top-0 bg-zinc-900/95 backdrop-blur z-50">
‎        <h1 class="text-2xl font-bold tracking-wider text-amber-500 uppercase"><i class="fa-solid font-black fa-scissors mr-2"></i>Navalha & Cia</h1>
‎        <div class="hidden md:flex space-x-6">
‎            <a href="#servicos" class="hover:text-amber-500 transition">Serviços</a>
‎            <a href="#sobre" class="hover:text-amber-500 transition">Sobre</a>
‎            <a href="#contato" class="hover:text-amber-500 transition">Contato</a>
‎        </div>
‎        <a href="https://wa.me/5500000000000" target="_blank" class="bg-amber-500 hover:bg-amber-600 text-zinc-900 font-bold px-4 py-2 rounded transition">
‎            Agendar Horário
‎        </a>
‎    </nav>
‎
‎    <!-- Hero Section -->
‎    <header class="relative bg-zinc-800 text-center py-24 px-4 bg-cover bg-center" style="background-image: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)), url('https://images.unsplash.com/photo-1503951914875-452162b0f3f1?auto=format&fit=crop&w=1200&q=80');">
‎        <h2 class="text-4xl md:text-6xl font-extrabold mb-4 uppercase tracking-wide">Estilo Tradicional & Corte Moderno</h2>
‎        <p class="text-zinc-300 text-lg md:text-xl max-w-2xl mx-auto mb-8">Tradição, ambiente descontraído e os melhores profissionais da região para cuidar do seu visual.</p>
‎        <a href="https://wa.me/5500000000000" target="_blank" class="bg-amber-500 hover:bg-amber-600 text-zinc-900 text-lg font-bold px-8 py-4 rounded-lg shadow-lg transition transform hover:scale-105 inline-block">
‎            <i class="fa-brands fa-whatsapp mr-2"></i>Agende pelo WhatsApp
‎        </a>
‎    </header>
‎
‎    <!-- Serviços e Preços -->
‎    <section id="servicos" class="max-w-5xl mx-auto py-20 px-6">
‎        <h3 class="text-3xl font-bold text-center mb-12 text-amber-500 uppercase tracking-wider">Nossos Serviços</h3>
‎        
‎        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
‎            <div class="bg-zinc-800 p-6 rounded-lg border border-zinc-700 hover:border-amber-500 transition">
‎                <h4 class="text-xl font-bold mb-2">Corte de Cabelo</h4>
‎                <p class="text-zinc-400 mb-4">Corte tradicional, degrade, fade ou estilizado com acabamento na navalha.</p>
‎                <span class="text-2xl font-bold text-amber-500">R$ 45,00</span>
‎            </div>
‎
‎            <div class="bg-zinc-800 p-6 rounded-lg border border-zinc-700 hover:border-amber-500 transition">
‎                <h4 class="text-xl font-bold mb-2">Barba Completa</h4>
‎                <p class="text-zinc-400 mb-4">Modelagem, toalha quente, óleo hidratante e alinhamento perfeito.</p>
‎                <span class="text-2xl font-bold text-amber-500">R$ 35,00</span>
‎            </div>
‎
‎            <div class="bg-zinc-800 p-6 rounded-lg border border-zinc-700 hover:border-amber-500 transition">
‎                <h4 class="text-xl font-bold mb-2">Combo Cabelo + Barba</h4>
‎                <p class="text-zinc-400 mb-4">O pacote completo com atendimento vip e bebida cortesia.</p>
‎                <span class="text-2xl font-bold text-amber-500">R$ 70,00</span>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <!-- Localização e Horários -->
‎    <section id="contato" class="bg-zinc-800 py-20 px-6 border-t border-zinc-700">
‎        <div class="max-w-5xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-12">
‎            <div>
‎                <h3 class="text-2xl font-bold mb-6 text-amber-500 uppercase">Horário de Funcionamento</h3>
‎                <ul class="space-y-3 text-zinc-300">
‎                    <li class="flex justify-between border-b border-zinc-700 pb-2"><span>Terça a Sexta</span> <span class="font-bold">09:00 - 20:00</span></li>
‎                    <li class="flex justify-between border-b border-zinc-700 pb-2"><span>Sábado</span> <span class="font-bold">08:00 - 18:00</span></li>
‎                    <li class="flex justify-between text-zinc-500"><span>Domingo e Segunda</span> <span>Fechado</span></li>
‎                </ul>
‎            </div>
‎
‎            <div>
‎                <h3 class="text-2xl font-bold mb-6 text-amber-500 uppercase">Onde Estamos</h3>
‎                <p class="text-zinc-300 mb-2"><i class="fa-solid fa-location-dot text-amber-500 mr-2"></i>Rua Exemplo, 123 - Centro, Sua Cidade</p>
‎                <p class="text-zinc-300 mb-6"><i class="fa-solid fa-phone text-amber-500 mr-2"></i>(00) 99999-9999</p>
‎                <a href="https://maps.google.com" target="_blank" class="inline-block bg-zinc-700 hover:bg-zinc-600 text-amber-500 font-bold px-6 py-3 rounded transition">
‎                    Ver no Google Maps
‎                </a>
‎            </div>
‎        </div>
‎    </section>
‎
‎    <!-- Rodapé -->
‎    <footer class="text-center py-6 text-zinc-500 text-sm border-t border-zinc-800">
‎        <p>&copy; 2026 Barbearia Navalha & Cia. Todos os direitos reservados.</p>
‎    </footer>
‎
‎</body>
‎</html>
‎
