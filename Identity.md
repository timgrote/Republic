Identity is one of the main problems to tackle with the [[Voting Project]] along with 
the [Circle/Logos/The Forum](https://substack.com/app-link/post?publication_id=567953&post_id=106913228&isFreemail=true&token=eyJ1c2VyX2lkIjoxMDY1OTQ0LCJwb3N0X2lkIjoxMDY5MTMyMjgsImlhdCI6MTY3ODMwMjcxOSwiZXhwIjoxNjgwODk0NzE5LCJpc3MiOiJwdWItNTY3OTUzIiwic3ViIjoicG9zdC1yZWFjdGlvbiJ9.yhyHgQolTxghUK2EXog3x1JPbstKiDGRr5eJLVJ2LlM) 

#### Reading
- [Hacker News Thread](https://news.ycombinator.com/item?id=35095063)
- https://www.w3.org/TR/did-core/
- https://www.w3.org/TR/vc-data-model/
- https://identity.foundation/
- https://www.ndss-symposium.org/ndss-paper/private-certifier-intersection/

# Trust
My current thesis is that similar to providing power to the individual over the collective. Identity is best verified locally then trusted more widley from there.

To start, let's get a basic level of a Verified Registered Voter:
- Have a gov issued ID
- Are in a state/county database of registered voters. [Example](https://www.sos.state.co.us/voter/pages/pub/olvr/findVoterReg.xhtml)

A trusted [[Notary]] could vouch that they witnessed both the person show the ID, and looked up the ID in the database. They could then issue a token to the voter, that they've been verified. The token is sent to a crypto wallet. The voter doesn't need to know about the wallet, they just need to be able to sign stuff. 

If a user loses their phone, or their private key, they can go see the Notary again, and the Notary will re-issue TheToken to the individuals new public address. The users name, DOB, and VoterID could possibly be encrypted in the TheToken, with the private key able to decrypt it. The private key/seed could be generated at the time of verification. 

> [!Important]
> The private seed/key is not generated by the Notary, it is the innate right of the individual to generate a new seed/keypair. It is the (government/circle's) right to issue that individual a verification token 

I would accept a user verified by this method as a proof of personhood.

Yes it could be spoofed, but I think I would accept this level of verification for voting purposes. 

TheToken is issued by a trusted circle (collecion of public keys) 

A republic trusts the states that comprise it. 
The states trust the other states in the republic 


An identity holds [[Reputation]]


It is also useful for 

## Crypto
Crypto in the math sense
Most people trust math. If a tweet, or photo or video is signed with a private/public keypair,  signed, that can be cryptographically verified by all. Via Math. Let's take that as a starting place. 

## Proof of Personhood
Keypairs can be controlled by computers or people. 
AI can control a set of keys, but for now cannot control others keys.
A public address holding a verified VerifiedRegisteredVoterToken(TheToken) is proof of personhood without the [burden of biometric data being included.](https://worldcoin.org/privacy) This could be useful in social media.
It could also be useful to reset passwords other accounts. (danger lies here)


