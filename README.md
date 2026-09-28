# vibeproof

A free skill for your AI that builds your website with you, so it doesn't look vibe coded.

You can spot a one prompt website in about two seconds. Purple gradients, fake reviews, buttons that go nowhere, no privacy policy. vibeproof asks you the right questions before it writes any code. Then it checks 59 things before you launch.

## What it does

1. **Grills you first.** Your goal, your colors, and the sites you love. The goal is usually getting a visitor on a call with you, so the whole page gets built around that. Every question comes with a recommended answer, so most of the time you just say yes.
2. **Reads your references.** Point it at your current site and it tells you what's working, what isn't, and exactly which colors to use. It knows the color wheel and color psychology, and it checks contrast before it suggests anything. Point it at Apple or Nike and it tells you what to borrow.
3. **Writes a brief your AI follows.** One file with your goal, palette, pages, and proof. Your AI re-reads it every session, so it stops guessing.
4. **Builds with real components.** Free libraries like Originkit, shadcn/ui, and Magic UI, restyled to your brand so nothing looks default.
5. **Checks everything before launch.** 20 features, 19 trust, legal, and accessibility checks, and 20 launch items. Then a final scan for the stuff that makes a site look AI made.

## Install

**Any AI coding agent** (Claude Code, Cursor, Codex, Copilot, Gemini CLI, and more):

```bash
npx skills add nradawg/vibeproof
```

**Claude Code plugin:**

```
/plugin marketplace add nradawg/vibeproof
/plugin install vibeproof@vibeproof
```

**By hand:** copy `skills/vibeproof` into `~/.claude/skills/` (or your agent's skills folder).

**ChatGPT, Gemini, Lovable, or v0:** upload the `skills/vibeproof` folder, or paste `SKILL.md` and the files in `references/` into the chat.

## Use it

Open your AI in a new folder (or your site's folder) and say something like:

- "Build me a website for my landscaping business"
- "Vibeproof my site: example.com"
- "Help me pick colors for my bakery"

Or type `/vibeproof`.

You end up with:

- `site-brief.md`, with your goal, palette, pages, and proof in one file
- The site, built from that brief
- A launch report that shows what's done, what got skipped and why, and what still needs you

## The checklist

<details>
<summary><b>20 features</b></summary>

- Dark mode toggle
- Announcement banner
- Site search
- Back to top button
- Mobile menu
- Loading states
- Hover states
- Scroll progress bar
- Copy button
- Print stylesheet
- Sticky header
- Skip to content link
- Password visibility toggle
- UTM tracking
- Form success state
- Form error state
- Confirmation modal
- Last updated date
- Expandable FAQ
- Floating contact button

</details>

<details>
<summary><b>19 trust, legal, and accessibility checks</b></summary>

- Color contrast
- Alt text on images
- Fix accessibility issues
- Clear button labels
- Keyboard friendly forms
- Privacy policy page
- Terms and conditions page
- Refund policy
- Cookie policy
- Cookie consent
- Form consent
- Check local laws
- Check tracking
- Only collect necessary data
- Check third party embeds
- Remove fake reviews
- Remove unsupported claims
- Add real business details
- Check image copyright

</details>

<details>
<summary><b>20 things before launch</b></summary>

- Call to action above the fold
- Sticky mobile call to action
- Response time promise
- Thank you page
- Custom 404 page
- Real reviews
- Case studies
- Team photo
- Five FAQs
- Maps and directions
- Unique page titles
- Meta descriptions
- Social share image
- Internal links
- Breadcrumbs
- robots.txt
- Local business schema
- Alt text on images
- Privacy policy page
- Google Analytics

</details>

Not every item fits every site. A bakery doesn't need a password toggle. vibeproof marks those "not needed" and tells you why, so nothing gets skipped by accident.

## Where the components come from

| Library | Good for |
|---|---|
| [Originkit](https://originkit.dev) | 250+ free animated components |
| [21st.dev](https://21st.dev) | Huge community library. A free account gets a few copies a day. |
| [shadcn/ui](https://ui.shadcn.com) | The base layer everything else plugs into |
| [Magic UI](https://magicui.design) | 150+ free animated components |
| [Aceternity UI](https://ui.aceternity.com) | Cinematic hero sections and effects |
| [React Bits](https://reactbits.dev) | Text animations and animated backgrounds |
| [tweakcn](https://tweakcn.com) | Theme editor for shadcn/ui |

More libraries, plus design galleries for inspiration, are in [`inspiration.md`](skills/vibeproof/references/inspiration.md).

## Credits

The design rules build on ideas from [impeccable](https://github.com/pbakaus/impeccable), [taste-skill](https://github.com/Leonxlnx/taste-skill), [UI UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill), and [awesome-design-md](https://github.com/VoltAgent/awesome-design-md).

Made by [Nick Raddon](https://raddonai.com). If you'd rather have someone build it for you, that's what I do.

## License

MIT. Use it however you want.
