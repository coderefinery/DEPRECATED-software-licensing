name: inverse
layout: true
class: middle, inverse

---

# Software licensing and citation

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
## 3) Show how to make your code better citable
## 4) .blue[Discussion]

---

## Questions we will try to answer

- How can you protect your ideas, names, and implementations?
- Can you copy-paste code from Stack Overflow into your code?
- Who owns the code you write?
- Who owns the code you have completely rewritten?
- How software licenses can influence the impact of your code.
- How to motivate contributions to your code by choice of license?

## Disclaimer

- I am not a lawyer
- This is not legal advice

---

## Patents vs. copyright

### When we create software, we may create patentable .blue[ideas], copyrightable .blue[expressions] of ideas, and trademarkable .blue[names]

- Patents protect ideas
- Copyright protects the **expression** of an idea
- Copyright is automatically attached to every novel expression of an idea (for a certain amount of years)
- Software that you write is copyrighted by default
- No person other than the creator has the right under copyright law to create "derivative works" (unless the license permits it)
- You cannot put a copyright on an algorithm. Or can you?

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

## What is free software?

### Software freedom

Is the freedom to ...

- ... run the software for any purpose
- ... study how the software works and to adapt it to your needs
- ... redistribute copies of the software
- ... improve the software and distribute your improvements to the public

---

## What is free software?

### .blue[Free software does not mean that software is for free]
### .blue[Open source license does not mean you need to share everything immediately]
### .blue[Open source does not mean public domain]: software in the public domain has no owner

---

## Problems with public domain

- In certain jurisdictions you cannot just give up your rights without an explicit license
- Public domain does not provide you a warranty and does not protect you from a lawsuit

Source: http://blog.milkingthegnu.org/2008/03/10-answers-for.html

Public license releases the original author from all responsibilities, and does
not guarantee that software does what it was intended to do; the other end of
the spectrum is a guaranteed service and responsibility for bugfixing.

---

## Zoo of licenses

- Public domain
- Closed source or open source
- Permissive
- Academic
- Reciprocal
- Custom
- Proprietary licenses/EULAs

### What happens if I do not choose a license?

- Software that you write is copyrighted by default
- Without a license it is not clear what use breaks copyright
- Nobody who is careful about her/his code base should use or even look at your code
- In other words: code without license is not useful for reuse or derivative work

---

## Questions to ask yourself when looking for the right license

- What do you want to achieve?
- What do you wish to avoid?
- Do you want to make money with the project?
- Do you mind if others do?
- Do you care about having access to derivative work?
- Do you want to attract developers?
- Do you care about impact of your code? Proprietary software users?

---

## Software licensing explained with cakes

<img src="img/cake-1.svg" style="width: 15%;"/>

- Imagine you compose a recipe for a really tasty cake.
- Your family and friends love it.
- In regular intervals you distribute cakes (release binaries).
- But you can only bake so many.

(cake emoji licensed under CC-BY-SA-4.0, attribution: Emoji One)

---

## Software licensing explained with cakes

<img src="img/cake-1.svg" style="width: 15%;"/>

- Imagine you compose a recipe for a really tasty cake.
- Your family and friends love it.
- In regular intervals you distribute cakes (release binaries).
- But you can only bake so many.

### A friend tells you: why not distribute the recipe?

- Create the OpenCake organization.
- Start a mailing list (feedback) and put your recipe on GitHub.
- More people will be able to enjoy the cake (increase impact).
- Maybe somebody will find ways to improve the recipe.
- They will know that it was your idea even though somebody else bakes it.

---

## Mrs. X (running a famous restaurant) finds your cake recipe on GitHub

<img src="img/cake-1.svg" style="width: 15%;"/>

- The chef tries it and it is great.
- The chef suggests improvements (derivative work):

<img src="img/cake-2.svg" style="width: 15%;"/>

- It becomes part of the restaurant menu.
- Or does it? Depends on your license!

---

## Possible outcomes 1/4: closed or custom

### Closed source

- Your cake is celebrated by The New Yorker magazine.
- People will have difficulties to reproduce your celebrated recipe.
- Nobody else will improve your recipe.
- Fewer tasty cakes will get consumed.

### Custom license

- No restaurant chef will touch it: too much hassle to employ a lawyer to be sure
  that the cake can be served to customers.
- But maybe they will bake it and eat it and not distribute it and that is OK.

---

## Possible outcomes 2/4: permissive

### MIT or Apache or BSD-2

- It is OK to use the recipe and sell the cake.
- It is OK to not share the improved recipe.
- If somebody becomes sick, it is not the fault of the OpenCake organization (limit of liability).
- OpenCake organization may not be able to build on top of the improvements.

### BSD-3

- In addition to the above it is understood that the updated recipe are not endorsed by OpenCake.

---

## Possible outcomes 3/4: reciprocal

### GNU GPL or GNU Affero GPL (for web services)

- If the cake is a part of the menu, the famous restaurant has to share the recipes of the entire menu.
- You can use their improved recipe and improve it further:

