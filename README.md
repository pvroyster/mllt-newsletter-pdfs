# mllt-newsletter-pdfs

Public source PDFs for the Texas Roots Weekly flipbooks on Heyzine, served to
Heyzine through jsDelivr at a URL pinned to a commit.

**One rule: every commit's file tree holds only the PDFs being uploaded in
that push.** Delete the previous files in the same commit that adds new ones.
jsDelivr refuses to serve a repository snapshot larger than 50 MB, and a
pinned URL reads the snapshot *at its own commit*, so removing old files never
breaks a link already handed to Heyzine. Git history keeps every file.

Never force-push or rewrite history here: that would break the pinned links.
