```aura width=860 height=200
<div style={{
  width: '100%',
  height: '100%',
  background: '#050508',
  display: 'flex',
  alignItems: 'center',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  boxSizing: 'border-box'
}}>
  <style>{`
    @keyframes lehaGlow1 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(180px, -30px) scale(1.3); }
    }
    @keyframes lehaGlow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-150px, 40px) scale(1.2); }
    }
    @keyframes lehaGlow3 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(120px, 50px) scale(1.4); }
    }
    .leha-g1 { animation: lehaGlow1 9s ease-in-out infinite; }
    .leha-g2 { animation: lehaGlow2 11s ease-in-out infinite; }
    .leha-g3 { animation: lehaGlow3 7s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="200" style={{
    position: 'absolute',
    top: 0,
    left: 0,
    pointerEvents: 'none'
  }}>
    <defs>
      <radialGradient id="heroPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="60%" stopColor="rgba(147,51,234,0.4)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>

      <radialGradient id="heroBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.9)" />
        <stop offset="65%" stopColor="rgba(37,99,235,0.3)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>

      <radialGradient id="heroPink">
        <stop offset="0%" stopColor="rgba(236,72,153,0.8)" />
        <stop offset="100%" stopColor="rgba(219,39,119,0)" />
      </radialGradient>
    </defs>

    <circle className="leha-g1" cx="200" cy="180" r="180" fill="url(#heroPurple)" />
    <circle className="leha-g2" cx="550" cy="190" r="170" fill="url(#heroBlue)" />
    <circle className="leha-g3" cx="380" cy="100" r="140" fill="url(#heroPink)" />
  </svg>

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    marginLeft: 48,
    gap: 8,
    position: 'relative',
    zIndex: 2
  }}>
    <div style={{
      display: 'flex',
      alignItems: 'center',
      fontSize: 38,
      fontWeight: 800,
      color: '#ffffff',
      letterSpacing: '-1px',
      lineHeight: 1
    }}>
      Leha
      <span style={{
        fontSize: 18,
        color: '#c084fc',
        marginLeft: 10,
        fontWeight: 600
      }}>
        (root@leha)
      </span>
    </div>

    <div style={{
      fontSize: 14,
      color: 'rgba(216,180,254,0.9)',
      fontWeight: 400
    }}>
      Future Cybersecurity Specialist | CTF & Reverse Engineering
    </div>

    <div style={{
      display: 'flex',
      gap: 8,
      marginTop: 8
    }}>
      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>C++</div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>Python</div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>Assembly</div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>Kali Linux</div>
    </div>
  </div>
