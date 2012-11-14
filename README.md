AssetFix
========

Application for fixing assets

To use this application place the file in your Joomla Root. Then browse to it, so if your root is example.com 
you would browe to example.com/assetfix.

There are currently two branches, master and j3. Both branches will run in either Joomla 2.5 or Joomla 3 sites.

The master branch will only fix articles and categories (and may not fix all categories if the problems are complex).

The newer branch, j3, will 
  Fix a corrupted root asset if possible or tell you if it is not.
  Fix extension assets 
  Rebuild the category table
  Fix article assets.

It will not fix assets for other extensions although the pattern for articles can be modified for other extensions.