```aura width=860 height=200
<div style={{
  width: '100%', height: '100%', background: '#050508',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)', boxSizing: 'border-box'
}}>
  <style>{`
      @keyframes glow-move-1 { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(180px, -30px) scale(1.3); } }
      @keyframes glow-move-2 { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(-150px, 40px) scale(1.2); } }
      @keyframes glow-move-3 { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(120px, 50px) scale(1.4); } }
      #b1-g1 { animation: glow-move-1 9s ease-in-out infinite; }
      #b1-g2 { animation: glow-move-2 11s ease-in-out infinite; }
      #b1-g3 { animation: glow-move-3 7s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bg1-1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="60%" stopColor="rgba(147,51,234,0.4)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="bg1-2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="65%" stopColor="rgba(37,99,235,0.35)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="bg1-3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(236,72,153,0.85)" />
        <stop offset="70%" stopColor="rgba(219,39,119,0)" />
      </radialGradient>
    </defs>
    <circle id="b1-g1" cx="200" cy="180" r="180" fill="url(#bg1-1)" />
    <circle id="b1-g2" cx="550" cy="190" r="170" fill="url(#bg1-2)" />
    <circle id="b1-g3" cx="380" cy="100" r="140" fill="url(#bg1-3)" />
  </svg>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:48, gap:8, position: 'relative' }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Leha <span style={{ fontSize: 18, color: '#c084fc', marginLeft: 10, alignSelf: 'center', fontWeight: 600 }}>(root@leha)</span>
    </div>
    <div style={{ display:'flex', fontSize:14, color:'rgba(216,180,254,0.9)', fontWeight:400 }}>
      Future Cybersecurity Specialist | CTF & Reverse Engineering 💻
    </div>
    <div style={{ display:'flex', gap:8, marginTop:8 }}>
      <div style={{ padding:'5px 14px', borderRadius:20, background:'rgba(147,51,234,0.25)', border:'1px solid rgba(192,132,252,0.5)', color:'#f3e8ff', fontSize:12, fontWeight:600 }}>C++</div>
      <div style={{ padding:'5px 14px', borderRadius:20, background:'rgba(147,51,234,0.25)', border:'1px solid rgba(192,132,252,0.5)', color:'#f3e8ff', fontSize:12, fontWeight:600 }}>Python</div>
      <div style={{ padding:'5px 14px', borderRadius:20, background:'rgba(147,51,234,0.25)', border:'1px solid rgba(192,132,252,0.5)', color:'#f3e8ff', fontSize:12, fontWeight:600 }}>Assembly</div>
      <div style={{ padding:'5px 14px', borderRadius:20, background:'rgba(147,51,234,0.25)', border:'1px solid rgba(192,132,252,0.5)', color:'#f3e8ff', fontSize:12, fontWeight:600 }}>Kali Linux</div>
    </div>
  </div>
