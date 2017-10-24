name: inverse
layout: true
class: middle, inverse

---

# Software licensing

## [Radovan Bast](http://bast.fr)

### [NeIC](https://neic.nordforsk.org)/ [UiT The Arctic University of Norway](https://uit.no)

Text is free to share and remix under [CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Acknowledgements:
- Oxana Smirnova (suggestions and corrections)

---

layout: false

# Goals

## 1) Motivate why software licenses matter
## 2) Provide guidance on which license to choose
## 3) Practical tips
## 4) Discussion

---

## Questions we will try to answer

- Can I copy-paste code from Stack Overflow into my code?
- Who owns the code you write?
- Where does derivative work start and end?
- How can you protect your ideas, names, and implementations?
- How software licenses can influence the impact of your code.
- How to motivate contributions to your code?

---

# IANAL TINLA

## I am not a lawyer

## This is not legal advice

---

## When to worry about software licenses

Beginning of a project is the time when we tend to worry the least about a
software license

Beginning of a project is the time when we should carefully think about a
license because it may be difficult to change it later

---

## Patents vs. copyright

### When we create software, we may create patentable ideas, copyrightable expressions of ideas, and trademarkable names

- Patents protect ideas
- Copyright protects the **expression** of an idea
- Copyright is automatically attached to every novel expression of an idea (for a certain amount of years)
- Software that you write is copyrighted by default
- No person other than the creator has the right under copyright law to create "derivative works" (unless the license permits it)

---

## These slides are an expression of an idea

- Can I patent them?
- Do I need to copyright them?
- Are you allowed to share them via email or Twitter or similar?

---

## These slides are an expression of an idea

- Can I patent them? No
- Do I need to copyright them? No (copyright by default)
- Are you allowed to share them via email or Twitter or similar? Yes!

### Yes to sharing!

- Sharing explicitly allowed by creative commons license (CC BY-SA 4.0)
- Otherwise probably fine according to "fair use"

---

## Zoo of licenses

- Public domain
- Closed source or open source
- Permissive
- Academic
- Reciprocal
- Custom
- Proprietary licenses/EULAs also exist

### What happens if I do not choose a license?

- Software that you write is copyrighted by default
- Without a license it is not clear what use breaks copyright
- Nobody who is careful about her/his code base should use or even look at your code
- In other words: code without license is not useful for reuse or derivative work

---

## What is free software?

### Software freedom

Is the freedom to ...

- ... run the software for any purpose
- ... study how the software works and to adapt it to your needs
- ... redistribute copies of the software
- ... improve the software and distribute your improvements to the public

### Does not mean that software costs nothing or that it has no owner

### Fear of being scooped

- Releasing under an open source license does not mean you need to share everything immediately

---

## Public domain

- Software in the public domain has no owner
- Open source does not mean public domain
- Open source software remains the intellectual property of the copyright owner

### Problems with public domain

- In certain jurisdictions you cannot just give up your rights without an explicit license
- Public domain does not provide you a warranty and does not protect you from a lawsuit

Source: http://blog.milkingthegnu.org/2008/03/10-answers-for.html

Public license releases the original author from all responsibilities, and does
not guarantee that software does what it was intended to do; the other end of
the spectrum is a guaranteed service and responsibility for bugfixing.

---

## Academic licenses vs. reciprocal licenses

### Academic/permissive

- Derivative works do not have to be contributed back into public commons
- One-way remixable

### Reciprocal

- .red[Derivative works are required to be distributed under the same license]
- Two-way remixable
- Copyleft/reciprocity
- Share-alike

---

## Creative commons licenses (not quite a software license)

### Open content

Right to:

- Retain
- Reuse
- Revise
- Remix
- Redistribute

### Copyleft movement

- "Some rights reserved" instead of "all rights reserved"
- Goal: support the building of a richer public domain

### CC0 (creative commons zero)

- Equivalent of public domain

https://en.wikipedia.org/wiki/Creative_Commons

---

## Are you allowed to use open source software in a closed source project?

Depends on whether you distribute it:

- No distribution: you can use it in almost any way you can imagine
- If distributed: depends on the open source license

How can somebody find out that you redistribute open source software breaking license terms
if you distribute only binaries?

- Unethical (and illegal)
- Problematic for your own court case to demonstrate that somebody else stole your closed source code

---

## Can I copy-paste code from Stack Overflow into my code?

- Non-code: CC BY-SA 3.0 with attribution required
- Code: MIT license

### You are recommended to do one of these 2 things, or both:

- A) Add a comment to your code that links back to the post where you found it, or
- B) Comply with the MIT as it is typically used, by including the full license text in your source

https://meta.stackexchange.com/questions/271080/the-mit-license-clarity-on-using-code-on-stack-overflow-and-stack-exchange

---

## Derivative works

