A vote is a [[BallotObject]] with choices(or [[Race]]s) filled in (or not) and signed by a voter. Part of the [[Voting Project]]

My understanding is that the way to store this on a blockchain, would be to compress it and store it on a chain. In order to do this we need to find a way of storing the ballot either in a user signed transaction (as the data)

### On Chain Storage of Votes
Possible ways to store votes on chain
- Compress each ballot and store it as data in a signed transaction onchain
- Some combination of NFTs (sounds complex and expensive)
- need to research how DAOs are counting votes, including Cardano and ETH


One possible way to compress/store a vote is to have a pointer to a ballot, and list of choices for or against (0 or 1) on measures, or a candidateID for candidate votes. Then the only things actually stored are the results of the vote, and not all possible choices of the ballot.