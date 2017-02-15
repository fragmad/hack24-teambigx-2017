# Ideas

## Friendly git wrapper

After a conversation on slack with Kate from Hackspace (amongst others), it seems there's a gap in the world for a
'friendly' git client for non-technical people to use. Git is great for collaboration on things other than code, but
it's not exactly friendly to use.

I was thinking around the lines of something similar to Dropbox, where you can designate a folder that mirrors a git
repository, with all the git interaction happening in the background, alerting you when someone else has altered a
document etc.

A web interface to manage/track changes and view history could be useful here too.

## .docx diff

Along the same lines - perhaps in combination with or as a separate project, a diff tool for .docx files.

.docx files are binary so git doesn't try and diff them, but they are zip files with XML inside really so it should be
possible to have a look inside and actually do a visual diff of some kind.
