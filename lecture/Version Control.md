## ROI

- Lecture: 30 - 60 minutes
	- Learn the concept of version control and know the most used platform
- Exercise: 30 - 60+ minutes
	- Sign up GitHub, Create repository, and Check In/Out
- Extension: 60+ minutes
	- Organize git modules
- Advance: 60+ minutes
	- Install gitlab and set up for personal use

## Why Version Control

Imagine you’re writing the best comic book ever. You start with a simple idea: a superhero named Zap who can teleport. You sketch the first page—Zap zipping through the city, saving cats from trees. It’s awesome! But then you get a wild idea: what if Zap’s teleporting goes haywire and he ends up in a dinosaur jungle? You rewrite the story, scribbling over your old pages. Cool, but now you miss the city version. You try another idea—Zap on a spaceship—but accidentally spill juice on your notebook, losing half your work. Ugh! You wish you could go back to that first cat-saving story, but it’s gone, and your comic’s a mess.

Now, picture this: what if you had a magic sketchbook? Every time you drew a new page or changed your story, it saved a copy of the old one. You could flip back to Zap in the city, peek at the dinosaur jungle, or tweak the spaceship idea—all without losing anything. You’d have every version of your comic, safe and sound, and you could pick the one you liked best or even mix them together later. That’s what version control does for one person!

---

Version control isn’t just for teams—it’s super helpful when you’re working solo, too. It’s like a backup system and a time machine for your projects. Let’s say you’re coding a game, writing a story, or designing a poster. With a version control tool (like Git), you save “snapshots” of your work as you go. Each snapshot—called a “commit”—keeps track of what you changed. If you mess up (like deleting half your game by accident), you can jump back to an earlier version. Or if you try a crazy idea (Zap in space!) and don’t like it, you can ditch it without losing your original.

For example, imagine you’re coding a little app that makes a cat meow when you click it. You save your first version—works great! Then you add a barking dog sound, but it glitches. With version control, you can rewind to the meowing cat and skip the barking disaster. It’s all about keeping your ideas safe and letting you experiment without fear.

So, even if you’re flying solo on a project, version control is like your trusty sidekick—saving your work, tracking your changes, and letting you be as creative as you want. What do you think—would you use it for your next comic or game?

Alright, let’s dive into explaining version control to middle school students with a story!

---

Imagine you and your friends are working together on a super cool group project: building a giant treehouse. You’ve got sketches for the design, a list of materials, and a plan for how it’ll all come together. Everyone’s excited, so you split up the work. You draw the blueprint, your friend Mia writes the supply list, and your buddy Leo figures out the steps to build it.

At first, everything’s great. But then Mia decides to add a rope ladder to the supply list, while Leo changes the steps to include a slide instead of stairs. You, meanwhile, tweak the blueprint to add a secret trapdoor. You’re all working on your own copies of the project, but when you meet up to put it all together—uh-oh! Nothing matches. Mia’s list doesn’t fit your trapdoor idea, and Leo’s slide messes up the whole design. It’s a mess, and you start arguing about whose version is the "right" one. Worse, you realize you’ve lost the original plan from the start, so you can’t even go back to fix it. Disaster!

Now, what if there was a magic notebook that kept track of every change you all made? A notebook where you could see Mia’s rope ladder idea, Leo’s slide plan, and your trapdoor sketch—all saved step by step. Better yet, what if it let you mix the best parts together, go back to an earlier version if something went wrong, or even work on new ideas without ruining the main plan? That’s what version control is like!

---

Version control is a tool that helps people—like programmers, designers, or even treehouse builders—keep track of changes to their work. Think of it like that magic notebook. Every time you change something (say, a line of code or a project file), version control saves a “snapshot” of it. You can see who changed what, when, and why. If you make a mistake, you can rewind to an earlier version. And if you’re working with a team, it makes sure everyone’s ideas can come together without turning into a big, confusing mess.

For example, programmers use version control systems like Git. They can write code, save their changes (called “commits”), and share them with teammates. If someone’s code breaks the project, they can undo it. It’s like having a time machine and a teamwork superpower rolled into one!

So, just like your treehouse crew could’ve avoided chaos with that magic notebook, version control keeps projects organized, safe, and fun to work on together. Pretty cool, right? What do you think—would you use something like that for your next big idea?

## Use git

Once upon a time in the land of coding, there was a brilliant inventor named Linus Torvalds. Linus wasn’t just any coder—he was the mastermind behind Linux, a super-smart operating system that powered computers all over the world. Back in the early 2000s, Linus and his team of Linux builders were busy crafting their magical creation, but they hit a big problem. They needed a way to keep track of all the changes they made to their code—thousands of tiny tweaks, like adding new spells to a wizard’s book. Without a good system, their project was turning into a chaotic pile of scrolls, with no one sure which version was the latest or who had changed what.

