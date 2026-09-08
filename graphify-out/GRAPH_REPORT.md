# Graph Report - AFSA-Legal-Framework  (2026-09-08)

## Corpus Check
- cluster-only mode — file stats not available

## Summary
- 17 nodes · 23 edges · 5 communities (3 shown, 2 thin omitted)
- Extraction: 9% EXTRACTED · 83% INFERRED · 9% AMBIGUOUS · INFERRED: 19 edges (avg confidence: 0.7)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `153de95d`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- AFSA / AIFC Legal Regulation and Framework
- Prudential Rules for Investment Firms
- AIFC Rules on Digital Asset Activities
- AIFC Rules on Providing Money Services
- AIFC Substantial Presence Rules

## God Nodes (most connected - your core abstractions)
1. `AFSA / AIFC Legal Regulation and Framework` - 16 edges
2. `Prudential Rules for Investment Firms` - 3 edges
3. `AIFC Rules on Digital Asset Activities` - 3 edges
4. `General Rules` - 2 edges
5. `Perimeter Guidance` - 2 edges
6. `Manual for Preparation of Returns for Investment Firms` - 2 edges
7. `Financial Services Framework Regulations` - 2 edges
8. `Guidance for AIFC Banks Conducting Settlement for Digital Asset Trading Facility Operators and Digital Asset Service Providers` - 2 edges
9. `Rules and Mechanisms of Cooperation of Unbacked Digital Asset Exchanges and/or Centre Participants with Second-Tier Banks of the Republic of Kazakhstan` - 2 edges
10. `AIFC Rules on Providing Money Services` - 2 edges

## Surprising Connections (you probably didn't know these)
- `AIFC Rules on Providing Money Services` --conceptually_related_to--> `AFSA / AIFC Legal Regulation and Framework`  [INFERRED]
  02 AIFC RULES ON PROVIDING MONEY SERVICES.pdf → README.md
- `Manual for Preparation of Returns for Investment Firms` --conceptually_related_to--> `AFSA / AIFC Legal Regulation and Framework`  [INFERRED]
  04 Manual for Preparation of Returns for Investment Firms.pdf → README.md
- `Rules on the Substantial Presence of AIFC Participants Applying Tax Exemptions for CIT, VAT` --conceptually_related_to--> `AFSA / AIFC Legal Regulation and Framework`  [INFERRED]
  05 RULES ON THE SUBSTANTIAL PRESENCE OF THE AIFC PARTICIPANTS APPLYING TAX EXEMPTIONS FOR THE PAYMENT OF CIT, VAT.pdf → README.md
- `Guidance on the Rules on the Substantial Presence of AIFC Participants Applying Tax Exemptions for CIT, VAT` --conceptually_related_to--> `AFSA / AIFC Legal Regulation and Framework`  [INFERRED]
  06 Guidance on the Rules on the Substantial Presence of the Astana International Financial Centre Participants Applying Tax Exemptions for the Payment of Corporate Income Tax, Value Added Tax.pdf → README.md
- `Guidance for AIFC Banks Conducting Settlement for Digital Asset Trading Facility Operators and Digital Asset Service Providers` --conceptually_related_to--> `AFSA / AIFC Legal Regulation and Framework`  [INFERRED]
  09 Guidance for AIFC Banks conducting settlement for Digital Asset Trading Facility Operators and  Digital Asset Service Providers.pdf → README.md

## Hyperedges (group relationships)
- **Investment Firm Prudential and Reporting Requirements** — 03_prudential_rules_for_investment_firms, 04_manual_for_preparation_of_returns_for_investment_firms, financial_services_framework_regulations [INFERRED 0.65]
- **AIFC Substantial Presence Tax Exemption Rules and Guidance** — 05_rules_on_substantial_presence_tax_exemptions_cit_vat, 06_guidance_on_rules_on_substantial_presence_tax_exemptions, afsa_legal_framework [INFERRED 0.70]
- **AIFC Digital Asset Regulatory Framework** — 08_aifc_rules_on_digital_asset_activities, 09_guidance_for_aifc_banks_settlement_digital_asset_operators_providers, 10_rules_mechanisms_cooperation_unbacked_digital_asset_exchanges_second_tier_bank [INFERRED 0.75]

