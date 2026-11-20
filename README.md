# PID Playground

**Live site: https://chefjeffphd.github.io/pid-playground/**

An interactive PID control simulator for MEGN 300 (Instrumentation & Automation), Colorado School of Mines. It shows what the P, I and D terms each do, one at a time.

- **Quadcopter altitude:** follows the lecture's drone example. Kp = 1 sits on the ground, Kp = 2 hovers at 50 m (steady-state error), PI removes the error, and PID removes the overshoot.
- **Motor + pendulum arm:** a motor holds an arm against gravity, and can swing it up to the inverted position.
- **Guided lessons:** bang-bang, P only, PI, integral windup, PID, sensor noise and disturbances, each tied to a lecture slide.
- **Test bench:** run step tests, overlay the responses and compare rise time, overshoot, settling time, steady-state error and IAE.

Everything is in one self-contained `index.html` with no dependencies. It also works offline: download the file and open it in a browser.

Keyboard: Space pause · T run test · R reset · 1/2/3 toggle P/I/D · ← → lessons · G gust/kick
