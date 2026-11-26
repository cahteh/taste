# Interface

*Interface*: Latin *inter*, between, and *facies*, face. The surface where a person and a system meet. It shows the work and little else.

These are rules, not values. Sizes, colours and fonts live in each project's tokens. Every rule names a role, so it holds in every theme.

## Where these rules apply

- **Folio** opens on the fiat themes: a dialed-in, ordinary CRM, light or dark, never dark by default. Every rule here applies.
- **The HUD theme** turns that CRM into something more magical. Light is its material. Every rule here applies, and Light weighs more.
- **The Clarity website** is a normal, friendly site with real content, testimonials, videos and docs. It takes Type, Colour, Light, Motion, Behaviour, Phones and Pictures from this page, and nothing else.

## Bare

- No callouts, subtitles, helper notes, taglines or flavour text. If a control needs a sentence, fix the control.
- No title that repeats the navigation or the breadcrumb. A section does not restate its own name. A home screen's greeting is its title.
- What may stay: a real constraint, a consequence the person must know before acting, and a status.
- One place to change a setting. One save per view, and autosave where it can.

## Calm

Folio keeps a person on their frequency. It never hurries them.

- No urgency colours. Red and amber do not mark what is late, failed or waiting. Plain words do ("Didn't send", "Check"), set in ink where the rest of the row is muted, with the action beside them.
- Order carries urgency. What blocks the day comes first.
- No alarms, no shaking, no counters that race. A count is a plain number.
- A list of things that need the person ends. When it is empty it says so once, in muted text, and the moment flashes clear.
- Destructive actions say what they do in their label. Undo comes before confirm.

## Layout

- A screen holds exactly what it needs. A record opens beside the list, so the list stays in view.
- Quiet chrome. Parts are split by hairline rules, not boxes. A card is for the one thing on a screen that floats or repeats. Shadow belongs to floating layers only.
- Spacing steps by 4. Space inside a group is smaller than space between groups. Equal things get equal sizes.
- Things line up: icons in one column, labels on one line, numbers right-aligned.
- Two control heights: one for main actions, one for compact ones.
- Nested radius: inner equals outer minus padding.

## Navigation

- **The rail.** Flat, grouped rooms split by a rule. No nested trees and no catch-all menu on it. The owner chooses the rooms, and a person may change them for themselves.
- A workspace with few rooms keeps the rail collapsed and fixed: icons only, no toggle. Carter, 11/25, for crew: "Collapsed, fixed".
- **No room twice.** A room has one way in. A screen does not repeat the rail as a list of doors, and a tab does not repeat a rail item.
- The current room is lit, not boxed: the room's light pools behind its icon. Hover is a faint ink tint.
- A room with something new shows a count. Never a bare dot.
- A collapsed rail names each room in a tip. The first tip waits; the rest follow the pointer at once.
- Settings and the other pages open from the portrait menu. The rail is crossed by keyboard as well as by hand.

## Rooms

*Room*: Old English *rūm*, space, room to move. A space a person works in, not a box on a page.

- An opened room hangs in the space at the centre, with no frame around it and no panel behind it (Carter, 11/22). Its parts stay split by rules.
- A room opens full screen, split beside another, or as a companion beside the one in use.
- Each room opens one way and closes one way. Escape goes back one step, on every page.
- The house lights go down when a room opens, so its light can be read.

## Sheets

*Sheet*: Old English *scēte*, a cloth spread out. A grid people already know, kept.

- A client who ran on a spreadsheet gets a sheet, not a form. EH Baker's crew sheet is the model for Folio's default sheet. Carter, 11/26: "the default folio sheet will be modeled after this one exactly".
- Column letters stay. Carter, 11/26: "i like the letters and want it to be a true folio sheet".
- Tabs keep the client's own names from the sheet they left: Assign Crew, Report Log. The room around them keeps Folio's name (Schedule).
- One sheet, one component, one Sheet menu, wherever it opens: in its room or as a file in Drive. A file's name shows once, in the top bar.
- A second view of the same data is a tab of the same sheet, not a new room. Carter, 11/26: "reports should be on another tab of the sheet just like their used to on google sheets".

## Play

*Play*: Old English *plega*, brisk movement, exercise. The game is in the work and never in the way of it.

- Folio is a CRM first. The game sits behind it, reached on purpose, and stays out of fiat's daily screens.
- What is lit records what a person did, taken from History. Each lit thing names the record that lit it and opens it.
- No points, streaks, numbered levels or leaderboards. No confetti or sparkle. No copy that explains the game.
- **The Craft in One Light is a sky.** Each room is a constellation, each deed a star, the Calling a few faint stars at the rim. The screen holds about one constellation; the whole sky is crossed by free camera, with a small map and a way home. Carter, 11/26: "the full span of this skill tree requireds navigating free cam around the board"; "almost like constallations, were getting somwhere, destiny UX is cool".
- **The Craft in fiat is simplified advancements.** One tab per room held, a small fixed tree read left to right that fits one screen: square frames, elbow lines, a card on hover. Carter, 11/26: "a simplified advancements, a la minecraft, for the fiat view of these". The mechanic is taken, never the look, art or icons.
- What is next is named; what lies beyond it stays unnamed and faint.

## Marks

*Mark*: Old English *mearc*, a boundary, a sign. A mark earns its place by being rare.

