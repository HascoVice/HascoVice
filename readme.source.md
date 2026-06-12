```aura width=900 height=280 align=center
<div style={{ display: 'flex', position: 'relative', width: '100%', height: '100%', background: '#04050a', borderRadius: '16px', alignItems: 'center', justifyContent: 'center', overflow: 'hidden' }}>
  <svg width="900" height="280" viewBox="0 0 900 280" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="28%" cy="35%" r="60%">
        <stop offset="0%" stopColor="#7c3aed" stopOpacity="0.9" />
        <stop offset="100%" stopColor="#04050a" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="g2" cx="74%" cy="68%" r="55%">
        <stop offset="0%" stopColor="#06b6d4" stopOpacity="0.85" />
        <stop offset="100%" stopColor="#04050a" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="g3" cx="55%" cy="50%" r="45%">
        <stop offset="0%" stopColor="#f472b6" stopOpacity="0.4" />
        <stop offset="100%" stopColor="#04050a" stopOpacity="0" />
      </radialGradient>
      <linearGradient id="ln" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stopColor="#22d3ee" />
        <stop offset="50%" stopColor="#a78bfa" />
        <stop offset="100%" stopColor="#f472b6" />
      </linearGradient>
    </defs>
    <rect x="0" y="0" width="900" height="280" fill="#04050a" />
    <ellipse cx="250" cy="90" rx="340" ry="190" fill="url(#g1)">
      <animate attributeName="opacity" values="0.5;0.95;0.5" dur="5s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="-60 0;60 0;-60 0" dur="10s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="660" cy="170" rx="320" ry="180" fill="url(#g2)">
      <animate attributeName="opacity" values="0.95;0.5;0.95" dur="7s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="60 0;-60 0;60 0" dur="13s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="450" cy="130" rx="260" ry="150" fill="url(#g3)">
      <animate attributeName="opacity" values="0.3;0.7;0.3" dur="6s" repeatCount="indefinite" />
    </ellipse>
    <line x1="170" y1="206" x2="730" y2="206" stroke="url(#ln)" strokeWidth="2.5" strokeDasharray="900" strokeDashoffset="900">
      <animate attributeName="strokeDashoffset" values="900;0" dur="3.5s" repeatCount="indefinite" />
    </line>
  </svg>
  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', zIndex: 2 }}>
    <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '76px', fontWeight: 800, letterSpacing: '3px', color: 'transparent', backgroundImage: 'linear-gradient(90deg,#22d3ee,#a78bfa,#f472b6)', backgroundClip: 'text', WebkitBackgroundClip: 'text' }}>HASSAN AIDIBE</div>
    <div style={{ display: 'flex', fontFamily: 'Inter', fontSize: '17px', fontWeight: 600, letterSpacing: '9px', color: '#cbd5e1', marginTop: '6px' }}>FULLSTACK DEVELOPER</div>
    <div style={{ display: 'flex', marginTop: '20px' }}>
      <div style={{ display: 'flex', fontSize: '13px', color: '#22d3ee', border: '1px solid #22d3ee55', borderRadius: '20px', padding: '5px 14px', marginRight: '10px' }}>6 yrs XP</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#a78bfa', border: '1px solid #a78bfa55', borderRadius: '20px', padding: '5px 14px', marginRight: '10px' }}>3 SaaS shipped</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#f472b6', border: '1px solid #f472b655', borderRadius: '20px', padding: '5px 14px' }}>open to CDI</div>
    </div>
  </div>
</div>
```

