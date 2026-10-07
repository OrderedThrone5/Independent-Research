# Optimizing Artificial Trees for Carbon Capture

**Harnessing Advanced Adsorbents in Artificial Trees to Combat Climate Change**

Pretom Chowdhury · Supervisor: Matthew Woo · Forest Hills High School

📄 **[Read the full paper (PDF, 30 pages)](artificial-trees-carbon-capture-paper.pdf)**

## Recognition

- 🏆 Winner, New York State Science Fair

## Question

Large direct-air-capture plants like Climeworks need huge amounts of infrastructure. Could a small, cheap "artificial tree" that sits in a neighborhood capture a useful amount of CO₂? And which sorbent material and amine coating work best?

This project was my own idea. It was inspired by Klaus S. Lackner's work on artificial trees, and I built and ran the whole thing in my basement.

## Method

- **Sorbents:** silica gel, zeolite 13X and alumina
- **Amine coatings (20%):** triethanolamine (TEOA), monoethanolamine (MEA), and a mix of the two (MIX)
- The coated sorbent was sealed in an airtight chamber and CO₂ was pumped in. A CO₂ meter logged the reading every hour for six hours.
- Four trials were run for each sorbent and coating combination.
- Each unit cost about **$24** to build.

## Results

CO₂ captured in the first and sixth hour (ppm), as reported in the paper's average plots:

| Sorbent | Coating | Hour 1 | Hour 6 |
| --- | --- | ---: | ---: |
| Silica gel | **MIX** | **6,431** | 1,496 |
| Silica gel | MEA | 2,492 | 1,239 |
| Silica gel | TEOA | 1,795 | 1,015 |
| Zeolite 13X | **MEA** | **4,867** | ~1,260 |
| Zeolite 13X | TEOA | 1,751 | ~1,260 |
| Zeolite 13X | MIX | 1,712 | ~1,270 |
| Alumina | **MIX** | **2,528** | 1,181 |
| Alumina | MEA | 1,891 | 1,204 |
| Alumina | TEOA | 1,017 | 626 |

An ANOVA found statistically significant differences in CO₂ absorption for every sorbent: p = 0.0057 for silica, p = 0.028 for zeolite and p = 0.0002 for alumina.

## Takeaways

- **Fastest capture:** silica gel with the TEOA/MEA mix, followed by zeolite with MEA.
- **Steadiest capture:** MEA held its rate better over the six hours than the other coatings.
- **The main limit is saturation.** Every combination slowed sharply after the first few hours, so the next step is to make the material last longer and to find a way to regenerate it.
- **Cost:** about $300 per ton of CO₂. One unit captures far less than an industrial plant, but it is cheap enough that many could be placed around homes, schools, parks and transit hubs, and they could run on solar or wind power.
