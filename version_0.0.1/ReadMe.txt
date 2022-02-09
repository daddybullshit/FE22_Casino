Let us pretend we have few billionaries Casino from Las Vegas as our stakeholder.

As your manager, I want you to do minimal work to complete a few tasks.
Please, do not make this example beautiful or advanced, we just want to keep it simple
(and ugly this time).

Your solution may be incomplete, we will tidy it together later another time. For
example, you may notice, there is no <head> and <body> or <title> tags in the HTML files.
Let us at this moment run at bare minimum as much as we can. We work according to MVP.

A minimum viable product (MVP) is a version of a product with just enough features to be
usable by early customers who can then provide feedback for future product development.

https://en.wikipedia.org/wiki/Minimum_viable_product

## PROBLEM ##

You have to solve following 3 problems. You do not need to solve all problems.

1. In index.html, the "Next" button has to link to register.html.

2. The name you enter in register.html has to be passed to exchange.html.
If you entered Adam as your first name on register.html, then it has to say
"Hello Adam" on exchange.html.

3. In exchange.html, the "Exit" has to be a button that links back to index.html.

Your solutions you put in the solution folder, not into the Problem folder. Next week
we work on version 0.0.2.

## HELP ##

Help with git
https://www.youtube.com/watch?v=pDmYNK68IEc

git clone https://github.com/Mikael-Helin/FE22_Casino.git
cd FE22_Casino

#Maybe you do not need to do following 2 configuration steps,
#if you do, insert your own name and e-mail.

git config user.name "Pelle Svanslös"
git config user.email pelle@svanslos.com

#Then create your own branch, use for example your name

git checkout -b pelle

#Make your changes in the Solution folder.
#When you are done, do

git add .
git commit -m "whatever comment you may want to say"
git push --set-upstream origin pelle

