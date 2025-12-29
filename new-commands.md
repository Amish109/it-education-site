- git branch -r (to show all branch including origin)
- git checkout -b (to create and switch to new branch)
- git merge fixes (from main - to branch u wanna merge. the fixes branch in)
- git log (shows the commit historys)

# TAGS
## ANNOTATED TAG (Which is for relaease , and it will be visible to all members of github) / (without annoted just remove '-a' it will be just for us)
git tag -a v0.1.0 -m "First release : Basic structure of website complete

Features included :
- Responsive navigation
- Hero section with CTA
- Learning path timeline
- Technology stack grid
- Technology stack grid
- Students testimonials
- Contact form with validation
- Professional footer
- Global UI polish
"

## Show tag
git tag -l
git show v0.1.0

## Push tag
git push origin v0.1.0















A pre-release is a version that’s not considered stable yet. It’s meant for:

Testing

Early access

Feedback

QA / internal users

Examples:

v1.0.0-beta

v2.0.0-alpha

v1.1.0-rc.1