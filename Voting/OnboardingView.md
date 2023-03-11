This is part of the [[Voting Project]]
In order to vote, users must be verified that they are eligible to vote. This is very tricky.
The onboarding view will have to interact with their governmentID, and convey a sense of security that the information is safe and encrypted. Also that it's verified. If this thing works, the second thing that's going to happen is state actors are going to try to spin up thousands/millions of fake voters to fuck with the election.  Once a user is onboarded and their information verified, they go to the [[ProfileView]]

### Verification
I believe that registered voter databases are public.
Initially a user can specify their name/DOB and we find it in a voter database. 

If we tie a verification level to a voterID, votes can be filtered by verification level

A notary could issue votingID NFT that's in a multisig wallet so if people lose their IDs, they can reclaim their vote and tie it to a new wallet if needed.

#### Verification Levels
No Verification (global participation)
Name/DOB matches a record in a State/county voter registration database(us only)
Name/DOB matches record, and a paid notary issues the NFT.

### Wallet
In my initial take, there is a wallet built into the app, with a seed phrase. Users can back up their seed phrase, but if they lose it, they can visit a notary and get assigned a new voting NFT. A new seed would be generated at this time.
The seed phrase could be used to store crypto, but that's not the point of the app. The app uses the wallet only for ID verification and vote signing. For now the wallet aspect is hidden from the user. It's just a cool voting app that they had to work a little to get trusted with.
