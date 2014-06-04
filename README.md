fammin
======

the absolute minimum to get going with famous and meteor.

using hacked require.js and the prebuilt [single-file famous their gitrepo](https://github.com/Famous/famous/tree/master/dist) This makes it easy to update famous.

note that we had to modify require.js to work with meteor, [see the end of](https://github.com/dcsan/fammin/blob/master/app/client/lib/02-require.js#L2080)
	client/lib/02-require.js

however, this technique is just placing our own app code in the /public/ directory and allowing require.js to load it - not an optimal or "meteor like" way to do things at all.
