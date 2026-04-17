---
layout: post
title: "Building a Bitcoin Circular Economy: Five Spectrums You Have to Navigate"
date: 2026-04-18
categories: bitcoin circular-economy adoption lightning
author: pretyflaco
description: "Five spectrums you have to navigate when choosing tools, wallets, and an approach for your Bitcoin circular economy"
image: /assets/images/bce-spectrums.png
license: "CC BY 4.0"
license_url: "https://creativecommons.org/licenses/by/4.0/"
---

![Building a Bitcoin Circular Economy]({{ site.baseurl }}/assets/images/bce-spectrums.png)

*Based on a talk I gave to the Bitcoin Beach Grants network on April 16, 2026.*

---

I've spent the last five years building tools for Bitcoin adoption in the real world. First with the Bitcoin Beach Wallet (now [Blink](https://blink.sv)), then organizing the [Adopting Bitcoin](https://adoptingbitcoin.org) conference since 2021, and more recently leading [OpenMMLN](https://github.com/OpenMMLN), an open-source framework to bridge mobile money and the Lightning Network across Africa.

In that time, I've watched dozens of Bitcoin circular economies launch. Some thrived. Some stalled. The ones that stalled almost always made the same mistake: they tried to impose a rigid, ideological template onto a community that didn't fit it.

The communities that thrived understood something fundamental: **a circular economy is a journey -- maybe even a never-ending journey -- not a destination.** There is no point at which all your work is done and the world is free of fiat and usury. This is a constant effort that stretches over years.

And the most important thing to understand about that journey is that your community is not Twitter. On the internet, people who think alike self-select into echo chambers. In a real-world circular economy, you are bound by the people who live in your territory. You can't pick and choose them. You can't transplant people so you have the right demographic. You have to deal with a huge spectrum: different education backgrounds, different social backgrounds, different levels of intelligence, different threat models.

Bitcoin is not for everyone -- it's for anyone. But when you try to build a circular economy in a small place with enormous human diversity, you have to find common ground. If you are too narrow-minded, too fixated on how things should be, you will lose too many people. And you need those people. You can't do payments with yourself. The sats have to flow, and that requires participation.

So what I want to lay out here are five spectrums that every circular economy leader has to navigate. There is no single right answer. Context matters. But there is a direction of travel.

---

# 1. Custodial <> Self-Custodial

