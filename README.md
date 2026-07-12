 · SVG
<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" font-family="'JetBrains Mono','Fira Code','SFMono-Regular',Consolas,monospace">
<defs>
<clipPath id="outerClip"><rect x="0" y="0" width="1180" height="610" rx="28" ry="28"/></clipPath>
<clipPath id="leftClip"><rect x="24" y="24" width="420" height="562" rx="20" ry="20"/></clipPath>
<clipPath id="rightClip"><rect x="468" y="24" width="688" height="562" rx="20" ry="20"/></clipPath>
<radialGradient id="bgBase" cx="20%" cy="10%" r="90%">
      <stop offset="0%" stop-color="#F1F6FB"/>
      <stop offset="100%" stop-color="#FFFFFF"/>
    </radialGradient>
<radialGradient id="blobPurple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#2563EB" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blobCyan" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#06B6D4" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="blobEmerald" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>
<filter id="noise" x="0" y="0" width="100%" height="100%">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch" result="noise"/>
      <feColorMatrix in="noise" type="matrix" values="0 0 0 0 1  0 0 0 0 1  0 0 0 0 1  0 0 0 0.02 0"/>
    </filter>
<linearGradient id="glassPanel" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#F8FAFC" stop-opacity="0.92"/>
      <stop offset="100%" stop-color="#F8FAFC" stop-opacity="0.72"/>
    </linearGradient>
    <linearGradient id="glassReflect" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0.5"/>
      <stop offset="35%" stop-color="#FFFFFF" stop-opacity="0"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0"/>
    </linearGradient>
<linearGradient id="borderShimmer" x1="0%" y1="0%" x2="100%" y2="0%" gradientTransform="rotate(0)">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0"/>
      <stop offset="45%" stop-color="#06B6D4" stop-opacity="0.9"/>
      <stop offset="55%" stop-color="#06B6D4" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
      <animateTransform attributeName="gradientTransform" type="rotate" from="0 0.5 0.5" to="360 0.5 0.5" dur="6s" repeatCount="indefinite"/>
    </linearGradient>
<linearGradient id="accentGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2563EB"/>
      <stop offset="50%" stop-color="#06B6D4"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>
<linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="100%" gradientTransform="translate(0,0)">
      <stop offset="0%" stop-color="#2563EB"/><stop offset="50%" stop-color="#06B6D4"/><stop offset="100%" stop-color="#2563EB"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="-0.6 0; 0.6 0; -0.6 0" dur="6s" repeatCount="indefinite"/>
    </linearGradient>
<filter id="glowCyanViolet" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="3.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glowSoft" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="panelShadow" x="-30%" y="-30%" width="160%" height="160%">
      <feDropShadow dx="0" dy="10" stdDeviation="18" flood-color="#000000" flood-opacity="0.12"/>
    </filter>
<linearGradient id="scanline" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#FFFFFF" stop-opacity="0"/>
      <stop offset="50%" stop-color="#06B6D4" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#FFFFFF" stop-opacity="0"/>
    </linearGradient>
<linearGradient id="pillFill" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#2563EB" stop-opacity="0.16"/>
      <stop offset="100%" stop-color="#06B6D4" stop-opacity="0.16"/>
    </linearGradient>
