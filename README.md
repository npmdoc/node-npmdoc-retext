# api documentation for  [retext (v5.0.0)](https://github.com/wooorm/retext)  [![npm package](https://img.shields.io/npm/v/npmdoc-retext.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-retext) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-retext.svg)](https://travis-ci.org/npmdoc/node-npmdoc-retext)
#### Natural language processor powered by plugins

[![NPM](https://nodei.co/npm/retext.png?downloads=true)](https://www.npmjs.com/package/retext)

[![apidoc](https://npmdoc.github.io/node-npmdoc-retext/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-retext_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-retext/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-retext/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-retext/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Titus Wormer",
        "email": "tituswormer@gmail.com",
        "url": "http://wooorm.com"
    },
    "bugs": {
        "url": "https://github.com/wooorm/retext/issues"
    },
    "contributors": [
        {
            "name": "Titus Wormer",
            "email": "tituswormer@gmail.com",
            "url": "http://wooorm.com"
        }
    ],
    "dependencies": {
        "retext-latin": "^2.0.0",
        "retext-stringify": "^2.0.0",
        "unified": "^6.0.0"
    },
    "description": "Natural language processor powered by plugins",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "5d9018c4a677d6103c142362d76f50eb1d398bf6",
        "tarball": "https://registry.npmjs.org/retext/-/retext-5.0.0.tgz"
    },
    "engines": {
        "node": ">=0.11.0"
    },
    "files": [
        "index.js"
    ],
    "homepage": "https://github.com/wooorm/retext",
    "keywords": [
        "natural",
        "language",
        "concrete",
        "syntax",
        "tree",
        "cst",
        "parse",
        "stringify",
        "process"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "wooorm",
            "email": "tituswormer@gmail.com"
        }
    ],
    "name": "retext",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "https://github.com/wooorm/retext/tree/master/packages/retext"
    },
    "scripts": {},
    "version": "5.0.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module retext](#apidoc.module.retext)
