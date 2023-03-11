The thought on this is to have a way for people to vote that can be trusted. It empowers the individual by letting them vote anonymously and securely.

Initially I'm thinking this is a no brainer for a blockchain app. Daniel Brr? may think otherwise, and he seems to have thought a ton about Digital IDs. We should speak to other people about how to prove identity. Part of this is going to end up being showing proof of personhood. This in it's self is a huge idea to tackle.

## The Vision
The initial vision of this project was to have a voting app for the 2024 US election. The app will not be connected to the official election. But it goes viral and both people on the left and right end up using it. One side will initially use it to say that their candidate obviously has more votes. The other side will scoff. Then they will realize that they can participate in it too, and they will co-opt it to get their team going. At some point the media picks up on this on both sides and the whole thing goes viral. The American (US) people (and possibly the world) end up realizing that they have a vote that is:
- anonymous yet verifiable
- Not controlled by any one group
- transparent: all votes can be seen, and the way they're counted and tallied is in the open.
- Flexible: The ballot can include different voting methods, from the electoral college (yuck), popular vote, ranked choice, etc. People could choose their voting methods
The election/poll is summarized on a website call it the [[ElectionView]], with an easy to understand graph (pie chart?). On this pie chart, you can zoom in and see individual votes, it's made up of hexagons, each one being a vote. If the user is signed in, they can go see their vote and the thing will zoom to their vote (google earth style) This is the joy of the thing, seeing your vote as part of a larger whole. When you click on your vote, you can decrypt it, verify it, change  it even.  The [[ElectionView]] is what ends up going viral in the media. There are no visible sponsors. Maybe we agree to take starter money from the Libertarian Party (maybe not). Eventually both red and blue teams start paying attention to development. It starts to make headway. By 2026 people are paying attention to it from the start, it's bigger, it's trusted more. 2028 and maybe some cities/network states are holding elections with this thing. People will realize that their ID is sovereign and that sovereignty will empower a new way of interacting with each other.  At some point, people realize that this is how they want government to be chosen, how it can function. There's some quote (Buckminster Fuller?) about how you don't tear down old systems, you build better ones. That's this project.

# Tasks
- [ ] Wireframe the mobile and desktop pages/apps
- [ ] Connect to blockchain
	- [ ] Understand onchain data structure of ballot \
	- [ ] Get identity trusted
- [ ] Start designing the actual Apps
- [ ] Test them
- [ ] Iterate
- [ ] Go public
- [ ] Iterate

## The App
The app is what people interact with on their phones/computers. It has to be easy to understand, easy to use. To start it has the following screens:
- [[ElectionView]]
- [[BallotView]]
- [[ProfileView]]
- [[OnboardingView]]

### Get the Vote Out
One idea is to have the app be a sort of 'get the vote out' app. In order to use the app, you have to be a registered voter. If you you're not registered, we can tell them where to go to get registered. The app will encourage voters. Well build a killer front end to it. Maybe take donations from different political parties, (not just libertarian)
Eventually people might trust it more than the actual system. We should be able to digitize the ballot in each county which will include the state and federal elections on it.

## The Crypto
Using the blockchain might be a mistake, we should talk to some people about DigitalIDs and if its possible to use some form of that along with a centralized database. But really, it seems like a crypto thing. We don't care about the chain it runs on, we can run it on different chains if we want.
For arguments sake, I'm going to explore using the ETH blockchain
### NFT ID
To start, each voter will have to claim they're registration by taking a selfie holding an ID and declaring there registered county. Maybe they provide a voter ID # if there is one. If not, we check the name/address on the ID with the voter registery. If the pair already exists, maybe we have another user look at the picture and verify it.  This could be an AI project later. But voter participation in the thing is even better. If a voterID# is already spoken for, extra in person verification is needed and the NFT is given to the address of the person with the best verification. This allows people to lose their seed, and just re-register. Some friction to it, but that's the cost of being verified. It adds some friction against voter fraud.
The only thing stored is the voterID, and it is encrypted within the user account, verifiable by the holder if wanted.

[[BallotObject]]


### The Election
An election is just a collection of sections of  ballots. The date/time of the election the ballots are counted from a snapshot of the chain at that time.
There can be multiple elections off of a single ballot. Each just being a different way of counting the ballot, such as popular vote, electoral college vote.
Some elections will require different ballots completely, such as ranked choice. They will be counted differently, and even display different information in different ways (imagine an animated view of a ranked choice ballot)\

### Conversation
The thing should have a way to tie into a social network
point is to have a conversation about why people are voting certain ways


### Holding Representatives Accountable
One view in the app shows local representatives and their voting history. There's a button to contact the representative (phone, email, twitter, etc) Representives have a verified ID of course, and they can sign their own stances on issues.