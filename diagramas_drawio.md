# Diagramas para Draw.io — Charla Meta-Rock

Cada sección tiene la descripción del diagrama y el XML para importar en draw.io (File → Open From → Device, o Edit → XML).

---

## Slide 7 — Amazon Bedrock: Menú de modelos

Bedrock arriba al centro, 5 modelos abajo conectados. Claude marcado como "Elegido". 2400 x 700px

```xml
<mxfile>
  <diagram name="Bedrock Models">
    <mxGraphModel dx="1200" dy="600" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="2" value="Amazon Bedrock&#xa;Fully Managed" style="rounded=1;whiteSpace=wrap;fillColor=#4A1A6B;strokeColor=#9333EA;fontColor=#FFFFFF;fontSize=16;fontStyle=1;arcSize=20;verticalAlign=middle;" vertex="1" parent="1"><mxGeometry x="400" y="30" width="250" height="90" as="geometry"/></mxCell>
        <mxCell id="3" value="Claude&#xa;Anthropic" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FF9900;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="30" y="200" width="140" height="70" as="geometry"/></mxCell>
        <mxCell id="4" value="✅ Elegido" style="rounded=1;whiteSpace=wrap;fillColor=#FF9900;strokeColor=none;fontColor=#1A2332;fontSize=10;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="55" y="280" width="90" height="25" as="geometry"/></mxCell>
        <mxCell id="5" value="Llama&#xa;Meta" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#0668E1;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="220" y="200" width="140" height="70" as="geometry"/></mxCell>
        <mxCell id="6" value="Titan&#xa;Amazon" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#61BC63;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="410" y="200" width="140" height="70" as="geometry"/></mxCell>
        <mxCell id="7" value="Mistral&#xa;Mistral AI" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#34D399;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="600" y="200" width="140" height="70" as="geometry"/></mxCell>
        <mxCell id="8" value="Cohere&#xa;Cohere" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FFCC00;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="790" y="200" width="140" height="70" as="geometry"/></mxCell>
        <mxCell id="10" style="edgeStyle=orthogonalEdgeStyle;strokeColor=#FF9900;" edge="1" source="2" target="3" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="11" style="edgeStyle=orthogonalEdgeStyle;strokeColor=#0668E1;" edge="1" source="2" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="12" style="edgeStyle=orthogonalEdgeStyle;strokeColor=#61BC63;" edge="1" source="2" target="6" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="13" style="edgeStyle=orthogonalEdgeStyle;strokeColor=#34D399;" edge="1" source="2" target="7" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="14" style="edgeStyle=orthogonalEdgeStyle;strokeColor=#FFCC00;" edge="1" source="2" target="8" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="15" value="🚀 Sin servidores" style="text;fontColor=#FFFFFF;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="100" y="370" width="160" height="30" as="geometry"/></mxCell>
        <mxCell id="16" value="💰 Pago por uso" style="text;fontColor=#FFFFFF;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="380" y="370" width="160" height="30" as="geometry"/></mxCell>
        <mxCell id="17" value="🔄 Cambiar modelo = 1 línea" style="text;fontColor=#FFFFFF;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="640" y="370" width="220" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Slide 8 — IA Multimodal: Texto + Imagen → Respuesta

Flujo horizontal: Texto + Imagen → Claude → Respuesta. 2400 x 700px

```xml
<mxfile>
  <diagram name="Multimodal">
    <mxGraphModel dx="1200" dy="450" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="t" value="IA Multimodal: Texto + Imagen → Respuesta" style="text;fontColor=#FFFFFF;fontSize=18;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="10" width="500" height="30" as="geometry"/></mxCell>
        <mxCell id="2" value="📝 &quot;¿Qué ves?&quot;&#xa;Texto" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FF9900;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="30" y="100" width="160" height="90" as="geometry"/></mxCell>
        <mxCell id="p" value="+" style="text;fontColor=#FF9900;fontSize=28;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="120" width="40" height="40" as="geometry"/></mxCell>
        <mxCell id="3" value="📷 Frame&#xa;Imagen JPEG" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#0668E1;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="250" y="100" width="160" height="90" as="geometry"/></mxCell>
        <mxCell id="4" value="🧠 Claude&#xa;Sonnet 4.5" style="rounded=1;whiteSpace=wrap;fillColor=#4A1A6B;strokeColor=#9333EA;fontColor=#FFFFFF;fontSize=14;fontStyle=1;arcSize=15;" vertex="1" parent="1"><mxGeometry x="510" y="100" width="160" height="90" as="geometry"/></mxCell>
        <mxCell id="5" value="💬 &quot;Veo una sala&#xa;con personas...&quot;&#xa;Respuesta" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#61BC63;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="770" y="100" width="170" height="90" as="geometry"/></mxCell>
        <mxCell id="6" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="3" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="7" style="strokeColor=#61BC63;strokeWidth=2;endArrow=block;" edge="1" source="4" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="8" value="Un solo request. Texto e imagen juntos. Bedrock hace el resto." style="text;fontColor=#AAB7C4;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="250" width="500" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Slide 9 — Arquitectura Meta-Rock

