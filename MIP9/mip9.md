# MIP9: Community Greenlight

## Preamble
```
MIP#: 9
Title: Community Greenlight
Author(s): Rune Christensen (@Rune23), Charles St.Louis (@CPSTL)
Contributors: @LongForWisdom, Leo Jsaraceno (@Mitote), Helge Andreas Qvam (@planet_X)
Type: Process
Status: Request for Comments (RFC)
Date Proposed: 2020-04-06
Date Ratified: <yyyy-mm-dd>
Dependencies: MIP6
Replaces: n/a
```

## References
No referenced materials.

## Sentence Summary

MIP9 defines the process by which MKR Token Holders can signal their judgment on the value of a potential collateral type before domain teams spend time thoroughly investigating its inclusion into the Maker Protocol.

## Paragraph Summary

This proposal aims to standardize the process for allowing MKR Token Holders to inform the Domain Teams of their preferences for collateral types that have been proposed through MIP6. The preferences of the MKR Token holders are expressed in the form of an on-chain governance poll. The governance poll (Greenlight poll) runs at the end of the governance cycle and will run for a period of two weeks.

## Component Summary

**MIP9c1: The Community Greenlight Process**  
Defines the community greenlight process and its interaction with the collateral onboarding process.

**MIP9c2: The Community Greenlight Outcomes**  
Defines the possible outcomes from the community greenlight process.

**MIP9c3: The Community Greenlight Requirements**  
Defines the resposibilities of the Governance Facilitators in the community greenlight process. 

**MIP9c4: Community Greenlight Poll Template**  
Defines a governance poll template to be used in the on-chain Community Greenlight poll.

## Motivation

While domain teams are free to choose their own workload, an on-chain governance poll provides the Domain Teams key insights into the community's sentiment for each collateral type that has been proposed. In addition to this, it is important to gather the opinion of MKR Token Holders towards the proposed collateral asset before the full domain work takes place. This helps prevent work from being wasted on undesirable collateral types.


## Specification / Proposal Details

### MIP9c1: The Community Greenlight Process
- For an asset to be onboarded to the Maker Protocol, it must pass a MKR vote. Community greenlight is the process through which early sentiment is measured and used to direct the work of domain teams towards assets that MKR Holders will be willing to onboard after work has been completed.
- The community greenlight process for a potential collateral asset consists of an on-chain governance poll using the template defined in MIP9c4. 
- The community greenlight polls occur at a fixed time each governance cycle, starting on the 4th Monday of the month and running for a period of 2 weeks.
- A potential collateral asset is valid for a community greenlight poll if it has a MIP6 Application that has been published on the official forum for a period of of 2 weeks prior to the community greenlight poll start date.

### Overall Process Overview Diagram

<img width="686" alt="mip9" src="https://user-images.githubusercontent.com/32653033/79087697-23b06b80-7d0e-11ea-8411-82d6b4f0a0e5.png">

### MIP9c2: The Community Greenlight Outcomes
**Greenlit**  
- The community greenlight poll for the potential collateral asset ends with more **greenlight** votes than **rejected** votes.
- The potential collateral asset is marked as having been **greenlit** by the community.
- Domain teams may feel confident in allocating time to work on the potential collateral asset.
- Potential collateral asset is now eligible for the domain greenlight process defined in MIP8.

**Rejected**  
- The community greenlight poll for the potential collateral asset ends with more **rejected** votes than **greenlight** votes.
- The potential collateral asset is marked as having been **rejected** by the community.
- Domain teams may still choose to work on a collateral type that has been **rejected** if they are confident that governance will approve future inclusion.
- Community greenlight polls for assets that have been **rejected** can be rerun in the future at the discretion of the Governance Facilitators.

### MIP9c3: The Community Greenlight Requirements
- The Governance Facilitators are responsible for creating a Community Greenlight Poll for each valid potential collateral asset each month.
- If a previously rejected potential collateral asset is included in the monthly greenlight polls a reason must be communicated to the community via the official forum before the greenlight poll takes place.
- The Governance Facilitators are responsible for maintaining a list of collaterals based on the outcome of the individual Community Greenlight Polls. This list should include collateral types that have both passed and failed to pass their Community Greenlight Polls.
- At the Governance Facilitators discretion community greenlight polls may be deferred to later months.
- If the Governance Facilitators opt to defer community greenlight polls a reason must be communicated to the community via the official forum before the greenlight poll takes place.

---
### MIP9c4: Community Greenlight Poll Template 

In this template, the asset ETH is used as an example. 

Additional informational material or reference links may be added to the poll content at the discretion of the Governance Facilitators.

**Poll Title**  
MIP9 Community Greenlight Poll: ETH (Ether)

**Description**  
If greenlight votes exceed reject votes, this poll is to be taken as a signal to domain teams that MKR Token Holders have approved further domain work with the aim of adding ETH (Ether) as a collateral asset to the Maker Protocol.  

**Duration**  
2 weeks

**Poll Options**  
Greenlight  
Reject

---
