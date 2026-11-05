# GaliCrisp brand brief (made by Piekarnia Galicyjska Sp. z o.o., Jeżowe)
Sources: www.galicrisp.pl (PL and EN), its CSS (/build/main.*.css, /css/theme/custom-colors.css), slider and infographic JPGs, packshots. Retrieved 2026-11-05.

## Colours
- **Brand red `#E11339`**: logo banner in the supplied logo. The site's logo-header.png uses `#E01A38`, which is the same red.
- Red on packs and in banners, sampled from images: pack band `#E40C30`. Banner field `#D01B2C`, darkening to `#AE0D17` and `#8D0408` at the vignetted edges. The packshot backdrop is red textured paper with a dark vignette.
- **Black / charcoal**: tenant `--primary-color: #000000` (nav bar, buttons, links). `--cta-color: #464241` (dark warm grey). Dark slide background `#130F10`.
- **Warm neutrals**: `--section-color: #F2EBE3` (cream section background). Pack cream sampled at `#F0DECC` and `#F6EAD8`.
- **Caramel / bread browns**: `--product-section-color: #BA834A` and `--product-cta-color: #8B653E`.
- **Gold accent** (serif headline accents in banners, sampled): about `#E8C088`.
- Text: body `#212529`, muted `#676767`. The base theme's `#2E6836` green is overridden by the tenant colours and is not GaliCrisp's.
- Flavour colour-coding on pack flavour bars (inferred from packshots): teal (3 seeds), olive/lime green (pumpkin & cheese, herbs), orange (cheese), dark red (tomato), purple (caramelised onion), navy (superseeds), black (protein).

## Typography
- **Oswald** (self-hosted TTFs, ExtraLight to Bold; it is a Google Font). Used for `.page-title` and `.title` (uppercase), the nav and top bar (uppercase), and category names (Oswald-Light, 2rem).
- **Bahnschrift** (Microsoft DIN-style font, self-hosted, *not* on Google Fonts). Used for the body (`Bahnschrift-SemiLight`), subtitles (`Bahnschrift-Regular`) and emphasis (`SemiBold`). Closest Google Font: **Barlow** (or *Barlow Semi Condensed*; *D-DIN* is not on Google Fonts).
- `Darkwoman` is declared in @font-face, but no selector uses it.
- No Google Fonts `<link>` on the site. Font Awesome 5 is used for social icons.
- Banner and slider headlines use a high-contrast Didone-style serif ("Dlaczego GaliCrisp?", "Feel the Crunch"). The face is not in the CSS because it is baked into the images. Inferred closest: **Playfair Display** or **Bodoni Moda**, light/regular weight. Banner small caps look like a DIN face, so Bahnschrift/Barlow (inferred).
- Logo wordmark: rounded, heavy humanist sans. Inferred closest: **Baloo 2 ExtraBold** or **Nunito Black**. Always use the logo image rather than re-typesetting the wordmark.

## Logo
- White, rounded, bold "GaliCrisp" wordmark on a red, slightly rotated or slanted parallelogram banner. The letters have a thin outline and overhang the banner edges (the "G" on the left and the "p" on the right).
- The header version is red with white letters. The footer version (logo-footer.png) is all-white for dark or red backgrounds.
- On packs the logo sits in the red band at the top of a cream label. Directly under it is a small uppercase line name ("CRISPBREAD", "FOCACCIA SNACK"…), then a coloured flavour bar.

## Photography and packaging
- **Packshots**: front-on pack renders centred on a red textured backdrop. One or two round cream claim badges sit at the lower right ("LOW SUGARS", "SOURCE OF FIBRE", "SUITABLE FOR VEGETARIAN", "WITH WHEAT SOURDOUGH", "26g PROTEIN"; PL "NISKA ZAWARTOŚĆ CUKRÓW", "ŹRÓDŁO BŁONNIKA", "ODPOWIEDNI dla WEGETARIAN").
- **Packs**: cream/beige label with a red top band. Formats are a window bag (crispbread), a tall flow-wrap (flatbread, focaccia), a carton (crackers, crispies, straws) and a clear bag (wholegrain). Each pack has a food illustration or photo of its ingredients.
- **Lifestyle**: warm, moody food photography. Crispbread on slate or ceramic boards with figs, grapes and seeds, dark (`#130F10`) or red backdrops, and flour-dusted hands kneading dough. There are also production-line shots (gloved hands, seed toppings).