## Communities (5 total, 2 thin omitted)

### Community 0 - "AFSA / AIFC Legal Regulation and Framework"
Cohesion: 0.33
Nodes (7): General Rules, Perimeter Guidance, Fees Rules, Rules on Currency Regulation and Provision of Information on Currency Transactions in the AIFC, AFSA / AIFC Legal Regulation and Framework, Practical Guidance to AIFC Anti-Money Laundering and Counter-Terrorist Financing Framework, AFSA Legal Framework README

### Community 1 - "Prudential Rules for Investment Firms"
Cohesion: 0.67
Nodes (3): Prudential Rules for Investment Firms, Manual for Preparation of Returns for Investment Firms, Financial Services Framework Regulations

### Community 2 - "AIFC Rules on Digital Asset Activities"
Cohesion: 0.67
Nodes (3): AIFC Rules on Digital Asset Activities, Guidance for AIFC Banks Conducting Settlement for Digital Asset Trading Facility Operators and Digital Asset Service Providers, Rules and Mechanisms of Cooperation of Unbacked Digital Asset Exchanges and/or Centre Participants with Second-Tier Banks of the Republic of Kazakhstan

## Ambiguous Edges - Review These
- `General Rules` → `Perimeter Guidance`  [AMBIGUOUS]
  01 Perimeter Guidance.pdf · relation: references
- `AIFC Rules on Providing Money Services` → `Glossary`  [AMBIGUOUS]
  GLOSSARY.pdf · relation: references

## Knowledge Gaps
- **4 isolated node(s):** `Fees Rules`, `Rules on Currency Regulation and Provision of Information on Currency Transactions in the AIFC`, `Practical Guidance to AIFC Anti-Money Laundering and Counter-Terrorist Financing Framework`, `AFSA Legal Framework README`
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 4 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **2 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `General Rules` and `Perimeter Guidance`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **What is the exact relationship between `AIFC Rules on Providing Money Services` and `Glossary`?**
  _Edge tagged AMBIGUOUS (relation: references) - confidence is low._
- **Why does `AFSA / AIFC Legal Regulation and Framework` connect `AFSA / AIFC Legal Regulation and Framework` to `Prudential Rules for Investment Firms`, `AIFC Rules on Digital Asset Activities`, `AIFC Rules on Providing Money Services`, `AIFC Substantial Presence Rules`?**
  _High betweenness centrality (0.933) - this node is a cross-community bridge._
- **Why does `Prudential Rules for Investment Firms` connect `Prudential Rules for Investment Firms` to `AFSA / AIFC Legal Regulation and Framework`?**
  _High betweenness centrality (0.004) - this node is a cross-community bridge._
- **Why does `AIFC Rules on Digital Asset Activities` connect `AIFC Rules on Digital Asset Activities` to `AFSA / AIFC Legal Regulation and Framework`?**
  _High betweenness centrality (0.004) - this node is a cross-community bridge._
- **Are the 15 inferred relationships involving `AFSA / AIFC Legal Regulation and Framework` (e.g. with `General Rules` and `Perimeter Guidance`) actually correct?**
  _`AFSA / AIFC Legal Regulation and Framework` has 15 INFERRED edges - model-reasoned connections that need verification._
- **Are the 3 inferred relationships involving `Prudential Rules for Investment Firms` (e.g. with `AFSA / AIFC Legal Regulation and Framework` and `Financial Services Framework Regulations`) actually correct?**
  _`Prudential Rules for Investment Firms` has 3 INFERRED edges - model-reasoned connections that need verification._