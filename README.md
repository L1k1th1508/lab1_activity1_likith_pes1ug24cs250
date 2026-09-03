# lab1_activity1_likith_pes1ug24cs250
# Academic elective bidding and allocation system
## Repository Contents

| File | Description |
|---|---|
| [`Academic_Elective_Bidding_Requirements_Table.xlsx`](./Academic_Elective_Bidding_Requirements_Table.xlsx) | 5 Functional Requirements (FR-001–FR-005) and 2 Non-Functional Requirements (NFR-001, NFR-002), each with Req ID, Type, Description, Priority, Acceptance Criteria, and Rationale. |
| [`uml_diagram_academicelective biddingandallocaionsystem.pdf`](./uml_diagram_academicelective%20biddingandallocaionsystem.pdf) | UML Use-Case Diagram showing all actors, primary use cases, and at least one `«include»` and one `«extend»` relationship. |
| [`UseCase_Flow_UC01.docx`](./UseCase_Flow_UC01.docx) | One-page Use-Case Flow Specification for the core use case *Submit Elective Bids*, detailing Preconditions, Postconditions, Main Success Scenario, and Alternate Flow(s). |

## Use-Case Summary

- **UC-01** Submit Elective Bids *(includes UC-02)*
- **UC-02** Validate Prerequisites & Credit Limit
- **UC-03** View Bid Status
- **UC-04** View Final Elective Allocation
- **UC-05** Configure Elective Catalog & Bidding Window
- **UC-06** Run Allocation Solver *(extended by UC-07)*
- **UC-07** Manually Resolve Allocation Conflict

## Key Requirements

- **FR-001:** Distribute 100 bidding credits across ranked preferences with prerequisite validation.
- **NFR-001:** Allocation solver processes 5,000 student bids and resolves conflicts in under 30 seconds.

## Tools Used

UML modelling: Draw.io / Lucidchart
