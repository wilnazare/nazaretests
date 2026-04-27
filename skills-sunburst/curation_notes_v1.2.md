# Skills Sunburst Curation v1.2

Canonical phrase-family rollup on top of v1.1.

What changed:
- Collapsed nested phrase variants inside each subskill, e.g. instructional design / instructional design expertise / instructional design principles now display as instructional design.
- Kept slice sizing based on unique JD files, so one advert still only contributes once to a subskill JD frequency.
- Dampened weighted score inflation by scoring canonical phrase families rather than every extracted n-gram variant.
- Added source phrase maps so each canonical phrase can still be traced back to the raw extracted phrases.

Counts still use the same de-duplicated 100-JD corpus baseline.