<img src="img/cake-2.svg" style="width: 15%;"/>
<img src="img/cake-3.svg" style="width: 15%;"/>

- Other restaurants can then reuse and improve the full menu and the hope is that we will all eat better food.

---

## Possible outcomes 4/4: share-alike

### GNU Lesser GPL (LGPL)

- The famous restaurant has to share only the improved cake recipe but can keep the rest of the menu closed.
- The restaurant guests have to be able to exchange the cake from the menu by improved cakes from other restaurants (dynamic relinking).

### Mozilla Public License v2.0

- Like LGPL but do not require that the modified cake can be exchanged by the restaurant guest.

---

## Back to code: derivative works

- Collective works and derivative works are also original works of authorship
- Collective work: aggregation of separately written software
- Joint work: contribution to a joint work is owned by all of its authors jointly

### Why is it important to know?

- Because the license may limit what you can do with the derivative work

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

You need at least two persons/teams

1. Team A studies code A
2. Team A writes specifications for code A
3. Legal team checks specifications
4. Team B never sees code A
5. Team B implements code B based on specifications

Result is **not** derivative work.

---

## Are you allowed to use open source software in a closed source project?

Depends on whether you distribute it:

- No distribution: you can use it in almost any way you can imagine
- If distributed: depends on the open source license

### How can somebody find out that you redistribute open source software breaking license terms if you distribute only binaries?

---

## Are you allowed to use open source software in a closed source project?

Depends on whether you distribute it:

- No distribution: you can use it in almost any way you can imagine
- If distributed: depends on the open source license

### How can somebody find out that you redistribute open source software breaking license terms if you distribute only binaries?

- Unethical (and illegal)
- Problematic for your own court case if somebody else stole your closed source code

---

## Can I copy-paste code from Stack Overflow into my code?

---

## Can I copy-paste code from Stack Overflow into my code?

- Non-code: CC BY-SA 3.0 with attribution required
- Code: MIT license

### You are recommended to do one of these 2 things, or both:

- A) Add a comment to your code that links back to the post where you found it, or
- B) Comply with the MIT as it is typically used, by including the full license text in your source

https://meta.stackexchange.com/questions/271080/the-mit-license-clarity-on-using-code-on-stack-overflow-and-stack-exchange

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

## Recommendations

- License your code very early in the project
- Consider license-compatibility "up" and "down"
- Take an [OSI](https://opensource.org/licenses)-approved license: makes it easier to evaluate
  [compatibility](https://en.wikipedia.org/wiki/License_compatibility)
- Do not use custom licenses for open source: compatibility not clear

### Practical aspects

- Add a LICENSE file to your repository (GitHub understands it)
- Agree on a licensing strategy and make it public and visible
- License your supporting information (images) under
  creative commons (use [Zenodo](https://zenodo.org) or [Figshare](https://figshare.com))

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

## Good resources for software licensing

- https://www.software.ac.uk/choosing-open-source-licence
- http://oss-watch.ac.uk/resources/ipr
- http://www.rosenlaw.com/oslbook.htm
- http://depth-first.com/articles/2006/12/29/dispelling-open-source-confusion-an-introduction-to-licenses/
- http://blog.milkingthegnu.org/2008/03/10-answers-for.html
- http://www.oreilly.com/openbook/osfreesoft/
- https://tldrlegal.com/
- https://hintjens.gitbooks.io/social-architecture/content/chapter2.html
- https://users.aalto.fi/~darstr1/cheatsheets/ipr-cheatsheet.pdf

---

## Making your code citable

### Create a DOI for each release

- https://guides.github.com/activities/citable-code/
- https://zenodo.org

---

## Citation file format

- [A standard format for CITATION files](https://software.ac.uk/blog/2017-12-12-standard-format-citation-files)
- [Citation File Format (CFF) 1.0.3](https://citation-file-format.github.io)


### Specifications

- Machine-readable
- Human-writable: easy to read, write and edit
- Standard format: [YAML](http://yaml.org)
- Support fine-grained types: software source code, software executable, software container, and virtual machine (image), etc.
- Versioned
- Include DOI, hash, or at least contact information
- Support all scenarios for authorship and roles for authors
- Allow to link to [ORCID](https://orcid.org)
- Compatibility with other formats (Zenodo, Figshare)
- Allow unicode, UTF-8 encoding

---

Example [CITATION.cff](https://github.com/citation-file-format/citation-file-format/blob/master/CITATION.cff) file:

```
cff-version: 0.9-RC1
message: "If you use, or want to cite, the Citation File Format in this version (0.9-RC1), please use the following metadata."
references:
  - type: report
    authors:
      - family-names: Druskat
        given-names: Stephan
        orcid: 0000-0003-4925-7248
        role: main-author
    title: "Citation File Format (CFF)"
    version: 0.9-RC1
    repository-code: https://github.com/sdruskat/citation-file-format
    year: 2017
    date-published: 2017-10-06
    doi: 10.5281/zenodo.1003150
```