</defs>
<style>
      .pill { transition: transform 0.25s ease, filter 0.25s ease; transform-box: fill-box; transform-origin: center; }
      .pill:hover { transform: scale(1.08); filter: drop-shadow(0 0 10px #06B6D4); }
      .social:hover .socialGlow { opacity: 1; }
      .social { transform-box: fill-box; transform-origin: center; transition: transform 0.2s ease; }
      .social:hover { transform: translateY(-3px); }
      text { letter-spacing: 0.2px; }
    </style>
<g clip-path="url(#outerClip)">
<rect x="0" y="0" width="1180" height="610" fill="url(#bgBase)"/>
<rect x="0" y="0" width="1180" height="610" filter="url(#noise)" opacity="0.5"/>
<circle cx="150" cy="120" r="220" fill="url(#blobPurple)">
      <animate attributeName="cx" values="150;230;150" dur="14s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="120;180;120" dur="16s" repeatCount="indefinite"/>
    </circle>
    <circle cx="950" cy="480" r="260" fill="url(#blobCyan)">
      <animate attributeName="cx" values="950;860;950" dur="18s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="480;420;480" dur="15s" repeatCount="indefinite"/>
    </circle>
    <circle cx="700" cy="60" r="180" fill="url(#blobEmerald)">
      <animate attributeName="cx" values="700;760;700" dur="12s" repeatCount="indefinite"/>
    </circle>
<circle cx="248" cy="45" r="2.0" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.2s" begin="0.7s" repeatCount="indefinite"/><animate attributeName="cy" values="45;15;45" dur="6.8s" begin="0.7s" repeatCount="indefinite"/></circle><circle cx="229" cy="578" r="1.1" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.1s" begin="0.1s" repeatCount="indefinite"/><animate attributeName="cy" values="578;548;578" dur="7.9s" begin="0.1s" repeatCount="indefinite"/></circle><circle cx="467" cy="258" r="1.7" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="4.1s" begin="1.0s" repeatCount="indefinite"/><animate attributeName="cy" values="258;228;258" dur="5.4s" begin="1.0s" repeatCount="indefinite"/></circle><circle cx="1136" cy="449" r="1.3" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.9s" begin="4.0s" repeatCount="indefinite"/><animate attributeName="cy" values="449;419;449" dur="9.0s" begin="4.0s" repeatCount="indefinite"/></circle><circle cx="33" cy="183" r="2.0" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.7s" begin="0.8s" repeatCount="indefinite"/><animate attributeName="cy" values="183;153;183" dur="7.4s" begin="0.8s" repeatCount="indefinite"/></circle><circle cx="709" cy="124" r="1.1" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="4.5s" begin="4.2s" repeatCount="indefinite"/><animate attributeName="cy" values="124;94;124" dur="5.8s" begin="4.2s" repeatCount="indefinite"/></circle><circle cx="561" cy="64" r="2.0" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.7s" begin="4.9s" repeatCount="indefinite"/><animate attributeName="cy" values="64;34;64" dur="8.7s" begin="4.9s" repeatCount="indefinite"/></circle><circle cx="795" cy="100" r="1.8" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="8.1s" begin="3.1s" repeatCount="indefinite"/><animate attributeName="cy" values="100;70;100" dur="10.6s" begin="3.1s" repeatCount="indefinite"/></circle><circle cx="760" cy="216" r="2.0" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="4.2s" begin="1.1s" repeatCount="indefinite"/><animate attributeName="cy" values="216;186;216" dur="5.5s" begin="1.1s" repeatCount="indefinite"/></circle><circle cx="612" cy="101" r="2.2" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="8.3s" begin="1.9s" repeatCount="indefinite"/><animate attributeName="cy" values="101;71;101" dur="10.8s" begin="1.9s" repeatCount="indefinite"/></circle><circle cx="948" cy="393" r="1.2" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.8s" begin="3.4s" repeatCount="indefinite"/><animate attributeName="cy" values="393;363;393" dur="7.5s" begin="3.4s" repeatCount="indefinite"/></circle><circle cx="166" cy="195" r="1.7" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.2s" begin="2.3s" repeatCount="indefinite"/><animate attributeName="cy" values="195;165;195" dur="6.8s" begin="2.3s" repeatCount="indefinite"/></circle><circle cx="572" cy="590" r="1.3" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.6s" begin="3.8s" repeatCount="indefinite"/><animate attributeName="cy" values="590;560;590" dur="7.3s" begin="3.8s" repeatCount="indefinite"/></circle><circle cx="134" cy="254" r="2.2" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="8.0s" begin="2.0s" repeatCount="indefinite"/><animate attributeName="cy" values="254;224;254" dur="10.4s" begin="2.0s" repeatCount="indefinite"/></circle><circle cx="155" cy="236" r="2.3" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.8s" begin="3.6s" repeatCount="indefinite"/><animate attributeName="cy" values="236;206;236" dur="8.9s" begin="3.6s" repeatCount="indefinite"/></circle><circle cx="455" cy="531" r="1.6" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="8.6s" begin="2.3s" repeatCount="indefinite"/><animate attributeName="cy" values="531;501;531" dur="11.1s" begin="2.3s" repeatCount="indefinite"/></circle><circle cx="562" cy="162" r="1.3" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.8s" begin="1.3s" repeatCount="indefinite"/><animate attributeName="cy" values="162;132;162" dur="8.8s" begin="1.3s" repeatCount="indefinite"/></circle><circle cx="897" cy="428" r="1.5" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="9.0s" begin="0.7s" repeatCount="indefinite"/><animate attributeName="cy" values="428;398;428" dur="11.7s" begin="0.7s" repeatCount="indefinite"/></circle><circle cx="1030" cy="113" r="2.1" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="8.3s" begin="0.8s" repeatCount="indefinite"/><animate attributeName="cy" values="113;83;113" dur="10.8s" begin="0.8s" repeatCount="indefinite"/></circle><circle cx="347" cy="452" r="1.8" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="5.9s" begin="3.0s" repeatCount="indefinite"/><animate attributeName="cy" values="452;422;452" dur="7.7s" begin="3.0s" repeatCount="indefinite"/></circle><circle cx="978" cy="561" r="1.4" fill="#10B981" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="6.8s" begin="4.7s" repeatCount="indefinite"/><animate attributeName="cy" values="561;531;561" dur="8.8s" begin="4.7s" repeatCount="indefinite"/></circle><circle cx="254" cy="569" r="2.1" fill="#2563EB" opacity="0"><animate attributeName="opacity" values="0;0.8;0" dur="7.8s" begin="1.7s" repeatCount="indefinite"/><animate attributeName="cy" values="569;539;569" dur="10.2s" begin="1.7s" repeatCount="indefinite"/></circle>
<g filter="url(#panelShadow)">
<rect x="24" y="24" width="420" height="562" rx="20" fill="url(#glassPanel)" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
</g>
<rect x="24" y="24" width="420" height="562" rx="20" fill="url(#glassReflect)"/>
<rect x="24.75" y="24.75" width="418.5" height="560.5" rx="19.3" fill="none" stroke="url(#borderShimmer)" stroke-width="1.5"/>
<g clip-path="url(#leftClip)">
<rect x="24" y="-56" width="420" height="80" fill="url(#scanline)"><animate attributeName="y" values="-56;586" dur="5s" repeatCount="indefinite"/></rect>
<g id="asciiFloat">
<animateTransform attributeName="transform" type="translate" values="0,0; 0,-7; 0,0" dur="5s" repeatCount="indefinite"/>
<text x="58" y="60" font-size="12" letter-spacing="3" fill="#475569" font-weight="600">CYBER://PORTRAIT</text>
<text xml:space="preserve" x="58" y="94" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">     .-------------.<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="0.0s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="119" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">    /  SYSTEM  BOOT  \<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="0.22s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="144" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   |   .-.     .-.   |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="0.44s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="169" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   |  ( o )   ( o )  |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="0.66s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="194" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   |   '-'     '-'   |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="0.88s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="219" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   |      \___/      |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="1.1s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="244" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">    \               /<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="1.32s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="269" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">     '-.---------.-'<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="1.54s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="294" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">       |  ONLINE  |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="1.76s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="319" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   .---'----------'---.<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="1.98s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="344" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   |  ~ DEV MODE: ON  |<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="2.2s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="369" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   '--------.---------'<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="2.42s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="394" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">        .---+---.<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="2.64s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="419" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">       [|]     [|]<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="2.86s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="444" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">       ---     ---<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="3.08s" fill="freeze"/></text>
<text xml:space="preserve" x="58" y="469" font-size="14.5" fill="url(#asciiGrad)" filter="url(#glowCyanViolet)" opacity="0">   &gt; building things_<animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="3.3s" fill="freeze"/></text>
<rect x="60" y="482" width="9" height="16" fill="#06B6D4" opacity="0"><animate attributeName="opacity" values="0;0;1;0;1;0;1;0" keyTimes="0;0.01;0.05;0.35;0.4;0.7;0.75;1" dur="1.6s" begin="3.82s" repeatCount="indefinite"/></rect>
</g>
</g>
<g filter="url(#panelShadow)">
<rect x="468" y="24" width="688" height="562" rx="20" fill="url(#glassPanel)" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
</g>
<rect x="468" y="24" width="688" height="562" rx="20" fill="url(#glassReflect)"/>
<rect x="468.75" y="24.75" width="686.5" height="560.5" rx="19.3" fill="none" stroke="url(#borderShimmer)" stroke-width="1.5"/>
<g clip-path="url(#rightClip)">
<rect x="468" y="24" width="688" height="40" fill="#EEF2F7"/>
<line x1="468" y1="64" x2="1156" y2="64" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
<circle cx="494" cy="44.0" r="6" fill="#FF5F56" opacity="0.9"/>
<circle cx="516" cy="44.0" r="6" fill="#FFBD2E" opacity="0.9"/>
<circle cx="538" cy="44.0" r="6" fill="#27C93F" opacity="0.9"/>
<text x="812.0" y="48.0" text-anchor="middle" font-size="12.5" fill="#475569">visitor@profile: ~</text>
<rect x="468" y="-56" width="688" height="80" fill="url(#scanline)"><animate attributeName="y" values="-56;586" dur="6.5s" begin="1s" repeatCount="indefinite"/></rect>
<g><clipPath id="clipGreet"><rect x="512" y="90" width="0" height="30"><animate attributeName="width" values="0;140" dur="0.6s" begin="0.2s" fill="freeze"/></rect></clipPath><text x="512" y="110" font-size="26" font-weight="700" fill="#0F172A" clip-path="url(#clipGreet)">Hi 👋</text></g>
<g><clipPath id="clipName"><rect x="512" y="128" width="0" height="32"><animate attributeName="width" values="0;340" dur="0.9s" begin="0.9s" fill="freeze"/></rect></clipPath><text x="512" y="150" font-size="24" font-weight="700" fill="url(#accentGrad)" clip-path="url(#clipName)">I'm Alex Rivera</text></g>
<g><clipPath id="clipRole0"><rect x="530" y="168" width="0" height="26"><animate attributeName="width" values="0;173;173;0;0" keyTimes="0;0.0200;0.1733;0.1933;1" dur="15.0s" begin="1.9s" repeatCount="indefinite"/></rect></clipPath><text x="512" y="186" font-size="16.5" fill="#06B6D4">&gt;<tspan dx="6" x="530" fill="#0F172A" clip-path="url(#clipRole0)">Frontend Engineer</tspan></text><rect x="530" y="170" width="8" height="19" fill="#06B6D4"><animate attributeName="x" values="530;703" keyTimes="0;0.0200" dur="15.0s" begin="1.9s" repeatCount="indefinite" calcMode="discrete" fill="freeze"/><animate attributeName="opacity" values="1;0;1;0;1;0" dur="0.8s" begin="1.9s" repeatCount="indefinite"/></rect></g>
<g><clipPath id="clipRole1"><rect x="530" y="168" width="0" height="26"><animate attributeName="width" values="0;204;204;0;0" keyTimes="0;0.0200;0.1733;0.1933;1" dur="15.0s" begin="4.9s" repeatCount="indefinite"/></rect></clipPath><text x="512" y="186" font-size="16.5" fill="#06B6D4">&gt;<tspan dx="6" x="530" fill="#0F172A" clip-path="url(#clipRole1)">Full Stack Developer</tspan></text><rect x="530" y="170" width="8" height="19" fill="#06B6D4"><animate attributeName="x" values="530;734" keyTimes="0;0.0200" dur="15.0s" begin="4.9s" repeatCount="indefinite" calcMode="discrete" fill="freeze"/><animate attributeName="opacity" values="1;0;1;0;1;0" dur="0.8s" begin="4.9s" repeatCount="indefinite"/></rect></g>
<g><clipPath id="clipRole2"><rect x="530" y="168" width="0" height="26"><animate attributeName="width" values="0;235;235;0;0" keyTimes="0;0.0200;0.1733;0.1933;1" dur="15.0s" begin="7.9s" repeatCount="indefinite"/></rect></clipPath><text x="512" y="186" font-size="16.5" fill="#06B6D4">&gt;<tspan dx="6" x="530" fill="#0F172A" clip-path="url(#clipRole2)">Open Source Contributor</tspan></text><rect x="530" y="170" width="8" height="19" fill="#06B6D4"><animate attributeName="x" values="530;765" keyTimes="0;0.0200" dur="15.0s" begin="7.9s" repeatCount="indefinite" calcMode="discrete" fill="freeze"/><animate attributeName="opacity" values="1;0;1;0;1;0" dur="0.8s" begin="7.9s" repeatCount="indefinite"/></rect></g>
<g><clipPath id="clipRole3"><rect x="530" y="168" width="0" height="26"><animate attributeName="width" values="0;112;112;0;0" keyTimes="0;0.0200;0.1733;0.1933;1" dur="15.0s" begin="10.9s" repeatCount="indefinite"/></rect></clipPath><text x="512" y="186" font-size="16.5" fill="#06B6D4">&gt;<tspan dx="6" x="530" fill="#0F172A" clip-path="url(#clipRole3)">UI Engineer</tspan></text><rect x="530" y="170" width="8" height="19" fill="#06B6D4"><animate attributeName="x" values="530;642" keyTimes="0;0.0200" dur="15.0s" begin="10.9s" repeatCount="indefinite" calcMode="discrete" fill="freeze"/><animate attributeName="opacity" values="1;0;1;0;1;0" dur="0.8s" begin="10.9s" repeatCount="indefinite"/></rect></g>
<g><clipPath id="clipRole4"><rect x="530" y="168" width="0" height="26"><animate attributeName="width" values="0;133;133;0;0" keyTimes="0;0.0200;0.1733;0.1933;1" dur="15.0s" begin="13.9s" repeatCount="indefinite"/></rect></clipPath><text x="512" y="186" font-size="16.5" fill="#06B6D4">&gt;<tspan dx="6" x="530" fill="#0F172A" clip-path="url(#clipRole4)">AI Enthusiast</tspan></text><rect x="530" y="170" width="8" height="19" fill="#06B6D4"><animate attributeName="x" values="530;663" keyTimes="0;0.0200" dur="15.0s" begin="13.9s" repeatCount="indefinite" calcMode="discrete" fill="freeze"/><animate attributeName="opacity" values="1;0;1;0;1;0" dur="0.8s" begin="13.9s" repeatCount="indefinite"/></rect></g>
<line x1="512" y1="214" x2="1112" y2="214" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
<g opacity="0" transform="translate(-14,0)"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="5.0s" fill="freeze"/><animateTransform attributeName="transform" type="translate" values="-14,0;0,0" dur="0.5s" begin="5.0s" fill="freeze"/><text x="512" y="240" font-size="14.5">📍</text><text x="540" y="240" font-size="13.5" fill="#475569">Location:</text><text x="640" y="240" font-size="13.5" fill="#0F172A">San Francisco, CA</text></g>
<g opacity="0" transform="translate(-14,0)"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="5.35s" fill="freeze"/><animateTransform attributeName="transform" type="translate" values="-14,0;0,0" dur="0.5s" begin="5.35s" fill="freeze"/><text x="512" y="266" font-size="14.5">🎓</text><text x="540" y="266" font-size="13.5" fill="#475569">Education:</text><text x="640" y="266" font-size="13.5" fill="#0F172A">B.S. Computer Science</text></g>
<g opacity="0" transform="translate(-14,0)"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="5.7s" fill="freeze"/><animateTransform attributeName="transform" type="translate" values="-14,0;0,0" dur="0.5s" begin="5.7s" fill="freeze"/><text x="512" y="292" font-size="14.5">🎯</text><text x="540" y="292" font-size="13.5" fill="#475569">Current Focus:</text><text x="662" y="292" font-size="13.5" fill="#0F172A">Building developer tools</text></g>
<g opacity="0" transform="translate(-14,0)"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="6.05s" fill="freeze"/><animateTransform attributeName="transform" type="translate" values="-14,0;0,0" dur="0.5s" begin="6.05s" fill="freeze"/><text x="512" y="318" font-size="14.5">🌐</text><text x="540" y="318" font-size="13.5" fill="#475569">Portfolio:</text><text x="640" y="318" font-size="13.5" fill="#0F172A">yourwebsite.dev</text></g>
<g opacity="0" transform="translate(-14,0)"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="6.4s" fill="freeze"/><animateTransform attributeName="transform" type="translate" values="-14,0;0,0" dur="0.5s" begin="6.4s" fill="freeze"/><text x="512" y="344" font-size="14.5">✉</text><text x="540" y="344" font-size="13.5" fill="#475569">Email:</text><text x="640" y="344" font-size="13.5" fill="#0F172A">hello@yourwebsite.dev</text></g>
<line x1="512" y1="386" x2="1112" y2="386" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
<text x="512" y="408" font-size="12.5" letter-spacing="2.5" fill="#475569" font-weight="600">SKILLS</text>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="6.8s" fill="freeze"/><rect x="512" y="424" width="53" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="538" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">React</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="6.92s" fill="freeze"/><rect x="574.0" y="424" width="68" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="608" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">Next.js</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.04s" fill="freeze"/><rect x="651.2" y="424" width="68" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="685" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">Node.js</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.16s" fill="freeze"/><rect x="728.4000000000001" y="424" width="91" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="774" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">TypeScript</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.279999999999999s" fill="freeze"/><rect x="828.4000000000001" y="424" width="76" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="866" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">Tailwind</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.3999999999999995s" fill="freeze"/><rect x="913.2" y="424" width="61" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="944" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">Python</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.52s" fill="freeze"/><rect x="982.8000000000001" y="424" width="61" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="1013" y="442" text-anchor="middle" font-size="12.5" fill="#0F172A">Docker</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.64s" fill="freeze"/><rect x="512" y="461" width="76" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="550" y="480" text-anchor="middle" font-size="12.5" fill="#0F172A">Postgres</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.76s" fill="freeze"/><rect x="596.8" y="461" width="38" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="616" y="480" text-anchor="middle" font-size="12.5" fill="#0F172A">AWS</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="7.88s" fill="freeze"/><rect x="643.5999999999999" y="461" width="38" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="662" y="480" text-anchor="middle" font-size="12.5" fill="#0F172A">Git</text></g>
<g class="pill" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="8.0s" fill="freeze"/><rect x="690.3999999999999" y="461" width="53" height="28" rx="15" fill="url(#pillFill)" stroke="#06B6D4" stroke-opacity="0.55" stroke-width="1"/><text x="717" y="480" text-anchor="middle" font-size="12.5" fill="#0F172A">Figma</text></g>
<line x1="512" y1="515" x2="1112" y2="515" stroke="rgba(15,23,42,0.08)" stroke-width="1"/>
<g class="social" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="8.2s" fill="freeze"/><circle class="socialGlow" cx="528" cy="543" r="20" fill="none" stroke="#06B6D4" stroke-opacity="0" stroke-width="1.5"><animate attributeName="stroke-opacity" values="0;0.55;0" dur="2.4s" begin="8.2s" repeatCount="indefinite"/></circle><circle cx="528" cy="543" r="16" fill="#EEF2F7" stroke="rgba(15,23,42,0.08)" stroke-width="1" filter="url(#glowSoft)"/><text x="528" y="548" text-anchor="middle" font-size="11.5" font-weight="700" fill="url(#accentGrad)">G</text><text x="550" y="548" font-size="12.5" fill="#475569">GitHub</text></g>
<g class="social" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="8.35s" fill="freeze"/><circle class="socialGlow" cx="658" cy="543" r="20" fill="none" stroke="#06B6D4" stroke-opacity="0" stroke-width="1.5"><animate attributeName="stroke-opacity" values="0;0.55;0" dur="2.4s" begin="8.35s" repeatCount="indefinite"/></circle><circle cx="658" cy="543" r="16" fill="#EEF2F7" stroke="rgba(15,23,42,0.08)" stroke-width="1" filter="url(#glowSoft)"/><text x="658" y="548" text-anchor="middle" font-size="11.5" font-weight="700" fill="url(#accentGrad)">L</text><text x="680" y="548" font-size="12.5" fill="#475569">LinkedIn</text></g>
<g class="social" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="8.5s" fill="freeze"/><circle class="socialGlow" cx="788" cy="543" r="20" fill="none" stroke="#06B6D4" stroke-opacity="0" stroke-width="1.5"><animate attributeName="stroke-opacity" values="0;0.55;0" dur="2.4s" begin="8.5s" repeatCount="indefinite"/></circle><circle cx="788" cy="543" r="16" fill="#EEF2F7" stroke="rgba(15,23,42,0.08)" stroke-width="1" filter="url(#glowSoft)"/><text x="788" y="548" text-anchor="middle" font-size="11.5" font-weight="700" fill="url(#accentGrad)">T</text><text x="810" y="548" font-size="12.5" fill="#475569">Twitter</text></g>
<g class="social" opacity="0"><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.001;1" dur="0.01s" begin="8.649999999999999s" fill="freeze"/><circle class="socialGlow" cx="918" cy="543" r="20" fill="none" stroke="#06B6D4" stroke-opacity="0" stroke-width="1.5"><animate attributeName="stroke-opacity" values="0;0.55;0" dur="2.4s" begin="8.649999999999999s" repeatCount="indefinite"/></circle><circle cx="918" cy="543" r="16" fill="#EEF2F7" stroke="rgba(15,23,42,0.08)" stroke-width="1" filter="url(#glowSoft)"/><text x="918" y="548" text-anchor="middle" font-size="11.5" font-weight="700" fill="url(#accentGrad)">P</text><text x="940" y="548" font-size="12.5" fill="#475569">Portfolio</text></g>
</g>
</g>
<rect x="1" y="1" width="1178" height="608" rx="27" fill="none" stroke="rgba(15,23,42,0.08)" stroke-width="1.5"/>
</svg>
