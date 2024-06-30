# White Paper 2.0

## Table of Contents

1.  [Trust](#1-trust)
2.  [Overview](#2-overview)
3.  [The Problem](#3-the-problem)
4.  [The Solution](#4-the-solution)
5.  [Benefits](#5-benefits)
6.  [Andromeda Operating System Explained](#6-andromeda-operating-system-explained)
    *   [6.1) UX - The User Experience](#61-ux---the-user-experience)
        *   [6.1.1) The Desktop](#611-the-desktop)
        *   [6.1.2) Object Browser](#612-object-browser)
        *   [6.1.3) Learn](#613-learn)
        *   [6.1.4) App Store](#614-app-store)
        *   [6.1.5) ADO Builder](#615-ado-builder)
        *   [6.1.6) App Builder](#616-app-builder)
        *   [6.1.7) Andromeda.js](#617-andromedajs)
        *   [6.1.8) GraphQL / Indexer](#618-graphql--indexer)
        *   [6.1.9) CLI - The Command Line Interface](#619-cli---the-command-line-interface)
    *   [6.2) aOS - Andromeda Operating System](#62-aos---andromeda-operating-system)
        *   [6.2.1) Andromeda Messaging Protocol (AMP) & Interchain Communications](#621-andromeda-messaging-protocol-amp--interchain-communications)
        *   [6.2.2) ADOs - Andromeda Digital Objects](#622-ados---andromeda-digital-objects)
        *   [6.2.3) ADOP/ALL - ADO Packages & Andromeda Logic Library](#623-adopall---ado-packages--andromeda-logic-library)
        *   [6.2.4) Andromeda Apps](#624-andromeda-apps)
            *   [Authorization](#authorization)
            *   [Authentication](#authentication)
        *   [6.2.5) aOS Kernel](#625-aos-kernel)
        *   [6.2.6) Users & Groups](#626-users--groups)
        *   [6.2.7) Permissions](#627-permissions)
        *   [6.2.8) VFS - Virtual File Systems](#628-vfs---virtual-file-systems)
        *   [6.2.9) aOS Networking](#629-aos-networking)
        *   [6.2.10) aOS User Space](#6210-aos-user-space)
    *   [6.3) Andromeda Chain Technical Stack](#63-andromeda-chain-technical-stack)
7.  [Tokenomics](#7-tokenomics)
    *   [Domains](#domains)
    *   [Network Effects](#network-effects)
    *   [Tokenomic Categories](#tokenomic-categories)
    *   [Utility Value Abstraction Layers](#utility-value-abstraction-layers)
    *   [Tokenomics Summary](#tokenomics-summary)
8.  [Governance](#8-governance)
9.  [Market & Customer Segments](#9-market--customer-segments)
10. [Core Contributors](#10-core-contributors)
11. [Conclusion](#11-conclusion)
12. [Bibliography](#12-bibliography)
13. [Appendix 1 - Tech Tree](#appendix-1---tech-tree)
14. [Appendix 2 - Operating System Comparison - Detail](#appendix-2---operating-system-comparison---detail)
15. [White Paper Legal Disclaimer](#white-paper-legal-disclaimer)

# 1. Trust

Trust within and between societies, trust in business… trust between strangers and in a larger community. Trust is the foundation of human prosperity. The technology described here allows trust to flow throughout the world, imbuing civilization with what Josh Stark calls “hardness<sup>1</sup>” - elevating trust, reliability and legitimacy in human affairs, institutions, commerce, markets, etc..

We hope that our contribution to the advancement of cryptographic trust objects will make as dramatic an impact on society as we clearly envision.

Andromeda is dedicated to the advancement of what we believe is the center of gravity of future societal change for the better: trust.

> <sup>1</sup> Atoms Institutions and Blockchains By Josh Stark - In this brilliant article Josh Stark makes the case that civilization needs hardness in

> ##### “On January 3, 2009, a new trust architecture entered the world with the launch of Bitcoin.”

> – Kevin Werbach August 29, 2021

# 2. Overview

As a community<sup>2</sup>, they share incentivized digital asset participation through rapid business model innovation and deployment that matches the accelerating rate of global change. They can compose solutions to instantly access Web3 infrastructure rails for decentralized and permissionless access to cryptocurrencies, DeFi, computation, storage, payment, marketplace, distribution, application, and other service infrastructure. Andromeda removes the technological barriers to Web3 resources so that business models can be created and tested at global scale in minutes, at no cost.

Andromeda is an operating system for using and building applications on decentralized blockchain infrastructure. It is an entirely new class of software that is the culmination of technical breakthroughs beginning with Bitcoin, followed by Ethereum and then advanced by the Cosmos technical stack - currently used by 3 of 5 of the largest crypto projects<sup>3</sup>. This arc of progress continues with the emergence of modular blockchains and a perfusion of purpose-built blockchains. The inevitable multi-chain future converges upon a new kind of operating system - a missing and critical software layer that manages the complexity of interacting with, and building on, public blockchain infrastructure.

History is being repeated. Early mainframe computers had individually developed programs and applications for each computer. The same thing occurred for PCs and Smartphones. Adoption skyrocketed once an operating system was built that could be shared by everyone to build new applications and create a common user experience. Operating systems have repeatedly unlocked powerful and valuable Network Effects<sup>4</sup> for usage of the hardware, operating system, applications, and users. The multi-chain future needs an operating system for the same reasons.

Andromeda’s network effects produce important new capabilities to decentralized blockchain infrastructure. It enables users, developers, and creators to use and access the aggregated capabilities of multiple blockchain ecosystems. Similarly, they can access all of the users across those ecosystems. The multi-chain distribution, on-chain architecture, and scaling laws introduce a new way to sustainably incentivize and monetize open source software to support explosive growth.

The Andromeda Operating System (“aOS”) is where Web3 starts. It is where developers and creators find revolutionary tools to rapidly build Web3 projects in minutes instead of months; enabling them to re-imagine and re-architect the internet with trust, privacy, and reliable currency. It opens up global capital, global trade, global market access, and emancipates them from the capture of tech giants, shaky institutions, and excess-rent-seeking-intermediaries.

> Andromeda powers business model innovation and deployment  that democratizes value creation for users, builders and digital asset participants.

> <sup>2</sup> Cassatt, Amanda Web3 Marketing A Handbook for the Next Internet Revolution describes the merging of user, builder and investor into

Users can discover the awesome power and capabilities unleashed by public, permissionless infrastructure. With the Andromeda Operating System everyone can access the best blockchains and projects. Developers can compose powerful solutions that integrate across projects and chains, creating seamless single-chain, cross-chain or multi-chain applications. It is where the multi-chain future becomes Easier, Better, Faster.

Users may access a familiar operating system desktop similar to PC, Mac and mobile. Users get easy access to their decentralized apps. They get a familiar file explorer-like experience that enables discovery and organization of the user’s DeFi instruments, NFTs, and other Web3 assets. Users can shop for best-in-class Apps in the App Store and developers can shop for developer tools. User Settings allow selection of their default chain, wallet and other account settings. And they get access to standard apps such as: Fiat On-ramps, Banking, Crypto Vaults, DEX, NFT Marketplace, Automation, Notifications, Storage, and DAOs.

> ##### “The real revolution is the evolution of consciousness.”
>
> – Unknown

Creators and developers get enterprise-class developer tools. These include the Andromeda Development Framework, a powerful no-code and low-code builder, and an expressive and succinct Command Line Interface (the “CLI”). This suite of tools are used to rapidly build multi-chain and cross-chain applications from a library of special smart contracts that are modular and composable. These are called Andromeda Digital Objects (“ADOs”). ADOs are located in the Andromeda Logic Library (the “ALL”) and installed on many blockchains.

> <sup>4</sup> Network Effects <https://www.nfx.com/post/70-percent-value-network-effects>

# 3. The Problem

Users, creators, and developers have no common starting point for a staggering array of blockchains, apps, projects, tools, utilities, and wallets. There is nothing to deliver a unified user experience (UX) across Web3. Every Web3 project stands alone in the UX; either stranded in the mind of the user or lost amongst their browser’s bookmarks. And despite the many Web3 applications and blockchains, users can forget about cross-application or cross-chain integration. It’s a ghost of an idea whose time, apparently, has not yet come. Until now, with Andromeda, making it possible.

## Failure Signals

Developers are forced to build every project as a one-off. Each project employs smart contracts that are unique in all the world, their own special flower. The monolithic smart contract design pattern, employed throughout the world, is an industry-killing catastrophe. It forces programmers to copy paste ad infinitum and then hook up all their code like artisans carefully sewing patterns one stitch at a time. The results speak for themselves: poor audit results, reliability issues, code brittleness, difficulty extending functionality, and absence of integrations to practically anything. ChatGPT and AI will only compound the problems posed by an infinity of unique monolithic smart contracts. The list of problems goes on and on - see the Medium article: Andromeda Macros Theses for more.

Web3 is too difficult. There is a missing layer to make it easy. Global adoption rates of Web3 prove it’s too difficult to use. Venture capitalists have encountered a never ending carousel of projects innovating in a narrowly-banded design space. This has restricted startups to a binary parade of DeFi or NFT projects for several years. These facts are the signposts of weak tooling. And there are many other signs.

The ERC1155 smart contract standard defines something between a fungible and non-fungible token. Conceptually, it has the potential for a vast design space yet it is scarcely deployed. And this is because it’s trapped outside of any useful business models that are supported in Web3. It represents a value accrual and capture problem that no one has solved. It’s too hard, requires too much software, requires new tokenomics, that together, is apparently beyond the kin of the industry to solve. The hurdle is too high and creates a prohibitive entry point. And therefore the design space lies barren.

So far, the multi-chain future has meant transacting some cryptocurrency from one blockchain to the next. This is nice to have but it’s restrictive. It only addresses a narrow set of possibilities offered by endless blockspace and a perfusion of innovative blockchain capabilities emerging throughout the industry. If nothing changes, and nothing new is contrived, the commercialization of this bounty of innovation will never happen. Bridges, routers, and relayers by themselves are limited in the problems they solve. A new layer is required that can powerfully and seamlessly integrate all the blockchain capabilities available today.

The speed of building business solutions on public blockchain infrastructure has been significantly impaired because of the limitations of the underlying blockchain and smart contract platforms. Domain specific languages aren’t up to the job. The observed project durations, for the functionality delivered, stands in marked contrast to Web 2. Another signpost that the tools aren’t good enough yet.

## Failed Models

Web3’s treacherous regulatory standing demands new tooling and services to mitigate the legal vulnerability and regulatory risks of businesses and users. This, most emphatically, does not look like each project individually and singly addressing the problem. Instead, it looks like a set of out-of-the–box services that users and developers can access with the click of a button.

“Code is Law” is an aspiration of the future and a guiding light for how reliable and hardened protocols should be. But In fact, Law is Law, and citizens must abide by it. Web3 has provided no capability for the global community to enjoy the benefits of a public blockchain infrastructure without abandoning their customary legal forms in contract law, property law, copyright law, etc. This creates unresolvable conflicts<sup>5</sup> between the immutability of the blockchain and business conduct under the law. New capabilities are required to address these limitations.

Web3 is built on a foundation of open source development. And for decades a valid business model for Open Source development has not emerged. Developers have relied on corporate tithing to sustain their efforts. The future of civilization cannot rely upon the tithing<sup>6</sup> of profit-driven corporations. Historically, open source has motivated its workforce using positive social affirmation. This was surprisingly successful for decades. However, the advent of GitHub, generational social changes, and demand for software development, have significantly diminished this earlier model of open source software development<sup>7</sup>. Creating a viable, sustainable, and reliable model for open source development is essential to the success of the industry - and probably civilization itself.

Conventional smart contract design typically limits their operation to user-initiated execution. This requires endless hand-holding, off-chain and untrusted triggers to execute whatever methods and logic is contained within a smart contract. The potential of the ‘actor model’ is not realized in these implementations and impedes the entire range of possibilities conferred by autonomous agents. The future requires a new layer to handle this.

> <sup>5</sup> Edmund Schuster’s brilliant and scathing white paper, Cloud Crypto Land, describes the conflict between blockchain technology and law. Regrettably, Schuster’s claims had to be made without the benefits provided by a maturing Web3 and the imminent benefits of aOS <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3476678>

## Insufficient Tooling

The tooling available is not good enough to build powerful applications. And worse, the available tools reject the very foundation of Web3 by using centralized API providers. The world awaits a set of tools that will enable compelling applications to onboard the next billion users. Full exploitation of Web3’s promise requires a powerful set of tools.

History repeats, and these problems of information technology have been seen many times. The crisis of slow adoption and burdensome application development happened with mainframe computers, PCs, Browsers, and Mobile Apps. The solution of course, described in the next section, is a new layer.

# 4. The Solution

It is possible because of the recent and concurrent technical achievements of the Cosmos Ecosystem, Tendermint, CosmWasm, the Inter-blockchain Communication Protocol (“IBC”) and Andromeda’s breakthroughs in modular composable smart contract architecture and application messaging protocol. It has emerged at the earliest possible moment in the history of this technical stack.

aOS lives natively on-chain; no APIs, no intermediaries. aOS uniquely solves many important limitations present in Web3 today. These are explained in more detail in the Medium article Andromeda Macro Theses<sup>8</sup>.

aOS supports blockchains running CosmWasm smart contract infrastructure. This means Cosmos Ecosystem chains, Solana, Terra, and some Avalanche L2s can access the full power of the aOS. Multi-currency support is gained via the many omnichains and bridges (see Axelar) that connect to Ethereum, Bitcoin, Polygon, Polkadot, and others.

Users get a unified experience. Creators and developers get tooling that lets them rapidly prototype, build, and launch highly functional decentralized apps. The Andromeda Development Framework lets developers use and build modular smart contracts instead of monolithic smart contracts.

aOS is a comprehensive response to the problems identified above.

This new layer simplifies business model creation so that creators and developers are guided by objectives, business-logic, and requirements. They are less constrained by the technical limitations of their environment. They get customizable, functional, and user-configurable digital objects. Code use, and re-use, across the entire ecosystem stabilizes and standardizes on modular code components. Over time, specific functions are standardized, best practices created, and specific industries converge on hardened protocol services. This delivers reduced engineering requirements, diminished smart contract failure risks, and minimizes auditing time. Developers use a library of certified and signed smart contracts to speed up auditing, improve trust, and build confidence.

Creators and developers compose their own Web3 projects with access to chain-native currencies, DeFi assets, yield, and can seamlessly access currencies, a variety of token standards, or integrate to other projects, on a single chain or across the multi-chain ecosystem.

aOS is available to all projects, users, and developers wherever it is installed. It operates natively on any chain with CosmWasm smart contract support. Existing projects can wrap their smart contracts with wrapper contracts from the aOS library to add to or extend functionality. Solutions using the tools native to the protocol allows for the development of applications limited only by the boundaries of the innovative mind.

aOS is the layer between public blockchain infrastructure and traditional organizations. It supports activities like legal contracts, certified communications, file storage, multi-step structured transactions, and process workflows. It transcends the limitations of monolithic blockchain application design and offers unifying multi-chain capabilities with a common protocol and standard.

aOS is engineered to deploy and operate independently on a single chain while also operating, and interoperating, across thousands of blockchains, and all of the projects on those blockchains. This creates a network topology that supports exponential scaling as defined by Reed’s Law<sup>9</sup>. The result is exponential and aggregated access to users, projects, capabilities, and blockchains across multiple ecosystems.

aOS delivers tools to implement an entirely new model of application development or transition from an old model to new one. Andromeda delivers a fully generalized application development framework.

The powerful combination of the Andromeda blockchain and aOS serve as your Web3 innovation playground, making what was once impossible possible. This is where new aOS capabilities are explored, developed, and studied. It launches with unique capabilities explained below in the section Andromeda Operating System. However, it is not essential to aOS operation on any other blockchain. Nor is it the sole source of utilitly value, described in the Tokenomics section.

# 5. Benefits

It simplifies the overall Web3 experience by hiding the complexity and making it easy to start, easy to use and easy to build. A user’s applications, intent, and purpose organize the user experience. Users no longer need to continually navigate complexity.

For developers and creators, aOS is the user interface between the blockchain and the projects and protocols that run on the blockchain; difficult blockchain resource interactions are abstracted away so they can be easily managed and seamless to the user. This enables:

aOS confers many benefits whether you are a user, creator or developer. Usability is preeminent.

Exponential scaling becomes possible because of the aOS network effects driven by incentivized open source development.

1.  Business model creation and deployment with aligned with the accelerating rate of global change
2.  Capacity to build and Test business models at Global Scale in minutes at no cost
3.  De-risking business and fraud reduction
4.  Instant access to infrastructure rails - permissionless access to compute, storage, payment, marketplace, distribution, application, and other service infrastructure
5.  Tokenization and Digital Ownership of assets
6.  Global market access
7.  Instant community access
8.  Eliminate intermediaries
9.  Variable costs of operation

## Benefits of an Operating System

*   **Ease of use:** aOS provides a user-friendly interface that makes it easy for users to interact with blockchains, access and run Apps. It also includes various features such as an automation task manager, an assets manager like a file explorer, and system settings that allow users to control and customize their Web3 experience.
*   **Multi-Chain & Cross-Chain Support:** aOS is designed to operate on any CosmWasm blockchain and enable it to connect to any other blockchain. aOS includes a cross-chain messaging protocol and uses IBC for connecting blockchains to other blockchains. This enables standard, reliable communication between them.
*   **Compatibility:** aOS enables different blockchains and projects to work together by providing a standard set of interfaces and protocols. This makes it easier to connect and integrate different blockchains and their projects’ capabilities from the same App or aOS Desktop and Tooling.
*   **Security:** aOS includes various security features that benefit users and developers. These include signed smart contract interoperation and a user credential system that simplifies multi-chain usage.
*   **Performance:** aOS enables asynchronous integration of many blockchains and their projects, allowing developers to optimize the performance of Apps. This means Apps can improve the overall speed and capabilities by using multiple blockchains - without being trapped by the capabilities of any single monolithic blockchain.
*   **Asset Management:** aOS provides a file explorer and virtual file system for managing and storing Web3 assets like DeFi instruments, NFTs and Real World Assets (“RWAs”).
*   **System Administration:** Andromeda has the tools and utilities for managing and maintaining a network of thousands of aOS instances on as many blockchains, including task scheduling, performance monitoring, and system updates or upgrades.
*   **Off-chain Integration:** aOS provides special smart contracts for connecting to Oracles, enterprise applications, and services.

## Beneficial Features

Selected features of Andromeda’s aOS, tools and utilities:

1.  Trust is embedded into Digital Objects;
2.  Open Source software development can be monetized - it is now economically viable;
3.  Access to the very best public blockchains in the world with industry-optimized and functionally-optimized chains;
4.  Standardized off-the-shelf application primitives;
5.  Expanded and undiscovered (new) design space;
6.  Rapid prototyping and innovation becomes possible;
7.  User tools to bridge traditional and decentralized business architectures;
8.  Rapid-onboarding of traditional businesses;
9.  Fully armed business payload off-the-shelf;
10. Pre-audited and tested modular components;
11. Expanded off-chain functionality; and
12. Easily create autonomous agents.

The value proposition of Web3 is multi-dimensional. Part of the value comes from integration of money with everything else.

## Architectural Benefits

The aOS is built using a decentralized on-chain smart contract library. Unlike other tools that use centralized API’s and centralized application providers, aOS runs natively on-chain. This confers many benefits unmatched by any other architecture. Consider the following benefits:

1.  Control - no single point of failure;
2.  Security - better trust assumptions than L2s - relies on L1 security guarantees;
3.  Scaling - unlimited blockspace;
4.  No race conditions;
5.  No Licensing fee - all variable costs;
6.  Simpler and faster to build;
7.  More Composable;
8.  More Extensible;
9.  More Resilient;
10. No hidden dependencies;
11. No out of state conditions;
12. Full control/No vendor lock-in or capture;
13. Flexible solution design;
14. Complex enmeshed; and
15. Larger design space.

# 6. Andromeda Operating System Explained

It is designed to scale across thousands of blockchains. The sections below describe the aOS 1) conceptually, 2) through the UX and 3) the components of the technical architecture and their benefits.

aOS can be explained using a Simple Comparison to Conventional operating systems - see the diagram below. Operating systems are typically composed of a Kernel and a User Space. The Kernel handles hardware resources and the User Space handles user inputs and access to Kernel resources. In the diagram below, on the left-hand side is a Conventional OS. In conventional computer operating systems the kernel manages and allocates resources such as memory, processing power, and storage to different programs and processes running on the computer. This ensures that each program has access to the resources it needs to function properly. On the right-hand side is a Decentralized OS like aOS. In this case the kernel manages access to blockchains.

> Andromeda is an operating system plus a suite of tools and utilities.

[Diagram: Description in progress]

The User Space is where the user interface and application development occur. This is where shared interfaces, standards, and controls create a common user and developer experience for all users of the operating system. These services are very similar for computers or blockchains. Except a decentralized operating system for public blockchain infrastructure hasn’t existed until the aOS. The User Space is where the user experience is created.

The aOS is engineered to operate on multiple chains and across chains. It is best understood as an interoperating network of aOS instances or nodes. In the diagram below, from the top down, Users / Creators / Devs interact with a browser-based Frontend / UX. The browser connects to multiple instances of the aOS. Each aOS instance has access to applications (Protocols) and its respective blockchain’s resources. The aOS communicates between Protocols and blockchains using two protocols IBC and AMP explained below. The effect is to create a unified experience for Users / Creators / Developers.

[Diagram: Description in progress]

In the next diagram found below, a different view of the same aOS architecture. This diagram shows how the aOS is installed as a library of smart contracts called the ALL. The ALL contains ADOs that are composable into Apps. These ADOs can be configured to communicate from one blockchain to the next using Andromeda Messaging Protocol (“AMP”) and IBC protocols - explained in more detail in the aOS section below. Conceptually, this architecture unifies all of the blockchains with a common user interface and a common blockchain to blockchain interface.

[Diagram: Description in progress]

This diagram below shows 6 blockchains each with the aOS operating on-chain. Any single instance of the aOS can communicate to another to access an application’s contracts on that chain. In this way, an application can be created on one chain that uses resources from another chain. 

[Diagram: Description in progress]

The network effects for any single chain running aOS is profound. In the diagram below ‘Your Chain’ has aOS installed which enables all of the other chains to access ‘Your Chain’s’ unique resources, applications, and services. This means applications on other chains can be rapidly composed to ‘Your Chain’s’ capabilities without creating bridges or individual integrations across all of the chains.

[Diagram: Description in progress]

The overall network effects of aOS distribution results in a user’s experience with applications that span blockchains in multiple ecosystems. The aOS desktop has a standard load of applications sourced throughout the ecosystem. Developers can rapidly build applications that integrate capabilities from many different blockchains.

[Diagram: Description in progress]

## 6.1) UX - The User Experience

The user experience is delivered via web browser. All information displayed in the browser is dynamically constructed from on-chain data. This includes configurable smart contracts (ADOs), attributes, help, and modal information. This has several effects. Backend developers (smart contract engineers) get to deploy contracts (ADOs) that build front-ends dynamically. This in turn means the aOS and the UX can rapidly expand functionality with the addition of each ADO.

### 6.1.1) The Desktop

The Desktop is where a user, creator, or developer’s Web3 experience begins. Here is where they access My Apps, My Assets, the App Store, the App Builder, ADO Builder, Andromeda Chain, and the Help or Learn sections. Comprehensive step-by-step guides introduce new users to Web3 principles and onboard them to aOS. Default applications are available so users have the most popular apps ready to go. Fiat to cryptocurrency on-ramp and off-ramp capabilities are readily available to make it fast and easy.

[Diagram: Description in progress]

### 6.1.2) Object Browser

The Object Browser is an easy to use and intuitive digital asset explorer; much like File Explorers found on a PC or Mac operating system. This is where a user can access their on-chain assets whether those are NFTs, DeFi instruments, applications, or ADOs. In the example below the top right-hand drop-down menu displays the various chains where a user’s assets can be found. Assets can be searched, sorted, and discovered using many different attributes.

[Diagram: Description in progress]

### 6.1.3) Learn

The Learn section has a comprehensive set of documents to onboard users, creators, and developers. This includes a Conceptual Breakdown with boxes and arrows, The Basics, How-To-Guides, videos and detailed developer documentation.

[Diagram: Description in progress]

### 6.1.4) App Store

The App Store has decentralized applications that are ready for free installation or purchase. Developers and creators can now monetize their efforts of contributing to open-source projects by listing their apps for sale in the App Store.

[Diagram: Description in progress]

### 6.1.5) ADO Builder

Developers can access the ADO Builder. This is where ADOs are configured and built. ADOs are the modular and composable smart contracts that power the aOS. The ADO Builder is a menu-driven no-code builder that allows you to configure and customize smart contracts used in the creation of apps. ADOs are described in more detail below.

[Diagram: Description in progress]

### 6.1.6) App Builder

The App Builder is where ADOs are composed into complex single or multi-chain applications. This is quickly accomplished with a drag-and-drop functionality. In the screenshot below, the left-hand panel has an inventory of project templates that can be moved onto the canvas. This example features an application using three (3) separate zones (Andromeda/Secret/Terra2 blockchains) and nine (9) different ADOs. Each ADO can be configured using the ADO Builder accessed directly from the canvas. Adding a new blockchain to create a separate zone is accomplished with the simple click of a button. The mini-window in the lower right corner provides a zoomed-out view of the overall canvas - very helpful when building highly complex multi-chain and multi-ADO applications.

[Diagram: Description in progress]

The App builder gives you the power to create a vast array of cutting-edge applications that can leverage the full potential of the multi-chain ecosystem. From building complex workflows, to tokenized real-world assets, supply chain management capabilities, NFTs, agent-based financial transactions to portfolio balancing and management - the possibilities truly are limitless. With the App builder, you can unleash your creativity and transform your ideas into powerful, fully functional applications that can drive innovation and change across multiple industries.

The App Builder can publish applications directly to the blockchain(s) or it can be used to rapidly prototype applications or business models. Either way, complex systems of ADOs can be modeled and exported for use in the CLI or a developer’s IDE. Similarly, developers can import their Andromeda application code into the App Builder. They can do the same thing with applications purchased on the App Store. For example, the store contains Apps for crowd sale of real world assets tokenized with NFTs, real world assets tokenized with fungible tokens, NFTs for digital goods and more.

### 6.1.7) Andromeda.js

The Andromeda Javascript Library serves as the off-chain logic that maps user intentions to backend execution. It indexes all objects, relationships, permissions and functionality. This library can be used with the CLI, IOT devices, web interface, and can even be plugged into larger systems commonly found in enterprise environments.

### 6.1.8) GraphQL / Indexer

Andromeda uses GraphQL and an Indexer to rapidly read and retrieve information from blockchains. The Indexer tracks events on the chain and provides convenience and scalability.

### 6.1.9) CLI - The Command Line Interface

The CLI is succinct and expressive. It supports multi-chain interaction. It is built to work with any of the chains where Andromeda is deployed. This removes the need for developers to learn how to deploy contracts on each of the chains. Wallets can be managed in the CLI.

The CLI also allows developers to interact with all of the ADOs found on any chain. It can create, manage, or interact with new ones, read data from, update, migrate, change ownership and permissions of ADOs. CLI input and output can be imported to an IDE, Andromeda’s App Builder or ADO Builder.

## 6.2) aOS - Andromeda Operating System

The aOS is a next generation layer that abstracts common operations for decentralized state machines. aOS is comprised of subsystems that simplify interactions with different blockchain resources: networking (IBC), a virtual filesystem (VFS), User Accounts, Digital Object support and a more robust and complex messaging system for contract interactions. Each instance is loosely coupled to other chains with aOS via messaging and bridging/relaying protocols.

aOS is installed and instantiated on each compatible blockchain as a system of smart contracts. These contracts create the environment for users to interact with. The suite of contracts that make up the aOS Kernel communicate through the Andromeda Messaging Protocol (AMP).

The design principles behind aOS have been heavily influenced by the design patterns in the UNIX & Linux operating systems. Instead of hard drive sectors and files, the aOS uses hashed addresses and smart contracts. Like Unix, services and commands are atomic, interoperable, finely abstracted and loosely coupled.

### 6.2.1) Andromeda Messaging Protocol (AMP) & Interchain Communications

The AMP brings simplicity to using a single protocol to communicate across blockchains. Instead of having to set up dozens of channels between chains for services to communicate one to one, AMP wraps these messages so they can be routed much more efficiently.

The current architecture of IBC is not easily scalable because a unique channel is required between any two contracts on different chains. AMP solves this by creating a single entry point into the aOS kernel networking layer on each chain. IBC is used to transport AMP messages. Furthermore, AMP handles metering of Andromeda Network Fees, fee aggregation for different abstraction layers - see Tokenomics section.

AMP is the ADO messaging protocol. It is a set of rules and conventions that govern the exchange of messages between ADOs. AMP handles communications between ADOs on the same chain and across chains. There are several benefits to using a messaging protocol:

*   **Interoperability:** AMP allows ADOs to communicate with each other by establishing a common set of rules and conventions for exchanging messages. This enables interoperability between contracts on any project on any integrated chain.

*   **Reliability:** AMP includes error detection and correction mechanisms to ensure the reliability of message exchange - increasing the overall security and resilience of the system. It helps to reduce the likelihood of errors or lost messages, improving the overall reliability of communication.

*   **Scalability:** AMP enables large scale communications of ADOs - essential to unlocking the overall scalability aOS to thousands of blockchains

*   **Security:** AMP handles encrypted and authenticated messages to protect against unauthorized access, spoofing, or tampering with messages.

*   **Ease of use:** AMP is a simple and straightforward way for developers to create and introduce new ADOs that communicate with each other. It also makes it easier to wrap non-ADO smart contracts so they can interact natively within the aOS.

The AMP specification requires:

1.  The user and group must be specified and authorized.
2.  One or more targets must be specified. Either the VFS path or the Contract Address or CodeID, but not both.
3.  The “fee source” must be specified, even if it’s the originating wallet.
4.  Limits can be set to ensure no runaway costs inadvertently happen.
5.  Multiple Execution tasks can be assigned and should be executed in order.
6.  Contract Execution Fees (Gas) are handled at the L1 level and are not the aOS’s responsibility.

> A key feature of crypto - an open source decentralized computing platform - is that projects can act as a multiplier when their composable components are reused, recycled, and adapted by others. Composability is to software as compounding interest is to finance: an exponential force - Chris Dixon, Managing Partner at a16z

### 6.2.2) ADOs - Andromeda Digital Objects

ADOs are a breakthrough in modular, composable smart-contract architecture. They are the foundation of aOS. aOS discards the monolithic smart-contract architecture widely used throughout the world. Instead, ADOs are designed to snap together like legos so they can be composed into complex apps. Each ADO is atomic, with the simplest functionality possible, and with simple inputs and simple outputs. In this way ADOs can be assembled to support complex and capable apps.

Typical smart contract design uses a key-set acting directly with another. ADOs discard this usual key-set to protocol hard-coupling. Instead of a key-set acting directly with a service, an intermediate object is inserted. The user (key set) owns an object, and the object acts as a proxy to the service. This change in architecture accomplishes many new capabilities never before seen in Web3.

These objects utilize the ERC/CW-721 standard to assign ownership and manage transferability. Each object in the system is defined at a human readable address in the VFS (virtual filesystem). In this way, an ADO will begin to be recognized as a file, similar to modern day operating systems. To go further, instead of having financial positions in a service and relying on bespoke indexers to keep track of things, ADOs allow for users to track their assets in a central place, on-chain. 

### Examples of ADOs

* Address List
* Auction
   - English Auction
   - Vickrey Auction
* App
* Crowdfund
* CW20
* CW20-Staking
* CW721
* CW721-Bids
* CW721 Staking
* CW721 Timelock
* Gumball/Randomizer
* Lockdrop
* Primitive - uInt128
* Primitive - Decimal
* Primitive - Coin
* Primitive - Bool
* Primitive - Vector
* Primitive - Binary
* Marketplace
* Merkle Airdrop
* Rates
* Rate Limiting Withdrawals
* Receipt
* Splitter
* TimeLock
* Vault
* Vesting
* Weighted Distribution Splitter
* Wrapped CW721
* IBC
    - ICS 721
    - ICS 20
* Automation
    - Oracle
    - Storage
    - Task Balancer
    - Condition
    - Evaluation
    - Execute
* Exchange ADO
* Swapper

### ADO Examples

A Collateralized Debt Position (CDP) can be managed through a lending platform ADO. This ADO exists as a “file” in the VFS, such as “/home/username/loan”. It has metadata associated with it, so it is easily identified and managed.

Another ADO is a Splitter that is instructed to split funds sent to it via any number of user configurable methods (weighted, fixed percentage, etc.). This ADO can split and forward funds to other ADOs via AMP. 

The Automated Market Maker (“AMM”) Swap ADO is used to simply swap one asset for another. The ADO can be configured to be ‘one-way’ where it will only accept one asset and exchange it for another, or ‘two-way’ where it will simply swap one for the other regardless. Slippage tolerance can also be set to prevent substantial fluctuation in price changes.

### ADOs Working Together

ADOs communicate with other ADOs through AMP. This allows for common rule adherence and enforcement. This common layer between ADOs allows for any ADO to communicate with any other ADO, without the need for custom adaptors. AMP handles all of the inputs and outputs similar to how standard in and standard out work.

Creating a Logic ADO that compares the aforementioned CDP’s ratio to a set number, allows for on-chain decision making when funds are moved into the system. 

[Diagram: Description in progress - Diagram 1]

For example:

Every Monday a user schedules a transfer of fiat via Kado. The funds are sent to the logic ADO mentioned prior. If 175% is the targeted Loan to Value ratio (“LTV”), the new funds will be used to top up the collateral to this amount, then whatever is left over will go to the Splitter ADO mentioned above. The Splitter could be configured to send the cryptocurrency to three different AMM Swap ADOs to build positions based on the Splitter’s configured ratio.

### 6.2.3) ADOP/ALL - ADO Packages & Andromeda Logic Library

ADOs are organized on-chain as a library called ALL. The ALL is organized like typical development libraries with version control, unique identifiers, and metadata for secure retrieval, usage, maintenance and deprecation.

ADOs are specified as Andromeda Digital Object Packages (ADOPs). These are like NPM or other widely used package management schemes. This ensures strictly enforced package standards according to a comprehensive package specification. This supports rapid scaling of the library through community submissions into a production workflow. This workflow supports testing, auditing, document validation, library curation, tokenomics, panel designs, and all required metadata. 

### 6.2.4) Andromeda Apps 

A Collection of ADOs defines an Andromeda App. Applications can be a simple off-the-shelf pattern as well as incredibly elaborate with dozens upon dozens of ADOs. In the example below, users, creators, and developers employ aOS to utilize an application with multiple ADOs interoperating across three different blockchains. This creates a vast new design space for decentralized applications.

[Diagram: Description in progress - Diagram 2]

The Andromeda Application Framework (AAF) specifies ADOs on various chains that have an address and code\_id that is unique. These two values are mapped to a location in the VFS. 

Example: juno1unclk8rny…2gamhad0usxl7jnd:122 -> /home/username/my_ado

[Diagram: Description in progress - Diagram 3]

#### Authorization

Each ADO in the system has globally recognized permissions enforced by the aOS kernel. These permissions look much like they do in a traditional Unix/Linux system using a numeric system similar to chmod<sup>10</sup>. 

#### Authentication 

ADOs need to be able to trust the message they receive from the kernel. If an AMP packet is sent to an ADO, the data being passed can be trusted to be correct. This is possible because the AMP Contract is the only contract that’s allowed to communicate with the ADO through Andromeda Compliant Interfaces (“ACI”). Messages cannot be spoofed. 

[Diagram: Description in progress - Diagram 4]

Messages coming from an ADO back to AMP are screened for validity and integrity. Whether it’s an ADO, regular Wallet, or Andromeda User Account, all messages are screened or verified upon entry to the Kernel. 

For clarity, ADOs are prohibited from communicating directly between each other through AMP messages. The concept behind AMP is that it is a managed, trusted and closed-ended protocol. 

### 6.2.5) aOS Kernel 

The aOS Kernel manages the connections to the ADOP/ALL, VFS, Users/Groups, Permissions, Networking, and Economics as seen below. 

[Diagram: Description in progress - Diagram 5]

### 6.2.6) Users & Groups 

Users and Groups are an abstraction away from simple pub/private key systems currently in use. There are many, many issues with having all assets/positions/etc being linked to a single key. This poses a single point of failure. It’s also extremely unsophisticated. Being able to attach metadata to a user, extensible functionality around this user concept is vital to a robust and complex operating system.

### 6.2.7) Permissions

Permissions are managed similar to the unix file system<sup>11</sup>. This system has not been developed yet and has been intentionally left short. It will be updated as the design and build out progress. 

### 6.2.8) VFS - Virtual File Systems

The aOS VFS is responsible for creating a singular and hierarchical namespace per chain that allows for users to easily reference objects within the system. This is similar to modern operating systems. It is not necessary to know the inode or sector where a file or data resides, it is only necessary to use the file system path. 

The benefits of the VFS: 

* **Abstraction:** It provides an abstraction layer between the operating system and the underlying file systems, allowing the operating system to interact with different file systems in a consistent way, regardless of their underlying structure or format.

* **Portability:** It allows the operating system to access resources across blockchains. 

* **Compatibility:** It allows the operating system to read and write files differently without the need for additional software or implementation overhead.

* **Flexibility:** It enables the creation of virtual file systems that can be encrypted, or assets in a compressed or encrypted format, or to create snapshots of the file system/digital assets/digital objects at a specific point in time.

* **Security:** It can be used to provide a secure file system, by providing access controls, encryption and integrity checks.

The aOS implementation of a virtual file system is setup as a Universal Resource Identifier (URI<sup>12</sup>). It is a string of characters that identify resources. It is implemented in the form: 

`[network protocol]://[chainname]/path/to/resource`

As an example: 

`ibc://chainname/path/to/object`

If the owner of an ADO requires an auth then path is specified: 

`ibc://juno/home/superphly/ado1` where superphly is a user

There are several benefits to this scheme: 

1. The URI provide a unique and persistent way to identify resources, so that even if the location or name of the resource changes, the URI will still point to it. 

2. The URI allows for easy sharing and linking of resources across different blockchains and Apps.

3. The URI enables the creation of more meaningful and human-readable URLs.

4. URIs can be used to identify both online and offline resources, making them a versatile means of identification.

### 6.2.9) aOS Networking

Wide adoption of technologies like IBC means there is now a very large constellation of L1 chains communicating. Consequently, it is now trivial to communicate between chains using IBC channels. AMP uses these channels and acts as the communication backbone of the aOS. IBC simply passes AMP messages from chain to chain. This is accomplished by referencing a remote chain and object in the following form and the OS handles the routing: 

`ibc://injective/home/superphly/my_ado`

Other protocols can be used such as Axelar or other protocols in the future.

### Optimization 

Message optimization is accomplished by speeding up initial messages by using lookups off-chain for the initial messages. These sort of shortcuts are screened for validity. For instance, instead of sending in the VFS path and incurring the lookup cost, they can just send in the address + code_id directly. ADOs can either store the address + code_id of an ADO, or they can store the path if they require better readability or more flexibility (the referenced ADO can be swapped out later). 

The same thing can be done for user IDs. “superphly” can be specified or just use the ID, which bypasses the need to do a username lookup. GraphQL + Utilities are helpful in managing these scenarios.

### Backwards Compatibility

Non-Andromeda contracts can interact with aOS using a proxy/wrapper contract. There are ADOs that respond to normal calls and then “wraps” them into AMP messages. These adhere to a clear separation of concerns.

### 6.2.10) aOS User Space 

Operating Systems use the term “user space” to describe the part of the system where users and programs, such as applications and utilities, run. These processes and resources are quarantined to prevent affecting other users, giving users a nice sandbox to play in.

User space programs have a lower level of privilege than kernel space programs, meaning that they have more limited access to system resources and are more restricted in their actions. User space programs do not have direct access to the hardware or to other kernel-level resources and must rely on system calls to request services from the kernel, which then performs the requested action on their behalf.

In general, user space is less privileged and less sensitive than kernel space. This separation of privilege helps to enhance the security and stability of the system by limiting the damage that can be caused by a malfunctioning or malicious user space program. 

Examples of user space programs for aOS include decentralized applications, financial assets, collectables, scripts and other resources owned by users.

## 6.3) Andromeda Chain Technical Stack

The Andromeda Technical Stack encompasses aOS and the Andromeda Blockchain. It includes the following:

* Tendermint/Cosmos SDK
    - GoLang
* Inter-Blockchain Communication (IBC) 
    - Go-IBC
* Rust & CosmWasm
    - Kernel
        ° Networking
        ° Economics
        ° Users & Groups
        ° VFS
* Chain Indexing
    - Block Explorer
    - Object Explorer
    - GraphQL
* JavaScript Library
* Multiple Wallets
* DApp Frontend 

> ##### “The blockchain looks purely technical but, again like the internet, it is sociotechnical in nature.”
>
> –Werbach

# 7. Tokenomics 

The tokenomic models described below are designed for their utility to power the Andromeda Operating System (the aOS), the Andromeda Blockchain, and those blockchains where aOS is installed. The multi-chain distribution of aOS results in historically unique tokenomic models that capture and index value across blockchains and their ecosystems.  

aOS’ unique network effects produce important new capabilities for decentralized blockchain infrastructure. It enables users, developers, and creators to use, access, integrate and aggregate the capabilities of multiple blockchain ecosystems. Similarly, they can access all of the users across those ecosystems. The multi-chain distribution, on-chain architecture, and scaling laws introduce a new way to sustainably incentivize and monetize open source software to support explosive growth.

A full treatment of Andromeda Tokenomics can be found in the Andromeda Tokenomics White Paper. Below is an introduction to the key Andromeda Tokenomic Concepts.  

### Domains

ANDR is a token originated on the Andromeda Blockchain. The token is used in two domains 1) it secures the Andromeda Blockchain and 2) it powers the aOS. The demand for ANDR scales exponentially across many blockchains and ecosystems because of the aOS. Most of the anticipated utility value of ANDR is a function of the wide deployment and usage of the aOS on many different blockchains. 

> Andromeda is powered by the ANDR token.

The Andromeda Blockchain is not essential to the deployment and use of the aOS across blockchains. However, it is vital to the ongoing innovation, automation, and other unique capabilities the Andromeda Blockchain is bringing to market.

### Network Effects 

Andromeda’s capability to create ecosystem wide network effects are the result of the deployed aOS topology. It is fundamental to understanding the scope and nature of Andromeda’s tokenomic models. A typical blockchain creates utility value based on the unit economics per user. Andromeda’s operating system creates value and provides more abundant opportunities to expand and extend value than a single project or blockchain. This is possible because it radically expands the application design space with functionality across many chains.  

aOS utility value increases as an exponential of users across many blockchain.

Sarnoff’s Law describes a single project’s utility value potential as it scales in proportion with the number of users.  Metcalfe’s Law or Reed’s Law, in the diagram below, describes the potential utility value driven by network scaling properties of aOS in the multi-chain and multi-ecosystem future. 

[Diagram: Description in progress - Diagram 6] 

ANDR Value scales as a function of Metcalfe’s Law V=n<sup>2</sup> or Reed’s Law V=2<sup>n</sup> where ‘n’ is the number of users on all the blockchains using aOS. After years of study, from multiple recognized experts (entrepreneurs with unicorn exits), NFX has become the business standard for Network Effects thinking, investing, and incubation. NFX teaches that once critical mass is achieved (enough users) the value of the network exceeds the value of the product. Metcalfe defined it as Value = n<sup>2</sup>.  

The multi-chain topology of aOS means tokenomics can be powered using multiple cryptocurrencies across many blockchains. The effect is that ANDR indexes value across ecosystems with a diversified portfolio of cryptocurrencies. As a simple example, consider a single multi-chain application operating on blockchains A and B. When the Andromeda Network Fees are collected on each chain they can be paid in either ANDR or the chain-native token. So this simple application can create utility value with ANDR, Token A or Token B. In this way, aOS creates increased demand for any blockchain’s token where aOS is installed.

### Tokenomic Categories

The Andromeda aOS and blockchain are engineered to support many different tokenomic models concurrently. This confers significant benefits to ANDR. Andromeda has retained expert advice to analyze and model these different options.

Andromeda’s different tokenomic models are organized into five categories:

1. Utility Capture
2. Total Value Locked (TVL)
3. Wealth Preservation
4. Governance
5. Modular Tokenomics

ANDR is used in both domains: aOS and the Andromeda Blockchain. Both domains benefit from multiple tokenomic model categories. They confer maximum flexibility and improve resilience. 

For example, aOS operates on many different blockchains and therefore if any single chain fails the impact to the overall value of ANDR is limited to that single chain. Thus mitigating the risks to ANDR of any single-chain failure. Similarly, because ANDR is deployed across many tokenomic models it is less susceptible to the failure of any single tokenomic model. Andromeda uses multiple abstraction layers to create even more flexibility for utility value - both for the protocol and for developers building on the protocol. 

### Utility Value Abstraction Layers

Utility Value Abstraction Layers conceptualize and define where utility value is created in each domain. aOS is engineered to support Tokenomic Models that can capture, meter, aggregate and store value at different layers. This is a powerful innovation that unlocks new commercial possibilities for ‘Making Web3 Open Source Software Investable and Sustainable’ - discussed in the Andromeda Tokenomics White Paper. It also helps Web3 solutions align with the customary payment arrangements used by enterprises such as subscription models, application bundlings, and other desirable variable usage schemes. Importantly, it enables communities, consortia, trade groups and collectivities to participate in Collaborative Finance (CoFi) arrangements for automatic debt obligation clearing and other high-yield and highly-efficient capital allocation strategies.

[Diagram: Description in progress - Diagram 7] 

### Tokenomics Summary 

ANDR, aOS and the Andromeda Blockchain introduce entirely new tokenomic models and scaling effects for unprecedented utility value for industry. This utility value is denominated in the ANDR token and many different cryptocurrencies. The effect is to index the utility value across all of the ecosystems where aOS is deployed. Furthermore, the utility value scales exponentially with Network Effects as a function of the number of blockchains where the aOS is deployed. The aOS unlocks a vast application design space to drive rapid user growth. ANDR represents a diversified portfolio of blockchains’ utility value. 

There are many benefits from multiple tokenomic models. Unlike most blockchains and crypto projects worldwide, Andromeda’s multi-tokenomic model eliminates the risk of any single tokenomic model failure. The aOS is more resilient and ANDR carries lower risks from those sorts of single model failures. Users and enterprises can choose to operate aOS on chains that meet their needs and thereby enjoy user-selectable risks. The overall aOS topology reduces or mitigates single-chain failure risk for ANDR. 

These different tokenomic models presented here will not be implemented concurrently. They will be implemented in phases. Some models, or modifications, may or may not be implemented at all based on ANDR stakeholder requirements and ongoing analysis and tokenomic design.  

> Decentralized public infrastructure built with open source software is the foundation upon which to build trusted institutions and human prosperity. Supporting economically viable open source software is humanity’s greatest defense against the encroachment of governments, business, malicious agents and AI on human rights.

# 8. Governance

Andromeda DAO is an organization dedicated to building and scaling the open-source aOS and the Andromeda Blockchain. The DAO establishes operating system and blockchain standards and frameworks to promote and support universal adoption of trustless, decentralized public operating systems and blockchain infrastructure.

Because Andromeda Protocol has many economic constituents, and because it operates across the Cosmos and other ecosystems, optimizing the total value creation is a coordination game<sup>13</sup>. This means there are many different ways to govern and direct the ongoing development of the platform. There are many different, and sometimes competing, objectives between constituents.

> Governance of the Andromeda Protocol is conducted by a Distributed Autonomous Organization. 

The Core Contributors believe proper governance and protocol design are constructed for an infinite game<sup>14</sup>. This means governance should be organized to represent all of the constituents. It means governance is flexible, changeable, and antifragile. The intention of governance is to fully represent constituents of the Andromeda Protocol and to achieve the fullest expression and realization of their objectives. 

The expectation is that Governance decentralization will increase over time. Governance is organized according to Minimum Decentralized Units. This design gives the DAO maximum flexibility to exercise more or less decentralized control over time. Initially, the DAO will be simply divided into two domains: Andromeda Blockchain and aOS Minimum Decentralized Units<sup>15</sup> (MDUs).

1. Chain - Maintenance, DevOps, Innovation, Emergency
2. aOS - Maintenance, DevOps, Innovation, Emergency

The MDUs could evolve over time to encompass:

1. UX/Front End - Maintenance, DevOps, Innovation, Emergency
2. Tokenomics
3. Organization & Compensation
4. ADO/App Audit Committee 
5. Organization Audit Committee
6. Compensation Committee
7. Group Strategy 
8. Regulatory support
9. Legal support
10. Community Management
11. Communications & Marketing

# 9. Market & Customer Segments

aOS is a new platform layer with a vast generalized application development design space. Like Microsoft and Apple’s operating systems, there are many industries and applications where the aOS can be used. The market for globally distributed advanced digital objects within a widely distributed operating system is too large to speculate on at this stage of market education and evolution. However, for perspective, the global real estate market represents over $24 trillion USD. The e-learning marketplace tops $7 Trillion USD. The potential DeFi market-size is similarly large.

> The total addressable market for a decentralized multi-chain and cross-chain operating system is not known.

Potential customer segments by industries and corporate functions:

1. Real Estate
2. Equities
3. Jurisdictional Fencing
4. Gaming
5. Metaverse
6. Internet of Things (IOT)
7. Patents
8. Insurance
9. Bonds
10. Credit Scoring
11. Carbon Credits
12. Royalties
13. Taxes
14. Regulatory Compliance
15. Medical Records
16. Corporate Treasury & Management
17. Decentralized eCommerce

# 10. Core Contributors 

**Cody Marx Bailey** Core Contributor – Protocol Architect

Cody is a veteran in the blockchain, cryptography, and distributed systems space. In 2013 he started working on early developments in Ethereum Smart Contracts. In 2017, he co-authored the ERC-721 Non-Fungible Token standard for the Ethereum chain. Since then, he has been developing complex financial blockchain instruments. 

**Brendan Cooper** Core Contributor - Technology Strategy & Economics 

Brendan Cooper has led technology strategy and implementation for globally recognized companies and venture funded startups. He led the digital transformation for the largest collectible company in the world, Panini, using the converged stack of emerging cryptographic platforms, primitives, smart contracts, artificial intelligence/machine learning, eCommerce, mobile and XR technologies. 

**Connor Barr** Core Contributor - Lead Engineer

Full stack, Cosm/Wasm, and blockchain integrated web and DApp development. Connor helped develop a Blockchain supported toll road app, as part of a team, which placed 2nd at the 2019 MOBI Hackathon first phase, also receiving the “Most Feasible” award. 

**Mant Hawkins** Core Contributor - Business Strategy, Leadership 

Mant learned his foundational serial entrepreneur skills as a combat veteran which he applied as a multiple time Founder and CEO, Corporate Board Member, National Defense Industry Association President with expertise in aviation, directed energy technology, smart building commercial real estate, ERC-721 Projects, Blockchain Prop Tech and “the business of blockchain. “ As a Colonel (Retired) of the United States Marine Corps (USMC), TOPGUN Instructor, he commanded an FA-18 squadron (250 people/12 FA-18s) and group level (3 squadrons), led all USMC air and aviation ground combat operations in Iraq, Think Tank Director for the Commanding General of US Central Command and was the Director of the Global Combating Terrorism Network for US Special Operations Command.

# 11. Conclusion

Builders and creators now have the tools to rapidly create new Web3 business models by composing and assembling the best Web3 capabilities found across blockchains and ecosystems. aOS removes technological barriers to:

1. Business model creation and deployment aligned with the accelerating rate of global change
2. Build and test business models at Global Scale in minutes at no cost
3. De-risking business and fraud reduction
4. Instant access to infrastructure rails - permissionless access to compute, storage, payment, marketplace, distribution, application, and other service infrastructure
5. Tokenization and Digital Ownership of assets
6. Global market access
7. Instant community access
8. Eliminate intermediaries
9. Variable costs of operation

Andromeda Operating System (aOS) is a multi-chain, cross-chain operating system built on a breakthrough in modular and composable smart contract architecture. It powers decentralized applications, aggregates capabilities across chains, and creates network effects. aOS, and the blockchains that use it, harness scaled network effects. New tokenomic models index value across many blockchains utilizing a multi-cryptocurrency design.  

aOS and all participating chains benefit from aOS network effects. All get increased demand on their token. aOS is launching on 6 blockchains and is engineered to handle thousands of blockchains. Network effects means token value scales as a function of Metcalfe’s Law V=n<sup>2</sup> where ‘n’ is the number of users on all the blockchains using aOS. There are many different kinds of network effects that arise from aOS. 

A vast application design space unlocks powerful incentives to produce compelling Web3 value and ANDR utility value. These communities are incentivized to build and test business models at global scale in minutes at no cost.

aOS creates a viable new model for monetizing open source software development leading to explosive growth across Web3.

# 12. Bibliography

Van Valkenburg, Peter. The Best explanation of BITCOIN you will ever hear | PV Valkenburg; Congressional hearing <https://www.youtube.com/watch?v=HzxKs-Jd0H4> 

Kwon, J., & Buchman, E. (n.d.). Internet of Blockchains (Whitepaper). December 20, 2020, from <https