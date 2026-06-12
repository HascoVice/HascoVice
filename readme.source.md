```aura width=900 height=240 align=center
<div style={{ display: 'flex', width: '100%', height: '100%' }}>
  <svg width="900" height="240" viewBox="0 0 900 240">
    <defs>
      <radialGradient id="g1" cx="30%" cy="40%" r="60%">
        <stop offset="0%" stopColor="#7c3aed" stopOpacity="0.9" />
        <stop offset="100%" stopColor="#05060a" stopOpacity="0" />
      </radialGradient>
      <radialGradient id="g2" cx="75%" cy="60%" r="55%">
        <stop offset="0%" stopColor="#06b6d4" stopOpacity="0.85" />
        <stop offset="100%" stopColor="#05060a" stopOpacity="0" />
      </radialGradient>
      <linearGradient id="txt" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stopColor="#22d3ee">
          <animate attributeName="stopColor" values="#22d3ee;#a78bfa;#f472b6;#22d3ee" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="50%" stopColor="#a78bfa">
          <animate attributeName="stopColor" values="#a78bfa;#f472b6;#22d3ee;#a78bfa" dur="6s" repeatCount="indefinite" />
        </stop>
        <stop offset="100%" stopColor="#f472b6">
          <animate attributeName="stopColor" values="#f472b6;#22d3ee;#a78bfa;#f472b6" dur="6s" repeatCount="indefinite" />
        </stop>
      </linearGradient>
    </defs>
    <rect x="0" y="0" width="900" height="240" fill="#05060a" />
    <ellipse cx="270" cy="100" rx="320" ry="180" fill="url(#g1)">
      <animate attributeName="opacity" values="0.4;0.9;0.4" dur="5s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="-50 0;50 0;-50 0" dur="9s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="650" cy="150" rx="300" ry="170" fill="url(#g2)">
      <animate attributeName="opacity" values="0.9;0.4;0.9" dur="7s" repeatCount="indefinite" />
      <animateTransform attributeName="transform" type="translate" values="50 0;-50 0;50 0" dur="12s" repeatCount="indefinite" />
    </ellipse>
    <line x1="80" y1="186" x2="820" y2="186" stroke="url(#txt)" strokeWidth="2" strokeDasharray="1200" strokeDashoffset="1200">
      <animate attributeName="strokeDashoffset" values="1200;0" dur="3s" repeatCount="indefinite" />
    </line>
    <text x="450" y="120" fontFamily="Inter" fontSize="74" fontWeight="800" fill="url(#txt)" textAnchor="middle" letterSpacing="3">HASSAN AIDIBE</text>
    <text x="450" y="162" fontFamily="Inter" fontSize="19" fontWeight="500" fill="#94a3b8" textAnchor="middle" letterSpacing="8">FULLSTACK DEVELOPER</text>
  </svg>
</div>
```

```aura width=900 height=66 align=center
<div style={{ display: 'flex', width: '100%', height: '100%' }}>
  <svg width="900" height="66" viewBox="0 0 900 66">
    <rect x="0" y="0" width="900" height="66" fill="#0a0c14" rx="10" />
    <circle cx="26" cy="33" r="6" fill="#ff5f56" />
    <circle cx="48" cy="33" r="6" fill="#ffbd2e" />
    <circle cx="70" cy="33" r="6" fill="#27c93f" />
    <text x="106" y="40" fontFamily="Inter" fontSize="18" fill="#22d3ee">~ $</text>
    <text x="146" y="40" fontFamily="Inter" fontSize="18" fill="#e2e8f0">shipping SaaS in production · open to CDI</text>
    <rect x="648" y="24" width="11" height="20" fill="#a78bfa">
      <animate attributeName="opacity" values="1;1;0;0" dur="1s" repeatCount="indefinite" />
    </rect>
  </svg>
</div>
```

```aura width=900 height=300 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#0a0c14', borderRadius: '12px', padding: '24px 30px', color: '#e2e8f0', fontFamily: 'Inter' }}>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', marginBottom: '14px' }}>hassan@dev:~$ whoami --stack</div>
  <div style={{ display: 'flex', flexDirection: 'column', fontSize: '15px', lineHeight: '1.7' }}>
    <div style={{ display: 'flex' }}><span style={{ color: '#a78bfa', width: '110px' }}>front</span><span style={{ color: '#e2e8f0' }}>React · Next.js · Vue.js · React Native · TypeScript · TailwindCSS</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#22d3ee', width: '110px' }}>back</span><span style={{ color: '#e2e8f0' }}>Node.js · Express · Laravel · Symfony · PHP · Golang · GraphQL</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#f472b6', width: '110px' }}>infra</span><span style={{ color: '#e2e8f0' }}>Docker · Kubernetes · Terraform · GitHub Actions</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#34d399', width: '110px' }}>ai / ml</span><span style={{ color: '#e2e8f0' }}>Mistral · AssemblyAI · ElevenLabs · GPT-4o · Claude Code</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#fbbf24', width: '110px' }}>data</span><span style={{ color: '#e2e8f0' }}>PostgreSQL · MySQL · Redis</span></div>
  </div>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', margin: '18px 0 12px' }}>hassan@dev:~$ ls --shipped</div>
  <div style={{ display: 'flex', flexDirection: 'column', fontSize: '14px', lineHeight: '1.7' }}>
    <div style={{ display: 'flex' }}><span style={{ color: '#22d3ee', width: '120px' }}>Klark</span><span style={{ color: '#94a3b8' }}>SaaS B2B all-in-one · 12 modules · micro-frontends (Module Federation)</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#a78bfa', width: '120px' }}>Soluweld</span><span style={{ color: '#94a3b8' }}>SaaS B2B · gestion & coordination du soudage industriel</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#f472b6', width: '120px' }}>Gustave AI</span><span style={{ color: '#94a3b8' }}>chatbot IA conciergerie Airbnb · fine-tuning Mistral</span></div>
    <div style={{ display: 'flex' }}><span style={{ color: '#34d399', width: '120px' }}>Dubba</span><span style={{ color: '#94a3b8' }}>plateforme web de doublage vidéo · word-level + diarisation</span></div>
  </div>
</div>
```

```aura width=900 height=120 align=center
<div style={{ display: 'flex', flexDirection: 'column', width: '100%', height: '100%', background: '#05060a', borderRadius: '12px', padding: '20px 30px', fontFamily: 'Inter', justifyContent: 'center' }}>
  <div style={{ display: 'flex', color: '#64748b', fontSize: '15px', marginBottom: '10px' }}>hassan@dev:~$ ./contact.sh</div>
  <div style={{ display: 'flex', gap: '28px', fontSize: '15px' }}>
    <span style={{ color: '#22d3ee' }}>HETIC · Mastere CTO & Tech Lead</span>
    <span style={{ color: '#a78bfa' }}>linkedin.com/in/Hassan-Aidibe</span>
    <span style={{ color: '#f472b6' }}>github.com/HascoVice</span>
  </div>
</div>
```
