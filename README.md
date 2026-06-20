# Lestur — *les saman* ("read together")

A gentle reading tool from **Buinho FabLab** (Messejana, Portugal) for a **grown-up and a child to read side by side**. Built for a child with dyslexia, in **Icelandic** (is-IS), where the obstacle isn't single sounds but holding a whole word together — and where low morale matters as much as skill.

**No levels. No scores the child can see. Never "wrong" — only "again, slower".** Each word read together grows one plant in a garden.

It's a **PWA**: open the link, then *Add to Home Screen*, and it behaves like an app — including offline after the first open. Nothing leaves the device (the garden is stored only in the phone's local storage).

> The cycle is the Buinho **TMI** method in disguise: *Sound it out → Trace → We read it.* Pedagogy: soft mastery + epistemological pluralism (Turkle & Papert).

---

## Uma ferramenta de leitura — *Lestur*

Ferramenta do **Buinho FabLab** para um **adulto ler ao lado de uma criança**. Pensada para uma criança com dislexia, em **islandês**: a ortografia é transparente, por isso o obstáculo não é o fonema isolado mas segurar a palavra inteira — e a **moral** conta tanto como a competência.

**Sem níveis. Sem notas visíveis à criança. Nunca "errado" — só "outra vez, mais devagar".** Cada palavra lida em conjunto faz crescer uma planta no jardim.

É uma **PWA**: abre-se por um link, faz-se *Adicionar ao ecrã inicial*, e comporta-se como app — funciona offline depois da primeira abertura. Nada sai do dispositivo (o jardim fica só no armazenamento local do telemóvel).

---

## How to run / Como correr

It's a static site — no backend. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

Deployed as a static site (Render, GitHub Pages, or Webtuga). Auto-deploy on push.

## Known limits (this version) / Limitações

- **Audio:** uses the browser's Web Speech API with `lang="is-IS"`. Many phones have **no native Icelandic voice**, so words may sound accented. For an honest test, pre-recorded native clips are the next step.
- **Word bank:** a small real sample — *fiskur, hestur, kind, sól*.

## v2 (later) / depois

- AI-generated words & micro-stories tuned to the child's interests ("Claude in Claude"), never repeating.
- Curated Icelandic word bank.
- Optional offline run on a Raspberry Pi (local AI, rural).

---

*Buinho Educativo · CC BY-SA 4.0*