I wrote a piece a few years ago called ["The Bullish Case for Bitcoin Custodians."](https://www.swanbitcoin.com/industry/the-bullish-case-for-bitcoin-custodians/) Not because I believe we should all entrust our Bitcoin to Wall Street or Michael Saylor or Jack Mallers -- or Blink, for that matter. I believe the opposite: it's an existential risk to Bitcoin if everybody uses custodial solutions. The Bitcoin network is healthy and the Bitcoin mission is secure when as many people as possible hold their own keys, run their own nodes, and validate their own transactions.

But we face a dilemma. We also need Bitcoin to succeed as peer-to-peer electronic cash. If Bitcoin is only held in ETFs and on MicroStrategy's balance sheet, that's a systemic risk too. We need people actually using Bitcoin for payments, and that means we need to onboard millions of people who are not technical enough -- or confident enough -- to secure a cryptographic secret where losing it means losing everything.

This is genuinely novel in the history of humankind. We've never had a technology in the mainstream where forgetting a piece of information, or having your dog eat a piece of paper, means your entire wealth is gone. It's a new power, and like any power, people need to learn how to wield it.

Think of it like driving. You can't sit a 16-year-old in a car and say, "Stop using the bus. The car is real freedom." Yes, the car is real freedom. But for the time being, the bus gets them from A to B just as well. Then they go to driving school. They learn the rules. They practice. Eventually they're ready for the freedom -- and the responsibility -- of driving themselves.

Custodial wallets are the bus. Self-custody is the car. The goal is to get everyone driving eventually. But don't let self-custody ideology prevent people from getting started in the first place.

What works in practice: start custodial. Zero friction, no seed phrases, no channel management. A new user should be able to receive sats within 60 seconds. That's how you create the wow effect. That's how you hook people. Once they understand how Bitcoin is useful for their daily life -- once they have that personal experience -- they now have the preconditions to learn more, gain confidence, and graduate to self-custody.

The key insight: your community members will be spread across this entire spectrum simultaneously. Some on day one, some already running their own nodes. A good tool should support the entire journey, not just one end of it.

---

# 2. Spending <> Saving

In the Bitcoin circular economy world, there's enormous emphasis on spending. Use Bitcoin as money. Get the sats flowing. Onboard merchants. This is important, and I understand why it's the focus -- partly as a response to the media narrative that "Bitcoin isn't suitable for payments" (they intentionally omit the existence of the Lightning Network, which is essentially malicious reporting).

But I would argue that saving in Bitcoin is actually more revolutionary than spending it.

This might sound contrarian in a circular economy context, but hear me out. In many of the places where Bitcoin circular economies are being built, people live under highly inflationary fiat currencies. The effects of inflationary money on human behavior are well-studied, particularly by Austrian economists: when your money depreciates in value, you are disincentivized from saving. Why would you? So people develop high time preference. They think short-term. They don't plan for the future. They don't have hope for the future. This affects every decision they make, and it leads to what we'd broadly call degenerate developments in society.

Look at the buildings and architecture from the era of the gold standard. Look at the quality of the materials, the art. Something changed when we moved to fiat money. We Bitcoiners have put our finger on exactly what changed, and we have the solution.

Having access to a hard asset -- absolutely limited, that nobody can print more of, that you can protect with cryptography from any attempt to confiscate it -- this is profoundly powerful. Savings mitigates future uncertainty. If you have something you can liquidate for any service you may need, your future becomes less uncertain. That gives you peace of mind. And a person with peace of mind makes fundamentally different decisions from someone living paycheck to paycheck.

I speak from personal experience. I became a low time preference person after finding Bitcoin and starting to save. It was very different before.

So yes: Lightning for daily spending, on-chain for long-term savings. Both matter. But don't forget the savings side just because the circular economy narrative emphasizes spending.

There's a related point here about optionality. Imagine I tell you there's an amazing room that will improve your life in every way. Everything I say about it is true. Other people confirm it. But then I tell you: there's no exit door. Would you walk in?

No sane person would, even if everything I said was true. You need to know you can leave.

Dollar accounts, off-ramps, the ability to convert back to fiat -- these are the exit door. Not because we want people to leave Bitcoin, but because people will never enter if they know they can't leave. Each individual should determine their own exposure to Bitcoin versus fiat. Don't push them in any direction. Bitcoin is adopted voluntarily, and everyone knows their own timeline, risk appetite, and circumstances best.

---

# 3. Open Source <> Closed Source

This is where I become quite radical, and I make no apologies for it.

Any application that you use and cannot audit what it does is malware, in my opinion. At a minimum, it's extremely suspicious. And especially now that we have AI with amazing code review abilities, it is trivially easy to verify whether open-source software does what it claims. Find a GitHub repository, give the link to your AI tool, tell it to review the code. It takes minutes.

There is no good reason why Bitcoin software should be closed source. None. In a movement that is built entirely on open protocols -- Bitcoin is open source, all Lightning implementations are open source -- there is no excuse for the applications on top to be black boxes.

The risk goes beyond security. There are serious lock-in effects with closed-source tools, particularly ones that leverage network effects. Imagine your community adopts a closed-source wallet. It works great. The founders seem trustworthy -- you saw them speak at a conference. Fast forward two or three years. Bear market. The company's situation has changed. They become, let's say, morally flexible. They change their terms of service. They introduce surveillance. Or they just go bankrupt.

With open-source software, the community can fork it, run it themselves, keep the tool alive. With closed source, you're stranded.

I have to call out a fresh example. Tether, the largest stablecoin issuer, released a wallet recently. They market it as self-custodial. But it's closed source. Even if they give you keys and seed words, you cannot validate that the application doesn't copy those seed words and send them to a Tether server. Calling this "self-custodial" is disingenuous marketing. It's misleading.

What makes it worse: these people live in Lugano, Switzerland. In the first world. They would never use an app that's not open source for their own finances. But they're targeting people in the Global South -- lower income, lower education -- with this product. They claim to be "banking the unbanked." I call it predatory behavior.

Build on open-source rails. Your community should be able to survive any single company failing. [Blink](https://github.com/blinkbitcoin) is fully open source. [BTCPay Server](https://btcpayserver.org) is fully open source. [LNbits](https://lnbits.com) is fully open source. Use them.

---

# 4. Technical <> Non-Technical Users

Your community has both. Your tools must serve both.

On one end, you have people who may be illiterate, who interact with Bitcoin purely through QR codes, who need the absolute simplest UX imaginable. No seed phrases. No channel management. Trial accounts where you don't even need a phone number to get started.

On the other end, you have technical people who want APIs, self-hosted nodes, integrations with open protocols, the ability to build custom solutions. These people are incredibly valuable to your community. They create what amounts to magic -- and magic fascinates people. Having technically literate people in your community who can push back with facts against FUD, who can build new tools, who can explain how the technology works -- this is how innovation diffuses.

Think about it historically. When electricity was first invented, people made propaganda that it was the work of the devil and would burn houses down. We had the same with the internet. We have it now with Bitcoin -- "it's going to boil the oceans." The only way to refute these accusations is to have knowledgeable people who can counter them with facts.

The design principle is straightforward: design for the least technical person, empower the most technical person, on the same platform. At Blink, a five-year-old or an eighty-year-old can send and receive payments. But we also have one of the best Lightning APIs available at [dev.blink.sv](https://dev.blink.sv), which developers can use to build crowdfunding platforms, marketplaces, exchanges, games -- anything.

Don't let your community stagnate technologically. Even if your current tools work fine today, stay on top of what's emerging. The tools we have are good but far from perfect, and the landscape is shifting fast.

---

# 5. Push Education <> Pull Attraction

I'm going to be brief here because I was once guilty of exactly what I'm warning against, and I suspect most of you have already learned this lesson.

Pushing Bitcoin onto people who aren't curious about it doesn't work. People need to be genuinely curious to be receptive. They have to be willing to learn. If you're standing in front of someone reciting everything you know about Bitcoin and you can see in their face that it's just gobbledygook -- stop. You're wasting your time and theirs.

The alternative: become a beacon. Solve real problems that people already have. Use Bitcoin to do things that make people say, "What is that thing you used to pay? How does that work?" That organic curiosity, that word of mouth, that's how durable adoption happens. Bitcoin solves problems people already have -- you shouldn't have to explain the problem to them.

Go slow enough that the slowest person in your community can keep up. Make sure your meetups have content for people learning the ABCs. But also go fast enough that you personally enjoy the journey and don't feel stuck. Both speeds need to coexist.

---

# The Unlock: You Are the Builder

I want to close with the thing that excites me most, and it's genuinely new.

All of those companies sitting in San Francisco and London building Bitcoin software -- they have no idea about the problems where you are. They don't know how business works in your town. They don't know what the friction points are. Whether there are capital controls. Whether KYC requirements are excessive or nonexistent.

You have that intelligence. Nobody else does. You are the expert on your community's problems. And if you understand the problem really well, you are in a better position than anyone else on the planet to build the solution.

The paradigm shift is that you don't have to be a developer anymore to build software. AI coding tools like [OpenCode](https://opencode.ai), Claude, Codex -- they have changed everything. I recently gave a [masterclass at Africa Free Routing](https://github.com/pretyflaco/africafreerouting/tree/main/masterclass/202604) where participants went from a blank terminal to a live Lightning donation page in 40 minutes. Zero hosting cost. Five dollars in AI credits, paid via Lightning. Some of those people are now building exchanges and marketplaces.

If you haven't started, start. Get a GitHub account. Try OpenCode. Open your terminal on a Sunday when you have time. The only thing that can happen is you spend a couple of sats on AI credits and nobody uses your app because it sucks. But you will learn enormously. And this is where the value of open source compounds: you don't have to build from scratch. Every puzzle piece exists on GitHub. Fork it, cherry-pick what you need, combine apps from different projects into something that works for your community.

The era where developers sit somewhere and users sit somewhere else and there's no communication between them -- that era is over. People are building their own software now. So should Bitcoiners.

If there's one thing you take away from this: **the barrier to building payment infrastructure has never been lower. The best time to start is now.**

---

## Discussion

Join the conversation:

- [Nostr](https://njump.to/nevent1qqsxlqgz500v29ljcs74pl5lww72lmd3hudyx7wqlwt6cwzvk4963rgpypmhxue69uhhyetvv9ujumn0v3jhyatwdejhyuewdejhgam0wf4j7q3qflac02t5hw6jljk8x7mec22uq37ert8d3y3mpwzcma726g5pz4lsxpqqqqqqzp3j5w9)
- [X / Twitter](https://x.com/i/status/2045279231051956517)
- [Stacker News](https://stacker.news/items/1473492)

---

## License

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

*Kemal -- Istanbul, April 2026*
*kemal@blinkbtc.com*
