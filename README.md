<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visual & AI & Brand Designer Portfolio</title>
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;700;800&display=swap');
        
        :root {
            --bg-dark: #0A0A0C;
            --card-dark: #121215;
            --border-dark: #222226;
        }

        body {
            background-color: var(--bg-dark);
            color: #E4E4E7;
            font-family: 'Plus Jakarta Sans', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            overflow-x: hidden;
            scroll-behavior: smooth;
        }

        /* 细腻的定制滚动条 */
        ::-webkit-scrollbar {
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #0A0A0C;
        }
        ::-webkit-scrollbar-thumb {
            background: #222226;
            border-radius: 3px;
        }
        ::-webkit-scrollbar-thumb:hover {
            background: #4F46E5;
        }

        /* 严格控制 1700px 核心版心 */
        .max-w-custom {
            max-width: 1700px;
        }
    </style>
</head>
<body class="selection:bg-indigo-600 selection:text-white">

    <nav class="fixed top-0 left-0 w-full z-50 bg-[#0A0A0C]/60 backdrop-blur-md border-b border-[#222226]">
        <div class="max-w-custom mx-auto px-6 md:px-12 lg:px-16 h-20 flex items-center justify-between">
            <div class="text-xl font-bold tracking-[0.2em] bg-gradient-to-r from-white to-zinc-400 bg-clip-text text-transparent">
                DESIGNER.AI
            </div>
            <div class="hidden md:flex items-center space-x-12 text-xs uppercase tracking-[0.2em] text-zinc-400">
                <a href="#hero" class="hover:text-white transition-colors">首页</a>
                <a href="#about" class="hover:text-white transition-colors">经历</a>
                <a href="#projects" class="hover:text-white transition-colors">作品</a>
                <a href="#advantages" class="hover:text-white transition-colors">优势</a>
                <a href="#contact" class="px-5 py-2 bg-white text-black font-semibold hover:bg-indigo-600 hover:text-white transition-all rounded-none">
                    联系我
                </a>
            </div>
        </div>
    </nav>

    <section id="hero" class="relative h-screen w-full flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-transparent to-[#0A0A0C] z-10"></div>
        
        <video autoPlay loop muted playsInline class="absolute inset-0 w-full h-full object-cover opacity-25 mix-blend-screen pointer-events-none">
            <source src="https://assets.mixkit.co/videos/preview/mixkit-abstract-laser-lights-background-41764-large.mp4" type="video/mp4">
        </video>

        <div class="absolute inset-0 bg-[linear-gradient(to_right,#1f1f23_1px,transparent_1px),linear-gradient(to_bottom,#1f1f23_1px,transparent_1px)] bg-[size:5rem_5rem] opacity-30 [mask-image:radial-gradient(ellipse_60%_50%_at_50%_40%,#000_70%,transparent_100%)]"></div>

        <div class="relative z-20 max-w-custom w-full px-6 md:px-12 lg:px-16 text-left">
            <p class="text-xs md:text-sm tracking-[0.4em] text-indigo-400 uppercase mb-6 font-semibold flex items-center gap-2 animate-pulse">
                <span class="w-1.5 h-1.5 bg-indigo-400 rounded-full"></span> VISUAL / AI / BRAND DESIGNER PORTFOLIO
            </p>
            <h1 class="text-5xl md:text-8xl lg:text-9xl font-extrabold tracking-tight leading-none mb-10 text-white select-none">
                SHAPING THE <br />
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-zinc-100 via-zinc-400 to-zinc-700">
                    AI VISUAL ERA.
                </span>
            </h1>
            <p class="text-zinc-400 text-base md:text-xl max-w-3xl font-light leading-relaxed mb-14">
                打破传统设计边界，融合前沿 AI 算法重构创意工作流。深度探索 Midjourney、Stable Diffusion 在品牌与视觉管线中的精准商业定制，构建克制、高级且极具未来感的数字美学。
            </p>
            <a href="#contact" class="inline-flex items-center space-x-3 group text-xs tracking-[0.2em] border-b border-white pb-2 hover:text-indigo-400 hover:border-indigo-400 transition-all font-medium">
                <span>START A PROJECT / 发起合作</span>
                <i data-lucide="arrow-up-right" class="w-4 h-4 transform group-hover:translate-x-1 group-hover:-translate-y-1 transition-transform"></i>
            </a>
        </div>
    </section>

    <main class="max-w-custom mx-auto px-6 md:px-12 lg:px-16 space-y-36 md:space-y-56 py-20">
        
        <section id="about" class="grid grid-cols-1 lg:grid-cols-12 gap-16 items-center scroll-mt-28">
            <div class="lg:col-span-5 relative group overflow-hidden bg-[#121215] border border-[#222226] aspect-[4/5]">
                <img 
                    src="https://images.unsplash.com/photo-1618005182384-a83a8bd57fbe?q=80&w=2564&auto=format&fit=crop" 
                    alt="Profile Art" 
                    class="w-full h-full object-cover filter grayscale contrast-125 opacity-60 group-hover:scale-105 group-hover:opacity-80 transition-all duration-700 ease-out"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-[#0A0A0C] via-transparent to-transparent"></div>
            </div>

            <div class="lg:col-span-7 space-y-10">
                <div class="space-y-4">
                    <span class="text-xs uppercase tracking-[0.3em] text-indigo-400 font-mono font-bold">[ 01 / PROFILE ]</span>
                    <h2 class="text-3xl md:text-5xl font-bold text-white tracking-tight">探索纯粹美学与智能算法的交汇点</h2>
                </div>
                
                <p class="text-zinc-400 text-base md:text-lg leading-relaxed font-light">
                    作为一名深耕行业多年的视觉、AI 与品牌跨界设计师。我拒绝流于平庸的模板式设计，擅长利用尖端 AI 技术重构传统创意管线。曾在多家知名创意厂牌与硬科技独角兽企业担任视觉核心负责人，帮助企业从 0 到 1 沉淀高级、精细、过目不忘的跨媒介视觉资产。
                </p>

                <div class="grid grid-cols-3 gap-6 pt-10 border-t border-[#222226]">
                    <div>
                        <div class="text-2xl md:text-4xl font-mono font-bold text-white mb-2">40+</div>
                        <div class="text-[10px] md:text-xs uppercase tracking-wider text-zinc-500 font-medium">商业项目交付</div>
                    </div>
                    <div>
                        <div class="text-2xl md:text-4xl font-mono font-bold text-white mb-2">2,500+</div>
                        <div class="text-[10px] md:text-xs uppercase tracking-wider text-zinc-500 font-medium">AI 工业流时数</div>
                    </div>
                    <div>
                        <div class="text-2xl md:text-4xl font-mono font-bold text-white mb-2">08</div>
                        <div class="text-[10px] md:text-xs uppercase tracking-wider text-zinc-500 font-medium">行业顶尖奖项</div>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects" class="space-y-20 scroll-mt-28">
            <div class="flex flex-col md:flex-row md:items-end justify-between gap-6">
                <div class="space-y-4">
                    <span class="text-xs uppercase tracking-[0.3em] text-indigo-400 font-mono font-bold">[ 02 / SELECTED WORKS ]</span>
                    <h2 class="text-3xl md:text-5xl font-bold text-white tracking-tight">用严谨商业逻辑包裹的视觉艺术</h2>
                </div>
                <p class="text-zinc-500 max-w-sm text-sm font-light leading-relaxed">
                    精选代表作：展示如何运用精确的现代栅格系统、多维材质探索与领先的生成式设计为头部品牌强势赋能。
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div class="group cursor-pointer space-y-6">
                    <div class="relative overflow-hidden bg-[#121215] border border-[#222226] aspect-[16/10]">
                        <img 
                            src="https://images.unsplash.com/photo-1634017839464-5c339ebe3cb4?q=80&w=2564&auto=format&fit=crop" 
                            alt="Project One" 
                            class="w-full h-full object-cover filter brightness-[0.85] contrast-105 group-hover:scale-[1.02] group-hover:brightness-100 transition-all duration-700 ease-out"
                        />
                        <div class="absolute top-6 right-6 p-3.5 bg-[#0A0A0C]/80 backdrop-blur-md opacity-0 group-hover:opacity-100 transition-all duration-300 border border-[#222226]">
                            <i data-lucide="arrow-up-right" class="w-5 h-5 text-white"></i>
                        </div>
                    </div>
                    <div class="flex justify-between items-start pt-2">
                        <div>
                            <h3 class="text-xl font-medium text-white group-hover:text-indigo-400 transition-colors">Cybernetic Brand Identity 2026</h3>
                            <p class="text-xs tracking-widest text-zinc-500 mt-2 font-mono uppercase">Brand Strategy / AI Generation</p>
                        </div>
                    </div>
                </div>

                <div class="group cursor-pointer space-y-6">
                    <div class="relative overflow-hidden bg-[#121215] border border-[#222226] aspect-[16/10]">
                        <img 
                            src="https://images.unsplash.com/photo-1614741118887-7a4ee193a5fa?q=80&w=2564&auto=format&fit=crop" 
                            alt="Project Two" 
                            class="w-full h-full object-cover filter brightness-[0.85] contrast-105 group-hover:scale-[1.02] group-hover:brightness-100 transition-all duration-700 ease-out"
                        />
                        <div class="absolute top-6 right-6 p-3.5 bg-[#0A0A0C]/80 backdrop-blur-md opacity-0 group-hover:opacity-100 transition-all duration-300 border border-[#222226]">
                            <i data-lucide="arrow-up-right" class="w-5 h-5 text-white"></i>
                        </div>
                    </div>
                    <div class="flex justify-between items-start pt-2">
                        <div>
                            <h3 class="text-xl font-medium text-white group-hover:text-indigo-400 transition-colors">Neo-Minimalism UI Ecosystem</h3>
                            <p class="text-xs tracking-widest text-zinc-500 mt-2 font-mono uppercase">Visual System / Digital Design</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="advantages" class="space-y-20 scroll-mt-28">
            <div class="space-y-4">
                <span class="text-xs uppercase tracking-[0.3em] text-indigo-400 font-mono font-bold">[ 03 / ADVANTAGES ]</span>
                <h2 class="text-3xl md:text-5xl font-bold text-white tracking-tight">核心行业优势竞争壁垒</h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="p-10 bg-[#121215]/40 border border-[#222226] hover:border-zinc-700 transition-all duration-500 flex flex-col justify-between group">
                    <div class="space-y-6">
                        <div class="p-3.5 w-fit bg-[#0A0A0C] border border-[#222226] text-indigo-400 group-hover:text-white group-hover:bg-indigo-600 transition-all">
                            <i data-lucide="cpu"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-white tracking-wide">AI 工业级重构</h3>
                        <p class="text-zinc-400 text-sm leading-relaxed font-light">
                            熟练掌握高阶 ControlNet 精准控图、LoRA 模型微调及文生图全链路。不仅是做创意图，而是将 AI 无缝内嵌至商业量产与策划案落地，提升百倍创意能效。
                        </p>
                    </div>
                    <div class="text-[10px] font-mono text-zinc-600 pt-10">/ 01_CREATIVE_AI</div>
                </div>

                <div class="p-10 bg-[#121215]/40 border border-[#222226] hover:border-zinc-700 transition-all duration-500 flex flex-col justify-between group">
                    <div class="space-y-6">
                        <div class="p-3.5 w-fit bg-[#0A0A0C] border border-[#222226] text-indigo-400 group-hover:text-white group-hover:bg-indigo-600 transition-all">
                            <i data-lucide="layers"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-white tracking-wide">顶尖宏观品牌思维</h3>
                        <p class="text-zinc-400 text-sm leading-relaxed font-light">
                            绝不流于单纯的视觉包装。从品牌定位、用户体感、竞争差异化出发，推导整套高度系统化、具备跨媒介延展生命力的视觉识别指南与资产。
                        </p>
                    </div>
                    <div class="text-[10px] font-mono text-zinc-600 pt-10">/ 02_BRAND_STRATEGY</div>
                </div>

                <div class="p-10 bg-[#121215]/40 border border-[#222226] hover:border-zinc-700 transition-all duration-500 flex flex-col justify-between group">
                    <div class="space-y-6">
                        <div class="p-3.5 w-fit bg-[#0A0A0C] border border-[#222226] text-indigo-400 group-hover:text-white group-hover:bg-indigo-600 transition-all">
                            <i data-lucide="framer"></i>
                        </div>
                        <h3 class="text-xl font-semibold text-white tracking-wide">全链路极致执行</h3>
                        <p class="text-zinc-400 text-sm leading-relaxed font-light">
                            兼备三维质感表现、高级动态视觉以及 C 端数字化体验设计能力。以像素级苛刻眼光把控落地物料输出，对高级留白、栅格系统和字体排版有偏执追求。
                        </p>
                    </div>
                    <div class="text-[10px] font-mono text-zinc-600 pt-10">/ 03_TOTAL_EXECUTION</div>
                </div>
            </div>
        </section>
        
    </main>

    <section id="contact" class="h-screen w-full bg-gradient-to-t from-zinc-950 to-[#0A0A0C] flex flex-col justify-between pt-36 pb-12 border-t border-[#222226]/60 scroll-mt-20">
        <div class="max-w-custom mx-auto px-6 md:px-12 lg:px-16 w-full flex-1 flex flex-col justify-center items-center text-center">
            <span class="text-xs uppercase tracking-[0.4em] text-indigo-400 mb-6 font-mono font-bold animate-bounce">LET'S BUILD THE FUTURE</span>
            
            <h2 class="text-4xl md:text-7xl font-extrabold tracking-tight text-white max-w-5xl leading-tight mb-14">
                准备好为你的品牌资产 <br />
                注入高级感的科技基因了吗？
            </h2>
            
            <a 
                href="mailto:hello@yourdomain.com" 
                class="px-10 py-5 bg-white text-black font-bold text-base hover:bg-indigo-600 hover:text-white transition-all transform hover:scale-105 duration-300 flex items-center space-x-3 rounded-none shadow-2xl shadow-indigo-500/10"
            >
                <i data-lucide="mail" class="w-5 h-5"></i>
                <span>HELLO@YOURDOMAIN.COM</span>
            </a>
        </div>

        <div class="max-w-custom mx-auto px-6 md:px-12 lg:px-16 w-full border-t border-[#222226] pt-8 flex flex-col md:flex-row justify-between items-center text-xs text-zinc-500 font-mono gap-4">
            <div>© 2026 YOUR NAME. ALL RIGHTS RESERVED.</div>
            <div class="flex space-x-10">
                <a href="#" class="hover:text-white transition-colors tracking-widest">BEHANCE</a>
                <a href="#" class="hover:text-white transition-colors tracking-widest">DRIBBBLE</a>
                <a href="#" class="hover:text-white transition-colors tracking-widest">INSTAGRAM</a>
            </div>
        </div>
    </section>

    <script>
        // 初始化运行图标渲染
        lucide.createIcons();
    </script>
</body>
</html>
