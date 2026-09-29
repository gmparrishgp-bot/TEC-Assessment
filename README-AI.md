# AI placement rebuild
This branch is the replacement for the failed keyword-scored prototype. It is intentionally separate from the current GitHub Pages deployment.

Design: technician answer -> model reasoning -> per-course evidence ledger -> targeted follow-up or next domain -> binary SIGN/DON'T SIGN report.

The evaluator is instructed to credit correct shop-language reasoning and alternate diagnostic sequences rather than vocabulary matches. Weak evidence stops depth only in that area. Verbatim Q/A history is retained in assessment state. Results include evidence, CSV and email summary.

This requires a server-side reasoning model and is designed for Vercel. GitHub Pages alone cannot securely do this.