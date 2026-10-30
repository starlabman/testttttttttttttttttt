# ZecHub glossary review: Ewe (`ee`)

Glossary version 1. Kit: pages.

**How to fill in**

- **✅ column:** write `OK` if the shown rendering is right, `keep English` to keep the English word, or the rendering you would use. One rendering per cell. Leave it empty if you are not sure. Do not edit the ID column.
- **Notes column (important):** for every row you change or mark `keep English`, write one short line in your own words saying why, for example "this is what local exchanges and wallets use" or "this word means a street address". Also use Notes when the right word depends on the context (verb or noun, menu or page), or when a row is unclear. Changes without a note may not be accepted.

Names that stay in English in every language (brands, products, programmes) are not in these tables; they are listed in `translation/protected-terms.json`.

## Conflicts to decide first

No conflicts.

## Terms in wiki pages
(`terms`: 62 rows)

| # | ID | English | Meaning | Occurrences | Seen today in `ee` pages | Proposed | ✅ Confirmed | Notes |
|---|---|---|---|---:|---|---|---|---|
| 1 | wallet | wallet | App or device that holds the keys to your coins and lets you send and receive them. | 1,694 | wallet (English) ×253, wallets (English) ×58 |  | gakotoku | A money-pouch metaphor fits something that holds keys; confirm that it works naturally for a digital wallet. |
| 2 | shielded | shielded | Protected by Zcash's zero-knowledge encryption: a shielded address, transaction or pool hides sender, receiver and amount. Not: encrypted (generic). Translate 'encrypted' normally. | 1,433 | shielded (English) ×466, unshielded (English) ×2 |  | ɣaɣla | This short term suggests hidden details; confirm it does not imply generic encryption. |
| 3 | transaction | transaction | A transfer of coins recorded on the blockchain. | 1,281 | transaction (English) ×79, transactions (English) ×66 |  | gaɖoɖo | This is a concise term for a transfer; confirm it specifically fits a blockchain transaction. Yellow Card API docs use the word transaction: [limits](https://docs.yellowcard.engineering/docs/api-transaction-limits.md). |
| 4 | address | address | A string that identifies where to send coins (shielded z-address, unified address, transparent t-address). Not: a street address, or 'to address' (speak to, deal with). | 1,140 | address (English) ×163, addresses (English) ×35 |  | dzesi | This means a sign or identifying mark; using it for a payment destination needs context checking. |
| 5 | privacy | privacy | Keeping your financial information hidden from others; the core value of Zcash. | 844 | privacy (English) ×106 |  | ɣaɣla | This candidate suggests hidden information; confirm it expresses financial privacy rather than encryption. |
| 6 | pool | pool | A bucket of coins sharing one privacy technology (the shielded Orchard pool, the transparent pool); also a mining pool. Suggestion: keep English. | 732 | pool (English) ×136, pools (English) ×58 |  | keep English | The term has several specialised meanings in Zcash and mining, so keeping the established English avoids ambiguity. |
| 7 | block | block | A batch of transactions added to the blockchain; block height is its position in the chain. Not: 'to block' (prevent, stop). | 657 | block (English) ×479, blocks (English) ×54 |  | blɔk | This loanword distinguishes a blockchain block from the ordinary verb to block. |
| 8 | payment | payment | Sending coins to pay someone. | 607 | payment (English) ×60, payments (English) ×12 | Fexexe (gaɖoɖo ɖe ame aɖe be woaxe fe) | Fexexe | The interpreter accepted this short term in the trial. Yellow Card serves Ghana and uses the word payments: [service](https://yellowcard.io/), [stablecoin payments](https://docs.yellowcard.engineering/docs/accept-stablecoin-payments.md). |
| 9 | node | node | A computer running Zcash software that stores and checks the blockchain. Suggestion: keep English. | 600 | node (English) ×420, nodes (English) ×87 |  | keep English | Keeping the standard technical term avoids confusion with an ordinary computer or network node. |
| 10 | proof | proof | Cryptographic proof: mathematical evidence that a statement is true (for example that a transaction is valid) without showing the data. Not: proof as general evidence in a non-cryptographic sense. Suggestion: keep English. | 569 | proof (English) ×82, proofs (English) ×25 |  | dase | The proposed Ewe word means testimony or evidence; its cryptographic sense needs confirmation. |
| 11 | chain | chain | Short for blockchain. | 476 | chain (English) ×101, chains (English) ×2 |  | blɔk-kuku | This short form follows the interpreter trial wording for blockchain; confirm that it works for the shorter term chain. |
| 12 | transparent | transparent | The public, Bitcoin-like part of Zcash where addresses and amounts are visible to everyone. | 455 | transparent (English) ×95 |  | keep English | The term refers to Zcash's public pool type, not just ordinary transparency, so keeping English avoids ambiguity. |
| 13 | note | note | In Zcash, a shielded unit of value (like a private coin) held by a shielded address. Not: a written note or remark, and 'to note' (to notice); translate those normally. | 411 | note (English) ×40, notes (English) ×16 |  | keep English | In Zcash this is a protocol value, not a written note; no concise Ewe label is established yet. |
| 14 | encryption | encryption | Scrambling data so only holders of the right key can read it; 'encrypted' describes such data. | 309 | encrypted (English) ×87, encryption (English) ×39, encrypt (English) ×19 |  | keep English | Keep this distinct from shielded, which describes hidden transaction details rather than encryption generally. |
| 15 | blockchain | blockchain | The shared public record of all transactions, built from linked blocks. Suggestion: keep English. | 296 | blockchain (English) ×257, blockchains (English) ×18 |  | blɔk-kuku | The interpreter used this short compound in the trial; confirm it names the shared transaction ledger. |
| 16 | exchange | exchange | A business or service where people buy, sell or trade cryptocurrencies (a crypto exchange). Not: the verb 'to exchange' (to swap one thing for another). Suggestion: keep English. | 281 | exchange (English) ×59, exchanges (English) ×33 |  | asitsatsa | This Ewe word refers to trade; its use for a crypto-exchange service needs confirmation. |
| 17 | signature | signature | Cryptographic proof that the holder of a key approved a transaction or message. Not: a handwritten signature. | 213 | signature (English) ×33, signatures (English) ×17 | Asidede agbalẽ te | keep English | The proposal suggests handwriting, while a crypto signature proves key-authorised approval. |
| 18 | custodial | custodial | Who holds the keys: custodial means a company holds your coins for you; non-custodial or self-custody means you hold them. | 212 | custodial (English) ×38, non-custodial (English) ×23, custody (English) ×16, self-custody (English) ×2 |  | keep English | The term distinguishes who controls the keys; a literal short translation could obscure that responsibility. |
| 19 | memo | memo | A short private message attached to a shielded transaction. | 208 | memo (English) ×62, memos (English) ×25 | Nuŋlɔɖi kpui ɣaɣla si wotsɔ kpe ɖe asitsatsa si wotsɔ akpoxɔnu wɔe ŋu | nya | The short candidate means a word or message; confirm it fits the private message attached to a transaction. |
| 20 | mining | mining | Using computers to add new blocks to the blockchain and earn newly created coins. Not: 'determining' and other words that merely contain the letters. | 208 | mining (English) ×42, mine (English) ×2, mined (English) ×1 |  | keep English | This means the crypto process of creating and validating blocks, not extracting minerals; keep English until a short term is confirmed. |
| 21 | commitment | commitment | A cryptographic value that binds to hidden data (e.g. a note commitment) without revealing it. Not: a promise or pledge. Suggestion: keep English. | 202 | commitment (English) ×29, commitments (English) ×12 | Adzɔgbeɖeɖe | keep English | The proposal may suggest a promise; this term has a specific cryptographic meaning. |
| 22 | fee | fee | The small amount paid to the network to process a transaction. | 199 | fee (English) ×22, fees (English) ×7 |  | fe | The trial wording uses this word for a payment charge; confirm it also fits a network transaction fee. |
| 23 | zero-knowledge | zero-knowledge | Cryptography that proves something is true without revealing the underlying information. Suggestion: keep English. | 197 | zero-knowledge (English) ×32, zero knowledge (English) ×6 |  | keep English | This is a specific cryptographic method, so keeping the established technical term avoids a misleading literal translation. |
| 24 | grant | grant | Money awarded to fund a project or contributor (e.g. Zcash Community Grants). Not: 'to grant' (to allow, give). | 191 | grants (English) ×54, grant (English) ×18 |  | keep English | This means awarded project funding, not the verb ?to grant?; keeping English avoids mixing the senses. |
| 25 | tools | tools | Software or services that help do something (privacy tools, developer tools). | 184 | tools (English) ×22, tool (English) ×10 |  | dɔwɔnu | This short term is already used for tools in the menu; confirm it also fits software and services. |
| 26 | viewing-key | viewing key | A key that lets someone see, but not spend, the transactions of a wallet. Capitalised 'Viewing Key' is already a protected name. Suggestion: keep English. | 179 | viewing key (English) ×38, viewing keys (English) ×7, view key (English) ×1, view keys (English) ×1 |  | keep English | This is a specific wallet key type; keeping the recognised technical label avoids confusion with an ordinary viewing key. |
| 27 | swap | swap | Exchanging one cryptocurrency directly for another. Suggestion: keep English. | 178 | swap (English) ×49, swaps (English) ×24 |  | asitsatsa | This Ewe word refers to trade; its use for a direct crypto-asset swap needs confirmation. |
| 28 | token | token | A digital asset created on a blockchain, other than the chain's own coin. Suggestion: keep English. | 173 | token (English) ×54, tokens (English) ×7 |  | keep English | This is a blockchain asset category, so keeping its established technical name avoids a generic reading. |
| 29 | consensus | consensus | The rules and process by which nodes agree on the state of the blockchain. | 159 | consensus (English) ×35 |  | keep English | This means agreement on the blockchain state under protocol rules, not just general agreement. |
| 30 | staking | staking | Locking coins to help secure a proof-of-stake network and earn rewards; 'stake' is the amount locked. Not: a wooden stake, or a stake in a bet; never translate as a tree, post or field. | 139 | staking (English) ×45, stake (English) ×30, staked (English) ×10, stakes (English) ×1 |  | keep English | This is the crypto process of locking coins for network participation, not a physical stake or wager. |
| 31 | decentralized | decentralized | Run by many independent participants rather than one company or server. | 136 | decentralized (English) ×35, decentralization (English) ×14, decentralisation (English) ×3, decentralised (English) ×1 |  | keep English | This describes a system run by independent participants, not simply something located far away. |
| 32 | network-upgrade | network upgrade | A scheduled change to Zcash's rules that all nodes adopt at a set block height (NU5, NU6 and so on). | 128 | network upgrade (English) ×44, network upgrades (English) ×12 | Ɖɔa ƒe dodoɖedzi (tɔtrɔ si woɖo ɖi na Zcash ƒe sewo, si ɖɔdzinɔla ɖe sia ɖe xɔna le blɔk-kɔkɔme ɖoɖoɖi aɖe dzi) | keep English | This is a scheduled change to protocol rules; keeping the technical label avoids an overly broad translation. |
| 33 | developer | developer | A person who writes software, here usually for Zcash or a Zcash wallet. Not: development (the activity), which is usually translated. | 126 | developer (English) ×22, developers (English) ×18 | Ŋgɔyiyi | dɔwɔla | The current menu uses this word for developers; confirm it specifically means a software developer. |
| 34 | full-node | full node | A node that downloads and verifies the entire blockchain. Suggestion: keep English. | 120 | full node (English) ×25, full nodes (English) ×2 |  | keep English | This is a specific type of blockchain node; keeping the technical label avoids losing the ?full chain? distinction. |
| 35 | on-chain | on-chain | Recorded on the blockchain itself; off-chain means outside it. Suggestion: keep English. | 119 | on-chain (English) ×14, off-chain (English) ×5, onchain (English) ×4 |  | blɔk-kuku dzi | This follows the interpreter trial wording for information recorded on the blockchain. |
| 36 | governance | governance | How decisions about Zcash (funding, upgrades) are made and by whom. | 103 | governance (English) ×18 |  | dziɖuɖu | This short form is already used for governance in the menu; confirm its fit for Zcash decision-making. |
| 37 | turnstile | turnstile | Zcash mechanism that checks the total coins leaving a pool never exceed what entered it. Suggestion: keep English. | 97 | turnstile (English) ×46, turnstiles (English) ×1 |  | keep English | This is a named Zcash accounting mechanism, so keeping its technical label avoids a misleading literal translation. |
| 38 | spending-key | spending key | The secret key that authorises spending coins; whoever has it controls the funds. Suggestion: keep English. | 94 | spending key (English) ×5, spending keys (English) ×1 |  | keep English | This is a specific secret key that authorises spending, not a general key. |
| 39 | miner | miner | A person or machine that does mining. | 92 | miner (English) ×9, miners (English) ×1 | Nukula (ame alo mɔ̃ si wɔa blɔk-kuku ƒe dɔa) | keep English | The short proposal may be read as ?buyer?; the long explanation is too unwieldy as a glossary term. |
| 40 | nullifier | nullifier | A unique value published when a shielded note is spent, so the same note cannot be spent twice, without revealing which note it was. Suggestion: keep English. | 88 | nullifier (English) ×61, nullifiers (English) ×8 |  | keep English | This is a specific value preventing a shielded note from being spent twice; a generic translation could obscure that role. |
| 41 | hardware-wallet | hardware wallet | A small device that stores keys offline and signs transactions (e.g. Ledger, Keystone). Suggestion: keep English. | 76 | hardware wallet (English) ×3, hardware wallets (English) ×1 |  | keep English | This names a specific offline key-storing device, so the established technical term is clearer. |
| 42 | bridge | bridge | A service that moves assets between two different blockchains. Not: a physical bridge. | 68 | bridge (English) ×16, bridges (English) ×2 |  | keep English | This means a service moving assets between blockchains, not a physical bridge. |
| 43 | halving | halving | The scheduled event that cuts the block reward in half, about every four years. | 61 | halving (English) ×8, halvings (English) ×2 | Fetu ƒe afãmama (azɔ si me woɖea blɔk ƒe fetu dzi wòzua afã, ƒe ene ɖe sia ɖe) | afãmama | This short form expresses halving; confirm that it clearly means cutting the block reward in half. |
| 44 | finalizer | finalizer | A participant in Zcash's proof-of-stake layer that votes to make blocks final; stakers delegate to a finalizer. Not: anything to do with a final match or contest. Suggestion: keep English. | 58 | finalizer (English) ×33, finalizers (English) ×5 |  | keep English | This is a specific proof-of-stake participant, not someone finishing a contest. |
| 45 | newsletter | newsletter | A regular email or post that collects ZecHub and Zcash news. | 50 | newsletter (English) ×12 |  | nyadzɔdzɔgbalẽ | This short form is already used for newsletter in the menu; confirm it suits a recurring email or post. |
| 46 | trusted-setup | trusted setup | A one-time ceremony that generates public parameters for a proof system; its secret must be destroyed. | 50 | trusted setup (English) ×9 |  | keep English | This names a one-time cryptographic ceremony; keep the technical term to avoid implying ordinary trust. |
| 47 | bond | bond | Stake locked and delegated to a finalizer for a period; unbonding releases it. Not: a financial bond (debt security) or a personal bond. | 46 | bond (English) ×17, bonds (English) ×3 |  | keep English | This is locked and delegated stake, not a financial security or personal relationship. |
| 48 | scaling | scaling | Increasing how many transactions a network can handle. Not: shrinking or resizing. | 46 | scaling (English) ×17, scalability (English) ×12 |  | keep English | This means increasing transaction capacity, not changing size in either direction. |
| 49 | faucet | faucet | A website that gives away tiny amounts of (often test) coins for free. Suggestion: keep English. | 43 | faucet (English) ×15, faucets (English) ×7 |  | keep English | Keeping ?faucet? avoids confusing a crypto giveaway site with a water tap. |
| 50 | seed-phrase | seed phrase | A list of 12 to 24 words that backs up and restores a wallet. | 41 | seed phrase (English) ×3 |  | keep English | This is the wallet backup phrase; keeping the established label avoids confusion with an ordinary seed. |
| 51 | dashboard | dashboard | A page that shows live figures and charts at a glance. | 41 | dashboard (English) ×34, dashboards (English) ×1 |  | keep English | This is a live data-and-chart overview page; the familiar interface term is concise. |
| 52 | cross-chain | cross-chain | Working across two or more different blockchains. Suggestion: keep English. | 39 | cross-chain (English) ×21 |  | keep English | This describes operation across blockchains; the established technical term is clearer than a literal compound. |
| 53 | use-case | use case | A concrete way people use Zcash (payments, donations, records). | 31 | use case (English) ×1, use cases (English) ×1 |  | zã nyawo | This short form is already used for ?Use Cases? in the menu; confirm it also works in wiki prose. |
| 54 | smart-contract | smart contract | A program stored on a blockchain that runs automatically when its conditions are met. Suggestion: keep English. | 25 | smart contract (English) ×11, smart contracts (English) ×9 |  | keep English | This is an established blockchain-programming term; a literal rendering may not communicate its technical meaning. |
| 55 | light-client | light client | Wallet software that does not download the full blockchain but asks a server for the data it needs. Suggestion: keep English. | 24 | light client (English) ×8, light clients (English) ×1 |  | keep English | This names wallet software that relies on a server instead of downloading the full chain; keep the technical label. |
| 56 | selective-disclosure | selective disclosure | Showing chosen transaction details to a chosen party (e.g. with a viewing key) while keeping the rest private. | 19 | selective disclosure (English) ×2 |  | keep English | This means revealing chosen details while keeping others private; no concise Ewe term is confirmed. |
| 57 | treasury | treasury | Money held by a community or organisation to fund shared work. | 18 | treasury (English) ×3 |  | gakotoku | The candidate refers to a money pouch; its use for a community fund is a proposed metaphor to confirm. |
| 58 | top-up | top up | Adding credit to a prepaid phone or account, paid with ZEC. | 14 | top-up (English) ×3, top ups (English) ×1, top-ups (English) ×1 |  | keep English | This means adding prepaid account or phone credit, so the existing service term is clearer. |
| 59 | permissionless | permissionless | Open to anyone without asking for approval. | 13 |  |  | keep English | This means open to use without prior approval; keep English until a short natural Ewe term is confirmed. |
| 60 | unlinkable | unlinkable | Impossible to connect to each other: an observer cannot tell that two items belong to the same person. Not: 'disconnected' or 'detachable'; the meaning is 'cannot be linked'. | 12 |  |  | keep English | This means two items cannot be associated with each other, not simply disconnected. |
| 61 | brand | brand | ZecHub or Zcash brand material: logos, colours, visual identity. Not: trademark (a legal term). | 4 | brand (English) ×1 |  | keep English | This refers to visual identity and design assets, not only a legal trademark. |
| 62 | visualizer | visualizer | A tool that draws Zcash network or address data as pictures. Not: visualizing / visualization (the activity), which is usually translated. | 1 | visualizer (English) ×1 |  | nukpɔkpɔ | This candidate is based on the idea of seeing; confirm it works as the name of a data-visualisation tool. |

## General style questions
(`style`: 8 questions)

| # | ID | Question | Current | ✅ Answer | Notes |
|---|---|---|---|---|---|
| A | register | How to address the reader (formal or informal 'you'), and does it differ between tutorials and technical pages? |  | Use informal singular wò for direct instructions; use mi when addressing several readers. | A consistent direct tone suits tutorials and technical pages; avoid switching forms without a clear audience change. |
| B | english_in_brackets | When an English term is kept, add the English in brackets: never / first-use / always? |  | Give the English term in brackets at first use only, then use the Ewe term. | This introduces unfamiliar terminology without making every sentence harder to read. |
| C | loanwords | Crypto loanwords (blockchain, token, smart contract): keep English / translate? |  | Keep established crypto loanwords; explain them briefly in Ewe at first use. | Avoid long literal calques for specialist concepts. |
| D | capitalise_kept_english_at_sentence_start | Capitalise a kept English term at the start of a sentence (yes / no)? |  | Yes; follow normal sentence capitalization. | This keeps English loanwords consistent with the surrounding sentence. |
| E | numerals | Digits: western (0-9) only, or native digits allowed? |  | Use Western digits 0–9. | This is consistent with amounts, dates, block heights, and technical interfaces. |
| F | decimal_separator | Decimal separator (0.5 or 0,5)? |  | Use the decimal point: 0.5. | This matches common international financial and software notation. |
| G | quotes | Quotation marks? |  | Use “…” consistently for quotations. | One consistent quote style is easier to read across the site. |
| H | abbreviations_with_full_stop | Abbreviations written with a full stop that do not end a sentence? |  | Do not add a full stop to initialisms such as ZEC, DAO, or API. | Keep standard technical abbreviations intact and distinguish them from sentence punctuation. |





# ZecHub glossary review: Ewe (`ee`)

Glossary version 1. Kit: ui.

**How to fill in**

- **✅ column:** write `OK` if the shown rendering is right, `keep English` to keep the English word, or the rendering you would use. One rendering per cell. Leave it empty if you are not sure. Do not edit the ID column.
- **Notes column (important):** for every row you change or mark `keep English`, write one short line in your own words saying why, for example "this is what local exchanges and wallets use" or "this word means a street address". Also use Notes when the right word depends on the context (verb or noun, menu or page), or when a row is unclear. Changes without a note may not be accepted.

Names that stay in English in every language (brands, products, programmes) are not in these tables; they are listed in `translation/protected-terms.json`.

## Conflicts to decide first

No conflicts.

## Top menu (header) and its submenus
(`navigation`: 73 labels)

| # | ID | English | Ewe | ✅ Confirmed | Notes |
|---:|---|---|---|---|---|
| 1 | navigation.wallets | Wallets | Gakotokuwo | Gakotokuwo | A money-pouch metaphor fits something that holds keys; confirm that it works naturally for digital wallets. |
| 2 | navigation.guides | Guides | Mɔfialawo | OK |  |
| 3 | navigation.tutorials | Tutorials | Nufiamewo | OK |  |
| 4 | navigation.governance | Governance | Dziɖuɖu | OK |  |
| 5 | navigation.visualizer | Visualizer | Nukpɔkpɔ ƒe mɔ̃ | OK |  |
| 6 | navigation.dao | DAO | DAO ƒe ŋkɔ | OK |  |
| 7 | navigation.newsletter | Newsletter | Nyadzɔdzɔgbalẽ | OK |  |
| 8 | navigation.donate | Donate | Na nu | OK |  |
| 9 | navigation.explore | Explore | Tsa le eme | OK |  |
| 10 | navigation.developers | Developers | Dɔwɔlawo | OK |  |
| 11 | navigation.community | Community | Hatsotso | OK |  |
| 12 | navigation.contribute | Contribute | Dzɔ nu | Kpe ɖe ŋu | This short phrase expresses helping or contributing more directly. |
| 13 | navigation.dashboard | Dashboard | Dashboard ƒe ʋuƒo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 14 | navigation.more | More | Gawu | OK |  |
| 15 | navigation.usingZcash.label | Use Zcash | Zã Zcash | OK |  |
| 16 | navigation.usingZcash.buyingZec | Buying ZEC | ZEC ƒeƒle | OK |  |
| 17 | navigation.usingZcash.faucets | Faucets | Pɔmpiwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 18 | navigation.usingZcash.wallets | Wallets | Gadzraɖoƒewo | Gakotokuwo | A money-pouch metaphor fits something that holds keys; confirm that it works naturally for digital wallets. |
| 19 | navigation.usingZcash.exchanges | Exchanges | Nuwo ɖɔliɖɔli | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 20 | navigation.usingZcash.blockExplorers | Block Explorers | Block Nukulawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 21 | navigation.usingZcash.shieldedPools | Shielded Pools | Ta Siwo Wotsɔ Akpoxɔnu Wɔe | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 22 | navigation.usingZcash.transparentExchangeAddresses | Transparent Exchange Addresses | Adrɛs Siwo Wotsɔna Ðoa Nui Siwo Me Kɔkɔe | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 23 | navigation.usingZcash.transactions | Transactions | Adzɔnuwo ƒe asitsatsa | gaɖoɖowo | This uses the short trial term for blockchain transfers rather than a phrase suggesting trade. |
| 24 | navigation.usingZcash.memos | Memos | Nuŋlɔɖiwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 25 | navigation.usingZcash.mobileTopUps | Mobile Top Ups | Asitelefon dzi Top Ups | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 26 | navigation.usingZcash.paymentRequestUris | Payment Request URIs | Fexexe ƒe Biabia ƒe URIwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 27 | navigation.usingZcash.paymentProcessors | Payment Processors | Fexexe Ŋuti Dɔwɔlawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 28 | navigation.usingZcash.recoveringFunds | Recovering Funds | Gawo Xɔxɔ | OK |  |
| 29 | navigation.usingZcash.tools | Tools | Dɔwɔnuwo | OK |  |
| 30 | navigation.usingZcash.useCases | Use Cases | Zã Nyawo | OK |  |
| 31 | navigation.usingZcash.useCasesSubmenu.startHere | Start Here | Dze Egɔme Le Afi Sia | OK |  |
| 32 | navigation.usingZcash.useCasesSubmenu.acceptPayments | Accept Payments | Lɔ̃ Ðe Fexexewo Dzi | OK |  |
| 33 | navigation.usingZcash.useCasesSubmenu.freelancePrivacy | Freelance Privacy | Ame ŋutɔ ƒe Nyatakakawo Ŋuti Nyatakakawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 34 | navigation.usingZcash.useCasesSubmenu.journalistPrivacy | Journalist Privacy | Nyadzɔdzɔŋlɔlawo ƒe Nyatakakawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 35 | navigation.usingZcash.useCasesSubmenu.keepingRecords | Keeping Records | Nuŋlɔɖiwo Dzraɖoƒe | OK |  |
| 36 | navigation.usingZcash.useCasesSubmenu.privateCommunityTreasury | Private Community Treasury | Ame ŋutɔ ƒe Nutoa me Gadzɔdzɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 37 | navigation.usingZcash.useCasesSubmenu.donations | Donations | Nudzɔdzɔwo | OK |  |
| 38 | navigation.usingZcash.useCasesSubmenu.sendMoneyPrivately | Send Money Privately | Ðo Ga Ðe Ame Ðokui Si | OK |  |
| 39 | navigation.zcashCommunity.label | Ecosystem | Nu gbagbewo ƒe agbenɔnɔ ƒe ɖoɖo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 40 | navigation.zcashCommunity.communityBlogs | Community Blogs | Nutoa me Blogwo | OK |  |
| 41 | navigation.zcashCommunity.communityLinks | Community Links | Nutoa Me Kadodowo | OK |  |
| 42 | navigation.zcashCommunity.communityForum | Community Forum | Nutoa me Takpekpe | OK |  |
| 43 | navigation.zcashCommunity.communityProjects | Community Projects | Nutoa me Dɔwɔnawo | OK |  |
| 44 | navigation.zcashCommunity.zcashMedia | Zcash Media | Zcash Nyadzɔdzɔgblɔmɔnuwo | OK |  |
| 45 | navigation.zcashCommunity.zcashPodcasts | Zcash Podcasts | Zcash ƒe Podcastwo | OK |  |
| 46 | navigation.zcashCommunity.ecosystemSecurity | Zcash Ecosystem Security | Zcash Nutoa me ƒe Dedienɔnɔ | OK |  |
| 47 | navigation.zcashCommunity.cypherpunkZeroNFT | Cypherpunk Zero NFT | Cypherpunk Zero NFT ƒe agbalẽa | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 48 | navigation.zcashCommunity.zconArchive | Zcon Archive | Zcon ƒe Nudzraɖoƒe | OK |  |
| 49 | navigation.organizations.label | Organizations | Habɔbɔwo | OK |  |
| 50 | navigation.organizations.brand | Brand | Nudzadzra ŋkɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 51 | navigation.organizations.coinholderDirectedRetroactiveGrants | CoinHolder Directed Retroactive Grants | Kɔingadzilawo ƒe kpekpeɖeŋu siwo wotsɔ na nu siwo va yi | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 52 | navigation.guidesSubmenu.zgoPaymentProcessor | Zgo Payment Processor | Zgo Fexexe Ŋuti Dɔwɔƒe | OK |  |
| 53 | navigation.guidesSubmenu.free2zLive | Free2z Live | Free2z Live | OK |  |
| 54 | navigation.guidesSubmenu.nymVpn | Nym VPN | Nym VPN | OK |  |
| 55 | navigation.guidesSubmenu.usingZecInDefi | Using ZEC in DeFi | ZEC zazã le DeFi me | OK |  |
| 56 | navigation.guidesSubmenu.usingZecPrivately | Using ZEC Privately | ZEC Zazã le Adzame | OK |  |
| 57 | navigation.guidesSubmenu.raspberryPiZcashdNode | Raspberry Pi Zcashd Node | Raspberry Pi Zcashd ƒe ƒuƒoƒo | OK |  |
| 58 | navigation.guidesSubmenu.raspberryPi5ZebraLightwalletdZingo | Raspberry pi5 Zebra Lightwalletd Zingo | Raspberry pi5 Zebra ƒe Kekeli ƒe Zingo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 59 | navigation.guidesSubmenu.raspberryPiZebraNode | Raspberry Pi Zebra Node | Raspberry Pi Zebra Node ƒe ƒuƒoƒo | OK |  |
| 60 | navigation.guidesSubmenu.akashNetwork | Akash Network | Akash ƒe Nyatakakadzraɖoƒe | OK |  |
| 61 | navigation.guidesSubmenu.avalancheRedbridge | Avalanche RedBridge | Avalanche ƒe Tɔdzisasrã Dzĩ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 62 | navigation.guidesSubmenu.zkoolMultisig | Zkool Multisig | Zkool Multisig ƒe dɔwɔwɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 63 | navigation.guidesSubmenu.ywalletFrostDemo | Ywallet FROST Demo | Ywallet FROST ƒe wɔwɔfia | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 64 | navigation.guidesSubmenu.blockchainExplorers | Blockchain Explorers | Blockchain ƒe Nukulawo | OK |  |
| 65 | navigation.guidesSubmenu.btcPayServerPlugin | BTCPayServer Plugin | BTCPayServer ƒe Dɔwɔnu | OK |  |
| 66 | navigation.guidesSubmenu.visualizingZcashNetwork | Visualizing the Zcash Network | Zcash Network la kpɔkpɔ le susu me | OK |  |
| 67 | navigation.guidesSubmenu.visualizingZcashAddresses | Visualizing Zcash Addresses | Zcash Adrɛswo Kpɔkpɔ le susu me | OK |  |
| 68 | navigation.guidesSubmenu.zcashImprovementProposals | Zcash Improvement Proposals | Zcash ƒe Ŋgɔyiyi ƒe Aɖaŋuɖoɖowo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 69 | navigation.guidesSubmenu.zingolibAndZainoTutorial | Zingolib and Zaino Tutorial | Zingolib kple Zaino ƒe Nufiame | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 70 | navigation.guidesSubmenu.zenithInstallation | Zenith Installation | Zenith ƒe Dɔwɔɖoɖo | OK |  |
| 71 | navigation.guidesSubmenu.zeroKnowledgeVsDecoys | Zero Knowledge vs Decoy Systems | Zero Sidzedze vs Decoy Dɔwɔɖoɖowo | OK |  |
| 72 | navigation.overview | Overview | Kpɔɖeŋu bliboa | OK |  |
| 73 | navigation.shop | Shop | Fiase | OK |  |

## Submenu entries (page names in the menus)
(`menuLabels`: 81 labels)

| # | ID | English | Ewe | ✅ Confirmed | Notes |
|---:|---|---|---|---|---|
| 1 | menuLabels.Accept Payments | Accept Payments | Lɔ̃ Ðe Fexexewo Dzi | OK |  |
| 2 | menuLabels.Akash Network Zebra | Akash Network Zebra | Akash Network Zebra | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 3 | menuLabels.Avalanche RedBridge | Avalanche RedBridge | Avalanche ƒe Tɔdzisasrã Dzĩ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 4 | menuLabels.BTCPayServer Zcash Plugin | BTCPayServer Zcash Plugin | BTCPayServer Zcash ƒe Dɔwɔnu | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 5 | menuLabels.Blockchain Explorers | Blockchain Explorers | Blockchain ƒe Nukulawo | OK |  |
| 6 | menuLabels.Brand | Brand | Nudzadzra ŋkɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 7 | menuLabels.Buying ZEC | Buying ZEC | ZEC ƒeƒle | OK |  |
| 8 | menuLabels.Community Blogs | Community Blogs | Nutoa me Blogwo | OK |  |
| 9 | menuLabels.Community Forum | Community Forum | Nutoa me Takpekpe | OK |  |
| 10 | menuLabels.Community Links | Community Links | Nutoa Me Kadodowo | OK |  |
| 11 | menuLabels.Community Projects | Community Projects | Nutoa me Dɔwɔnawo | OK |  |
| 12 | menuLabels.Contribute | Contribute | Dzɔ nu | Kpe ɖe ŋu | This short phrase expresses helping or contributing more directly. |
| 13 | menuLabels.Cypherpunk Zero NFT | Cypherpunk Zero NFT | Cypherpunk Zero NFT ƒe agbalẽa | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 14 | menuLabels.DAO | DAO | DAO ƒe ŋkɔ | OK |  |
| 15 | menuLabels.Developers | Developers | Dɔwɔlawo | OK |  |
| 16 | menuLabels.Donations | Donations | Nudzɔdzɔwo | OK |  |
| 17 | menuLabels.Exchanges | Exchanges | Nuwo ɖɔliɖɔli | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 18 | menuLabels.Extras | Extras | Nu bubuwo | OK |  |
| 19 | menuLabels.Faucets | Faucets | Pɔmpiwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 20 | menuLabels.Free2z Live | Free2z Live | Free2z Live | OK |  |
| 21 | menuLabels.Freelance Privacy | Freelance Privacy | Ame ŋutɔ ƒe Nyatakakawo Ŋuti Nyatakakawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 22 | menuLabels.Governance | Governance | Dziɖuɖu | OK |  |
| 23 | menuLabels.Guides | Guides | Mɔfialawo | OK |  |
| 24 | menuLabels.How to Participate | How to Participate | Ale Si Nàkpɔ Gome le Eme | OK |  |
| 25 | menuLabels.Journalist Privacy | Journalist Privacy | Nyadzɔdzɔŋlɔlawo ƒe Nyatakakawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 26 | menuLabels.Keeping Records | Keeping Records | Nuŋlɔɖiwo Dzraɖoƒe | OK |  |
| 27 | menuLabels.Memos | Memos | Nuŋlɔɖiwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 28 | menuLabels.Mobile Top Ups | Mobile Top Ups | Asitelefon dzi Top Ups | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 29 | menuLabels.Newsletter | Newsletter | Nyadzɔdzɔgbalẽ | OK |  |
| 30 | menuLabels.Nym VPN | Nym VPN | Nym VPN | OK |  |
| 31 | menuLabels.Payment Processors | Payment Processors | Fexexe Ŋuti Dɔwɔlawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 32 | menuLabels.Payment Request URIs | Payment Request URIs | Fexexe ƒe Biabia ƒe URIwo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 33 | menuLabels.Podcast | Podcast | Na | keep English | The current Ewe value reads like a verb, not the name of a media format. |
| 34 | menuLabels.Private Community Treasury | Private Community Treasury | Ame ŋutɔ ƒe Nutoa me Gadzɔdzɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 35 | menuLabels.Raspberry Pi 4 Full Node | Raspberry Pi 4 Full Node | Raspberry Pi 4 Blibo Node | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 36 | menuLabels.Raspberry pi 4 Zebra Node | Raspberry pi 4 Zebra Node | Raspberry pi 4 Zebra ƒe Node | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 37 | menuLabels.Raspberry pi5 Zebra Lightwalletd Zingo | Raspberry pi5 Zebra Lightwalletd Zingo | Raspberry pi5 Zebra ƒe Kekeli ƒe Zingo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 38 | menuLabels.Recovering Funds | Recovering Funds | Gawo Xɔxɔ | OK |  |
| 39 | menuLabels.Research | Research | Numekuku | OK |  |
| 40 | menuLabels.Send Money Privately | Send Money Privately | Ðo Ga Ðe Ame Ðokui Si | OK |  |
| 41 | menuLabels.Shielded Pools | Shielded Pools | Ta Siwo Wotsɔ Akpoxɔnu Wɔe | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 42 | menuLabels.Sitemap | Sitemap | Nyatakakadzraɖoƒe ƒe Nɔnɔmetata | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 43 | menuLabels.Start Here | Start Here | Dze Egɔme Le Afi Sia | OK |  |
| 44 | menuLabels.Store | Store | Fiase | OK |  |
| 45 | menuLabels.Tools | Tools | Dɔwɔnuwo | OK |  |
| 46 | menuLabels.Transactions | Transactions | Adzɔnuwo ƒe asitsatsa | gaɖoɖowo | This uses the short trial term for blockchain transfers rather than a phrase suggesting trade. |
| 47 | menuLabels.Transparent Exchange Addresses | Transparent Exchange Addresses | Adrɛs Siwo Wotsɔna Ðoa Nui Siwo Me Kɔkɔe | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 48 | menuLabels.Tutorials | Tutorials | Nufiamewo | OK |  |
| 49 | menuLabels.Use Cases | Use Cases | Zã Nyawo | OK |  |
| 50 | menuLabels.Using ZEC Privately | Using ZEC Privately | ZEC Zazã le Adzame | OK |  |
| 51 | menuLabels.Using ZEC in DeFi | Using ZEC in DeFi | ZEC zazã le DeFi me | OK |  |
| 52 | menuLabels.Using Zcash | Using Zcash | Zcash zazã | OK |  |
| 53 | menuLabels.Visual Identity | Visual Identity | Ŋutega ƒe Dzesidede Ame | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 54 | menuLabels.Visualizer | Visualizer | Nukpɔkpɔ ƒe mɔ̃ | OK |  |
| 55 | menuLabels.Visualizing Zcash Addresses | Visualizing Zcash Addresses | Zcash Adrɛswo Kpɔkpɔ le susu me | OK |  |
| 56 | menuLabels.Visualizing the Zcash Network | Visualizing the Zcash Network | Zcash Network la kpɔkpɔ le susu me | OK |  |
| 57 | menuLabels.Wallets | Wallets | Gakotokuwo | Gakotokuwo | A money-pouch metaphor fits something that holds keys; confirm that it works naturally for digital wallets. |
| 58 | menuLabels.Ywallet FROST Demo | Ywallet FROST Demo | Ywallet FROST ƒe wɔwɔfia | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 59 | menuLabels.ZIPs & Grants | ZIPs & Grants | ZIPwo & Gakpekpeɖeŋunana | OK |  |
| 60 | menuLabels.Zcash Community | Zcash Community | Zcash Habɔbɔa ƒe Habɔbɔ | Zcash Habɔbɔ | This removes the repeated wording for ?community.? |
| 61 | menuLabels.Zcash Ecosystem Security | Zcash Ecosystem Security | Zcash Nutoa me ƒe Dedienɔnɔ | OK |  |
| 62 | menuLabels.Zcash Governance | Zcash Governance | Zcash Dziɖuɖu | OK |  |
| 63 | menuLabels.Zcash Improvement Proposals | Zcash Improvement Proposals | Zcash ƒe Ŋgɔyiyi ƒe Aɖaŋuɖoɖowo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 64 | menuLabels.Zcash Media | Zcash Media | Zcash Nyadzɔdzɔgblɔmɔnuwo | OK |  |
| 65 | menuLabels.Zcash Organizations | Zcash Organizations | Zcash Habɔbɔwo | OK |  |
| 66 | menuLabels.Zcash Podcasts | Zcash Podcasts | Zcash ƒe Podcastwo | OK |  |
| 67 | menuLabels.Zcon Archive | Zcon Archive | Zcon ƒe Nudzraɖoƒe | OK |  |
| 68 | menuLabels.Zcon Vozes Archive | Zcon Vozes Archive | Zcon Vozes ƒe Nudzraɖoƒe | OK |  |
| 69 | menuLabels.Zenith Installation | Zenith Installation | Zenith ƒe Dɔwɔɖoɖo | OK |  |
| 70 | menuLabels.Zero-Knowledge vs Decoys | Zero-Knowledge vs Decoys | Zero-Sidzedze vs Ameflulawo | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 71 | menuLabels.Zgo Payment Processor | Zgo Payment Processor | Zgo Fexexe Ŋuti Dɔwɔƒe | OK |  |
| 72 | menuLabels.Zingolib and Zaino Tutorial | Zingolib and Zaino Tutorial | Zingolib kple Zaino ƒe Nufiame | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 73 | menuLabels.Zkool Multisig | Zkool Multisig | Zkool Multisig ƒe dɔwɔwɔ | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 74 | menuLabels.Custodial Exchanges | Custodial Exchanges | Vidzikpɔkpɔ ƒe Asitɔtrɔ | OK |  |
| 75 | menuLabels.Zcash Use Cases | Zcash Use Cases | Zcash Zazã ƒe Nyawo | OK |  |
| 76 | menuLabels.Zcash Tech | Zcash Tech | Zcash Mɔ̃ɖaŋununya | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 77 | menuLabels.Privacy Tools | Privacy Tools | Dɔwɔnu Siwo Wozãna Ðe Ameŋunyatakakawo Ŋu | OK |  |
| 78 | menuLabels.Glossary & FAQ's | Glossary & FAQ's | Nyagɔmeɖegbalẽ & FAQ's | OK |  |
| 79 | menuLabels.Pay for AI | Pay for AI | Pay for AI | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 80 | menuLabels.Community Building | Community Building | Community Building | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 81 | menuLabels.Nym Mixnet Wallet Setup | Nym Mixnet Wallet Setup | Nym Mixnet Wallet Setup | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |

## Yellow coin menu (bottom right)
(`exploreMenu`: 15 labels)

| # | ID | English | Ewe | ✅ Confirmed | Notes |
|---:|---|---|---|---|---|
| 1 | exploreMenu.Full Explore | Full Explore | Dzro Nu Bliboe | OK |  |
| 2 | exploreMenu.Start Here | Start Here | Dze Egɔme Le Afi Sia | OK |  |
| 3 | exploreMenu.Tutorials | Tutorials | Nufiamewo | OK |  |
| 4 | exploreMenu.Using Zcash | Using Zcash | Zcash zazã | OK |  |
| 5 | exploreMenu.Guides | Guides | Mɔfialawo | OK |  |
| 6 | exploreMenu.Zcash Tech | Zcash Tech | Zcash Mɔ̃ɖaŋununya | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 7 | exploreMenu.Zcash Organizations | Zcash Organizations | Zcash Habɔbɔwo | OK |  |
| 8 | exploreMenu.Zcash Community | Zcash Community | Zcash Habɔbɔa ƒe Habɔbɔ | Zcash Habɔbɔ | This removes the repeated wording for ?community.? |
| 9 | exploreMenu.Privacy Tools | Privacy Tools | Dɔwɔnu Siwo Wozãna Ðe Ameŋunyatakakawo Ŋu | OK |  |
| 10 | exploreMenu.Research | Research | Numekuku | OK |  |
| 11 | exploreMenu.Glossary & FAQs | Glossary & FAQs | Nyagɔmeɖegbalẽ & Nyabiasewo | OK |  |
| 12 | exploreMenu.Contribute | Contribute | Dzɔ nu | Kpe ɖe ŋu | This short phrase expresses helping or contributing more directly. |
| 13 | exploreMenu.For Forks & Maintainers | For Forks & Maintainers | Forks & Dzadzraɖolawo | OK |  |
| 14 | exploreMenu.Fork zechub-wiki | Fork zechub-wiki | Gaflo zechub-wiki | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |
| 15 | exploreMenu.Fork zechub | Fork zechub | Fɔklɔ zechub | keep English | This is a specialised, branded, or context-sensitive label; keeping the familiar English wording is clearer than an unverified calque. |

## Side menu on article pages
(`sideMenu`: 2 labels)

| # | ID | English | Ewe | ✅ Confirmed | Notes |
|---:|---|---|---|---|---|
| 1 | sideMenu.navigation | Navigation | Tɔdziʋuɖoɖo | OK |  |
| 2 | sideMenu.explore | Explore | Tsa le eme | OK |  |
