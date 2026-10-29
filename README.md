<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gbsnsgrckr/gbsnsgrckr/main/assets/banner-dark.svg?v=2">
  <img src="https://raw.githubusercontent.com/gbsnsgrckr/gbsnsgrckr/main/assets/banner-light.svg?v=2" alt="Kyle" width="100%">
</picture>

Computer science student at Arizona State University, and I run
[Black Canyon Software](https://github.com/BlackCanyonSoftware) — a one-person
shop in Phoenix.

Nearly everything I build lives in private repositories, so this profile reads
quieter than the work is. Here is what is behind it.

### Vantage

When players get stuck they rarely post about it — they search. Vantage reads
the questions players ask search engines, groups them into the problems behind
them, and tells a studio where its players actually need help: ranked,
categorised, and tracked week over week against the game's own patch history.

Three seeds against Elden Ring, on the first run, surfaced *"why is everything
hostile"* and *"what is poise"* — quest-state confusion and unexplained
mechanics that no review or Discord thread would have named that plainly. The
pipeline runs end to end on one game and a small seed set. It is a walking
skeleton, not a product.

### Market Predictor

Cross-sectional equity return forecasting across the S&P 500 and Nasdaq 100.
It ranks the universe by expected excess return over one, three and five
trading days rather than guessing at price, because ranking is far more
learnable than price levels and maps directly onto position sizing.

The backtest is done, 392 tests pass, and the pipeline runs unattended on a
Raspberry Pi. The out-of-sample record is still filling, and until it is in
there is nothing to claim. Superseded results stay in the write-up, because
what was believed and why it was wrong is part of the record.

### ai-suite

A complete local AI stack on one machine with no API spend: a single
OpenAI-compatible endpoint in front of every model, and an orchestrator that
delegates to specialists for coding, image generation, speech and research,
loading each on demand.

### doctools

One command that turns PDF, Word, PowerPoint and the rest into clean text a
language model can actually read — equations kept as LaTeX, diagrams as cropped
images, boilerplate thrown away, and an exact report of what it removed. Built
because feeding a model a raw extraction gets you confident answers drawn from
noise.

### Pixel Galaxy Studio

A local web app for designing a pixel-art galaxy background and exporting it as
a seamlessly looping MP4 — for Wallpaper Engine, a phone lock screen, or
anywhere a looping video works. Every knob pulled out onto a panel, a full-size
live preview, and a frame-exact video encoder.

### DAYnNIGHT

A live Windows desktop wallpaper that is the sky outside, right now. The sun
rises when it rises where you are, crosses at the altitude it really crosses
and sets when it really sets; twilight is the real twilight, the moon shows
tonight's phase, and four thousand stars turn at the sidereal rate.

There is no video file and no loop — the scene is computed from your clock and
your coordinates, so a whole day costs a few hundred kilobytes of shader rather
than tens of gigabytes of frames, and 0.15% of one CPU core to leave running.
The application is an editor, and a preset is a small file you can change and
send to someone.

---

Mostly Python; some JavaScript, Java and C#.
[blackcanyonsoftware.com](https://www.blackcanyonsoftware.com)
