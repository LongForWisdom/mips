# MIP4: MIP Amendment and Removal Process

## Preamble
```
MIP#: 4
Title: MIP Amendment and Removal Process
Author(s): Rune Christensen (@Rune23), Charles St.Louis (@CPSTL)
Contributors: @LongForWisdom
Type: Process
Status: Request for Comments (RFC)
Date Proposed: 2020-04-06
Date Ratified: <yyyy-mm-dd>
Dependencies: n/a
Replaces: n/a
  ```

## References
**[MIP4c2-Subproposal-Template.md](MIP4c2-Subproposal-Template.md)**  
**[MIP4c3-Subproposal-Template.md](MIP4c3-Subproposal-Template.md)**  

## Sentence Summary

MIP4 defines processes for the amendment and removal of accepted MIPs.

## Paragraph Summary

MIP4 contains two process components which define both the MIP amendment and MIP removal processes. The first allows for making small and relatively superficial changes to accepted MIPs. The second allows for the removal of accepted MIPs that Maker Governance veiws as no longer desireable. 

## Component Summary

**MIP4c1: Purpose Description**  
Suggests the purpose of the amendment and removal processes and possible reasons for using each process.

**MIP4c2: MIP Amendment Process**  
A process component which defines a method and template for the amendment of one or more accepted MIP.

**MIP4c3: MIP Removal Process**  
A process component which defines a method and template for the removal of one or more accepted MIP.

## Motivation

The motivation behind this proposal is that changing small details to MIPs should not require the original MIP to become obsolete or replaced, so this MIP is needed to define and outline the process behind making these changes to MIPs once they have been accepted. Additionally, this MIP defines the process for the removal of MIPs that are have become no longer useful.

## Specification / Proposal Details

### MIP4c1: Purpose Description

**Amendments**  
MIP Amendments that preserve the MIP number can be performed as long as there are no changes to the purpose of the MIP or to the MIP's external output dependencies. They should only be used when minor changes are required. 

**Validity**  
The validity of MIP Amendments is ultimately up to the community but possible reasons for amendments could be (but are not limited to): 
-  A formatting change
-  Typos
-  Rewording/clarification

MIP Amendments are invalid if, based on the assessment of the community, the changes are so severe that they should be achieved through a MIP replacement instead.

**Removals**  
MIP4 also enables the removal of Accepted MIPs. This process should be used where a MIP has outlived its usefulness.
    
---
### MIP4c2: MIP Amendment Process 

MIP4c2 is a Process MIP component that allows the amendment of an Accepted MIP using a subproposal. MIP4c2 subproposals have the following parameters:
- **Default Feedback Period**: 3 months
- **Frozen Period**: 1 month

MIP4c2 subproposals must use the template located at  **[MIP4c2-Subproposal-Template.md](MIP4c2-Subproposal-Template.md)**. This template is considered ratified once this MIP moves to Accepted status.

MIP4c2 sub-proposals should be limited to a single MIP, or limited to a single change. If one of these conditions is not met, the sub-proposal is considered invalid.

---
### MIP4c3: MIP Removal Process 

MIP4c3 is a Process MIP component that allows the removal of an Accepted MIP using a subproposal. MIP4c3 subproposals have the following parameters:
- **Default Feedback Period**: 3 months
- **Frozen Period**: 1 month

MIP4c3 subproposals must use the template located at  **[MIP4c3-Subproposal-Template.md](MIP4c3-Subproposal-Template.md)**. This template is considered ratified once this MIP moves to Accepted status.

If there are other MIPs that depend on a MIP that is being removed, they must either be removed within the same sub-proposal, or replaced or amended during the same governance cycle. If these conditions are not met, the sub-proposal is considered invalid.

---
