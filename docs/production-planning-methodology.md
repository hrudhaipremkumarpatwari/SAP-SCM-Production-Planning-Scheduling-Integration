# Production Planning Methodology

This note summarizes the Week 3 production-planning approach used in the internship project.

## Planning sequence

1. Collect demand / forecast requirements.
2. Validate planning master data: product, location, BOM, routing, resource, production version and calendar.
3. Run medium-term supply planning using SAP APO SNP concepts.
4. Transfer feasible supply requirements into detailed production planning.
5. Create or review planned orders in PP/DS.
6. Schedule operations against finite resource capacity.
7. Sequence products to reduce changeovers and protect priority demand.
8. Review material shortages, resource overloads and timing exceptions.
9. Reschedule, split lots, use overtime or alternate sources where required.
10. Synchronize execution-relevant data with ERP through CIF concepts.
11. Monitor schedule adherence, OTIF, utilization, changeovers and shortages.

## Scenario assumptions

The fictional Deccan Harvest Foods plant produces three millet-based products on shared production and packaging resources. Peak-week demand is intentionally placed close to available packaging capacity so the exercise can demonstrate a realistic bottleneck and the need for finite scheduling.

## Key planning principle

The project separates **supply planning** from **detailed scheduling**. SNP is used conceptually for the broader supply plan, while PP/DS is used for short-term sequencing and finite-capacity scheduling. This distinction helps avoid treating an unconstrained plan as an executable production schedule.
