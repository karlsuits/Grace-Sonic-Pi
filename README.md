East Village Sound Sampler
 
Helpful Resources:
•	Sonic Pi Official Website: https://sonic-pi.net/ 
•	Great website with tutorials: https://sonic-pi.mehackit.org
•	Free audio editing app: https://www.audacityteam.org
•	Paid audio editing app (Adobe Audition): https://www.adobe.com/ 
•	iPhone field recorder: Apple Voice Memos (simple ,free app, included on all iPhones)
•	Android field recorder: Smart Recorder (simple, free app with background recording)
•	Hardware field recorder used for samples: Zoom H4N
 
Welcome to the East Village Sound Sampler project!
Today, you’ll create a sampler made up of real sounds recorded from the streets of New York City using Sonic Pi — a tool that lets you make music through code.
In this project, you’ll explore your creativity, curiosity, and technical skills.
 
🌱 Pick Your Creative Growth Path
Path	What You'll Do
Planting Seeds	Start by playing a few sounds and making tiny edits.
Tending the Garden	Build a basic remix by layering sounds together.
Blooming Fully	Dive deep — use loops, effects, and full creativity to create your remix!
👉 Pick the path that feels right for you today — there's no wrong choice!
 
 
📂 Getting Started
1.	Download all project files (starter code + samples).
2.	Open Sonic Pi.
3.	Open the starter file you want:
o	planting-seeds.sonic-pi
o	tending-the-garden.sonic-pi
o	blooming-fully.sonic-pi
4.	Press Run — and start remixing!
 
🛠️ Quick Sonic Pi Code Tips
Variable
folder = "/Users/your_username/Desktop/Samples/"
sample folder, "thud.wav"
  A variable like folder saves a location or value you can reuse.
Parameters
sample folder, "traffic.wav", amp: 0.5, rate: 1.2
  Parameters like amp: (volume) and rate: (speed) change how your sample sounds.
Sleep (Timing)
sample folder, "snare.wav"
sleep 1
sample folder, "thud.wav"
sleep 1
  sleep means wait a certain number of seconds before doing the next thing.
Loops
live_loop :drums do
  sample folder, "thud.wav"
  sleep 1
  sample folder, "snare.wav"
  sleep 1
end
  live_loop repeats your code forever, creating beats or evolving rhythms.
Effects
with_fx :reverb do
  sample folder, "voice.wav"
end
  with_fx adds cool sound effects like echo, reverb, and filters.
 
🎵 Challenge Ideas
•	Layer sounds to create your own story.
•	Change speeds (rate:) and volumes (amp:) to remix samples.
•	Add effects like reverb, echo, or slicer to make it your own.
•	Think about movement: make sounds enter and exit at different times!
•	Remix responsibly and respectfully — telling new stories while honoring the community sounds around you.
 
🌟 Final Tip
Be playful. Be curious. Remix the world with care and creativity.
🌟 Happy coding! 🌟

