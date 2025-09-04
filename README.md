<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Happy Teachers' Day, My Love</title>
  <style>
    :root { --pink: #ffd6e7; --text: #7a004c; --card: #fff5fa; }
    html, body { height: 100%; margin:0; }
    body { background: var(--pink); display: grid; place-items: center; font-family: ui-rounded, system-ui, -apple-system, Segoe UI, Roboto, Arial, "Apple Color Emoji", "Segoe UI Emoji"; color: var(--text); }
    .message { position: relative; background: var(--card); padding: 44px 36px; border-radius: 32px; box-shadow: 0 20px 50px rgba(0,0,0,.18); text-align: center; width: min(92vw, 920px); }
    h1 { margin: 0 0 10px; font-size: clamp(34px, 6.8vw, 72px); line-height: 1.1; }
    p { margin: 0; font-size: clamp(14px, 2.6vw, 18px); opacity: .85; }
    .flowers { position: absolute; inset: -12px; pointer-events: none; }
    .flower { position: absolute; font-size: clamp(26px, 4vw, 42px); filter: drop-shadow(0 4px 4px rgba(0,0,0,.1)); }
    .f1{ top: 6%; left: 8%; } .f2{ top: 8%; right: 10%; } .f3{ top: 42%; left: 4%; }
    .f4{ top: 42%; right: 4%; } .f5{ bottom: 8%; left: 10%; } .f6{ bottom: 6%; right: 8%; }
    .f7{ top: 18%; left: 46%; } .f8{ bottom: 18%; left: 46%; }
    @keyframes drift { 0%{ transform: translateY(0);} 50%{ transform: translateY(-6px);} 100%{ transform: translateY(0);} }
    .flower { animation: drift 4.2s ease-in-out infinite; }
  </style>
</head>
<body>
  <div class="message" role="group" aria-label="Teachers Day greeting with flowers">
    <div class="flowers" aria-hidden="true">
      <span class="flower f1">🌸</span>
      <span class="flower f2">🌺</span>
      <span class="flower f3">💐</span>
      <span class="flower f4">🌷</span>
      <span class="flower f5">🌼</span>
      <span class="flower f6">🌹</span>
      <span class="flower f7">💮</span>
      <span class="flower f8">🌻</span>
    </div>
    <h1>Happy Teachers' Day, My Love</h1>
    <p>Thank you for teaching with your heart. You make the world bloom. ♡</p>
  </div>
</body>
</html>