1.  [function <span class="apidocSignatureSpan">retext.</span>Compiler (tree)](#apidoc.element.retext.Compiler)
1.  [function <span class="apidocSignatureSpan">retext.</span>Parser ()](#apidoc.element.retext.Parser)
1.  [function <span class="apidocSignatureSpan">retext.</span>Parser.super_ (doc, file)](#apidoc.element.retext.Parser.super_)
1.  [function <span class="apidocSignatureSpan">retext.</span>data (key, value)](#apidoc.element.retext.data)
1.  [function <span class="apidocSignatureSpan">retext.</span>freeze ()](#apidoc.element.retext.freeze)
1.  [function <span class="apidocSignatureSpan">retext.</span>parse (doc)](#apidoc.element.retext.parse)
1.  [function <span class="apidocSignatureSpan">retext.</span>process (doc, cb)](#apidoc.element.retext.process)
1.  [function <span class="apidocSignatureSpan">retext.</span>processSync (doc)](#apidoc.element.retext.processSync)
1.  [function <span class="apidocSignatureSpan">retext.</span>run (node, file, cb)](#apidoc.element.retext.run)
1.  [function <span class="apidocSignatureSpan">retext.</span>runSync (node, file)](#apidoc.element.retext.runSync)
1.  [function <span class="apidocSignatureSpan">retext.</span>stringify (node, doc)](#apidoc.element.retext.stringify)
1.  [function <span class="apidocSignatureSpan">retext.</span>use (value)](#apidoc.element.retext.use)
1.  object <span class="apidocSignatureSpan">retext.</span>Parser.super_.prototype
1.  object <span class="apidocSignatureSpan">retext.</span>Parser.super_.prototype.tokenizeParagraphPlugins
1.  object <span class="apidocSignatureSpan">retext.</span>Parser.super_.prototype.tokenizeRootPlugins
1.  object <span class="apidocSignatureSpan">retext.</span>Parser.super_.prototype.tokenizeSentencePlugins
1.  object <span class="apidocSignatureSpan">retext.</span>attachers

#### [module retext.Parser](#apidoc.module.retext.Parser)
1.  [function <span class="apidocSignatureSpan">retext.</span>Parser ()](#apidoc.element.retext.Parser.Parser)
1.  [function <span class="apidocSignatureSpan">retext.Parser.</span>super_ (doc, file)](#apidoc.element.retext.Parser.super_)

#### [module retext.Parser.super_](#apidoc.module.retext.Parser.super_)
1.  [function <span class="apidocSignatureSpan">retext.Parser.</span>super_ (doc, file)](#apidoc.element.retext.Parser.super_.super_)

#### [module retext.Parser.super_.prototype](#apidoc.module.retext.Parser.super_.prototype)
1.  boolean <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>position
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>parse (value)](#apidoc.element.retext.Parser.super_.prototype.parse)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>run (key, nodes)](#apidoc.element.retext.Parser.super_.prototype.run)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenize (value)](#apidoc.element.retext.Parser.super_.prototype.tokenize)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeParagraph ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraph)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizePunctuation (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizePunctuation)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeRoot ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeRoot)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSentence ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentence)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSource (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSource)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSymbol (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSymbol)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeText (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeText)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeWhiteSpace (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeWhiteSpace)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeWord ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeWord)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>use (key, plugins)](#apidoc.element.retext.Parser.super_.prototype.use)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>useFirst (key, plugins)](#apidoc.element.retext.Parser.super_.prototype.useFirst)
1.  object <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeParagraphPlugins
1.  object <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeRootPlugins
1.  object <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSentencePlugins

#### [module retext.Parser.super_.prototype.tokenizeParagraphPlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeParagraphPlugins)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.0)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.1)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>10 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.10)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.2)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.3)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>4 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.4)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>5 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.5)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>6 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.6)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>7 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.7)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>8 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.8)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>9 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.9)

#### [module retext.Parser.super_.prototype.tokenizeRootPlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeRootPlugins)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.0)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.1)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.2)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.3)

#### [module retext.Parser.super_.prototype.tokenizeSentencePlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeSentencePlugins)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.0)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.1)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.2)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.3)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>4 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.4)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>5 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.5)
1.  [function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>6 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.6)



# <a name="apidoc.module.retext"></a>[module retext](#apidoc.module.retext)

#### <a name="apidoc.element.retext.Compiler"></a>[function <span class="apidocSignatureSpan">retext.</span>Compiler (tree)](#apidoc.element.retext.Compiler)
- description and source-code
```javascript
function compiler(tree) {
  return toString(tree);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser"></a>[function <span class="apidocSignatureSpan">retext.</span>Parser ()](#apidoc.element.retext.Parser)
- description and source-code
```javascript
function Of() {
  if (!(this instanceof Of)) {
    return new From(arguments);
  }

  return Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_"></a>[function <span class="apidocSignatureSpan">retext.</span>Parser.super_ (doc, file)](#apidoc.element.retext.Parser.super_)
- description and source-code
```javascript
function ParseLatin(doc, file) {
  var value = file || doc;

  if (!(this instanceof ParseLatin)) {
    return new ParseLatin(doc, file);
  }

  this.doc = value ? String(value) : null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.data"></a>[function <span class="apidocSignatureSpan">retext.</span>data (key, value)](#apidoc.element.retext.data)
- description and source-code
```javascript
function data(key, value) {
  if (string(key)) {
<span class="apidocCodeCommentSpan">    /* Set 'key'. */
</span>    if (arguments.length === 2) {
      assertUnfrozen('data', frozen);

      namespace[key] = value;

      return processor;
    }

    /* Get 'key'. */
    return (has(namespace, key) && namespace[key]) || null;
  }

  /* Set space. */
  if (key) {
    assertUnfrozen('data', frozen);
    namespace = key;
    return processor;
  }

  /* Get space. */
  return namespace;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.freeze"></a>[function <span class="apidocSignatureSpan">retext.</span>freeze ()](#apidoc.element.retext.freeze)
- description and source-code
```javascript
function freeze() {
  var values;
  var plugin;
  var options;
  var transformer;

  if (frozen) {
    return processor;
  }

  while (++freezeIndex < attachers.length) {
    values = attachers[freezeIndex];
    plugin = values[0];
    options = values[1];
    transformer = null;

    if (options === false) {
      return;
    }

    if (options === true) {
      values[1] = undefined;
    }

    transformer = plugin.apply(processor, values.slice(1));

    if (func(transformer)) {
      transformers.use(transformer);
    }
  }

  frozen = true;
  freezeIndex = Infinity;

  return processor;
}
```
- example usage
```shell
...
var unified = require('unified');
var latin = require('retext-latin');
var stringify = require('retext-stringify');

module.exports = unified()
.use(latin)
.use(stringify)
.freeze();
...
```

#### <a name="apidoc.element.retext.parse"></a>[function <span class="apidocSignatureSpan">retext.</span>parse (doc)](#apidoc.element.retext.parse)
- description and source-code
```javascript
function parse(doc) {
  var file = vfile(doc);
  var Parser;

  freeze();
  Parser = processor.Parser;
  assertParser('parse', Parser);

  if (newable(Parser)) {
    return new Parser(String(file), file).parse();
  }

  return Parser(String(file), file); // eslint-disable-line new-cap
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.process"></a>[function <span class="apidocSignatureSpan">retext.</span>process (doc, cb)](#apidoc.element.retext.process)
- description and source-code
```javascript
function process(doc, cb) {
  freeze();
  assertParser('process', processor.Parser);
  assertCompiler('process', processor.Compiler);

  if (!cb) {
    return new Promise(executor);
  }

  executor(null, cb);

  function executor(resolve, reject) {
    var file = vfile(doc);

    pipeline.run(processor, {file: file}, done);

    function done(err) {
      if (err) {
        reject(err);
      } else if (resolve) {
        resolve(file);
      } else {
        cb(null, file);
      }
    }
  }
}
```
- example usage
```shell
...
var profanities = require('retext-profanities');
var emoji = require('retext-emoji');
var report = require('vfile-reporter');

retext()
  .use(profanities)
  .use(emoji, {convert: 'encode'})
  .process('He’s set on beating your butt for sheriff! :cop:', function (err, file) {
    console.log(String(file));
    console.error(report(err || file));
  });
'''

Yields:
...
```

#### <a name="apidoc.element.retext.processSync"></a>[function <span class="apidocSignatureSpan">retext.</span>processSync (doc)](#apidoc.element.retext.processSync)
- description and source-code
```javascript
function processSync(doc) {
  var complete = false;
  var file;

  freeze();
  assertParser('processSync', processor.Parser);
  assertCompiler('processSync', processor.Compiler);
  file = vfile(doc);

  process(file, done);

  assertDone('processSync', 'process', complete);

  return file;

  function done(err) {
    complete = true;
    bail(err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.run"></a>[function <span class="apidocSignatureSpan">retext.</span>run (node, file, cb)](#apidoc.element.retext.run)
- description and source-code
```javascript
function run(node, file, cb) {
  assertNode(node);
  freeze();

  if (!cb && func(file)) {
    cb = file;
    file = null;
  }

  if (!cb) {
    return new Promise(executor);
  }

  executor(null, cb);

  function executor(resolve, reject) {
    transformers.run(node, vfile(file), done);

    function done(err, tree, file) {
      tree = tree || node;
      if (err) {
        reject(err);
      } else if (resolve) {
        resolve(tree);
      } else {
        cb(null, tree, file);
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.runSync"></a>[function <span class="apidocSignatureSpan">retext.</span>runSync (node, file)](#apidoc.element.retext.runSync)
- description and source-code
```javascript
function runSync(node, file) {
  var complete = false;
  var result;

  run(node, file, done);

  assertDone('runSync', 'run', complete);

  return result;

  function done(err, tree) {
    complete = true;
    bail(err);
    result = tree;
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.stringify"></a>[function <span class="apidocSignatureSpan">retext.</span>stringify (node, doc)](#apidoc.element.retext.stringify)
- description and source-code
```javascript
function stringify(node, doc) {
  var file = vfile(doc);
  var Compiler;

  freeze();
  Compiler = processor.Compiler;
  assertCompiler('stringify', Compiler);
  assertNode(node);

  if (newable(Compiler)) {
    return new Compiler(node, file).compile();
  }

  return Compiler(node, file); // eslint-disable-line new-cap
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.use"></a>[function <span class="apidocSignatureSpan">retext.</span>use (value)](#apidoc.element.retext.use)
- description and source-code
```javascript
function use(value) {
  var settings;

  assertUnfrozen('use', frozen);

  if (value === null || value === undefined) {
<span class="apidocCodeCommentSpan">    /* empty */
</span>  } else if (func(value)) {
    addPlugin.apply(null, arguments);
  } else if (typeof value === 'object') {
    if ('length' in value) {
      addList(value);
    } else {
      addPreset(value);
    }
  } else {
    throw new Error('Expected usable value, not '' + value + ''');
  }

  if (settings) {
    namespace.settings = extend(namespace.settings || {}, settings);
  }

  return processor;

  function addPreset(result) {
    addList(result.plugins);

    if (result.settings) {
      settings = extend(settings || {}, result.settings);
    }
  }

  function add(value) {
    if (func(value)) {
      addPlugin(value);
    } else if (typeof value === 'object') {
      if ('length' in value) {
        addPlugin.apply(null, value);
      } else {
        addPreset(value);
      }
    } else {
      throw new Error('Expected usable value, not '' + value + ''');
    }
  }

  function addList(plugins) {
    var length;
    var index;

    if (plugins === null || plugins === undefined) {
      /* empty */
    } else if (array(plugins)) {
      length = plugins.length;
      index = -1;

      while (++index < length) {
        add(plugins[index]);
      }
    } else {
      throw new Error('Expected a list of plugins, not '' + plugins + ''');
    }
  }

  function addPlugin(plugin, value) {
    var entry = find(plugin);

    if (entry) {
      if (plain(entry[1]) && plain(value)) {
        value = extend(entry[1], value);
      }

      entry[1] = value;
    } else {
      attachers.push(slice.call(arguments));
    }
  }
}
```
- example usage
```shell
...
'use strict';

var unified = require('unified');
var latin = require('retext-latin');
var stringify = require('retext-stringify');

module.exports = unified()
.use(latin)
.use(stringify)
.freeze();
...
```



# <a name="apidoc.module.retext.Parser"></a>[module retext.Parser](#apidoc.module.retext.Parser)

#### <a name="apidoc.element.retext.Parser.Parser"></a>[function <span class="apidocSignatureSpan">retext.</span>Parser ()](#apidoc.element.retext.Parser.Parser)
- description and source-code
```javascript
function Of() {
  if (!(this instanceof Of)) {
    return new From(arguments);
  }

  return Super.apply(this, arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_"></a>[function <span class="apidocSignatureSpan">retext.Parser.</span>super_ (doc, file)](#apidoc.element.retext.Parser.super_)
- description and source-code
```javascript
function ParseLatin(doc, file) {
  var value = file || doc;

  if (!(this instanceof ParseLatin)) {
    return new ParseLatin(doc, file);
  }

  this.doc = value ? String(value) : null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.retext.Parser.super_"></a>[module retext.Parser.super_](#apidoc.module.retext.Parser.super_)

#### <a name="apidoc.element.retext.Parser.super_.super_"></a>[function <span class="apidocSignatureSpan">retext.Parser.</span>super_ (doc, file)](#apidoc.element.retext.Parser.super_.super_)
- description and source-code
```javascript
function ParseLatin(doc, file) {
  var value = file || doc;

  if (!(this instanceof ParseLatin)) {
    return new ParseLatin(doc, file);
  }

  this.doc = value ? String(value) : null;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.retext.Parser.super_.prototype"></a>[module retext.Parser.super_.prototype](#apidoc.module.retext.Parser.super_.prototype)

#### <a name="apidoc.element.retext.Parser.super_.prototype.parse"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>parse (value)](#apidoc.element.retext.Parser.super_.prototype.parse)
- description and source-code
```javascript
parse = function (value) {
  return this.tokenizeRoot(value || this.doc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.run"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>run (key, nodes)](#apidoc.element.retext.Parser.super_.prototype.run)
- description and source-code
```javascript
function run(key, nodes) {
  var wareKey = key + 'Plugins';
  var plugins = this[wareKey];
  var index = -1;

  if (plugins) {
    while (plugins[++index]) {
      plugins[index](nodes);
    }
  }

  return nodes;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenize"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenize (value)](#apidoc.element.retext.Parser.super_.prototype.tokenize)
- description and source-code
```javascript
tokenize = function (value) {
  return tokenize(this, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraph"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeParagraph ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraph)
- description and source-code
```javascript
tokenizeParagraph = function () {
  return this.run(key, callback.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizePunctuation"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizePunctuation (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizePunctuation)
- description and source-code
```javascript
function createText(value, eat, parent) {
  if (value === null || value === undefined) {
    value = '';
  }

  return (eat || noopEat)(value)({
    type: type,
    value: String(value)
  }, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeRoot"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeRoot ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeRoot)
- description and source-code
```javascript
tokenizeRoot = function () {
  return this.run(key, callback.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentence"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSentence ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentence)
- description and source-code
```javascript
tokenizeSentence = function () {
  return this.run(key, callback.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSource"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSource (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSource)
- description and source-code
```javascript
function createText(value, eat, parent) {
  if (value === null || value === undefined) {
    value = '';
  }

  return (eat || noopEat)(value)({
    type: type,
    value: String(value)
  }, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSymbol"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeSymbol (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSymbol)
- description and source-code
```javascript
function createText(value, eat, parent) {
  if (value === null || value === undefined) {
    value = '';
  }

  return (eat || noopEat)(value)({
    type: type,
    value: String(value)
  }, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeText"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeText (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeText)
- description and source-code
```javascript
function createText(value, eat, parent) {
  if (value === null || value === undefined) {
    value = '';
  }

  return (eat || noopEat)(value)({
    type: type,
    value: String(value)
  }, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeWhiteSpace"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeWhiteSpace (value, eat, parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeWhiteSpace)
- description and source-code
```javascript
function createText(value, eat, parent) {
  if (value === null || value === undefined) {
    value = '';
  }

  return (eat || noopEat)(value)({
    type: type,
    value: String(value)
  }, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeWord"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>tokenizeWord ()](#apidoc.element.retext.Parser.super_.prototype.tokenizeWord)
- description and source-code
```javascript
tokenizeWord = function () {
  return this.run(key, callback.apply(this, arguments));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.use"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>use (key, plugins)](#apidoc.element.retext.Parser.super_.prototype.use)
- description and source-code
```javascript
function use(key, plugins) {
  var self = this;
  var wareKey;

<span class="apidocCodeCommentSpan">  /* Throw if the method is not pluggable. */
</span>  if (!(key in self)) {
    throw new Error(
      'Illegal Invocation: Unsupported 'key' for ' +
      ''use(key, plugins)'. Make sure 'key' is a ' +
      'supported function'
    );
  }

  /* Fail silently when no plugins are given. */
  if (!plugins) {
    return;
  }

  wareKey = key + 'Plugins';

  /* Make sure 'plugins' is a list. */
  if (typeof plugins === 'function') {
    plugins = [plugins];
  } else {
    plugins = plugins.concat();
  }

  /* Make sure 'wareKey' exists. */
  if (!self[wareKey]) {
    self[wareKey] = [];
  }

  /* Invoke callback with the ware key and plugins. */
  callback(self, wareKey, plugins);
}
```
- example usage
```shell
...
'use strict';

var unified = require('unified');
var latin = require('retext-latin');
var stringify = require('retext-stringify');

module.exports = unified()
.use(latin)
.use(stringify)
.freeze();
...
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.useFirst"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.</span>useFirst (key, plugins)](#apidoc.element.retext.Parser.super_.prototype.useFirst)
- description and source-code
```javascript
function use(key, plugins) {
  var self = this;
  var wareKey;

<span class="apidocCodeCommentSpan">  /* Throw if the method is not pluggable. */
</span>  if (!(key in self)) {
    throw new Error(
      'Illegal Invocation: Unsupported 'key' for ' +
      ''use(key, plugins)'. Make sure 'key' is a ' +
      'supported function'
    );
  }

  /* Fail silently when no plugins are given. */
  if (!plugins) {
    return;
  }

  wareKey = key + 'Plugins';

  /* Make sure 'plugins' is a list. */
  if (typeof plugins === 'function') {
    plugins = [plugins];
  } else {
    plugins = plugins.concat();
  }

  /* Make sure 'wareKey' exists. */
  if (!self[wareKey]) {
    self[wareKey] = [];
  }

  /* Invoke callback with the ware key and plugins. */
  callback(self, wareKey, plugins);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.retext.Parser.super_.prototype.tokenizeParagraphPlugins"></a>[module retext.Parser.super_.prototype.tokenizeParagraphPlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeParagraphPlugins)

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.0"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.0)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.1"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.1)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.10"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>10 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.10)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.2"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.2)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.3"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.3)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.4"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>4 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.4)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.5"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>5 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.5)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.6"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>6 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.6)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.7"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>7 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.7)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.8"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>8 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.8)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.9"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeParagraphPlugins.</span>9 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeParagraphPlugins.9)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.retext.Parser.super_.prototype.tokenizeRootPlugins"></a>[module retext.Parser.super_.prototype.tokenizeRootPlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeRootPlugins)

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.0"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.0)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.1"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.1)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.2"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.2)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.3"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeRootPlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeRootPlugins.3)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.retext.Parser.super_.prototype.tokenizeSentencePlugins"></a>[module retext.Parser.super_.prototype.tokenizeSentencePlugins](#apidoc.module.retext.Parser.super_.prototype.tokenizeSentencePlugins)

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.0"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>0 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.0)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.1"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>1 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.1)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.2"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>2 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.2)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.3"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>3 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.3)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.4"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>4 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.4)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.5"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>5 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.5)
- description and source-code
```javascript
function iterator(parent) {
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'modifier'');
  }

  return iterate(children, callback, parent);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.6"></a>[function <span class="apidocSignatureSpan">retext.Parser.super_.prototype.tokenizeSentencePlugins.</span>6 (parent)](#apidoc.element.retext.Parser.super_.prototype.tokenizeSentencePlugins.6)
- description and source-code
```javascript
function visitor(parent) {
  var index = -1;
  var children = parent && parent.children;

  if (!children) {
    throw new Error('Missing children in 'parent' for 'visitor'');
  }

  while (++index in children) {
    callback(children[index], index, parent);
  }
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
