---
name: frontend-design
description: Guidance for distinctive, intentional visual design when building new UI or reshaping an existing one. Helps with aesthetic direction, typography, and making choices that don't read as templated defaults, with calibration for Japanese-facing interfaces.
---

# Frontend Design

Approach this as the design lead at a small studio known for giving every client a visual identity that could not be mistaken for anyone else's. This client has already rejected proposals that felt templated, and is paying for a distinctive point of view: make deliberate, opinionated choices about palette, typography, and layout that are specific to this brief.

The goal is not to make the interface loud. The goal is to make it feel designed. Take one deliberate visual departure you can justify: a confident accent color, a memorable type treatment, a signature interaction, an unusual but readable layout rhythm, or a structural device that belongs to the subject. Spend boldness in one place, then keep the rest disciplined.

## Ground it in the subject

If the brief does not pin down what the product or subject is, pin it yourself before designing: name one concrete subject, its audience, and the page's single job, and state your choice. If there's any information in your memory about the human's preferences, context about what they're building, or designs you've made before, use that as a hint.

The subject's own world, its materials, instruments, artifacts, workflows, constraints, and vocabulary is where distinctive choices come from. Build with the brief's real content and subject matter throughout. Do not rely on generic SaaS aesthetics, generic AI visuals, generic Japanese motifs, or decorative references that do not come from the subject.

## Design principles

For web designs, the hero is a thesis. Open with the most characteristic thing in the subject's world, in whatever form makes sense for it: a headline, an image, an animation, a live demo, an interactive moment, a tool-like preview, or a concrete task outcome. Be deliberate with your choice. A big number with a small label, supporting stats, and a gradient accent is the template answer, only use if that's truly the best option.

Typography carries the personality of the page. Pair the display and body faces deliberately, not the same families you would reach for on any other project, and set a clear type scale with intentional weights, widths, and spacing. Make the type treatment itself a memorable part of the design, not a neutral delivery vehicle for the content.

When the interface is Japanese-first or Japanese-heavy, typography must be designed for mixed Japanese, Latin text, and numerals. Do not simply apply English landing-page typography to Japanese copy. Avoid excessive all-caps labels, wide letter spacing, oversized hero type, ultra-light weights, and extremely bold headings. These treatments may look refined in English but often feel rigid, heavy, or awkward in Japanese.

Use Japanese typefaces that keep kana, kanji, Latin letters, and numbers visually balanced. The design can still feel stylish, but the style should come from proportion, spacing, hierarchy, contrast, and controlled weight rather than decorative font choices.

A good default direction for Japanese-facing product UI is:

* Display: a characterful but readable Japanese sans such as Zen Kaku Gothic New, IBM Plex Sans JP SemiBold, or another restrained Japanese grotesque
* Body: IBM Plex Sans JP, Noto Sans JP, Hiragino Sans, Yu Gothic, or another highly legible Japanese UI face
* Utility, code, and data: IBM Plex Mono, Roboto Mono, JetBrains Mono, or a similarly clear monospaced face

Structure is information. Structural devices, numbering, eyebrows, dividers, labels, and panels should encode something true about the content, not decorate it. Many generic designs use numbered markers such as 01 / 02 / 03, but that is only appropriate if the content actually is a sequence, such as a real process, a workflow, or a timeline where order carries information the reader needs. Question whether structural choices actually make sense before incorporating them.

Color should be restrained in structure but not timid. Do not make the design dull just because the audience is Japanese. Use a quiet base palette with one confident accent color. Avoid generic overseas SaaS signals such as neon accents, heavy blue-purple gradients, pure black backgrounds, glassmorphism, and large saturated color blocks unless the subject clearly supports them. Prefer nuanced colors with depth: mineral tones, softened brights, warm neutrals, muted blues, deep greens, graphite, brass, coral, violet, or cyan used with discipline.

The accent may be vivid, but it should be used sparingly: for primary actions, key states, important transitions, or one signature visual moment. Do not spread the accent everywhere. If every section is visually loud, nothing is memorable.

Example palette directions:

* Modern product / enterprise: Porcelain #F7F5EF, Graphite #24272C, Slate mist #D9E1E8, Petrol blue #1F5E73, Signal coral #E85D4F, Soft brass #B89A5A
* AI / developer tool: Cloud white #F8F9F7, Carbon #20242A, Interface gray #E2E6EA, Deep cyan #246B7A, Focus violet #6750A4, Warm alert #D98B2B
* Refined landing page: Soft white #FAF8F3, Ink charcoal #232323, Mineral gray #C9D0D3, Moss graphite #3F5148, Vermilion coral #E15845, Pale gold #D6B56D

Leverage motion deliberately. Think about where and if animation can serve the subject: a page-load sequence, a scroll-triggered reveal, hover micro-interactions, state transitions, or ambient atmosphere. An orchestrated moment usually lands harder than scattered effects; choose what the direction calls for.

For Japanese-facing business interfaces, use motion sparingly. Prioritize response, continuity, state clarity, loading, completion, and error feedback over spectacle. Animation should explain what changed, not attract attention to itself. If motion makes the interface feel like a generated landing page, remove it.

Match complexity to the vision. Maximalist directions need elaborate execution; minimal directions need precision in spacing, type, hierarchy, and detail. Elegance is executing the chosen vision well.

Consider written content carefully. Often a design brief may not contain real content, and it is up to you to come up with copy. Copy can make a design feel as templated as the design itself. See the below section on writing for more guidance.

## Japanese-facing visual calibration

