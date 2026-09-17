# Project Ametrine

## What is it?

Project Ametrine is intended to be a AI sludge-free fork of Bazzite. After discovering the use of things such as Claude in the repo, I decided to take matters into my own hands. Upstream permits the use of AI, so this won't. In fact, it's actively discouraged.

## Why the name?

It fits in with upstream's naming scheme. It's not from Fedora Atomic, it's from Bazzite, and I make it clear. Not much will change, except that there will be a greater vigilance against Generative AI. It's also going to be a little more opinionated.

## Well, okay, sounds good, so how do I get in?

If you're running Bazzite already, then it's easy. All you need to do is run:
`rpm-ostree rebase ostree-image-signed:docker://ghcr.io/cyberneticidol/project-ametrine:stable`
and let ostree take care of the rest. The Secure Boot signature should still be the same. If you run into problems, it might be easier to turn it off.
