<!DOCTYPE html>  
<html lang=**"**ar**"** dir=**"**rtl**"**>  
<head>  
    <meta charset=**"**UTF-8**"**>  
    <meta name=**"**viewport**"** content=**"**width=device-width, initial-scale=1.0**"**>  
    <title>MK - **أداة** **تعديل** **فريمات** **الفيديو**</title>  
    <script src=**"**https**:**//cdn.tailwindcss.com**"**></script>  
    <link href=**"**https**:**//fonts.googleapis.com/css2?family=Tajawal**:**wght@400;500;700;900&display=swap**"** rel=**"**stylesheet**"**>  
    <style>  
        * {  
            font-family**:** **'**Tajawal**'**, sans-serif;  
        }  
        .glow-effect {  
            box-shadow**:** 0 0 30px -5px rgba**(**56, 189, 248, 0.2**)**;  
        }  
    </style>  
</head>  
<body class=**"**bg-slate-950 text-slate-100 min-h-screen flex flex-col justify-between selection**:**bg-cyan-500 selection**:**text-slate-950**"**>  
  
    <!-- Header Navigation -->  
    <header class=**"**w-full border-b border-slate-800 bg-slate-900/50 backdrop-blur-md sticky top-0 z-50**"**>  
        <div class=**"**max-w-5xl mx-auto px-4 py-4 flex items-center justify-between**"**>  
            <div class=**"**flex items-center gap-3**"**>  
                <div class=**"**w-10 h-10 rounded-xl bg-gradient-to-tr from-cyan-500 via-sky-500 to-indigo-500 flex items-center justify-center font-extrabold text-slate-950 text-xl shadow-lg tracking-wider**"**>  
                    MK  
                </div>  
                <div>  
                    <h1 class=**"**font-extrabold text-lg text-slate-100 tracking-wide**"**>MK Tools</h1>  
                    <p class=**"**text-xs text-slate-400**"**>**مُعالج** **فريمات** **الفيديو** **بدون** **فقدان** **الجودة**</p>  
                </div>  
            </div>  
            <span class=**"**inline-flex items-center px-3 py-1 rounded-full text-xs font-semibold bg-cyan-500/10 text-cyan-400 border border-cyan-500/20**"**>  
                **معالجة** **محلية** **آمنة** 🔒  
            </span>  
        </div>  
    </header>  
  
    <!-- Main Container -->  
    <main class=**"**max-w-4xl mx-auto px-4 py-8 flex-1 flex flex-col items-center justify-center w-full**"**>  
          
        <!-- Hero Title -->  
        <div class=**"**text-center mb-8 max-w-2xl**"**>  
            <h2 class=**"**text-3xl sm**:**text-4xl font-black text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 via-sky-200 to-indigo-400 mb-3**"**>  
                **أداة** MK **لرفع** **المقاطع** **بجودة** **كاملة**  
            </h2>  
            <p class=**"**text-slate-400 text-sm sm**:**text-base leading-relaxed**"**>  
                **تعديل** **وسم** **معدل** **الإطارات** **(**Metadata**)** **فوراً** **لتبدو** 30 FPS **بدون** **ضغط** **أو** **تقليل** **الجودة،** **لتبقى** **الدقة** **والألوان** **بأعلى** **جودة** **ممكنة**.  
            </p>  
        </div>  
  
        <!-- Main Card Container -->  
        <div class=**"**w-full bg-slate-900/80 border border-slate-800 rounded-3xl p-6 sm**:**p-8 backdrop-blur-xl shadow-2xl glow-effect**"**>  
              
            <!-- Drag and Drop Zone -->  
            <div id=**"**dropZone**"** class=**"**border-2 border-dashed border-slate-700 hover**:**border-cyan-400/60 rounded-2xl p-8 sm**:**p-12 text-center cursor-pointer transition-all duration-300 bg-slate-950/50 hover**:**bg-slate-800/40 group relative overflow-hidden**"**>  
                <input type=**"**file**"** id=**"**fileInput**"** accept=**"**video/mp4,video/quicktime**"** class=**"**hidden**"**>  
                  
                <div class=**"**flex flex-col items-center gap-4 relative z-10**"**>  
                    <div class=**"**w-16 h-16 rounded-2xl bg-slate-800/80 group-hover**:**bg-cyan-500/10 flex items-center justify-center text-3xl group-hover**:**scale-110 transition-transform duration-300 border border-slate-700 group-hover**:**border-cyan-500/40**"**>  
                        🎬  
                    </div>  
                    <div>  
                        <p class=**"**font-bold text-slate-200 group-hover**:**text-cyan-400 transition-colors text-base sm**:**text-lg**"** id=**"**fileLabel**"**>  
                            **اضغط** **هنا** **لاختيار** **فيديو** MP4 **أو** **اسحبه** **إلى** **هنا**  
                        </p>  
                        <p class=**"**text-xs text-slate-500 mt-1**"**>**يدعم** **صيغ** MP4 **و** MOV **(معالجة** **سريعة** **بالمؤشرات** **الحية)**</p>  
                    </div>  
                </div>  
            </div>  
  
            <!-- Selected File Status Box -->  
            <div id=**"**fileDetails**"** class=**"**hidden mt-4 p-4 rounded-xl bg-slate-800/50 border border-slate-700 flex items-center justify-between**"**>  
                <div class=**"**flex items-center gap-3 overflow-hidden**"**>  
                    <span class=**"**text-2xl**"**>📹</span>  
                    <div class=**"**truncate**"**>  
                        <p id=**"**fileName**"** class=**"**font-medium text-slate-200 text-sm truncate**"**></p>  
                        <p id=**"**fileSize**"** class=**"**text-xs text-slate-400**"**></p>  
                    </div>  
                </div>  
                <button id=**"**removeFileBtn**"** class=**"**text-slate-400 hover**:**text-rose-400 p-2 text-sm transition-colors**"**>  
                    **إزالة** ✕  
                </button>  
            </div>  
  
            <!-- Primary Process Button -->  
            <div class=**"**mt-6**"**>  
                <button id=**"**processBtn**"** onclick=**"**processVideo**()"** disabled   
                    class=**"**w-full py-4 px-6 rounded-xl font-bold text-slate-950 bg-gradient-to-r from-cyan-400 to-sky-400 hover**:**from-cyan-300 hover**:**to-sky-300 disabled**:**from-slate-800 disabled**:**to-slate-800 disabled**:**text-slate-500 disabled**:**cursor-not-allowed transition-all duration-300 shadow-lg shadow-cyan-500/20 active**:**scale-[0.99] flex items-center justify-center gap-2 text-base sm**:**text-lg**"**>  
                    <span>**معالجة** **الفيديو** **وتحميله**</span>  
                    <span class=**"**text-xl**"**>⬇️</span>  
                </button>  
            </div>  
  
            <!-- Status Indicator -->  
            <div id=**"**statusBox**"** class=**"**hidden mt-4 p-4 rounded-xl text-center text-sm font-medium**"**></div>  
  
            <!-- Separator Line -->  
            <div class=**"**my-6 border-t border-slate-800**"**></div>  
  
            <!-- Dedicated TikTok Upload Button -->  
            <div>  
                <a href=**"**https**:**//www.tiktok.com/upload**"** target=**"**_blank**"** rel=**"**noopener noreferrer**"**  
                    class=**"**w-full py-3.5 px-6 rounded-xl font-bold text-slate-100 bg-slate-800/80 hover**:**bg-slate-800 border border-slate-700 hover**:**border-cyan-500/40 transition-all duration-300 active**:**scale-[0.99] flex items-center justify-center gap-3 text-base group**"**>  
                    <span class=**"**text-xl group-hover**:**scale-110 transition-transform**"**>📱</span>  
                    <span>**الذهاب** **إلى** **تيك** **توك** **للرفع** **(**TikTok Upload**)**</span>  
                    <span class=**"**text-xs text-slate-400 bg-slate-900 px-2 py-1 rounded border border-slate-700 group-hover**:**border-cyan-500/30**"**>**نافذة** **جديدة** ↗</span>  
                </a>  
            </div>  
  
        </div>  
  
        <!-- Instructions Grid -->  
        <section class=**"**w-full mt-10 grid grid-cols-1 md**:**grid-cols-3 gap-4**"**>  
            <div class=**"**p-5 rounded-2xl bg-slate-900/40 border border-slate-800/80**"**>  
                <div class=**"**text-cyan-400 font-bold text-lg mb-1**"**>1. **اختيار** **الفيديو**</div>  
                <p class=**"**text-slate-400 text-xs sm**:**text-sm**"**>**قم** **برفع** **مقطع** **الفيديو** **بالدقة** **العالية** **(حتى** 4K**)** **بدون** **الحاجة** **لتقليل** **الجودة**.</p>  
            </div>  
            <div class=**"**p-5 rounded-2xl bg-slate-900/40 border border-slate-800/80**"**>  
                <div class=**"**text-sky-400 font-bold text-lg mb-1**"**>2. **المعالجة** **والتحميل**</div>  
                <p class=**"**text-slate-400 text-xs sm**:**text-sm**"**>**اضغط** **زر** **المعالجة** **ليتم** **تعديل** **الـ** 30fps **وتحميل** **الفيديو** **على** **جهازك** **فوراً**.</p>  
            </div>  
            <div class=**"**p-5 rounded-2xl bg-slate-900/40 border border-slate-800/80**"**>  
                <div class=**"**text-indigo-400 font-bold text-lg mb-1**"**>3. **النشر** **اليدوي**</div>  
                <p class=**"**text-slate-400 text-xs sm**:**text-sm**"**>**اضغط** **زر** **التوجه** **لتيك** **توك** **بأسفل** **الأداة** **لتسجيل** **الدخول** **ورفع** **الفيديو** **من** **التنزيلات**.</p>  
            </div>  
        </section>  
    </main>  
  
    <!-- Footer -->  
    <footer class=**"**w-full border-t border-slate-800/60 py-4 text-center text-xs text-slate-500**"**>  
        MK Engine — **جميع** **العمليات** **تتم** **محلياً** **على** **جهازك** 100% **دون** **رفع** **البيانات** **لأي** **سيرفر**.  
    </footer>  
  
    <!-- Logic Script -->  
    <script>  
        const dropZone = document.getElementById**('**dropZone**')**;  
        const fileInput = document.getElementById**('**fileInput**')**;  
        const processBtn = document.getElementById**('**processBtn**')**;  
        const fileDetails = document.getElementById**('**fileDetails**')**;  
        const fileName = document.getElementById**('**fileName**')**;  
        const fileSize = document.getElementById**('**fileSize**')**;  
        const removeFileBtn = document.getElementById**('**removeFileBtn**')**;  
        const statusBox = document.getElementById**('**statusBox**')**;  
  
        let selectedFile = null;  
  
        // Drag & Drop Handlers  
        dropZone.addEventListener**('**click**'**, **()** => fileInput.click**())**;  
  
        dropZone.addEventListener**('**dragover**'**, **(**e**)** => {  
            e.preventDefault**()**;  
            dropZone.classList.add**('**border-cyan-400**'**, **'**bg-slate-800/50**')**;  
        }**)**;  
  
        [**'**dragleave**'**, **'**dragend**'**].forEach**(**type => {  
            dropZone.addEventListener**(**type, **()** => {  
                dropZone.classList.remove**('**border-cyan-400**'**, **'**bg-slate-800/50**')**;  
            }**)**;  
        }**)**;  
  
        dropZone.addEventListener**('**drop**'**, **(**e**)** => {  
            e.preventDefault**()**;  
            dropZone.classList.remove**('**border-cyan-400**'**, **'**bg-slate-800/50**')**;  
            if **(**e.dataTransfer.files.length > 0**)** {  
                handleFileSelect**(**e.dataTransfer.files[0]**)**;  
            }  
        }**)**;  
  
        fileInput.addEventListener**('**change**'**, **(**e**)** => {  
            if **(**e.target.files.length > 0**)** {  
                handleFileSelect**(**e.target.files[0]**)**;  
            }  
        }**)**;  
  
        removeFileBtn.addEventListener**('**click**'**, **(**e**)** => {  
            e.stopPropagation**()**;  
            resetFile**()**;  
        }**)**;  
  
        function handleFileSelect**(**file**)** {  
            if **(**!file.type.includes**('**mp4**')** && !file.type.includes**('**quicktime**'))** {  
                showStatus**('يرجى** **اختيار** **ملف** **فيديو** **بصيغة** MP4 **أو** MOV **فقط**.**'**, **'**error**')**;  
                return;  
            }  
  
            selectedFile = file;  
            fileName.innerText = file.name;  
            fileSize.innerText = **(**file.size / **(**1024 * 1024**))**.toFixed**(**2**)** + **'** **ميجابايت'**;  
              
            fileDetails.classList.remove**('**hidden**')**;  
            processBtn.disabled = false;  
            hideStatus**()**;  
        }  
  
        function resetFile**()** {  
            selectedFile = null;  
            fileInput.value = **''**;  
            fileDetails.classList.add**('**hidden**')**;  
            processBtn.disabled = true;  
            hideStatus**()**;  
        }  
  
        async function processVideo**()** {  
            if **(**!selectedFile**)** return;  
  
            processBtn.disabled = true;  
            showStatus**('جاري** **تعديل** **فريمات** **الفيديو** **والتجهيز** **للتحميل**...**'**, **'**info**')**;  
  
            try {  
                const buffer = await selectedFile.arrayBuffer**()**;  
                const bytes = new Uint8Array**(**buffer**)**;  
  
                // Patching MP4 timescale metadata directly inside atoms  
                const modifiedBytes = patchMp4Timescale**(**bytes, 30**)**;  
  
                const blob = new Blob**(**[modifiedBytes], { type**:** selectedFile.type || **'**video/mp4**'** }**)**;  
                const url = URL.createObjectURL**(**blob**)**;  
                  
                // Automatic Download  
                const downloadLink = document.createElement**('**a**')**;  
                downloadLink.href = url;  
                downloadLink.download = `MK_30fps_${selectedFile.name}`;  
                document.body.appendChild**(**downloadLink**)**;  
                downloadLink.click**()**;  
                document.body.removeChild**(**downloadLink**)**;  
                  
                setTimeout**(()** => URL.revokeObjectURL**(**url**)**, 10000**)**;  
  
                showStatus**('تمت** **معالجة** **الفيديو** **وتحميله** **بنجاح**! **يمكنك** **الآن** **الضغط** **على** **زر** **تيك** **توك** **بالأسفل** **لرفعه**.**'**, **'**success**')**;  
                processBtn.disabled = false;  
  
            } catch **(**err**)** {  
                console.error**(**err**)**;  
                showStatus**('حدث** **خطأ** **أثناء** **معالجة** **ملف** **الفيديو**.**'**, **'**error**')**;  
                processBtn.disabled = false;  
            }  
        }  
  
        function patchMp4Timescale**(**bytes, targetFps**)** {  
            for **(**let i = 0; i < bytes.length - 8; i++**)** {  
                if **(**bytes[i] === 0x6D && bytes[i+1] === 0x64 && bytes[i+2] === 0x68 && bytes[i+3] === 0x64**)** {  
                    const version = bytes[i + 4];  
                    let timescaleOffset = **(**version === 1**)** ? i + 24 **:** i + 16;  
                      
                    if **(**timescaleOffset + 4 <= bytes.length**)** {  
                        const view = new DataView**(**bytes.buffer**)**;  
                        view.setUint32**(**timescaleOffset, targetFps * 1000, false**)**;  
                    }  
                }  
            }  
            return bytes;  
        }  
  
        function showStatus**(**message, type**)** {  
            statusBox.classList.remove**('**hidden**'**, **'**bg-cyan-500/10**'**, **'**text-cyan-400**'**, **'**bg-emerald-500/10**'**, **'**text-emerald-400**'**, **'**bg-rose-500/10**'**, **'**text-rose-400**')**;  
              
            if **(**type === **'**info**')** {  
                statusBox.classList.add**('**bg-cyan-500/10**'**, **'**text-cyan-400**')**;  
            } else if **(**type === **'**success**')** {  
                statusBox.classList.add**('**bg-emerald-500/10**'**, **'**text-emerald-400**')**;  
            } else if **(**type === **'**error**')** {  
                statusBox.classList.add**('**bg-rose-500/10**'**, **'**text-rose-400**')**;  
            }  
              
            statusBox.innerText = message;  
        }  
  
        function hideStatus**()** {  
            statusBox.classList.add**('**hidden**')**;  
        }  
    </script>  
</body>  
</html>  