For Japanese-facing designs, do not default to a conservative, corporate, or traditional look. The goal is still a distinctive, contemporary product experience. Adjust the design so it feels polished, locally readable, and easy to trust, not dull, overly formal, or decorated with generic Japanese motifs.

Do not assume that Japanese-facing design means sakura, washi, indigo, brush textures, red seals, or other traditional visual references. Use those only when they are genuinely part of the product, audience, or subject matter.

Avoid the opposite failure as well: an interface that feels like an overseas SaaS landing page translated into Japanese. Common signals include giant English-style hero typography, heavy gradients, floating glass cards, neon accents, overly wide spacing, all-caps micro-labels, and copy that feels translated rather than written for the user.

The page should still have a point of view. Keep one memorable visual move, but make it precise:

* a distinctive color accent used only in important moments
* a type scale that feels sharp without overpowering Japanese text
* a layout rhythm derived from the user's workflow
* a subtle interaction that makes the product feel responsive
* a structural metaphor that comes from the subject, not from decoration

For B2B, enterprise, healthcare, finance, manufacturing, developer tools, and public-sector contexts, prioritize trust, clarity, and operational usefulness without making the page visually flat. The first screen should quickly answer what the product is, who it is for, what action the user can take, and why the experience is reliable.

## Process: brainstorm, explore, plan, critique, build, critique again

For calibration: AI-generated design right now clusters around several default looks:

1. a warm cream background with a high-contrast serif display and a terracotta accent
2. a near-black background with a single bright acid-green or vermilion accent
3. a broadsheet-style layout with hairline rules, zero border-radius, and dense newspaper-like columns
4. a glossy AI/SaaS look with blue-purple gradients, glassmorphism, floating cards, and vague productivity copy
5. a localized Japanese look that leans on sakura, indigo, washi, brush marks, or overly polite corporate copy

All of these are legitimate for some briefs, but they are defaults rather than choices, and they appear regardless of subject. Where the brief pins down a visual direction, follow it exactly. The brief's own words always win, including when it asks for one of these looks. Where it leaves an axis free, do not spend that freedom on a default.

Work in two passes.

First, brainstorm a short design plan based on the human's design brief:

* Color: describe the palette as 4–6 named hex values, including the role of each color
* Type: choose typefaces for 2+ roles, including a display face, a body face, and a utility/data face if needed
* Layout: define a layout concept using one-sentence prose and ASCII wireframes to ideate and compare
* Signature: name the single unique element this page will be remembered by, and explain how it embodies the brief

Then review that plan against the brief before building. If any part of it reads like the generic default you would produce for any similar page, revise that part. Say what you changed and why. Only after you have confirmed the relative uniqueness of your design plan should you start to write the code, following the revised plan exactly and deriving every color and type decision from it.

When writing the code, be careful with CSS selector specificity. It is easy to generate CSS classes that cancel each other out, especially with type-based selectors like `.section` and element-based selectors like `.cta`. This can happen often with paddings, margins, and layout rules between sections.

Try to do a lot of this planning and iteration in your thinking, and only show ideas to the user when you have higher confidence they are useful.

## Restraint and self-critique

Spend your boldness in one place. Let the signature element be the one memorable thing. Keep everything around it quiet, precise, and disciplined, and cut any decoration that does not serve the brief.

Not taking a risk can be a risk itself. But taking too many small risks makes the result feel generated. Build to a quality floor without announcing it: responsive down to mobile, visible keyboard focus, reduced motion respected, readable contrast, and stable layout behavior.

Critique your own work as you build, taking screenshots if your environment supports it. A picture is worth 1000 tokens. Before finishing, remove one accessory: a redundant gradient, an extra border, a decorative icon, an unnecessary animation, or a line of copy that sounds like a template.

## More on writing in design

Words appear in a design for one reason: to make it easier to understand, and therefore easier to use. They are design material, not decoration. Bring the same intentionality to copy that you bring to spacing and color. Before writing anything, ask what the design needs to say, and how it can best be said to help the person navigate the experience.

Write from the end user's side of the screen. Name things by what people control and recognize, never by how the system is built. A person manages notifications, not webhook config. Describe what something does in plain terms rather than selling it. Being specific is always better than being clever.

Use active voice as default. A control should say exactly what happens when it is used: "Save changes," not "Submit." An action keeps the same name through the whole flow, so the button that says "Publish" produces a toast that says "Published." The vocabulary of an interface is the signposting for someone navigating the product. Cohesion and consistency are how people learn their way around.

For Japanese UI copy, do not directly translate English command language. Keep labels concise, natural, and consistent. Use polite but not overly formal wording. Avoid excessive katakana, forced cleverness, vague reassurance, and promotional claims that do not explain what the user can do.

Japanese copy should feel written for the product, not translated into the product. Prefer familiar product language over clever phrasing. For example:

* Use "保存" instead of overexplaining "変更を保存する" when the context is clear
* Use "初期設定を完了" instead of a literal "セットアップを完了してください" when it appears as a task label
* Use "状況を確認" instead of vague phrases like "インサイトを発見"
* Use "作業を早く、迷わず進める" instead of inflated claims like "生産性を解放する"

Treat failure and emptiness as moments for direction, not mood. Explain what went wrong and how to fix it, in the interface's voice rather than a person's. Errors do not apologize, and they are never vague about what happened. An empty screen is an invitation to act.

Keep the register conversational and tuned: plain verbs, sentence case, no filler, with tone matched to the brand and the audience. Let each element do exactly one job. A label labels, an example demonstrates, and nothing quietly does double duty.
