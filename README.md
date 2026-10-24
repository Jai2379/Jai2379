## Jaiaditya Asudani

Nanotechnology Engineering at the University of Waterloo. I picked nano for the physics and ended up spending most of my time in a terminal. What I build usually connects software to something outside it: a production commerce backend, adversarial ML, robot-arm firmware, CAD for design teams.

I learn by shipping. Hand me a tool I've never used and I'll be building with it by the next day.

### Now

- Second year, BASc Nanotechnology Engineering, Waterloo
- Finished a software engineering internship at EIC Ltd (summer 2026)
- Open to co-op roles in software, ML and robotics

### EIC Ltd, summer 2026

Built a headless B2B commerce platform that runs in production: Next.js 15, React 19 and TypeScript across 27 API endpoints, on Supabase Postgres through Prisma, with Upstash Redis and Resend.

- **Auth from scratch.** HS256 JWTs, bcrypt, expiring email verification and a merchant-approval state machine, with constant-time login and seven Redis rate limiters against credential stuffing.
- **Cache.** Four-tier stale-while-revalidate (memory → Postgres → disk → static bundle) behind a 24-request concurrency pool, so the upstream catalog API never blocks a page load.
- **Settlement.** Custom-quote totals are recomputed inside a transaction, and order and invoice rows are written as one atomic unit.

### Projects

**[Artists With Souls](https://github.com/Jai2379/AWS-Artists-With-Soul-)** · PyTorch, Flask, Celery, Redis\
FGSM and PGD perturbations against a ResNet-50 surrogate that make artwork unreliable training data for vision models, with Grad-CAM to show the attention shift. Running the attack at 512 px and transferring it to full resolution cut processing time by more than 90%. Team build, GDGHacks 2026.

**[Credit Card Fraud Detector](https://github.com/Jai2379/credit-card-fraud-detector)** · scikit-learn, imbalanced-learn, SQLite\
Random Forest with a drift-triggered retraining loop. It rebuilds itself when recall drops below 0.90 or the feature schema changes, and every model ships with its own feature manifest.

**[Uber Fleet Operations](https://github.com/Jai2379/Uber-Fleet-Operations)** · pandas, scikit-learn, SQLite, Power BI\
Pre-dispatch cancellation classifier on ~150K NCR ride bookings, plus a Power BI layer that found ₹5M (8.84%) of booking value tied up in incomplete rides.

**[6-DOF Robotic Arm](https://github.com/Jai2379/6-DOF-Robotic-Arm-Arduino-Controller)** · C++, Arduino, SolidWorks\
Parallel-linkage arm designed in SolidWorks. Arduino firmware runs coordinated joint-space interpolation with table-driven limits over a serial command protocol.

**[Histogram + Distribution Fitting](https://github.com/Jai2379/Histogram-Web-App-Distribution-Curve)** · Streamlit, SciPy\
Turns binned data into weighted samples and fits 11 `scipy.stats` distributions, automatically or by hand.

### Toolbox

```
languages   Python · TypeScript · JavaScript · C/C++ · SQL
web         Next.js · React · Node.js · Flask · REST
data / ml   PyTorch · scikit-learn · pandas · NumPy · Power BI
infra       PostgreSQL · Prisma · Redis · Celery · SQLite · Vercel
hardware    SolidWorks · Onshape · Fusion 360 · AutoCAD · Arduino
```

### Away from the keyboard

- Mechanical work on Waterloo design teams: Waterloop (hyperloop pod), Electrium Mobility (e-bike), UW NanoRobotics
- Five years in Air Cadets, finishing as Warrant Officer and Flight Commander for a flight of 30+
- I build Roblox games for fun

### Contact

[jaiadityaasudani.vercel.app](https://jaiadityaasudani.vercel.app) · [LinkedIn](https://linkedin.com/in/jaiadityaasudani) · jasudani@uwaterloo.ca
