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
    @keyframes glow1 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(180px, -30px) scale(1.3); }
    }

    @keyframes glow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-150px, 40px) scale(1.2); }
    }

    @keyframes glow3 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(120px, 50px) scale(1.4); }
    }

    #heroGlow1 { animation: glow1 9s ease-in-out infinite; }
    #heroGlow2 { animation: glow2 11s ease-in-out infinite; }
    #heroGlow3 { animation: glow3 7s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="200" style={{
    position: 'absolute',
    top: 0,
    left: 0
  }}>
    <defs>
      <radialGradient id="heroPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="60%" stopColor="rgba(147,51,234,0.4)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>

      <radialGradient id="heroBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="65%" stopColor="rgba(37,99,235,0.35)" />
        <stop offset="100%" stopColor="rgba(0,0,0,0)" />
      </radialGradient>

      <radialGradient id="heroPink">
        <stop offset="0%" stopColor="rgba(236,72,153,0.85)" />
        <stop offset="70%" stopColor="rgba(219,39,119,0)" />
      </radialGradient>
    </defs>

    <circle id="heroGlow1" cx="200" cy="180" r="180" fill="url(#heroPurple)" />
    <circle id="heroGlow2" cx="550" cy="190" r="170" fill="url(#heroBlue)" />
    <circle id="heroGlow3" cx="380" cy="100" r="140" fill="url(#heroPink)" />
  </svg>

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    marginLeft: 48,
    gap: 8,
    position: 'relative'
  }}>
    <div style={{
      display: 'flex',
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
        alignSelf: 'center',
        fontWeight: 600
      }}>
        (root@leha)
      </span>
    </div>

    <div style={{
      display: 'flex',
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
      }}>
        C++
      </div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>
        Python
      </div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>
        Assembly
      </div>

      <div style={{
        padding: '5px 14px',
        borderRadius: 20,
        background: 'rgba(147,51,234,0.25)',
        border: '1px solid rgba(192,132,252,0.5)',
        color: '#f3e8ff',
        fontSize: 12,
        fontWeight: 600
      }}>
        Kali Linux
      </div>
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
      50% { transform: translate(220px, -25px) scale(1.4); }
    }

    @keyframes statsGlow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-200px, 30px) scale(1.3); }
    }

    #statsGlow1 { animation: statsGlow1 10s ease-in-out infinite; }
    #statsGlow2 { animation: statsGlow2 8s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="140" style={{
    position: 'absolute',
    top: 0,
    left: 0
  }}>
    <defs>
      <radialGradient id="statsPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>

      <radialGradient id="statsBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
    </defs>

    <circle id="statsGlow1" cx="200" cy="110" r="170" fill="url(#statsPurple)" />
    <circle id="statsGlow2" cx="660" cy="100" r="170" fill="url(#statsBlue)" />
  </svg>

  <div style={{
    display: 'flex',
    flexDirection: 'column',
    alignItems: 'center',
    gap: 4,
    position: 'relative'
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#c084fc',
      textShadow: '0 0 15px rgba(192,132,252,0.6)'
    }}>
      11
    </span>

    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>
      REPOS
    </span>
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
    position: 'relative'
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#60a5fa',
      textShadow: '0 0 15px rgba(96,165,250,0.6)'
    }}>
      146
    </span>

    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>
      STARS
    </span>
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
    position: 'relative'
  }}>
    <span style={{
      fontSize: 38,
      fontWeight: 800,
      color: '#fbbf24',
      textShadow: '0 0 15px rgba(251,191,36,0.6)'
    }}>
      2466
    </span>

    <span style={{
      fontSize: 11,
      color: 'rgba(233,213,255,0.8)',
      letterSpacing: 1.5,
      fontWeight: 700
    }}>
      COMMITS
    </span>
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
  gap: 18
}}>
  <style>{`
    @keyframes stackGlow1 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(-240px, -40px) scale(1.4); }
    }

    @keyframes stackGlow2 {
      0%, 100% { transform: translate(0px, 0px) scale(1); }
      50% { transform: translate(200px, 30px) scale(1.3); }
    }

    #stackGlow1 { animation: stackGlow1 11s ease-in-out infinite; }
    #stackGlow2 { animation: stackGlow2 9s ease-in-out infinite; }
  `}</style>

  <svg width="860" height="180" style={{
    position: 'absolute',
    top: 0,
    left: 0
  }}>
    <defs>
      <radialGradient id="stackPurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.95)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>

      <radialGradient id="stackBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.95)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
    </defs>

    <circle id="stackGlow1" cx="720" cy="130" r="190" fill="url(#stackPurple)" />
    <circle id="stackGlow2" cx="150" cy="140" r="180" fill="url(#stackBlue)" />
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
      width: 110,
      letterSpacing: 0.5
    }}>
      LANGUAGES
    </span>

    <div style={{
      display: 'flex',
      gap: 10
    }}>
      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         C++
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Python
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Assembly
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Bash
      </div>
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
      width: 110,
      letterSpacing: 0.5
    }}>
      TOOLS
    </span>

    <div style={{
      display: 'flex',
      gap: 10
    }}>
      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Kali Linux
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Ghidra
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         Wireshark
      </div>

      <div style={{
        padding: '6px 16px',
        borderRadius: 10,
        background: 'rgba(255,255,255,0.07)',
        border: '1px solid rgba(255,255,255,0.15)',
        color: '#ffffff',
        fontSize: 13,
        fontWeight: 600
      }}>
         GDB
      </div>
    </div>
  </div>
