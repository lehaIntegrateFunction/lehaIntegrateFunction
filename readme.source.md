```aura width=860 height=200
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(110,80,220,0.18)', boxSizing: 'border-box'
}}>

  <style>{`
      @keyframes float-slow { 0%, 100% { transform: translateX(0px); opacity: 0.8; } 50% { transform: translateX(350px); opacity: 1.2; } }
      @keyframes float-medium { 0%, 100% { transform: translateX(0px); opacity: 0.7; } 50% { transform: translateX(-250px); opacity: 1.1; } }
      @keyframes float-fast { 0%, 100% { transform: translateX(0px); opacity: 0.9; } 50% { transform: translateX(200px); opacity: 0.6; } }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-fast 9s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="200" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110,20,210,0.72)" />
        <stop offset="70%" stopColor="rgba(90,15,180,0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,60,255,0.6)" />
        <stop offset="70%" stopColor="rgba(30,50,200,0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0,130,255,0.45)" />
        <stop offset="70%" stopColor="rgba(0,100,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="glow-1" cx="180" cy="230" rx="260" ry="190" fill="url(#g1)" />
    <ellipse id="glow-2" cx="300" cy="240" rx="220" ry="160" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="240" rx="180" ry="140" fill="url(#g3)" />
  </svg>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:48, gap:8, position: 'relative' }}>
    <div style={{ display:'flex', fontSize:36, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Leha <span style={{ fontSize: 18, color: '#a030ff', marginLeft: 10, alignSelf: 'center' }}>(root@leha)</span>
    </div>
    <div style={{ display:'flex', fontSize:14, color:'rgba(180,165,255,0.8)', fontWeight:400 }}>
      Future Cybersecurity Specialist | CTF & Reverse Engineering 💻
    </div>
    <div style={{ display:'flex', gap:8, marginTop:6 }}>
      <div style={{ padding:'4px 12px', borderRadius:20, background:'rgba(80,40,220,0.2)', border:'1px solid rgba(100,70,240,0.4)', color:'rgba(205,195,255,0.9)', fontSize:12, fontWeight:600 }}>C++</div>
      <div style={{ padding:'4px 12px', borderRadius:20, background:'rgba(80,40,220,0.2)', border:'1px solid rgba(100,70,240,0.4)', color:'rgba(205,195,255,0.9)', fontSize:12, fontWeight:600 }}>Python</div>
      <div style={{ padding:'4px 12px', borderRadius:20, background:'rgba(80,40,220,0.2)', border:'1px solid rgba(100,70,240,0.4)', color:'rgba(205,195,255,0.9)', fontSize:12, fontWeight:600 }}>Assembly</div>
      <div style={{ padding:'4px 12px', borderRadius:20, background:'rgba(80,40,220,0.2)', border:'1px solid rgba(100,70,240,0.4)', color:'rgba(205,195,255,0.9)', fontSize:12, fontWeight:600 }}>Kali Linux</div>
    </div>
  </div>
</div>
```

<br />

```aura width=860 height=140
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', justifyContent: 'space-around',
  borderRadius: 16, border: '1px solid rgba(110,80,220,0.18)',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  boxSizing: 'border-box'
}}>
  <style>{`
      @keyframes float-glow2 { 0%, 100% { transform: translateX(0px); opacity: 0.7; } 50% { transform: translateX(220px); opacity: 1; } }
      #glow-bg2 { animation: float-glow2 10s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="140" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g4" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(160,30,255,0.45)" />
        <stop offset="70%" stopColor="rgba(130,20,220,0)" />
      </radialGradient>
    </defs>
    <ellipse id="glow-bg2" cx="350" cy="140" rx="320" ry="130" fill="url(#g4)" />
  </svg>

  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 36, fontWeight: 800, color: '#a78bfa' }}>11</span>
    <span style={{ fontSize: 11, color: 'rgba(200,195,225,0.5)', letterSpacing: 1.5, fontWeight: 600 }}>REPOS</span>
  </div>
  <div style={{ width: 1, height: 50, background: 'rgba(255,255,255,0.08)', position: 'relative' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 36, fontWeight: 800, color: '#60a5fa' }}>146</span>
    <span style={{ fontSize: 11, color: 'rgba(200,195,225,0.5)', letterSpacing: 1.5, fontWeight: 600 }}>STARS</span>
  </div>
  <div style={{ width: 1, height: 50, background: 'rgba(255,255,255,0.08)', position: 'relative' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 4, position: 'relative' }}>
    <span style={{ fontSize: 36, fontWeight: 800, color: '#f59e0b' }}>2466</span>
    <span style={{ fontSize: 11, color: 'rgba(200,195,225,0.5)', letterSpacing: 1.5, fontWeight: 600 }}>COMMITS</span>
  </div>
</div>
```

<br />

```aura width=860 height=180
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', flexDirection: 'column', justifyContent: 'center', padding: '24px 40px',
  borderRadius: 16, border: '1px solid rgba(110,80,220,0.18)',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  boxSizing: 'border-box', gap: 18
}}>
  <style>{`
      @keyframes float-glow3 { 0%, 100% { transform: translateX(0px); opacity: 0.6; } 50% { transform: translateX(-250px); opacity: 0.9; } }
      #glow-bg3 { animation: float-glow3 12s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="180" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g5" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(40,70,255,0.4)" />
        <stop offset="70%" stopColor="rgba(20,50,200,0)" />
      </radialGradient>
    </defs>
    <ellipse id="glow-bg3" cx="650" cy="180" rx="300" ry="140" fill="url(#g5)" />
  </svg>

  <div style={{ fontSize: 11, color: 'rgba(200,195,225,0.4)', fontWeight: 700, letterSpacing: 1.5, position: 'relative' }}>
    TECH STACK
  </div>

  <div style={{ display: 'flex', alignItems: 'center', gap: 24, position: 'relative' }}>
    <span style={{ fontSize: 12, color: '#a78bfa', fontWeight: 600, width: 110, letterSpacing: 0.5 }}>LANGUAGES</span>
    <div style={{ display: 'flex', gap: 10 }}>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>C++</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Python</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Assembly</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Bash</span>
    </div>
  </div>

  <div style={{ display: 'flex', alignItems: 'center', gap: 24, position: 'relative' }}>
    <span style={{ fontSize: 12, color: '#60a5fa', fontWeight: 600, width: 110, letterSpacing: 0.5 }}>FRAMEWORKS</span>
    <div style={{ display: 'flex', gap: 10 }}>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Kali Linux</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Ghidra</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>Wireshark</span>
      <span style={{ padding: '6px 14px', borderRadius: 8, background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.08)', color: '#ffffff', fontSize: 13, fontWeight: 500 }}>GDB</span>
    </div>
  </div>
</div>
```

<br/>

<div align="center">

[![Telegram](https://img.shields.io/badge/Telegram-000000?style=for-the-badge&logo=telegram&logoColor=0088ff)](https://t.me/rootrace)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=0088ff)](https://www.tiktok.com/@user1101000010010000)
[![Email](https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=0088ff)](mailto:qwer290310@gmail.com)

</div>

<br/>

## `$ tail -f contribution.log`

<div align="center">

<img src="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/output/github-contribution-grid-snake.svg" width="100%"/>

</div>