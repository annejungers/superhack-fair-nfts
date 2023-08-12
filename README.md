# superhack-fair-nfts

# PROBLEM
Royalties on secondary sales are a new way that creators can benefit from their work. Typically the value of a creator's work accrues over time, and in the past, the creator has got little benefit. This benefit went to intermediators instead. This is something that the blockchain tries to eliminate.

The blockchain allows royalty expectations to be encoded in a smart contract. This has become a common feature of NFTs. However, it cannot be enforced in smart contracts, so it is up to the marketplace whether to observe the creators wishes.  Many marketplaces enforce royalties, but plenty do not. Over-the-counter trades and side-payments also prove a problem.

Those marketplaces that do enforce royalties use various strategies that are designed to capture buyers and creators at the cost of interoperability and fair competition. Standardisation is a solution, but will only come with social and market pressue.

Some members of the crypto community argue that enforcement is against the ethos of the movement. Our position is that there can be a choice: a creator can chose not to ask for a royalty and the buyer has the choice not to buy, and in some cases, or not to pay the royalty. However, the choice to ignore the wishes of a creator should come with other costs. 

# APPROACH
This project will use various techniques to surface and highlight to buyers and creators the way in which NFTs have been traded, and the degree to which royalies have been paid.

It is expected that this will tend create a bifurcation in the market between those that care about profit more than the creation itself. Some creations will naturally fall into the 'flipper' category and traded for nothing other than expectation of profit. Others will appeal to holders who keep them more for their artistic merit, collectability or some accrued benefit. 

It is our thesis that exposing and highlighting the history of royalties for an NFT will improve the desirability of those with a cleaner record. This will likely flow through to price appreciation, counterbalancing the royalty costs in some way.

The solution will therefore incentivise payment of royalties by:
    • Creating a stigma around unpaid royalties and a social norm that they should be paid, 
      so that there is a value differential in price.
    • Exposing the royalty payment status at point of sale.
    • Highlighting cases where the royalty has not been paid.
    • Exposing suspiciously low prices (over-the-counter side-payments).
    • Examining and creating standards that can be used by creators to make avoidance difficult.
    • Exposing attempts to avoid payment using various techniques such as wrapping.
    • Allowing users to transfer between wallets without it being classified as an over-the-counter trade with unpaid royalties.

# PROJECT STREAMS

### Research
Locate all the market places and identify whether they:
    • enforce
    • don't enforce
    • allow users to choose
    • use ERC2981
    • use some other standard
    • what standard?
Examine ERC standards and other proposals that could be of advantage in encouraging or enforcing royalities.
Examine ways of assigning reputation to an NFT. Eg
    • certifications or attestations
    • onchain or provable offchain reputation records

### Exposing royalty history
A general portal that allows the buyer to check everything that has happened to an NFT. This is might be a summary 'Fair-trade' score as well as a list of events ordered by time. Where each transfer might be annotated with:  
    • Royalty status - paid/unpaid/unknown
    • Marketplace info (if known)
    • Avoidance strategies (eg wrapping) 
    • Transfers between a users's own wallets

A portal feature allowing an attestation to be attached to an NFT. This can be viewed on our portals as well as supporting marketplaces.

A portal feature allowing a motivated person, to 'clean' the NFT by compensating for unpaid royalties.

A creator portal focussed on showing the creator how their creations are traded, on which marketplaces, what royalties are being paid or otherwise, etc.

### Highlighting royalty avoidance
Unanswered questions:
    • Who invokes the process?
    • Is the result stored onchain?
    • Is it a DAO?
    • who would want to be a member of the DAO, 
    • what's the incentive? 
    • Who pays? 

### Enforcement strategies
While it is not possible to prevent avoidance of royalties, it is possible to make it difficult and easily observed. By standards or widely adopted conventions, avoidance strategies can be highlighted and contribute a bad reputation.

Define a standard method which allows anyone to find out the royalty status of an NFT.
- onchain extension to ERC721?
- offchain?

Define a standard way to register a proof of royalty payment.
Consider:
    • Onchain or offchain?
    • Is it way to pay and set the status?
    • Is it a way to register the payment transaction, the royalty transaction 

Define how the royalty status can be honestly recorded for historical transactions.
    • who sets it?
    • how does it get set?
    • can it be appealed?

Define a convention for signaling the royalty status to a marketplace
    • A trait?
    • Attestation
    • Other method?

### The multiple wallet problem
The problem of "moving NFTs between a holder's wallet" is often quoted as the reason that onchain enforcement is impractical. This is only true if there is no way to remove the stigma, or signaling that a transfer not a sale. To achieve this a couple of strategies can be expored:

#### Proof of Same Human (PoSH):
Using Worldcoin or sybil-detection system, a holder can prove that the sender (current owner) and receiver in a transfer are the same real person.

#### Proof of 'rugability' (PoR):
No rational buyer would trade with seller if it is possible for the seller to 'rug' (effectively double-spend) the NFT. Therefore trading in such away is a signal that is complete trust between the parties.  An observer can have a high level of confidence that the seller and buyer are the same person, family or that the NFT was gifted.
The challenge is then to design a standard protocol where the receiver provides a means by which the sender can reverse the transaction. In addition this protocol must be observable, such that it can be used to allow non-payment of royalies without reputational damage to the NFT.