## Tone of voice and claims (quoted exactly)
- The tone is B2B and confident, built on partnership, craft and heritage. Short, two-part serif headlines.
- Slider and banner claims: "Feel the Crunch", "Twój Produkt. Nasza Ekspertyza.", "Twój Brand Nasze Doświadczenie.", "Dlaczego GaliCrisp?", "Przekąski z potencjałem", "Rozwijaj biznes z naszymi produktami", "Jakość, doświadczenie i innowacja w każdym naszym produkcie."
- Home: "Jakość, Doświadczenie, Elastyczność oraz Innowacja. To filary, które towarzyszą nam od ponad 30 lat…". EN: "Quality, Experience, Flexibility and Innovation."
- About: "Wierzymy w siłę lepszych pomysłów.", "Najlepsze produkty nie powstają przez przypadek.", "To tworzenie czegoś, czym warto się dzielić."
- Quality page: "Jakość zaczyna się od ludzi.", "Gotowe na Twój rynek".
- Proof numbers: "30+ lat doświadczenia", "20+ rynków eksportowych", "35+ kategorii produktów". Craft cues: natural sourdough ("naturalny zakwas", ~24h), long fermentation, wholemeal flours, olive oil. The chairman is a "Mistrz Piekarnictwa".
- CTAs: "Sprawdź ofertę", "Poznaj Nas", "Współpraca", "Zostań partnerem", "Poznaj możliwości Private Label".

## Product range naming (as on site; names are uppercase, with "&" between flavours and the weight shown as "g")
- Categories in PL / EN: PIECZYWO CHRUPKIE / CRISPBREAD; KRAKERSY / CRACKERS; SNACKI PIEKARNICZE / BAKERY SNACKS; PRZEKĄSKI WYTRAWNE / SAVOURY BISQUITS (spelled this way on the site).
- Crispbread lines: Classic CRISPBREAD 135 g and 180 g; DELI CRISPBREAD 180 g; ARTISAN CRISPBREAD 120 g; WHOLEGRAIN CRISPBREAD 200 g; PROTEIN CRISPBREAD 180 g (PL "wysokobiałkowe"). Flatbread: FLATBREAD 130 g (PL "PIECZYWKO"; the packs say "CRISPY FLATBREAD").
- Crackers: DELI CRACKERS 100 g and 130 g (PL "KRAKERSY DELI", "NA ZAKWASIE" = sourdough); PREMIUM RYE CRACKERS 130 g (PL "KRAKERSY ŻYTNIE PREMIUM").
- Bakery snacks: DIP FOCACCIA 120 g and FOCACCIA SNACK 100 g. Savoury: CRISPIES 90 g, STRAWS 100 g, MINI STRAWS 100 g.
- Flavours: 3 SEEDS, PUMPKIN & CHEESE, CHEESE & TOMATO, CHEESE & ONION, CARAMELIZED ONION, SUPERSEEDS, TRIPLE CHEESE / 3 CHEESES, TOMATO & BASIL, SESAME & BEETROOT, OLIVE OIL & SEA SALT, OLIVE OIL & HERBS, GOUDA CHEESE, SEEDS & GOUDA CHEESE, ROSEMARY & SEA SALT. PL-only: ZIOŁA PROWANSALSKIE.

## Motifs and icons
- Thin white line icons joined by a dotted path with node dots: TRADYCJA, JAKOŚĆ (shield with tick), INNOWACJA (bulb), ELASTYCZNOŚĆ (puzzle), PRZYSZŁOŚĆ (clock), "30+" in a circle.
- Round claim badges with line pictograms (wheat ear, leaf, arrow-down sugar cube).
- Pill-shaped buttons: black, or red with white text. Scattered crispbread pieces and seeds are used as decoration. A sketch-style baker illustration appears on the about page (baker.png).

## Assets in this folder
- logo.png: the supplied logo, tightly cropped, with only the outside white made transparent (251×107). logo_site.png: the site header logo (420×204, native transparency, sharper), which is the better of the two. logo.datauri.txt: logo_site, quantized to 64 colours, about 6.6 KB.
- hero.webp: the "Poznaj GaliCrisp – Feel the Crunch" homepage slide (1140×392), from https://www.galicrisp.pl/media/cache/homepage_top_slider/images/slides/2026/09/28/whatsapp-image-2026-10-27-at-13-20-28-1-6ae09816abc5b916035676.jpg