```aura width=900 height=420 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '16px', padding: '28px 32px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', alignItems: 'center', marginBottom: '22px' }}>
    <div style={{ display: 'flex', width: '4px', height: '22px', background: 'linear-gradient(180deg,#22d3ee,#a78bfa)', borderRadius: '2px', marginRight: '12px' }}></div>
    <div style={{ display: 'flex', fontSize: '20px', fontWeight: 700, color: '#f1f5f9' }}>Tech Stack</div>
  </div>
  <div style={{ display: 'flex', flexWrap: 'wrap' }}>
    <div style={{ display: 'flex', flexDirection: 'column', width: '410px', marginRight: '20px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#a78bfa', marginBottom: '10px' }}>FRONTEND</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>React</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Next.js</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Vue.js</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>React Native</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>TypeScript</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#c4b5fd', background: '#a78bfa1a', border: '1px solid #a78bfa44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>TailwindCSS</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '410px', marginBottom: '18px' }}>
      <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#22d3ee', marginBottom: '10px' }}>BACKEND</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Node.js</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Express</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Laravel</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Symfony</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>PHP</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Golang</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee1a', border: '1px solid #22d3ee44', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>GraphQL</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '410px', marginRight: '20px' }}>
      <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#f472b6', marginBottom: '10px' }}>INFRA & DEVOPS</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Docker</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Kubernetes</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Terraform</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b61a', border: '1px solid #f472b644', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>GitHub Actions</div>
      </div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '410px' }}>
      <div style={{ display: 'flex', fontSize: '12px', fontWeight: 700, letterSpacing: '2px', color: '#34d399', marginBottom: '10px' }}>AI / ML & DATA</div>
      <div style={{ display: 'flex', flexWrap: 'wrap' }}>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Mistral</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>AssemblyAI</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>ElevenLabs</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#a7f3d0', background: '#34d3991a', border: '1px solid #34d39944', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>GPT-4o</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fde68a', background: '#fbbf241a', border: '1px solid #fbbf2444', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>PostgreSQL</div>
        <div style={{ display: 'flex', fontSize: '13px', color: '#fde68a', background: '#fbbf241a', border: '1px solid #fbbf2444', borderRadius: '8px', padding: '4px 11px', marginRight: '7px', marginBottom: '7px' }}>Redis</div>
      </div>
    </div>
  </div>
</div>
```

```aura width=900 height=300 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '16px', padding: '28px 32px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', alignItems: 'center', marginBottom: '20px' }}>
    <div style={{ display: 'flex', width: '4px', height: '22px', background: 'linear-gradient(180deg,#a78bfa,#f472b6)', borderRadius: '2px', marginRight: '12px' }}></div>
    <div style={{ display: 'flex', fontSize: '20px', fontWeight: 700, color: '#f1f5f9' }}>Shipped Projects</div>
  </div>
  <div style={{ display: 'flex', flexWrap: 'wrap' }}>
    <div style={{ display: 'flex', flexDirection: 'column', width: '396px', background: '#11141d', border: '1px solid #22d3ee33', borderRadius: '12px', padding: '16px 18px', marginRight: '16px', marginBottom: '16px' }}>
      <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#22d3ee', marginBottom: '6px' }}>Klark</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5' }}>SaaS B2B all-in-one · 12 modules métier en micro-frontends (Module Federation)</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '396px', background: '#11141d', border: '1px solid #a78bfa33', borderRadius: '12px', padding: '16px 18px', marginBottom: '16px' }}>
      <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#a78bfa', marginBottom: '6px' }}>Soluweld</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5' }}>SaaS B2B · gestion & coordination du soudage industriel</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '396px', background: '#11141d', border: '1px solid #f472b633', borderRadius: '12px', padding: '16px 18px', marginRight: '16px' }}>
      <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#f472b6', marginBottom: '6px' }}>Gustave AI</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5' }}>Chatbot IA conciergerie Airbnb · fine-tuning Mistral par logement</div>
    </div>
    <div style={{ display: 'flex', flexDirection: 'column', width: '396px', background: '#11141d', border: '1px solid #34d39933', borderRadius: '12px', padding: '16px 18px' }}>
      <div style={{ display: 'flex', fontSize: '16px', fontWeight: 700, color: '#34d399', marginBottom: '6px' }}>Dubba</div>
      <div style={{ display: 'flex', fontSize: '13px', color: '#94a3b8', lineHeight: '1.5' }}>Plateforme web de doublage vidéo · word-level + diarisation</div>
    </div>
  </div>
</div>
```

```aura width=900 height=130 align=center
<div style={{ display: 'flex', alignItems: 'center', justifyContent: 'space-between', width: '100%', height: '100%', background: 'linear-gradient(90deg,#0a0c14,#11141d)', borderRadius: '16px', padding: '0 36px', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', flexDirection: 'column' }}>
    <div style={{ display: 'flex', fontSize: '18px', fontWeight: 700, color: '#f1f5f9' }}>Let's build something great.</div>
    <div style={{ display: 'flex', fontSize: '13px', color: '#64748b', marginTop: '4px' }}>HETIC · Mastère CTO & Tech Lead</div>
  </div>
  <div style={{ display: 'flex' }}>
    <div style={{ display: 'flex', fontSize: '13px', color: '#a5f3fc', background: '#22d3ee14', border: '1px solid #22d3ee44', borderRadius: '10px', padding: '8px 16px', marginLeft: '10px' }}>in/Hassan-Aidibe</div>
    <div style={{ display: 'flex', fontSize: '13px', color: '#fbcfe8', background: '#f472b614', border: '1px solid #f472b644', borderRadius: '10px', padding: '8px 16px', marginLeft: '10px' }}>@HascoVice</div>
  </div>
</div>
```