- The spark is Folio's mark, and the way a person reaches Folio or Sophia. Carter, 11/26: "this IS the spark , the magic of folio".
- Ask Folio in fiat; ask Sophia in One Light. One mark, drawn simply for fiat and as light for One Light. Carter: "it should also read as a 2d sketch, the main render will be its appearance in onelight, and simplified version for ask folio".
- A mark is not reused as an ornament. It does not become a node, a bullet or a frame. Carter, 11/26: "i dont like that almond let alone overusing it.."
- The almond (vesica, mandorla) is out, as a mark and as a shape.

## Type

- One family for everything. No serif partner, no monospace. A serif inside a wordmark is part of the mark.
- Numbers use tabular figures in the same family, in one format per screen.
- A few sizes. Hierarchy comes from size and colour before weight.
- Labels are stored in sentence case. Section labels may be set in capitals by CSS.
- **Gradient text, done well.** Carter, 11/26: "can use gradient text , just not poorly". Done well, it reads as light falling on the type: one hue, the text's own role thinning toward a fainter step of itself, on the one statement a screen leads with, legible at its faintest end. Done poorly: several hues, an accent sweep, rainbow fills, or gradients on body text and labels.

## Colour

*Token*: Old English *tācen*, a sign. A token names a role, and the theme gives it a value.

- Views read tokens, never a raw colour, so another theme can sit beside the first.
- One neutral ramp carries surfaces, lines and text. Text has three working roles: ink, mid, muted. The faintest step never carries text.
- One accent, used rarely: the primary action, the selection, focus, the number that matters. Clarity blue, unless the owner picks another.
- Two brand roles. *Arrive*, an emerald, marks an arrival, once per screen. *Clear*, a clarified white, is what a thing takes as it resolves.
- Depth comes from surface steps, hairlines and the room's light, not from decorative gradients.
- Icons come from one set, at one size and stroke per place, in the colour of their text role. No emoji in chrome.
- AA contrast for all text, small labels included.

## Light

Carter: "with any visual update i want to consider using the manifested light , letting it sit in the space of the room". And: "should be calming, and eligant, light can just spawn in however we need it does not need a source". And: "glow is life affirming, physics, light, reactive, functional... not simply a cosmetic effect".

- Light is a working material. It shows that something is alive, that it answers a touch, or that it matters: the current room, the live step of a day, the action a person is about to take.
- It sits in the space behind and below the content, never on top of it, and never crosses text.
- It needs no lamp. A source may come later, by Carter's choice.
- It is calm. It holds still and never pulses. Only something live may breathe, and then slowly.
- It reads the theme's own roles, so each theme lights itself.
- Every visual change asks whether the light belongs in it. Light that only decorates is left out.

## Envoys

*Envoy*: French *envoyé*, one sent. An agent that speaks for a person or a team.

- An envoy speaks under its own name and carries a mark that says it is an envoy. A person's words carry no mark.
- The mark opens to show where the envoy comes from. Nothing about an agent is hidden from the people it speaks to.
- AI is never drawn as sparkles, blobs or magic wands. An envoy is shown by its name and its mark.

## Motion

- Motion explains a change. It is short and smooth, on one easing curve.
- Three signatures. The *flash*: something resolves. The *pour*: things arrive in order. The *turn*: the other side of the same thing.
- A screen that opens at once does not animate in. A pour plays on the first arrival only.
- Numbers roll only when the value changes, never on load.
- Nothing loops unless it is live.
- Everything that moves has a reduced-motion version that shows the end state.

## Behaviour

- Undo over confirm, for anything reversible.
- Autosave with a quiet "Saved". Edit in place, not in a modal.
- A side panel, not a modal, for what stays open while the person works.
- An action is visible where it is needed. Hover only reveals what is also reachable by keyboard.
- A loader waits before it shows, and a skeleton matches the final layout so nothing jumps.
- Every state is designed: loading, empty, error, too much data.
- A visible focus ring for the keyboard.

## Charts

- A smooth line, a live end dot, a value label that rides the line, eased changes between ranges.
- One accent per chart, on a muted grid.
- A change says what it compares to.

## Phones

*Tactical*: Greek *taktikos*, of arranging. A phone screen is arranged for one move.

- A phone gets its own design, not the desktop made small. It may differ in tabs and order.
- One job per screen, one main action, fewer words. Never dense.
- The tab bar follows the rail's rooms and order, unless the owner sets it otherwise.
- Targets are at least 40 tall. Text links get a 44 tap zone. A whole row is the target.

## Pictures

- App screens rarely need one. Their moments come from the product.
- Where a picture belongs, a public-domain painting or a real photograph comes before a generated image. Credit it quietly.
- Sample data is synthetic and plausible.

## Signs it is not finished

- Anything explaining the interface to the person using it.
- A title that repeats the navigation. A room reachable two ways.
- Red or amber used to hurry someone. A status dot with no label.
- Blobs and sparkles for AI. Light that crosses text or pulses.
- A frame or panel drawn around a room. Boxes where a hairline would do.
- Emoji as icons or decoration. Pills and badges on everything.
- Read-only values styled as fields.
- A raw colour in a view.
- A screen that would fit another product with the name swapped.
- A mark used as decoration, or repeated until it means nothing.
- Points, streaks or levels. A game that explains itself.

---

Some signs are adapted from [unslop](https://github.com/heydamir/unslop) by Damir Sokolovsky, CC BY 4.0.
