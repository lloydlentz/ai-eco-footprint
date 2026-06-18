# AI Eco Footprint

An interactive, single-page environmental footprint estimator that helps people compare everyday climate-impact choices across home energy, transportation, food, waste, digital life, device replacement, and AI usage.

Live site: [https://lloydlentz.github.io/ai-eco-footprint/](https://lloydlentz.github.io/ai-eco-footprint/)  
Advanced impact map: [https://lloydlentz.github.io/ai-eco-footprint/advanced.html](https://lloydlentz.github.io/ai-eco-footprint/advanced.html)  
GitHub repository: [https://github.com/lloydlentz/ai-eco-footprint](https://github.com/lloydlentz/ai-eco-footprint)

## Purpose

This project was created for a broader discussion about the environmental impact of AI. The goal is not to make AI feel either harmless or uniquely catastrophic. Instead, the tool places AI usage inside a more complete personal environmental footprint, next to categories people already understand: heating, electricity, driving, flying, diet, consumption, recycling, composting, and digital habits.

The interface is designed for conversation and exploration. A user can adjust inputs and immediately see how their estimated annual footprint changes in pounds of CO2e, how they compare with a U.S. benchmark, and how AI usage relates to larger lifestyle categories.

## Initial Prompt

The project began from this request:

> I'd like to build an interactive html style visualization tool that shows an individual's overal environmental impact. I want to include all of the key things that can imact one's overall enviro footprint. From recycling, to home heating, to car travel, to air travel, to AI usage. This is in a broader discussion about AI environmental impact. so I want to somehow highlight this. I want this to be a visually appealing, web interface.
>
> Can you add a dial meter that shows compared to average / other US.
>
> Can you put metrics in US (miles, gallons, pounds)
>
> Can you add a link to sources at the bottom?
>
> Can you add an option to show living in a dorm/apartment?
>
> Can you show estimated miles of air travel?
>
> Can you add some checkboxes that folks use to cut down on enviro footprint? Vegan/meat, coposting and/or a couple other things good intentioned folks may do.

Additional follow-up requests expanded the tool to include digital life beyond AI, device replacement, and social media use.

## What It Includes

- A visual dial comparing the user's annual estimate with a U.S. benchmark.
- U.S. customary inputs and outputs, including miles, gallons, kWh, therms, and pounds of CO2e.
- Home setting options for a single-family house, apartment or condo, and dorm/shared campus housing.
- Transportation inputs for car miles, MPG, and estimated annual air miles.
- Food-pattern options ranging from higher-meat diets to vegan diets.
- Digital-life inputs for AI prompts, image/video generations, streaming, social media, gaming/high-power computing, cloud storage, and device replacement.
- Action checkboxes for recycling, composting, thermostat/weatherization, renewable electricity, transit/carpooling, buying less, and electronics repair/recycling.
- Source links and assumptions at the bottom of the page.

## Advanced Impact Map

The advanced page is an exploratory draft for expanding the project beyond a single CO2e estimate. It introduces impact lenses for climate, energy, water, materials, land, air quality, waste, and digital infrastructure.

Each element includes a popup-style detail panel with:

- What to measure
- Broader comparison context
- Caveats and interpretation notes
- High-value reduction levers

View it at:

[https://lloydlentz.github.io/ai-eco-footprint/advanced.html](https://lloydlentz.github.io/ai-eco-footprint/advanced.html)

## Context

Personal environmental-footprint estimates are inherently approximate. They depend on local electricity grids, housing type, climate, travel patterns, diet, product lifecycles, and many other variables. This tool is meant as an educational estimator rather than a formal carbon accounting system.

AI usage is especially difficult to estimate precisely because per-request energy use varies by model, provider, hardware, request type, system load, and data-center energy mix. The tool therefore treats AI as one visible slice of a wider digital footprint and pairs it with broader digital activities such as streaming, social media, cloud storage, gaming, and device replacement.

That framing is intentional: individual AI prompts matter, but the larger systems conversation includes data centers, transmission networks, electricity supply, device lifecycles, and how rapidly digital demand grows.

## Sources

The app links to sources and reference material used for broad assumptions, including:

- [EPA: typical passenger vehicle emissions](https://www.epa.gov/greenvehicles/greenhouse-gas-emissions-typical-passenger-vehicle)
- [EPA: greenhouse gas equivalencies calculator references](https://www.epa.gov/energy/greenhouse-gas-equivalencies-calculator-calculations-and-references)
- [EIA: average U.S. household electricity use](https://www.eia.gov/tools/faqs/faq.php?id=97&t=3)
- [EPA eGRID electricity emissions data](https://www.epa.gov/egrid)
- [IEA: Energy and AI](https://www.iea.org/reports/energy-and-ai)
- [IEA: data centres and data transmission networks](https://www.iea.org/energy-system/buildings/data-centres-and-data-transmission-networks)
- [EPA: electronics donation and recycling](https://www.epa.gov/recycle/electronics-donation-and-recycling)
- [Our World in Data: food choice and emissions](https://ourworldindata.org/food-choice-vs-eating-local)

## GitHub Pages

This is a static site served from `index.html`.

GitHub Pages is configured to publish from:

- Branch: `main`
- Folder: `/ (root)`

The published site is available at:

[https://lloydlentz.github.io/ai-eco-footprint/](https://lloydlentz.github.io/ai-eco-footprint/)
