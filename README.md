# THORNEVERSE SITE - BETA VERSION
## Ready to deploy!

---

## WHAT'S INCLUDED

| File | Purpose |
|------|---------|
| `index.html` | Homepage with manifesto + 3 series |
| `ruin-series.html` | All 7 Ruin Series books listed |
| `reader-book1.html` | The Ruin In Her Eyes (16 chapters) |
| `reader-book2.html` | The Lies On Her Lips (23 chapters) |
| `reader-book3.html` | The Birth of the Demon (21 chapters) |
| `reader-book4.html` | The Silence In Her Mind (75 chapters) |
| `thorn-heights.html` | Placeholder - Coming Soon |
| `count-backwards.html` | Placeholder - Coming Soon |
| `CNAME` | Points to yaznil-cross.com |

---

## PER-BOOK CODE SYSTEM

Each book has its own codes. Readers must come back to you for the next book's code.

### BOOK 1 CODES (The Ruin In Her Eyes)
```
RUIN1-01    RUIN1-06    RUIN1-11    RUIN1-16
RUIN1-02    RUIN1-07    RUIN1-12    RUIN1-17
RUIN1-03    RUIN1-08    RUIN1-13    RUIN1-18
RUIN1-04    RUIN1-09    RUIN1-14    RUIN1-19
RUIN1-05    RUIN1-10    RUIN1-15    RUIN1-20
```

### BOOK 2 CODES (The Lies On Her Lips)
```
RUIN2-01    RUIN2-06    RUIN2-11    RUIN2-16
RUIN2-02    RUIN2-07    RUIN2-12    RUIN2-17
RUIN2-03    RUIN2-08    RUIN2-13    RUIN2-18
RUIN2-04    RUIN2-09    RUIN2-14    RUIN2-19
RUIN2-05    RUIN2-10    RUIN2-15    RUIN2-20
```

### BOOK 3 CODES (The Birth of the Demon)
```
RUIN3-01    RUIN3-06    RUIN3-11    RUIN3-16
RUIN3-02    RUIN3-07    RUIN3-12    RUIN3-17
RUIN3-03    RUIN3-08    RUIN3-13    RUIN3-18
RUIN3-04    RUIN3-09    RUIN3-14    RUIN3-19
RUIN3-05    RUIN3-10    RUIN3-15    RUIN3-20
```

### BOOK 4 CODES (The Silence In Her Mind)
```
RUIN4-01    RUIN4-06    RUIN4-11    RUIN4-16
RUIN4-02    RUIN4-07    RUIN4-12    RUIN4-17
RUIN4-03    RUIN4-08    RUIN4-13    RUIN4-18
RUIN4-04    RUIN4-09    RUIN4-14    RUIN4-19
RUIN4-05    RUIN4-10    RUIN4-15    RUIN4-20
```

### MASTER CODE (Works on ALL books)
```
YAZNIL-MASTER
```

---

## HOW TO USE THIS FOR FEEDBACK

**Example workflow:**

1. Give Reader "Tasha" code `RUIN1-05` for Book 1
2. Tasha reads Book 1
3. Tasha finishes → messages you "Done with Book 1!"
4. You ask: "What did you think? Any feedback?"
5. Tasha gives feedback
6. You give her `RUIN2-05` for Book 2
7. Repeat

**Tracking suggestion:**

| Reader | Book 1 | Book 2 | Book 3 | Book 4 | Notes |
|--------|--------|--------|--------|--------|-------|
| Tasha | RUIN1-05 | RUIN2-05 | - | - | Loved Ch 8 |
| Malik | RUIN1-12 | - | - | - | Still reading |
| Cousin | RUIN1-03 | RUIN2-03 | RUIN3-03 | RUIN4-03 | VIP reader |

---

## HOW IT WORKS FOR READERS

1. You give them a Book 1 code
2. They go to site → Ruin Series → Book 1 → Read Now
3. Enter email + their code → they're in
4. Code saved to browser (auto-login on same device)
5. Different device? Same code works again
6. Finish Book 1 → come back to you for Book 2 code
7. Book 1 code does NOT work on Book 2

---

## BOOK DETAILS

| Book | Type | Indicator |
|------|------|-----------|
| Book 1 | Dark Erotica | Heat (purple/red) |
| Book 2 | Dark Erotica | Heat (purple/red) |
| Book 3 | Psychological Horror (NO sex) | Dread (gray tones) |
| Book 4 | Extreme Dark (dubcon/noncon) | Heat + Extreme Warning |

---

## TO DEPLOY

1. Download all 10 files
2. Go to GitHub: `github.com/Yaznil-Cross/thorneverse`
3. Delete ALL old files in the repo
4. Upload ALL new files
5. Wait 2 minutes
6. Live at yaznil-cross.com

---

## TO ADD/REMOVE CODES LATER

Open the specific book's reader file (e.g., `reader-book1.html`) and find:

```javascript
const VALID_CODES = [
    'RUIN1-01','RUIN1-02', ...
];
```

Edit → Save → Push to GitHub

---

## VERSION INFO

- Reader: v3.1 (word-based pagination, ~250 words/page, button controls)
- Book 1: V1.2 (408 pages)
- Book 2: V1.1 (274 pages)
- Book 3: V1.1 (606 pages)
- Book 4: V1.1 (484 pages)

---

*Built for Yaznil.Cross | December 2025*
