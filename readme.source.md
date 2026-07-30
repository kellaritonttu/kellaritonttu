```aura width=800 height=210
<div style={{
  display: 'flex',
  flexDirection: 'column',
  alignItems: 'center',
  justifyContent: 'center',
  width: '100%',
  height: '100%',
  background: 'linear-gradient(135deg, #1a1210 0%, #130e0a 60%, #0a0f08 100%)',
  borderRadius: '16px',
  border: '1px solid #2e1f1a',
  gap: '18px',
  position: 'relative',
  overflow: 'hidden',
}}>
  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '0',
    left: '0',
    right: '0',
    height: '3px',
    background: 'linear-gradient(90deg, #ff4500 0%, #ff8c42 50%, #3db86a 100%)',
  }} />

  <div style={{
    display: 'flex',
    position: 'absolute',
    top: '-60px',
    right: '-60px',
    width: '200px',
    height: '200px',
    borderRadius: '50%',
    background: 'radial-gradient(circle, rgba(255,69,0,0.08) 0%, transparent 70%)',
  }} />

  <div style={{
    display: 'flex',
    alignItems: 'center',
    gap: '20px',
  }}>
    <div style={{
      display: 'flex',
      width: '76px',
      height: '76px',
      borderRadius: '50%',
      background: 'linear-gradient(135deg, #ff4500, #ff8c42, #3db86a)',
      alignItems: 'center',
      justifyContent: 'center',
    }}>
      <div style={{
        display: 'flex',
        width: '70px',
        height: '70px',
        borderRadius: '50%',
        overflow: 'hidden',
        border: '2px solid #1a1210',
      }}>
        <img
          src="https://github.com/kellaritonttu.png"
          style={{
            width: '70px',
            height: '70px',
          }}
        />
      </div>
    </div>

    <div style={{ display: 'flex', flexDirection: 'column', gap: '5px' }}>
      <span style={{
        fontSize: '38px',
        fontWeight: '700',
        color: '#e8e0d8',
        letterSpacing: '-1px',
      }}>
        Oleksii
      </span>
      <span style={{
        fontSize: '14px',
        color: '#ff8c42',
        fontWeight: '500',
        letterSpacing: '1.5px',
        textTransform: 'uppercase',
      }}>
        DevOps · Cloud Engineer · Open Source
      </span>
    </div>
  </div>

  <div style={{ display: 'flex', gap: '8px' }}>
    {[
      { tag: 'DevOps',  bg: 'rgba(255,69,0,0.12)',    border: '#ff4500', color: '#ff4500' },
      { tag: 'AWS',     bg: 'rgba(255,140,66,0.12)',   border: '#ff8c42', color: '#ff8c42' },
      { tag: 'GCP',     bg: 'rgba(61,184,106,0.12)',   border: '#3db86a', color: '#3db86a' },
      { tag: 'Python',  bg: 'rgba(168,197,168,0.12)',  border: '#4ade80', color: '#4ade80' },
    ].map(({ tag, bg, border, color }) => (
      <div key={tag} style={{
        display: 'flex',
        padding: '4px 14px',
        borderRadius: '999px',
        background: bg,
        border: `1px solid ${border}`,
        color: color,
        fontSize: '12px',
        fontWeight: '700',
        letterSpacing: '0.8px',
        textTransform: 'uppercase',
      }}>
        {tag}
      </div>
    ))}
  </div>
</div>
```

[![GitHub Stats](https://ghstats.dev/api/card?username=kellaritonttu&theme=catppuccin&hide=trend%2Cavg%2Cactive_day%2Cgrade%2Ccontributions%2Crepos%2Cfollowers&custom_title=Stats&border_radius=10)](https://github.com/kellaritonttu)
