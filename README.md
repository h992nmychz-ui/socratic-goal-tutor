# socratic-goal-tutor

An agent skill that turns Claude into a goal-first tutor. Most tutor prompts start at "test me". This one starts at "what are you trying to be able to do, and how will we both know you can?"

It works for a university course, a certificate, an interview, or plain curiosity about a topic.

What it does:

1. **Goal.** Takes a loose wish ("I want to learn about derivatives") and turns it into a checkable goal with a proof. It asks at most three questions.
2. **Fetch.** Collects the real material for that goal: your files, the web, or your learning platform through a browser you are signed in to. It never types your password.
3. **Map.** Breaks the goal into can-do items. One is ticked only when you have done it unaided.
4. **Board.** Fills in a ready-made whiteboard page (`assets/board.html`) with your goal, your path and your can-do list, and ticks it off as you show each skill.
5. **Teach.** One idea per turn: everyday scene, worked case, one check, mark, next.
6. **Slips.** Keeps a log of your repeat mistakes and opens each session with them.
7. **Proof.** A past paper, a rehearsal, or a teach-back, scored honestly.

For courses it follows the course's rules on AI and graded work: it explains the method on a made-up example and leaves the real task to you.

## Install

Copy the `socratic-goal-tutor` folder into `~/.claude/skills/`.

Then say what you want to learn.

## Do not commit

Course files (past papers, slides, hand-ins) belong to your school. Keep them, and your notes file, out of this repository.

## License

MIT. See `LICENSE`.
