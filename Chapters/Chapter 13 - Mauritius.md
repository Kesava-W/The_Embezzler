# Chapter Thirteen — Mauritius

The tip came in through CERT-MU on a Tuesday, forwarded to the Cybercrime Unit at CCID with a covering note so bare it barely qualified as one - a flagged login trace, an Indian trust's banking portal, an IP address that had bounced through two other countries before it settled, however briefly, somewhere on Mauritian soil. No sender name. No explanation of how whoever had sent it had come to be looking at an Indian NGO's server logs in the first place. It sat in a shared inbox for the better part of a morning before anyone opened it, filed by the system under a priority tag that undersold, by some distance, what was actually inside it.

Inspector Reshma Bunwaree read it twice before she took it to anyone. The second read was slower than the first, her finger tracing the routing hops on the printed page as though the paper itself might yield something the screen hadn't.

"Twenty-two of us in this unit," she said to her sergeant, dropping the printout on his desk, "and somebody just handed us a case that isn't even ours to have."

"Not ours how?"

"The crime happened in Bangalore. We're being asked to run down the Mauritius end of something that killed a man in India." She was already pulling up a second file as she said it - a name that had crossed her desk once before, three weeks earlier, in an entirely different context, a note she'd made at the time and then more or less forgotten about. "Except this isn't the first time this quarter I've seen a Mauritius IP mentioned somewhere it shouldn't be. There were whispers, informal, nothing anyone filed - two other Indian cases, same pattern, never anything solid enough to open a file on. I dismissed them at the time. I'm less comfortable dismissing them now."

Her sergeant leaned over the printout, scanning it with the particular squint of a man trying to look more useful than he currently felt. "Two inspectors and twenty desk officers, and this is what lands on us."

"That's exactly what I said."

By the time she'd finished cross-referencing what little there was, Assistant Commissioner Kevin Appadoo was in the room too, brought in less for his cybercrime expertise, which was modest, than for the name that kept surfacing whenever anyone traced the trail back toward anything resembling a physical location.

"Aadhunik Marine Freight," Appadoo said, reading over her shoulder, and something in his posture changed, a very small straightening, the kind a person doesn't fully notice themselves doing. "Of course it is."

"You know something about them I don't?"

"I know the owner slapped me across the face once for suggesting he stop breaking the law." He didn't say it as a joke, though it landed like one anyway, the sergeant suppressing a laugh he clearly hadn't meant to nearly let out. "And I know his operations manager - Deelchand, the one from the Ganja business - has exactly the kind of access this would need. Warehouses, server racks for the shipping manifests, a company nobody looks at too closely because everyone already assumes the trouble there is drugs, not this."

"You want to bring him in personally."

"I want to see his face when we ask."

Deelchand wasn't the first name on the whiteboard, in the end - a rival freight operator, a man called Callikan who'd been undercutting Aadhunik Marine Freight's harbour contracts for two years and had motive enough on paper to make Bunwaree's sergeant genuinely excited about it for the better part of a day. Callikan had the grudge, the resources, even a nephew who'd studied computer science in France. He also, once they'd looked properly, had an entire fleet of his own container ships to run and had spent the night of the Bangalore breach at a shipping conference in Réunion with forty witnesses and a hotel bill to prove it. The whiteboard came down within the afternoon, the name wiped clean, no apology offered to a man who never learned he'd been considered at all.

It took them four days to bring Deelchand in for questioning, and less than one to conclude he had nothing to do with it.

"I don't understand computers the way you're describing," Deelchand told them, across a table that had seen considerably more confident men across it, and considerably guiltier ones. He said it plainly, without the practised outrage of a man performing innocence - which, Bunwaree noted to herself, wasn't the same thing as innocence, but was at least a different texture of it. "I can send an email. My daughter has to help me with the WiFi password most weeks. You think I broke into a bank in India?"

"Someone with access to your company's network did."

"Then look at the network. Don't look at me." He didn't flinch under it, which by itself told Bunwaree less than she'd have liked. "And whatever night you are asking me about - the fourteenth, you said - I was in an ADSU waiting room until nearly midnight, signing forms about my own case. Ask them. I have never once, in this whole mess, had a night with less alibi than that one."

Bunwaree let a silence sit after that, the kind she used deliberately, watching to see if a man would fill it with something he shouldn't. Deelchand simply watched her back, waiting, hands flat on the table, and eventually she was the one who broke it.

"We'll be checking the log."

"Check it. It will tell you I am a very boring man with a very bad password."

The ADSU log confirmed it within the hour. A forensic pass on his phone and his one ageing laptop turned up nothing beyond what a man who genuinely struggled with a WiFi password would produce - no encryption tools, no unusual software, nothing that explained how someone with his history and his access could also, somehow, possess the specific technical skill the Bangalore breach had demonstrated. The forensic officer who ran the pass told Bunwaree, half joking, that the laptop's most advanced piece of software was a solitaire game.

"He's not it," Bunwaree said, two days later, in Appadoo's office, with considerably less certainty in her voice than the sentence should have carried. "Whoever did this used him - his company, maybe, or just the general noise around it - as cover. Not the other way round."

"So who."

"That's the part I can't give you." She turned her laptop around so he could see the trace map for himself - a scatter of hops across four countries, IP addresses that had gone dead or reassigned themselves within hours of each appearance, a pattern too clean to be an amateur covering tracks and too varied to be a single fixed operation running from one physical address. "Every time we get close enough to ask a foreign provider for subscriber information, the address has already moved. Whoever this is isn't hiding badly and hoping we don't look. They're routing around us like they already know exactly how we look."

Appadoo didn't say anything for a moment, still looking at the map, at the small red flags scattered across it like a trail somebody had deliberately dropped and then deliberately swept up again a step behind him, his own reflection faintly visible in the laptop screen's glare.

"This isn't some boy in a bedroom," he said finally.

"No."

"You think it's state-level."

"I think," Bunwaree said, choosing the words carefully, the way a person chooses words they're not yet ready to put in a report, "that whoever this is has done this kind of thing before, for someone who taught them how to do it properly. And I think we are not going to catch them by being thorough. Thorough is what they're already three steps ahead of."

"That's not something I can put in a briefing note."

"I know." She closed the laptop. "Put in the briefing note that we're pursuing active leads. That part's even true, technically."

Neither of them said the rest of it out loud - that the file would sit open on both their desks for months without moving, not because nobody was working it, but because for the first time either of them could remember, being good at the job simply wasn't going to be enough.
