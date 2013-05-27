# Sud Web Newsletter Templates

Here are the Mailchimp templates used by Sud Web for its emailing needs.  
Versionned files makes it easier for us to keep track of updates and fix things more easily.

Every template is living in its own folder in `src`, alongside its related materials.

Goals and objectives:
- convert existing templates and used materials to this repository
- migrate to `juice` to create proper templates with automatic CSS inlining
- migrate layouts to the new Sud Web identify (cf. [2013 website](http://sudweb.fr/2013/))

## Install

**Note**: this is a future perspective, it's not working yet.

The tooling rely on `node.js` and `npm` for components dependencies.

```bash
npm install -g grunt-cli
npm install
```

You then need to run the following command to automatically rebuild the inlined and usable HTML templates:

```bash
grunt watch
```
