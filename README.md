# Dachshund stencil illustration

The delivered image is **[artifacts/image.png](artifacts/image.png)**: one miniature dachshund trotting in profile toward the left, rendered as chunky cobalt-blue ink shapes on a white field. The long low body, short legs in stride, long snout, hanging ear, lifted curved tail, rough brush edges, and white stencil gaps are visible. The animal is centered with generous margins, with no text, scenery, outline, or cast shadow.

The final image is a **4800 × 3600 pixel, 4:3 landscape, 8-bit RGB PNG**. Resolution metadata is approximately 300 pixels per inch, equivalent to 16 × 12 inches. The image is opaque. Eight white pixels were added above and below the generator's 4800 × 3584 output to obtain exact 4:3 dimensions; all original image pixels were preserved.

Generated with the connected image service using `google/nano-banana-2.1`. The submitted creative prompt is in [prompt.txt](prompt.txt). Midjourney was unavailable in the connected catalog, and the [specified reference post](https://x.com/sergeantsref/status/2118851171087417639) returned HTTP 403. Generation therefore used the requester's written style description; exact correspondence to `--sref 2553812497` remains unverified.

Visual review was performed by inspecting the generated PNG and the final export. Known departures: the blue and white areas retain subtle raster color variation, so this is not a mathematically two-color bitmap with an entirely pure-white field; the ear has a pronounced white separating gap but lacks broad white cuts across its interior. There is no intentional tonal modeling or additional visible color family.

[result.json](result.json) records the output contract, dimensions, file checksum, validation results, and visual limitations. Local validation checks the PNG signature, chunk checksums, complete decompression, dimensions, exact aspect ratio, and preservation of the generated pixels. These checks establish file integrity; the visual observations are an agent review, not independent certification.

The PNG is the finished deliverable and needs no build or network access. It is intentionally left untracked for the assignment's separate artifact upload. Scratch files under `test/scratch/` are disposable and are not needed to view the delivered image.
