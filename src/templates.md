# More on Project Templates

It’s tempting to say that this and that DAO is going to be able to fund any kinds of projects, but this approach pushes the risks to stratospheric levels, and the DAO is then faced with the ages-old investment “adage”: you don’t really know anything, so spray and pray. 

Pipeline aims to disrupt *the way certain creative products* are *produced* and distributed. It concerns itself with *known production quantities* while also avoiding inserting itself into the creative process.

We could loosely define Pipeline as a replacement for the centralized “studio” system, where all functions of a vertically-integrated publisher/studio/distributor behemoth are replaced with autonomous, decentralized operational units that all act together towards much the same goals, but in a fairer fashion and with more efficient access to markets .

To deliver on this promise, we want less chaos and pivoting, like in startup enterprises, and more of established processes like in well-researched products.

*In fact, it would serve Pipeline well to simply adopt the technical-level conveyor belts underpinning the production and distribution of the traditional forms of written and visual material.*

For instance, we don’t need to invent the wheel where book writing is concerned – even though there are variations in how exactly writers move from milestone to milestone and which transformations and when are subsequently applied to the manuscript – where Pipeline is concerned, the milestones are likely to be the same for any book.

Say, writers famously schism themselves into plotters and pantsers. Plotters plan everything out (which often causes writer’s block) and then set out to write; pantsers just write until it’s done (which more often causes regret and rewrites).  

The nature of the creative process, however, is such that at the end there’s no market advantage to either approach. Ultimately, both types of writers will arrive at multiple manuscript drafts, each draft hopefully stronger than the last. 

They will also inevitably break down books into chapters to tackle the humongous task piecemeal, so here already we’re beginning to see the seeds of a template.

We could consider chapters low-level deliverables, and drafts, major milestones. 

On both, there will be back-and-forth with an editor or several, either real-time or iterative, until finally all parties are satisfied with the result. And we could have an illustrator process running in parallel, with its own deliverables (images for the book.)

I’m just briefly touching on the specifics here (as more research is required), but the key takeaway is that the whole process can be formalized using a business process modeling language, and that formal description becomes a *project template*.

A process expressed in a business process modeling language will closely resemble a finite state machine (an FSM). An FSM is a computation model which can be expressed in software, and both BPMLs and FSMs deals in *actors*, *states*, *input events* and *output events*. Coincidentally, this is the same model smart contracts follow. When an input event changes the state of a smart contract and optionally produces an output event, we call such transformation a *transaction*.

So now, at least at the conceptual level, we see that it’s possible to map a creative process to a smart contract by formally describing the “business process of the creative process.”

Ultimately, the idea here is to have multiple Project Templates and a processing engine running the templates, but also be able to augment existing templates and create new one, through Pipeline DAO’s proposal/voting process.

Instead of writing a new smart contract every time there’s an augmentation or a new template, it should be possible to develop a more generalized template execution engine that would interpret the templates.
