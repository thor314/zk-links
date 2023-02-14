# A Concise, Opinionated ZK Link Tree
Reader note: This is a work in progress. When it's ready, I'll advertise it more. But I already think it's reasonably useful enough to pin.

WTF Why? Why another link tree? Aren't there already a billion link trees?
Yeah, there are already a billion link trees. [Some](https://kb.delendum.xyz/zk-knowledge) of them kick ass.

This link tree aims to be objective-oriented, introductory, complete, concise, and application-agnostic in its resources. It is directed at non-experts, who are looking to gain familiarity with mathematics, cryptography, implementations, and primitives. For these non-experts, the resource will provide comprehensive and best-in-class links to blog posts and books, rather than papers. For experts, the resource will also provide comprehensive resources as a reference. Additionally, comprehensive link dumps, as well as the excellent Delendum resource, are provided for those who prefer all-the-links. Finally, several applications and projects are included to help users stay up-to-date with the latest developments.

If you have suggestions or disagree with my opinion that $RESOURCE is the best on $TOPIC, DM me an argument for a better one on Twitter @cryptograthor.

## Best single overview and canonical reference
- [Delendum's ZKP knowledge base](https://kb.delendum.xyz/zk-knowledge#foundations-of-zksnarks) is what this link tree would be, were it 20 times more comprehensive. Includes resources on the foundational papers and libraries, as well as excellent tables comparing protocols and their components. It includes, for example, this excellent table on polynomial commitment schemes:
![[Screen Shot 2022-09-30 at 3.51.16 PM.png]]
## Ser, gib introductory and comprehensive content:
### to learn the fundamentals; basic number-theory, algebra, and cryptography
You don't need the fundamentals if you're in a hurry to write code or even skip straight to zk, but they are good if you intend to build a well-grounded knowledge base.
- Interactive Post: [Number theory explained from first principles by Kaspar Etter](https://explained-from-first-principles.com/number-theory) recommended for an excellent introductory and complete resource to number theory used in cryptography, taking full advantage of the web as a medium.
- If you're in no hurry, pick up a book on Algebra, eg [Dummit and Foote,](https://www.amazon.com/Abstract-Algebra-3rd-David-Dummit/dp/0471433349) which "presents the material clearly but doesn't dummit down".
- Book: [An Introduction to Mathematical Cryptography](https://drive.google.com/drive/u/1/folders/1ILBHUZrDZDku3HfK1yyp6AbBD_F3nRm5) recommended as a complete mathematical resource to asymmetric key cryptography. Especially recommended are the first 5 chapters, ch 7 on signatures, and the section from 8 on cryptographic hashes. Don't worry too much about symmetric key cryptography or lattices. Also don't worry if the elliptic curve stuff goes over your head.
    - I chose this over [The Joy of Cryptography](https://joyofcryptography.com/) for its more complete coverage of algebraic primitives, elliptic curves, and asymmetric key cryptography. Joy is a better introduction to symmetric key cryptography.
### to learn about all aspects of mathematical ZK
- Blog post: [Zero Knowledge Proofs: An illustrated primer by Matthew Green](https://blog.cryptographyengineering.com/2014/11/27/zero-knowledge-proofs-illustrated-primer/) a thorough high-level two-part introductory blog post on ZK proofs.
- Book: [Proofs Arguments and Zero Knowledge by Justin Thaler](https://people.cs.georgetown.edu/jthaler/ProofsArgsAndZK.pdf) recommended for completeness and accessibility over current state of zk protocols and their underlying primitives. In particular, I recommend the final chapter for a high level over the current state of the art of zk protocols.
- Videos: [ZK Whiteboard Sessions by ZK Hack and Community](https://zkhack.dev/whiteboard/) Recommended for video content by experts in the community, with excellent links to major papers and blog posts in a sensible order.
- Docs: [ZKDocs by Trail of Bits](https://www.zkdocs.com/docs/zkdocs/) is a good grab-bag reference to mathematical and cryptographic concepts that you may or may not be familiar with. Not very complete yet, but well put together and still growing. Doesn't cover complete zk protocols, so much as generally useful-to-know concepts and primitives, such as Shamir's Secret Sharing, and Schnorr's identification protocol.
### ZK served with implementation details
- Book: [The Moon Math Manual by Anna Kaplan](https://raw.githubusercontent.com/LeastAuthority/moonmath-manual/main/main-moonmath.pdf) introduces aspects of zero-knowledge from a development perspective. Generally applicable topics balance of math and implementation details, only goes into depth on one major protocol, Groth16 (which is good).
- Repo: [arkworks](https://github.com/arkworks-rs) is the goto Rust implementation for commonly used protocols.
- Small Reference: [ZK Community Reference by ZKProof](https://docs.zkproof.org/reference.pdf)  a 120-page community reference covering theoretical aspects of definition and theory, as well as practical aspects of implementation and applications.
### to write zk-applications for Ethereum
- [ZK Learning Resources by 0xPARC](https://learn.0xparc.org/materials/intro) is the most comprehensive resource I'm currently aware of on writing zk-applications with Circom.
### linktrees with all the links
Useful if you want to see everything popular or significant in $NAME_A_TOPIC.
- [Ingoyama's link tree](https://github.com/ingonyama-zk/ingopedia)
- [Matter Labs' link tree](https://github.com/matter-labs/awesome-zero-knowledge-proofs)
- todo: read [Zero Knowledge Canon, part 1 & 2 - a16z crypto](https://a16zcrypto.com/zero-knowledge-canon/)

## I, $INTREPID_READER, want the best resource on $PRIMITIVE:
This section needs the most fleshing out.
### elliptic curves and pairings:
- Interactive introductory blog post: [The Animated Elliptic Curve by @XargsNotBombs](https://curves.xargs.org/)
- Book: [Pairings For Beginners by Craig Costello](http://infosec.pusan.ac.kr/wp-content/uploads/2019/09/Pairings-For-Beginners.pdf) 120 pages on as much as you'll ever need to know about pairings, and probably more.
### PCS
- pedersen commitments
- Inner product arguments
- KZG
- FRI
- DARK
- Plonkish Arithmetization

## Misc Applications
I'm including this section specifically to include one book, but it may grow over time. This is a great area to suggest resources. I'd love a good resource on Zcash, for instance.
### Monero
- book: [Zero to Monero](https://www.getmonero.org/library/Zero-to-Monero-2-0-0.pdf). Monero, a private cryptocurrency, is one of the largest in-production zero-knowledge applications. I would put 3:1 odds that Monero gets put on a US sanctions list within 3 years (before 2026). This is a 120-page book on Monero and the primitives used.

## I'm here for a good time, where should I hang out?
### community
- Hang out with us on the [ZK Hack Discord](https://discord.gg/tHXyEbEqVN). We're an open zero-knowledge enthusiast community, with several study groups and an annual ZK Capture The Flag.
### a weekly podcast covering ZK and blockchain topics
- [ZK Podcast](https://zeroknowledge.fm/) about a third of these resources are produced by the folks at the ZK Podcast. They're the best.
### monthly newsletter
- [ZK Mesh](https://zkmesh.substack.com/) A monthly newsletter with links to papers, articles, and resources you might have missed.
### a jobs board
- [ZK Jobs Board](https://jobsboard.zeroknowledge.fm/) get a zk job already, cryptographippie.

## Underdiscussed projects:
This section needs work
There are popular projects you probably have heard of already (zk-rollups 👀 ).
I'd like to close out by signal boosting some great projects you may not have heard about.
An application in verifiable, self-hostable, decentralized identity:
- WorldCoin
Privacy enablers:
- NYM
- Penumbra
ZK Instruction Sets:
- RISC Zero
- Scroll (and in general, zkEVM designers)
ZK applied research on general applications:
- 0xPARC

## I'm asking for help
(todo: move some of these into a new section)
This post could be more complete. There are several areas that I wish I had a more complete resource to recommend. Instead of recomminding an good-but-not-comprehensive, or comprehensive-but-not-good resource, I've deferred to recommending other link-trees, like Delendum's, who in turn link to the canonical papers.
I would like more complete resources on:
- polynomial commitment schemes
    - pedersen commitments
    - Inner product arguments
    - KZG
    - FRI
    - DARK
    - Plonkish Arithmetization
- R1CS
- A high level, non-mathematical history of research and development in the space
- The GKR Protocol and Sumcheck
- Using existing ZK R1CS compilers (eg Circom)
