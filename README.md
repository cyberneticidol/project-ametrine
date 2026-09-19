# Project Ametrine

## What is it?

Project Ametrine is intended to be a AI sludge-free fork of Bazzite. After discovering the use of things such as Claude in the repo, I decided to take matters into my own hands. Upstream permits the use of AI, so this won't. In fact, it's actively discouraged.

## Why the name?

It fits in with upstream's naming scheme. It's not from Fedora Atomic, it's from Bazzite, and I make it clear. Not much will change, except that there will be a greater vigilance against Generative AI. It's also going to be a little more opinionated.

## Well, okay, sounds good, so how do I get in?

If you're running Bazzite already, then it's easy. All you need to do is run:
`rpm-ostree rebase ostree-image-signed:docker://ghcr.io/cyberneticidol/project-ametrine:stable`
and let ostree take care of the rest. The Secure Boot signature should still be the same. If you run into problems, it might be easier to turn it off.

## If I'm on a fancy handheld PC?

Same command! Well.. almost. It's `project-ametrine-deck`. All images are listed, so you're welcome to take a look and see what fits your needs.

## I have a comment/I think something's missing...

Then you're welcome to open an Issue! If you have a fix for something, feel free to open a PR and I'll take a look!

## What should I expect?

Well, it's intended to avoid all forms of Generative AI. However, a lot of the packages come upstream from Fedora, which is contaminated with Generative AI. While some apps are replaced with AI-free ones, it might not be possible, so the aim is harm reduction. I didn't delete the commits containing Generative AI because that would be destroying history, and I don't do that.

## Then why are you pulling commits from upstream?

Because it's easier, and it allows me to check if any Generative AI is used.

## What are the branch names?

"Main" is the stable branch. It's locked to prevent unstable changes.
"Testing" is when unstable changes pass smoke testing. Kind of like RC builds.
"Unstable" is the core development branch. Things can break without warning!