</div>
```

```aura width=150 height=44 link="https://t.me/ТВОЙ_НИК" inline align=center
<SocialMediaButton
  icon="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/main/telegram-icon.svg"
  text="Telegram"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#1af4ff' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="30"
/>
```

```aura width=150 height=44 link="https://tiktok.com/@ТВОЙ_НИК" inline align=center
<SocialMediaButton
  icon="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/main/icontiktok.jpg"
  text="TikTok"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#1af4ff' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="30"
/>
```

```aura width=150 height=44 link="mailto:ТВОЯ_ПОЧТА@example.com" inline align=center
<SocialMediaButton
  icon="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/main/gmail-icon.svg"
  text="Email"
  backgroundColor="#111111"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '10%', color: '#111111' },
    { offset: '50%', color: '#eeeeee' },
    { offset: '60%', color: '#1af4ff' },
    { offset: '80%', color: '#111111' },
    { offset: '100%', color: '#555555' },
  ]}
  iconSize="30"
/>
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
  padding: '22px 32px',
  borderRadius: 18,
  border: '1px solid rgba(139,92,246,0.5)',
  fontFamily: 'Inter, sans-serif',
  position: 'relative',
  overflow: 'hidden',
  boxSizing: 'border-box',
  gap: 14
}}>
  <style>{`
    @keyframes snakeGlow1 {
      0%, 100% {
        transform: translate(0px, 0px) scale(1);
      }

      50% {
        transform: translate(180px, -20px) scale(1.25);
      }
    }

    @keyframes snakeGlow2 {
      0%, 100% {
        transform: translate(0px, 0px) scale(1);
      }

      50% {
        transform: translate(-160px, 25px) scale(1.2);
      }
    }

    #snakeGlow1 {
      animation: snakeGlow1 9s ease-in-out infinite;
    }

    #snakeGlow2 {
      animation: snakeGlow2 11s ease-in-out infinite;
    }
  `}</style>

  <svg width="860" height="180" style={{
    position: 'absolute',
    top: 0,
    left: 0
  }}>
    <defs>
      <radialGradient id="snakePurple">
        <stop offset="0%" stopColor="rgba(168,85,247,0.75)" />
        <stop offset="70%" stopColor="rgba(126,34,206,0)" />
      </radialGradient>

      <radialGradient id="snakeBlue">
        <stop offset="0%" stopColor="rgba(59,130,246,0.7)" />
        <stop offset="70%" stopColor="rgba(29,78,216,0)" />
      </radialGradient>
    </defs>

    <circle
      id="snakeGlow1"
      cx="180"
      cy="150"
      r="150"
      fill="url(#snakePurple)"
    />

    <circle
      id="snakeGlow2"
      cx="700"
      cy="50"
      r="150"
      fill="url(#snakeBlue)"
    />
  </svg>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: 10,
    position: 'relative'
  }}>
    <span style={{
      color: '#c084fc',
      fontSize: 14,
      fontWeight: 800
    }}>
      $
    </span>

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
      boxShadow: '0 0 10px rgba(34,197,94,0.8)',
      marginLeft: 3
    }} />
  </div>

  <div style={{
    display: 'flex',
    alignItems: 'center',
    justifyContent: 'center',
    width: '100%',
    padding: '14px 10px',
    borderRadius: 12,
    background: 'rgba(255,255,255,0.035)',
    border: '1px solid rgba(255,255,255,0.08)',
    position: 'relative',
    boxSizing: 'border-box'
  }}>
    <img
      src="https://raw.githubusercontent.com/lehaIntegrateFunction/LehaIntegrateFunction/output/github-contribution-grid-snake.svg"
    />
  </div>
</div>
```