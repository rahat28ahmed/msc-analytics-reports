# Agentic AI for Promotional Stock Replenishment

Individual business report for Digital Economy, Tools and Techniques, MSc Business Analytics, University of Greenwich, 2025–26. Lunex UK is the case-study company set for the assignment.

## Question

Lunex UK runs 320 supermarkets. When a promoted product sells faster than forecast, it takes about three hours for an order to reach the supplier, by which time the shelf is empty. The report puts the cost at £2.5 to £3 million a year in lost promotional revenue and asks whether an agentic AI system could close that gap safely.

## Approach

1. Mapped the constraints: five disconnected systems synchronising every 45 minutes, manual approval for orders above £1,500, a 35% rate of store managers overriding automated reorder suggestions, 180 suppliers on different ordering platforms, and EU AI Act audit obligations for the 40 EU-based suppliers.
2. Compared enhanced rule-based ERP automation, a predictive analytics upgrade and an agentic AI system. Only the agentic system acts on the shortage rather than just detecting it.
3. Specified an event-driven agent that activates only when a promoted product sells more than 20% above forecast within the first four hours. It checks stock, confirms supplier availability, places orders under £1,500 and logs every step.

## Recommendations

- Replace the 45-minute batch cycle with a real-time data pipeline before deploying any agent.
- Build in safeguards from the start: a £1,500 spending limit, safe termination when data is inconsistent, escalation to a manager within 30 minutes, and audit logs aligned with the EU AI Act.
- Use three governance tiers (restricted, monitored, trusted), with alcohol, regulated pharmaceuticals and cross-border imports kept under human control.
- Roll out over 18 months: foundations, then a 20-store pilot, then 150 stores, with the full 320 stores projected by month 24.
- Address the override rate by involving store managers in setting the agent's thresholds and escalation rules.

The projected benefit is a 15 to 20% reduction in lost promotional revenue, about £400,000 to £600,000 a year, against an implementation cost of roughly £1.1 to £1.4 million, which gives a payback period of around 24 to 30 months.

## Limitations and Risks

- During the move to real-time data the agent could act on outdated information and place incorrect orders.
- The 35% override rate suggests cultural resistance will take time to resolve.
- EU AI Act compliance is an ongoing cost rather than a one-off.
- The figures depend on the case-study data and published industry estimates.
