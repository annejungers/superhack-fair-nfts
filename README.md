# superhack-fair-nfts

# PROBLEM
Royalties on secondary sales are a new way that creators can benefit from their work. Typically the value of a creator's work accrues over time, and in the past, the creator has got little benefit. This benefit went to intermediators instead. This is something that the blockchain tries to eliminate.

The blockchain allows royalties to be encoded in a smart contract. This has become a common feature of NFTs. However, it cannot be enforced in smart contracts and is up to the marketplace whether to observe the creators wishes.  Many marketplaces enforce royalties, but plenty do not. Over-the-counter trades, also prove a problem.

Those marketplaces that do enforce royalties use various strategies that are designed to capture buyers and creators at the cost of interoperability and fair competition. Standardisation is a solution, but will only come with social and market pressue.

Many members of the crypto community also argue that enforcement is also against the ethos of the movement. Our position is that there can be a choice: a creator can chose not to ask for a royalty, however the choice to ignore the wishes of a creator should come with other costs. 

# APPROACH
This project will use various techniques to surface and highlight to buyers and creators the way in which NFTs have been traded, and the degree to which royalies have been paid.

It is expected that this will tend create a bifurcation in the market between those that care about profit more than the creation itself. Some creations will naturally fall into the 'flipper' category and traded for nothing other than expectation of profit. Others will appeal to holders who keep them more for their artistic merit, collectability or some accrued benefit. 

It is our thesis that exposing and highlighting the history of royalties for an NFT will improve the desirability of those with a cleaner record. This will likely flow through to price, counterbalancing the royalty in some way.

The solution will therefore incentivise payment of royalties by:
    • Creating a stigma around unpaid royalties and a social norm that they should be paid, 
      so that there is a value differential in price that counterbalances the royalty cost.
    • Exposing the royalty payment status at point of sale
    • Highlighting cases where the royalty has not been paid
    • Exposing suspiciously low prices (over the counter side-payments)
    • Examining and creating standards that can be used by creators to make avoidance difficult
    • Exposing attempts to avoid payment using various techniques such as wrapping
    • Allowing users to transfer between wallets without being classified as an over-the-counter trade with unpaif royalties.

# PROJECT STREAMS

## Research
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

## Exposing royalty history
A general portal that allows the buyer to check everything that has happened to an NFT. This is might be a summary 'Fair-trade' score as well as a list of events ordered by time. Where each transfer might be annotated with:  
    • Royalty status - paid/unpaid/unknown
    • Marketplace info (if known)
    • Avoidance strategies (eg wrapping) 
    • Transfers between a users's own wallets

A portal feature allowing an attestation to be attached to an NFT. This can be viewed our portals as well as supporting marketplaces.

A creator portal focussed on showing the creator how their creations are traded, which marketplaces, what royalties are being paid or otherwise, etc.

## Highlighting royalty avoidance
Unanswered questions:
    • Who invokes the process?
    • Is the result stored onchain?
    • Is it a DAO?
    • who would want to be a member of the DAO, 
    • what's the incentive? 
    • Who pays? 

MOVING NFT BETWEEN WALLETS
Proof of Same Human (PoSH):
Use Worldcoin to detect the case where a an owner has moved an NFT to another wallet that they own.  I.e. owner of sender and receiver is proves that they are the same person.

Proof of Rugability (PoR):
The receiving user proves that they can be rugged by the sender. In this way, it is unlikely the receiver would perform the transaction unless they are the same person, close friend, family member, or it is a gift.

CREATE ERC STANDARDS
Define an interface that allows anyone to find out the royalty status of an NFT.
Consider:
    • Is it positive (ie a reputation)?
    • Is it negative (inverse reputation)?
    • Is it boolean, tri-state or scalar?
Define a way to register a proof of royalty payment.
Consider:
    • Is it way to pay and set the status?
    • Is it a way to register the payment transaction, the royalty transaction 
Define how the status gets set
    • who sets it?
    • how does it get set?
    • can it be appealed?
    • A DAO....?
Define a convention for showing the royalty status on a marketplace
    • A trait?
    • Other method?