At first, they used tools like CVS and Subversion—think of them as old, creaky filing cabinets. These worked okay for small projects, but for something as big as Linux, with hundreds of coders scribbling away, they were too slow and clunky. Then, in 2002, they tried a fancy tool called BitKeeper, which was like a shiny new spellbook. It was fast and let everyone work together better, even when they weren’t in the same room. Linus loved it! But in 2005, trouble struck. The folks who owned BitKeeper got into a fight with some Linux coders over how it was being used, and—poof!—they took it away. Linus was furious. “Fine,” he said, “I’ll make my own magic tool, and it’ll be better than anything out there!”

So, in April 2005, Linus locked himself in his workshop (well, his computer, really) and started building. He wanted a system that was lightning-fast, worked even without an internet connection, and let every coder have their own copy of the project—like giving each wizard their own spellbook that could magically sync with the others. In just _two weeks_, Linus created Git! He named it after a silly British word for a stubborn person (or maybe himself), saying, “I’m an egotistical git, so I’ll call it that.” The first version was rough, but it worked—and soon, his Linux team was using it to tame their wild code.

Git’s story didn’t stop there. It was like a seed that grew into a mighty tree. At first, only Linus and his Linux crew used it, but word spread. Other coders peeked at Git and thought, “Whoa, this is cool!” Unlike older tools that kept everything in one big castle (centralized systems), Git let everyone carry their own little castle (distributed). You could save your changes, experiment with wild ideas, and undo mistakes—all on your own machine. If you wanted to share, you’d send your updates to a friend or a big library like GitHub, which popped up in 2008 to make sharing even easier.

Why did Git get so popular? Imagine you’re drawing a comic, and you can save every page, try a crazy twist (like dinosaurs attacking), and go back if it flops—all without losing your work. Git does that for code! It’s fast, free, and doesn’t need a bossy central server telling it what to do. Plus, it’s tough—Linus built it to handle Linux’s millions of lines of code, so it can take on anything. Soon, big companies like Google, Microsoft, and even game makers started using it. Little projects, like your first app, loved it too. By the 2010s, Git was everywhere, with GitHub turning it into a global clubhouse where millions of coders swap ideas.

Today, Git’s like the superhero of version control—saving projects, sparking teamwork, and letting creators experiment without fear. From Linus’s grumpy “I’ll do it myself” moment in 2005, it’s grown into a tool that powers websites, games, and even robots. Pretty epic, right? What do you think—would you use Git to save your next big adventure?
### github

### gitlab

### gogs

### more


## Others

- **Subversion (SVN)**
    - What it’s like: Think of a big library where all your project files live on one central shelf. You “check out” a book (file), make changes, and put it back for everyone to see.
    - How it works: It’s centralized, meaning there’s one main copy of everything, and you connect to it to save your updates.
    - Good for: People who like one main “truth” for their project, like a team working on a single game design.
    - Fun fact: It’s older than Git and was super popular before Git came along!
- **Mercurial**
    - What it’s like: Imagine a sketchbook that’s a lot like Git’s, where you save snapshots of your comic as you draw. It’s simple and fast, like a lightweight magic notebook.
    - How it works: It’s distributed (like Git), so you keep your own copy of the project and can share changes with others.
    - Good for: Coders who want something easy to learn but still powerful, maybe for a small app or website.
    - Fun fact: It’s nicknamed “Hg” (its chemical symbol) because “Mercurial” means quick and changeable!
- **Perforce (Helix Core)**
    - What it’s like: Picture a giant vault for huge projects—like a movie studio storing all its video clips and special effects. You lock a file to work on it, then unlock it when you’re done.
    - How it works: It’s centralized and great at handling big files (like game graphics or videos), not just code.
    - Good for: Big teams working on massive projects, like video games with tons of art and sound.
    - Fun fact: Companies like Ubisoft use it for games like _Assassin’s Creed_!
- **CVS (Concurrent Versions System)**
    - What it’s like: An old-school filing cabinet where you store versions of your homework. You can work on files at the same time as others, but it’s a bit clunky.
    - How it works: It’s centralized and lets multiple people edit stuff together, tracking changes over time.
    - Good for: Simple projects where you don’t need fancy features—like an early website from the ‘90s.
    - Fun fact: It’s one of the oldest version control systems, born way back in 1986!
- **Bazaar**
    - What it’s like: A friendly journal where you can write your story however you want—alone or with friends. It’s flexible and easy to use.
    - How it works: It’s distributed like Git and Mercurial, letting you save your own versions and share them later.
    - Good for: Beginners or small groups who want something less complicated, like a school coding club.
    - Fun fact: It was made to be super user-friendly, so it’s less intimidating than some other tools!
- **Gerrit**
	- An open-source web-based tool for reviewing code changes before they’re merged into a version control system like Git.