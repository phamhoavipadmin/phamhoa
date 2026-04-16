<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>CHECK FF TOOL v2.6 – ADMIN PHAM HOA .NET</title>
  <meta name="description" content="CHECK FF TOOL – Công cụ kiểm tra tài khoản Free Fire chuyên nghiệp. Tra cứu mail xác thực, liên kết, bảo mật và nhiều tính năng khác." />
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            mono: ['"Share Tech Mono"', 'Courier New', 'monospace'],
          },
          colors: {
            neon: '#00ff88',
            violet: '#7c3aed',
            cyber: '#06b6d4',
          },
          animation: {
            'pulse-slow': 'pulse 3s cubic-bezier(0.4,0,0.6,1) infinite',
            'spin-slow': 'spin 2s linear infinite',
          }
        }
      }
    }
  </script>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Share+Tech+Mono&family=Orbitron:wght@700;900&display=swap" rel="stylesheet" />
  <style>
    *,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
    html,body{height:100%;overflow-x:hidden;}
    body{background:#060610;font-family:'Share Tech Mono',monospace;color:#fff;}
    ::-webkit-scrollbar{width:4px;}
    ::-webkit-scrollbar-track{background:#060610;}
    ::-webkit-scrollbar-thumb{background:#00ff8840;border-radius:2px;}
    .grid-bg{position:fixed;inset:0;pointer-events:none;opacity:.25;z-index:0;background-image:linear-gradient(rgba(0,255,136,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(0,255,136,.04) 1px,transparent 1px);background-size:40px 40px;}
    .glow-green{text-shadow:0 0 20px #00ff88,0 0 40px rgba(0,255,136,.3);}
    .glow-violet{text-shadow:0 0 10px #7c3aed;}
    .glow-cyan{text-shadow:0 0 10px #06b6d4;}
    @keyframes pulseDot{0%,100%{opacity:1;transform:scale(1);}50%{opacity:.5;transform:scale(.8);}}
    .pulse-dot{animation:pulseDot 1.5s ease-in-out infinite;}
    @keyframes scanMove{0%{top:0%;}100%{top:100%;}}
    .scan-line{position:absolute;left:0;right:0;height:2px;pointer-events:none;background:linear-gradient(90deg,transparent,rgba(0,255,136,.18),transparent);animation:scanMove 4s linear infinite;}
    .matrix-char{position:absolute;font-family:'Share Tech Mono',monospace;font-size:14px;color:#00ff88;user-select:none;pointer-events:none;text-shadow:0 0 8px #00ff88;}
    @keyframes glitch{0%{transform:translateX(0);}25%{transform:translateX(2px);}50%{transform:translateX(-2px);}75%{transform:translateX(1px);}100%{transform:translateX(0);}}
    .glitch{animation:glitch .15s steps(1) infinite;}
    @keyframes spin{to{transform:rotate(360deg);}}
    .spinner{width:16px;height:16px;border-radius:50%;border:2px solid #00ff88;border-top-color:transparent;animation:spin .7s linear infinite;display:inline-block;flex-shrink:0;}
    .spinner-lg{width:32px;height:32px;border-width:2px;}
    .card-glass{background:rgba(0,0,0,.5);border:1px solid rgba(0,255,136,.12);border-radius:1rem;}
    .tab-active{background:linear-gradient(135deg,rgba(0,255,136,.15),rgba(124,58,237,.15));color:#00ff88 !important;border:1px solid rgba(0,255,136,.2) !important;box-shadow:0 0 15px rgba(0,255,136,.1);}
    .tab-inactive{color:#555;border:1px solid transparent;}
    .tool-panel{overflow:hidden;max-height:0;transition:max-height .3s ease;}
    .tool-panel.open{max-height:400px;}
    .modal-overlay{position:fixed;inset:0;z-index:50;display:flex;align-items:center;justify-content:center;padding:1rem;background:rgba(0,0,0,.85);backdrop-filter:blur(6px);}
    .modal-overlay.hidden{display:none;}
    .corner-tl{position:absolute;top:0;left:0;width:32px;height:32px;border-top:2px solid #00ff88;border-left:2px solid #00ff88;border-radius:1rem 0 0 0;opacity:.6;}
    .corner-tr{position:absolute;top:0;right:0;width:32px;height:32px;border-top:2px solid #00ff88;border-right:2px solid #00ff88;border-radius:0 1rem 0 0;opacity:.6;}
    .corner-bl{position:absolute;bottom:0;left:0;width:32px;height:32px;border-bottom:2px solid #00ff88;border-left:2px solid #00ff88;border-radius:0 0 0 1rem;opacity:.6;}
    .corner-br{position:absolute;bottom:0;right:0;width:32px;height:32px;border-bottom:2px solid #00ff88;border-right:2px solid #00ff88;border-radius:0 0 1rem 0;opacity:.6;}
    button{cursor:pointer;font-family:'Share Tech Mono',monospace;}
    input,select,textarea{font-family:'Share Tech Mono',monospace;}
    input:focus,select:focus{outline:none;}
    .chevron{transition:transform .25s ease;}
    .chevron.open{transform:rotate(180deg);}
    #page-login,#page-dashboard{min-height:100vh;}
    @keyframes pingOnce{0%{transform:scale(1);opacity:.2;}100%{transform:scale(1.6);opacity:0;}}
    .ping-shield{animation:pingOnce 1.5s ease-out infinite;}
    .otp-box{width:40px;height:40px;text-align:center;border-radius:.5rem;background:#0a0a1a;border:1px solid rgba(255,255,255,.1);color:#fff;font-family:'Share Tech Mono',monospace;font-size:1rem;outline:none;transition:border-color .2s,box-shadow .2s;}
    .otp-box:focus{border-color:rgba(124,58,237,.6);box-shadow:0 0 8px rgba(124,58,237,.2);}
    .amount-btn{padding:.6rem;border-radius:.75rem;border:1px solid rgba(255,255,255,.08);background:#050515;color:#666;font-size:.7rem;transition:all .2s;cursor:pointer;}
    .amount-btn.selected{color:var(--provider-color);}
    .amount-btn:hover{opacity:.85;}
    .provider-dropdown{position:absolute;z-index:20;top:calc(100% + 4px);left:0;right:0;border-radius:.75rem;overflow:hidden;border:1px solid rgba(0,255,136,.2);background:#080815;}
    .provider-dropdown.hidden{display:none;}
    .provider-option{width:100%;display:flex;align-items:center;gap:.5rem;padding:.75rem 1rem;background:transparent;border:none;font-size:.8rem;cursor:pointer;transition:background .15s;}
    .provider-option:hover{background:rgba(255,255,255,.04);}
    .toast{position:fixed;top:20px;right:20px;z-index:100;padding:12px 20px;border-radius:12px;font-size:13px;transform:translateX(120%);transition:transform .3s ease;max-width:350px;}
    .toast.show{transform:translateX(0);}
    .toast-success{background:rgba(0,255,136,.15);border:1px solid rgba(0,255,136,.4);color:#00ff88;}
    .toast-error{background:rgba(239,68,68,.15);border:1px solid rgba(239,68,68,.4);color:#ef4444;}
  </style>
</head>
<body>
  <div class="grid-bg"></div>
  <div id="toast" class="toast"></div>

  <div id="page-login" >
    <div id="matrix-container" class="absolute inset-0 overflow-hidden pointer-events-none z-0"></div>
    <div class="scan-line" style="z-index:1;"></div>
    <div class="absolute inset-0 pointer-events-none z-0" style="background-image:linear-gradient(rgba(0,255,136,.03) 1px,transparent 1px),linear-gradient(90deg,rgba(0,255,136,.03) 1px,transparent 1px);background-size:50px 50px;"></div>
    <div class="absolute top-1/4 left-1/4 w-64 h-64 rounded-full pointer-events-none" style="background:#00ff88;opacity:.04;filter:blur(60px);"></div>
    <div class="absolute bottom-1/4 right-1/4 w-64 h-64 rounded-full pointer-events-none" style="background:#7c3aed;opacity:.06;filter:blur(60px);"></div>

    <div class="relative z-10 min-h-screen flex items-center justify-center px-4 py-10">
      <div class="w-full max-w-md">
        <div class="text-center mb-8">
          <div class="inline-flex items-center gap-3 mb-4">
            <div class="relative flex-shrink-0">
              <svg id="shield-icon" class="w-10 h-10" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2" style="filter:drop-shadow(0 0 12px #00ff88);"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
              <div class="absolute inset-0 ping-shield flex items-center justify-center opacity-20"><svg class="w-10 h-10" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg></div>
            </div>
            <div>
              <h1 id="login-title" class="text-3xl tracking-widest uppercase font-bold glow-green" style="font-family:'Share Tech Mono',monospace;color:#00ff88;transition:all .1s;">CHECK FF TOOL</h1>
              <p class="glow-violet mt-1 tracking-widest text-xs" style="color:#7c3aed;letter-spacing:.3em;">ADMIN: PHAM HOA.NET v2.6</p>
            </div>
          </div>
          <div class="flex items-center justify-center gap-6 text-xs">
            <div class="flex items-center gap-1.5"><div class="w-2 h-2 rounded-full pulse-dot" style="background:#00ff88;box-shadow:0 0 6px #00ff88;"></div><span style="color:#00ff88;">SERVER: ONLINE</span></div>
            <div class="flex items-center gap-1.5"><div class="w-2 h-2 rounded-full pulse-dot" style="background:#7c3aed;box-shadow:0 0 6px #7c3aed;animation-delay:.5s;"></div><span style="color:#7c3aed;">SECURE CONNECTION</span></div>
          </div>
        </div>

        <div class="relative rounded-2xl p-8 border" style="background:linear-gradient(135deg,rgba(0,20,10,.95) 0%,rgba(10,5,30,.95) 100%);border-color:rgba(0,255,136,.3);box-shadow:0 0 40px rgba(0,255,136,.1),inset 0 0 40px rgba(0,0,0,.5);">
          <div class="corner-tl"></div><div class="corner-tr"></div><div class="corner-bl"></div><div class="corner-br"></div>
          <div class="mb-6">
            <div class="flex items-center gap-2 mb-2">
              <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2"><polyline points="4 17 10 11 4 5"/><line x1="12" y1="19" x2="20" y2="19"/></svg>
              <span class="text-xs tracking-wider" style="color:#00ff88;">NHẬP UID FREE FIRE</span>
            </div>
            <p class="text-xs" style="color:#555;">&gt; Nhập ID game để truy cập dữ liệu tài khoản...</p>
          </div>
          <div class="mb-6">
            <label class="block text-xs tracking-widest uppercase mb-2" style="color:#00ff88;">[ Player UID ]</label>
            <div class="relative">
              <div class="absolute left-4 top-1/2 -translate-y-1/2"><svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#7c3aed" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg></div>
              <input id="uid-input" type="password" placeholder="VD: 123456789" class="w-full rounded-xl pl-12 pr-12 py-4 text-sm transition-all" style="background:#050510;border:1px solid rgba(0,255,136,.15);color:#00ff88;caret-color:#00ff88;" autocomplete="off" />
              <button id="toggle-uid-btn" class="absolute right-4 top-1/2 -translate-y-1/2 transition-colors hover:text-green-400" style="color:#555;" aria-label="Toggle visibility">
                <svg id="eye-icon" class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/></svg>
              </button>
            </div>
          </div>
          <button id="login-btn" class="w-full py-4 rounded-xl tracking-widest uppercase text-sm relative overflow-hidden transition-all duration-300 disabled:opacity-50 disabled:cursor-not-allowed flex items-center justify-center gap-3" style="background:linear-gradient(135deg,#00cc66,#5b21b6);box-shadow:0 0 25px rgba(0,255,136,.4),0 0 50px rgba(124,58,237,.2);color:#fff;border:1px solid rgba(0,255,136,.4);">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>
            TRUY CẬP HỆ THỐNG
          </button>
          <div id="loading-logs" class="hidden mt-4 space-y-1"></div>
          <div id="login-error" class="hidden mt-4 p-3 rounded-lg text-center text-xs" style="border:1px solid rgba(239,68,68,.3);background:rgba(239,68,68,.08);color:#ef4444;"></div>
          <div class="mt-6 p-3 rounded-lg" style="border:1px solid rgba(124,58,237,.2);background:rgba(124,58,237,.05);">
            <p class="text-xs text-center" style="color:#666;">⚠️ Chỉ sử dụng cho mục đích hợp pháp | CHECK FF TOOL</p>
          </div>
        </div>
        <div class="mt-6 grid grid-cols-3 gap-3">
          <div class="rounded-xl p-3 text-center border" style="background:rgba(0,0,0,.4);border-color:rgba(0,255,136,.2);"><div class="font-bold" style="color:#00ff88;text-shadow:0 0 10px #00ff88;">10903</div><div class="text-xs mt-1" style="color:#555;">ONLINE</div></div>
          <div class="rounded-xl p-3 text-center border" style="background:rgba(0,0,0,.4);border-color:rgba(124,58,237,.2);"><div class="font-bold" style="color:#7c3aed;text-shadow:0 0 10px #7c3aed;">7+</div><div class="text-xs mt-1" style="color:#555;">TOOLS</div></div>
          <div class="rounded-xl p-3 text-center border" style="background:rgba(0,0,0,.4);border-color:rgba(245,158,11,.2);"><div class="font-bold" style="color:#f59e0b;text-shadow:0 0 10px #f59e0b;">99.9%</div><div class="text-xs mt-1" style="color:#555;">UPTIME</div></div>
        </div>
      </div>
    </div>
  </div>

  <div id="page-dashboard" class="hidden">
    <header class="sticky top-0 z-40 border-b" style="background:rgba(6,6,16,.95);backdrop-filter:blur(20px);border-color:rgba(0,255,136,.12);box-shadow:0 0 30px rgba(0,255,136,.05);">
      <div class="max-w-6xl mx-auto px-4 py-3 flex items-center justify-between flex-wrap gap-3">
        <div class="flex items-center gap-3">
          <svg class="w-7 h-7" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2" style="filter:drop-shadow(0 0 8px #00ff88);"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          <div>
            <span class="font-bold text-lg tracking-widest" style="color:#00ff88;text-shadow:0 0 15px rgba(0,255,136,.5);">CHECK FF TOOL</span>
            <span class="text-xs ml-2" style="color:#444;">v2.6</span>
          </div>
        </div>
        <div class="flex items-center gap-2 flex-wrap">
          <div class="flex items-center gap-2 px-4 py-2 rounded-xl border text-xs" style="background:rgba(245,158,11,.1);border-color:rgba(245,158,11,.3);color:#f59e0b;">
            <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="1" y="4" width="22" height="16" rx="2" ry="2"/><circle cx="18" cy="12" r="1"/></svg>
            Ví: <span id="wallet-balance">0đ</span>
          </div>
          <button id="btn-pricing" class="flex items-center gap-2 px-4 py-2 rounded-xl border text-xs transition-all hover:scale-105" style="background:rgba(124,58,237,.1);border-color:rgba(124,58,237,.3);color:#7c3aed;box-shadow:0 0 10px rgba(124,58,237,.15);">
            <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20.59 13.41l-7.17 7.17a2 2 0 0 1-2.83 0L2 12V2h10l8.59 8.59a2 2 0 0 1 0 2.82z"/><line x1="7" y1="7" x2="7.01" y2="7"/></svg>
            Bảng Giá
          </button>
          <button id="btn-payment" class="flex items-center gap-2 px-4 py-2 rounded-xl border text-xs transition-all hover:scale-105" style="background:rgba(0,255,136,.1);border-color:rgba(0,255,136,.3);color:#00ff88;box-shadow:0 0 10px rgba(0,255,136,.15);">
            <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="1" y="4" width="22" height="16" rx="2" ry="2"/><line x1="1" y1="10" x2="23" y2="10"/></svg>
            Nạp tiền
          </button>
          <a href="/logout.php" id="btn-logout" class="flex items-center gap-2 px-3 py-2 rounded-xl border text-xs transition-all" style="border-color:rgba(185,28,28,.3);color:#dc2626;text-decoration:none;">
            <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M9 21H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h4"/><polyline points="16 17 21 12 16 7"/><line x1="21" y1="12" x2="9" y2="12"/></svg>
            Logout
          </a>
        </div>
      </div>
    </header>

    <div class="max-w-6xl mx-auto px-4 py-6 relative z-10">
      <div class="rounded-2xl border mb-6 relative overflow-hidden" style="background:linear-gradient(135deg,rgba(0,20,10,.9) 0%,rgba(10,5,30,.9) 50%,rgba(0,0,0,.9) 100%);border-color:rgba(0,255,136,.2);box-shadow:0 0 40px rgba(0,255,136,.08);">
        <div class="absolute left-0 right-0 h-px pointer-events-none" style="top:50%;background:linear-gradient(90deg,transparent,rgba(0,255,136,.2),transparent);"></div>

                <div class="flex items-start gap-4 p-6 flex-wrap">
          <div class="relative flex-shrink-0">
            <div class="w-20 h-20 rounded-2xl overflow-hidden border-2 flex items-center justify-center" style="border-color:rgba(0,255,136,.4);box-shadow:0 0 20px rgba(0,255,136,.2);background:#060610;">
              <span style="color:#00ff88;font-size:32px;font-weight:bold;">FF</span>
            </div>
            <div class="absolute -bottom-1 -right-1 w-5 h-5 rounded-full border-2" style="border-color:#060610;background:#00ff88;box-shadow:0 0 8px #00ff88;"></div>
          </div>
          <div class="flex-1 min-w-0">
            <div class="flex items-center gap-3 flex-wrap mb-1">
              <h1 class="text-2xl font-bold" style="color:#fff;text-shadow:0 0 10px rgba(255,255,255,.3);">—</h1>
                          </div>
            <p class="text-sm mt-0.5" style="color:#555;">UID: <span id="display-uid">—</span></p>
                        <div class="flex items-center gap-2 mt-2 flex-wrap">
              <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="#555" stroke-width="2"><circle cx="12" cy="12" r="10"/><line x1="2" y1="12" x2="22" y2="12"/><path d="M12 2a15.3 15.3 0 0 1 4 10 15.3 15.3 0 0 1-4 10 15.3 15.3 0 0 1-4-10 15.3 15.3 0 0 1 4-10z"/></svg>
              <span class="text-xs" style="color:#555;">Khu vực: VN</span>
              <span style="color:#333;">|</span>
              <svg class="w-3.5 h-3.5" viewBox="0 0 24 24" fill="none" stroke="#555" stroke-width="2"><line x1="4" y1="9" x2="20" y2="9"/><line x1="4" y1="15" x2="20" y2="15"/><line x1="10" y1="3" x2="8" y2="21"/><line x1="16" y1="3" x2="14" y2="21"/></svg>
              <span class="text-xs" style="color:#555;">Guild: —</span>
            </div>
          </div>
          <div class="grid grid-cols-2 gap-3 w-full sm:w-auto flex-shrink-0">
            <div class="rounded-xl p-3 border text-center" style="background:rgba(0,255,136,.03);border-color:rgba(0,255,136,.15);">
              <svg class="w-4 h-4 mx-auto mb-1" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2"><polyline points="22 12 18 12 15 21 9 3 6 12 2 12"/></svg>
              <div class="font-bold" style="color:#00ff88;font-size:15px;">0</div>
              <div class="text-xs mt-0.5" style="color:#555;">EXP</div>
            </div>
            <div class="rounded-xl p-3 border text-center" style="background:rgba(245,158,11,.03);border-color:rgba(245,158,11,.15);">
              <svg class="w-4 h-4 mx-auto mb-1" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2"><polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/></svg>
              <div class="font-bold" style="color:#f59e0b;font-size:15px;">0</div>
              <div class="text-xs mt-0.5" style="color:#555;">LIKE</div>
            </div>
            <div class="rounded-xl p-3 border text-center" style="background:rgba(124,58,237,.03);border-color:rgba(124,58,237,.15);">
              <svg class="w-4 h-4 mx-auto mb-1" viewBox="0 0 24 24" fill="none" stroke="#7c3aed" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
              <div class="font-bold" style="color:#7c3aed;font-size:11px;">—</div>
              <div class="text-xs mt-0.5" style="color:#555;">TẠO ACC</div>
            </div>
            <div class="rounded-xl p-3 border text-center" style="background:rgba(6,182,212,.03);border-color:rgba(6,182,212,.15);">
              <svg class="w-4 h-4 mx-auto mb-1" viewBox="0 0 24 24" fill="none" stroke="#06b6d4" stroke-width="2"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
              <div class="font-bold" style="color:#06b6d4;font-size:11px;">—</div>
              <div class="text-xs mt-0.5" style="color:#555;">ĐĂNG NHẬP CUỐI</div>
            </div>
          </div>
        </div>
              </div>

      <div class="flex gap-1 p-1 rounded-xl border mb-6" style="background:rgba(0,0,0,.5);border-color:rgba(0,255,136,.1);">
        <button id="tab-info" onclick="switchTab('info')" class="flex-1 flex items-center justify-center gap-2 py-2.5 px-4 rounded-lg text-sm transition-all tab-active">
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
          Thông tin
        </button>
        <button id="tab-tools" onclick="switchTab('tools')" class="flex-1 flex items-center justify-center gap-2 py-2.5 px-4 rounded-lg text-sm transition-all tab-inactive">
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M19.07 4.93l-1.41 1.41M3 12H1m4.93-7.07L4.51 3.51M12 3V1M20.49 20.49l-1.41-1.41M21 12h2"/></svg>
          Công cụ
        </button>
        <button id="tab-security" onclick="switchTab('security')" class="flex-1 flex items-center justify-center gap-2 py-2.5 px-4 rounded-lg text-sm transition-all tab-inactive">
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="11" width="18" height="11" rx="2" ry="2"/><path d="M7 11V7a5 5 0 0 1 10 0v4"/></svg>
          Bảo mật
        </button>
      </div>

      <div id="content-info" class="grid grid-cols-1 lg:grid-cols-2 gap-5">
        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2"><path d="M21 2l-2 2m-7.61 7.61a5.5 5.5 0 1 1-7.778 7.778 5.5 5.5 0 0 1 7.777-7.777zm0 0L15.5 7.5m0 0l3 3L22 7l-3-3m-3.5 3.5L19 4"/></svg>
            Access Token
          </h3>
          <div class="rounded-xl border p-4" style="background:#050510;border-color:rgba(255,255,255,.06);">
            <div class="flex items-center justify-between flex-wrap gap-2">
              <span class="text-sm" style="color:#555;">Token</span>
              <div class="flex items-center gap-2">
                <span id="token-display" class="text-xs truncate max-w-[180px]" style="color:#999;">Không Khả Dụng</span>
                              </div>
            </div>
          </div>
        </div>

        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#7c3aed" stroke-width="2"><path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2"/><circle cx="12" cy="7" r="4"/></svg>
            Thông tin cơ bản
          </h3>
          <div class="rounded-xl border p-4 space-y-3" style="background:#050510;border-color:rgba(255,255,255,.06);">
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">Tên HĐ</span><span class="text-sm" style="color:#ccc;">—</span></div>
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">UID</span><span class="text-sm" style="color:#ccc;">—</span></div>
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">Cấp độ</span><span class="text-sm" style="color:#ccc;">Level 0</span></div>
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">Hạng</span><span class="text-sm" style="color:#ccc;">Unranked</span></div>
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">Guild</span><span class="text-sm" style="color:#ccc;">—</span></div>
            <div class="flex items-center justify-between"><span class="text-sm" style="color:#555;">Credit Score</span><span class="text-sm" style="color:#ccc;">0</span></div>
                      </div>
        </div>

        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#06b6d4" stroke-width="2"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"/><polyline points="22,6 12,13 2,6"/></svg>
            Mail xác thực
          </h3>
          <div class="rounded-xl border p-4 space-y-3" style="background:#050510;border-color:rgba(255,255,255,.06);">
            <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#555;">Mail Xác Thực</span>
              <div class="flex items-center gap-1.5">
                <span class="mail-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
            <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#555;">Mail đang gắn</span>
              <div class="flex items-center gap-1.5">
                <span class="mail-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
            <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#555;">Thời gian gắn</span>
              <div class="flex items-center gap-1.5">
                <span class="mail-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                      </div>
        </div>

        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"/><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"/></svg>
            Liên kết
          </h3>
          <div class="rounded-xl border p-4 space-y-3" style="background:#050510;border-color:rgba(255,255,255,.06);">
                        <div class="flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-5 h-5 rounded flex items-center justify-center text-xs font-bold text-white" style="background:#ea4335;">G</span>
                <span class="text-sm" style="color:#555;">Google</span>
              </div>
              <div class="flex items-center gap-1.5">
                <span class="link-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                        <div class="flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-5 h-5 rounded flex items-center justify-center text-xs font-bold text-white" style="background:#aaa;">🍎</span>
                <span class="text-sm" style="color:#555;">iCloud</span>
              </div>
              <div class="flex items-center gap-1.5">
                <span class="link-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                        <div class="flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-5 h-5 rounded flex items-center justify-center text-xs font-bold text-white" style="background:#4680C2;">VK</span>
                <span class="text-sm" style="color:#555;">VKontakte</span>
              </div>
              <div class="flex items-center gap-1.5">
                <span class="link-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                        <div class="flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-5 h-5 rounded flex items-center justify-center text-xs font-bold text-white" style="background:#1DA1F2;">X</span>
                <span class="text-sm" style="color:#555;">Twitter (X)</span>
              </div>
              <div class="flex items-center gap-1.5">
                <span class="link-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                        <div class="flex items-center justify-between">
              <div class="flex items-center gap-2">
                <span class="w-5 h-5 rounded flex items-center justify-center text-xs font-bold text-white" style="background:#1877F2;">f</span>
                <span class="text-sm" style="color:#555;">Facebook</span>
              </div>
              <div class="flex items-center gap-1.5">
                <span class="link-masked text-xs" style="color:#999;">*****</span>
                              </div>
            </div>
                                  </div>
        </div>
      </div>

      <div id="content-tools" class="hidden card-glass p-5">
        <h3 class="font-bold mb-5 flex items-center gap-2 text-white">
          <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2"><circle cx="12" cy="12" r="3"/><path d="M19.07 4.93l-1.41 1.41M3 12H1m4.93-7.07L4.51 3.51M12 3V1M20.49 20.49l-1.41-1.41M21 12h2"/></svg>
          Công cụ <span class="text-xs ml-2" style="color:#555;">Ví: <span id="tools-wallet-balance">0đ</span></span>
        </h3>
        <div class="space-y-2" id="tools-list"></div>
      </div>

      <div id="content-security" class="hidden grid grid-cols-1 lg:grid-cols-2 gap-5">
        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#7c3aed" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
            Mã bảo mật (6)
          </h3>
          <div class="rounded-xl border p-4 space-y-4" style="background:#050510;border-color:rgba(255,255,255,.06);">
            <div>
              <span class="text-xs mb-2 block" style="color:#555;">Mã</span>
              <div class="flex gap-2 flex-wrap">
                <input id="otp-0" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,0)" />
                <input id="otp-1" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,1)" />
                <input id="otp-2" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,2)" />
                <input id="otp-3" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,3)" />
                <input id="otp-4" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,4)" />
                <input id="otp-5" class="otp-box" type="text" maxlength="1" oninput="otpNext(this,5)" />
                <button onclick="checkSecCode()" class="flex-1 py-2 rounded-lg text-sm transition-all hover:opacity-90 min-w-[80px]" style="background:linear-gradient(135deg,#5b21b6,#7c3aed);color:#fff;box-shadow:0 0 15px rgba(124,58,237,.3);">Check ngay</button>
              </div>
            </div>
            <div class="flex items-center justify-between">
              <span class="text-xs" style="color:#555;">Kết quả</span>
              <span id="sec-result" class="text-sm" style="color:#666;">Chưa check</span>
            </div>
          </div>
        </div>

        <div class="card-glass p-5">
          <h3 class="font-bold mb-4 flex items-center gap-2 text-white">
            <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="#f59e0b" stroke-width="2"><path d="M18 8A6 6 0 0 0 6 8c0 7-3 9-3 9h18s-3-2-3-9"/><path d="M13.73 21a2 2 0 0 1-3.46 0"/></svg>
            Trạng thái bảo mật
          </h3>
          <div class="rounded-xl border p-4 space-y-3" style="background:#050510;border-color:rgba(255,255,255,.06);">
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Mail xác thực</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa gắn</span>
              </div>
            </div>
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Mã bảo mật</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa gắn</span>
              </div>
            </div>
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Google</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa gắn</span>
              </div>
            </div>
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Facebook</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa gắn</span>
              </div>
            </div>
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Xác thực 2 lớp</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa bật</span>
              </div>
            </div>
                        <div class="flex items-center justify-between">
              <span class="text-sm" style="color:#666;">Mã OTP dự phòng</span>
              <div class="flex items-center gap-1.5">
                <div class="w-1.5 h-1.5 rounded-full" style="background:#ef4444;box-shadow:0 0 4px #ef4444;"></div>
                <span class="text-xs" style="color:#ef4444;">Chưa thiết lập</span>
              </div>
            </div>
                      </div>
        </div>
      </div>
    </div>
  </div>

  <div id="pricing-modal" class="modal-overlay hidden">
    <div class="relative w-full max-w-5xl max-h-[90vh] overflow-y-auto rounded-2xl border" style="background:linear-gradient(135deg,#0a0a15 0%,#050510 100%);border-color:rgba(0,255,136,.2);box-shadow:0 0 60px rgba(0,255,136,.1);" onclick="event.stopPropagation()">
      <div class="sticky top-0 z-10 flex items-center justify-between p-6 border-b" style="border-color:rgba(0,255,136,.1);background:linear-gradient(135deg,#0a0a15 0%,#050510 100%);">
        <h2 class="text-2xl tracking-widest uppercase" style="color:#00ff88;text-shadow:0 0 20px rgba(0,255,136,.5);">⚡ Bảng Giá Dịch Vụ</h2>
        <button onclick="closePricing()" class="p-2 rounded-lg border transition-all hover:text-white" style="border-color:rgba(255,255,255,.12);color:#999;" aria-label="Close"><svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg></button>
      </div>
      <div class="p-6 grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4" id="pricing-grid"></div>
    </div>
  </div>

  <div id="payment-modal" class="modal-overlay hidden">
    <div class="relative w-full max-w-md rounded-2xl border overflow-hidden" style="background:linear-gradient(135deg,#0a0a18 0%,#050510 100%);border-color:rgba(0,255,136,.25);box-shadow:0 0 60px rgba(0,255,136,.1);" onclick="event.stopPropagation()">
      <div class="flex items-center justify-between p-5 border-b" style="border-color:rgba(0,255,136,.1);">
        <div class="flex items-center gap-3">
          <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="#00ff88" stroke-width="2" style="filter:drop-shadow(0 0 8px #00ff88);"><rect x="1" y="4" width="22" height="16" rx="2" ry="2"/><line x1="1" y1="10" x2="23" y2="10"/></svg>
          <div>
            <h2 class="font-bold tracking-wider" style="color:#00ff88;">NẠP TIỀN TỰ ĐỘNG</h2>
            <p class="text-xs" style="color:#555;">Quét mã QR qua ứng dụng ngân hàng</p>
          </div>
        </div>
        <button onclick="closePayment()" class="p-2 rounded-lg border transition-all hover:text-white" style="border-color:rgba(255,255,255,.1);color:#999;" aria-label="Close"><svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="18" y1="6" x2="6" y2="18"/><line x1="6" y1="6" x2="18" y2="18"/></svg></button>
      </div>
      
      <div class="p-5 space-y-4 text-center">
        <div class="inline-block p-3 rounded-xl bg-white mx-auto shadow-lg">
          <img src="https://via.placeholder.com/200x200.png?text=QR+Code+VietinBank" alt="QR Code VietinBank" class="w-48 h-48 object-contain rounded-lg" />
        </div>

        <div class="text-left space-y-3 p-4 rounded-xl border mt-2" style="background:#050515;border:1px solid rgba(0,255,136,.15);">
          
          <div class="flex justify-between items-center border-b pb-2" style="border-color:rgba(255,255,255,.05);">
            <span class="text-xs uppercase tracking-wider" style="color:#555;">Ngân hàng</span>
            <span class="text-sm font-bold text-white">VietinBank</span>
          </div>
          
          <div class="flex justify-between items-center border-b pb-2" style="border-color:rgba(255,255,255,.05);">
            <span class="text-xs uppercase tracking-wider" style="color:#555;">Chủ tài khoản</span>
            <span class="text-sm font-bold text-white">LO VAN HOA</span>
          </div>

          <div class="flex justify-between items-center border-b pb-2" style="border-color:rgba(255,255,255,.05);">
            <span class="text-xs uppercase tracking-wider" style="color:#555;">Số tài khoản</span>
            <div class="flex items-center gap-2">
              <span class="text-sm font-bold" style="color:#00ff88;">105885614494</span>
              <button onclick="copyToClipboard('105885614494')" class="px-2 py-1 rounded text-xs transition-colors" style="background:rgba(0,255,136,.1);color:#00ff88;border:1px solid rgba(0,255,136,.2);">Copy</button>
            </div>
          </div>

          <div class="flex justify-between items-center">
            <span class="text-xs uppercase tracking-wider" style="color:#555;">Nội dung CK</span>
            <div class="flex items-center gap-2">
              <span class="text-sm font-bold" style="color:#f59e0b;">NAP CHECKFF</span>
              <button onclick="copyToClipboard('NAP CHECKFF')" class="px-2 py-1 rounded text-xs transition-colors" style="background:rgba(245,158,11,.1);color:#f59e0b;border:1px solid rgba(245,158,11,.2);">Copy</button>
            </div>
          </div>

        </div>

        <div class="mt-4 p-3 rounded-lg text-xs" style="background:rgba(124,58,237,.05);border:1px solid rgba(124,58,237,.2);">
          <p style="color:#ccc;">⚡ Giao dịch được xử lý tự động trong vòng <span style="color:#00ff88;font-weight:bold;">1-3 phút</span> sau khi chuyển khoản thành công. Sai nội dung vui lòng liên hệ Admin.</p>
        </div>
      </div>
    </div>
  </div>

<script>
/* ===== GLOBAL DATA FROM PHP ===== */
const IS_LOGGED_IN = false;
const USER_UID = '';
const IS_FAKE = false;
const ACCESS_TOKEN = '';
const TOOLS_CONFIG = [{"id":"token_login","name":"Log acc qua token","price":50000,"desc":"Đăng nhập tài khoản bằng access token","status":"active","color":"#7c3aed"},{"id":"link_manage","name":"Gắn\/Gỡ liên kết","price":100000,"desc":"Gắn hoặc gỡ liên kết tài khoản","status":"active","color":"#06b6d4"},{"id":"mail_manage","name":"Gắn\/Gỡ Mail Xác Thực","price":100000,"desc":"Gắn hoặc gỡ mail xác thực","status":"active","color":"#00ff88"},{"id":"block_otp","name":"Chặn mã xác thực","price":59000,"desc":"Chặn mã OTP gửi về thiết bị","status":"active","color":"#f59e0b"},{"id":"otp_receive","name":"Nhận mã OTP","price":69000,"desc":"Nhận mã OTP qua SMS hoặc email","status":"active","color":"#10b981"},{"id":"spam_login","name":"Spam login","price":139000,"desc":"Spam đăng nhập liên tục vào tài khoản","status":"active","color":"#ef4444"},{"id":"ban_7day","name":"Ban 7 ngày","price":79000,"desc":"Ban tài khoản trong 7 ngày","status":"active","color":"#f97316"},{"id":"check_password","name":"Check mật khẩu","price":150000,"desc":"Kiểm tra & hiển thị mật khẩu + thông tin bảo mật tài khoản","status":"active","color":"#06b6d4"}];

/* ===== TOAST ===== */
function showToast(msg, type='success') {
  const t = document.getElementById('toast');
  t.className = 'toast toast-' + type + ' show';
  t.textContent = msg;
  setTimeout(() => t.classList.remove('show'), 3000);
}

/* ===== MATRIX BG ===== */
(function(){
  const container=document.getElementById('matrix-container');
  if(!container) return;
  const chars=[];
  for(let i=0;i<60;i++){
    const el=document.createElement('span');
    el.className='matrix-char';
    const x=Math.random()*100;const y=Math.random()*100;
    const speed=0.5+Math.random()*1.5;
    const op=0.1+Math.random()*0.4;
    el.style.left=x+'%';el.style.top=y+'%';el.style.opacity=op;
    el.textContent=String.fromCharCode(0x30A0+Math.floor(Math.random()*96));
    container.appendChild(el);
    chars.push({el,y,speed,op});
  }
  setInterval(()=>{
    chars.forEach(c=>{
      c.y=c.y>100?-5:c.y+c.speed*0.1;
      c.el.style.top=c.y+'%';
      if(Math.random()>0.95) c.el.textContent=String.fromCharCode(0x30A0+Math.floor(Math.random()*96));
    });
  },100);
  setInterval(()=>{
    const t=document.getElementById('login-title');
    if(!t) return;
    t.style.textShadow='2px 0 #ff0055,-2px 0 #00ffff,0 0 20px #00ff88';
    t.style.transform='translateX(2px)';
    setTimeout(()=>{
      t.style.textShadow='0 0 20px #00ff88,0 0 40px rgba(0,255,136,.3)';
      t.style.transform='translateX(0)';
    },200);
  },3000);
})();

/* ===== UID INPUT ===== */
const uidInput=document.getElementById('uid-input');
if(uidInput){
  uidInput.addEventListener('input',function(){
    this.style.borderColor=this.value?'rgba(0,255,136,.5)':'rgba(0,255,136,.15)';
    this.style.boxShadow=this.value?'0 0 15px rgba(0,255,136,.1),inset 0 0 15px rgba(0,0,0,.5)':'inset 0 0 15px rgba(0,0,0,.5)';
  });
  uidInput.addEventListener('keydown',e=>{ if(e.key==='Enter') document.getElementById('login-btn').click(); });
}

/* Toggle UID visibility */
let uidVisible=false;
document.getElementById('toggle-uid-btn')?.addEventListener('click',()=>{
  uidVisible=!uidVisible;
  uidInput.type=uidVisible?'text':'password';
  document.getElementById('eye-icon').innerHTML=uidVisible
    ?'<path d="M17.94 17.94A10.07 10.07 0 0 1 12 20c-7 0-11-8-11-8a18.45 18.45 0 0 1 5.06-5.94M9.9 4.24A9.12 9.12 0 0 1 12 4c7 0 11 8 11 8a18.5 18.5 0 0 1-2.16 3.19m-6.72-1.07a3 3 0 1 1-4.24-4.24"/><line x1="1" y1="1" x2="23" y2="23"/>'
    :'<path d="M1 12s4-8 11-8 11 8 11 8-4 8-11 8-11-8-11-8z"/><circle cx="12" cy="12" r="3"/>';
});

/* ===== LOGIN (AJAX) ===== */
const LOADING_STEPS=['Kết nối máy chủ...','Xác thực UID...','Giải mã dữ liệu...','Tải thông tin tài khoản...'];

document.getElementById('login-btn')?.addEventListener('click',function(){
  const uid=uidInput.value.trim();
  if(!uid) return;
  const btn=this;
  btn.disabled=true;
  btn.style.background='linear-gradient(135deg,#003322,#1a0a4a)';
  btn.style.boxShadow='none';
  btn.innerHTML='<span class="spinner"></span><span class="text-green-400 animate-pulse text-sm">ĐANG KẾT NỐI HỆ THỐNG...</span>';

  const logsEl=document.getElementById('loading-logs');
  const errorEl=document.getElementById('login-error');
  logsEl.innerHTML='';logsEl.classList.remove('hidden');
  errorEl.classList.add('hidden');

  let step=0;
  const interval=setInterval(()=>{
    if(step>=LOADING_STEPS.length){clearInterval(interval);doLogin(uid);return;}
    const div=document.createElement('div');
    div.className='flex items-center gap-2 text-xs';
    div.innerHTML=`<span style="color:#00ff88;">></span><span style="color:#555;">${LOADING_STEPS[step]}</span><span style="color:#00ff88;" class="ml-auto">OK</span>`;
    logsEl.appendChild(div);
    step++;
  },600);
});

function doLogin(uid) {
  const formData = new FormData();
  formData.append('uid', uid);

  fetch('/api/login.php', { method: 'POST', body: formData })
    .then(r => r.json())
    .then(data => {
      if (data.status === 'success') {
        window.location.reload();
      } else {
        showLoginError(data.message || 'Đăng nhập thất bại');
        resetLoginBtn();
      }
    })
    .catch(err => {
      showLoginError('Lỗi kết nối. Vui lòng thử lại.');
      resetLoginBtn();
    });
}

function showLoginError(msg) {
  const el = document.getElementById('login-error');
  el.textContent = '❌ ' + msg;
  el.classList.remove('hidden');
}

function resetLoginBtn() {
  const btn = document.getElementById('login-btn');
  btn.disabled = false;
  btn.style.background = 'linear-gradient(135deg,#00cc66,#5b21b6)';
  btn.style.boxShadow = '0 0 25px rgba(0,255,136,.4),0 0 50px rgba(124,58,237,.2)';
  btn.innerHTML = '<svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polygon points="13 2 3 14 12 14 11 22 21 10 12 10 13 2"/></svg>TRUY CẬP HỆ THỐNG';
}

/* ===== TABS ===== */
function switchTab(tab){
  ['info','tools','security'].forEach(t=>{
    document.getElementById('content-'+t)?.classList.add('hidden');
    document.getElementById('tab-'+t)?.classList.remove('tab-active');
    document.getElementById('tab-'+t)?.classList.add('tab-inactive');
  });
  document.getElementById('content-'+tab)?.classList.remove('hidden');
  document.getElementById('tab-'+tab)?.classList.add('tab-active');
  document.getElementById('tab-'+tab)?.classList.remove('tab-inactive');
}

/* ===== TOKEN ===== */
let tokenVisible=false;
function toggleToken(){
  tokenVisible=!tokenVisible;
  const d=document.getElementById('token-display');
  d.textContent=tokenVisible?ACCESS_TOKEN:'Ẩn token';
}

/* ===== MAIL/LINK MASK ===== */
let mailMasked=true;
function toggleMailMask(){
  mailMasked=!mailMasked;
  document.querySelectorAll('.mail-masked').forEach(el=>el.classList.toggle('hidden',!mailMasked));
  document.querySelectorAll('.mail-real').forEach(el=>el.classList.toggle('hidden',mailMasked));
}
let linkMasked=true;
function toggleLinkMask(){
  linkMasked=!linkMasked;
  document.querySelectorAll('.link-masked').forEach(el=>el.classList.toggle('hidden',!linkMasked));
  document.querySelectorAll('.link-real').forEach(el=>el.classList.toggle('hidden',linkMasked));
}

/* ===== COPY ===== */
function copyToClipboard(text){
  navigator.clipboard.writeText(text).then(()=>showToast('Đã copy!')).catch(()=>{});
}

/* ===== OTP ===== */
function otpNext(el,idx){
  el.value=el.value.replace(/\D/g,'');
  if(el.value&&idx<5) document.getElementById('otp-'+(idx+1)).focus();
}
function checkSecCode(){
  const code=[0,1,2,3,4,5].map(i=>document.getElementById('otp-'+i).value).join('');
  if(code.length<6) return;
  const res=document.getElementById('sec-result');
  res.textContent='Đang kiểm tra...';res.style.color='#666';

  const fd = new FormData();
  fd.append('code', code);
  fetch('/api/check_security.php', {method:'POST', body:fd})
    .then(r=>r.json())
    .then(data=>{
      res.textContent = data.message;
      res.style.color = data.valid ? '#00ff88' : '#ef4444';
    })
    .catch(()=>{
      res.textContent = '❌ Lỗi kết nối';
      res.style.color = '#ef4444';
    });
}

/* ===== TOOLS ===== */
const openTools=new Set();

function initTools(){
  const list=document.getElementById('tools-list');
  if(!list) return;
  list.innerHTML='';
  TOOLS_CONFIG.forEach(tool=>{
    const isOpen=openTools.has(tool.id);
    const wrapper=document.createElement('div');
    wrapper.id='tool-wrapper-'+tool.id;
    const priceStr = tool.price > 0 ? ` (${Number(tool.price).toLocaleString('vi-VN')}đ/lần)` : ' (Miễn phí)';
    wrapper.innerHTML=`
      <button onclick="toggleTool('${tool.id}')"
              class="w-full flex items-center justify-between p-4 rounded-xl border text-sm transition-all"
              style="background:${isOpen?tool.color+'08':'rgba(0,0,0,.3)'};border-color:${isOpen?tool.color+'30':'rgba(255,255,255,.06)'};color:#fff;box-shadow:${isOpen?'0 0 15px '+tool.color+'10':'none'};"
              id="tool-btn-${tool.id}">
        <div class="flex items-center gap-3">
          <div class="w-2 h-2 rounded-full flex-shrink-0" style="background:${tool.color};box-shadow:0 0 6px ${tool.color};"></div>
          <span>${tool.name}${priceStr}</span>
        </div>
        <svg class="w-4 h-4 chevron${isOpen?' open':''}" id="chevron-${tool.id}" viewBox="0 0 24 24" fill="none" stroke="${tool.color}" stroke-width="2"><polyline points="6 9 12 15 18 9"/></svg>
      </button>
      <div class="tool-panel${isOpen?' open':''}" id="panel-${tool.id}">
        <div class="mx-2 rounded-b-xl border-x border-b p-4" style="background:${tool.color}05;border-color:${tool.color}20;">
          ${getToolContent(tool)}
        </div>
      </div>`;
    list.appendChild(wrapper);
  });
}

function toggleTool(id){
  const tool=TOOLS_CONFIG.find(t=>t.id===id);
  const panel=document.getElementById('panel-'+id);
  const btn=document.getElementById('tool-btn-'+id);
  const chevron=document.getElementById('chevron-'+id);
  if(openTools.has(id)){
    openTools.delete(id);panel.classList.remove('open');chevron.classList.remove('open');
    btn.style.background='rgba(0,0,0,.3)';btn.style.borderColor='rgba(255,255,255,.06)';btn.style.boxShadow='none';
  } else {
    openTools.add(id);panel.classList.add('open');chevron.classList.add('open');
    btn.style.background=tool.color+'08';btn.style.borderColor=tool.color+'30';btn.style.boxShadow='0 0 15px '+tool.color+'10';
  }
}

function getToolContent(tool){
  const c=tool.color;
  const resultId = 'result-'+tool.id;
  
  // check_password tool
  if(tool.id==='check_password') return `<div class="space-y-3">
    <div class="p-3 rounded-lg border" style="background:rgba(6,182,212,.08);border-color:rgba(6,182,212,.2);">
      <p class="text-xs" style="color:#06b6d4;">🔍 Hệ thống sẽ truy xuất & hiển thị mật khẩu tài khoản</p>
    </div>
    <button onclick="useTool('check_password')" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">KIỂM TRA MẬT KHẨU</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
    
  if(tool.id==='token_login') return `<div class="space-y-3">
    <label class="text-xs" style="color:${c};">Nhập token để đăng nhập:</label>
    <input id="input-token" type="text" placeholder="Paste access token..." class="w-full rounded-lg px-3 py-2.5 text-white text-xs outline-none" style="background:#050510;border:1px solid ${c}30;"/>
    <button onclick="useTool('token_login')" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">ĐĂNG NHẬP</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='link_manage') return `<div class="space-y-3">
    <div class="flex gap-2 flex-wrap">
      <select id="link-platform" class="flex-1 rounded-lg px-3 py-2 text-xs outline-none" style="background:#050510;border:1px solid ${c}30;color:#999;"><option>Google</option><option>Facebook</option><option>Twitter</option><option>VKontakte</option></select>
      <select id="link-action" class="rounded-lg px-3 py-2 text-xs outline-none" style="background:#050510;border:1px solid ${c}30;color:#999;"><option>Gắn</option><option>Gỡ</option></select>
    </div>
    <button onclick="useTool('link_manage',{platform:document.getElementById('link-platform').value,action:document.getElementById('link-action').value})" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">THỰC HIỆN</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='mail_manage') return `<div class="space-y-3">
    <input id="input-mail" type="email" placeholder="Email xác thực mới..." class="w-full rounded-lg px-3 py-2.5 text-white text-xs outline-none" style="background:#050510;border:1px solid ${c}30;"/>
    <div class="flex gap-2 flex-wrap">
      <button onclick="useTool('mail_manage',{mail_action:'Gắn'})" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">GẮN MAIL</button>
      <button onclick="useTool('mail_manage',{mail_action:'Gỡ'})" class="px-4 py-2 rounded-lg text-xs" style="background:rgba(239,68,68,.1);color:#ef4444;border:1px solid rgba(239,68,68,.3);">GỠ MAIL</button>
    </div>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='block_otp') return `<div class="space-y-3">
    <div class="flex items-center justify-between p-3 rounded-lg border" style="background:rgba(245,158,11,.08);border-color:rgba(245,158,11,.2);">
      <span class="text-sm" style="color:#f59e0b;">Chặn mã xác thực OTP</span>
    </div>
    <div class="flex gap-2 flex-wrap">
      <button onclick="useTool('block_otp')" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">KÍCH HOẠT CHẶN</button>
    </div>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='otp_receive') return `<div class="space-y-3">
    <p class="text-xs" style="color:#555;">Nhận mã OTP qua SMS hoặc email đã liên kết</p>
    <button onclick="useTool('otp_receive')" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">GỬI MÃ OTP</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='spam_login') return `<div class="space-y-3">
    <input id="spam-uid" type="text" placeholder="UID mục tiêu..." class="w-full rounded-lg px-3 py-2.5 text-white text-xs outline-none" style="background:#050510;border:1px solid ${c}30;"/>
    <input id="spam-count" type="number" placeholder="Số lần spam (tối đa 999)..." class="w-full rounded-lg px-3 py-2.5 text-white text-xs outline-none" style="background:#050510;border:1px solid ${c}30;"/>
    <button onclick="useTool('spam_login',{target_uid:document.getElementById('spam-uid').value,spam_count:document.getElementById('spam-count').value})" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">BẮT ĐẦU SPAM</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  if(tool.id==='ban_7day') return `<div class="space-y-3">
    <input id="ban-uid" type="text" placeholder="UID cần ban..." class="w-full rounded-lg px-3 py-2.5 text-white text-xs outline-none" style="background:#050510;border:1px solid ${c}30;"/>
    <div class="flex items-center gap-2 p-2 rounded border" style="border-color:rgba(249,115,22,.2);background:rgba(249,115,22,.08);">
      <svg class="w-4 h-4 flex-shrink-0" viewBox="0 0 24 24" fill="none" stroke="#f97316" stroke-width="2"><path d="M10.29 3.86L1.82 18a2 2 0 0 0 1.71 3h16.94a2 2 0 0 0 1.71-3L13.71 3.86a2 2 0 0 0-3.42 0z"/><line x1="12" y1="9" x2="12" y2="13"/><line x1="12" y1="17" x2="12.01" y2="17"/></svg>
      <span class="text-xs" style="color:#f97316;">Chức năng này sẽ ban tài khoản trong 7 ngày</span>
    </div>
    <button onclick="useTool('ban_7day',{target_uid:document.getElementById('ban-uid').value})" class="px-4 py-2 rounded-lg text-xs" style="background:${c}30;color:${c};border:1px solid ${c}40;">THỰC HIỆN BAN</button>
    <div id="${resultId}" class="text-xs mt-2" style="color:#666;"></div></div>`;
  
  return '';
}

/* Use tool via AJAX */
function useTool(toolId, extra={}) {
  const resultEl = document.getElementById('result-'+toolId);
  if(resultEl) { resultEl.innerHTML='<span class="spinner"></span> Đang xử lý...'; resultEl.style.color='#f59e0b'; }

  const fd = new FormData();
  fd.append('tool_id', toolId);
  for(const k in extra) fd.append(k, extra[k]);

  fetch('/api/use_tool.php', {method:'POST', body:fd})
    .then(r=>r.json())
    .then(data=>{
      if(data.status==='success'){
        if(resultEl){ resultEl.innerHTML=data.message + (data.result?.detail ? '<br><span style="color:#999;">'+data.result.detail+'</span>' : ''); resultEl.style.color='#00ff88'; }
        // Update wallet display
        if(data.new_balance!==undefined){
          document.getElementById('wallet-balance').textContent=Number(data.new_balance).toLocaleString('vi-VN')+'đ';
          document.getElementById('tools-wallet-balance').textContent=Number(data.new_balance).toLocaleString('vi-VN')+'đ';
        }
        showToast(data.message);
      } else {
        if(resultEl){ resultEl.textContent='❌ '+data.message; resultEl.style.color='#ef4444'; }
        showToast(data.message, 'error');
      }
    })
    .catch(()=>{
      if(resultEl){ resultEl.textContent='❌ Lỗi kết nối'; resultEl.style.color='#ef4444'; }
    });
}

/* Init tools on page load */
if(IS_LOGGED_IN) initTools();

/* ===== PRICING MODAL ===== */
const PLANS=[
  {name:'Check MXT & LK',subtitle:'Vĩnh Viễn: 299.000đ',price:'49.000đ/lần',color:'#00ff88',features:['Tra cứu mail xác thực','Tra cứu liên kết ẩn','Hỗ trợ 24/7','Bảo hành trọn đời']},
  {name:'Gỡ & Gắn MXT',subtitle:'Vĩnh Viễn: 699.000đ',price:'299.000đ',color:'#7c3aed',popular:true,features:['Gỡ MXT nhanh chóng & tiện lợi','Gỡ + Gắn ngay cả khi acc bị khóa','Không cần log vào acc','Hỗ trợ 24/7']},
  {name:'Spam log',subtitle:'Vĩnh Viễn: 649.000đ',price:'139.000đ',color:'#f59e0b',features:['Spam Đăng Nhập 24/24','Ngăn người khác đăng nhập','Spam lên đến 15 ngày','Dashboard quản lí spam']},
  {name:'Gắn & Gỡ liên kết',subtitle:'Vĩnh Viễn: liên hệ',price:'Liên hệ',color:'#06b6d4',features:['Gắn/Gỡ liên kết theo nhu cầu','Thao tác khi acc bị khóa','Hỗ trợ 24/7']},
  {name:'Dò mã bảo mật',subtitle:'Vĩnh Viễn: 679.000đ',price:'679.000đ',color:'#10b981',features:['Dò mã bảo mật nhanh chóng','Giải pháp an toàn','Hỗ trợ 24/7']},
  {name:'Ban 7 ngày',subtitle:'Vĩnh Viễn: 699.000đ',price:'79.000đ/lần',color:'#ef4444',features:['Ban acc bằng access token','Bảo vệ tài khoản','Hỗ trợ 24/7']},
];

function buildPricingGrid(){
  const grid=document.getElementById('pricing-grid');grid.innerHTML='';
  PLANS.forEach(plan=>{
    const card=document.createElement('div');
    card.className='relative rounded-xl p-5 border transition-all hover:scale-[1.02]';
    card.style.cssText=`background:linear-gradient(135deg,${plan.color}08 0%,rgba(0,0,0,.6) 100%);border-color:${plan.color}25;${plan.popular?'box-shadow:0 0 20px '+plan.color+'20':''}`;
    const featHTML=plan.features.map(f=>`<li class="flex items-start gap-2"><svg class="w-4 h-4 flex-shrink-0 mt-0.5" viewBox="0 0 24 24" fill="none" stroke="${plan.color}" stroke-width="2"><polyline points="20 6 9 17 4 12"/></svg><span class="text-sm leading-snug" style="color:#999;">${f}</span></li>`).join('');
    card.innerHTML=`${plan.popular?`<div class="absolute -top-3 left-1/2 -translate-x-1/2 px-4 py-1 rounded-full text-xs font-bold" style="background:${plan.color};color:#000;">PHỔ BIẾN NHẤT</div>`:''}<div class="mb-4"><h3 class="font-bold text-white text-lg">${plan.name}</h3><p class="text-xs mt-0.5" style="color:${plan.color};">${plan.subtitle}</p></div><ul class="space-y-2 mb-5">${featHTML}</ul><div class="border-t pt-4" style="border-color:${plan.color}20;"><div class="font-bold text-xl" style="color:${plan.color};">${plan.price}</div><button onclick="closePricing();openPayment()" class="mt-3 w-full py-2.5 rounded-lg text-sm tracking-wider transition-all hover:opacity-90" style="background:linear-gradient(135deg,${plan.color}40,${plan.color}20);border:1px solid ${plan.color}50;color:${plan.color};">MUA NGAY</button></div>`;
    grid.appendChild(card);
  });
}
document.getElementById('btn-pricing')?.addEventListener('click',()=>{buildPricingGrid();document.getElementById('pricing-modal').classList.remove('hidden');});
document.getElementById('pricing-modal')?.addEventListener('click',closePricing);
function closePricing(){document.getElementById('pricing-modal').classList.add('hidden');}

/* ===== SCRIPT NẠP THẺ (ĐƯỢC GIỮ LẠI ĐỂ KHÔNG LỖI) ===== */
const PROVIDERS=[
  {id:'VIETTEL',name:'Viettel',color:'#e4002b',amounts:[10000,20000,50000,100000,200000,500000]},
  {id:'GARENA',name:'Garena',color:'#ff6600',amounts:[50000,100000,200000,500000,1000000]},
  {id:'MOBIFONE',name:'MobiFone',color:'#009639',amounts:[10000,20000,50000,100000,200000,500000]},
  {id:'VINAPHONE',name:'VinaPhone',color:'#0072bc',amounts:[10000,20000,50000,100000,200000,500000]},
  {id:'VIETNAMOBILE',name:'Vietnamobile',color:'#ff0099',amounts:[10000,20000,50000,100000]},
  {id:'ZING',name:'Zing',color:'#00b4d8',amounts:[10000,20000,50000,100000]},
];
let currentProvider=PROVIDERS[0];let selectedAmount=0;let payStatus='idle';let _pollTimer=null;let showProviders=false;
function applyProvider(p){} function renderAmounts(){} function renderProviderDropdown(){} function toggleProviders(){} function setShowProviders(show){} function submitPayment(){} function startCardPolling(requestId){} function updateWalletDisplay(balance){} function renderPayStatus(msg='',polling=false){} function resetPayment(){}

function openPayment(){
  clearInterval(_pollTimer);
  // Đoạn dưới đã được thêm điều kiện để không bị lỗi trên giao diện QR mới
  if(document.getElementById('provider-btn')) {
      applyProvider(PROVIDERS[0]);renderProviderDropdown();renderAmounts();
      payStatus='idle';renderPayStatus();
      if(document.getElementById('card-serial')) document.getElementById('card-serial').value='';
      if(document.getElementById('card-code')) document.getElementById('card-code').value='';
  }
  document.getElementById('payment-modal').classList.remove('hidden');
}

document.getElementById('btn-payment')?.addEventListener('click',openPayment);
document.getElementById('payment-modal')?.addEventListener('click',function(e){if(e.target===this){clearInterval(_pollTimer);closePayment();}});
function closePayment(){document.getElementById('payment-modal').classList.add('hidden');setShowProviders(false);}
document.addEventListener('keydown',e=>{if(e.key==='Escape'){closePricing();closePayment();}});
</script>

<style>
@keyframes zalo-ping {
  0%   { transform: scale(1);   opacity: .7; }
  80%  { transform: scale(1.9); opacity: 0; }
  100% { transform: scale(1.9); opacity: 0; }
}
@keyframes zalo-bounce {
  0%,100% { transform: translateY(0); }
  50%      { transform: translateY(-6px); }
}
.zalo-float {
  position: fixed;
  bottom: 28px;
  right: 24px;
  z-index: 9999;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 6px;
}
.zalo-float-btn {
  width: 56px;
  height: 56px;
  border-radius: 50%;
  background: linear-gradient(135deg, #0068ff, #0096ff);
  box-shadow: 0 4px 20px rgba(0,104,255,.5);
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  animation: zalo-bounce 2.5s ease-in-out infinite;
  transition: transform .2s, box-shadow .2s;
  text-decoration: none;
  position: relative;
}
.zalo-float-btn:hover {
  transform: scale(1.12) translateY(-2px) !important;
  box-shadow: 0 6px 28px rgba(0,104,255,.7);
  animation-play-state: paused;
}
.zalo-float-btn::before {
  content: '';
  position: absolute;
  inset: 0;
  border-radius: 50%;
  background: rgba(0,104,255,.5);
  animation: zalo-ping 1.8s ease-out infinite;
}
.zalo-float-label {
  background: rgba(0,104,255,.85);
  backdrop-filter: blur(8px);
  color: #fff;
  font-size: 11px;
  font-weight: 600;
  letter-spacing: .04em;
  padding: 3px 10px;
  border-radius: 20px;
  white-space: nowrap;
  box-shadow: 0 2px 10px rgba(0,104,255,.4);
}
</style>

<div class="zalo-float">
  <a href="zalo.me/84386265304"
     target="_blank" rel="noopener"
     class="zalo-float-btn"
     title="Liên hệ Zalo hỗ trợ"
     id="zalo-float-link">
    <svg width="30" height="30" viewBox="0 0 48 48" fill="none">
      <rect width="48" height="48" rx="24" fill="white" fill-opacity=".15"/>
      <path fill="white" d="M24 6C14.059 6 6 14.059 6 24c0 3.252.88 6.3 2.416 8.916L6 42l9.322-2.396A17.906 17.906 0 0 0 24 42c9.941 0 18-8.059 18-18S33.941 6 24 6zm0 32.4a14.326 14.326 0 0 1-7.308-2.006l-.524-.31-5.42 1.544 1.553-5.305-.342-.545A14.298 14.298 0 0 1 9.6 24C9.6 15.936 15.936 9.6 24 9.6S38.4 15.936 38.4 24 32.064 38.4 24 38.4zm7.93-10.526c-.434-.217-2.567-1.268-2.965-1.413-.398-.144-.689-.216-.979.216-.29.433-1.124 1.412-1.378 1.701-.253.288-.507.324-.94.108-.434-.216-1.832-.675-3.49-2.154-1.29-1.15-2.16-2.57-2.413-3.002-.252-.433-.027-.667.19-.882.196-.193.433-.506.65-.757.217-.253.289-.434.433-.72.145-.289.072-.54-.035-.757-.108-.217-.98-2.364-1.343-3.237-.353-.851-.714-.736-.98-.75-.253-.012-.543-.015-.832-.015-.29 0-.757.109-1.153.54-.397.43-1.51 1.477-1.51 3.6 0 2.123 1.546 4.174 1.762 4.462.217.29 3.044 4.649 7.374 6.518 1.03.445 1.836.711 2.462.91 1.034.328 1.977.282 2.72.171.83-.124 2.567-1.05 2.93-2.063.362-1.013.362-1.881.253-2.063-.108-.18-.398-.289-.832-.505z"/>
    </svg>
  </a>
  <span class="zalo-float-label">Hỗ trợ Zalo</span>
</div>

</body>
</html>
