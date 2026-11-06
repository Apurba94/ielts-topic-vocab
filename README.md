# Topic Vocabulary

Words for the topics IELTS returns to: environment, education, health, technology, work, cities and more.

Part of the [IELTS Study Suite](https://github.com/Apurba94/ielts-study-suite): 100 free study apps for IELTS. This one is for the IELTS Academic and General Training test. It works offline, as a Windows program or in the browser.

## Download and run

- **Windows:** download `Topic Vocabulary.exe` from the [latest release](https://github.com/Apurba94/ielts-topic-vocab/releases/latest) and open it. Nothing to install. It opens in its own window and saves your progress in your user folder.
- **Browser:** open it online in the suite's web edition at https://ielts-study-suite.vercel.app/apps/ielts-topic-vocab/ . Progress stays in that browser.
- **From source:** `python launcher.py` (Python 3.10 or later, no packages needed).

## What it does

Writing Task 2 and Speaking Part 3 keep returning to the same topics: the environment, education, health, technology, work, cities, culture, society and the economy. Precise topic words (emissions, curriculum, sedentary, urbanisation) let you say more with fewer words. Ninety words in nine topics, with cards, quizzes and examples written for the suite.

Sections: Cards, Quiz, List, Progress, About.

## How to use it

1. Choose a topic in **Cards** and learn a few words a day.
2. Test yourself by topic in **Quiz**.
3. Before writing an essay, read the words for its topic in **List** and use two or three of them.

## Good to know

- All questions, passages, recordings and definitions were written for this suite. None are official IELTS questions. For official practice, use the materials on ielts.org and from the test partners.
- It follows IELTS as delivered on computer in 2026. Formats change, so check ielts.org before your test.
- Listening uses the voices installed on your computer, which sound less natural than real test recordings.
- Feedback on writing and speaking counts what a program can count honestly, such as length and linking words. It is not an IELTS band score. Band conversions for Listening and Reading are approximate.
- Not endorsed by or affiliated with the British Council, IDP or Cambridge University Press & Assessment. IELTS is a registered trademark of its owners.

## For developers

The app is plain HTML and JavaScript in `web/`, run by a small Python launcher that serves it on 127.0.0.1 only and needs a secret token for saving. Tests: `node --test "tests/*.test.js"` (29 tests) and `python -m unittest discover -s tests`. Build the .exe with `python build_exe.py`.

Built with AI assistance (Claude Code). MIT licence. By JANIN A APURBA.
