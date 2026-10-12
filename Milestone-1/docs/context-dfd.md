# PearlMart Level 0 Context DFD

## Main Process

The context diagram shows one process: **0 PearlMart Inventory Management System**. It represents the entire system as a single process, without internal data stores.

## External Entities

The diagram has four external entities:
- **Employee**
- **Customer**
- **Supplier**
- **Manager (inventory/store)**

The Employee and Manager entities are shown separately in this version of the diagram.

## Data Flows

The directions below are recorded from the submitted Level 0 diagram.

| External Entity | Data Sent to PearlMart System | Data Received from PearlMart System |
|---|---|---|
| Employee | Login credentials; Password change details; Inventory update details; Expired goods records request; Expired item removal details; Item search details; Sale cancellation request | Authentication Result; Inventory action result; Expired goods list; Item search results; Cancellation confirmation |
| Customer | Purchase item details; Replacement item details; Unavailable item request | Purchase receipt; Replacement request decision; Unavailable item request confirmation |
| Supplier | Supplier invoice; Goods delivery information | Order details |
| Manager (inventory/store) | Supplier order details; Received goods verification; Request to review customer requests; Report type | Received goods details; Customer requests list; Summary report |

## System Boundary

All four external entities exchange information with the single PearlMart Inventory Management System process. The diagram does not show the system's internal processes or data stores. Supplier operations remain outside the system.

## Diagram

[View the actual Level 0 Context DFD screenshot attached to Issue #2](https://github.com/sa2305215/PearlMart-MileStone1/issues/2#issuecomment-6127326275).

## Review Notes

This document describes the **submitted screenshot**, rather than a revised or proposed diagram. Before final submission, confirm whether **Manager (inventory/store)** should be represented through the general **Employee** entity, following the instructor's clarification. Also check balancing with the Level 1 DFD. Any resulting diagram changes should be reflected in this document and the final Visual Paradigm file.
