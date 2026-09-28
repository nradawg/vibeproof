# Color

Use this to read the colors a business already has and to build a palette that fits its goal.

## The color wheel in one minute

- **Primary:** red, yellow, blue. **Secondary:** orange, green, purple. **Tertiary:** the six in between, like blue green.
- **Warm colors** (red, orange, yellow) feel energetic and close. **Cool colors** (blue, green, purple) feel calm and farther away.
- **Tints** add white. **Shades** add black. **Tones** add gray. Good sites use lots of tints and shades of one or two hues, not lots of hues.

## Harmonies

Pick one on purpose and name it when you present a palette.

| Harmony | What it is | Good for |
|---|---|---|
| Monochromatic | One hue in many tints and shades | Calm, premium, minimal. The easiest to get right. |
| Analogous | Three neighbors on the wheel, like blue, blue green, and green | Friendly, natural, cohesive brands |
| Complementary | Two opposites, like navy and orange | A brand color plus a button that pops |
| Split complementary | One color plus the two neighbors of its opposite | The pop of complementary with less tension |
| Triadic | Three colors evenly spaced around the wheel | Playful brands. Let one color lead or it gets loud. |

For most business sites: a neutral base, the brand hue, and one accent from across the wheel that only the goal button uses.

## The 60-30-10 rule

- **60%** neutral background, tinted slightly toward the brand hue instead of pure gray
- **30%** the brand color and its shades: headings, section backgrounds, icons
- **10%** the accent, saved for the goal button and key links

If the accent shows up everywhere, the button stops standing out.

## What colors usually say

These are common associations in Western markets, not laws. Meaning shifts with culture, shade, and what sits next to it. Use this to reason, then check it against the actual business.

| Color | Usually signals | Common fits | Watch out |
|---|---|---|---|
| Blue | Trust, calm, competence | Finance, health, law, tech, trades | So common it can blend in |
| Green | Growth, health, nature, money | Landscaping, wellness, eco, finance | Neon greens read cheap |
| Red | Energy, urgency, appetite | Food, fitness, sales, emergency services | Also means error and danger. Use it in small doses. |
| Orange | Friendly, affordable, action | Buttons, home services, kids | Too much feels loud or discount |
| Yellow | Optimism, attention | Highlights, construction, food | Fails contrast on white, so never use it for text |
| Purple | Luxury, creativity | Beauty, creative studios, premium brands | The purple to blue gradient is the biggest AI tell there is |
| Pink | Playful, caring, youthful | Beauty, bakeries, lifestyle | Pair it with a strong neutral |
| Black | Premium, bold, serious | Luxury, fashion, high end products | Pure black is harsh on screens. Use a near black. |
| White and light neutrals | Clean, simple, open | The base for almost everything | Pure white everywhere feels sterile |
| Brown and earth tones | Natural, warm, dependable | Coffee, woodwork, outdoors | Can look dated without a crisp accent |

## Diagnose an existing site

When they point you at their site, work through this, then tell them plainly what they need.

1. **Collect the colors.** Logo, buttons, links, headings, backgrounds. If you can read the HTML or CSS, check the color variables (like `--primary`) and the button styles. Write down each hex code and where it's used.
2. **Name the harmony,** or say there isn't one.
3. **Read the signal.** What do the colors say, and is that what the business wants to say? A law firm in neon orange says cheap and loud. A spa in bright red says urgent, not calm.
4. **Check contrast** on text and buttons, using the rules below.
5. **Prescribe.** Keep what builds recognition (usually the logo color). Change what fights the goal. Give exact hex codes and the job each one does.

The tone to use:

> Your navy says trust, which is right for a lender, so keep it. The problem is your buttons are navy too, so nothing tells people where to click. Make the booking button #E07A2F, a warm orange from across the wheel, with near black text on it (5.7:1). White text on that orange only gets 3:1, which fails for button text.

Always calculate the contrast of any color you suggest before you say it passes.

## Contrast rules (WCAG AA)

- **Body text:** at least 4.5:1 against its background
- **Large text** (24px and up, or 18.7px and up if bold): at least 3:1
- **Buttons, inputs, icons, and focus rings:** at least 3:1 against what's around them
- Check light mode and dark mode separately
- Never use color alone to carry meaning. Errors and success messages also get text or an icon.

Check any pair with the WebAIM contrast checker: https://webaim.org/resources/contrastchecker/

## Build the palette

Give them two options. Each one needs:

- **Background** and **surface** (cards, sections): near white, or near black in dark mode, tinted slightly toward the brand hue
- **Text** and **muted text:** a near black and a softer one that still passes 4.5:1
- **Brand:** their color, plus a lighter and a darker shade
- **Accent:** the goal button only
- **States:** success green, error red, and a focus ring color that passes 3:1

Present it like this:

| Role | Hex | Used for | Contrast |
|---|---|---|---|
| Background | #F8F7F4 | Page background | |
| Text | #1C1B19 | Body copy | 16.1:1 on background |
| Muted text | #5F5B55 | Captions, secondary text | 6.3:1 on background |
| Brand | #1F3A5F | Headings, footer | 10.7:1 on background |
| Accent | #E07A2F | Booking button only | 5.7:1 with #1C1B19 text |

Then say which harmony it uses and why it fits their three feeling words.

## Palettes that look vibe coded

- Purple to blue gradients with glowing blobs behind the hero
- Neon colors on pure black
- A different bright color on every card
- Gradient text on headings
- Gray text on gray backgrounds
- Every button and link in the accent color
