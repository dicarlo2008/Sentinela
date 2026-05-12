<!DOCTYPE html>
<html lang="pt-PT">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LinuxBot Forense | Security Engine</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fira+Code:wght@300;400;500;700&display=swap');

        :root {
            --neon-green: #00ff41;
            --dark-bg: #0a0a0a;
            --card-bg: #141414;
        }

        body {
            background-color: var(--dark-bg);
            color: #e0e0e0;
            font-family: 'Fira Code', monospace;
            line-height: 1.6;
        }

        .neon-border {
            border: 1px solid var(--neon-green);
            box-shadow: 0 0 10px rgba(0, 255, 65, 0.2);
        }

        .neon-text {
            color: var(--neon-green);
            text-shadow: 0 0 5px rgba(0, 255, 65, 0.5);
        }

        .gradient-bg {
            background: linear-gradient(180deg, #141414 0%, #0a0a0a 100%);
        }

        .status-pulse {
            width: 10px;
            height: 10px;
            background-color: var(--neon-green);
            border-radius: 50%;
            display: inline-block;
            animation: pulse 2s infinite;
        }

        @keyframes pulse {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 255, 65, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(0, 255, 65, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(0, 255, 65, 0); }
        }

        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #0a0a0a;
        }
        ::-webkit-scrollbar-thumb {
            background: #333;
            border-radius: 4px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: var(--neon-green);
        }
    </style>
