ROLE: You are an award-winning data visualization designer who builds
interactive, editorial-quality web graphics.

AUDIENCE: Community college students in a data storytelling class, seeing
this on a projector. They should understand it in 10 seconds and want to
explore it.

TASK: Using the attached CSV (fictional monthly revenue for 6 cafés x 4
products, 2024-2025), build ONE self-contained HTML page with a truly unique
visualization whose shape fits the data's story.

THE STORY (put this in the headline): "Every summer, the cold brew spiral
grows." Cold brew peaks every summer, grew 22% in 2025, and delivered 72% of
the company's growth.

FORMAT:
1. Hero: a large serif headline (the finding, not the topic) and a 2-3
   sentence "how to read it" line.
2. Main visual: a top-down coffee cup (rim, saucer, handle) containing a
   24-month spiral. January 2024 starts at the center and winds outward to
   December 2025 at the rim. Each month is a petal-shaped bar; petal LENGTH
   = that month's revenue. Months go clockwise, January at the top, with
   month labels around the edge. 2024 petals are faded and 2025 petals are
   bright. Include a scale key showing what a full-length petal is worth.
3. Controls: chips to pick the product (Cold brew, Hot coffee, Food, Tea,
   All) and the café (All cafés + each café), plus a "Pour two years" button
   that animates the petals growing month by month.
4. A side readout that updates with every selection: 2025 revenue (big
   number), change from 2024, best month, summer vs. winter ratio, and a
   one-sentence insight (e.g., Campus loses ~40% of sales when students
   leave).
5. Section 2: "Six cafés, six glasses": 2025 revenue per café as
   straight-sided glasses stacked by product, sorted largest to smallest,
   with a total above each glass.
6. Section 3: "the pour": one horizontal stacked bar showing where the
   $190K of 2024-to-2025 growth came from, by product, with labels.
7. A collapsible table of the monthly numbers.

TONE / STYLE: a dark "after-hours café" look: espresso-brown background,
cream text, Instrument Serif for headlines, Schibsted Grotesk for body
text. Product colors: hot coffee = copper, cold brew = ice blue,
food = raspberry, tea = matcha green. One bold idea (the cup), everything
else quiet.

CONSTRAINTS:
- Compute every number from the CSV. Do not invent or round away any figure.
- Keep it honest: glasses must have straight sides on ONE shared scale so
  layer heights are exactly proportional; bars start at zero; time runs in
  order.
- Colors must be distinguishable for color-blind viewers; never use color
  alone (add a legend and labels).
- Hover tooltips on petals and glass layers with exact values.
- Label the data "fictional" in the header and footer.
- No external libraries; plain HTML, CSS, SVG and JavaScript in one file.
  Respect reduced-motion settings.

EVALUATION: Before answering, check: (1) Does the headline state a finding
with a number? (2) Would a viewer find the summer pattern within 10
seconds? (3) Does every number match the CSV? (4) Is anything distorted or
not to scale? Fix any problem, then give me the complete HTML file.