- Collective works and derivative works are also original works of authorship
- Collective work: aggregation of separately written software
- Joint work: contribution to a joint work is owned by all of its authors jointly

### Goals for derivative work

- Encourage free and open source software development
- Avoid scaring proprietary software users away

Reference: http://www.rosenlaw.com/lj19.htm

---

## How can you tell when you have created a derivative work?

- Modifying source code by revising the code or translating it into another
  computer language, recasting, or adapting is derivative work

### Typically not derivative works:

- Linking to libraries (static or dynamic), plug-ins, and drivers
- If you can use a code without looking at the source code (library), you are probably not creating derivative work

Reference: http://www.rosenlaw.com/lj19.htm

---

## Clean room design

You need at least two teams

1. Team A studies code A
2. Team A writes specifications for code A
3. Legal team checks specifications
4. Team B never sees code A
5. Team B implements code B based on specifications

Result is **not** derivative work.

### Can I write a code from scratch and call it "Linux"?

- Imagine I have never seen the Linux source code
- No: Trademark protection

---

## Questions to ask yourself when looking for the right license

- What do you want to achieve?
- What do you wish to avoid?
- Do you want to make money with the project?
- Do you mind if others do?
- Do you care about derivative work?
- Do you want to attract developers?
- Do you care about impact of your code? Proprietary software users?

---

## Recommendations

- Consider compatibility "up" and "down"
- Take an [OSI](https://opensource.org/licenses)-approved license: makes it easier to evaluate
  [compatibility](https://en.wikipedia.org/wiki/License_compatibility)
- Do not use custom licenses: compatibility not clear

### Permissive (I don't care; you can use my code even in commercial code)

- I need to limit my liability: MIT or Apache or BSD2
- In addition I wish to have the no-endorsement clause: BSD3

### Reciprocal (you can use my code if I can use your code)

- GNU GPL or GNU Affero GPL (for web services)

### Share-alike but compatible with closed-source code (you can use my code if I can use changes you make to my code)

- Dynamic relinking possible: GNU Lesser GPL
- Dynamic or static linking: Mozilla Public License v2.0

---

## Can I change the license later?

- The copyright owner can
- Who is the copyright owner if your code got contributions from other
  developers? You may need to get a signed agreement from all past
  contributors.
- Consider drafting a contributor license agreement (CLA) and copyright assignment (CA)
- Make contributors aware that contributions may imply CLA and CA

---

## Who owns the copyright for software you write?

- You?
- Your university?

### Intellectual property depends on the country!

- So-called works made for hire
- Personal experience: if you ask legal experts it can get complicated
- Nobody can take away code from you if you develop in your free time on your hardware using your own network

### Even within a country it can vary depending on the employer (public vs private)

---

## If you own your software

- You can relicense
- You can dual-license

### If you do not own your software, you can:

- Request a transfer of ownership (check with your university)
- Open source your code to make sure you are not locked out of your own code
  once you change affiliation (you might need to inform your university)

---

## Practical aspects

- Add a LICENSE file to your repository (GitHub understands it)
- Agree on a licensing strategy and make it public and visible
- License your supporting information (images) under
  creative commons (use [Zenodo](https://zenodo.org) or [Figshare](https://figshare.com))
- Unrelated but still recommended: make your code easy to cite (use [Zenodo](https://zenodo.org) to assign DOIs to code releases)

### Personal observation

- People are generally good and will cite your code and involve you in derivative projects

---

## Should I add a copyright header?

You should mark an original work with a copyright notice in the form:

```
(c) Copyright <year> <author>
```

- No longer required to obtain copyright
- However it provides added protection: defendant cannot argue s/he was unaware who owned the copyright on the work

Reference: http://www.rosenlaw.com/oslbook.htm

---

## My personal choices

### When I have the choice, I prefer to ...

- ... use an open source code (scientific reproducibility)
- ... develop under an open source license to keep access to my code
- ... develop under a share-alike license in order to not lock myself out of improvements to my code
- ... contribute to a share-alike licensed software of others because I know they won't run away with my code
- ... distribute my code under a share-alike license to motivate people like me to contribute

### When I am "forced" to contribute to a closed-source code ...

- ... I contribute my code explicitly under LGPL or MPL (to not lose control)

### Food for thought

Is closed-source development compatible with reproducible research?

---

## Good resources

- https://www.software.ac.uk/choosing-open-source-licence
- http://oss-watch.ac.uk/resources/ipr
- http://www.rosenlaw.com/oslbook.htm
- http://depth-first.com/articles/2006/12/29/dispelling-open-source-confusion-an-introduction-to-licenses/
- http://blog.milkingthegnu.org/2008/03/10-answers-for.html
- http://www.oreilly.com/openbook/osfreesoft/
- https://tldrlegal.com/
- https://hintjens.gitbooks.io/social-architecture/content/chapter2.html
