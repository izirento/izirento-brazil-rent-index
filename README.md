# Brazil: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Brazil: deposits, rent increases, termination notice, lease terms and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

Federal Tenant Law (Lei nº 8.245 of 18 October 1991, Lei do Inquilinato), read from the Federal Senate's compiled text (legis.senado.leg.br). The Presidency portal (planalto.gov.br) did not respond to our server, so its consolidated version was not compared. Only residential urban leases are covered. No figure for rent indexation is given: the Law leaves the adjustment clause to the parties.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main law | Lei nº 8.245 of 18 October 1991 on leases of urban property (Lei do Inquilinato), as amended. | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| contract_form | Term | A lease may be agreed for any term; a term of ten years or more needs the spouse's consent (Art. 3). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| termination | Landlord during fixed term | During the agreed term the landlord may not take the property back; the tenant may return it by paying the agreed penalty, proportional to the time served (Art. 4). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| termination | Tenant notice, open-ended lease | The tenant may end an open-ended lease by written notice of at least 30 days; without notice the landlord may claim one month's rent and charges (Art. 6). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| rent_increase | Change of rent and indexation | The parties may agree a new rent or add or change an adjustment clause (Art. 18). Without agreement, after three years of the lease or of the last agreement, either party may ask the court to revise the rent to market level (Art. 19). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| rent_payment | Advance payment and due date | Except in listed cases and holiday lets, the landlord may not require rent in advance (Art. 20). Unless agreed otherwise, rent is due by the sixth working day of the following month (Art. 23, I). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| deposit | Guarantees allowed | The landlord may require one guarantee: a deposit (caução), a guarantor (fiança), rent-guarantee insurance or assignment of investment-fund units; more than one guarantee in the same lease is void (Art. 37). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| deposit | Cash deposit cap | A cash deposit may not exceed three months' rent and is placed in a savings account, with the returns going to the tenant (Art. 38, para. 2). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| landlord_duties | Landlord duties | The landlord must hand over the property fit for use, guarantee peaceful use, answer for defects existing before the lease, give an itemised receipt, pay administration and agency fees and pay property taxes and fire insurance unless agreed otherwise (Art. 22). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| termination | End of lease of 30 months or more | A written lease of 30 months or more ends at the end of the term without notice; if the tenant stays more than 30 days without objection it continues for an indefinite term, and the landlord may then end it at any time giving 30 days to vacate (Art. 46). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| termination | Lease under 30 months | A lease shorter than 30 months is extended automatically for an indefinite term, and the landlord may recover the property only on listed grounds, such as own or family use, licensed works, or after five years of uninterrupted lease (Art. 47). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |
| termination | Eviction with tenant's consent | In listed eviction actions, if the tenant agrees to leave, the court sets six months to vacate from service (Art. 61). | [Senado Federal - Legislação Federal](https://legis.senado.leg.br/norma/550121/publicacao/34619996) |

## Português

**Brasil.** Dados abertos sobre locação residencial e deveres do locador (Lei nº 8.245/1991): caução, reajuste e revisão do aluguel, prazos de aviso e despejo, com link para a fonte oficial em cada valor.

*Os dados são fornecidos no estado em que se encontram, sem qualquer responsabilidade. Apenas organizamos o que as fontes oficiais publicam. Verifique cada valor na fonte primária.*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `brazil_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Brazil: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-brazil-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
