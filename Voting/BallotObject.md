### The Ballot
Once a user is verified, the app will display a [[BallotView]] for the county they're in. This ballot is identical to the county ballot.  
There will also be alternative ballots, for alternative election counting methods.
The ballot can be stored as a JSON object Something like:

```json
{
  "county": "Example County",
  "state": "Example State",
  "ballot_measures": [
    {
      "title": "Proposition 1",
      "description": "Shall the county increase the local sales tax by 1% to fund road repairs?",
      "choices": [
        {
          "label": "Yes",
          "value": 1
        },
        {
          "label": "No",
          "value": 2
        }
      ]
    },
    {
      "title": "Proposition 2",
      "description": "Shall the county issue bonds to build a new courthouse?",
      "choices": [
        {
          "label": "For",
          "value": 1
        },
        {
          "label": "Against",
          "value": 2
        }
      ]
    }
  ],
  "state_offices": [
    {
      "office": "Governor",
      "candidates": [
        {
          "name": "John Smith",
          "party": "Republican"
        },
        {
          "name": "Jane Doe",
          "party": "Democratic"
        },
        {
          "name": "Justin Amash",
          "party": "Libertarian"
        }
      ]
    },
    {
      "office": "Senator",
      "candidates": [
        {
          "name": "Alice Brown",
          "party": "Democratic"
        },
        {
          "name": "Tom Green",
          "party": "Republican"
        },
        {
          "name": "Sarah White",
          "party": "Libertarian"
        }
      ]
    }
  ],
  "federal_offices": [
    {
      "office": "Representative",
      "district": 1,
      "candidates": [
        {
          "name": "Mike Black",
          "party": "Democratic"
        },
        {
          "name": "Jim White",
          "party": "Republican"
        }
      ]
    },
    {
      "office": "Senator",
      "candidates": [
        {
          "name": "Susan Brown",
          "party": "Democratic"
        },
        {
          "name": "Jack Green",
          "party": "Republican"
        },
        {
          "name": "Dave Smith",
          "party": "Independent"
        }
      ]
    }
  ]
}

```

Note that the BallotObject is just a collection of choices or [[Race]]s. Once a voter makes those choices, it is stored as a [[Vote]] on the blockchain


In this way, a certified county ballot (verified by notary in that county) can contain votes in a 
- Presidential Race
- State Governer Race
- Etc.

This points to identity being verified locally, and trustable by a Federal(Republic) level