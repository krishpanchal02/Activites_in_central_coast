# TARGET: today's build

Choose the idea, person, interaction, and visual direction. The agent can help phrase and save your decisions after you approve them. The provided scope and review safeguards stay in place.

- **Thing:** A one-page Central Coast visitor guide where tourists select a destination to view its photo gallery, estimated cost, and travel distance.
- **Audience:** Tourists visiting California's Central Coast who want to compare appealing places to visit and plan a simple outing.
- **Requirements:** One working primary interaction: selecting a destination opens or updates its pictures. Each destination makes its estimated price and distance from San Luis Obispo understandable, and honors the approved standing rule in AGENTS.md.
- **Guardrails:** Static browser code. No required external service, keys, accounts, runtime AI, or private data. Label estimated prices and any sample content. Preserve the example and publishing setup. Work on a branch and wait for human review before shipping.
- **Experience:** Colorful, visually appealing, and photo-led; destination images are the focus while price and distance remain easy to compare.
- **Test:** I can select a destination, view its pictures, confirm its labeled estimated price and distance, and point to the standing rule's effect in the actual preview. After I approve and merge, the same registered Pages URL works.

The coastal example has a [completed TARGET](examples/coast/SPEC.md). It demonstrates the format, not a required topic.
