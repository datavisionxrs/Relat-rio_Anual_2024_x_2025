<!DOCTYPE html>
<html lang="pt-pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Açoriana & DataVisionX - Relatório Comercial 2025</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700;800&display=swap" rel="stylesheet">
    <style>
        :root {
            --brand-red: #b91c1c; 
            --brand-orange: #f97316;
            --brand-gradient: linear-gradient(135deg, #b91c1c 0%, #f97316 100%);
        }
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
            background-color: #f8fafc;
        }
        .bg-brand-gradient { background: var(--brand-gradient); }
        .text-gradient {
            background: var(--brand-gradient);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        .section-card {
            background: white;
            border-radius: 1.5rem;
            border: 1px solid #e2e8f0;
            box-shadow: 0 4px 12px -2px rgb(0 0 0 / 0.05);
            transition: all 0.3s ease;
        }
        .section-card:hover {
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1);
            transform: translateY(-2px);
        }
        .metric-up { color: #10b981; }
        .sparkline {
            stroke-dasharray: 100;
            stroke-dashoffset: 100;
            animation: dash 2.5s ease-out forwards;
        }
        @keyframes dash {
            to { stroke-dashoffset: 0; }
        }
        @keyframes grow-bar {
            from { height: 0; }
            to { height: var(--target-height); }
        }
        .bar-grow {
            animation: grow-bar 1.5s ease-out forwards;
        }
        .custom-scrollbar::-webkit-scrollbar {
            width: 4px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: rgba(0, 0, 0, 0.05);
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: var(--brand-orange);
            border-radius: 10px;
        }
    </style>
</head>
<body class="text-slate-900">

    <!-- Navegação -->
    <nav class="sticky top-0 z-50 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex items-center space-x-3">
                    <div class="w-9 h-9 bg-brand-gradient rounded-lg flex items-center justify-center text-white font-extrabold shadow-sm">A</div>
                    <span class="font-extrabold text-lg uppercase tracking-tight text-slate-800">Comercial <span class="text-brand-orange">2025</span></span>
                </div>
                <div class="hidden md:flex space-x-8 text-[11px] font-black uppercase tracking-[0.15em] text-slate-500">
                    <a href="#performance" class="hover:text-brand-red transition">Performance</a>
                    <a href="#positivos" class="hover:text-brand-red transition">Sucessos</a>
                    <a href="#negativos" class="hover:text-brand-orange transition">Gaps</a>
                    <a href="#estrategia" class="hover:text-brand-red transition">Acções</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- 1. Visão Executiva -->
    <header id="visao" class="py-16 md:py-20 bg-white border-b border-slate-100">
        <div class="max-w-5xl mx-auto px-4">
            <div class="inline-block px-4 py-1.5 mb-8 text-[10px] font-black tracking-[0.25em] text-white uppercase bg-brand-gradient rounded-full shadow-sm">
                Açoriana • Documento Estratégico
            </div>
            <h1 class="text-4xl md:text-6xl font-black mb-10 leading-[1.1] text-slate-900 text-center md:text-left">
                Desempenho Comercial Anual | <br><span class="text-gradient uppercase">2024 vs 2025</span>
            </h1>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-10 items-start">
                <div class="md:col-span-2 text-lg md:text-xl text-slate-600 leading-relaxed font-light text-left">
                    O ano de 2025 consolidou a nossa trajectória de expansão. O faturamento cresceu <strong>15,92%</strong>, superando o volume físico e provando a força da nossa estratégia de mix e recomposição de margem comercial.
                </div>
                <div class="p-6 bg-orange-50 rounded-3xl border border-orange-100 shadow-sm text-left">
                    <h4 class="text-brand-orange font-black text-xs uppercase tracking-widest mb-3 leading-none">Atenção Estratégica</h4>
                    <p class="text-sm text-slate-700 leading-relaxed font-medium">
                        Identificamos retrações severas em redes de grande relevância e SKUs maduros, exigindo intervenção comercial imediata para sustentar o market share.
                    </p>
                </div>
            </div>
        </div>
    </header>

    <!-- 2. Insights de Performance -->
    <section id="performance" class="py-24 bg-slate-50">
        <div class="max-w-7xl mx-auto px-4">
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-12 border-l-4 border-brand-red pl-6">
                <h2 class="text-3xl font-black text-slate-900 tracking-tight">Painel Analítico de Resultados</h2>
                <p class="text-slate-400 font-bold uppercase text-[10px] tracking-[0.2em] mt-2 md:mt-0">Fechamento Consolidado Jan-Dez</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-stretch">
                <!-- LADO ESQUERDO: Resultado Geral -->
                <div class="lg:col-span-7 section-card p-8 md:p-10 bg-white">
                    <h3 class="text-lg font-extrabold text-slate-800 mb-12 flex items-center">
                        <span class="w-1.5 h-6 bg-brand-red mr-3 rounded-full"></span> Resultado Acumulado Anual
                    </h3>

                    <div class="space-y-10 text-left">
                        <!-- Metric Row -->
                        <div class="flex items-center justify-between group">
                            <div class="space-y-1">
                                <span class="text-[10px] font-black text-slate-400 uppercase tracking-widest leading-none">Faturamento Total</span>
                                <div class="text-2xl md:text-3xl font-black text-slate-900 tracking-tighter italic">R$ 29,0M <span class="mx-2 text-slate-300 font-light">→</span> R$ 33,6M</div>
                            </div>
                            <div class="flex flex-col items-end">
                                <span class="text-xl md:text-2xl font-black text-emerald-500 leading-none">+15,92%</span>
                                <svg class="w-20 h-8 text-emerald-500/20" viewBox="0 0 100 40">
                                    <path d="M0 35 L20 30 L40 32 L60 20 L80 15 L100 5" fill="none" stroke="currentColor" stroke-width="4" class="sparkline" />
                                </svg>
                            </div>
                        </div>

                        <div class="flex items-center justify-between group">
                            <div class="space-y-1">
                                <span class="text-[10px] font-black text-slate-400 uppercase tracking-widest leading-none">Volume Total (Kg/Un)</span>
                                <div class="text-2xl md:text-3xl font-black text-slate-900 tracking-tighter italic">6,3M <span class="mx-2 text-slate-300 font-light">→</span> 7,0M</div>
                            </div>
                            <div class="flex flex-col items-end">
                                <span class="text-xl md:text-2xl font-black text-emerald-500 leading-none">+11,80%</span>
                                <svg class="w-20 h-8 text-emerald-500/20" viewBox="0 0 100 40">
                                    <path d="M0 35 L20 33 L40 28 L60 25 L80 18 L100 10" fill="none" stroke="currentColor" stroke-width="4" class="sparkline" />
                                </svg>
                            </div>
                        </div>

                        <div class="flex items-center justify-between group">
                            <div class="space-y-1">
                                <span class="text-[10px] font-black text-slate-400 uppercase tracking-widest leading-none">Positivação (Clientes Ativos)</span>
                                <div class="text-2xl md:text-3xl font-black text-slate-900 tracking-tighter italic">2.968 <span class="mx-2 text-slate-300 font-light">→</span> 3.449</div>
                            </div>
                            <div class="flex flex-col items-end">
                                <span class="text-xl md:text-2xl font-black text-emerald-500 leading-none">+16,21%</span>
                                <svg class="w-20 h-8 text-emerald-500/20" viewBox="0 0 100 40">
                                    <path d="M0 38 L20 30 L40 35 L60 22 L80 15 L100 5" fill="none" stroke="currentColor" stroke-width="4" class="sparkline" />
                                </svg>
                            </div>
                        </div>
                    </div>

                    <div class="grid grid-cols-2 gap-6 mt-12 pt-10 border-t border-slate-100">
                        <div class="p-6 bg-slate-50 rounded-2xl text-left">
                            <p class="text-[10px] text-slate-400 font-black uppercase mb-2 tracking-widest">Preço Médio</p>
                            <p class="text-xl md:text-2xl font-black text-brand-red tracking-tight">R$ 4,77 <span class="text-xs font-bold text-emerald-600 ml-1">↑3.7%</span></p>
                        </div>
                        <div class="p-6 bg-slate-50 rounded-2xl text-left">
                            <p class="text-[10px] text-slate-400 font-black uppercase mb-2 tracking-widest">Ticket Médio</p>
                            <p class="text-xl md:text-2xl font-black text-brand-red tracking-tight">R$ 332,36 <span class="text-xs font-bold text-emerald-600 ml-1">↑22.8%</span></p>
                        </div>
                    </div>
                </div>

                <!-- LADO DIREITO: Dezembro -->
                <div class="lg:col-span-5 section-card p-8 md:p-10 bg-slate-900 text-white flex flex-col justify-between shadow-2xl relative overflow-hidden">
                    <div class="absolute right-0 top-0 w-32 h-32 bg-brand-orange opacity-5 blur-3xl"></div>
                    <div class="space-y-12 relative z-10">
                        <div class="flex items-center space-x-3 text-left">
                            <div class="w-1.5 h-6 bg-brand-orange rounded-full"></div>
                            <h3 class="text-xl font-extrabold text-white leading-none">Destaque de Dezembro</h3>
                        </div>
                        
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6 text-left">
                            <div class="p-5 bg-white/5 rounded-2xl border border-white/10 hover:bg-white/10 transition-colors">
                                <p class="text-[10px] text-slate-400 font-black uppercase tracking-[0.15em] mb-4 leading-none">Faturamento</p>
                                <p class="text-3xl font-extrabold text-white leading-none tracking-tighter">R$ 3,33M</p>
                                <p class="text-sm font-bold text-orange-400 mt-3 uppercase tracking-tighter">+11,58%</p>
                            </div>
                            <div class="p-5 bg-white/5 rounded-2xl border border-white/10 hover:bg-white/10 transition-colors">
                                <p class="text-[10px] text-slate-400 font-black uppercase tracking-[0.15em] mb-4 leading-none">Volume</p>
                                <p class="text-3xl font-extrabold text-white leading-none tracking-tighter">678K</p>
                                <p class="text-sm font-bold text-orange-400 mt-3 uppercase tracking-tighter">+11,22%</p>
                            </div>
                            <div class="p-5 bg-white/5 rounded-2xl border border-white/10 hover:bg-white/10 transition-colors text-left leading-none">
                                <p class="text-[10px] text-slate-400 font-black uppercase tracking-[0.15em] mb-4 leading-none">Positivação</p>
                                <p class="text-3xl font-extrabold text-white leading-none tracking-tighter">2.491</p>
                                <p class="text-sm font-bold text-orange-400 mt-3 uppercase tracking-tighter">+10,96%</p>
                            </div>
                            <div class="p-5 bg-white/5 rounded-2xl border border-white/10 hover:bg-white/10 transition-colors text-left leading-none">
                                <p class="text-[10px] text-slate-400 font-black uppercase tracking-[0.15em] mb-4 leading-none">Preço Médio</p>
                                <p class="text-3xl font-extrabold text-white leading-none tracking-tighter">R$ 4,92</p>
                                <p class="text-sm font-bold text-blue-300 mt-3 uppercase italic leading-none tracking-tighter">Estável</p>
                            </div>
                        </div>
                    </div>
                    <div class="mt-12 p-6 bg-white/5 rounded-3xl border border-white/10 text-left relative z-10">
                        <p class="text-sm leading-relaxed text-slate-300 italic">
                            <span class="text-white font-bold block mb-1 underline decoration-brand-orange underline-offset-4 uppercase tracking-tighter leading-none">Conclusão de Dezembro:</span>
                            Crescimento 'redondo' e sustentável, validando a força da execução comercial na ponta sem queima de margem.
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 3. Fatores de Sucesso -->
    <section id="positivos" class="py-24 bg-white text-left">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-2xl font-black mb-16 text-center uppercase tracking-[0.2em] text-slate-400 italic leading-none">Fatores de Sucesso</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 items-stretch">
                
                <!-- Card 1: Expansão -->
                <div class="section-card p-10 bg-slate-50 flex flex-col justify-between border-b-8 border-brand-red shadow-lg">
                    <div>
                        <div class="w-12 h-12 bg-brand-red rounded-2xl flex items-center justify-center text-white mb-8 shadow-lg shadow-red-100">
                            <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"></path></svg>
                        </div>
                        <h4 class="font-black text-slate-900 mb-4 text-xl">Expansão de Base</h4>
                        <p class="text-4xl font-black text-brand-red tracking-tighter leading-none">+16,21%</p>
                        <p class="text-[10px] font-black uppercase text-slate-400 tracking-widest mt-2 mb-8 leading-none">Crescimento de Clientes Ativos</p>
                    </div>
                    <p class="text-sm text-slate-600 leading-relaxed font-medium italic leading-snug">O ganho de capilaridade regional reduziu a vulnerabilidade comercial frente aos grandes grupos, equilibrando a carteira.</p>
                </div>

                <!-- Card 2: Motor do Ano (Vendas) -->
                <div class="section-card p-10 bg-slate-900 text-white flex flex-col justify-between shadow-xl border-b-8 border-brand-orange">
                    <div>
                        <h4 class="font-black text-orange-400 uppercase text-[11px] tracking-widest mb-10 text-center uppercase leading-none">Motor do Ano (Vendas)</h4>
                        <div class="space-y-4 text-slate-100 text-left text-sm leading-none font-medium">
                            <div class="flex justify-between items-center border-b border-white/5 pb-2">
                                <span class="text-slate-400">Pão de Alho 300g</span><span class="text-emerald-400 font-black">+ 23,4%</span>
                            </div>
                            <div class="flex justify-between items-center border-b border-white/5 pb-2">
                                <span class="text-slate-400">Massa Talharim 400g</span><span class="text-emerald-400 font-black">+ 16,7%</span>
                            </div>
                            <div class="flex justify-between items-center border-b border-white/5 pb-2">
                                <span class="text-slate-400">Pastel DG 400g</span><span class="text-emerald-400 font-black">+ 27,7%</span>
                            </div>
                            <div class="flex justify-between items-center border-b border-white/5 pb-2">
                                <span class="text-slate-400">Pastel DL 400g</span><span class="text-emerald-400 font-black">+ 27,8%</span>
                            </div>
                            <div class="flex justify-between items-center pb-2 text-left">
                                <span class="text-slate-400">Lasanha 400g</span><span class="text-emerald-400 font-black">+ 13,8%</span>
                            </div>
                        </div>
                    </div>
                    <div class="mt-8 p-4 bg-white/5 rounded-2xl border border-white/10 text-center leading-tight">
                        <p class="text-[9px] text-orange-300 font-black uppercase tracking-widest mb-1 leading-none">Representatividade</p>
                        <p class="text-sm font-bold text-white uppercase tracking-tighter">TOP 5 compõem <span class="text-emerald-400 text-lg font-black italic">59%</span> do total.</p>
                    </div>
                </div>

                <!-- Card 3: Performance por Canal (GRÁFICO QUALIFICADO) -->
                <div class="section-card p-10 bg-white border-2 border-slate-100 flex flex-col justify-between shadow-2xl relative overflow-hidden">
                    <div class="relative z-10 text-left">
                        <h4 class="font-black uppercase text-[10px] tracking-widest mb-8 text-slate-400 border-l-4 border-brand-red pl-3 leading-none uppercase">Crescimento por Canal</h4>
                        
                        <!-- Gráfico Visual de Crescimento -->
                        <div class="flex items-end justify-around h-44 mb-10 pt-4 bg-slate-50/50 rounded-[2rem] relative border border-slate-100 shadow-inner">
                            <!-- Bar 1: Redes -->
                            <div class="flex flex-col items-center group w-1/3">
                                <div class="relative w-full px-2">
                                    <div class="bg-brand-red w-full rounded-t-2xl shadow-lg bar-grow relative" style="--target-height: 140px; height: 0;">
                                        <div class="absolute -top-9 left-1/2 -translate-x-1/2 bg-brand-red text-white text-[10px] font-black px-2 py-1 rounded shadow-lg whitespace-nowrap leading-none tracking-tighter animate-pulse">
                                            +18,5%
                                        </div>
                                    </div>
                                </div>
                                <span class="mt-3 text-[10px] font-black text-slate-900 uppercase tracking-tighter leading-none">REDES</span>
                                <span class="text-[8px] font-bold text-slate-400 uppercase mt-1 leading-none tracking-tighter">29.6% share</span>
                            </div>

                            <!-- Bar 2: Varejo -->
                            <div class="flex flex-col items-center group w-1/3 text-left">
                                <div class="relative w-full px-2 text-left">
                                    <div class="bg-slate-300 w-full rounded-t-2xl shadow-md bar-grow opacity-80" style="--target-height: 110px; height: 0;">
                                        <div class="absolute -top-9 left-1/2 -translate-x-1/2 bg-slate-700 text-white text-[10px] font-black px-2 py-1 rounded shadow-lg whitespace-nowrap leading-none tracking-tighter">
                                            +14,9%
                                        </div>
                                    </div>
                                </div>
                                <span class="mt-3 text-[10px] font-black text-slate-900 uppercase tracking-tighter leading-none">VAREJO</span>
                                <span class="text-[8px] font-bold text-slate-400 uppercase mt-1 leading-none tracking-tighter">70.4% share</span>
                            </div>
                        </div>

                        <!-- Ticket Médio Detail -->
                        <div class="p-4 bg-slate-900 rounded-[2rem] shadow-xl text-left border border-white/10 group overflow-hidden relative">
                            <div class="absolute right-0 top-0 opacity-10 p-2 text-white"><svg class="w-12 h-12" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M12 7a1 1 0 110-2h5a1 1 0 011 1v5a1 1 0 11-2 0V8.414l-4.293 4.293a1 1 0 01-1.414 0L8 10.414l-4.293 4.293a1 1 0 01-1.414-1.414l5-5a1 1 0 011.414 0L11 10.586 14.586 7H12z" clip-rule="evenodd"></path></svg></div>
                            <p class="text-[9px] font-black uppercase text-brand-orange tracking-widest mb-1 leading-none">Ticket Médio Redes</p>
                            <p class="text-2xl font-black text-white italic tracking-tighter leading-none">R$ 1.035,60</p>
                            <p class="text-[10px] text-emerald-400 font-bold mt-2 leading-none">Ganho real: +R$ 74,09 p/ pedido</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 4. Pontos Negativos / Gaps (REDES EM QUEDA ACTUALIZADO) -->
    <section id="negativos" class="py-24 bg-slate-50 border-y border-slate-200 text-left">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-2xl font-black mb-16 text-center uppercase tracking-[0.2em] text-brand-red leading-none">Zonas de Intervenção Crítica</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- PRODUTOS BAIXO DESEMPENHO -->
                <div class="section-card p-8 border-t-[10px] border-brand-red text-left">
                    <h4 class="font-black text-red-600 mb-8 flex items-center uppercase text-[10px] tracking-[0.2em] leading-none">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 000 2h6a1 1 0 100-2H7z" clip-rule="evenodd"></path></svg>
                        PRODUTOS BAIXO DESEMPENHO
                    </h4>
                    <div class="space-y-3">
                        <div class="p-4 bg-red-50 rounded-2xl border border-red-100 flex justify-between items-center group">
                            <div class="leading-none"><p class="font-bold text-slate-800 text-sm tracking-tighter">Batata Palha 70g</p><p class="text-[10px] font-black text-red-600 uppercase tracking-tighter mt-1 leading-none">Faturamento</p></div>
                            <span class="text-xl font-black text-red-600 tracking-tighter">-30,2%</span>
                        </div>
                        <div class="p-4 bg-red-50 rounded-2xl border border-red-100 flex justify-between items-center group">
                            <div class="leading-none"><p class="font-bold text-slate-800 text-sm tracking-tighter">Batata Palha 400g</p><p class="text-[10px] font-black text-red-600 uppercase tracking-tighter mt-1 leading-none">Faturamento</p></div>
                            <span class="text-xl font-black text-red-600 tracking-tighter">-16,7%</span>
                        </div>
                        <div class="p-4 bg-red-50 rounded-2xl border border-red-100 flex justify-between items-center group">
                            <div class="leading-none"><p class="font-bold text-slate-800 text-sm tracking-tighter">Milho Queijo 120g</p><p class="text-[10px] font-black text-red-600 uppercase tracking-tighter mt-1 leading-none">Faturamento</p></div>
                            <span class="text-xl font-black text-red-600 tracking-tighter">-23,8%</span>
                        </div>
                        <div class="p-4 bg-red-50 rounded-2xl border border-red-100 flex justify-between items-center group">
                            <div class="leading-none"><p class="font-bold text-slate-800 text-sm tracking-tighter">Milho Cebola 120g</p><p class="text-[10px] font-black text-red-600 uppercase tracking-tighter mt-1 leading-none">Faturamento</p></div>
                            <span class="text-xl font-black text-red-600 tracking-tighter">-25,4%</span>
                        </div>
                    </div>
                </div>

                <!-- REDES EM QUEDA (DADOS EXATOS) -->
                <div class="section-card p-8 border-t-[10px] border-slate-800">
                    <h4 class="font-black text-slate-800 mb-8 flex items-center uppercase text-[10px] tracking-[0.2em] leading-none">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 20 20"><path d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 000 2h6a1 1 0 100-2H7z"></path></svg>
                        REDES EM QUEDA
                    </h4>
                    <div class="bg-slate-900 text-white p-6 rounded-[2.5rem] mb-6 shadow-xl border border-white/5">
                        <div class="text-brand-orange font-black text-xs mb-6 italic tracking-widest uppercase text-center border-b border-white/10 pb-3 leading-none">Mapeamento Crítico</div>
                        
                        <div class="space-y-4 max-h-[350px] overflow-y-auto pr-2 custom-scrollbar text-left">
                            <div class="flex justify-between items-center group border-b border-white/5 pb-2">
                                <span class="text-[11px] font-bold text-slate-300">GRUPO LANZ</span>
                                <span class="text-red-500 font-black text-[12px] tracking-tighter">- 26,8%</span>
                            </div>
                            <div class="flex flex-col group border-b border-white/5 pb-2">
                                <div class="flex justify-between items-center">
                                    <span class="text-[11px] font-bold text-white uppercase tracking-tighter italic">MONACO</span>
                                    <span class="text-red-500 font-black text-[12px] tracking-tighter">- 11,5%</span>
                                </div>
                                <div class="mt-2 space-y-1">
                                    <span class="block text-red-400 font-black text-[9px] uppercase tracking-widest leading-none italic tracking-tighter">• Contrato encerrado (Dez/25)</span>
                                    <span class="block text-slate-400 font-bold text-[9px] uppercase leading-none italic tracking-tighter">• Peso faturamento: 8,06%</span>
                                </div>
                            </div>
                            <div class="flex justify-between items-center group border-b border-white/5 pb-2">
                                <span class="text-[11px] font-bold text-slate-300 uppercase leading-none">SUPER BARATO</span>
                                <span class="text-red-400 font-black text-[12px] tracking-tighter">- 10,2%</span>
                            </div>
                            <div class="flex justify-between items-center group border-b border-white/5 pb-2">
                                <span class="text-[11px] font-bold text-slate-300 uppercase leading-none">NUNES</span>
                                <span class="text-red-400 font-black text-[12px] tracking-tighter">- 8,1%</span>
                            </div>
                            <div class="flex justify-between items-center group border-b border-white/5 pb-2">
                                <span class="text-[11px] font-bold text-slate-300 uppercase leading-none">ACERTE</span>
                                <span class="text-red-400 font-black text-[12px] tracking-tighter">- 3,7%</span>
                            </div>
                            <div class="flex justify-between items-center group">
                                <span class="text-[11px] font-bold text-slate-300 uppercase leading-none">MULLER</span>
                                <span class="text-orange-400 font-black text-[12px] tracking-tighter">2,2%</span>
                            </div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-500 italic px-2 text-center leading-snug">Auditoria imediata nas razões de saída e proposta comercial de retomada agressiva.</p>
                </div>

                <!-- Rotas em Alerta -->
                <div class="section-card p-8 border-t-[10px] border-brand-orange text-left leading-none">
                    <h4 class="font-black text-orange-600 mb-8 flex items-center uppercase text-[10px] tracking-[0.2em] leading-none">
                        <svg class="w-5 h-5 mr-2" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M12 1.586l-4.586 4.586L4 2.172 2.172 4 5.586 7.414 1.172 11.828 4 14.656l4.414-4.414 4.414 4.414 2.828-2.828-4.414-4.414L16 3.172 12 1.586z" clip-rule="evenodd"></path></svg>
                        Sinais Mistos por Rota
                    </h4>
                    <div class="space-y-6 text-left leading-none">
                        <div class="flex items-start space-x-4 p-4 bg-orange-50/30 rounded-2xl border border-orange-100/50">
                            <span class="w-3 h-3 bg-brand-orange rounded-full mt-1 flex-shrink-0 animate-pulse"></span>
                            <p class="text-xs text-slate-700 leading-relaxed text-left leading-snug"><strong>Grupo 01:</strong> Rotas 13 e 06 operando com volume físico negativo em relação ao ano anterior.</p>
                        </div>
                        <div class="flex items-start space-x-4 p-4 bg-orange-50/30 rounded-2xl border border-orange-100/50">
                            <span class="w-3 h-3 bg-brand-orange rounded-full mt-1 flex-shrink-0"></span>
                            <p class="text-xs text-slate-700 leading-relaxed text-left leading-snug"><strong>Rota 14:</strong> Queda crítica na positivação e perda severa de base ativa.</p>
                        </div>
                        <div class="flex items-start space-x-4 p-4 bg-orange-50/30 rounded-2xl border border-orange-100/50">
                            <span class="w-3 h-3 bg-brand-orange rounded-full mt-1 flex-shrink-0"></span>
                            <p class="text-xs text-slate-700 leading-relaxed text-left leading-snug font-medium italic"><strong>Grupo 02:</strong> Perda de volume mascarada por sucessivos ajustes de ticket médio.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 6. Plano de Intervenção -->
    <section id="estrategia" class="py-24 bg-brand-gradient text-white text-center md:text-left shadow-inner border-0">
        <div class="max-w-7xl mx-auto px-4">
            <h2 class="text-4xl font-black mb-16 text-center tracking-tight text-white uppercase tracking-widest leading-none">Plano Estratégico 2026</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white p-10 rounded-[2.5rem] shadow-2xl flex flex-col hover:scale-105 transition duration-500">
                    <span class="w-12 h-12 bg-brand-red text-white flex items-center justify-center rounded-2xl font-black mb-8 shadow-xl mx-auto md:mx-0 uppercase">A</span>
                    <h4 class="text-slate-900 font-black mb-6 uppercase text-[10px] tracking-widest leading-none text-center md:text-left">Blindar Motores</h4>
                    <p class="text-slate-600 text-sm flex-grow leading-relaxed text-center md:text-left leading-snug">Política de Ruptura Zero nos SKUs Motores. Garantir stock absoluto onde o volume é garantido.</p>
                    <div class="mt-8 pt-4 border-t border-slate-100 text-[10px] text-slate-400 font-black uppercase tracking-widest text-center uppercase tracking-widest text-center md:text-left">Pão Alho / Massas</div>
                </div>
                <div class="bg-white p-10 rounded-[2.5rem] shadow-2xl flex flex-col hover:scale-105 transition duration-500">
                    <span class="w-12 h-12 bg-brand-orange text-white flex items-center justify-center rounded-2xl font-black mb-8 shadow-xl mx-auto md:mx-0">B</span>
                    <h4 class="text-slate-900 font-black mb-6 uppercase text-[10px] tracking-widest leading-none text-center md:text-left">Acção de Giro</h4>
                    <p class="text-slate-600 text-sm flex-grow leading-relaxed text-center md:text-left leading-snug">Ciclo intensivo de 30 dias para reativar Batata Palha e Salgadões. Foco em pricing estratégico.</p>
                    <div class="mt-8 pt-4 border-t border-slate-100 text-[10px] text-slate-400 font-black uppercase tracking-widest text-center md:text-left uppercase">Recuperação SKUs</div>
                </div>
                <div class="bg-white p-10 rounded-[2.5rem] shadow-2xl flex flex-col hover:scale-105 transition duration-500">
                    <span class="w-12 h-12 bg-brand-red text-white flex items-center justify-center rounded-2xl font-black mb-8 shadow-xl mx-auto md:mx-0 text-center md:text-left leading-none">C</span>
                    <h4 class="text-slate-900 font-black mb-6 uppercase text-[10px] tracking-widest leading-none text-center md:text-left">Auditoria Rede</h4>
                    <p class="text-slate-600 text-sm flex-grow leading-relaxed text-center md:text-left leading-snug font-medium italic">Auditoria presencial nos pontos com queda crítica (Grupo Lanz e Monaco).</p>
                    <div class="mt-8 pt-4 border-t border-slate-100 text-[10px] text-slate-400 font-black uppercase tracking-widest text-center md:text-left uppercase">Meta 60 Dias</div>
                </div>
                <div class="bg-white p-10 rounded-[2.5rem] shadow-2xl flex flex-col hover:scale-105 transition duration-500 text-center md:text-left">
                    <span class="w-12 h-12 bg-brand-orange text-white flex items-center justify-center rounded-2xl font-black mb-8 shadow-xl mx-auto md:mx-0 text-center md:text-left">D</span>
                    <h4 class="text-slate-900 font-black mb-6 uppercase text-[10px] tracking-widest leading-none text-center md:text-left text-left leading-none">Gestão Rotas</h4>
                    <p class="text-slate-600 text-sm flex-grow leading-relaxed text-center md:text-left leading-snug">Intervenção tática nas rotas críticas (13, 06, 14). Ativar capilaridade e frequência.</p>
                    <div class="mt-8 pt-4 border-t border-slate-100 text-[10px] text-slate-400 font-black uppercase tracking-widest text-center md:text-left uppercase">Gestão Direta</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-24 bg-white border-t border-slate-100 text-center">
        <div class="max-w-4xl mx-auto px-4 text-center">
            <h2 class="text-4xl font-black text-slate-900 italic mb-12 tracking-tight leading-snug text-center">
                "2026 exige blindar os pilares de volume e <br>estancar as quedas silenciosas que consomem a margem."
            </h2>
            <div class="flex justify-center space-x-4 mb-10 text-center">
                <div class="h-2 w-24 bg-brand-red rounded-full shadow-sm"></div>
                <div class="h-2 w-12 bg-brand-orange rounded-full shadow-sm"></div>
                <div class="h-2 w-6 bg-slate-200 rounded-full shadow-sm"></div>
            </div>
            <p class="text-slate-400 text-[10px] font-black uppercase tracking-[0.6em] text-center italic tracking-widest leading-none uppercase">Açoriana & DataVisionX • Janeiro 2026</p>
        </div>
    </footer>

</body>
</html>
