**Shayan Defence**



Revisions
--> RQs DONE
* For each chapter, create a set of "research questions" and then restructure the middle/end to answer them. 
  * Examples
    * https://arxiv.org/pdf/2304.09822
    * https://arxiv.org/pdf/2304.02981
    * https://arxiv.org/pdf/2312.02752
  * Intro: enumerate the questions, 1 paragraph on why they are important & novel (reader knows something more than they did before, assuming they have read every paper in your related work), 1 paragraph answer
  * Restructure the (sub)-sections of the paper to map each one of the RQs, recall the RQ (one sentence near the start), recall the answer to the RQ (one sentence near the end)

- Background chapter -- DONE

  - I am going to explain Bitcoin because it introduced a novel type of consensus---Nakamoto consensus
  - PoW
    - From there, I'll explain Ethereum and Monero
    - Alternatives to Bitcoin's consensus (POW): Monero is just a small step from Bitcoin, reworks the proof of work -> takeaway is computer-based mining. Also adds privacy but we don't use this in the thesis
    - PoS: Ethereum
    - Paragraph of others...

| Chapter        | Blockchain System                  |
| -------------- | ---------------------------------- |
| Crypto-jacking | Monero                             |
| Front-running  | Ethereum EVM, applicable to others |
| Oracles        | General to any blockchain          |
| Auditing       | Ethereum EVM, applicable to others |
|                |                                    |

- Smart contracts as “verified code” -> DONE
  - Opt-in to verifiability (via Etherscan)

  

- EOA vs contract addresses -> reread and make sure it is ok --> DONE
  - Different in terms of keys



Knowledge gaps

- I see these gaps but (a) what are they and (b) why do they matter?

- Why these four? (Front-running, cryptojacking, auditing, oracles)
  - Important topics that are being discussed in industry but not in academia
  - 200 problems for blockchains, 50/200 you are a comparative advantage (short-list)… you selected 4 to work on
  - Why did you select them? What is the criteria? We saw it as important -> why are they important? 
    - (Keep showing up?)
  - Identify 200 "nuances" in blockchains
    - Short-list: comparative advantage (tie to your experience)
    - Timing -> foresaw issues becoming important, timely paper can open doors
    - Importance -> impact, unforseen consequences
    - Talked, read, events, conferences, talks, industry problems -> no shortage of things to work on, so how did I select?
    - Exercise: what did you throw away? Unimportant, inconsequential, timing was off (too much attention from others, no contribution) (too early), mis-match with expertise (what I had and what I wanted to learn), ...
    - Four problems in this thesis, common thing was they weren't thrown away... not complete set...



Title: “hidden layers” “of” blockchains

- Not correct

- No definitions
  - Front-running, cryptojacking, oracles -> developers/users shortfall in knowledge of (expectation gap, mental models, red-tape, fine print)
  - Discrepancy between "how blockchains work" and "how tradition systems work", where assumption is that blockchains are the same traditional systems
  - Nuances, discrepancies

  * Understanding Technical {Nuances} of Blockchains // and their {Unforeseen} Consequences
  * What I study // and why
    * Make sure there is a crisp definition of each thing in {}
    * Nuances:
  
- | Chapter        | Blockchain System                                        | Non-Blockchain System                                        |
  | -------------- | -------------------------------------------------------- | ------------------------------------------------------------ |
  | Crypto-jacking | Trick users into mining without them realizing           | Nodes are deliberately deployed                              |
  | Front-running  | Everyone can see your transaction before it is finalized | A sent transaction is only seen by the server that processes it |
  | Oracles        | Smart contracts can only reference on-chain events       | Servers can access anything online                           |
  | Auditing       | Not so different from traditional system                 | Financial audit procedures are well-developed                |
  |                |                                                          |                                                              |

- | Chapter        | What was Unforeseen? | What was the consequence? |
  | -------------- | -------------------- | ------------------------- |
  | Crypto-jacking | ?                    | ?                         |
  | Front-running  | ?                    | ?                         |
  | Oracles        | ?                    | ?                         |
  | Auditing       | ?                    | ?                         |
  |                |                      |                           |



Personal motivation
- Thesis
- Connect it better to the research questions



References -- DONE
- Fine toothed comb
- URLs



Chapter blurbs
- Co-authors (not supervisors) -- DONE
- Captions of tables/figures -> no relative time references (last 12 months) -- DONE

 

Conclusion
- No summaries
- Future work is vague
- What is the connection between them? Theme?









---



- Cryptojacking
  - Accessibility libraries
- Front-running
  - Mitigation is novel techniques, existing techniques?
    - Positive or normative



Oracles SoK Methodology

- Oracles -> analysis of papers, know the details, how many papers did you look at?
  - Selection criteria for what we looked at? Be specific
  - How did you make sure you didn’t miss something (comprehensive)? Speaking tour, google, 
  - Not ad hoc

- Taxonomy -> how you come up with it? (c.f., password alternatives SoK) Discussion, iterative 
  - Positive not normative
  - Clarified 

- Table 5.1
  - How do you come up with criteria?
  - UDS -> drop U -> D and S
  - How do we future-proof it? Generally we cannot (not our issue)
    - We don’t rate brands of oracles, we distil into primitives
    - Has it stood the test of time?

  