4 cajas horizontales: Meta Ray-Ban → App Android → Amazon Bedrock → Respuesta TTS. 2400 x 700px

```xml
<mxfile>
  <diagram name="Arquitectura">
    <mxGraphModel dx="1200" dy="600" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="t" value="Arquitectura Meta-Rock" style="text;fontColor=#FFFFFF;fontSize=22;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="300" y="15" width="400" height="35" as="geometry"/></mxCell>
        <mxCell id="2" value="🕶️ Meta Ray-Ban&#xa;Cámara + Mic" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#0668E1;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="30" y="140" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="3" value="📱 App Android&#xa;Kotlin + Compose" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FF9900;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="300" y="140" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="4" value="☁️ Amazon Bedrock&#xa;Claude Sonnet 4.5" style="rounded=1;whiteSpace=wrap;fillColor=#4A1A6B;strokeColor=#9333EA;fontColor=#FFFFFF;fontSize=13;fontStyle=1;arcSize=15;" vertex="1" parent="1"><mxGeometry x="570" y="140" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="5" value="🔊 Respuesta&#xa;Text-to-Speech" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#61BC63;fontColor=#FFFFFF;fontSize=13;arcSize=15;" vertex="1" parent="1"><mxGeometry x="840" y="140" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="6" value="Bluetooth" style="strokeColor=#58A6FF;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=11;labelBackgroundColor=none;" edge="1" source="2" target="3" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="7" value="HTTPS API" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=11;labelBackgroundColor=none;" edge="1" source="3" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="8" value="Respuesta" style="strokeColor=#61BC63;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=11;labelBackgroundColor=none;" edge="1" source="4" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="9" value="📝 Texto + 📷 Imagen  →  🧠 Análisis multimodal  →  💬 Respuesta por voz" style="text;fontColor=#AAB7C4;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="150" y="300" width="600" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Slide 11 — Wake Word: Flujo sin SDKs comerciales

4 pasos horizontales: SpeechRecognizer → Resultados parciales → Detección → ¡Activar! 2400 x 700px

```xml
<mxfile>
  <diagram name="Wake Word">
    <mxGraphModel dx="1200" dy="450" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="t" value="Wake Word: Cómo funciona sin SDKs comerciales" style="text;fontColor=#FFFFFF;fontSize=18;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="10" width="500" height="30" as="geometry"/></mxCell>
        <mxCell id="2" value="🎤 SpeechRecognizer&#xa;Escucha continua" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FFFFFF;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="30" y="100" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="3" value="📝 Resultados parciales&#xa;&quot;oye vier...&quot;" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FFCC00;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="280" y="100" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="4" value="🔍 Detección&#xa;contains(&quot;oye viernes&quot;)" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FF9900;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="530" y="100" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="5" value="⚡ ¡Activar!&#xa;onWakeWord()" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#61BC63;fontColor=#FFFFFF;fontSize=12;fontStyle=1;arcSize=15;" vertex="1" parent="1"><mxGeometry x="780" y="100" width="180" height="80" as="geometry"/></mxCell>
        <mxCell id="6" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="2" target="3" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="7" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="3" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="8" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="4" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="9" value="💡 EXTRA_PARTIAL_RESULTS = true  →  Android manda texto mientras hablas" style="text;fontColor=#AAB7C4;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="150" y="260" width="600" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Slide 13 — Pipeline: De video crudo a imagen para la IA

5 pasos: Video I420 (~2MB) → NV21 → JPEG 85% (~150KB) → Scale 512px (~30KB) → Bedrock.

