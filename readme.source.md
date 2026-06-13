```aura width=900 height=300 align=center
<div style={{ display: 'flex', position: 'relative', width: '100%', height: '100%', background: '#04050a', borderRadius: '16px', alignItems: 'center', justifyContent: 'center', overflow: 'hidden' }}>
  <svg width="900" height="300" viewBox="0 0 900 300" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="26%" cy="32%" r="60%"><stop offset="0%" stopColor="#7c3aed" stopOpacity="0.95" /><stop offset="100%" stopColor="#04050a" stopOpacity="0" /></radialGradient>
      <radialGradient id="g2" cx="76%" cy="70%" r="55%"><stop offset="0%" stopColor="#06b6d4" stopOpacity="0.9" /><stop offset="100%" stopColor="#04050a" stopOpacity="0" /></radialGradient>
      <radialGradient id="g3" cx="55%" cy="48%" r="45%"><stop offset="0%" stopColor="#f472b6" stopOpacity="0.45" /><stop offset="100%" stopColor="#04050a" stopOpacity="0" /></radialGradient>
    </defs>
    <rect x="0" y="0" width="900" height="300" fill="#04050a" />
    <ellipse cx="240" cy="90" rx="340" ry="200" fill="url(#g1)"><animate attributeName="opacity" values="0.5;0.95;0.5" dur="5s" repeatCount="indefinite" /><animateTransform attributeName="transform" type="translate" values="-60 0;60 0;-60 0" dur="11s" repeatCount="indefinite" /></ellipse>
    <ellipse cx="670" cy="190" rx="320" ry="190" fill="url(#g2)"><animate attributeName="opacity" values="0.95;0.5;0.95" dur="7s" repeatCount="indefinite" /><animateTransform attributeName="transform" type="translate" values="60 0;-60 0;60 0" dur="14s" repeatCount="indefinite" /></ellipse>
    <ellipse cx="450" cy="140" rx="260" ry="160" fill="url(#g3)"><animate attributeName="opacity" values="0.3;0.7;0.3" dur="6s" repeatCount="indefinite" /></ellipse>
    <line x1="0" y1="0" x2="900" y2="0" stroke="#22d3ee" strokeWidth="1.5" opacity="0.22"><animate attributeName="y1" values="0;300;0" dur="8s" repeatCount="indefinite" /><animate attributeName="y2" values="0;300;0" dur="8s" repeatCount="indefinite" /></line>
    <circle cx="150" cy="60" r="2" fill="#22d3ee"><animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite" /><animate attributeName="r" values="1.5;3;1.5" dur="3s" repeatCount="indefinite" /></circle>
    <circle cx="780" cy="80" r="2" fill="#a78bfa"><animate attributeName="opacity" values="1;0.2;1" dur="4s" repeatCount="indefinite" /></circle>
    <circle cx="820" cy="230" r="2" fill="#f472b6"><animate attributeName="opacity" values="0.3;1;0.3" dur="3.5s" repeatCount="indefinite" /><animate attributeName="r" values="1.5;3;1.5" dur="3.5s" repeatCount="indefinite" /></circle>
    <circle cx="120" cy="250" r="2" fill="#34d399"><animate attributeName="opacity" values="1;0.3;1" dur="4.5s" repeatCount="indefinite" /></circle>
    <circle cx="700" cy="250" r="1.5" fill="#67e8f9"><animate attributeName="opacity" values="0.2;0.9;0.2" dur="5s" repeatCount="indefinite" /></circle>
    <circle cx="200" cy="140" r="1.5" fill="#c4b5fd"><animate attributeName="opacity" values="0.9;0.2;0.9" dur="4.2s" repeatCount="indefinite" /></circle>
    <circle cx="500" cy="55" r="1.5" fill="#f9a8d4"><animate attributeName="opacity" values="0.2;1;0.2" dur="3.8s" repeatCount="indefinite" /></circle>
    <circle cx="350" cy="245" r="1.5" fill="#6ee7b7"><animate attributeName="opacity" values="1;0.2;1" dur="5.5s" repeatCount="indefinite" /></circle>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 2 }}>
    <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '78px', fontWeight: 800, letterSpacing: '3px', color: 'transparent', backgroundImage: 'linear-gradient(90deg,#22d3ee,#a78bfa,#f472b6)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>HASSAN AIDIBE</div>
    <div style={{ display: 'flex', alignItems: 'center', marginTop: '14px', background: '#0a0c1490', border: '1px solid #1e293b', borderRadius: '10px', padding: '8px 16px' }}>
      <div style={{ display: 'flex', width: '9px', height: '9px', borderRadius: '50%', background: '#34d399', marginRight: '8px' }}><animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '15px', color: '#94a3b8', marginRight: '6px' }}>~/dev $</div>
      <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '15px', fontWeight: 600, color: '#e2e8f0' }}>building SaaS products</div>
      <div style={{ display: 'flex', width: '2px', height: '17px', background: '#22d3ee', marginLeft: '3px' }}><animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite" /></div>
    </div>
    <div style={{ display: 'flex', marginTop: '18px' }}>
      <div style={{ display: 'flex', fontSize: '13px', color: '#22d3ee', border: '1px solid #22d3ee55', borderRadius: '20px', padding: '5px 14px', marginRight: '10px' }}>4 ans alternance</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#a78bfa', border: '1px solid #a78bfa55', borderRadius: '20px', padding: '5px 14px', marginRight: '10px' }}>2 ans freelance</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#f472b6', border: '1px solid #f472b655', borderRadius: '20px', padding: '5px 14px' }}>open to CDI</div>
    </div>
  </div>
</div>
```
```aura width=900 height=120 align=center
<div style={{ display: 'flex', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '16px', padding: '0 20px', alignItems: 'center', justifyContent: 'space-between', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', width: '210px' }}>
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '8px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.2s" begin="0s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', fontSize: '34px', fontWeight: 800, color: 'transparent', backgroundImage: 'linear-gradient(90deg,#22d3ee,#67e8f9)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>4</div>
    </div>
    <div style={{ display: 'flex', fontSize: '11px', color: '#94a3b8', marginTop: '3px', letterSpacing: '1px' }}>ANS ALTERNANCE</div>
  </div>
  <div style={{ display: 'flex', width: '1px', height: '46px', background: '#1e293b' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', width: '210px' }}>
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '8px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.2s" begin="0.5s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', fontSize: '34px', fontWeight: 800, color: 'transparent', backgroundImage: 'linear-gradient(90deg,#a78bfa,#c4b5fd)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>2</div>
    </div>
    <div style={{ display: 'flex', fontSize: '11px', color: '#94a3b8', marginTop: '3px', letterSpacing: '1px' }}>ANS FREELANCE</div>
  </div>
  <div style={{ display: 'flex', width: '1px', height: '46px', background: '#1e293b' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', width: '210px' }}>
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#f472b6', marginRight: '8px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.2s" begin="1s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', fontSize: '34px', fontWeight: 800, color: 'transparent', backgroundImage: 'linear-gradient(90deg,#f472b6,#f9a8d4)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>3</div>
    </div>
    <div style={{ display: 'flex', fontSize: '11px', color: '#94a3b8', marginTop: '3px', letterSpacing: '1px' }}>SAAS LIVRÉS</div>
  </div>
  <div style={{ display: 'flex', width: '1px', height: '46px', background: '#1e293b' }}></div>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', width: '210px' }}>
    <div style={{ display: 'flex', alignItems: 'center' }}>
      <div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '8px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.2s" begin="1.5s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', fontSize: '34px', fontWeight: 800, color: 'transparent', backgroundImage: 'linear-gradient(90deg,#34d399,#6ee7b7)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>12</div>
    </div>
    <div style={{ display: 'flex', fontSize: '11px', color: '#94a3b8', marginTop: '3px', letterSpacing: '1px' }}>MODULES MÉTIER</div>
  </div>
</div>
```
```aura width=900 height=440 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '16px', padding: '28px 32px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', alignItems: 'center', marginBottom: '22px' }}>
    <div style={{ display: 'flex', width: '4px', height: '22px', background: 'linear-gradient(180deg,#22d3ee,#a78bfa)', borderRadius: '2px', marginRight: '12px' }}></div>
    <div style={{ display: 'flex', fontSize: '20px', fontWeight: 700, color: '#f1f5f9' }}>Tech Stack</div>
  </div>
  <div style={{ display: 'flex', flexWrap: 'wrap' }}>
    <div style={{ display: 'flex', flexDirection: 'column', width: '408px', marginRight: '20px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', alignItems: 'center', marginBottom: '10px' }}>
        <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#a78bfa', marginRight: '10px' }}>FRONTEND</div>
        <div style={{ display: 'flex', flexGrow: 1, height: '1px', background: 'linear-gradient(90deg,#a78bfa55,#0a0c14)' }}></div>
        <div style={{ display: 'flex', width: '5px', height: '5px', borderRadius: '50%', background: '#a78bfa', marginLeft: '6px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.6s" repeatCount="indefinite" /></div>
      </div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.00s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>React</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.12s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>Next.js</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.24s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>Vue.js</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.36s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>React Native</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.48s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>TypeScript</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.60s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>TailwindCSS</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.72s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#a78bfa', marginRight: '7px' }}></div>Remotion</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '408px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', alignItems: 'center', marginBottom: '10px' }}>
        <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#22d3ee', marginRight: '10px' }}>BACKEND</div>
        <div style={{ display: 'flex', flexGrow: 1, height: '1px', background: 'linear-gradient(90deg,#22d3ee55,#0a0c14)' }}></div>
        <div style={{ display: 'flex', width: '5px', height: '5px', borderRadius: '50%', background: '#22d3ee', marginLeft: '6px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.6s" repeatCount="indefinite" /></div>
      </div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.84s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Node.js</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="0.96s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Express</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.08s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Laravel</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.20s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Symfony</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.32s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>PHP</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.44s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Golang</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.56s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>Wails</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.68s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#22d3ee', marginRight: '7px' }}></div>GraphQL</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '408px', marginRight: '20px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', alignItems: 'center', marginBottom: '10px' }}>
        <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#f472b6', marginRight: '10px' }}>INFRA & DEVOPS</div>
        <div style={{ display: 'flex', flexGrow: 1, height: '1px', background: 'linear-gradient(90deg,#f472b655,#0a0c14)' }}></div>
        <div style={{ display: 'flex', width: '5px', height: '5px', borderRadius: '50%', background: '#f472b6', marginLeft: '6px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.6s" repeatCount="indefinite" /></div>
      </div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.80s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#f472b6', marginRight: '7px' }}></div>Docker</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="1.92s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#f472b6', marginRight: '7px' }}></div>Kubernetes</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.04s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#f472b6', marginRight: '7px' }}></div>Terraform</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.16s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#f472b6', marginRight: '7px' }}></div>GitHub Actions</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '408px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', alignItems: 'center', marginBottom: '10px' }}>
        <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#34d399', marginRight: '10px' }}>AI / ML & DATA</div>
        <div style={{ display: 'flex', flexGrow: 1, height: '1px', background: 'linear-gradient(90deg,#34d39955,#0a0c14)' }}></div>
        <div style={{ display: 'flex', width: '5px', height: '5px', borderRadius: '50%', background: '#34d399', marginLeft: '6px' }}><animate attributeName="opacity" values="1;0.2;1" dur="2.6s" repeatCount="indefinite" /></div>
      </div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.28s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>Mistral</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.40s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>AssemblyAI</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.52s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>ElevenLabs</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.64s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>GPT-4o</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.76s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>PostgreSQL</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="2.88s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>MySQL</div>
        <div style={{ display: 'flex', alignItems: 'center', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px 4px 9px', marginRight: '7px', marginBottom: '7px' }}><animate attributeName="opacity" values="0;0;1" keyTimes="0;0.05;0.4" dur="2.5s" begin="3.00s" fill="freeze" /><div style={{ display: 'flex', width: '6px', height: '6px', borderRadius: '50%', background: '#34d399', marginRight: '7px' }}></div>Redis</div>
      </div>
    </div>
  </div>
</div>
```
```aura width=900 height=420 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '16px', padding: '28px 32px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', alignItems: 'center', marginBottom: '20px' }}>
    <div style={{ display: 'flex', width: '4px', height: '22px', background: 'linear-gradient(180deg,#a78bfa,#f472b6)', borderRadius: '2px', marginRight: '12px' }}></div>
    <div style={{ display: 'flex', fontSize: '20px', fontWeight: 700, color: '#f1f5f9' }}>Shipped Projects</div>
  </div>
  <div style={{ display: 'flex', flexWrap: 'wrap' }}>
    <div style={{ display: 'flex', flexDirection: 'column', position: 'relative', width: '396px', background: '#11141d', border: '1px solid #22d3ee33', borderRadius: '12px', padding: '16px 18px', marginRight: '16px', marginBottom: '16px', overflow: 'hidden' }}>
      <div style={{ display: 'flex', position: 'absolute', top: 0, left: 0, width: '100%', height: '2px', background: '#22d3ee' }}><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', marginBottom: '8px' }}>
        <div style={{ display: 'flex', alignItems: 'center' }}>
          <div style={{ display: 'flex', width: '8px', height: '8px', borderRadius: '50%', background: '#22d3ee', marginRight: '9px' }}><animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite" /></div>
          <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#22d3ee' }}>Klark</div>
        </div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#22d3ee', background: '#22d3ee1a', borderRadius: '6px', padding: '2px 8px' }}>depuis 2025</div>
      </div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5', marginBottom: '11px' }}>SaaS B2B all-in-one · 12 modules métier en micro-frontends (Module Federation)</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>React 19</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>TypeScript</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Express</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Stripe</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Firebase</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', position: 'relative', width: '396px', background: '#11141d', border: '1px solid #a78bfa33', borderRadius: '12px', padding: '16px 18px', marginBottom: '16px', overflow: 'hidden' }}>
      <div style={{ display: 'flex', position: 'absolute', top: 0, left: 0, width: '100%', height: '2px', background: '#a78bfa' }}><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', marginBottom: '8px' }}>
        <div style={{ display: 'flex', alignItems: 'center' }}>
          <div style={{ display: 'flex', width: '8px', height: '8px', borderRadius: '50%', background: '#a78bfa', marginRight: '9px' }}><animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite" /></div>
          <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#a78bfa' }}>Soluweld</div>
        </div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#a78bfa', background: '#a78bfa1a', borderRadius: '6px', padding: '2px 8px' }}>2025 — 2026</div>
      </div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5', marginBottom: '11px' }}>SaaS B2B · gestion & coordination du soudage industriel</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>React</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>TypeScript</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Laravel</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Kubernetes</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', position: 'relative', width: '396px', background: '#11141d', border: '1px solid #f472b633', borderRadius: '12px', padding: '16px 18px', marginRight: '16px', marginBottom: '16px', overflow: 'hidden' }}>
      <div style={{ display: 'flex', position: 'absolute', top: 0, left: 0, width: '100%', height: '2px', background: '#f472b6' }}><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', marginBottom: '8px' }}>
        <div style={{ display: 'flex', alignItems: 'center' }}>
          <div style={{ display: 'flex', width: '8px', height: '8px', borderRadius: '50%', background: '#f472b6', marginRight: '9px' }}><animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite" /></div>
          <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#f472b6' }}>Gustave AI</div>
        </div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#f472b6', background: '#f472b61a', borderRadius: '6px', padding: '2px 8px' }}>2024</div>
      </div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5', marginBottom: '11px' }}>Chatbot IA conciergerie Airbnb · fine-tuning Mistral par logement</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Next.js</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Mistral</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Laravel</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Docker</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', position: 'relative', width: '396px', background: '#11141d', border: '1px solid #34d39933', borderRadius: '12px', padding: '16px 18px', marginBottom: '16px', overflow: 'hidden' }}>
      <div style={{ display: 'flex', position: 'absolute', top: 0, left: 0, width: '100%', height: '2px', background: '#34d399' }}><animate attributeName="opacity" values="0.3;1;0.3" dur="3s" repeatCount="indefinite" /></div>
      <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', marginBottom: '8px' }}>
        <div style={{ display: 'flex', alignItems: 'center' }}>
          <div style={{ display: 'flex', width: '8px', height: '8px', borderRadius: '50%', background: '#34d399', marginRight: '9px' }}><animate attributeName="opacity" values="1;0.35;1" dur="2.4s" repeatCount="indefinite" /></div>
          <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#34d399' }}>Dubba</div>
        </div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#34d399', background: '#34d3991a', borderRadius: '6px', padding: '2px 8px' }}>2025</div>
      </div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5', marginBottom: '11px' }}>Plateforme web de doublage vidéo · word-level + diarisation</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>Next.js</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>AssemblyAI</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>ElevenLabs</div>
        <div style={{ display: 'flex', fontSize: '11px', color: '#cbd5e1', background: '#1e2330', borderRadius: '6px', padding: '2px 8px', marginRight: '6px', marginTop: '2px' }}>FastAPI</div>
      </div>
    </div>
  </div>
</div>
```
```aura width=900 height=150 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: 'linear-gradient(90deg,#0a0c14,#11141d)', borderRadius: '16px', overflow: 'hidden', fontFamily: 'Inter' }}>
  <svg width="900" height="3" viewBox="0 0 900 3" style={{ display: 'block' }}>
    <defs><linearGradient id="sweep" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stopColor="#22d3ee" /><stop offset="50%" stopColor="#a78bfa" /><stop offset="100%" stopColor="#f472b6" /></linearGradient></defs>
    <rect x="0" y="0" width="900" height="3" fill="url(#sweep)"><animate attributeName="opacity" values="0.4;1;0.4" dur="3s" repeatCount="indefinite" /></rect>
    <rect x="0" y="0" width="120" height="3" fill="#ffffff" opacity="0.6"><animate attributeName="x" values="-120;900" dur="4s" repeatCount="indefinite" /></rect>
  </svg>
  <div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', flexGrow: 1, padding: '0 36px' }}>
    <div style={{ display: 'flex', flexDirection: 'column' }}>
      <div style={{ display: 'flex', fontSize: '19px', fontWeight: 700, color: 'transparent', backgroundImage: 'linear-gradient(90deg,#e2e8f0,#94a3b8)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>Let's build something great.</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#64748b', marginTop: '5px' }}>HETIC · Mastère CTO & Tech Lead — disponible en CDI</div>
    </div>
    <div style={{ display: 'flex' }}>
      <div style={{ display: 'flex', fontSize: '13px', color: '#a7f3d0', background: '#34d39914', border: '1px solid #34d39944', borderRadius: '10px', padding: '8px 16px', marginLeft: '10px' }}>Email</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee14', border: '1px solid #22d3ee44', borderRadius: '10px', padding: '8px 16px', marginLeft: '10px' }}>in/Hassan-Aidibe</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b614', border: '1px solid #f472b644', borderRadius: '10px', padding: '8px 16px', marginLeft: '10px' }}>@HascoVice</div>
    </div>
  </div>
</div>
```
