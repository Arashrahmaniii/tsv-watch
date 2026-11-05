# TSV Watch: issuer objections to tokenized trading

The SEC's temporary Innovation Exemption (Release No. 34-106402, September 17, 2026) lets
Tokenized Securities Venues trade tokenized US stocks after notifying the issuer, who may object
within 30 days of receiving the notice. Each venue lists objections in its own public notice.
This repository is the combined list, rebuilt daily from every venue's notice.

- Site: https://arashrahmaniii.github.io/tsv-watch/
- Data: `objections.csv`, `objections.json`, `venues.json`, RSS `feed.xml`
- Each row links to the venue notice that first lists the objection; every notice version is
  identified by its SHA-256 hash.
- `verify/` holds an Ed25519-signed manifest of the data files. A valid signature proves the files
  are unchanged since signing, not that the facts are correct; check them against the linked notices.

Facts only. Inclusion on the SEC's venue list is not an approval. Receipt dates of Issuer Notices are
not public, so no objection deadlines are calculated. Not legal or investment advice.

Data licence: CC BY 4.0. Cite as: TSV Watch, "Issuer objections to tokenized trading", https://arashrahmaniii.github.io/tsv-watch/
Contact: arashrahmaniii696@gmail.com
