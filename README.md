# Cirrusboard-smilies
Smiley repository for Cirrusboard.

For more info about smilies see the [Wiki page](https://cirrus.voxelmanip.se/wiki/Smilies) about smilies.

## Notes
optimising smiley images:

```bash
optipng -o7 -zm1-9 -strip all -clobber *.png
```

smiley array def:

```php
$smilies = [
	'<smiley code>' => '<smiley image>',
	(rinse and repeat...)
];
```
