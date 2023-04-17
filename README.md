# Updater test


## Steps

- Make a branch called `v1.2` (where `1` and `2` reflect the new version number)
- Drop all the new files inside the repo
- Delete this README.md in that branch
- Stage and commit and push
- Make a new release from the branch https://github.com/Flam9/test123/releases/new
  - Tag is the version number, without the `v` prefix. eg: `1.2`
  - Target is this new branch we just pushed up
  - Title is the same as the tag, eg: `1.2`
  - Description is what we updated, shown to the user
  - Set as pre-release while testing. **If it's not a pre-release, users will get the new update! beware!**





## TODO

- Upload ZIP ourselves or let github generate it?
- File deletion. Maybe akin to requirements.txt?
