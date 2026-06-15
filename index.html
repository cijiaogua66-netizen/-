```html
<!DOCTYPE html>
<html lang="zh-CN" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>砸死种子蕨那场雨落在二十一世纪后</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入优雅无衬线字体与古风宋体衬线字（国内极速加载） -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+SC:wght@300;400;600&family=Noto+Sans+SC:wght@300;400;500&display=swap" rel="stylesheet">
    
    <style>
        /* 页面基础重置，限制多余的手势缩放卡顿 */
        html, body {
            font-family: 'Noto Sans SC', sans-serif;
            background-color: #050505;
            color: #e5e5e5;
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden; 
        }

        /* 古风及艺术字体 */
        .font-ancient {
            font-family: 'Noto Serif SC', serif;
            font-weight: 300;
        }

        /* 统一长文章阅读器的滚动条 */
        .reader-scroll::-webkit-scrollbar {
            width: 4px;
        }
        .reader-scroll::-webkit-scrollbar-track {
            background: #090909;
        }
        .reader-scroll::-webkit-scrollbar-thumb {
            background: #222;
            border-radius: 2px;
        }

        /* 背景风景图纯净淡入渐变，剔除缩放卡顿源 */
        .bg-slide {
            transition: opacity 1.5s ease-in-out;
            transform: none !important;
        }
        .bg-slide.active {
            opacity: 0.35;
        }

        /* SPA单页视图控制基类 */
        .page-content {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            opacity: 0;
            pointer-events: none;
            transition: opacity 0.5s ease-in-out;
            z-index: 10;
        }
        
        /* 核心逻辑：只有当前页获得 active-page 时，才显示并允许触控指针穿透交互 */
        .page-content.active-page {
            opacity: 1 !important;
            pointer-events: auto !important;
            z-index: 20 !important;
        }
    </style>
</head>
<body class="relative w-full h-full select-none">

    <!-- ==================== 全局顶栏 (带精密防碰撞隐藏控制) ==================== -->
    <header id="mainHeader" class="fixed top-0 left-0 w-full z-50 flex justify-between items-center px-6 py-6 md:px-12 transition-all duration-500">
        <!-- 左上角标志：仅在首页显示，切换至子页面时通过 JS 完全隐去，完美让位给子页面大标题 -->
        <div id="siteLogo" class="pointer-events-auto transition-opacity duration-300">
            <div class="group flex items-center space-x-3 tracking-widest text-xs uppercase opacity-60">
                <svg class="w-4 h-4 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M20.24 12.24a6 6 0 11-8.49-8.49L12 3.5l-.25-.25a6 6 0 01-8.49 8.49L12 20.5l8.24-8.26z" />
                </svg>
                <span class="font-light tracking-widest text-neutral-300">SEED FERN</span>
            </div>
        </div>

        <!-- 右上角目录汉堡菜单键 -->
        <button id="menuBtn" class="pointer-events-auto flex flex-col justify-between w-6 h-4 focus:outline-none group" aria-label="Menu">
            <span id="bar1" class="w-full h-[1.5px] bg-white transition-all duration-300 origin-left"></span>
            <span id="bar2" class="w-full h-[1.5px] bg-white transition-all duration-300"></span>
            <span id="bar3" class="w-full h-[1.5px] bg-white transition-all duration-300 origin-left"></span>
        </button>
    </header>

    <!-- 极简全屏菜单面板 -->
    <nav id="navOverlay" class="fixed inset-0 bg-[#050505] z-40 flex flex-col justify-center items-center opacity-0 pointer-events-none transition-all duration-500">
        <div class="absolute inset-0 bg-gradient-to-b from-neutral-950/20 via-neutral-900/40 to-black/20 pointer-events-none"></div>
        
        <div class="flex flex-col space-y-8 text-center z-10">
            <a href="#" onclick="showPage('home')" class="font-ancient text-xl text-neutral-400 hover:text-white tracking-[0.2em]">首页</a>
            <div class="h-[1px] w-8 bg-neutral-800 mx-auto my-2"></div>
            
            <span class="text-[10px] tracking-widest text-neutral-600 uppercase font-light">项目目录 / PROJECTS</span>
            
            <a href="#" onclick="showPage('ati')" class="font-ancient text-lg text-neutral-400 hover:text-white tracking-[0.15em]">阿嚏寺</a>
            <a href="#" onclick="showPage('novel')" class="font-ancient text-lg text-neutral-400 hover:text-white tracking-[0.15em]">小说</a>
            <a href="#" onclick="showPage('fish')" class="font-ancient text-lg text-neutral-400 hover:text-white tracking-[0.15em]">鱼儿醒来后说他做了一个梦</a>
            <a href="#" onclick="showPage('mystery')" class="font-ancient text-lg text-neutral-400 hover:text-white tracking-[0.15em]">？？？</a>
            <a href="#" onclick="showPage('world')" class="font-ancient text-lg text-neutral-400 hover:text-white tracking-[0.15em]">世界</a>
        </div>
        
        <div class="absolute bottom-8 text-[10px] text-neutral-600 tracking-widest uppercase pointer-events-none">
            © 2026 刺角瓜. All Rights Reserved.
        </div>
    </nav>

    <!-- ==================== 主体单页视图区 ==================== -->
    <main class="relative w-full h-full">

        <!-- ==================== 1. 首页 (HOME) ==================== -->
        <section id="page-home" class="page-content active-page flex flex-col justify-center items-center px-4">
            <!-- 全屏暗调风景大图轮播背景 (纯净无缩放) -->
            <div class="absolute inset-0 overflow-hidden -z-10 bg-black">
                <div class="absolute inset-0 bg-gradient-to-b from-[#050505]/40 via-transparent to-[#050505] z-10"></div>
                
                <!-- 预放多张引人注目的风景摄影作品占位，在此完全为您渲染 -->
                <div class="bg-slide absolute inset-0 bg-cover bg-center active" style="background-image: url('https://images.unsplash.com/photo-1500485035595-cbe6f645feb1?auto=format&fit=crop&q=80&w=1600');"></div>
                <div class="bg-slide absolute inset-0 bg-cover bg-center opacity-0" style="background-image: url('https://images.unsplash.com/photo-1475924156734-496f6cac6ec1?auto=format&fit=crop&q=80&w=1600');"></div>
                <div class="bg-slide absolute inset-0 bg-cover bg-center opacity-0" style="background-image: url('https://images.unsplash.com/photo-1518098268026-4e43a1a009de?auto=format&fit=crop&q=80&w=1600');"></div>
            </div>

            <!-- 完美的宋体古风大字“桥”，下方配有小号的“—— 刺角瓜” -->
            <div class="text-center flex flex-col items-center">
                <!-- “桥”字手工雕刻视觉 SVG 标志 -->
                <div class="mb-4 cursor-default">
                    <svg class="w-36 h-36 text-neutral-200 opacity-90 drop-shadow-[0_0_15px_rgba(255,255,255,0.15)]" viewBox="0 0 100 100" fill="currentColor">
                        <g transform="translate(10, 10)">
                            <path d="M 25,15 C 26,20 23,55 23,75" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" fill="none" />
                            <path d="M 10,35 C 20,34 28,31 40,30" stroke="currentColor" stroke-width="2" stroke-linecap="round" fill="none" />
                            <path d="M 23,35 C 18,45 12,58 5,68" stroke="currentColor" stroke-width="2" stroke-linecap="round" fill="none" />
                            <path d="M 23,38 C 28,48 35,58 42,65" stroke="currentColor" stroke-width="2" stroke-linecap="round" fill="none" />
                            <path d="M 68,12 C 60,16 52,22 46,28" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" fill="none" />
                            <path d="M 45,30 C 58,28 68,26 80,24" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" fill="none" />
                            <path d="M 40,46 C 55,44 65,42 82,41" stroke="currentColor" stroke-width="2" stroke-linecap="round" fill="none" />
                            <path d="M 62,28 C 63,42 61,60 55,78" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" fill="none" />
                            <path d="M 43,62 C 48,58 52,56 58,56" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" fill="none" />
                            <path d="M 66,54 C 74,54 80,58 85,63" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" fill="none" />
                        </g>
                    </svg>
                </div>
                <p class="text-xs text-neutral-400 font-ancient tracking-[0.4em] translate-x-[0.2em]">—— 刺角瓜</p>
            </div>

            <!-- 底部的细线指向 EXPLORE 动态指示 -->
            <div class="absolute bottom-10 left-1/2 -translate-x-1/2 flex flex-col items-center opacity-40 hover:opacity-100 transition-opacity duration-300 cursor-pointer" onclick="openMenu()">
                <span class="text-[9px] tracking-[0.3em] uppercase mb-1">Explore</span>
                <span class="w-[1px] h-8 bg-neutral-400"></span>
            </div>
        </section>

        <!-- ==================== 2. 阿嚏寺 (ACHOO TEMPLE) ==================== -->
        <section id="page-ati" class="page-content flex flex-col justify-start px-6 md:px-24 max-w-5xl mx-auto overflow-y-auto pt-24 pb-12">
            <!-- 直接由子页面大标题充当头部，防止了和主页Logo的叠放 -->
            <h2 class="font-ancient text-3xl md:text-5xl text-neutral-150 mb-4 tracking-widest border-l-2 border-neutral-700 pl-4 mt-6">阿嚏寺</h2>
            <p class="text-neutral-500 text-[10px] tracking-wider uppercase mb-8">ACHOO TEMPLE / PROJECT I</p>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-start">
                <div class="space-y-6 text-sm md:text-base text-neutral-300 leading-relaxed font-light">
                    <p>“那场雨下了太久，久到我们忘记了泥土最开始的颜色。”</p>
                    <p>在阿嚏寺，声音是唯一的建筑材料。每一次呼吸、每一次喷嚏，都会在虚无的梁柱间引起回响。种子蕨的化石藏在功德箱的底层，偶尔在深夜发出沙沙的叹息。</p>
                </div>
                <div class="relative group overflow-hidden border border-neutral-900 rounded-sm">
                    <img class="w-full h-64 object-cover filter grayscale opacity-40" src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?auto=format&fit=crop&q=80&w=800" alt="阿嚏寺占位">
                </div>
            </div>
        </section>

        <!-- ==================== 3. 小说：2D 十字路口极简交互 (NOVEL) ==================== -->
        <section id="page-novel" class="page-content flex flex-col justify-center items-center bg-[#020202] overflow-hidden">
            <div class="relative w-full h-full flex flex-col justify-center items-center">
                
                <!-- 顶部大标题 -->
                <div class="absolute top-20 text-center z-20 pointer-events-none">
                    <h2 class="font-ancient text-lg tracking-[0.3em] text-neutral-300">十字路口</h2>
                    <p class="text-[9.5px] tracking-[0.2em] text-neutral-500 mt-1 uppercase">点击路牌选择篇章 · 寻找泥沙中的记忆</p>
                </div>

                <!-- 交互 Canvas 绘图区域 -->
                <canvas id="roadCanvas" class="absolute inset-0 w-full h-full block z-10 cursor-pointer"></canvas>

                <!-- 极简质感悬浮路牌 -->
                <div class="absolute right-[8%] bottom-[20%] md:right-[15%] md:bottom-[30%] z-20">
                    <button onclick="openNumberSelector()" class="group flex flex-col items-center focus:outline-none transition-all duration-300 hover:scale-105 pointer-events-auto">
                        <div class="bg-neutral-950/90 border border-neutral-800 px-5 py-2 rounded-sm shadow-2xl flex flex-col items-center space-y-1">
                            <span class="font-ancient text-xs tracking-widest text-neutral-400 group-hover:text-white transition-colors">小说篇章</span>
                            <span class="text-[8px] tracking-[0.1em] text-neutral-600 font-mono">1 - 30 NOVELS</span>
                        </div>
                        <div class="w-[2px] h-12 bg-neutral-900"></div>
                        <div class="text-[9px] text-neutral-500 tracking-wider bg-black/80 px-2 py-0.5 rounded border border-neutral-900">选择</div>
                    </button>
                </div>
            </div>

            <!-- 数字选择栏 (侧边推入) -->
            <div id="numberSelector" class="fixed inset-y-0 right-0 w-80 bg-[#070707] border-l border-neutral-900 z-50 transform translate-x-full transition-transform duration-500 flex flex-col justify-between p-6 pt-24">
                <div>
                    <!-- 核心修改：关闭按钮向左下偏移，绝对不和顶栏发生重叠遮挡 -->
                    <button onclick="closeNumberSelector()" class="absolute top-6 left-6 text-neutral-500 hover:text-white text-xs tracking-widest uppercase focus:outline-none flex items-center space-x-2">
                        <svg class="w-3.5 h-3.5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12"/></svg>
                        <span>返回路口</span>
                    </button>
                    <div class="grid grid-cols-5 gap-3 mt-6 overflow-y-auto max-h-[70vh] pr-1" id="numbersGrid">
                        <!-- 动态载入数字 -->
                    </div>
                </div>
                <div class="text-[9px] text-neutral-600 tracking-widest text-center mt-4">
                    SEED FERN · 刺角瓜 撰写
                </div>
            </div>

            <!-- 小说阅读器 Overlay (全屏覆盖最高层，自带独立返回键) -->
            <div id="novelReader" class="fixed inset-0 bg-neutral-950 z-[60] opacity-0 pointer-events-none transition-opacity duration-500 flex flex-col justify-between overflow-hidden">
                
                <!-- 固定顶栏 (自带返回，彻底防止按钮撞车) -->
                <div class="w-full flex justify-between items-center px-6 py-5 md:px-12 border-b border-neutral-900 bg-neutral-950">
                    <button onclick="closeReader()" class="flex items-center space-x-2 text-xs tracking-widest text-neutral-400 hover:text-white transition-all duration-300 focus:outline-none">
                        <svg class="w-4 h-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 19l-7-7m0 0l7-7m-7 7h18"/>
                        </svg>
                        <span>返回十字路口</span>
                    </button>
                    <span id="readerChapterNum" class="text-[10px] tracking-widest text-neutral-500 font-mono">CHAPTER 00</span>
                </div>

                <!-- 正文内容区（顺滑滚动） -->
                <div class="flex-grow overflow-y-auto reader-scroll px-6 py-12 md:py-16">
                    <div class="max-w-2xl mx-auto w-full select-text pb-24">
                        <h3 id="readerTitle" class="font-ancient text-2xl md:text-3xl tracking-widest text-neutral-100 mb-8 border-b border-neutral-900 pb-4 leading-normal"></h3>
                        <div id="readerContent" class="text-neutral-300 font-light text-sm md:text-base leading-relaxed space-y-6 tracking-wide">
                            <!-- 文本 -->
                        </div>
                    </div>
                </div>

                <div class="w-full text-[9px] text-neutral-600 tracking-widest text-center py-4 bg-neutral-950 border-t border-neutral-900">
                    砸死种子蕨那场雨落在二十一世纪后 © 刺角瓜
                </div>
            </div>
        </section>

        <!-- ==================== 4. 梦 (THE FISH'S DREAM) ==================== -->
        <section id="page-fish" class="page-content flex flex-col justify-start px-6 md:px-24 max-w-5xl mx-auto overflow-y-auto pt-24 pb-12">
            <h2 class="font-ancient text-2xl md:text-4xl text-neutral-150 mb-4 tracking-widest border-l-2 border-neutral-700 pl-4 mt-6">鱼儿醒来后说他做了一个梦</h2>
            <p class="text-neutral-500 text-[10px] tracking-wider uppercase mb-8">THE FISH'S DREAM / PROJECT III</p>
            
            <div class="max-w-2xl space-y-6 text-sm md:text-base text-neutral-300 leading-relaxed font-light">
                <blockquote class="border-l border-neutral-600 pl-4 italic text-neutral-400">
                    “梦里没有水，只有无边无际的荒原。荒原上长满了高大如烟囱的种子蕨。它们不呼吸，只是在等待一场雨将它们彻底埋进地底。”
                </blockquote>
                <div class="relative overflow-hidden border border-neutral-900 rounded-sm">
                    <img class="w-full h-48 object-cover filter grayscale opacity-40" src="https://images.unsplash.com/photo-1544551763-46a013bb70d5?auto=format&fit=crop&q=80&w=800" alt="海洋占位">
                </div>
            </div>
        </section>

        <!-- ==================== 5. ？？？ (MYSTERY) ==================== -->
        <section id="page-mystery" class="page-content flex flex-col justify-center items-center px-6 text-center">
            <div class="max-w-md space-y-6">
                <h2 class="font-ancient text-5xl text-neutral-400 tracking-widest">？？？</h2>
                <p class="text-xs text-neutral-600 uppercase tracking-widest">SECRET PROJECT / IV</p>
                <div class="h-[1px] w-12 bg-neutral-900 mx-auto"></div>
                <p class="text-sm text-neutral-500 leading-relaxed font-light italic">
                    “尚未被命名的事物，往往承载着最多的可能性。”
                </p>
            </div>
        </section>

        <!-- ==================== 6. 世界 (WORLD) ==================== -->
        <section id="page-world" class="page-content flex flex-col justify-start px-6 md:px-24 max-w-5xl mx-auto overflow-y-auto pt-24 pb-12">
            <h2 class="font-ancient text-3xl md:text-5xl text-neutral-150 mb-6 tracking-widest border-l-2 border-neutral-700 pl-4 mt-6">世界</h2>
            <p class="text-neutral-500 text-[10px] tracking-wider uppercase mb-8">THE WORLD OVERVIEW / PROJECT V</p>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-sm">
                    <span class="text-xs text-neutral-600 font-mono">01 / GEOLOGY</span>
                    <h3 class="font-ancient text-base text-neutral-200 mt-2 mb-3">地质年代</h3>
                    <p class="text-xs text-neutral-400 leading-relaxed font-light">
                        种子蕨繁盛于石炭纪与二叠纪，它们是现代煤炭的重要前身。而这场落入二十一世纪的雨，正在解冻古老的碳层。
                    </p>
                </div>

                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-sm">
                    <span class="text-xs text-neutral-600 font-mono">02 / ECOLOGY</span>
                    <h3 class="font-ancient text-base text-neutral-200 mt-2 mb-3">刺角瓜生态</h3>
                    <p class="text-xs text-neutral-400 leading-relaxed font-light">
                        沙漠中唯一的异类。外表尖锐而荒诞，内部却充满酸甜的汁液，正如在冰冷机械的二十一世纪中苟活的浪漫主义。
                    </p>
                </div>

                <div class="p-6 bg-neutral-950 border border-neutral-900 rounded-sm">
                    <span class="text-xs text-neutral-600 font-mono">03 / ARCHIVE</span>
                    <h3 class="font-ancient text-base text-neutral-200 mt-2 mb-3">二十一世纪档案</h3>
                    <p class="text-xs text-neutral-400 leading-relaxed font-light">
                        收集日常细碎的声音、失效的电子元件、下雨天的水花，以及被我们遗忘的各种微小瞬间。
                    </p>
                </div>
            </div>
        </section>

    </main>

    <!-- 页脚 -->
    <footer class="fixed bottom-0 left-0 w-full z-30 flex justify-between items-center px-6 py-4 md:px-12 pointer-events-none">
        <div class="text-[9px] text-neutral-600 tracking-widest">© 2026 刺角瓜</div>
        <div class="text-[9px] text-neutral-600 tracking-widest hidden md:block">THE RAIN THAT KILLED SEED FERNS FELL IN THE 21ST CENTURY.</div>
    </footer>

    <!-- 16篇完整小说文本数据库 -->
    <script>
        const NOVELS_DATA = {
            1: {
                title: "一．初见",
                content: `<p>夏，午后枯燥，住户蜗居，</p>
                          <p>南怀河口，胡同深处藏着的老筒子楼。</p>
                          <p>四层，不高不低，住着七八户。</p>
                          <p>墙皮脱落，苔藓滋生，水渍像蛇在瓷砖地上，嗅。</p>
                          <p>厕所（水间，浴室，水管子，方便处等叫法共称），在此层正中。</p>
                          <p>楼梯口第一户，门口盆栽不少，添几分绿，门大开着，左右新帖 of 对联红艳，喜气洋洋。</p>
                          <p>一路往里走，经过几扇木门，大多是古铜色，或深黄。偶有铁门几扇，银白闪亮，光下一对视，就晃了眼。</p>
                          <p>门缝上多有插艾草，猜测端午前后，季节也对的上。</p>
                          <p>走到尾头靠着墙那间。门虚掩着，铁门，落了锈。</p>
                          <p>鞋柜木质的，落了霉。抽屉半开，躺着一把伞，桌上还睡着两把。</p>
                          <p>一阵风起了，沙沙作响。</p>
                          <p>一阵清香，横冲直撞。</p>
                          <p>一声笛声，再没动静。</p>
                          <p>时间不被搅动了，只好化掉，在浓稠的暑天，大步流星。</p>
                          <p>一眨眼。时钟走了一刻，稍凉快了些。又安静了些。</p>
                          <p>虚掩的门开了，出来一人，持着盆，去打水，笑盈盈，像发了财。</p>
                          <p>动静飘到另一户，有人小叹一声，客厅窜出一影子，光着脚。</p>
                          <p>也许是绿萝的叶子，也许是春兰的根。</p>
                          <p>总之女孩踏过盆栽，拿着海报纸，往楼中间去。他们俩在水间相遇。</p>
                          <p>男孩叫邱水，似发了财的那位。女孩叫阿木，影子像兔子的那位。</p>
                          <p>“楼下新开了家馄饨铺，去过么？”阿木开口，是试探，手头海报攥紧了点。</p>
                          <p>邱水答：“里头灯光太暗，没得食欲。”</p>
                          <p>又攥的松了些。</p>
                          <p>“我家亮堂，你倒是来嘛”</p>
                          <p>另一人还想答些什么。只是水溢出来，在池里奔走，拧上水龙头，便没了话说。</p>
                          <p>“今天心情不错？难得见你轻松不少。”</p>
                          <p>“其实你笑起来好看些，是我觉得好看些。”阿木瞥了眼邱水。</p>
                          <p>……</p>
                          <p>一阵风起了，叮 铃 哐 啷。</p>
                          <p>一阵躁动，门被关上。</p>
                          <p>一曲笛声，雀跃。</p>
                          <p>午后，至天黑，除了南怀河每晚都有的葫芦丝。偶尔来的推车嘎吱嘎吱，金属架子不稳，总在晃荡。除了艾草门依旧关着，来了只鸟，黄莺。再无动静。</p>
                          <p class="text-xs text-neutral-500 mt-6">——记于1983年的一个夏<br>——笔者：XXX（模糊不清）</p>`
            },
            2: {
                title: "二．《几重楼·祜子案》",
                content: `<p class="font-semibold text-neutral-400">【人物】</p>
                          <p class="text-sm">林景行（青衣/尼姑） · 苏峁（花脸/林工） · 吴棣华（方巾丑/方丈） · 鹬（小生/僧童） · 皮（二花脸/僧童） · 穆（花旦/女僧童） · 胡万财（袍带丑角/县令） · 衙役（随场应役）</p>
                          <div class="h-[1px] bg-neutral-900 my-4"></div>
                          <p class="font-semibold text-neutral-400">第一折  山遇</p>
                          <p><strong>苏峁：</strong> 担斧入山踏翠烟，松涛绕耳水潺潺. 平生不做亏心事，磊落襟怀天地宽。</p>
                          <p><strong>林景行：</strong> 蒲团坐断禅心乱，流水声中起俗缘。贫尼林景行，祜子庙修行。今奉师命，河畔采蔬。</p>
                          <p class="italic text-neutral-500">【失篮科，苏峁拾篮递还，二人对视】</p>
                          <p><strong>苏峁：</strong> 见她娥眉锁愁怨，清如秋水静如莲。僧衣难掩风华面，倒叫我樵夫意马牵。（白） 师父若有难处，尽可对俺言讲！</p>
                          <p><strong>林景行：</strong> 感君一语暖心田，身世飘零实可怜。父母双亡无牵绊，才入空门伴佛前。</p>
                          <p class="font-semibold text-neutral-400 mt-4">第二折 窥秘</p>
                          <p><strong>吴棣华：</strong> 口念弥陀心藏奸，莲台之下暗营钻. 咱家吴棣华，祜子庙方丈。林景行与苏峁私通，正好拿住把柄，逼她顺我！你三人死死盯住苏峁、林景行，他二人何时相见、何处往来，一字一句全给我记牢，不许有误！</p>
                          <p class="font-semibold text-neutral-400 mt-4">第三折 雨</p>
                          <p><strong>苏峁：</strong> 瘴气侵身神魂乱！大雨倾盆暗山川. 只道幽会无人见，却原来暗地有人窥探！心头火起恶念添，今日里叫你赴九泉！【劈斧科，穆身死。苏峁下】</p>
                          <p class="font-semibold text-neutral-400 mt-4">第四折 河</p>
                          <p><strong>林景行：</strong> 恨只恨孽缘牵起祸端. 我与他私相会情投意暖，谁料想杀人身负重罪愆. 入空门坏清规佛心已变，要还俗负罪孽怎对苍天？进退无门柔肠断，不如赴清流一死周全！</p>
                          <p><strong>鹬：</strong> 师父！万万使不得！那是吴棣华的奸计！他对你心怀不轨，命我三人跟踪记下，要拿把柄逼你从他！</p>
                          <p class="font-semibold text-neutral-400 mt-4">第五折 谳</p>
                          <p><strong>胡万财：</strong> 大胆苏峁！你连杀穆、吴棣华，从实招来！</p>
                          <p><strong>苏峁：</strong> 穆是俺所杀，方丈之死，与俺无关！要杀要剐，悉听尊便！</p>
                          <p><strong>林景行：</strong> 大人在上容奴禀，苏峁杀人有隐情。方丈之死非他行，望大人明察断分明！</p>
                          <p class="font-semibold text-neutral-400 mt-4">第六折 终章</p>
                          <p><strong>鹬：</strong> 恨奸贼弑主嫁祸心太险，设下巧计引他入深潭。皮他恨我知情要暗算，我叫他杀官自毙赴黄泉！</p>
                          <p class="italic text-neutral-500">【读遗书毕，哭倒】</p>
                          <p><strong>鹬：</strong> 手捧遗书泪如涌，一字一句刺心胸。胡狗贼昨夜将她污辱控，她清白尽毁赴河东！南怀河水浪千重，多少冤魂在其中。</p>
                          <p class="text-xs text-neutral-500 mt-4">【全剧终。】</p>`
            },
            3: {
                title: "三．梦",
                content: `<p>还是夏，夜。</p>
                          <p>云聚起来，星星躲起来，月亮跑出来。</p>
                          <p>一根线指着月亮，收音机的触角. 音量开的很小，收音机在哼：“夜半三更呦，盼天明。”一曲映山红。</p>
                          <p>阿嬷在天台，吹风，有凳子但她不坐. 阿水在阿嬷身后，在天台的门口，放着苹果盘和收音机的玻璃桌边. 有凳子但他躺地上。</p>
                          <p>“阿水，阿嬷考考你，天空是怎样子的，你记得老师上课讲的吗，比喻句。”</p>
                          <p>“天空是蓝色的。”</p>
                          <p>“这是什么比喻呦. 上课不听老师说话嘛阿水？你想想，还有什么是蓝色的，阿水？”</p>
                          <p>“阿水？”</p>
                          <p>叫阿水的孩子闭上了眼睛，把头扭向一边，撩起了衣服，包住头，用嘴模仿呼噜声. 阿嬷不再说话。</p>
                          <p>“夜半三更哟，盼天明……岭上开遍呦，映山红……”</p>
                          <p>歌声停了，呼噜也停了. 阿水猛的坐起. 伸出手来数一数，收音机还在，天台的门还开着。“阿嬷，你在吗？”无人答应. 阿嬷不见了。</p>
                          <p>阿水站起来，拍拍身上的灰，捡起外套抖了几下，夏夜凉爽，又安静，安静的有些冷，阿水穿上外套。</p>
                          <p>“阿嬷不要开玩笑好不喽，阿水知道你在。”无人答应。</p>
                          <p>他站在阿嬷刚刚站的位置，站好了，笔直的像笋，仰头，深邃的眼球. 水波，眺远的抛物线. 阿水笔直的看天空. 风像方格子桌布，缝缝补补的老头衫. 不多时候，他“睡着”了。</p>
                          <p>一些“无关紧要”的东西出现在阿水脑袋里. 有时飞到宇宙中，被黑洞牵引；有时落到隔壁村里，烟囱上，一缕白，和檐下的腊肉. 一分钟的等待，神明的安排. 阿水在想：天空外面有什么. 比喻是什么，是一个东西像一个东西，还是……</p>
                          <p>白天是亮的，夜晚是黑的. 猫是神秘，入夜后，成了诡异. 年老的猫最诡异。</p>
                          <p>“伸手不见五指。”阿水吞了吞口水. 好像有什么声音，他不敢把目光投向天台栏板一圈漆黑的阴影. 一二三四，收音机还在，苹果盘还在. 还有，阿嬷晾的衣服不见了！</p>
                          <p>月光纺着蓝纱，夜空也是蓝的. 可那是刚刚. 再看，天彻底黑了. 月亮微红，像一颗被水泡白了的，濒死的枣. 伸手不见五指，阿水又想起老师的话，不敢看自己的手。</p>
                          <p>“阿嬷不要你了！！！”<br>“阿嬷不要你了！！！”<br>“阿嬷不要你了！！！”</p>
                          <p>一阵幼小的尖叫划破了风. 一群鸟被惊起，还有一个笨拙的黑影. 一只肥胖的、慈祥的秃鹫，阿水最爱的人. 从晾衣架后面的拐角颤颤巍巍走出来. 一个灵巧的影子，受惊的鹿，窜了出去，迎到了大影子的怀里。</p>
                          <p>“阿嬷——</p>
                          <p class="text-xs text-neutral-500 mt-4">—— 邱水从梦里醒来。</p>`
            },
            4: {
                title: "四．璇玑",
                content: `<p class="font-mono text-xs md:text-sm text-center leading-loose text-neutral-400">
                            入,夜,他,惯,锁,门,此,非<br>
                            窥,私,之,险,窗,帘,柜,厅<br>
                            无,紧,闭,距,离,扣,门,室<br>
                            久,执,需,上,锁,住,皆,正<br>
                            已,仍,间,安,宁,心,然,门<br>
                            居,烦,空,为,亦,扉,幸,凡<br>
                            独,劳,增,免,匣,盒,无,可<br>
                            锁,落,需,皆,物,之,阖,闭
                          </p>
                          <div class="h-[1px] bg-neutral-900 my-6"></div>
                          <p>吴芒平，新安人，新安儿童医院降生，养有一狗. 曾在河口任职神经内科医生. 所在私立医院，生意不景气，草草倒闭卷款跑路，院长下落不明. 急诊部杂草丛生，没了人气。（流浪猫的天堂，跳蚤乐园，南山一中孩子心驰神往的圣殿，探险对象. 玻璃瓶公墓，文艺青年途经此处打卡点，牙模具农田）</p>
                          <p>曾参加“小秘密”俱乐部，活跃组员之一. 收入来源依靠于松溪路至宝塔井路段开网约车专车接送（夜）. 子午巷送外卖（昼）. 有摄影的习惯，常去镇子不远处后山取景，结识僧人老庐，忘年交. 俱乐部时间占比很大，因此工作三天打鱼两天晒网，常手机欠费。</p>
                          <p>曾前往关事厂流水线，剃了长发，洗了纹身（Χρειάζομαι wirklich echt wahr σωτηρία），多在凌晨0：00引吭高歌，如公鸡. 被厂外一农户投诉，不了了之，该农户一个冬季只身前往后山“打猎”，收获鸡仔一只，信纸一团. 此前，吴芒平辞职回乡。</p>
                          <p>曾患有一些疾病，爱吃棒骨和苋菜. 前二者并没有什么关联。</p>
                          <p class="italic text-neutral-400">是否独居（？）是否单身（？）现居何职（？）</p>
                          <p>他有很多小秘密。</p>`
            },
            5: {
                title: "五．被拆开的切分音，作曲家",
                content: `<p class="italic text-neutral-400">淤青，吐沫，嘶嘶，雨。<br>碎镜，灰衫，唰唰，笔。<br>梅迹，红痕，嗖嗖，洗。</p>
                          <p>今夜的镜子，照不出完整的你。</p>
                          <p>喜欢厨艺，南方小乡镇的戈登拉姆齐，湍湍的溪，摘青椒的身影，是你. 爱好和平，鼓捣雪花电视机，想看红旗招展的花枝招展的小人，唾弃工业废品是垃圾！</p>
                          <p>小巷子里人影攒动，流浪拓荒者前仆后继，发现了艺术——沾满盐粒和汽油的胡子，虱子 and 蚂蚁打架的头发丛，漏墨的圆珠笔. 捕捉这一刻，多美丽的动人作品. 按下快门的，是你。</p>
                          <p>爱听都柏林人，短促的哨笛，雀跃的马背后的旅行，下一站日程，没来得及实现. 就定格在甲午月，辛未日，夜里的夜莺，娇俏的使者，客人的歌声里。</p>
                          <p>一个影子，不再重要了. 带着缝衣针和榔头，没有带雨伞，拥着雨. 好心的门扉，绕着支点徐徐打开，光射了出来，是一张洁白的床，柜头显眼的氯丙嗪，一本日记，两本，三本. 榔头落下，这是预警，拿起毛巾，快速窒息，我忘记了什么，你，你忘记了什么。</p>
                          <p>好浪漫的肉，哪里的，脸颊上的. 好痛的雨，哪里的，头皮上的. 你是谁，为什么要害我. 我是谁，为什么在这里. 玩具熊，布谷鸟，时钟玩具，滴嘟滴. 滴，嘟，滴——</p>
                          <p>玫瑰花的葬礼，嘻嘻，夜的秘密. 她醒来了，神灵的记忆，还给你. 坚强的活下去，好吗，活下去。</p>
                          <p>一晚没有盐分的西兰花，清蒸苏打饼干，椒盐牛舌. 没有凶手，只有扭曲了的厨艺. 塑料袋，红白配，鱼腥草，丢下去，小区垃圾箱. 我好疼，要回家，在哪缴费，祜子门诊部？楼底下，垃圾袋，谁的肉啊！！快报警。</p>
                          <p>你看啊，日记，三本……几？是呀，一切都是你. ……你？（我）是你。</p>`
            },
            6: {
                title: "六．松树学院纪事",
                content: `<p>22:24，邱说去一教看看。</p>
                          <p>林说行，先去湖边走走，指不定能碰上蛤蟆. 吴没说话. 抿了口新泡 of 白茶，乐的。“干嘛非得碰上蛤蟆，人可不一定愿意碰上你。”</p>
                          <p>“这时候喝这，睡着睡不着，一会宵禁，你想去还去不了。”风来了，凉. 三人同时打了个寒颤，林把窗子关上了。</p>
                          <p>“好茶还需晚上品。”吴摇头晃脑，拉长嗓子，京剧做派。</p>
                          <p>“明没课，前些日子东湖那出事了，死了两个. 学校最近都忙这事，估计没空管咱.”邱没理吴，冲着林说. 林也没理邱，想着蛤蟆咋子了。</p>
                          <p>“我倒垃圾听别人说的，一个男的，有对象了，还叫小姐. 跑去外头荒郊野地不知道哪找了个破店开房. 开就开吧，还他妈不嫌刺激，录视频. 后边被他对象发现了. 发现就发现吧，男的倒不乐意，要分手. 转头找那小姐去了，后面那小姐发现这女孩是她同行。”邱大笑。</p>
                          <p>吴跟着大笑，咯咯的，像吞了芥末的癞皮狗。“你笑的真他妈难听。”邱更乐了。</p>
                          <p>林没想蛤蟆了，看着他俩，一阵惊悚. 风来了，敲敲窗户. 咚咚咚，三下，邱吴都不笑了. 一个去喝水，一个还念着“好茶还需晚上品”，悠悠的摆弄桌上的芍药花，下午邱给他的。</p>
                          <p>出门前，林扫了扫地. 吴还在唱念做打，和邱打情骂俏，说些骚哄哄的荤话。</p>
                          <p>走吧，邱拉了防吴. 吴呛了一口气，京腔憋到嘴里. 走吧，林放下笤帚，还没从惶恐里出来。</p>
                          <p>“你俩说，人死会去哪. 我阿公上个月没了，啊真叫人心里不美，我老梦他，他说他好着呢。”</p>
                          <p>邱说死了就死了，哪也不去，就是埋到地下. 有些还会把骨灰撒海里，有钱人就是随性，死了还图个标新立异。</p>
                          <p>吴翻个白眼，系个鞋带，看了看桌上的日记，上着锁。“净他妈瞎扯淡，人死了就成魂了，谁想他他去谁那. 魂虽然看不见，但能感觉谁想他，这就是是，是那个什么，量子纠缠。”</p>
                          <p>林呆着了. 邱自讨没趣的去外头了，掩着门. 抽烟。</p>
                          <p>“也不一定其实，也可能真有什么说头，黑白无常啦，阿努比斯啦，阎摩啦，加百列啦，塔纳托斯啦，哈迪斯啦……就是吧，死了也不代表死了，被忘了才是真正死了。”吴又看了眼笔记本，念叨：“To be, or not to be, that is the question.”</p>
                          <p>林还在那呆着. 邱把门推开，猛吸一口，烟从嘴巴鼻子一块冒出来。“有完没完，能不能走？”</p>
                          <p>吴边走边说，把芍药拿出来，碾碎，扔进了湖里. 悄悄的，林看见了. 云是淤青色. 水波潋滟，黢黑的大口，三人没再说话. 这样一直走. 到了一教楼下. 吴打趣，“谁先进去试试水？”</p>`
            },
            7: {
                title: "七．美丽旧世界",
                content: `<div class="space-y-6 text-sm">
                            <p><strong>1.</strong> 影子在月亮下窜动，扫地工人阖家欢乐. 晚班医生踏上出租. 影子拉长，变细，闪动，游离，停下，漫步，出现在很多角落. 窥视，他在快活着。</p>
                            <p><strong>2.</strong> 快活的城市，衰落兴起后，又衰落兴起. 可爱的平安城. 沿城墙走，月亮在游离，疯子在躲着. 稀疏，落寞，酒精，童话，幽灵，鬼和砍头诗。</p>
                            <p><strong>3.</strong> 没有弧度的冬天. 马路亮堂堂. 水渍东拼西凑. 一扇窗户旁，困顿的流浪汉，年纪十八岁，青年人，居住其中. 巧合的夜，他从地下车库跑向田野. 没有眼睛，没有翅膀，夜晚，他们从地下车库跑向天国。</p>
                            <p><strong>4.</strong> 农田里面有什么？是农夫的劳动，还是农夫与蛇. 农田里有闯进来的失忆者. 嘘，细细听，角落里城墙在偷看. 水泥干了，苔藓绿了，搭起脉络的人们早都死了。</p>
                            <p><strong>5.</strong> 影子撺掇着，想起深海恐惧症的奶奶. 想起人的一生有多久，能走多远. 我是否见过那个一生中仅此一人的人. 想起喝醉的时候，他看见了一团影子，裹挟九百万平方米的果树，和巨大天国中人们的灵魂。</p>
                            <p><strong>6.</strong> 终点，城北火车站，南山下的墓园，他选择一块田！一块湖泊一样，一块烧光一百万个傻子和拥趸的庸人的火，那片火从哪燃起？他想起海子：“其实，你的一只眼睛就可以照亮世界……不要再画基督的橄榄园，要画就画橄榄收获……洗净生命。”他揉了揉眼睛，剩下空空的夜，只剩卖火柴的小女孩。</p>
                            <p><strong>7.</strong> 田野里面有什么？据报道，出现麦田怪圈现象. 我们在下不完的雨里庆祝，节日快乐. 银色的，是，安静的夜. 空空的井是游离的，你，我，他。</p>
                            <p><strong>8.</strong> 散步，自由者的权利. 赞美忒利亚. 冥古宙、太古宙、元古宙、寒武纪、奥陶纪、志留纪、泥盆纪、石炭纪、二叠纪……人类历史只占地球寿命极小一部分. 总有奇人，愿往上攀。</p>
                            <p><strong>9.</strong> 田野里有什么？歇息的片警，严肃的武警. 银白手铐，银灰手套，一个眼熟者，报纸上的故人，高高山人民监狱. 一支烟，两瓶酒，刑事案底，被抹去的文件. 巨齿身后的山，快把人压倒。</p>
                            <p><strong>10.</strong> 田野里有什么？一把火，冬天的，炽热的，压碎显生宙的火. 一颗星球，一段时光，一群尝试散步的客人，一次躁动. 一场偶遇. 几声啸叫. 田里只剩虫鸣。</p>
                            <p><strong>11.</strong> 新气象的一天，小雨过后，天色放晴，十分舒适. 某办公室内，酒醒后，一人唏嘘. 另一人不经心的笑. 红色印章落下。</p>
                         </div>`
            },
            8: {
                title: "八．落梅村",
                content: `<p>落梅村里没有梅花，桃花可开了不少。</p>
                          <p>落梅村里小孩很多，阿婆的孙子孙女算是最机灵的两个，他们是阿竹和阿兰。</p>
                          <p>落梅村里有条狗，名叫阿瓜. 他是村里人养的，是村子养的，或者是村子背靠着的大山养的. 阿瓜喜欢大山。</p>
                          <p>在太阳剩下的一点红褪去的时间，我披着余晖来到村子. 村口阿兰和阿竹吵着闹着——讨论关乎落梅村名字的问题. 周围无声，除了虫鸣。</p>
                          <p>阿兰拿着木竿，到处敲敲. 这里是阿婆的家，落梅村的第一户。</p>
                          <p>槐树突然开始发抖，可能因为大地震动，大地震动可能又因为阿兰的木竿. 总之，槐花是掉了下来。</p>
                          <p>“从前从前，落梅村里满是梅花，直到一个悲伤的季节，梅花从树上落下，钻进土里离开了村子，因此落梅村就是梅花落光了的村子的意思。”胸有成竹的是阿兰。</p>
                          <p>阿竹坐在铺着竹席的竹椅上抱着阿瓜，点了点头。“很美”，又摇了摇头。“你去过后山吗？”“没有，你呢？”“我也没去过。”</p>
                          <p>阿竹突然神秘了起来. 我模糊听了几句阿竹大声的悄悄话. 大概是说后山有颗很老很老的树，比夜晚乘凉时看到天上的星星还老，那颗树会一直落下梅花，春夏秋冬. 那棵树不会累，不会死，就像村里人希望中的阿瓜那样，欣喜的落着花，保佑着远远，远在山下的村子。</p>
                          <p>阿竹和阿兰都笑了，我也笑了，只有阿瓜没笑. 他只是摇了摇尾巴。</p>`
            },
            9: {
                title: "九．留言",
                content: `<p class="font-ancient text-lg text-center leading-loose py-12">
                            向着北方跑吧<br>
                            那里有斑鸠的“鸢尾”<br>
                            恰如旧日的爱恋<br>
                            伸手摸时就一溜烟飞走
                          </p>`
            },
            10: {
                title: "十．爬山虎和跳楼机—-鹦鹉的由来",
                content: `<p class="font-mono text-xs text-neutral-400 text-center leading-relaxed">
                            ᠬᠠᠶ᠋ᠢᠷᠠ   ᠮᠢᠨᠢ   ᠬᠠᠶ᠋ᠢᠷᠠ   ᠮᠢᠨᠢ   ᠮᠢᠨᠤ   ᠬᠠᠶ᠋ᠢᠷᠠ   ᠮᠢᠨᠢ ，<br>
                            ᠤᠯᠠᠭᠠᠨ   ᠴᠡᠴᠡᠭ   ᠴᠢᠮᠠ   ᠳ᠋ᠠᠭᠠᠨ   ᠡᠷᠭᠦᠨᠡᠮ 。<br>
                            <span class="text-[9px] text-neutral-500">—— 摘自《太阳泉》</span>
                          </p>
                          <p class="text-xs text-neutral-500 text-center italic mt-1">【译】：亲爱的我，亲爱的我，我的亲爱的我，红色的花朵在你身旁绽放。</p>
                          <div class="h-[1px] bg-neutral-900 my-4"></div>
                          <p>离市里不远的郊区，植被茂密的地方. 山里，河边，诸如此类，人没有飞虫多（尤其是夏天）. 来这，开车才方便. 行人谁会来这，没有导航也很遭罪。</p>
                          <p>（这盛产：爬山虎，小洋楼。）</p>
                          <p>我说的那栋，从祜东街一直下来，走过北山钓场，直直下去，十几里吧，就入了郊区，经过很长一节树木遮天蔽日的路，就到了，就是那栋. 没有安保室和围墙，只有一圈木篱笆围着，上头缠着花藤. 芒平写信给我说，那家人总不在，留最小的孩子在家是经常的事儿. 烦人的是那个管家，戴个狐狸面具，很狡黠，下手黑着呢，邱平就折在那了。</p>`
            },
            11: {
                title: "十一．远上寒山石径斜，白云深处有白云",
                content: `<p>拨开发黄叶子一拢，斜身跨过树藤，脚下湿泥路. 天阴沉，无鸟声。</p>
                          <p>一人往山中走，手持一旧铁桶盛水. 至方碑处，所行已过半. 回头望，向下望，雾气薄薄渐起，林间苍白，来时路不可见. 低头望，桶中水不剩一捧。</p>
                          <p>此人撇嘴，歪头扫去颈上汗珠. 碑在此处，无动静. 碑上有小偈，难辨认，但幸旧识古字少许，可观一二，似儿歌一曲，用词古怪，尾缀处醒目：</p>
                          <p class="font-ancient text-center text-neutral-400 my-4">“山已荒，寺尚在。<br>心空者死，心满者生。”</p>
                          <p>其人不语，却有心事，走路缓了. 山行本不易，临登顶时候，天已黑了. 此人停步，四顾，寻一处歇息地，踩落叶片沙沙声响，他忽得想起薯片，眉头缓了，嘴角勾起淡淡的笑。</p>
                          <p>不远处忽有动静，或是狸子，或是乌鸦. 他抬起头. 高处一点，似小楼阁，黄澄澄.“应是快到了”，他想. 于是顾不得休息就动身，可实在疲惫，丢掉水桶. 细汗渗出灰衬衫，解开纽扣. 发丝遮掩视线不清，盘起头发. 凡身上衣物有垂重之感，阻碍爬升者，尽数褪去。</p>
                          <p>一僧点一小莲花灯，目旷幽空，发现了他. 不多时，见到此人，已不是原来面目. 山林静的像死了，只有钟响，佛门礼乐. 僧人笑了，你有心事. 此人言道前来朝拜，愿闻解救法. 僧人欲言，却止，示意下山. 人大恐，不知所措. 惴惴不安离去，回头望，一片漆黑. 无钟无寺无老僧。</p>`
            },
            12: {
                title: "十二．吱嘎，铁锈轰鸣",
                content: `<p>冷又厚的铁门，倚着长满车前子的水洼. 先前门后的楼和管道常有轰鸣，现在死了，无声. 他总是来这。</p>
                          <p>一场雨后，腥气飘着，没有方向，黏住行人. 可能菜市场门口鱼摊，可能工厂后林子的坟. 可能雨，可能他. 气味来源不明晰. 他踱进工厂。</p>
                          <p>三把椅子，空在车床前. 其中两把已锈了，剩一把十分新，有水. 他挑了有水那把坐，再不坐就锈了。</p>
                          <p>全部的夜开始低语，和矮草，野蛮的长. 一个布袋，透着红，他带来的. 拖了一路. 月亮惨白，怀里掏出剪刀. 他有些厌烦，皱眉，摸出一把铁器. 圆锤形状. 麻袋被剪开，两声闷响在随后. 无声…… 离开时，他没踩死一片草。</p>`
            },
            13: {
                title: "十三．《罗温·艾金森Rowan Atkinson的尖叫HOWL》",
                content: `<p>岁月是树是石根是田是什么都行. 留给他的礼物是决定的权利. 编织世界上一半河流与铁的蜘蛛没见过喀纳斯湾口处烧光了的清晨. 来自大地的姑娘把那儿的早上装进口袋。</p>
                          <p>小伙姑娘相爱在银色的光秃草地上直到三年之后第一次拉手并一发不可收拾. 他们在天使圣花园苹果树拐角处立墓碑望着远方哈哈大笑. 他们砸印度垃圾堆的苍蝇大吼虫孑看我的炸弹. 他们说他们尝试自杀三十余次，可面面相觑发现都厌倦大蒜。</p>
                          <p>他们在老旧日历描写十五世纪刚国雨林，绑架密西西比河的水管工，强行要求其品尝枣泥面包. 他们翻遍了极黑夜晚下所有的厕所隔间只为寻找和肮脏或禁忌有关的鬼与妖精. 他们用一百四十四个神秘意大利土著咒语复活亚瑟王和阿兰展开决斗. 后面男孩战死，可女孩用偷偷藏起来的最后一个咒就把他复活在坚硬罐头里，那罐头有大海那么宽。</p>
                          <p>他们抄写硬币上每一处被人忽视的细节. 他们说了一个哑谜从没人解出，除了开头提到的那位老者. 还有很多的事要做，他们想. 他们作了深刻决定要求书写他们的文字算上标点刚好一千。</p>`
            },
            14: {
                title: "十四．阿如兰",
                content: `<p>—— 阿如兰长在阁楼里。</p>
                          <p>村口那座破瓦楼是阿修家为数不多的财产之一，砖红色的墙被水渍染的乌黑. 他也在那苦苦支撑了三十多年. 二层是一个带窗的阁楼. 每当能听见雨声的夜晚，总有些不争气的木头板湿裂开来，掉在楼板上发出闷响。</p>
                          <p>自从家中第五个孩子出生，楼下就拥挤起来. 瓶瓶罐罐靠在墙壁，货物不能再占着地，就一股脑扔到院子. 墙上挂着的干辣椒串看起来碍眼，墙角是它们最好的去处…… 随性直接的整理方式是阿修一贯的作风。</p>
                          <p>而阁楼上堆着的，是发霉页面模糊的旧报纸、报废的钢齿轮、落灰的柴火，还有一个纽扣眼睛，总是笑着的兔子布袋。哦对，阁楼上还有阿如兰. 可是阿如兰不是兰花，不是植物. 她是阿修家唯一的女孩子. 她是极为神秘的。</p>
                          <p class="italic text-neutral-400">她后来叫阿木。</p>`
            },
            15: {
                title: "十五．某伟大人物的采访",
                content: `<p>人走时总是蹑手蹑脚. 收拾行李，穿衣服，恋恋不舍回头看看，或者没有太多想法只是离开. 告别这一行径缺少痕迹。</p>
                          <p>时代在走远时更加含蓄，好像比那个离去的家伙轻巧千百倍，至于它走后极少的人发觉到它走了，只是在一些恍然间、细微的场合自我醒悟道：“哦，这里以前不是这样的”。</p>
                          <p>一个孩子在不经意间就长大了. 自打一次照面开始，到下次照面，中间的过程全然空白. 空白缩短了时间的行程，才让人徒生惊叹：“昨天你在树下捡石头玩耍，明天就弹一曲复杂精密的古典乐了”。</p>`
            },
            16: {
                title: "十六．优秀“居民”们协商要多看看",
                content: `<p>威廉·罗伽蓝在酒馆门口抽烟. 再过三天零一个小时，就是他四十一岁的生日. 吉立安二世没忍住：“去看什么？？”“看人，你这蠢货。”“那有什么好看的？况且你只是看，他们身上发生什么你并不关心.”</p>
                          <p>旁边白衣女士点了一根烟，威廉饶有兴致的问：你也抽烟？他的眼珠没有转过来，依旧盯着马路对面长的像爱神的动物服装美男子. 对方扯起袖子露出刻着的纹身——一个农夫，一个情妇，一个商贾。威廉快速地移开目光。</p>
                          <p>“我认为观看路人是一种很好的养生方式. 观看从道教上说是劳神伤精.”伽蓝大声说. 场面混乱起来了. 珠宝商从校车上一跃而下：“我来加入，我认为观看路人是享受对吗？”</p>
                          <p>“人的生命如此短暂，如此长久. 记住他们的脸总是好的.”吉立安提醒他有健忘症.“我们都不是人啊”威廉说. 鸦雀无声，哄堂大笑. “外部世界的幻影罢了，但多看看也挺好.”</p>
                          <p>下雨了，车们用光了最后一丝力气朝着家狂奔. “这下没人可看了.”丘比特与伽蓝失魂落魄. 太阳也无非是一颗晨星而已，只有当我们醒着的时候才是真正的破晓. “看看”，所有人齐声说。</p>`
            }
        };

        // 17-30 空白连载占位
        for (let i = 17; i <= 30; i++) {
            NOVELS_DATA[i] = {
                title: `第 ${i} 篇 · 预留空境`,
                content: `<p class="text-center text-neutral-500 italic py-12">
                            （这是第 ${i} 篇小说占位符）<br><br>
                            等待在此续写二十一世纪的雨落与种子蕨的秘密……<br>
                            您可以在网页源代码的 NOVELS_DATA 中轻而易举地添加您的连载段落。
                          </p>`
            };
        }
    </script>

    <!-- 顶栏、2D十字路口与单页视图控制逻辑 (完全剔除虚拟连结报错) -->
    <script>
        // 1. 全局导航面板显隐与防堆叠机制
        let isMenuOpen = false;
        const menuBtn = document.getElementById('menuBtn');
        const navOverlay = document.getElementById('navOverlay');
        const bar1 = document.getElementById('bar1');
        const bar2 = document.getElementById('bar2');
        const bar3 = document.getElementById('bar3');

        function openMenu() {
            isMenuOpen = true;
            navOverlay.classList.remove('opacity-0', 'pointer-events-none');
            navOverlay.classList.add('opacity-100');
            bar1.style.transform = 'rotate(45deg) translate(2px, 2px)';
            bar2.style.opacity = '0';
            bar3.style.transform = 'rotate(-45deg) translate(2px, -2px)';
            // 目录展开时，显示顶部的Logo
            document.getElementById('siteLogo').classList.remove('opacity-0', 'pointer-events-none');
        }

        function closeMenu() {
            isMenuOpen = false;
            navOverlay.classList.remove('opacity-100');
            navOverlay.classList.add('opacity-0', 'pointer-events-none');
            bar1.style.transform = 'none';
            bar2.style.opacity = '1';
            bar3.style.transform = 'none';
            
            // 核心修复：如果不是首页，关闭目录后Logo保持完全隐藏状态，杜绝一切手机堆叠
            const activePage = document.querySelector('.page-content.active-page');
            if (activePage && activePage.id !== 'page-home') {
                document.getElementById('siteLogo').classList.add('opacity-0', 'pointer-events-none');
            }
        }

        menuBtn.addEventListener('click', () => {
            if (isMenuOpen) closeMenu(); else openMenu();
        });

        // 2. SPA页面物理显隐控制
        function showPage(pageId) {
            closeMenu();
            closeReader(); // 强制关闭可能残留的小说阅读器 overlay
            
            document.querySelectorAll('.page-content').forEach(page => {
                page.classList.remove('active-page');
            });
            const targetPage = document.getElementById(`page-${pageId}`);
            if (targetPage) targetPage.classList.add('active-page');

            // 标志管理：Logo只在首页Home浮现，在其他项目页面不显示，避免与子页面标题发生遮挡重合
            const logo = document.getElementById('siteLogo');
            if (pageId === 'home') {
                logo.classList.remove('opacity-0', 'pointer-events-none');
            } else {
                logo.classList.add('opacity-0', 'pointer-events-none');
            }

            // 初始化小说十字路口
            if (pageId === 'novel') {
                initCrossroadsAnimation();
            }
        }

        // 3. 首页全景摄影淡入渐变 (无缩放无卡顿)
        const slides = document.querySelectorAll('.bg-slide');
        let currentSlideIndex = 0;
        setInterval(() => {
            if (slides.length <= 1) return;
            slides[currentSlideIndex].classList.remove('active');
            slides[currentSlideIndex].classList.add('opacity-0');
            currentSlideIndex = (currentSlideIndex + 1) % slides.length;
            slides[currentSlideIndex].classList.remove('opacity-0');
            slides[currentSlideIndex].classList.add('active');
        }, 6000);

        // 4. 2D 十字路口 (删除所有脏乱小石子与虚线，更换为质感极简细线条)
        let canvas, ctx, animationFrameId, mouseX = 0, mouseY = 0, time = 0;
        let plants = [], motes = [];

        class SeedFern {
            constructor(x, y, scale, speed) {
                this.x = x; this.y = y; this.scale = scale;
                this.angleOffset = Math.random() * Math.PI * 2;
                this.speed = speed;
                this.baseAngle = (Math.random() - 0.5) * 0.1;
            }
            draw(ctx, time) {
                ctx.save(); ctx.translate(this.x, this.y);
                const sway = Math.sin(time * this.speed + this.angleOffset) * 0.08;
                ctx.rotate(this.baseAngle + sway); ctx.scale(this.scale, this.scale);
                ctx.strokeStyle = 'rgba(120, 120, 120, 0.3)'; ctx.fillStyle = 'rgba(25, 25, 25, 0.7)';
                ctx.lineWidth = 2.2; ctx.beginPath(); ctx.moveTo(0, 0); ctx.quadraticCurveTo(-10, -50, -5, -120); ctx.stroke();
                for (let i = 1; i <= 6; i++) {
                    const ratio = i / 7; const leafY = -120 * ratio; const leafWidth = 24 * (1 - ratio * 0.6);
                    ctx.beginPath(); ctx.ellipse(-leafWidth/2 - 2, leafY, leafWidth/2, 5, -0.3, 0, Math.PI * 2); ctx.fill(); ctx.stroke();
                    ctx.beginPath(); ctx.ellipse(leafWidth/2 + 2, leafY, leafWidth/2, 5, 0.3, 0, Math.PI * 2); ctx.fill(); ctx.stroke();
                }
                ctx.restore();
            }
        }

        // 神秘流萤微茫光尘 (营造高级感的流动点缀)
        class GlowMote {
            constructor(x, y) {
                this.x = x; this.y = y;
                this.radius = Math.random() * 1.5 + 0.5;
                this.vx = (Math.random() - 0.5) * 0.15;
                this.vy = (Math.random() - 0.5) * 0.15;
                this.baseAlpha = Math.random() * 0.25 + 0.05;
                this.pulse = Math.random() * 0.04 + 0.01;
            }
            draw(ctx, time) {
                this.x += this.vx; this.y += this.vy;
                const alpha = this.baseAlpha + Math.sin(time * this.pulse) * this.baseAlpha;
                ctx.beginPath(); ctx.arc(this.x, this.y, this.radius, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(200, 220, 255, ${Math.max(0, alpha)})`;
                ctx.fill();
            }
        }

        function initCrossroadsAnimation() {
            canvas = document.getElementById('roadCanvas');
            if (!canvas) return;
            ctx = canvas.getContext('2d');
            function resizeCanvas() {
                if (!canvas) return; canvas.width = canvas.offsetWidth; canvas.height = canvas.offsetHeight; generateCrossroads();
            }
            window.removeEventListener('resize', resizeCanvas); window.addEventListener('resize', resizeCanvas); resizeCanvas();
            
            canvas.addEventListener('mousemove', (e) => {
                const rect = canvas.getBoundingClientRect(); mouseX = e.clientX - rect.left; mouseY = e.clientY - rect.top;
            });
            mouseX = canvas.width / 2; mouseY = canvas.height / 2;

            function generateCrossroads() {
                plants = []; motes = [];
                const cx = canvas.width / 2, cy = canvas.height / 2;
                for (let i = 0; i < 12; i++) {
                    const rx = (Math.random() > 0.5 ? 1 : -1) * (100 + Math.random() * 300) + cx;
                    const ry = (Math.random() > 0.5 ? 1 : -1) * (100 + Math.random() * 300) + cy;
                    plants.push(new SeedFern(rx, ry, 0.45 + Math.random() * 0.45, 1.2 + Math.random() * 1.5));
                }
                for (let i = 0; i < 50; i++) motes.push(new GlowMote(Math.random() * canvas.width, Math.random() * canvas.height));
            }

            function animate() {
                time += 0.02; ctx.clearRect(0, 0, canvas.width, canvas.height);
                const cx = canvas.width / 2, cy = canvas.height / 2, roadWidth = Math.max(70, canvas.width * 0.08);

                const radialGlow = ctx.createRadialGradient(cx, cy, 20, cx, cy, Math.max(cx, cy));
                radialGlow.addColorStop(0, '#0c0c0c'); radialGlow.addColorStop(1, '#010101');
                ctx.fillStyle = radialGlow; ctx.fillRect(0, 0, canvas.width, canvas.height);

                // 十字深灰色路径
                ctx.fillStyle = '#070707';
                ctx.fillRect(0, cy - roadWidth/2, canvas.width, roadWidth);
                ctx.fillRect(cx - roadWidth/2, 0, roadWidth, canvas.height);

                // 改用：极其高级干净的细实线，替代以前杂乱难看的虚线
                ctx.strokeStyle = 'rgba(255, 255, 255, 0.12)'; ctx.lineWidth = 1; ctx.setLineDash([]);
                ctx.beginPath(); ctx.moveTo(0, cy - roadWidth/2); ctx.lineTo(canvas.width, cy - roadWidth/2); ctx.stroke();
                ctx.beginPath(); ctx.moveTo(0, cy + roadWidth/2); ctx.lineTo(canvas.width, cy + roadWidth/2); ctx.stroke();
                ctx.beginPath(); ctx.moveTo(cx - roadWidth/2, 0); ctx.lineTo(cx - roadWidth/2, canvas.height); ctx.stroke();
                ctx.beginPath(); ctx.moveTo(cx + roadWidth/2, 0); ctx.lineTo(cx + roadWidth/2, canvas.height); ctx.stroke();

                motes.forEach(m => m.draw(ctx, time));
                plants.forEach(p => p.draw(ctx, time));
                drawCharacter(cx, cy);

                animationFrameId = requestAnimationFrame(animate);
            }

            function drawCharacter(cx, cy) {
                ctx.save();
                ctx.translate(cx, cy + Math.sin(time * 2.5) * 1.5);
                const dist = Math.sqrt(Math.pow(mouseX - cx, 2) + Math.pow(mouseY - cy, 2)) || 1;
                const eX = ((mouseX - cx) / dist) * 2.5, eY = ((mouseY - cy) / dist) * 1.2;

                ctx.fillStyle = '#111'; ctx.beginPath(); ctx.arc(0, -22, 10, 0, Math.PI * 2); ctx.fill();
                ctx.fillStyle = '#222'; ctx.strokeStyle = 'rgba(200, 200, 200, 0.4)'; ctx.lineWidth = 1.2;
                ctx.beginPath(); ctx.moveTo(-22, -22); ctx.quadraticCurveTo(0, -38, 22, -22); ctx.closePath(); ctx.fill(); ctx.stroke();
                ctx.fillStyle = 'rgba(255, 255, 255, 0.8)';
                ctx.beginPath(); ctx.arc(-3 + eX, -20 + eY, 1, 0, Math.PI * 2); ctx.arc(3 + eX, -20 + eY, 1, 0, Math.PI * 2); ctx.fill();
                ctx.fillStyle = '#0f0f0f'; ctx.strokeStyle = 'rgba(80, 80, 80, 0.4)'; ctx.lineWidth = 1;
                ctx.beginPath(); ctx.moveTo(-10, -10); ctx.lineTo(-14, 20); ctx.quadraticCurveTo(0, 25, 14, 20); ctx.lineTo(10, -10); ctx.closePath(); ctx.fill(); ctx.stroke();
                ctx.restore();
            }

            if (animationFrameId) cancelAnimationFrame(animationFrameId); animate();
        }

        // 5. 小说篇章选择器与全屏阅读面板核心逻辑
        document.addEventListener('DOMContentLoaded', () => {
            showPage('home');
            const grid = document.getElementById('numbersGrid');
            for (let i = 1; i <= 30; i++) {
                const btn = document.createElement('button');
                btn.className = `w-11 h-11 text-xs font-mono rounded-sm transition-all duration-300 border ${i <= 16 ? 'border-neutral-700 hover:border-white text-neutral-200 bg-neutral-900/40 hover:bg-neutral-800' : 'border-neutral-900 text-neutral-600 bg-transparent'}`;
                btn.innerHTML = i < 10 ? `0${i}` : i;
                btn.onclick = () => openChapter(i);
                grid.appendChild(btn);
            }
        });

        function openNumberSelector() {
            document.getElementById('numberSelector').classList.remove('translate-x-full');
            // 打开目录时，彻底隐藏全局Header(汉堡菜单和 Logo)，防止其发生碰撞、遮叠或误触
            document.getElementById('mainHeader').classList.add('opacity-0', 'pointer-events-none');
        }

        function closeNumberSelector() {
            document.getElementById('numberSelector').classList.add('translate-x-full');
            document.getElementById('mainHeader').classList.remove('opacity-0', 'pointer-events-none');
        }

        function openChapter(num) {
            closeNumberSelector();
            const data = NOVELS_DATA[num];
            if (data) {
                document.getElementById('readerChapterNum').innerText = `CHAPTER ${num < 10 ? '0' + num : num}`;
                document.getElementById('readerTitle').innerText = data.title;
                document.getElementById('readerContent').innerHTML = data.content;
                const reader = document.getElementById('novelReader');
                reader.scrollTo({ top: 0 });
                reader.classList.remove('opacity-0', 'pointer-events-none');
                reader.classList.add('opacity-100');
                // 打开小说阅读器时彻底隔离顶栏，防止任何可能的手势误触
                document.getElementById('mainHeader').classList.add('opacity-0', 'pointer-events-none');
            }
        }

        function closeReader() {
            const reader = document.getElementById('novelReader');
            reader.classList.remove('opacity-100');
            reader.classList.add('opacity-0', 'pointer-events-none');
            // 点击返回时，精准回到 2D 十字路口界面，并让顶栏重新显现
            document.getElementById('mainHeader').classList.remove('opacity-0', 'pointer-events-none');
        }
    </script>
</body>
</html>

```
