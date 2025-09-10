# Fixing source code of scratch-www
# The main problems.
1. Uh..... why is there some general.somewordidk and aboutus.somewordidkmans
2. Some sentences are missing after fixing 1. problem.
(if you have other then open issue and then say which)
# How to fix them
To fix 1 problem, you need to grab init.js from the our repo and replace the old init.js with new one. the path to init.js is "(the source code of scratch-www)/src/". Replace it.
To fix 2 problem, you need to grab l10n.json from our repo and place it in the root of source code of scratch-www (not src/ folder) Or you can add to both folders. Now you can see it added.

# Advanced, optional fixing problems.
1. Uh that error in console log says about missing folder "intl"?
(if you need to add something here, open a issue and say)
To fix 1 problem, you need add in the root of source code of scratch-www folder "intl" and inside of it: add 2 empty files named "en.json" and "ru.json". Done! rerun using npm run start.