```xml
<mxfile>
  <diagram name="Image Pipeline">
    <mxGraphModel dx="1200" dy="450" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="t" value="Pipeline: De video crudo a imagen para la IA" style="text;fontColor=#FFFFFF;fontSize=18;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="10" width="500" height="30" as="geometry"/></mxCell>
        <mxCell id="2" value="📹 Video I420&#xa;30fps raw" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#AAAAAA;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="10" y="110" width="150" height="70" as="geometry"/></mxCell>
        <mxCell id="2b" value="~2MB" style="text;fontColor=#FF9900;fontSize=10;align=center;" vertex="1" parent="1"><mxGeometry x="110" y="90" width="50" height="20" as="geometry"/></mxCell>
        <mxCell id="3" value="🔄 NV21&#xa;Android format" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#0668E1;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="210" y="110" width="150" height="70" as="geometry"/></mxCell>
        <mxCell id="4" value="🖼️ JPEG 85%&#xa;Para pantalla" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FFCC00;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="410" y="110" width="150" height="70" as="geometry"/></mxCell>
        <mxCell id="4b" value="~150KB" style="text;fontColor=#FF9900;fontSize=10;align=center;" vertex="1" parent="1"><mxGeometry x="510" y="90" width="50" height="20" as="geometry"/></mxCell>
        <mxCell id="5" value="📐 Scale 512px&#xa;JPEG 60%" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#FF9900;fontColor=#FFFFFF;fontSize=12;arcSize=15;" vertex="1" parent="1"><mxGeometry x="610" y="110" width="150" height="70" as="geometry"/></mxCell>
        <mxCell id="5b" value="~30KB" style="text;fontColor=#FF9900;fontSize=10;align=center;" vertex="1" parent="1"><mxGeometry x="710" y="90" width="50" height="20" as="geometry"/></mxCell>
        <mxCell id="6" value="☁️ Bedrock&#xa;¡Listo!" style="rounded=1;whiteSpace=wrap;fillColor=#1A2332;strokeColor=#61BC63;fontColor=#FFFFFF;fontSize=12;fontStyle=1;arcSize=15;" vertex="1" parent="1"><mxGeometry x="810" y="110" width="150" height="70" as="geometry"/></mxCell>
        <mxCell id="6b" value="✅" style="text;fontColor=#61BC63;fontSize=10;align=center;" vertex="1" parent="1"><mxGeometry x="920" y="90" width="30" height="20" as="geometry"/></mxCell>
        <mxCell id="e1" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="2" target="3" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e2" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="3" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e3" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="4" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e4" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;" edge="1" source="5" target="6" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="9" value="De ~2MB a ~30KB  →  Rápido de enviar, barato de procesar" style="text;fontColor=#FF9900;fontSize=13;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="260" width="500" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Slide 16 — Máquina de Estados: Viernes

Flujo circular: IDLE → LISTENING → PROCESSING → RESPONDING → IDLE. Con labels entre cada estado. 2400 x 700px

```xml
<mxfile>
  <diagram name="State Machine">
    <mxGraphModel dx="1200" dy="500" grid="1" background="#1A2332">
      <root>
        <mxCell id="0"/>
        <mxCell id="1" parent="0"/>
        <mxCell id="t" value="Máquina de Estados — Viernes" style="text;fontColor=#FFFFFF;fontSize=20;fontStyle=1;align=center;" vertex="1" parent="1"><mxGeometry x="300" y="10" width="400" height="35" as="geometry"/></mxCell>
        <mxCell id="2" value="😴&#xa;IDLE" style="ellipse;whiteSpace=wrap;fillColor=#3C4656;strokeColor=#AAAAAA;fontColor=#FFFFFF;fontSize=13;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="30" y="120" width="100" height="100" as="geometry"/></mxCell>
        <mxCell id="3" value="🎤&#xa;LISTENING" style="ellipse;whiteSpace=wrap;fillColor=#4A2800;strokeColor=#FF9900;fontColor=#FF9900;fontSize=13;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="230" y="120" width="100" height="100" as="geometry"/></mxCell>
        <mxCell id="4" value="⚙️&#xa;PROCESSING" style="ellipse;whiteSpace=wrap;fillColor=#4A4000;strokeColor=#FFCC00;fontColor=#FFCC00;fontSize=12;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="430" y="120" width="100" height="100" as="geometry"/></mxCell>
        <mxCell id="5" value="💬&#xa;RESPONDING" style="ellipse;whiteSpace=wrap;fillColor=#1A3A1A;strokeColor=#61BC63;fontColor=#61BC63;fontSize=12;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="630" y="120" width="100" height="100" as="geometry"/></mxCell>
        <mxCell id="6" value="😴&#xa;IDLE" style="ellipse;whiteSpace=wrap;fillColor=#3C4656;strokeColor=#AAAAAA;fontColor=#FFFFFF;fontSize=13;fontStyle=1;" vertex="1" parent="1"><mxGeometry x="830" y="120" width="100" height="100" as="geometry"/></mxCell>
        <mxCell id="e1" value="&quot;Oye Viernes&quot;" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=10;labelBackgroundColor=none;" edge="1" source="2" target="3" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e2" value="Transcript" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=10;labelBackgroundColor=none;" edge="1" source="3" target="4" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e3" value="Bedrock" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=10;labelBackgroundColor=none;" edge="1" source="4" target="5" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="e4" value="TTS done" style="strokeColor=#FF9900;strokeWidth=2;endArrow=block;fontColor=#AAB7C4;fontSize=10;labelBackgroundColor=none;" edge="1" source="5" target="6" parent="1"><mxGeometry relative="1" as="geometry"/></mxCell>
        <mxCell id="err" value="❌ Error → vuelve a IDLE" style="text;fontColor=#FF3B30;fontSize=11;align=center;" vertex="1" parent="1"><mxGeometry x="370" y="280" width="200" height="25" as="geometry"/></mxCell>
        <mxCell id="modes" value="Voz → vuelve a IDLE  |  Botón 🎤 → vuelve a LISTENING" style="text;fontColor=#AAB7C4;fontSize=12;align=center;" vertex="1" parent="1"><mxGeometry x="200" y="330" width="500" height="30" as="geometry"/></mxCell>
      </root>
    </mxGraphModel>
  </diagram>
</mxfile>
```

---

## Instrucciones

1. Abrir [draw.io](https://app.diagrams.net/)
2. Extras → Edit Diagram (o Ctrl+Shift+X)
3. Pegar el XML de cada diagrama
4. Click "Close" → se renderiza
5. Exportar como PNG (File → Export as → PNG, escala 2x, fondo transparente o `#1A2332`)
6. Insertar en la slide correspondiente de PowerPoint
