Changelog
=========


1.5 (unreleased)
----------------

- Patch Password reset tool in Products.CMFPlone to use the optional volto_domain in the
  e-email which is sent to users, only if the request is made through REST.
  [fredvd]
  
- Add Volto settings control panel with frontend_domain field.
  [fredvd]


1.4 (2019-09-12)
----------------

- Re-add the link to be available.
  [sneridagh]


1.3 (2019-08-30)
----------------

- Re-add the collection to be available.
  [sneridagh]


1.2.0 (2019-08-30)
------------------

- UnPin p.restapi, because of conflicts, meh
  [sneridagh]


1.1.3 (2019-08-30)
------------------

- Pin p.restapi version.
  [sneridagh]


1.1.2 (2019-08-28)
------------------

- Update the text with more agnostic numbers.
  [sneridagh]


1.1.1 (2019-06-09)
------------------

- Update version numbers
  [sneridagh]


1.1.0 (2019-05-04)
------------------

- Documentation.
  [sneridagh]

- Clean up package, Python 3, tests.
  [sneridagh]


1.0.1 (2019-04-18)
------------------

- Fix small typos and link ranges
  [sneridagh]


1.0.0 (2019-04-18)
------------------

- Amend the text on the home page.
  [sneridagh]

- Releasing 1.0.0
  [sneridagh]


1.0.0a17 (2019-04-16)
---------------------

- Add collective.folderishtypes
  [sneridagh]


1.0.0a16 (2019-04-16)
---------------------

- Renamed optional cors configuration module, install restapi from scratch.
  [sneridagh]


1.0.0a15 (2019-04-15)
---------------------

- Add optional module with CORS ZCML.
  [sneridagh]


1.0.0a14 (2019-04-15)
---------------------

- Update to Python3 and Plone 5.2
  [sneridagh]


1.0.0a13 (2019-03-25)
---------------------

- Update versions on homepage.
  [sneridagh]


1.0.0a12 (2019-03-15)
---------------------

- Update versions on homepage.
  [sneridagh]


1.0.0a11 (2019-03-01)
---------------------

- Remove PAS plugin hack since in Volto 1.6.0 it is not required anymore.
  [sneridagh]


1.0.0a10 (2019-02-20)
---------------------

- Add a *inner* admin user to overcome the limitation on using Zope users.
  [sneridagh]


1.0.0a9 (2019-02-19)
--------------------

- Adding the PAS plugin to workaround the images/files pull from HTML.
  [sneridagh]

- Remove Event, Link and Collection type.
  [sneridagh]

1.0.0a8 (2019-02-17)
--------------------

- Updated front page.
  [sneridagh]


1.0.0a7 (2019-02-16)
--------------------

- Remove from the main nav non folderish items.
  [sneridagh]


1.0.0a6 (2019-02-15)
--------------------

- Enable editing on the Plone Site with Volto Editor :)
  [sneridagh]


1.0.0a5 (2019-02-12)
--------------------

- Remove CORS, since we put it on the buildout
  [sneridagh]


1.0.0a4 (2019-02-12)
--------------------

- Remove Homepage content type
- Add default tiles to portal the proper way
- Add title
- Add CORS default config
  [sneridagh]


1.0.0a3 (2019-02-12)
--------------------

- Fix it as json loads spects strings...
  [sneridagh]

1.0.0a2 (2019-02-12)
--------------------

- Fix not set value on site serializer.
  [sneridagh]


1.0.0a1 (2019-02-12)
--------------------

- Initial release.
  [kitconcept]
