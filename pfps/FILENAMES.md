filename spec for the pfp images

`/^pfp_(?:([a-z]+)_)?(\d+)(tp)?(us?)$/i` where:
- group 1: short description
- group 2: resolution (perfectly square)
- group 3: image has transparent background
- group 4: image doesn't have shadow (unshaded)