</div>
```

```aura width=860 height=140
<div style={{
  width: '100%',
  height: '100%',
  background: '#050508',
  display: 'flex',
  alignItems: 'center',
  justifyContent: 'space-around',
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  boxSizing: 'border-box'
}}>
  <style>{`
    @keyframes statsGlow1 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(180px, -20px) scale(1.3); }
    }
    @keyframes statsGlow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-180px, 25px) scale(1.2); }
    }
    .stats-g1 { animation: statsGlow1 9s ease-in-out infinite; }
    .stats-g2 { animation: statsGlow2 11s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="140" style={{
    position: 'absolute',
    top: 0,
    left: 0,
    pointerEvents: 'none'
  }}>
    <defs>
      <radialGradient id="statsPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.8)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="statsBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.8)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>

    <circle className="stats-g1" cx="180" cy="110" r="160" fill="url(#statsPurple)" />
    <circle className="stats-g2" cx="680" cy="60" r="160" fill="url(#statsBlue)" />
  </svg>

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    alignItems: 'center',
    gap: 4,
    position: 'relative',
    zIndex: 2
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#c084fc',
      textShadow: '0 0 15px rgba(192,132,252,0.6)'
    }}>11</span>
    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>REPOS</span>
  </div>

  <div style={{
    width: 1,
    height: 50,
    background: 'rgba(255,255,255,0.15)'
  }} />

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    alignItems: 'center',
    gap: 4,
    position: 'relative',
    zIndex: 2
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#60a5fa',
      textShadow: '0 0 15px rgba(96,165,250,0.6)'
    }}>146</span>
    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>STARS</span>
  </div>

  <div style={{
    width: 1,
    height: 50,
    background: 'rgba(255,255,255,0.15)'
  }} />

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    alignItems: 'center',
    gap: 4,
    position: 'relative',
    zIndex: 2
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#fbbf24',
      textShadow: '0 0 15px rgba(251,191,36,0.6)'
    }}>2466</span>
    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>COMMITS</span>
  </div>
</div>
```

```aura width=860 height=180
<div style={{
  width: '100%',
  height: '100%',
  background: '#050508',
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  padding: '24px 40px',
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  boxSizing: 'border-box',
  gap: 16
}}>
  <svg width="860" height="180" style={{
    position: 'absolute',
    top: 0,
    left: 0,
    pointerEvents: 'none'
  }}>
    <defs>
      <radialGradient id="techPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.65)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="techBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.6)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>

    <circle cx="120" cy="150" r="160" fill="url(#techPurple)" />
    <circle cx="750" cy="40" r="160" fill="url(#techBlue)" />
  </svg>

  <div style={{
    fontSize: 11,
    color: 'rgba(216,180,254,0.7)',
    fontWeight: 700,
    letterSpacing: 1.5,
    position: 'relative'
  }}>
    TECH STACK
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 24,
    position: 'relative'
  }}>
    <span style={{
      fontSize: 12,
      color: '#c084fc',
      fontWeight: 700,
      width: 110
    }}>
      LANGUAGES
    </span>

    <div style={{
      display: 'flex',
      gap: 10
    }}>
      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>🔵 C++</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>🐍 Python</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>⚙ Assembly</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>⌘ Bash</div>
    </div>
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 24,
    position: 'relative'
  }}>
    <span style={{
      fontSize: 12,
      color: '#60a5fa',
      fontWeight: 700,
      width: 110
    }}>
      TOOLS
    </span>

    <div style={{
      display: 'flex',
      gap: 10
    }}>
      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>🐉 Kali Linux</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>◈ Ghidra</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>◉ Wireshark</div>

      <div style={{
        padding: '7px 15px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#fff',
        fontSize: 13,
        fontWeight: 600
      }}>● GDB</div>
    </div>
  </div>
</div>
```

```aura width=860 height=100
<div style={{
  width: '100%',
  height: '100%',
  background: '#050508',
  display: 'flex',
  alignItems: 'center',
  justifyContent: 'center',
  gap: 16,
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  boxSizing: 'border-box'
}}>
  <svg width="860" height="100" style={{
    position: 'absolute',
    top: 0,
    left: 0,
    pointerEvents: 'none'
  }}>
    <defs>
      <radialGradient id="socialPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.55)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
      <radialGradient id="socialBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.5)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>
    </defs>

    <circle cx="250" cy="50" r="120" fill="url(#socialPurple)" />
    <circle cx="610" cy="50" r="120" fill="url(#socialBlue)" />
  </svg>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 9,
    padding: '10px 20px',
    borderRadius: 12,
    background: 'rgba(15,15,26,0.9)',
    border: '1px solid rgba(56,189,248,0.5)',
    color: '#38bdf8',
    fontSize: 13,
    fontWeight: 700,
    position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor">
      <path d="M21.9 4.2L18.8 19c-.23 1.04-.85 1.3-1.72.81l-4.72-3.48-2.28 2.19c-.25.25-.46.46-.94.46l.34-4.81 8.76-7.91c.38-.34-.08-.53-.59-.19L6.82 12.99l-4.66-1.46c-1.01-.32-1.03-1.01.21-1.5L20.6 3.1c.87-.32 1.63.2 1.3 1.1z"/>
    </svg>
    TELEGRAM
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 9,
    padding: '10px 20px',
    borderRadius: 12,
    background: 'rgba(15,15,26,0.9)',
    border: '1px solid rgba(244,63,94,0.5)',
    color: '#f43f5e',
    fontSize: 13,
    fontWeight: 700,
    position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="currentColor">
      <path d="M19.59 6.69a4.83 4.83 0 0 1-3.77-4.25V2h-3.45v13.67a2.89 2.89 0 1 1-2.89-2.89c.29 0 .56.04.83.1v-3.6a6.35 6.35 0 1 0 6.34 6.34V8a8.16 8.16 0 0 0 4.77 1.52v-3.4a4.85 4.85 0 0 1-1-.15z"/>
    </svg>
    TIKTOK
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 9,
    padding: '10px 20px',
    borderRadius: 12,
    background: 'rgba(15,15,26,0.9)',
    border: '1px solid rgba(168,85,247,0.5)',
    color: '#c084fc',
    fontSize: 13,
    fontWeight: 700,
    position: 'relative'
  }}>
    <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2">
      <rect x="3" y="5" width="18" height="14" rx="2" />
      <path d="m3 7 9 6 9-6" />
    </svg>
    EMAIL
  </div>
</div>
```

## `$ tail -f contribution.log`

```aura width=860 height=180
<div style={{
  width: '100%',
  height: '100%',
  background: '#050508',
  display: 'flex',
  flexDirection: 'column',
  justifyContent: 'center',
  padding: '20px 32px',
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  boxSizing: 'border-box',
  gap: 12
}}>
  <style>{`
    @keyframes terminalGlow1 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(170px, -20px) scale(1.25); }
    }
    @keyframes terminalGlow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-150px, 20px) scale(1.2); }
    }
    .terminal-g1 { animation: terminalGlow1 9s ease-in-out infinite; }
    .terminal-g2 { animation: terminalGlow2 11s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="180" style={{
    position: 'absolute',
    top: 0,
    left: 0,
    pointerEvents: 'none'
  }}>
    <defs>
      <radialGradient id="terminalPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.65)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>

      <radialGradient id="terminalBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.6)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
    </defs>

    <circle className="terminal-g1" cx="160" cy="150" r="150" fill="url(#terminalPurple)" />
    <circle className="terminal-g2" cx="720" cy="40" r="150" fill="url(#terminalBlue)" />
  </svg>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 9,
    position: 'relative',
    zIndex: 2
  }}>
    <span style={{
      color: '#c084fc',
      fontSize: 14,
      fontWeight: 800
    }}>$</span>

    <span style={{
      color: '#ffffff',
      fontSize: 14,
      fontWeight: 700
    }}>
      tail -f contribution.log
    </span>

    <span style={{
      width: 7,
      height: 7,
      borderRadius: '50%',
      background: '#22c55e',
      boxShadow: '0 0 10px rgba(34,197,94,0.8)'
    }} />
  </div>

  <div style={{
    width: '100%',
    height: 105,
    padding: 12,
    borderRadius: 12,
    background: 'rgba(255,255,255,0.035)',
    border: '1px solid rgba(255,255,255,0.08)',
    position: 'relative',
    boxSizing: 'border-box',
    display: 'flex',
    alignItems: 'center',
    justifyContent: 'center'
  }}>
    <svg width="790" height="82" viewBox="0 0 790 82" style={{
      width: '100%',
      height: '100%'
    }}>
      <rect width="790" height="82" rx="8" fill="rgba(0,0,0,0.18)" />

      <g opacity="0.9">
        <rect x="10" y="10" width="10" height="10" rx="2" fill="#17131f" />
        <rect x="24" y="10" width="10" height="10" rx="2" fill="#27203a" />
        <rect x="38" y="10" width="10" height="10" rx="2" fill="#3b2560" />
        <rect x="52" y="10" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="66" y="10" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="80" y="10" width="10" height="10" rx="2" fill="#3b2560" />
        <rect x="94" y="10" width="10" height="10" rx="2" fill="#17131f" />

        <rect x="10" y="24" width="10" height="10" rx="2" fill="#27203a" />
        <rect x="24" y="24" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="38" y="24" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="52" y="24" width="10" height="10" rx="2" fill="#c084fc" />
        <rect x="66" y="24" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="80" y="24" width="10" height="10" rx="2" fill="#27203a" />
        <rect x="94" y="24" width="10" height="10" rx="2" fill="#17131f" />

        <rect x="10" y="38" width="10" height="10" rx="2" fill="#17131f" />
        <rect x="24" y="38" width="10" height="10" rx="2" fill="#3b2560" />
        <rect x="38" y="38" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="52" y="38" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="66" y="38" width="10" height="10" rx="2" fill="#3b82f6" />
        <rect x="80" y="38" width="10" height="10" rx="2" fill="#60a5fa" />
        <rect x="94" y="38" width="10" height="10" rx="2" fill="#27203a" />

        <rect x="10" y="52" width="10" height="10" rx="2" fill="#27203a" />
        <rect x="24" y="52" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="38" y="52" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="52" y="52" width="10" height="10" rx="2" fill="#c084fc" />
        <rect x="66" y="52" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="80" y="52" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="94" y="52" width="10" height="10" rx="2" fill="#17131f" />

        <rect x="10" y="66" width="10" height="10" rx="2" fill="#17131f" />
        <rect x="24" y="66" width="10" height="10" rx="2" fill="#27203a" />
        <rect x="38" y="66" width="10" height="10" rx="2" fill="#3b2560" />
        <rect x="52" y="66" width="10" height="10" rx="2" fill="#6d28d9" />
        <rect x="66" y="66" width="10" height="10" rx="2" fill="#a855f7" />
        <rect x="80" y="66" width="10" height="10" rx="2" fill="#3b2560" />
        <rect x="94" y="66" width="10" height="10" rx="2" fill="#17131f" />
      </g>

      <path
        d="M120 66 L135 52 L150 52 L165 38 L180 38 L195 24 L210 24 L225 38 L240 38 L255 52 L270 52 L285 38 L300 38 L315 24 L330 24 L345 38 L360 38 L375 52 L390 52 L405 38 L420 38 L435 24 L450 24 L465 38 L480 38 L495 52 L510 52 L525 38 L540 38 L555 24 L570 24 L585 38 L600 38 L615 52 L630 52 L645 38 L660 38 L675 24 L690 24 L705 38 L720 38 L735 52 L750 52"
        fill="none"
        stroke="#a855f7"
        strokeWidth="3"
        strokeLinecap="round"
        strokeLinejoin="round"
        opacity="0.9"
      />

      <circle cx="750" cy="52" r="5" fill="#c084fc">
        <animate
          attributeName="opacity"
          values="1;0.35;1"
          dur="1.4s"
          repeatCount="indefinite"
        />
      </circle>
    </svg>
  </div>
</div>
```