# eTail Dossier — Task List

## Phase 1: Core Build
- [ ] Build single-page HTML/CSS/JS app (`index.html`)
- [ ] Load contacts from embedded JSON data (data/contacts.json)
- [ ] Card-based layout — each COMPANY gets a card showing all contacts underneath
- [ ] Search bar: fuzzy search across name, company, title, context
- [ ] Filter chips/dropdown by seller (Mentzer, Jack, Jessica, KJ, Eddie, Dan V, Steve Jones)
- [ ] Mobile-first responsive design (will be used on phones at conference)
- [ ] Company logos via Clearbit Logo API (`https://logo.clearbit.com/:domain`) or fallback initials
- [ ] LinkedIn profile links (one-tap open)
- [ ] PebblePost branding (Pebble Blue #1B2CCC, Deep Navy #000A62, Accent Cyan #34F3EE)

## Phase 2: Interactive Features
- [ ] Star/flag system with three states: "met" ✅, "help" 🤝, "priority" ⭐
- [ ] Flags persist in localStorage (survives refresh, no backend needed)
- [ ] Filter by flag status (show only: met, help, priority, unflagged)
- [ ] Contact count / stats bar at top

## Phase 3: Polish
- [ ] Smooth animations on search/filter
- [ ] Empty state when no results match
- [ ] "Clear filters" button
- [ ] Print-friendly mode (optional)

## Phase 4: Deploy
- [ ] Create GitHub repo (`jacobaross/etail-dossier` or as GitHub Pages on existing repo)
- [ ] Deploy to GitHub Pages
- [ ] Share URL

## Data Notes
- 40 company entries, ~55 individual contacts
- 7 sellers: Mentzer, Jack, Jessica, KJ, Eddie, Dan V, Steve Jones
- Some contacts missing LinkedIn URLs (Jack's contacts, KJ's contacts, Eddie's, Dan V's)
- One entry has "CMO" as name (Kathy Kuo Home — name not in doc)

## Design Notes
- "Marketer Facebook" vibe — clean, scannable, profile-card oriented
- Context bullets are the key differentiator — this is what makes it useful at the conference
- Seller badges should be color-coded for quick visual scanning
- Company logo prominent, contacts listed under each company
