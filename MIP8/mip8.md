# MIP8: Domain Greenlight

## Preamble
```
MIP#: 8
Title: Domain Greenlight
Author(s): Charles St.Louis (@CPSTL), Rune Christensen (@Rune23)
Contributors: @LongForWisdom, Leo Jsaraceno (@Mitote), Helge Andreas Qvam (@planet_X)
Type: Process
Status: Request for Comments (RFC)
Date Proposed: 2020-04-06
Date Ratified: <yyyy-mm-dd>
Dependencies: MIP7, MIP9
Replaces: n/a
```
## References
No referenced materials.

## Sentence Summary

MIP8 defines the process by which domain teams signal that a potential collateral type is worth the time spent investigating its inclusion in the Maker Protocol.

## Paragraph Summary

This proposal aims to define the process where at least one domain team from each domain (Risk, Smart Contracts, Oracles, Legal, etc) "Greenlights" the collateral type (based on research) in order for the collateral onboarding process to proceed.

## Component Summary

**MIP8c1: Domain Greenlight Process**  
Defines the domain greenlight process and its interaction with the collateral onboarding process.

**MIP8c2: Domain Greenlight Outcomes**  
Defines the possible outcomes from the domain greenlight process.

**MIP8c3: Domain Greenlight Requirements**  
Defines the responsibilities of the domain teams in the domain greenlight process.

## Motivation

The goal of this proposal is to inform the community about the pre-evaluation stage with the aim of identifying any show-stopping problems before time is spent on a full evaluation of the collateral type.

## Specification / Proposal Details

### MIP8c1: Domain Greenlight Process
- For an asset to be onboarded to the Maker Protocol, domain work must be provided from risk, oracle, smart contracts and optionally legal domain teams. Domain greenlight is the process through which domain teams signal their willingness to work on a collateral asset.
- The domain greenlight process occurs after a proposed collateral asset has passed a MIP9 Community Greenlight Poll.
- If any domain team signals unwillingness to work on a collateral asset, it does not mean that the asset will never be included as collateral in the Maker Protocol.
- If at least one domain team from the risk, oracle and smart contracts domains do not greenlight a collateral type, the onboarding process awaits alternative domain teams willing to perform the domain work. 

#### Overall Process Overview Diagram

<img width="822" alt="mip8-diagram" src="https://user-images.githubusercontent.com/32653033/79890509-9637e000-83cd-11ea-8078-7fcaac410a51.png">

---

### MIP8c2: Domain Greenlight Outcomes

**Greenlit**  
- If **greenlit**, the domain team has signaled their willingness to do the work required to add the collateral asset to the Maker Protocol.

**Deferred**  
- **Deferred** status signals that the domain team is willing to do the work required to add the collateral asset to the Maker Protocol provided certain criteria are met.
- Resumption criterion must be defined and communicated clearly by the domain team on the official forum.
- Until all **deferred** criteria are met, the deferring domain team will not proceed with the work required to add the collateral asset to the Maker Protocol.

**Rejected**  
- **Rejected** status signals that the domain team is unwilling to do the work required to add the collateral asset to the Maker Protocol.
- Optionally, the domain team may provide a reason for this rejection. 

### MIP8c3: Domain Greenlight Requirements

- Communication from domain teams regarding domain greenlight must come within two weeks of the end of the MIP9 Community Greenlight poll on the official forum.
- A domain team should aim to signal their greenlight outcome within two weeks of the end of the MIP9 Community Greenlight poll.
- If a domain team is not able to signal their greenlight outcome then they must do the following before the target date passes:
	- Post a reason for the delay on the official forum.
	- Post a new target date for communicating their domain greenlight outcome on the official forum.
- If subsequent dates will be missed, communication should be provided before the deadline passes, and should include a new target date. 
- If new information becomes available that changes the assessment of a domain team, they can modify their greenlight by posting on the official forum at any time.
- If a **deferred** outcome is given, resumption criteria must be provided.
- If resumption criteria from a **deferred** outcome are met, the greenlight outcome should be modified to **greenlit**.

---


    