</head>
<body class="p-4 md:p-8">

    <div class="max-w-5xl mx-auto">
        <!-- Header Section -->
        <header class="text-center mb-12 p-8 neon-border rounded-lg bg-black">
            <div class="mb-4">
                <span class="status-pulse mr-2"></span>
                <span class="text-xs uppercase tracking-widest opacity-70 text-white">System Online | Kernel Active</span>
            </div>
            <h1 class="text-3xl md:text-5xl font-bold neon-text mb-4 uppercase tracking-tighter">
                🛡️ LINUXBOT FORENSE
            </h1>
            <p class="text-lg md:text-xl font-medium text-white opacity-90">
                Inteligência Forense e Automação de Defesa de Borda
            </p>
        </header>

        <!-- Estratégia -->
        <section class="mb-10">
            <h2 class="text-xl neon-text mb-4 flex items-center">
                <span class="mr-2">📖</span> DESCRIÇÃO ESTRATÉGICA
            </h2>
            <div class="bg-zinc-900 p-6 rounded-lg border-l-4 border-green-500">
                <p>
                    O <strong>LinuxBot Forense</strong> é uma solução avançada de engenharia de segurança desenvolvida para análise profunda e em tempo real de logs de servidores Web (Nginx/HAProxy). O motor utiliza lógica de score comportamental para rastreio de reputação de IPs, mitigando ataques antes que alcancem a camada de aplicação.
                </p>
            </div>
        </section>

        <!-- Stack Tecnológica / Inteligência -->
        <section class="mb-10">
            <h2 class="text-xl neon-text mb-6 flex items-center">
                <span class="mr-2">🧠</span> LÓGICA DE INTELIGÊNCIA E PERSISTÊNCIA
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Card 1 -->
                <div class="p-5 rounded-lg bg-zinc-900 border border-zinc-800 hover:border-green-500 transition-colors">
                    <h3 class="text-green-400 font-bold mb-2">Scoring de Reputação</h3>
                    <p class="text-sm opacity-80">Avaliação dinâmica baseada em erros HTTP (400, 403, 444) e acesso a diretórios sensíveis.</p>
                </div>
                <!-- Card 2 -->
                <div class="p-5 rounded-lg bg-zinc-900 border border-zinc-800 hover:border-green-500 transition-colors">
                    <h3 class="text-green-400 font-bold mb-2">Cache Ultra-Rápido (Redis)</h3>
                    <p class="text-sm opacity-80">Rastreio imediato de tentativas e contagem de hits em milissegundos para bloqueio instantâneo.</p>
                </div>
                <!-- Card 3 -->
                <div class="p-5 rounded-lg bg-zinc-900 border border-zinc-800 hover:border-green-500 transition-colors">
                    <h3 class="text-green-400 font-bold mb-2">Persistência (MariaDB)</h3>
                    <p class="text-sm opacity-80">Histórico de incidentes para análise forense, identificação de reincidência e relatórios estruturados.</p>
                </div>
                <!-- Card 4 -->
                <div class="p-5 rounded-lg bg-zinc-900 border border-zinc-800 hover:border-green-500 transition-colors">
                    <h3 class="text-green-400 font-bold mb-2">Ação via Kernel</h3>
                    <p class="text-sm opacity-80">Integração nativa com o framework <strong>nftables</strong>, garantindo performance extrema e zero impacto na CPU.</p>
                </div>
            </div>
        </section>

        <!-- Arquitetura -->
        <section class="mb-10">
            <h2 class="text-xl neon-text mb-4 flex items-center">
                <span class="mr-2">📂</span> ARQUITETURA DO SISTEMA
            </h2>
            <div class="bg-black p-6 rounded-lg neon-border">
                <ul class="space-y-4">
                    <li class="flex items-start">
                        <span class="text-green-500 mr-2">▶</span>
                        <div>
                            <strong class="text-white">Motor de Análise:</strong> Scripts Bash/Python otimizados para parsing em tempo real.
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-green-500 mr-2">▶</span>
                        <div>
                            <strong class="text-white">Base de Inteligência Híbrida:</strong> 
                            <span class="block text-sm opacity-70">Redis (Estados voláteis) + MariaDB (Blacklist e Auditoria).</span>
                        </div>
                    </li>
                    <li class="flex items-start">
                        <span class="text-green-500 mr-2">▶</span>
                        <div>
                            <strong class="text-white">Interface Dashboard:</strong> Painel Streamlit para monitorização geográfica e forense.
                        </div>
                    </li>
                </ul>
            </div>
        </section>

        <!-- Automação -->
        <section class="mb-12">
            <h2 class="text-xl neon-text mb-4 flex items-center">
                <span class="mr-2">⚙️</span> OPERAÇÃO ZERO-TOUCH
            </h2>
            <div class="flex flex-col md:flex-row justify-between gap-4">
                <div class="flex-1 p-4 bg-zinc-900 text-center rounded-lg border-b-2 border-green-900">
                    <span class="text-2xl mb-2 block">1</span>
                    <span class="text-xs uppercase font-bold text-green-500">Monitorização</span>
                </div>
                <div class="flex-1 p-4 bg-zinc-900 text-center rounded-lg border-b-2 border-green-900">
                    <span class="text-2xl mb-2 block">2</span>
                    <span class="text-xs uppercase font-bold text-green-500">Identificação</span>
                </div>
                <div class="flex-1 p-4 bg-zinc-900 text-center rounded-lg border-b-2 border-green-900">
                    <span class="text-2xl mb-2 block">3</span>
                    <span class="text-xs uppercase font-bold text-green-500">Execução</span>
                </div>
            </div>
        </section>

        <!-- Footer / Nota -->
        <footer class="mt-20 pt-8 border-t border-zinc-800 text-center">
            <div class="bg-yellow-900/20 text-yellow-500 p-4 rounded-lg text-xs mb-8 text-left border border-yellow-900/50">
                <strong>NOTA DE SEGURANÇA:</strong> Por questões de integridade, os scripts de execução e comandos de infraestrutura são mantidos em ambiente privado. Este documento foca na arquitetura.
            </div>
            <div class="text-zinc-500 text-[10px] uppercase tracking-[0.3em]">
                Bare Metal Security Solutions | DicCarlo SOC
            </div>
        </footer>
    </div>

</body>
</html>
