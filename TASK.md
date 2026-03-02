# Gym Workout Web App

Build a single-page web app (HTML + CSS + JS, no framework) that displays Akhil's weekly workout schedule.

## Requirements
- 7 day tabs/buttons (Mon-Sun) at the top
- Tap a day to see that day's full workout
- Each exercise should show a GIF demonstrating proper form
- Source GIFs from public URLs (musclewiki, giphy, or any reliable exercise GIF source)
- Mobile-first, dark theme, clean minimal design
- No tracking, no login, no backend. Pure static site.
- Fast, instant feel. No loading spinners.

## Design
- Dark background (#111 or similar)
- Clean sans-serif font (Inter or system)
- Day selector as pill buttons at top
- Each workout section (Warmup, Main Body, Lead-Self etc) as collapsible or clearly separated blocks
- Exercise cards with GIF on left/top and details on right/bottom
- Max 3 colors. Restraint > variety.

## Workout Data

### MONDAY - MET CON / TEAM CHALLENGE

**Warm Up (4 min):**
- 20 Fast Toe Taps
- 10 Air Squats
- 10 Push-Ups
- 10 KB Deadlifts

**Lead-Self (30 min) - Metabolic Capacity Extension:**

Block A - Engine (10 min):
- Row/Ski/Bike: 45s hard / 75s easy x 5

Block B - Bodyweight Density (10 min) AMRAP:
- 10 Push-Ups
- 15 Air Squats
- 20 Sit-Ups

Block C - Core Flush (10 min) 3 rounds:
- Plank 30s
- Dead Bug 10/side
- Easy walk 60s

### TUESDAY - LOWER BODY STRENGTH

**Warm Up (5 min):**
- 2x10 ATG Split Squats (each leg)
- 2x10 Single-Leg Glute Bridges (each leg)
- 2x10 Lying Supermen

**Main Body (40 min, 6 per station):**

Station 1 - Barbell Squats (7 min):
- 8-12 Back Squats
- Partner Rest -> Swap
- Repeat 2-3 Sets

Station 2 - Trap Bar + DB RDL (7 min):
- KB DL 6-10 SUPERSET with DB RDL 10-15
- (Optional Sled Push 15-20m)
- Partner Rest -> Swap
- Repeat 2-3 Sets

Station 3 - Bulgarian Split Squats (7 min):
- 8-12/leg
- Partner Rest -> Swap
- Repeat 2-3 Sets

Station 4 - DB Lunges + Squat Hold (7 min):
- A: DB Walking Lunges 12-16/leg
- B: Squat Hold
- Swap, Rest 60-90s
- Repeat 2-3 Sets

### WEDNESDAY - UPPER ENGINE + HYPERTROPHY

**Warm Up (4 min):**
- 10 Scap Push-Ups
- 10 Band Pull-Aparts
- 10 Light DB Rows each arm
- 10 Slow Push-Ups

**Lead-Self (30 min):**

A - Upper Strength (10 min) 3 rounds:
- 10 DB Bench Press
- 12 DB Row each arm
- Rest 60 sec

B - Shoulder & Upper Back (10 min) 3 rounds:
- 10-12 Lateral Raises
- 12-15 Rear Delt Fly
- Rest 45-60 sec

C - Core (10 min) 3 rounds:
- 20 Sit-Ups
- 10-15 Leg Raises
- 30-second Side Plank each side
- Rest 45 sec

### THURSDAY - LEGS & LUNGS (30 MIN)

**Warm Up (4 min):**
- 10 Step-Ups each leg
- 10 Hip Hinges
- 10 Jumping Jacks
- 20 High Knees

**Lead-Self (30 min) - Lower Accessory:**

A - Moderate Engine (10 min):
- Bike, Row, or Ski

B - Lower Accessories (15 min) 3 rounds:
- 12 Hip Thrusts
- 15 DB RDL
- 12 Step-Ups each leg
- Rest 60 seconds

C - Cooldown (5 min)

### FRIDAY - 3 STATION RACE

**Warm Up (5 min) as a team, steady pace:**
- 200m easy jog or machine
- 20 Air Squats
- 20 Alternating Lunges
- 30 sec Plank
- 20 Toe Taps

**Main Workout - 3 Station Race (6 min per station):**
Teams rotate clockwise every 6 minutes on the buzzer.

Station 1 - Engine:
- Max calories in 6 minutes
- Any machine: rower, ski, bike
- One athlete works at a time
- Score: Total calories accumulated

Station 2 - Core Gauntlet (6 min total):
- Fixed internal structure, follow timing exactly
- Block 1: 3x1 min core work, 1x1 min rest
- Block 2: 2x1 min core work

Station 3 - Treadmill Max Distance:
- Max distance in 6 minutes
- Treadmill only
- One athlete runs at a time
- Swap runners as often as needed
- Score: Total distance accumulated

### SATURDAY - LEAD SELF TRAINING BLOCK

**Block A - Lower Body Strength (8 min) 2-3 rounds:**
- Goblet Squat 10-12 reps
- KB or DB RDL 10-12 reps
- Rest 60 seconds between rounds

**Block B - Upper Push/Pull (6 min) 2 rounds:**
- DB Shoulder Press 10-12 reps
- DB Row 10-12 reps each side
- Rest 45-60 seconds

**Block C - Core Stability (6 min) 2 rounds:**
- 15-20 Sit-Ups
- 10-15 Dead Bugs each side
- 30-40 second Plank
- Rest 45 seconds

### SUNDAY - KOT RECOVERY (30 MIN)

**Warm Up (5 min):**
- 30 sec knee-over-toe ankle rocks each leg
- 10 Patrick step-backs each side
- 12 tib raises against wall
- 30 sec deep squat sit
- 10 slow good mornings

**Main Block (25 min):**

Block A - ATG Split Squat Progression (7 min) 3 rounds:
- 8-10 ATG split squats each leg
- 4-second controlled descent
- 2-second pause at bottom
- Optional light counterbalance (DB or plate)
- Rest 20-30 sec between legs
- Progression: Add pause length or depth before adding load

Block B - Tibialis + Ankle Capacity (5 min) 3 rounds:
- 15-20 tib raises
- 20-30 sec calf stretch (straight knee)
- 15 single-leg calf raises (slow)
- Rest 30-45 sec between rounds
- Progression: Increase tib reps or tempo before adding external load

Block C - Step-Downs + Squat Depth (5 min) 3 rounds:
- 10-12 Poliquin step-downs each side
- 6-8 slantboard squats
- 5-second eccentric on every rep
- Rest 45-60 sec
- Progression: Increase eccentric time or add bottom pause

Block D - Jefferson Curl + Posterior Chain (4 min) 3 rounds:
- 8-10 Jefferson curls (very light)
- 8-10 tempo good mornings (3 sec down / 1 sec up)
- No rushing between reps
- Progression: Add range before load

Block E - Balance + Isometrics (4 min) 2 rounds:
- 30 sec single-leg balance (barefoot if possible)
- 20 sec deep split squat hold each side
- 30 sec deep squat breathing hold
- Progression: Eyes closed or longer holds

**Cooldown Flow (4 min):**
- 30 sec deep squat hold
- 30 sec pigeon stretch each side
- 30 sec hamstring stretch
- 30 sec hip flexor stretch each side
- Slow nasal breathing throughout

## GIF Sourcing
For each exercise, find a publicly accessible GIF URL showing proper form. Try these sources:
- https://fitnessprogramer.com/exercise/[exercise-name]/
- https://www.musclewiki.com/
- Search for "[exercise name] exercise gif" and use direct URLs
- Use placeholder colored div if a GIF can't be found (with exercise name text)

## Output
Single index.html file with all CSS and JS inline. Everything self-contained.
