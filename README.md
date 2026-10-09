# Süleyman Kılınç

Software engineering student at Fırat University, Turkey. From February 2027 I
will be on an Erasmus+ exchange at Częstochowa University of Technology, Poland.

I like projects where the answer can be measured, and where I have to find out
how wrong my first model was. The one I spend most time on is
[PerfHub](https://github.com/SuleymanKilincc/perfhub-ai), a frame-rate
predictor for PC games that publishes its own error.

[Website](https://suleymankilinc.com) ·
[PerfHub, live](https://perfhub.suleymankilinc.com)

## Featured project: PerfHub

A web app that estimates how fast a given CPU, GPU and RAM combination runs
each game in a catalogue of 176. The prediction runs in the browser; there is
no server behind it.

- **A model, not a lookup table.** It models frame time (the slower of the CPU
  and the GPU sets the pace), with separate models for VRAM spill, ray tracing,
  upscaling and frame generation, fitted to several hundred recorded benchmark
  results.
- **Accuracy is published, including where it fails.** The fitted benchmarks,
  the held-out sets and every known gap are written up in
  [CALIBRATION.md](https://github.com/SuleymanKilincc/perfhub-ai/blob/main/CALIBRATION.md),
  with the claims that turned out to be wrong.
- **Two implementations kept honest.** The engine exists in Python and
  TypeScript, and a conformance test compares them over thousands of generated
  cases on every push. The numbers quoted in the README are regenerated from the
  data, and CI fails if one is stale.
- **How it was built.** I source and check the measurements, decide what to
  measure next and test the site against real hardware. The code and the
  analysis are written with Claude Code, and the repository says so, commit by
  commit.

Python · TypeScript · React · FastAPI · SQLite · GitHub Actions

## Other projects

| Project | What it is |
|---|---|
| [paper-lantern-studio-db](https://github.com/SuleymanKilincc/paper-lantern-studio-db) | A game-studio simulation I use to learn PostgreSQL phase by phase: tables grow and get reshaped as the studio does. Runs in Docker Compose. |
| [Saglikta-Yapay-Zeka-Tani-Sistemi](https://github.com/SuleymanKilincc/Saglikta-Yapay-Zeka-Tani-Sistemi) | A chest X-ray classifier (MobileNetV2 transfer learning) behind a Flask web app, with PostgreSQL records and PDF reports. A learning project, not a medical device. Documentation in Turkish. |
| [Donanim-ve-Oyun-Benchmark-Hesaplamasi](https://github.com/SuleymanKilincc/Donanim-ve-Oyun-Benchmark-Hesaplamasi) | A Java console application that scores CPU and GPU pairs and finds the bottleneck. A simpler take on the same question. Documentation in Turkish. |
| [Java-Monopoly-Game](https://github.com/SuleymanKilincc/Java-Monopoly-Game) | A console Monopoly clone for up to four players, written while learning Java collections and object-oriented design. Documentation in Turkish. |

## Skills

<p>
  <img src="https://skillicons.dev/icons?i=python,java,ts,react,postgres,sqlite,docker,git,github,fastapi,flask&theme=dark" alt="Python, Java, TypeScript, React, PostgreSQL, SQLite, Docker, Git, GitHub, FastAPI, Flask" />
</p>

| | |
|---|---|
| **Working with** | Python, Java, TypeScript and React, SQL and PostgreSQL, SQLite, Docker Compose, Git and GitHub, FastAPI and Flask |
| **Learning now** | C# and .NET, relational design in PostgreSQL (schemas, indexes, transactions) |
| **Also** | Machine learning with TensorFlow and Keras, Blender and Unity, graphic design |

## Currently

- Measuring and refitting PerfHub's model against more games and graphics cards
- Learning C# and deeper PostgreSQL before the exchange
- Preparing for Erasmus+ in Częstochowa, February 2027