</div>
```

<br />

```aura width=860 height=140
<div style={{
  width: '100%', height: '100%', background: '#050508',
  display: 'flex', alignItems: 'center', justifyContent: 'space-around',
  borderRadius: 18, border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  boxSizing: 'border-box'
}}>
  <style>{`
      @keyframes glow-move-4 { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(220px, -25px) scale(1.4); } }
      @keyframes glow-move-5 { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(-200px, 30px) scale(1.3); } }
      @keyframes glow-move-5b { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(140px, -40px) scale(1.2); } }
      #b2-g1 { animation: glow-move-4 10s ease-in-out infinite; }
      #b2-g2 { animation: glow-move-5 8s ease-in-out infinite; }
      #b2-g3 { animation: glow-move-5b 9s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="140" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bg2-1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>
      <radialGradient id="bg2-2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
      <radialGradient id="bg2-3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(14,165,233,0.85)" />
        <stop offset="70%" stopColor="rgba(14,116,144,0)" />
      </radialGradient>
      <radialGradient id="bg2-4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(236,72,153,0.8)" />
        <stop offset="70%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle id="b2-g1" cx="200" cy="110" r="170" fill="url(#bg2-1)" />
    <circle id="b2-g2" cx="660" cy="100" r="170" fill="url(#bg2-2)" />
    <circle id="b2-g3" cx="430" cy="120" r="150" fill="url(#bg2-3)" />
    <circle cx="80" cy="50" r="110" fill="url(#bg2-4)" />
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 38, fontWeight: 800, color: '#c084fc', textShadow: '0 0 15px rgba(192,132,252,0.6)' }}>11</span>
    <span style={{ fontSize: 11, color: 'rgba(233,213,255,0.8)', letterSpacing: 1.5, fontWeight: 700 }}>REPOS</span>
  </div>
  <div style={{ width: 1, height: 50, background: 'rgba(255,255,255,0.15)', position: 'relative' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 38, fontWeight: 800, color: '#60a5fa', textShadow: '0 0 15px rgba(96,165,250,0.6)' }}>146</span>
    <span style={{ fontSize: 11, color: 'rgba(233,213,255,0.8)', letterSpacing: 1.5, fontWeight: 700 }}>STARS</span>
  </div>
  <div style={{ width: 1, height: 50, background: 'rgba(255,255,255,0.15)', position: 'relative' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 38, fontWeight: 800, color: '#fbbf24', textShadow: '0 0 15px rgba(251,191,36,0.6)' }}>2466</span>
    <span style={{ fontSize: 11, color: 'rgba(233,213,255,0.8)', letterSpacing: 1.5, fontWeight: 700 }}>COMMITS</span>
  </div>
</div>
```

<br />

```aura width=860 height=180
<div style={{
  width: '100%', height: '100%', background: '#050508',
  display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '24px 40px',
  borderRadius: 18, border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  boxSizing: 'border-box', gap: 18
}}>
  <style>{`
      @keyframes glow-move-6a { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(-240px, -40px) scale(1.4); } }
      @keyframes glow-move-6b { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(200px, 30px) scale(1.3); } }
      @keyframes glow-move-6c { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(-120px, -20px) scale(1.2); } }
      #b3-g1 { animation: glow-move-6a 11s ease-in-out infinite; }
      #b3-g2 { animation: glow-move-6b 9s ease-in-out infinite; }
      #b3-g3 { animation: glow-move-6c 10s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="180" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bg3-1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>
      <radialGradient id="bg3-2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
      <radialGradient id="bg3-3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(236,72,153,0.85)" />
        <stop offset="70%" stopColor="rgba(190,24,93,0)" />
      </radialGradient>
      <radialGradient id="bg3-4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(6,182,212,0.8)" />
        <stop offset="70%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle id="b3-g1" cx="720" cy="130" r="190" fill="url(#bg3-1)" />
    <circle id="b3-g2" cx="150" cy="140" r="180" fill="url(#bg3-2)" />
    <circle id="b3-g3" cx="450" cy="50" r="140" fill="url(#bg3-3)" />
    <circle cx="800" cy="30" r="100" fill="url(#bg3-4)" />
  </svg>

  <div style={{ fontSize: 11, color: 'rgba(216,180,254,0.7)', fontWeight: 700, letterSpacing: 1.5, position: 'relative' }}>
    TECH STACK
  </div>

  <div style={{ display: 'flex', alignItems: 'center', gap: 24, position: 'relative' }}>
    <span style={{ fontSize: 12, color: '#c084fc', fontWeight: 700, width: 110, letterSpacing: 0.5 }}>LANGUAGES</span>
    <div style={{ display: 'flex', gap: 10 }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#659ad2' }}></span> C++
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#3572A5' }}></span> Python
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#6E4C13' }}></span> Assembly
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#89e051' }}></span> Bash
      </div>
    </div>
  </div>

  <div style={{ display: 'flex', alignItems: 'center', gap: 24, position: 'relative' }}>
    <span style={{ fontSize: 12, color: '#60a5fa', fontWeight: 700, width: 110, letterSpacing: 0.5 }}>FRAMEWORKS</span>
    <div style={{ display: 'flex', gap: 10 }}>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#22d3ee' }}></span> Kali Linux
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#a855f7' }}></span> Ghidra
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#3b82f6' }}></span> Wireshark
      </div>
      <div style={{ display: 'flex', alignItems: 'center', gap: 6, padding: '6px 16px', borderRadius: 10, background: 'rgba(255,255,255,0.07)', border: '1px solid rgba(255,255,255,0.15)', color: '#ffffff', fontSize: 13, fontWeight: 600 }}>
        <span style={{ width: 8, height: 8, borderRadius: '50%', background: '#f43f5e' }}></span> GDB
      </div>
    </div>
  </div>
</div>
```

<br />

```aura width=860 height=100
<div style={{
  width: '100%', height: '100%', background: '#050508',
  display: 'flex', alignItems: 'center', justifyContent: 'center', gap: 16,
  borderRadius: 18, border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  boxSizing: 'border-box'
}}>
  <style>{`
      @keyframes glow-move-soc { 0%, 100% { transform: translate(0px, 0px) scale(1); } 50% { transform: translate(150px, -20px) scale(1.3); } }
      #b4-g1 { animation: glow-move-soc 8s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="100" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="bg4-1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(168,85,247,0.8)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="bg4-2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(59,130,246,0.8)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>
    <circle id="b4-g1" cx="300" cy="50" r="120" fill="url(#bg4-1)" />
    <circle cx="560" cy="50" r="120" fill="url(#bg4-2)" />
  </svg>

  <div style={{
    display: 'flex', alignItems: 'center', gap: 10, padding: '10px 22px',
    borderRadius: 12, background: 'rgba(15,15,26,0.85)', border: '1px solid rgba(56,189,248,0.5)',
    color: '#38bdf8', fontSize: 13, fontWeight: 700, position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="#38bdf8">
      <path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm4.64 6.8c-.15 1.58-.8 5.42-1.13 7.19-.14.75-.42 1-.68 1.03-.58.05-1.02-.38-1.58-.75-.88-.58-1.38-.94-2.23-1.5-.99-.65-.35-1.01.22-1.59.15-.15 2.71-2.48 2.76-2.69.01-.03.01-.14-.07-.2-.08-.06-.19-.04-.27-.02-.12.02-1.96 1.25-5.54 3.67-.52.36-.99.53-1.42.52-.47-.01-1.37-.26-2.03-.48-.82-.27-1.47-.42-1.42-.88.03-.24.37-.49 1.02-.75 3.98-1.73 6.64-2.87 7.97-3.44 3.8-1.58 4.59-1.86 5.1-1.87.11 0 .37.03.54.17.14.12.18.28.2.45-.02.07-.01.19-.03.32z"/>
    </svg>
    TELEGRAM
  </div>

  <div style={{
    display: 'flex', alignItems: 'center', gap: 10, padding: '10px 22px',
    borderRadius: 12, background: 'rgba(15,15,26,0.85)', border: '1px solid rgba(244,63,94,0.5)',
    color: '#f43f5e', fontSize: 13, fontWeight: 700, position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="#f43f5e">
      <path d="M19.59 6.69a4.83 4.83 0 0 1-3.77-4.25V2h-3.45v13.67a2.89 2.89 0 0 1-5.2 1.74 2.89 2.89 0 0 1 2.31-4.64c.29 0 .56.04.83.1v-3.6a6.35 6.35 0 0 0-.83-.05A6.34 6.34 0 0 0 3 15.57a6.34 6.34 0 0 0 10.86 4.43v-7a8.16 8.16 0 0 0 4.77 1.52v-3.4a4.85 4.85 0 0 1-1.04-.15z"/>
    </svg>
    TIKTOK
  </div>

  <div style={{
    display: 'flex', alignItems: 'center', gap: 10, padding: '10px 22px',
    borderRadius: 12, background: 'rgba(15,15,26,0.85)', border: '1px solid rgba(168,85,247,0.5)',
    color: '#c084fc', fontSize: 13, fontWeight: 700, position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="#c084fc">
      <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
    </svg>
    EMAIL
  </div>
</div>
```

<br/>

## `$ tail -f contribution.log`

<div align="center">

<img src="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/output/github-contribution-grid-snake.svg" width="100%"/>

</div>