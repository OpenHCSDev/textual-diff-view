## Native original declaration, Toad271 integration owner

Sourceb904a98, based on normal mainf6d3cdd. Original LineAnnotations.get_content_width returns its own number width and get_content_height returns its own row count. Declare both via existing height_dependency(INDEPENDENT_HEIGHT); all ordinary diff and inherited prepared patch consumers use this original definition. Three production lines added, no duplicated implementation/state/cache.

Paired Textual native-width declaration draft and Toad271 integration are required. Unknown subclass overrides stay conservative. Bounded actual native resize, content/style/member and relative/custom-hook controls pending; no CPU/original41MB/warm/default READY claim.
