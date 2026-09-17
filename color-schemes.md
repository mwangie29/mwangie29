# Five Individual Color Schemes

These systems translate the uploaded palette exploration into reusable UI tokens. Each theme keeps the same semantic roles so the product can change personality without changing its information architecture.

## A — Luminous Mint

**Direction:** Cool, energetic clarity for a confident product studio, portfolio, or SaaS interface.

| Role | Token | Hex | Recommended use |
| --- | --- | --- | --- |
| Foundation | `--mint-foundation` | `#071312` | Page background and deep canvas |
| Surface | `--mint-surface` | `#101D1C` | Cards, panels, navigation, overlays |
| Content | `--mint-content` | `#F4FBF7` | Primary text, icons, high-priority UI |
| Border | `--mint-border` | `#29413D` | Dividers, outlines, quiet structure |
| Energy primary | `--mint-energy` | `#2DE2C2` | CTAs, focus states, active navigation |
| Energy secondary | `--mint-energy-soft` | `#8BE9FD` | Highlights, secondary actions, data accents |
| Success | `--mint-success` | `#8BE28B` | Positive confirmation |
| Warning | `--mint-warning` | `#F3C969` | Caution and incomplete states |
| Error | `--mint-error` | `#F17878` | Destructive and failure states |
| Info | `--mint-info` | `#5EA7FF` | Informational feedback |

Use mint as the default recommendation when the product should feel **clear, modern, optimistic, and technically capable**.

## B — Spectral Blue

**Direction:** Deep, futuristic calm for technical products, developer tools, infrastructure, and intelligent systems.

| Role | Token | Hex | Recommended use |
| --- | --- | --- | --- |
| Foundation | `--spectral-foundation` | `#070C1D` | Page background and deep canvas |
| Surface | `--spectral-surface` | `#101A31` | Cards, panels, navigation, overlays |
| Content | `--spectral-content` | `#F4F7FF` | Primary text, icons, high-priority UI |
| Border | `--spectral-border` | `#31466E` | Dividers, outlines, quiet structure |
| Energy primary | `--spectral-energy` | `#2F7BFF` | CTAs, focus states, active navigation |
| Energy secondary | `--spectral-energy-soft` | `#7B5CFF` | Highlights, secondary actions, data accents |
| Success | `--spectral-success` | `#70D49A` | Positive confirmation |
| Warning | `--spectral-warning` | `#F4C86A` | Caution and incomplete states |
| Error | `--spectral-error` | `#F27B8A` | Destructive and failure states |
| Info | `--spectral-info` | `#64C7FF` | Informational feedback |

Use spectral blue when the product should feel **precise, intelligent, dependable, and future-facing**.

## C — Warm Tech

**Direction:** Approachable technical warmth for products that need credibility without feeling cold or overly corporate.

| Role | Token | Hex | Recommended use |
| --- | --- | --- | --- |
| Foundation | `--warm-foundation` | `#16110B` | Page background and deep canvas |
| Surface | `--warm-surface` | `#241B13` | Cards, panels, navigation, overlays |
| Content | `--warm-content` | `#FFF8EF` | Primary text, icons, high-priority UI |
| Border | `--warm-border` | `#5B4430` | Dividers, outlines, quiet structure |
| Energy primary | `--warm-energy` | `#FF9E2C` | CTAs, focus states, active navigation |
| Energy secondary | `--warm-energy-soft` | `#F0C38A` | Highlights, secondary actions, data accents |
| Success | `--warm-success` | `#A8D26D` | Positive confirmation |
| Warning | `--warm-warning` | `#F3C45E` | Caution and incomplete states |
| Error | `--warm-error` | `#EF7468` | Destructive and failure states |
| Info | `--warm-info` | `#79A9D8` | Informational feedback |

Use warm tech when the product should feel **human, trustworthy, crafted, and approachable**.

## D — Mineral / Organic Tech

**Direction:** Earthy depth for sustainability, infrastructure, security, wellness, and systems connected to the physical world.

| Role | Token | Hex | Recommended use |
| --- | --- | --- | --- |
| Foundation | `--mineral-foundation` | `#0B1613` | Page background and deep canvas |
| Surface | `--mineral-surface` | `#15251E` | Cards, panels, navigation, overlays |
| Content | `--mineral-content` | `#F1F7EE` | Primary text, icons, high-priority UI |
| Border | `--mineral-border` | `#3B5947` | Dividers, outlines, quiet structure |
| Energy primary | `--mineral-energy` | `#97C95C` | CTAs, focus states, active navigation |
| Energy secondary | `--mineral-energy-soft` | `#D7E8A6` | Highlights, secondary actions, data accents |
| Success | `--mineral-success` | `#A8D46F` | Positive confirmation |
| Warning | `--mineral-warning` | `#E8C66C` | Caution and incomplete states |
| Error | `--mineral-error` | `#E8796F` | Destructive and failure states |
| Info | `--mineral-info` | `#6AB4B0` | Informational feedback |

Use mineral when the product should feel **grounded, resilient, responsible, and quietly distinctive**.

## E — Experimental

**Direction:** Bold, high-contrast expression for creative technology, innovation labs, culture, and standout personal brands.

| Role | Token | Hex | Recommended use |
| --- | --- | --- | --- |
| Foundation | `--experimental-foundation` | `#160A17` | Page background and deep canvas |
| Surface | `--experimental-surface` | `#251027` | Cards, panels, navigation, overlays |
| Content | `--experimental-content` | `#FFF5FD` | Primary text, icons, high-priority UI |
| Border | `--experimental-border` | `#673052` | Dividers, outlines, quiet structure |
| Energy primary | `--experimental-energy` | `#FF3FA4` | CTAs, focus states, active navigation |
| Energy secondary | `--experimental-energy-soft` | `#8E4DFF` | Highlights, secondary actions, data accents |
| Success | `--experimental-success` | `#A8E063` | Positive confirmation |
| Warning | `--experimental-warning` | `#FFC45F` | Caution and incomplete states |
| Error | `--experimental-error` | `#FF6B78` | Destructive and failure states |
| Info | `--experimental-info` | `#62D4FF` | Informational feedback |

Use experimental when the product should feel **memorable, expressive, unconventional, and visually assertive**.

## Shared application rules

Use foundation for the canvas and surface for elevation rather than relying on heavy borders. Use content levels in this order: primary text, muted text, and disabled text. Reserve energy colors for actions, focus, selection, and meaningful data so the interface does not become visually noisy. Keep status colors consistent in meaning even when the theme changes; users should not have to relearn success, warning, error, or information states.

For accessibility, use the light content colors on foundation and surface backgrounds, and do not use energy colors as long paragraphs. Test every text and interactive-state combination against WCAG contrast requirements before shipping.

## Recommended selection

For Lewis’s full-stack and UI/UX profile, **A — Luminous Mint** is the strongest everyday system because it combines clarity with technical energy. **B — Spectral Blue** is the best alternative for a more engineering-led identity, while **E — Experimental** is the strongest campaign or portfolio accent system.
