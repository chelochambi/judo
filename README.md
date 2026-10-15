🥋 Base de Conocimiento de Judo (Jūdō - 柔道)
> *"El Judo no es únicamente un deporte o un método de combate; es una vía de educación integral para el desarrollo físico, mental y moral del individuo."*  
> — **Shihan Jigorō Kanō** (Fundador del Judo)
---
📌 Tabla de Contenidos
📖 Historia y Orígenes
☯️ Principios Filosóficos y Código Moral
🏛️ Clasificación de las Técnicas (Waza)
🥋 Sistema de Grados y Cinturones (Kyu y Dan)
📂 Estructura del Repositorio y Guías de Estudio
---
📖 Historia y Orígenes
El Judo fue fundado en 1882 en Tokio, Japón, por el maestro Jigorō Kanō (嘉納 治五郎). Kanō estudió diversas escuelas clásicas de Jujutsu tradicional (Kitō-ryū y Tenjin Shin'yō-ryū), caracterizadas por el combate cuerpo a cuerpo de los guerreros samuráis.
Refinando estas técnicas y eliminando los ataques letales o peligrosos, estructuró un método educativo en su escuela, el Kodokan (講道館), transformando un arte de combate (Bujutsu) en una vía de desarrollo personal y disciplina de vida (Budō).
⏳ Hitos Históricos del Judo
```mermaid
timeline
    title Evolución Histórica del Judo Kodokan
    1882 : Fundación del Kodokan en Tokio por Jigorō Kanō
    1895 : Creación del Gokyo-no-Waza (Primera progresión técnica)
    1926 : Creación de la Sección Femenina (Joshi-bu) en el Kodokan
    1951 : Fundación de la Federación Internacional de Judo (IJF)
    1964 : Debut del Judo masculino en los JJ.OO. de Tokio
    1992 : Inclusión oficial del Judo femenino en los JJ.OO. de Barcelona
```
---
☯️ Principios Filosóficos y Código Moral
El Judo se sustenta sobre tres pilares filosóficos interconectados desarrollados por Jigorō Kanō:
Principio	Nombre Japonés	Concepto y Aplicación
Ju	Jū (柔)	Suavidad / Adaptabilidad: Ceder ante la fuerza del oponente para redirigir su energía y vencer sin oponer resistencia directa.
Seiryoku Zen'yo	Seiryoku Zen'yō (精力善用)	Máxima Eficacia con el Mínimo Esfuerzo: Utilizar la energía física y mental de la forma más eficiente posible.
Jita Kyoei	Jita Kyōei (自他共栄)	Prosperidad y Beneficio Mutuo: El progreso individual debe contribuir al bienestar, respeto y desarrollo de la comunidad.
---
📜 El Código Moral del Judoca
Los valores inculcados dentro del Dōjō rigen la conducta y ética del practicante dentro y fuera del tatami:
```mermaid
mindmap
  root((📜 Código Moral del Judoca))
    Cortesía [Cortesía / Reigi<br>Respeto mutuo y trato deferente]
    Valor [Valor / Yūki<br>Hacer lo que es justo]
    Sinceridad [Sinceridad / Makoto<br>Expresarse sin falsedad]
    Honor [Honor / Meiyo<br>Ser fiel a la palabra dada]
    Modestia [Modestia / Kenkyō<br>Evaluar méritos sin soberbia]
    Respeto [Respeto / Sonkei<br>Inspirar y transmitir confianza]
    Autocontrol [Autocontrol / Jidō<br>Dominio de las emociones]
    Amistad [Amistad / Yūjō<br>Fraternidad y solidaridad]
```
---
🏛️ Clasificación de las Técnicas (Waza)
El repertorio del Judo se divide en tres grandes familias técnicas. Las técnicas de proyección (Nage-waza) y de control en suelo (Katame-waza) constituyen el pilar fundamental del aprendizaje diario, mientras que el Atemi-waza se reserva formalmente para las Katas superiores.
```mermaid
graph TD
    classDef main fill:#0284c7,stroke:#bae6fd,stroke-width:2px,color:#ffffff,font-weight:bold;
    classDef branch fill:#1e293b,stroke:#38bdf8,stroke-width:2px,color:#f8fafc;
    classDef leaf fill:#334155,stroke:#94a3b8,stroke-width:1px,color:#e2e8f0;

    Waza["🥋 Técnicas de Judo (Waza)"]:::main

    Nage["Nage-waza<br><b>(Proyecciones)</b>"]:::branch
    Katame["Katame-waza<br><b>(Controles de Suelo)</b>"]:::branch
    Atemi["Atemi-waza<br><b>(Golpeo*)</b>"]:::branch

    Waza --> Nage
    Waza --> Katame
    Waza --> Atemi

    Tachi["Tachi-waza<br><i>(De Pie)</i>"]:::leaf
    Sutemi["Sutemi-waza<br><i>(De Sacrificio)</i>"]:::leaf
    Nage --> Tachi
    Nage --> Sutemi

    Osae["Osaekomi-waza<br><i>(Inmovilizaciones)</i>"]:::leaf
    Shime["Shime-waza<br><i>(Estrangulaciones)</i>"]:::leaf
    Kansetsu["Kansetsu-waza<br><i>(Luxaciones)</i>"]:::leaf
    Katame --> Osae
    Katame --> Shime
    Katame --> Kansetsu
```
---
🥋 Sistema de Grados y Cinturones (Kyu y Dan)
La progresión en Judo se divide en grados estudiantiles (Kyu) y grados de maestría (Dan):
```mermaid
graph LR
    classDef kyu fill:#334155,stroke:#cbd5e1,stroke-width:1px,color:#f8fafc;
    classDef dan fill:#0f172a,stroke:#38bdf8,stroke-width:2px,color:#38bdf8,font-weight:bold;

    subgraph Grados Kyu (Estudiantiles)
        K6["6.º Kyu<br>⚪ Blanco"]:::kyu --> K5["5.º Kyu<br>🟡 Amarillo"]:::kyu
        K5 --> K4["4.º Kyu<br>🟠 Naranja"]:::kyu
        K4 --> K3["3.er Kyu<br>🟢 Verde"]:::kyu
        K3 --> K2["2.º Kyu<br>🔵 Azul"]:::kyu
        K2 --> K1["1.er Kyu<br>🟤 Marrón"]:::kyu
    end

    subgraph Grados Dan (Maestría)
        D1["1.er a 5.º Dan<br>⬛ Cinturón Negro"]:::dan --> D2["6.º a 8.º Dan<br>🔴⚪ Rojo y Blanco"]:::dan
        D2 --> D3["9.º y 10.º Dan<br>🔴 Cinturón Rojo"]:::dan
    end

    K1 --> D1
```
---
📂 Estructura del Repositorio y Guías de Estudio
Este repositorio contiene las guías de estudio interconectadas organizadas por nivel técnico:
Documento / Archivo	Nivel / Contenido	Descripción
🟡 `5-kyu-amarillo.md`	5.º Kyu	Progresión técnica de Gokyo 1 (Nage-waza y Ne-waza).
🟠 `4-kyu-naranja.md`	4.º Kyu	Progresión técnica de Gokyo 2 (Nage-waza y Ne-waza).
🟢 `3-kyu-verde.md`	3.er Kyu	Progresión técnica de Gokyo 3 (Nage-waza y Ne-waza).
🔵 `2-kyu-azul.md`	2.º Kyu	Progresión técnica de Gokyo 4 (Nage-waza y Ne-waza).
🟤 `1-kyu-marron.md`	1.er Kyu	Progresión técnica de Gokyo 5 (Nage-waza y Ne-waza).
🥋 `shodan.md`	1.er Dan / Shodan	Guía integral del Nage-no-Kata y Katame-no-Kata.
📚 `glosario-terminos.md`	General	Diccionario estandarizado de terminología en japonés.
---
<div align="center">
  <em>Desarrollado como guía de estudio y referencia técnica para la práctica del Judo Kodokan.</em>
</div>