

## Can I copy-paste code from Stack Overflow into my code?

---

## What is free software?

### Software freedom

- The freedom to run the software for any purpose
- The freedom to study how the software works and to adapt it to your needs
- The freedom to redistribute copies of the software
- The freedom to improve the software and distribute your improvements to the public

### Does not mean that software costs nothing or that it has no owner

---

## Are you allowed to use open source software in a closed source project?

Depends on whether you distribute it

How can somebody find out that you redistribute open source software breaking license terms
if you distribute only binaries?

---

## Food for thought

Is closed-source compatible with reproducible research?

---

## Goals

- Motivate why software licenses matter
- Provide guidance on which license to choose

---

## IANAL disclaimer

---

## Questions to ask yourself when looking for the right license

- What do you want to achieve?
- What do you wish to avoid?
- Do you want to make money with the project?
- Do you mind if others do?
- Do you care about derivative work?
- Do you want to attract developers?
- Do you want to not repel proprietary software users?

---

## Patents vs. copyright

### When we create software, we create both copyrightable expressions and patentable ideas

- Patents protect ideas
- Copyright protects the **expression** of an idea
- Copyright is automatically attached to every novel expression of an idea (for a certain amount of years)
- Software that you write is copyrighted by default
- No person other than the creator has the right under copyright law to create "derivative works"

---

## Practical aspects

- LICENSE file
- Copyright header
- Agree on a licensing strategy
- CLA
- License your supporting information (images) under creative commons (use Zenodo or Figshare)
- Unrelated but still recommended: use Zenodo to assign DOIs to code releases

---

## Can I write a code from scratch and call it "Linux"?

- Imagine I have never seen the Linux source code
- No: Trademark protection

---

## Should I add a copyright header?

You should mark an original work with a copyright notice in the form:

```
(c) Copyright <year> <author>
```

- No longer required to obtain copyright
- However it provides added protection: defendant cannot argue s/he was unaware who owned the copyright on the work

CITE ROSEN

---

## What happens if I do not choose a license?

- Nobody who is careful about her/his code base should use or even look at your code

---

## Who owns the copyright for software you write?

- You?
- Your university?

### Intellectual property depends on the country!

works made for hire

Personal experience: if you ask legal experts it can get complicated

### If you own your software

- You can relicense
- You can dual-license

### If you do not own your software, you can:

- Request a transfer of ownership (check with your university)
- Open source your code to make sure you are not locked out of your own code
  once you change affiliation (you might need to inform your university)

Nobody can take away code from you if you develop in your free time on your hardware using your own network.

---

## These slides are an expression of an idea

- Are you allowed to share them?

---

## These slides are an expression of an idea

- Are you allowed to share them via email or Twitter or similar?

### Yes!

- Explicitly allowed by creative commons license (CC-BY-SA 4.0)
- Otherwise probably fine according to "fair use"

---

## Creative commons licenses

---

## Public domain

- Software in the public domain has no owner
- Open source does not mean public domain
- Open source software remains the intellectual property of the copyright owner

### Problems with public domain

- In certain jurisdictions you cannot just give up your rights without an explicit license
- Public domain does not provide you a warranty and does not protect you from a law suit

SOURCE: http://blog.milkingthegnu.org/2008/03/10-answers-for.html

---

## When to worry about software licenses

- Beginning of a project is the time when we tend to worry the least about a software license
- Beginning of a project is the time when we should think about a license

---

## Academic licenses vs. reciprocal licenses

### Academic

- Derivative works do not have to be contributed back into public commons
- One-way remixable

### Reciprocal

- Copyleft synonymous for reciprocity
- Derivative works are required to be distributed under the same license
- Two-way remixable

---

## Reciprocity: Share and Share Alike?

- May be attractive to developers

---

## Can I change the license later?

- The copyright owner can
- Who is the copyright owner if your code got contributions from other
  developers? You may need to get a signed agreement from all past
  contributors.
- Consider drafting a contributor license agreement (CLA) and copyright assignment (CA)
- Make contributors aware that contributions may imply CLA and CA

---

## Derivative works

Collective works and derivative works are also original works of authorship

Collective work: aggregation of separately written software

-> Chain of title for copyright

Joint work: A contribution to a joint work is owned by all of its
authors jointly.

How can you tell when you have created a derivative work?

Very important question!

- Modifying source code by revising the code or translating it into another computer language, recasting, or adapting is derivative work

The primary indication of whether a new program is a derivative work is whether
the source code of the original program was **used**, modified, translated or
otherwise changed in any way to create the new program.

Typically not derivative works:

- Linking to libraries (static or dynamic), plug-ins, and drivers
- If you can use a code without looking at the source code (library), you are probably not creating derivative work

CITE ROSEN http://www.rosenlaw.com/lj19.htm

Goals:

- Encourage free and open source software development
- Avoid scaring proprietary software users away

---

## Clean room design

You need at least two teams

1. Team A studies code A
2. Team A writes specifications for code A
3. Legal team checks specifications
4. Team B never sees code A
5. Team B implements code B based on specifications

---

## Licenses and restrictions

- A license must contain limitations [VERIFY]
- Compare with poetic and WTF license
- Licenses may limit modifications of the code
- Open source licenses may limit modifications of the license

---

## Trademark

- Consider registering a trademark for the software name

---

## OSI-approved vs. custom license

---

## Recommendations

- Take a standard license
- Consider compatibility with libraries you use and code you want to be used by

### Permissive (you can use my code even in commercial code)

- I don't care but I care about limiting my liability: MIT
- I don't care but I care a bit more about X: BSD

### Reciprocal (you can use my code if I can use your code)

- GNU GPL, AGPL

### Share-alike but compatible with closed-source code (you can use my code if I can use changes you make to my code)

- Dynamic relinking possible: GNU LGPL
- Dynamic or static linking: MPL v2.0

---

## My personal choices

### When I have the choice

- I prefer to use an open source code (scientific reproducibility)
- I prefer to contribute to a share-alike licensed software
- I prefer to distribute my code under a share-alike license to motivate people like me to contribute
- I prefer to develop under a share-alike license in order to not lock myself out of the code I have written

---

## References

- https://www.software.ac.uk/choosing-open-source-licence
- http://oss-watch.ac.uk/resources/ipr
- http://www.rosenlaw.com/oslbook.htm
- http://depth-first.com/articles/2006/12/29/dispelling-open-source-confusion-an-introduction-to-licenses/
- http://blog.milkingthegnu.org/2008/03/10-answers-for.html
- http://www.oreilly.com/openbook/osfreesoft/
- https://tldrlegal.com/
- https://hintjens.gitbooks.io/social-architecture/content/chapter2.html
