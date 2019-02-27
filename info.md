Project Name
RToken Quorum, a Permissioned Security Token Platform

Project Tagline/Description
A token issuance and trading platform combining the open source R-Token compliance standard for digital securities with the institutional grade privacy features of the Quorum blockchain.

Security token platform leveraging the R-Token protocol and Quorum for global regulation while preserving issuer and transaction privacy.

Team Members. First and Last Names
Elena De La Paz Ryan Hall Shane Jarvie

Status.im ID for Each Team Member (we will use this to contact you and your team)
Shane Jarvie: 0x0476d5181718958bac93bb8b833243f4cf1e7fd1b5b7ee96687fb34a0734fcf836181247dd7e358ed6fcf87757323a62e84a10a8c5833c1313f280d9bc42656eb6

Ryan Hall 0x0488256c54f35afccd98354363da60c3f1360d2dedfc4034dc3f9acaf8e67256c3bef431c3a0aa4ee3afe297d1bfbe11900cfc30c01650426927156d79cbe17c59

Elena De La Paz 0x042ad1b418586a598a2e8dc623efa9e016828688d5f764a9103eb13944ef129db8693d44c3f3194d99b09a32f701d3e64eeb0fe590feefb87c607696ae0f33a2ec

Detailed Project Description (no more than 3-4 sentences)
A permissioned security token standard which enables global issuance and trading of ERC20 digital assets compliant with offering and investor level regulation , while providing issuers with fined grained privacy controls and minimal exposure of underlying investor transaction data.

For the compliance aspect, we used the leading open source ERC20 security token standard, the R-Token, a RegulatedToken that checks the validity potential transfers against a RegulatorService. This R-Token then leverages the Quorum privacy platform by allowing issuers to share knowledge of state while remaining agnostic to each other's trades.



We deploy a RegulatorService contract which is private to nodes owned by the regulator and issuers of R-Tokens. The issuer-specific R-Token contracts and state are private to only the issuer and regulator, meaning though two issuers can share knowledge of investors essential to ensuring legal compliance, they will not be aware each other's issuances and secondary trades.

This allows for issuers to only view their own token balances and state, while querying a global regulator service when attempting to make a transaction, and for no public entity outside of the regulator to be able to view all issuer transactions.



Describe your tech stack (e.g., protocols, languages, API’s, etc.)
Quorum, Solidity, React, Docker

Track for which you’re submitting (Open or Impact)
Open

All Bounties Completed/Incorporated
Quorum Sponsor Bounty #2: Privacy
