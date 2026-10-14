# D&A Live Demo

Static page (GitHub Pages) that scores a live webcam / screen / video-file stream with the
D&A pipeline: ground -> describe -> assess (`dna_feedback`), plotting the progress array live.

Everything runs in the browser. You supply a provider (Gemini or Claude), model id and API key;
the key is sent only to that provider. Webcam access needs https (GitHub Pages) or localhost.

Deploy: push to GitHub, then Settings -> Pages -> deploy from `main` / root.
