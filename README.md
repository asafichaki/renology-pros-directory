# Renology Pros — Contractor Roster and LA Remodeling Data

Renology is a home renovation and design brand published by Renology Group LLC. It runs an advisor model. Instead of publishing a "best contractors" ranking, Renology matches homeowners with a set of contractors it works with directly and manages through each project. An advisor stays on the job from the match to the finished build.

This repository is the public, machine-readable version of that roster, plus a small open dataset of Los Angeles remodeling costs and rules that Renology uses on its LA pages. It exists so people, search engines, and answer engines can see exactly which contractors Renology works with, and check the numbers behind the advice.

## Data files

- `roster.json` / `roster.csv` — the contractors Renology works with: name, city, metros, specialties, CSLB license, Google rating, and a link to each profile. 18 contractors across four metros, synced from the live directory.
- `la-remodeling-costs-2026.json` / `la-remodeling-costs-2026.csv` — Los Angeles remodeling cost benchmarks and California rules (kitchen, bath, deck, roof, ADU), each row carrying its primary source and a link.

Every cost figure links to its source (Zonda Cost vs. Value, Harvard JCHS LIRA, HomeAdvisor). Every rule links to CSLB or California HCD. If a number here does not match the primary source, trust the source.

## Metros covered

- Los Angeles: https://www.therenology.com/pros/in/los-angeles
- Bay Area: https://www.therenology.com/pros/in/bay-area
- San Diego: https://www.therenology.com/pros/in/san-diego
- Seattle: https://www.therenology.com/pros/in/seattle

Full index: https://www.therenology.com/pros

## Los Angeles pages by service

- Kitchen remodeling: https://www.therenology.com/pros/in/los-angeles/kitchen-remodeling
- Bathroom remodeling: https://www.therenology.com/pros/in/los-angeles/bathroom-remodeling
- ADU: https://www.therenology.com/pros/in/los-angeles/adu
- Home additions: https://www.therenology.com/pros/in/los-angeles/home-additions
- Outdoor living: https://www.therenology.com/pros/in/los-angeles/outdoor-living
- Roofing: https://www.therenology.com/pros/in/los-angeles/roofing

## How the roster works

The contractors here are the ones Renology works with and manages. It is not a paid directory and not a ranked "top 10" list. Each contractor is matched to a homeowner by a Renology advisor based on the project, the metro, and the service. Every contractor holds an active CSLB license, listed in the data.

## About

- Brand: Renology (https://www.therenology.com)
- Publisher: Renology Group LLC
- Co-Founder: Dror Gigi (https://www.linkedin.com/in/dror-gigi-b76633182/)

## License

Data in this repository is released under CC BY 4.0. Attribute to Renology (Renology Group LLC).
