**rishit nanavati**
 
Two years ago I couldn't get past the resume round of a single hackathon. The problem wasn't effort — it was that I had nothing to point to yet. So I started building the things that would eventually do the pointing.
 
Most recently: [Aris](https://github.com/bitbyrizbit/aris-ai), an on-device AI network — multiple devices splitting one task and running real inference locally, no server in the loop. First working version ran at 8–10 minutes per task. I traced it to beam search doing more work than the demo needed, switched to greedy decoding, and got it to ~2 minutes — a real quality-for-speed tradeoff, made on purpose and tested, not assumed.
 
What I don't have yet: the theory underneath the practice. I can get a model to converge; I can't always tell you *why* it does, or prove it will at scale. That gap is the next thing I'm working on, not something I'm pretending isn't there.
 
`rishitnanavati01@yahoo.com` · [linkedin](https://www.linkedin.com/in/therishitnanavati/)
