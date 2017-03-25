# api documentation for  [lodash (v4.17.4)](https://lodash.com/)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lodash.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lodash)
#### Lodash modular utilities.

[![NPM](https://nodei.co/npm/lodash.png?downloads=true)](https://www.npmjs.com/package/lodash)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lodash/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-lodash_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lodash/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-lodash/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "John-David Dalton",
        "email": "john.david.dalton@gmail.com",
        "url": "http://allyoucanleet.com/"
    },
    "bugs": {
        "url": "https://github.com/lodash/lodash/issues"
    },
    "contributors": [
        {
            "name": "John-David Dalton",
            "email": "john.david.dalton@gmail.com",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Mathias Bynens",
            "email": "mathias@qiwi.be",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {},
    "description": "Lodash modular utilities.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "78203a4d1c328ae1d86dca6460e369b57f4055ae",
        "tarball": "https://registry.npmjs.org/lodash/-/lodash-4.17.4.tgz"
    },
    "homepage": "https://lodash.com/",
    "icon": "https://lodash.com/icon.svg",
    "keywords": [
        "modules",
        "stdlib",
        "util"
    ],
    "license": "MIT",
    "main": "lodash.js",
    "maintainers": [
        {
            "name": "jdalton",
            "email": "john.david.dalton@gmail.com"
        },
        {
            "name": "mathias",
            "email": "mathias@qiwi.be"
        }
    ],
    "name": "lodash",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/lodash.git"
    },
    "scripts": {
        "test": "echo \"See https://travis-ci.org/lodash/lodash-cli for testing details.\""
    },
    "version": "4.17.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module lodash](#apidoc.module.lodash)
1.  function <span class="apidocSignatureSpan">lodash.</span>_
1.  [function <span class="apidocSignatureSpan">lodash.</span>add (value, other)](#apidoc.element.lodash.add)
1.  [function <span class="apidocSignatureSpan">lodash.</span>after (n, func)](#apidoc.element.lodash.after)
1.  [function <span class="apidocSignatureSpan">lodash.</span>ary (func, n, guard)](#apidoc.element.lodash.ary)
1.  [function <span class="apidocSignatureSpan">lodash.</span>assign (object, sources)](#apidoc.element.lodash.assign)
1.  [function <span class="apidocSignatureSpan">lodash.</span>assignIn (object, sources)](#apidoc.element.lodash.assignIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>assignInWith (object, sources)](#apidoc.element.lodash.assignInWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>assignWith (object, sources)](#apidoc.element.lodash.assignWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>at (object, paths)](#apidoc.element.lodash.at)
1.  [function <span class="apidocSignatureSpan">lodash.</span>attempt (func, args)](#apidoc.element.lodash.attempt)
1.  [function <span class="apidocSignatureSpan">lodash.</span>before (n, func)](#apidoc.element.lodash.before)
1.  [function <span class="apidocSignatureSpan">lodash.</span>bind (func, thisArg, partials)](#apidoc.element.lodash.bind)
1.  [function <span class="apidocSignatureSpan">lodash.</span>bindAll (object, methodNames)](#apidoc.element.lodash.bindAll)
1.  [function <span class="apidocSignatureSpan">lodash.</span>bindKey (object, key, partials)](#apidoc.element.lodash.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash.</span>camelCase (string)](#apidoc.element.lodash.camelCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>capitalize (string)](#apidoc.element.lodash.capitalize)
1.  [function <span class="apidocSignatureSpan">lodash.</span>castArray ()](#apidoc.element.lodash.castArray)
1.  [function <span class="apidocSignatureSpan">lodash.</span>ceil (number, precision)](#apidoc.element.lodash.ceil)
1.  [function <span class="apidocSignatureSpan">lodash.</span>chain (value)](#apidoc.element.lodash.chain)
1.  [function <span class="apidocSignatureSpan">lodash.</span>chunk (array, size, guard)](#apidoc.element.lodash.chunk)
1.  [function <span class="apidocSignatureSpan">lodash.</span>clamp (number, lower, upper)](#apidoc.element.lodash.clamp)
1.  [function <span class="apidocSignatureSpan">lodash.</span>clone (value)](#apidoc.element.lodash.clone)
1.  [function <span class="apidocSignatureSpan">lodash.</span>cloneDeep (value)](#apidoc.element.lodash.cloneDeep)
1.  [function <span class="apidocSignatureSpan">lodash.</span>cloneDeepWith (value, customizer)](#apidoc.element.lodash.cloneDeepWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>cloneWith (value, customizer)](#apidoc.element.lodash.cloneWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>compact (array)](#apidoc.element.lodash.compact)
1.  [function <span class="apidocSignatureSpan">lodash.</span>concat ()](#apidoc.element.lodash.concat)
1.  [function <span class="apidocSignatureSpan">lodash.</span>cond (pairs)](#apidoc.element.lodash.cond)
1.  [function <span class="apidocSignatureSpan">lodash.</span>conforms (source)](#apidoc.element.lodash.conforms)
1.  [function <span class="apidocSignatureSpan">lodash.</span>conformsTo (object, source)](#apidoc.element.lodash.conformsTo)
1.  [function <span class="apidocSignatureSpan">lodash.</span>constant (value)](#apidoc.element.lodash.constant)
1.  [function <span class="apidocSignatureSpan">lodash.</span>countBy (collection, iteratee)](#apidoc.element.lodash.countBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>create (prototype, properties)](#apidoc.element.lodash.create)
1.  [function <span class="apidocSignatureSpan">lodash.</span>curry (func, arity, guard)](#apidoc.element.lodash.curry)
1.  [function <span class="apidocSignatureSpan">lodash.</span>curryRight (func, arity, guard)](#apidoc.element.lodash.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>debounce (func, wait, options)](#apidoc.element.lodash.debounce)
1.  [function <span class="apidocSignatureSpan">lodash.</span>deburr (string)](#apidoc.element.lodash.deburr)
1.  [function <span class="apidocSignatureSpan">lodash.</span>defaultTo (value, defaultValue)](#apidoc.element.lodash.defaultTo)
1.  [function <span class="apidocSignatureSpan">lodash.</span>defaults (args)](#apidoc.element.lodash.defaults)
1.  [function <span class="apidocSignatureSpan">lodash.</span>defaultsDeep (args)](#apidoc.element.lodash.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">lodash.</span>defer (func, args)](#apidoc.element.lodash.defer)
1.  [function <span class="apidocSignatureSpan">lodash.</span>delay (func, wait, args)](#apidoc.element.lodash.delay)
1.  [function <span class="apidocSignatureSpan">lodash.</span>difference (array, values)](#apidoc.element.lodash.difference)
1.  [function <span class="apidocSignatureSpan">lodash.</span>differenceBy (array, values)](#apidoc.element.lodash.differenceBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>differenceWith (array, values)](#apidoc.element.lodash.differenceWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>divide (value, other)](#apidoc.element.lodash.divide)
1.  [function <span class="apidocSignatureSpan">lodash.</span>drop (array, n, guard)](#apidoc.element.lodash.drop)
1.  [function <span class="apidocSignatureSpan">lodash.</span>dropRight (array, n, guard)](#apidoc.element.lodash.dropRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>dropRightWhile (array, predicate)](#apidoc.element.lodash.dropRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash.</span>dropWhile (array, predicate)](#apidoc.element.lodash.dropWhile)
1.  [function <span class="apidocSignatureSpan">lodash.</span>each (collection, iteratee)](#apidoc.element.lodash.each)
1.  [function <span class="apidocSignatureSpan">lodash.</span>eachRight (collection, iteratee)](#apidoc.element.lodash.eachRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>endsWith (string, target, position)](#apidoc.element.lodash.endsWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>entries (object)](#apidoc.element.lodash.entries)
1.  [function <span class="apidocSignatureSpan">lodash.</span>entriesIn (object)](#apidoc.element.lodash.entriesIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>eq (value, other)](#apidoc.element.lodash.eq)
1.  [function <span class="apidocSignatureSpan">lodash.</span>escape (string)](#apidoc.element.lodash.escape)
1.  [function <span class="apidocSignatureSpan">lodash.</span>escapeRegExp (string)](#apidoc.element.lodash.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">lodash.</span>every (collection, predicate, guard)](#apidoc.element.lodash.every)
1.  [function <span class="apidocSignatureSpan">lodash.</span>extend (object, sources)](#apidoc.element.lodash.extend)
1.  [function <span class="apidocSignatureSpan">lodash.</span>extendWith (object, sources)](#apidoc.element.lodash.extendWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>fill (array, value, start, end)](#apidoc.element.lodash.fill)
1.  [function <span class="apidocSignatureSpan">lodash.</span>filter (collection, predicate)](#apidoc.element.lodash.filter)
1.  [function <span class="apidocSignatureSpan">lodash.</span>find (collection, predicate, fromIndex)](#apidoc.element.lodash.find)
1.  [function <span class="apidocSignatureSpan">lodash.</span>findIndex (array, predicate, fromIndex)](#apidoc.element.lodash.findIndex)
1.  [function <span class="apidocSignatureSpan">lodash.</span>findKey (object, predicate)](#apidoc.element.lodash.findKey)
1.  [function <span class="apidocSignatureSpan">lodash.</span>findLast (collection, predicate, fromIndex)](#apidoc.element.lodash.findLast)
1.  [function <span class="apidocSignatureSpan">lodash.</span>findLastIndex (array, predicate, fromIndex)](#apidoc.element.lodash.findLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash.</span>findLastKey (object, predicate)](#apidoc.element.lodash.findLastKey)
1.  [function <span class="apidocSignatureSpan">lodash.</span>first (array)](#apidoc.element.lodash.first)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flatMap (collection, iteratee)](#apidoc.element.lodash.flatMap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flatMapDeep (collection, iteratee)](#apidoc.element.lodash.flatMapDeep)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flatMapDepth (collection, iteratee, depth)](#apidoc.element.lodash.flatMapDepth)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flatten (array)](#apidoc.element.lodash.flatten)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flattenDeep (array)](#apidoc.element.lodash.flattenDeep)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flattenDepth (array, depth)](#apidoc.element.lodash.flattenDepth)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flip (func)](#apidoc.element.lodash.flip)
1.  [function <span class="apidocSignatureSpan">lodash.</span>floor (number, precision)](#apidoc.element.lodash.floor)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flow (funcs)](#apidoc.element.lodash.flow)
1.  [function <span class="apidocSignatureSpan">lodash.</span>flowRight (funcs)](#apidoc.element.lodash.flowRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forEach (collection, iteratee)](#apidoc.element.lodash.forEach)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forEachRight (collection, iteratee)](#apidoc.element.lodash.forEachRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forIn (object, iteratee)](#apidoc.element.lodash.forIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forInRight (object, iteratee)](#apidoc.element.lodash.forInRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forOwn (object, iteratee)](#apidoc.element.lodash.forOwn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>forOwnRight (object, iteratee)](#apidoc.element.lodash.forOwnRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>fromPairs (pairs)](#apidoc.element.lodash.fromPairs)
1.  [function <span class="apidocSignatureSpan">lodash.</span>functions (object)](#apidoc.element.lodash.functions)
1.  [function <span class="apidocSignatureSpan">lodash.</span>functionsIn (object)](#apidoc.element.lodash.functionsIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>get (object, path, defaultValue)](#apidoc.element.lodash.get)
1.  [function <span class="apidocSignatureSpan">lodash.</span>groupBy (collection, iteratee)](#apidoc.element.lodash.groupBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>gt (value, other)](#apidoc.element.lodash.gt)
1.  [function <span class="apidocSignatureSpan">lodash.</span>gte (value, other)](#apidoc.element.lodash.gte)
1.  [function <span class="apidocSignatureSpan">lodash.</span>has (object, path)](#apidoc.element.lodash.has)
1.  [function <span class="apidocSignatureSpan">lodash.</span>hasIn (object, path)](#apidoc.element.lodash.hasIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>head (array)](#apidoc.element.lodash.head)
1.  [function <span class="apidocSignatureSpan">lodash.</span>identity (value)](#apidoc.element.lodash.identity)
1.  [function <span class="apidocSignatureSpan">lodash.</span>inRange (number, start, end)](#apidoc.element.lodash.inRange)
1.  [function <span class="apidocSignatureSpan">lodash.</span>includes (collection, value, fromIndex, guard)](#apidoc.element.lodash.includes)
1.  [function <span class="apidocSignatureSpan">lodash.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash.indexOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>initial (array)](#apidoc.element.lodash.initial)
1.  [function <span class="apidocSignatureSpan">lodash.</span>intersection (arrays)](#apidoc.element.lodash.intersection)
1.  [function <span class="apidocSignatureSpan">lodash.</span>intersectionBy (arrays)](#apidoc.element.lodash.intersectionBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>intersectionWith (arrays)](#apidoc.element.lodash.intersectionWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>invert (object, iteratee)](#apidoc.element.lodash.invert)
1.  [function <span class="apidocSignatureSpan">lodash.</span>invertBy (object, iteratee)](#apidoc.element.lodash.invertBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>invoke (object, path, args)](#apidoc.element.lodash.invoke)
1.  [function <span class="apidocSignatureSpan">lodash.</span>invokeMap (collection, path, args)](#apidoc.element.lodash.invokeMap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isArguments (value)](#apidoc.element.lodash.isArguments)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isArray ()](#apidoc.element.lodash.isArray)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isArrayBuffer (value)](#apidoc.element.lodash.isArrayBuffer)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isArrayLike (value)](#apidoc.element.lodash.isArrayLike)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isArrayLikeObject (value)](#apidoc.element.lodash.isArrayLikeObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isBoolean (value)](#apidoc.element.lodash.isBoolean)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isBuffer (b)](#apidoc.element.lodash.isBuffer)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isDate (value)](#apidoc.element.lodash.isDate)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isElement (value)](#apidoc.element.lodash.isElement)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isEmpty (value)](#apidoc.element.lodash.isEmpty)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isEqual (value, other)](#apidoc.element.lodash.isEqual)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isEqualWith (value, other, customizer)](#apidoc.element.lodash.isEqualWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isError (value)](#apidoc.element.lodash.isError)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isFinite (value)](#apidoc.element.lodash.isFinite)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isFunction (value)](#apidoc.element.lodash.isFunction)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isInteger (value)](#apidoc.element.lodash.isInteger)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isLength (value)](#apidoc.element.lodash.isLength)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isMap (value)](#apidoc.element.lodash.isMap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isMatch (object, source)](#apidoc.element.lodash.isMatch)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isMatchWith (object, source, customizer)](#apidoc.element.lodash.isMatchWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isNaN (value)](#apidoc.element.lodash.isNaN)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isNative (value)](#apidoc.element.lodash.isNative)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isNil (value)](#apidoc.element.lodash.isNil)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isNull (value)](#apidoc.element.lodash.isNull)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isNumber (value)](#apidoc.element.lodash.isNumber)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isObject (value)](#apidoc.element.lodash.isObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isObjectLike (value)](#apidoc.element.lodash.isObjectLike)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isPlainObject (value)](#apidoc.element.lodash.isPlainObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isRegExp (value)](#apidoc.element.lodash.isRegExp)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isSafeInteger (value)](#apidoc.element.lodash.isSafeInteger)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isSet (value)](#apidoc.element.lodash.isSet)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isString (value)](#apidoc.element.lodash.isString)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isSymbol (value)](#apidoc.element.lodash.isSymbol)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isTypedArray (value)](#apidoc.element.lodash.isTypedArray)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isUndefined (value)](#apidoc.element.lodash.isUndefined)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isWeakMap (value)](#apidoc.element.lodash.isWeakMap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>isWeakSet (value)](#apidoc.element.lodash.isWeakSet)
1.  [function <span class="apidocSignatureSpan">lodash.</span>iteratee (func)](#apidoc.element.lodash.iteratee)
1.  [function <span class="apidocSignatureSpan">lodash.</span>join (array, separator)](#apidoc.element.lodash.join)
1.  [function <span class="apidocSignatureSpan">lodash.</span>kebabCase (string)](#apidoc.element.lodash.kebabCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>keyBy (collection, iteratee)](#apidoc.element.lodash.keyBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>keys (object)](#apidoc.element.lodash.keys)
1.  [function <span class="apidocSignatureSpan">lodash.</span>keysIn (object)](#apidoc.element.lodash.keysIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>last (array)](#apidoc.element.lodash.last)
1.  [function <span class="apidocSignatureSpan">lodash.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>lowerCase (string)](#apidoc.element.lodash.lowerCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>lowerFirst (string)](#apidoc.element.lodash.lowerFirst)
1.  [function <span class="apidocSignatureSpan">lodash.</span>lt (value, other)](#apidoc.element.lodash.lt)
1.  [function <span class="apidocSignatureSpan">lodash.</span>lte (value, other)](#apidoc.element.lodash.lte)
1.  [function <span class="apidocSignatureSpan">lodash.</span>map (collection, iteratee)](#apidoc.element.lodash.map)
1.  [function <span class="apidocSignatureSpan">lodash.</span>mapKeys (object, iteratee)](#apidoc.element.lodash.mapKeys)
1.  [function <span class="apidocSignatureSpan">lodash.</span>mapValues (object, iteratee)](#apidoc.element.lodash.mapValues)
1.  [function <span class="apidocSignatureSpan">lodash.</span>matches (source)](#apidoc.element.lodash.matches)
1.  [function <span class="apidocSignatureSpan">lodash.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash.matchesProperty)
1.  [function <span class="apidocSignatureSpan">lodash.</span>max (array)](#apidoc.element.lodash.max)
1.  [function <span class="apidocSignatureSpan">lodash.</span>maxBy (array, iteratee)](#apidoc.element.lodash.maxBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>mean (array)](#apidoc.element.lodash.mean)
1.  [function <span class="apidocSignatureSpan">lodash.</span>meanBy (array, iteratee)](#apidoc.element.lodash.meanBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>memoize (func, resolver)](#apidoc.element.lodash.memoize)
1.  [function <span class="apidocSignatureSpan">lodash.</span>memoize.Cache (entries)](#apidoc.element.lodash.memoize.Cache)
1.  [function <span class="apidocSignatureSpan">lodash.</span>merge (object, sources)](#apidoc.element.lodash.merge)
1.  [function <span class="apidocSignatureSpan">lodash.</span>mergeWith (object, sources)](#apidoc.element.lodash.mergeWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>method (path, args)](#apidoc.element.lodash.method)
1.  [function <span class="apidocSignatureSpan">lodash.</span>methodOf (object, args)](#apidoc.element.lodash.methodOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>min (array)](#apidoc.element.lodash.min)
1.  [function <span class="apidocSignatureSpan">lodash.</span>minBy (array, iteratee)](#apidoc.element.lodash.minBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>mixin (object, source, options)](#apidoc.element.lodash.mixin)
1.  [function <span class="apidocSignatureSpan">lodash.</span>multiply (value, other)](#apidoc.element.lodash.multiply)
1.  [function <span class="apidocSignatureSpan">lodash.</span>negate (predicate)](#apidoc.element.lodash.negate)
1.  [function <span class="apidocSignatureSpan">lodash.</span>noConflict ()](#apidoc.element.lodash.noConflict)
1.  [function <span class="apidocSignatureSpan">lodash.</span>noop ()](#apidoc.element.lodash.noop)
1.  [function <span class="apidocSignatureSpan">lodash.</span>now ()](#apidoc.element.lodash.now)
1.  [function <span class="apidocSignatureSpan">lodash.</span>nth (array, n)](#apidoc.element.lodash.nth)
1.  [function <span class="apidocSignatureSpan">lodash.</span>nthArg (n)](#apidoc.element.lodash.nthArg)
1.  [function <span class="apidocSignatureSpan">lodash.</span>omit (object, paths)](#apidoc.element.lodash.omit)
1.  [function <span class="apidocSignatureSpan">lodash.</span>omitBy (object, predicate)](#apidoc.element.lodash.omitBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>once (func)](#apidoc.element.lodash.once)
1.  [function <span class="apidocSignatureSpan">lodash.</span>orderBy (collection, iteratees, orders, guard)](#apidoc.element.lodash.orderBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>over (iteratees)](#apidoc.element.lodash.over)
1.  [function <span class="apidocSignatureSpan">lodash.</span>overArgs (func, transforms)](#apidoc.element.lodash.overArgs)
1.  [function <span class="apidocSignatureSpan">lodash.</span>overEvery (iteratees)](#apidoc.element.lodash.overEvery)
1.  [function <span class="apidocSignatureSpan">lodash.</span>overSome (iteratees)](#apidoc.element.lodash.overSome)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pad (string, length, chars)](#apidoc.element.lodash.pad)
1.  [function <span class="apidocSignatureSpan">lodash.</span>padEnd (string, length, chars)](#apidoc.element.lodash.padEnd)
1.  [function <span class="apidocSignatureSpan">lodash.</span>padStart (string, length, chars)](#apidoc.element.lodash.padStart)
1.  [function <span class="apidocSignatureSpan">lodash.</span>parseInt (string, radix, guard)](#apidoc.element.lodash.parseInt)
1.  [function <span class="apidocSignatureSpan">lodash.</span>partial (func, partials)](#apidoc.element.lodash.partial)
1.  [function <span class="apidocSignatureSpan">lodash.</span>partialRight (func, partials)](#apidoc.element.lodash.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>partition (collection, iteratee)](#apidoc.element.lodash.partition)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pick (object, paths)](#apidoc.element.lodash.pick)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pickBy (object, predicate)](#apidoc.element.lodash.pickBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>property (path)](#apidoc.element.lodash.property)
1.  [function <span class="apidocSignatureSpan">lodash.</span>propertyOf (object)](#apidoc.element.lodash.propertyOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pull (array, values)](#apidoc.element.lodash.pull)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pullAll (array, values)](#apidoc.element.lodash.pullAll)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pullAllBy (array, values, iteratee)](#apidoc.element.lodash.pullAllBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pullAllWith (array, values, comparator)](#apidoc.element.lodash.pullAllWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>pullAt (array, indexes)](#apidoc.element.lodash.pullAt)
1.  [function <span class="apidocSignatureSpan">lodash.</span>random (lower, upper, floating)](#apidoc.element.lodash.random)
1.  [function <span class="apidocSignatureSpan">lodash.</span>range (start, end, step)](#apidoc.element.lodash.range)
1.  [function <span class="apidocSignatureSpan">lodash.</span>rangeRight (start, end, step)](#apidoc.element.lodash.rangeRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>rearg (func, indexes)](#apidoc.element.lodash.rearg)
1.  [function <span class="apidocSignatureSpan">lodash.</span>reduce (collection, iteratee, accumulator)](#apidoc.element.lodash.reduce)
1.  [function <span class="apidocSignatureSpan">lodash.</span>reduceRight (collection, iteratee, accumulator)](#apidoc.element.lodash.reduceRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>reject (collection, predicate)](#apidoc.element.lodash.reject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>remove (array, predicate)](#apidoc.element.lodash.remove)
1.  [function <span class="apidocSignatureSpan">lodash.</span>repeat (string, n, guard)](#apidoc.element.lodash.repeat)
1.  [function <span class="apidocSignatureSpan">lodash.</span>replace ()](#apidoc.element.lodash.replace)
1.  [function <span class="apidocSignatureSpan">lodash.</span>rest (func, start)](#apidoc.element.lodash.rest)
1.  [function <span class="apidocSignatureSpan">lodash.</span>result (object, path, defaultValue)](#apidoc.element.lodash.result)
1.  [function <span class="apidocSignatureSpan">lodash.</span>reverse (array)](#apidoc.element.lodash.reverse)
1.  [function <span class="apidocSignatureSpan">lodash.</span>round (number, precision)](#apidoc.element.lodash.round)
1.  [function <span class="apidocSignatureSpan">lodash.</span>runInContext (context)](#apidoc.element.lodash.runInContext)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sample (collection)](#apidoc.element.lodash.sample)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sampleSize (collection, n, guard)](#apidoc.element.lodash.sampleSize)
1.  [function <span class="apidocSignatureSpan">lodash.</span>set (object, path, value)](#apidoc.element.lodash.set)
1.  [function <span class="apidocSignatureSpan">lodash.</span>setWith (object, path, value, customizer)](#apidoc.element.lodash.setWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>shuffle (collection)](#apidoc.element.lodash.shuffle)
1.  [function <span class="apidocSignatureSpan">lodash.</span>size (collection)](#apidoc.element.lodash.size)
1.  [function <span class="apidocSignatureSpan">lodash.</span>slice (array, start, end)](#apidoc.element.lodash.slice)
1.  [function <span class="apidocSignatureSpan">lodash.</span>snakeCase (string)](#apidoc.element.lodash.snakeCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>some (collection, predicate, guard)](#apidoc.element.lodash.some)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortBy (collection, iteratees)](#apidoc.element.lodash.sortBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedIndex (array, value)](#apidoc.element.lodash.sortedIndex)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedIndexBy (array, value, iteratee)](#apidoc.element.lodash.sortedIndexBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedIndexOf (array, value)](#apidoc.element.lodash.sortedIndexOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndex (array, value)](#apidoc.element.lodash.sortedLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndexBy (array, value, iteratee)](#apidoc.element.lodash.sortedLastIndexBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndexOf (array, value)](#apidoc.element.lodash.sortedLastIndexOf)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedUniq (array)](#apidoc.element.lodash.sortedUniq)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sortedUniqBy (array, iteratee)](#apidoc.element.lodash.sortedUniqBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>split (string, separator, limit)](#apidoc.element.lodash.split)
1.  [function <span class="apidocSignatureSpan">lodash.</span>spread (func, start)](#apidoc.element.lodash.spread)
1.  [function <span class="apidocSignatureSpan">lodash.</span>startCase (string)](#apidoc.element.lodash.startCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>startsWith (string, target, position)](#apidoc.element.lodash.startsWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>stubArray ()](#apidoc.element.lodash.stubArray)
1.  [function <span class="apidocSignatureSpan">lodash.</span>stubFalse ()](#apidoc.element.lodash.stubFalse)
1.  [function <span class="apidocSignatureSpan">lodash.</span>stubObject ()](#apidoc.element.lodash.stubObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>stubString ()](#apidoc.element.lodash.stubString)
1.  [function <span class="apidocSignatureSpan">lodash.</span>stubTrue ()](#apidoc.element.lodash.stubTrue)
1.  [function <span class="apidocSignatureSpan">lodash.</span>subtract (value, other)](#apidoc.element.lodash.subtract)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sum (array)](#apidoc.element.lodash.sum)
1.  [function <span class="apidocSignatureSpan">lodash.</span>sumBy (array, iteratee)](#apidoc.element.lodash.sumBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>tail (array)](#apidoc.element.lodash.tail)
1.  [function <span class="apidocSignatureSpan">lodash.</span>take (array, n, guard)](#apidoc.element.lodash.take)
1.  [function <span class="apidocSignatureSpan">lodash.</span>takeRight (array, n, guard)](#apidoc.element.lodash.takeRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>takeRightWhile (array, predicate)](#apidoc.element.lodash.takeRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash.</span>takeWhile (array, predicate)](#apidoc.element.lodash.takeWhile)
1.  [function <span class="apidocSignatureSpan">lodash.</span>tap (value, interceptor)](#apidoc.element.lodash.tap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>template (string, options, guard)](#apidoc.element.lodash.template)
1.  [function <span class="apidocSignatureSpan">lodash.</span>throttle (func, wait, options)](#apidoc.element.lodash.throttle)
1.  [function <span class="apidocSignatureSpan">lodash.</span>thru (value, interceptor)](#apidoc.element.lodash.thru)
1.  [function <span class="apidocSignatureSpan">lodash.</span>times (n, iteratee)](#apidoc.element.lodash.times)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toArray (value)](#apidoc.element.lodash.toArray)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toFinite (value)](#apidoc.element.lodash.toFinite)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toInteger (value)](#apidoc.element.lodash.toInteger)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toLength (value)](#apidoc.element.lodash.toLength)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toLower (value)](#apidoc.element.lodash.toLower)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toNumber (value)](#apidoc.element.lodash.toNumber)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toPairs (object)](#apidoc.element.lodash.toPairs)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toPairsIn (object)](#apidoc.element.lodash.toPairsIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toPath (value)](#apidoc.element.lodash.toPath)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toPlainObject (value)](#apidoc.element.lodash.toPlainObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toSafeInteger (value)](#apidoc.element.lodash.toSafeInteger)
1.  [function <span class="apidocSignatureSpan">lodash.</span>toUpper (value)](#apidoc.element.lodash.toUpper)
1.  [function <span class="apidocSignatureSpan">lodash.</span>transform (object, iteratee, accumulator)](#apidoc.element.lodash.transform)
1.  [function <span class="apidocSignatureSpan">lodash.</span>trim (string, chars, guard)](#apidoc.element.lodash.trim)
1.  [function <span class="apidocSignatureSpan">lodash.</span>trimEnd (string, chars, guard)](#apidoc.element.lodash.trimEnd)
1.  [function <span class="apidocSignatureSpan">lodash.</span>trimStart (string, chars, guard)](#apidoc.element.lodash.trimStart)
1.  [function <span class="apidocSignatureSpan">lodash.</span>truncate (string, options)](#apidoc.element.lodash.truncate)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unary (func)](#apidoc.element.lodash.unary)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unescape (string)](#apidoc.element.lodash.unescape)
1.  [function <span class="apidocSignatureSpan">lodash.</span>union (arrays)](#apidoc.element.lodash.union)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unionBy (arrays)](#apidoc.element.lodash.unionBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unionWith (arrays)](#apidoc.element.lodash.unionWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>uniq (array)](#apidoc.element.lodash.uniq)
1.  [function <span class="apidocSignatureSpan">lodash.</span>uniqBy (array, iteratee)](#apidoc.element.lodash.uniqBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>uniqWith (array, comparator)](#apidoc.element.lodash.uniqWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>uniqueId (prefix)](#apidoc.element.lodash.uniqueId)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unset (object, path)](#apidoc.element.lodash.unset)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unzip (array)](#apidoc.element.lodash.unzip)
1.  [function <span class="apidocSignatureSpan">lodash.</span>unzipWith (array, iteratee)](#apidoc.element.lodash.unzipWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>update (object, path, updater)](#apidoc.element.lodash.update)
1.  [function <span class="apidocSignatureSpan">lodash.</span>updateWith (object, path, updater, customizer)](#apidoc.element.lodash.updateWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>upperCase (string)](#apidoc.element.lodash.upperCase)
1.  [function <span class="apidocSignatureSpan">lodash.</span>upperFirst (string)](#apidoc.element.lodash.upperFirst)
1.  [function <span class="apidocSignatureSpan">lodash.</span>values (object)](#apidoc.element.lodash.values)
1.  [function <span class="apidocSignatureSpan">lodash.</span>valuesIn (object)](#apidoc.element.lodash.valuesIn)
1.  [function <span class="apidocSignatureSpan">lodash.</span>without (array, values)](#apidoc.element.lodash.without)
1.  [function <span class="apidocSignatureSpan">lodash.</span>words (string, pattern, guard)](#apidoc.element.lodash.words)
1.  [function <span class="apidocSignatureSpan">lodash.</span>wrap (value, wrapper)](#apidoc.element.lodash.wrap)
1.  [function <span class="apidocSignatureSpan">lodash.</span>xor (arrays)](#apidoc.element.lodash.xor)
1.  [function <span class="apidocSignatureSpan">lodash.</span>xorBy (arrays)](#apidoc.element.lodash.xorBy)
1.  [function <span class="apidocSignatureSpan">lodash.</span>xorWith (arrays)](#apidoc.element.lodash.xorWith)
1.  [function <span class="apidocSignatureSpan">lodash.</span>zip (array)](#apidoc.element.lodash.zip)
1.  [function <span class="apidocSignatureSpan">lodash.</span>zipObject (props, values)](#apidoc.element.lodash.zipObject)
1.  [function <span class="apidocSignatureSpan">lodash.</span>zipObjectDeep (props, values)](#apidoc.element.lodash.zipObjectDeep)
1.  [function <span class="apidocSignatureSpan">lodash.</span>zipWith (arrays)](#apidoc.element.lodash.zipWith)
1.  object <span class="apidocSignatureSpan">lodash.</span>memoize.Cache.prototype
1.  object <span class="apidocSignatureSpan">lodash.</span>templateSettings
1.  string <span class="apidocSignatureSpan">lodash.</span>VERSION

#### [module lodash.bind](#apidoc.module.lodash.bind)
1.  [function <span class="apidocSignatureSpan">lodash.</span>bind ()](#apidoc.element.lodash.bind.bind)
1.  function <span class="apidocSignatureSpan">lodash.bind.</span>placeholder

#### [module lodash.bindKey](#apidoc.module.lodash.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash.</span>bindKey (object, key, partials)](#apidoc.element.lodash.bindKey.bindKey)
1.  function <span class="apidocSignatureSpan">lodash.bindKey.</span>placeholder

#### [module lodash.curry](#apidoc.module.lodash.curry)
1.  [function <span class="apidocSignatureSpan">lodash.</span>curry (func, arity, guard)](#apidoc.element.lodash.curry.curry)
1.  function <span class="apidocSignatureSpan">lodash.curry.</span>placeholder

#### [module lodash.curryRight](#apidoc.module.lodash.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>curryRight (func, arity, guard)](#apidoc.element.lodash.curryRight.curryRight)
1.  function <span class="apidocSignatureSpan">lodash.curryRight.</span>placeholder

#### [module lodash.memoize](#apidoc.module.lodash.memoize)
1.  [function <span class="apidocSignatureSpan">lodash.</span>memoize (func, resolver)](#apidoc.element.lodash.memoize.memoize)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.</span>Cache (entries)](#apidoc.element.lodash.memoize.Cache)

#### [module lodash.memoize.Cache](#apidoc.module.lodash.memoize.Cache)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.</span>Cache (entries)](#apidoc.element.lodash.memoize.Cache.Cache)

#### [module lodash.memoize.Cache.prototype](#apidoc.module.lodash.memoize.Cache.prototype)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>clear ()](#apidoc.element.lodash.memoize.Cache.prototype.clear)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>delete (key)](#apidoc.element.lodash.memoize.Cache.prototype.delete)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>get (key)](#apidoc.element.lodash.memoize.Cache.prototype.get)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>has (key)](#apidoc.element.lodash.memoize.Cache.prototype.has)
1.  [function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>set (key, value)](#apidoc.element.lodash.memoize.Cache.prototype.set)

#### [module lodash.partial](#apidoc.module.lodash.partial)
1.  [function <span class="apidocSignatureSpan">lodash.</span>partial (func, partials)](#apidoc.element.lodash.partial.partial)
1.  function <span class="apidocSignatureSpan">lodash.partial.</span>placeholder

#### [module lodash.partialRight](#apidoc.module.lodash.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash.</span>partialRight (func, partials)](#apidoc.element.lodash.partialRight.partialRight)
1.  function <span class="apidocSignatureSpan">lodash.partialRight.</span>placeholder



# <a name="apidoc.module.lodash"></a>[module lodash](#apidoc.module.lodash)

#### <a name="apidoc.element.lodash.add"></a>[function <span class="apidocSignatureSpan">lodash.</span>add (value, other)](#apidoc.element.lodash.add)
- description and source-code
```javascript
add = function (value, other) {
  var result;
  if (value === undefined && other === undefined) {
    return defaultValue;
  }
  if (value !== undefined) {
    result = value;
  }
  if (other !== undefined) {
    if (result === undefined) {
      return other;
    }
    if (typeof value == 'string' || typeof other == 'string') {
      value = baseToString(value);
      other = baseToString(other);
    } else {
      value = baseToNumber(value);
      other = baseToNumber(other);
    }
    result = operator(value, other);
  }
  return result;
}
```
- example usage
```shell
...
 * @private
 * @param {Object} set The set to modify.
 * @param {*} value The value to add.
 * @returns {Object} Returns 'set'.
 */
function addSetEntry(set, value) {
  // Don't return 'set.add' because it's not chainable in IE 11.
  set.add(value);
  return set;
}

/**
 * A faster alternative to 'Function#apply', this function invokes 'func'
 * with the 'this' binding of 'thisArg' and the arguments of 'args'.
 *
...
```

#### <a name="apidoc.element.lodash.after"></a>[function <span class="apidocSignatureSpan">lodash.</span>after (n, func)](#apidoc.element.lodash.after)
- description and source-code
```javascript
function after(n, func) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  n = toInteger(n);
  return function() {
    if (--n < 1) {
      return func.apply(this, arguments);
    }
  };
}
```
- example usage
```shell
...
* @param {number} n The number of calls before 'func' is invoked.
* @param {Function} func The function to restrict.
* @returns {Function} Returns the new restricted function.
* @example
*
* var saves = ['profile', 'settings'];
*
* var done = _.after(saves.length, function() {
*   console.log('done saving!');
* });
*
* _.forEach(saves, function(type) {
*   asyncSave({ 'type': type, 'complete': done });
* });
* // => Logs 'done saving!' after the two async saves have completed.
...
```

#### <a name="apidoc.element.lodash.ary"></a>[function <span class="apidocSignatureSpan">lodash.</span>ary (func, n, guard)](#apidoc.element.lodash.ary)
- description and source-code
```javascript
function ary(func, n, guard) {
  n = guard ? undefined : n;
  n = (func && n == null) ? func.length : n;
  return createWrap(func, WRAP_ARY_FLAG, undefined, undefined, undefined, undefined, n);
}
```
- example usage
```shell
...
 * @category Function
 * @param {Function} func The function to cap arguments for.
 * @param {number} [n=func.length] The arity cap.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {Function} Returns the new capped function.
 * @example
 *
 * _.map(['6', '8', '10'], _.ary(parseInt, 1));
 * // => [6, 8, 10]
 */
function ary(func, n, guard) {
  n = guard ? undefined : n;
  n = (func && n == null) ? func.length : n;
  return createWrap(func, WRAP_ARY_FLAG, undefined, undefined, undefined, undefined, n);
}
...
```

#### <a name="apidoc.element.lodash.assign"></a>[function <span class="apidocSignatureSpan">lodash.</span>assign (object, sources)](#apidoc.element.lodash.assign)
- description and source-code
```javascript
assign = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
...
 *
 * function Foo() {
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.assign({ 'a': 1 }, new Foo);
 * // => { 'a': 1, 'b': 2 }
 *
 * _.assign({ 'a': 1 }, _.toPlainObject(new Foo));
 * // => { 'a': 1, 'b': 2, 'c': 3 }
 */
function toPlainObject(value) {
  return copyObject(value, keysIn(value));
...
```

#### <a name="apidoc.element.lodash.assignIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>assignIn (object, sources)](#apidoc.element.lodash.assignIn)
- description and source-code
```javascript
assignIn = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
...
 * function Bar() {
 *   this.c = 3;
 * }
 *
 * Foo.prototype.b = 2;
 * Bar.prototype.d = 4;
 *
 * _.assignIn({ 'a': 0 }, new Foo, new Bar);
 * // => { 'a': 1, 'b': 2, 'c': 3, 'd': 4 }
 */
var assignIn = createAssigner(function(object, source) {
  copyObject(source, keysIn(source), object);
});

/**
...
```

#### <a name="apidoc.element.lodash.assignInWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>assignInWith (object, sources)](#apidoc.element.lodash.assignInWith)
- description and source-code
```javascript
assignInWith = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.assignWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>assignWith (object, sources)](#apidoc.element.lodash.assignWith)
- description and source-code
```javascript
assignWith = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.at"></a>[function <span class="apidocSignatureSpan">lodash.</span>at (object, paths)](#apidoc.element.lodash.at)
- description and source-code
```javascript
function baseAt(object, paths) {
  var index = -1,
      length = paths.length,
      result = Array(length),
      skip = object == null;

  while (++index < length) {
    result[index] = skip ? undefined : get(object, paths[index]);
  }
  return result;
}
```
- example usage
```shell
...
 * @category Seq
 * @param {...(string|string[])} [paths] The property paths to pick.
 * @returns {Object} Returns the new 'lodash' wrapper instance.
 * @example
 *
 * var object = { 'a': [{ 'b': { 'c': 3 } }, 4] };
 *
 * _(object).at(['a[0].b.c', 'a[1]']).value();
 * // => [3, 4]
 */
var wrapperAt = flatRest(function(paths) {
  var length = paths.length,
      start = length ? paths[0] : 0,
      value = this.__wrapped__,
      interceptor = function(object) { return baseAt(object, paths); };
...
```

#### <a name="apidoc.element.lodash.attempt"></a>[function <span class="apidocSignatureSpan">lodash.</span>attempt (func, args)](#apidoc.element.lodash.attempt)
- description and source-code
```javascript
attempt = function (func, args) {
  try {
    return apply(func, undefined, args);
  } catch (e) {
    return isError(e) ? e : new Error(e);
  }
}
```
- example usage
```shell
...
* @category Util
* @param {Function} func The function to attempt.
* @param {...*} [args] The arguments to invoke 'func' with.
* @returns {*} Returns the 'func' result or error object.
* @example
*
* // Avoid throwing errors for invalid selectors.
* var elements = _.attempt(function(selector) {
*   return document.querySelectorAll(selector);
* }, '>_>');
*
* if (_.isError(elements)) {
*   elements = [];
* }
*/
...
```

#### <a name="apidoc.element.lodash.before"></a>[function <span class="apidocSignatureSpan">lodash.</span>before (n, func)](#apidoc.element.lodash.before)
- description and source-code
```javascript
function before(n, func) {
  var result;
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  n = toInteger(n);
  return function() {
    if (--n > 0) {
      result = func.apply(this, arguments);
    }
    if (n <= 1) {
      func = undefined;
    }
    return result;
  };
}
```
- example usage
```shell
...
 * @since 3.0.0
 * @category Function
 * @param {number} n The number of calls at which 'func' is no longer invoked.
 * @param {Function} func The function to restrict.
 * @returns {Function} Returns the new restricted function.
 * @example
 *
 * jQuery(element).on('click', _.before(5, addContactToList));
 * // => Allows adding up to 4 contacts to the list.
 */
function before(n, func) {
  var result;
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
...
```

#### <a name="apidoc.element.lodash.bind"></a>[function <span class="apidocSignatureSpan">lodash.</span>bind (func, thisArg, partials)](#apidoc.element.lodash.bind)
- description and source-code
```javascript
bind = function (func, thisArg, partials) {
  var bitmask = WRAP_BIND_FLAG;
  if (partials.length) {
    var holders = replaceHolders(partials, getHolder(bind));
    bitmask |= WRAP_PARTIAL_FLAG;
  }
  return createWrap(func, bitmask, thisArg, partials, holders);
}
```
- example usage
```shell
...
*
* function greet(greeting, punctuation) {
*   return greeting + ' ' + this.user + punctuation;
* }
*
* var object = { 'user': 'fred' };
*
* var bound = _.bind(greet, object, 'hi');
* bound('!');
* // => 'hi fred!'
*
* // Bound with placeholders.
* var bound = _.bind(greet, object, _, '!');
* bound('hi');
* // => 'hi fred!'
...
```

#### <a name="apidoc.element.lodash.bindAll"></a>[function <span class="apidocSignatureSpan">lodash.</span>bindAll (object, methodNames)](#apidoc.element.lodash.bindAll)
- description and source-code
```javascript
bindAll = function (object, methodNames) {
  arrayEach(methodNames, function(key) {
    key = toKey(key);
    baseAssignValue(object, key, bind(object[key], object));
  });
  return object;
}
```
- example usage
```shell
...
 * var view = {
 *   'label': 'docs',
 *   'click': function() {
 *     console.log('clicked ' + this.label);
 *   }
 * };
 *
 * _.bindAll(view, ['click']);
 * jQuery(element).on('click', view.click);
 * // => Logs 'clicked docs' when clicked.
 */
var bindAll = flatRest(function(object, methodNames) {
  arrayEach(methodNames, function(key) {
    key = toKey(key);
    baseAssignValue(object, key, bind(object[key], object));
...
```

#### <a name="apidoc.element.lodash.bindKey"></a>[function <span class="apidocSignatureSpan">lodash.</span>bindKey (object, key, partials)](#apidoc.element.lodash.bindKey)
- description and source-code
```javascript
bindKey = function (object, key, partials) {
  var bitmask = WRAP_BIND_FLAG | WRAP_BIND_KEY_FLAG;
  if (partials.length) {
    var holders = replaceHolders(partials, getHolder(bindKey));
    bitmask |= WRAP_PARTIAL_FLAG;
  }
  return createWrap(key, bitmask, object, partials, holders);
}
```
- example usage
```shell
...
* var object = {
*   'user': 'fred',
*   'greet': function(greeting, punctuation) {
*     return greeting + ' ' + this.user + punctuation;
*   }
* };
*
* var bound = _.bindKey(object, 'greet', 'hi');
* bound('!');
* // => 'hi fred!'
*
* object.greet = function(greeting, punctuation) {
*   return greeting + 'ya ' + this.user + punctuation;
* };
*
...
```

#### <a name="apidoc.element.lodash.camelCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>camelCase (string)](#apidoc.element.lodash.camelCase)
- description and source-code
```javascript
camelCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 3.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the camel cased string.
* @example
*
* _.camelCase('Foo Bar');
* // => 'fooBar'
*
* _.camelCase('--foo-bar--');
* // => 'fooBar'
*
* _.camelCase('__FOO_BAR__');
* // => 'fooBar'
...
```

#### <a name="apidoc.element.lodash.capitalize"></a>[function <span class="apidocSignatureSpan">lodash.</span>capitalize (string)](#apidoc.element.lodash.capitalize)
- description and source-code
```javascript
function capitalize(string) {
  return upperFirst(toString(string).toLowerCase());
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category String
 * @param {string} [string=''] The string to capitalize.
 * @returns {string} Returns the capitalized string.
 * @example
 *
 * _.capitalize('FRED');
 * // => 'Fred'
 */
function capitalize(string) {
  return upperFirst(toString(string).toLowerCase());
}

/**
...
```

#### <a name="apidoc.element.lodash.castArray"></a>[function <span class="apidocSignatureSpan">lodash.</span>castArray ()](#apidoc.element.lodash.castArray)
- description and source-code
```javascript
function castArray() {
  if (!arguments.length) {
    return [];
  }
  var value = arguments[0];
  return isArray(value) ? value : [value];
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.4.0
* @category Lang
* @param {*} value The value to inspect.
* @returns {Array} Returns the cast array.
* @example
*
* _.castArray(1);
* // => [1]
*
* _.castArray({ 'a': 1 });
* // => [{ 'a': 1 }]
*
* _.castArray('abc');
* // => ['abc']
...
```

#### <a name="apidoc.element.lodash.ceil"></a>[function <span class="apidocSignatureSpan">lodash.</span>ceil (number, precision)](#apidoc.element.lodash.ceil)
- description and source-code
```javascript
ceil = function (number, precision) {
  number = toNumber(number);
  precision = precision == null ? 0 : nativeMin(toInteger(precision), 292);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
...
* @since 3.10.0
* @category Math
* @param {number} number The number to round up.
* @param {number} [precision=0] The precision to round up to.
* @returns {number} Returns the rounded up number.
* @example
*
* _.ceil(4.006);
* // => 5
*
* _.ceil(6.004, 2);
* // => 6.01
*
* _.ceil(6040, -2);
* // => 6100
...
```

#### <a name="apidoc.element.lodash.chain"></a>[function <span class="apidocSignatureSpan">lodash.</span>chain (value)](#apidoc.element.lodash.chain)
- description and source-code
```javascript
function chain(value) {
  var result = lodash(value);
  result.__chain__ = true;
  return result;
}
```
- example usage
```shell
...
* var users = [
*   { 'user': 'barney',  'age': 36 },
*   { 'user': 'fred',    'age': 40 },
*   { 'user': 'pebbles', 'age': 1 }
* ];
*
* var youngest = _
*   .chain(users)
*   .sortBy('age')
*   .map(function(o) {
*     return o.user + ' is ' + o.age;
*   })
*   .head()
*   .value();
* // => 'pebbles is 1'
...
```

#### <a name="apidoc.element.lodash.chunk"></a>[function <span class="apidocSignatureSpan">lodash.</span>chunk (array, size, guard)](#apidoc.element.lodash.chunk)
- description and source-code
```javascript
function chunk(array, size, guard) {
  if ((guard ? isIterateeCall(array, size, guard) : size === undefined)) {
    size = 1;
  } else {
    size = nativeMax(toInteger(size), 0);
  }
  var length = array == null ? 0 : array.length;
  if (!length || size < 1) {
    return [];
  }
  var index = 0,
      resIndex = 0,
      result = Array(nativeCeil(length / size));

  while (index < length) {
    result[resIndex++] = baseSlice(array, index, (index += size));
  }
  return result;
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to process.
 * @param {number} [size=1] The length of each chunk
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {Array} Returns the new array of chunks.
 * @example
 *
 * _.chunk(['a', 'b', 'c', 'd'], 2);
 * // => [['a', 'b'], ['c', 'd']]
 *
 * _.chunk(['a', 'b', 'c', 'd'], 3);
 * // => [['a', 'b', 'c'], ['d']]
 */
function chunk(array, size, guard) {
  if ((guard ? isIterateeCall(array, size, guard) : size === undefined)) {
...
```

#### <a name="apidoc.element.lodash.clamp"></a>[function <span class="apidocSignatureSpan">lodash.</span>clamp (number, lower, upper)](#apidoc.element.lodash.clamp)
- description and source-code
```javascript
function clamp(number, lower, upper) {
  if (upper === undefined) {
    upper = lower;
    lower = undefined;
  }
  if (upper !== undefined) {
    upper = toNumber(upper);
    upper = upper === upper ? upper : 0;
  }
  if (lower !== undefined) {
    lower = toNumber(lower);
    lower = lower === lower ? lower : 0;
  }
  return baseClamp(toNumber(number), lower, upper);
}
```
- example usage
```shell
...
 * @category Number
 * @param {number} number The number to clamp.
 * @param {number} [lower] The lower bound.
 * @param {number} upper The upper bound.
 * @returns {number} Returns the clamped number.
 * @example
 *
 * _.clamp(-10, -5, 5);
 * // => -5
 *
 * _.clamp(10, -5, 5);
 * // => 5
 */
function clamp(number, lower, upper) {
  if (upper === undefined) {
...
```

#### <a name="apidoc.element.lodash.clone"></a>[function <span class="apidocSignatureSpan">lodash.</span>clone (value)](#apidoc.element.lodash.clone)
- description and source-code
```javascript
function clone(value) {
  return baseClone(value, CLONE_SYMBOLS_FLAG);
}
```
- example usage
```shell
...
 */
function lazyReverse() {
  if (this.__filtered__) {
    var result = new LazyWrapper(this);
    result.__dir__ = -1;
    result.__filtered__ = true;
  } else {
    result = this.clone();
    result.__dir__ *= -1;
  }
  return result;
}

/**
 * Extracts the unwrapped value from its lazy wrapper.
...
```

#### <a name="apidoc.element.lodash.cloneDeep"></a>[function <span class="apidocSignatureSpan">lodash.</span>cloneDeep (value)](#apidoc.element.lodash.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value) {
  return baseClone(value, CLONE_DEEP_FLAG | CLONE_SYMBOLS_FLAG);
}
```
- example usage
```shell
...
 * @param {*} value The value to recursively clone.
 * @returns {*} Returns the deep cloned value.
 * @see _.clone
 * @example
 *
 * var objects = [{ 'a': 1 }, { 'b': 2 }];
 *
 * var deep = _.cloneDeep(objects);
 * console.log(deep[0] === objects[0]);
 * // => false
 */
function cloneDeep(value) {
  return baseClone(value, CLONE_DEEP_FLAG | CLONE_SYMBOLS_FLAG);
}
...
```

#### <a name="apidoc.element.lodash.cloneDeepWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>cloneDeepWith (value, customizer)](#apidoc.element.lodash.cloneDeepWith)
- description and source-code
```javascript
function cloneDeepWith(value, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return baseClone(value, CLONE_DEEP_FLAG | CLONE_SYMBOLS_FLAG, customizer);
}
```
- example usage
```shell
...
*
* function customizer(value) {
*   if (_.isElement(value)) {
*     return value.cloneNode(true);
*   }
* }
*
* var el = _.cloneDeepWith(document.body, customizer);
*
* console.log(el === document.body);
* // => false
* console.log(el.nodeName);
* // => 'BODY'
* console.log(el.childNodes.length);
* // => 20
...
```

#### <a name="apidoc.element.lodash.cloneWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>cloneWith (value, customizer)](#apidoc.element.lodash.cloneWith)
- description and source-code
```javascript
function cloneWith(value, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return baseClone(value, CLONE_SYMBOLS_FLAG, customizer);
}
```
- example usage
```shell
...
*
* function customizer(value) {
*   if (_.isElement(value)) {
*     return value.cloneNode(false);
*   }
* }
*
* var el = _.cloneWith(document.body, customizer);
*
* console.log(el === document.body);
* // => false
* console.log(el.nodeName);
* // => 'BODY'
* console.log(el.childNodes.length);
* // => 0
...
```

#### <a name="apidoc.element.lodash.compact"></a>[function <span class="apidocSignatureSpan">lodash.</span>compact (array)](#apidoc.element.lodash.compact)
- description and source-code
```javascript
function compact(array) {
  var index = -1,
      length = array == null ? 0 : array.length,
      resIndex = 0,
      result = [];

  while (++index < length) {
    var value = array[index];
    if (value) {
      result[resIndex++] = value;
    }
  }
  return result;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {Array} array The array to compact.
 * @returns {Array} Returns the new array of filtered values.
 * @example
 *
 * _.compact([0, 1, false, 2, '', 3]);
 * // => [1, 2, 3]
 */
function compact(array) {
  var index = -1,
      length = array == null ? 0 : array.length,
      resIndex = 0,
      result = [];
...
```

#### <a name="apidoc.element.lodash.concat"></a>[function <span class="apidocSignatureSpan">lodash.</span>concat ()](#apidoc.element.lodash.concat)
- description and source-code
```javascript
function concat() {
  var length = arguments.length;
  if (!length) {
    return [];
  }
  var args = Array(length - 1),
      array = arguments[0],
      index = length;

  while (index--) {
    args[index - 1] = arguments[index];
  }
  return arrayPush(isArray(array) ? copyArray(array) : [array], baseFlatten(args, 1));
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to concatenate.
* @param {...*} [values] The values to concatenate.
* @returns {Array} Returns the new concatenated array.
* @example
*
* var array = [1];
* var other = _.concat(array, 2, [3], [[4]]);
*
* console.log(other);
* // => [1, 2, 3, [4]]
*
* console.log(array);
* // => [1]
*/
...
```

#### <a name="apidoc.element.lodash.cond"></a>[function <span class="apidocSignatureSpan">lodash.</span>cond (pairs)](#apidoc.element.lodash.cond)
- description and source-code
```javascript
function cond(pairs) {
  var length = pairs == null ? 0 : pairs.length,
      toIteratee = getIteratee();

  pairs = !length ? [] : arrayMap(pairs, function(pair) {
    if (typeof pair[1] != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    return [toIteratee(pair[0]), pair[1]];
  });

  return baseRest(function(args) {
    var index = -1;
    while (++index < length) {
      var pair = pairs[index];
      if (apply(pair[0], this, args)) {
        return apply(pair[1], this, args);
      }
    }
  });
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Util
* @param {Array} pairs The predicate-function pairs.
* @returns {Function} Returns the new composite function.
* @example
*
* var func = _.cond([
*   [_.matches({ 'a': 1 }),           _.constant('matches A')],
*   [_.conforms({ 'b': _.isNumber }), _.constant('matches B')],
*   [_.stubTrue,                      _.constant('no match')]
* ]);
*
* func({ 'a': 1, 'b': 2 });
* // => 'matches A'
...
```

#### <a name="apidoc.element.lodash.conforms"></a>[function <span class="apidocSignatureSpan">lodash.</span>conforms (source)](#apidoc.element.lodash.conforms)
- description and source-code
```javascript
function conforms(source) {
  return baseConforms(baseClone(source, CLONE_DEEP_FLAG));
}
```
- example usage
```shell
...
* @category Util
* @param {Array} pairs The predicate-function pairs.
* @returns {Function} Returns the new composite function.
* @example
*
* var func = _.cond([
*   [_.matches({ 'a': 1 }),           _.constant('matches A')],
*   [_.conforms({ 'b': _.isNumber }), _.constant('matches B')],
*   [_.stubTrue,                      _.constant('no match')]
* ]);
*
* func({ 'a': 1, 'b': 2 });
* // => 'matches A'
*
* func({ 'a': 0, 'b': 1 });
...
```

#### <a name="apidoc.element.lodash.conformsTo"></a>[function <span class="apidocSignatureSpan">lodash.</span>conformsTo (object, source)](#apidoc.element.lodash.conformsTo)
- description and source-code
```javascript
function conformsTo(object, source) {
  return source == null || baseConformsTo(object, source, keys(source));
}
```
- example usage
```shell
...
 * @param {Object} object The object to inspect.
 * @param {Object} source The object of property predicates to conform to.
 * @returns {boolean} Returns 'true' if 'object' conforms, else 'false'.
 * @example
 *
 * var object = { 'a': 1, 'b': 2 };
 *
 * _.conformsTo(object, { 'b': function(n) { return n > 1; } });
 * // => true
 *
 * _.conformsTo(object, { 'b': function(n) { return n > 2; } });
 * // => false
 */
function conformsTo(object, source) {
  return source == null || baseConformsTo(object, source, keys(source));
...
```

#### <a name="apidoc.element.lodash.constant"></a>[function <span class="apidocSignatureSpan">lodash.</span>constant (value)](#apidoc.element.lodash.constant)
- description and source-code
```javascript
function constant(value) {
  return function() {
    return value;
  };
}
```
- example usage
```shell
...
* @memberOf _
* @since 1.1.0
* @category Util
* @param {Object} [context=root] The context object.
* @returns {Function} Returns a new 'lodash' function.
* @example
*
* _.mixin({ 'foo': _.constant('foo') });
*
* var lodash = _.runInContext();
* lodash.mixin({ 'bar': lodash.constant('bar') });
*
* _.isFunction(_.foo);
* // => true
* _.isFunction(_.bar);
...
```

#### <a name="apidoc.element.lodash.countBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>countBy (collection, iteratee)](#apidoc.element.lodash.countBy)
- description and source-code
```javascript
countBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee, 2), accumulator);
}
```
- example usage
```shell
...
 * @since 0.5.0
 * @category Collection
 * @param {Array|Object} collection The collection to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee to transform keys.
 * @returns {Object} Returns the composed aggregate object.
 * @example
 *
 * _.countBy([6.1, 4.2, 6.3], Math.floor);
 * // => { '4': 1, '6': 2 }
 *
 * // The '_.property' iteratee shorthand.
 * _.countBy(['one', 'two', 'three'], 'length');
 * // => { '3': 2, '5': 1 }
 */
var countBy = createAggregator(function(result, value, key) {
...
```

#### <a name="apidoc.element.lodash.create"></a>[function <span class="apidocSignatureSpan">lodash.</span>create (prototype, properties)](#apidoc.element.lodash.create)
- description and source-code
```javascript
function create(prototype, properties) {
  var result = baseCreate(prototype);
  return properties == null ? result : baseAssign(result, properties);
}
```
- example usage
```shell
...
 *
 * _.isPlainObject([1, 2, 3]);
 * // => false
 *
 * _.isPlainObject({ 'x': 0, 'y': 0 });
 * // => true
 *
 * _.isPlainObject(Object.create(null));
 * // => true
 */
function isPlainObject(value) {
  if (!isObjectLike(value) || baseGetTag(value) != objectTag) {
    return false;
  }
  var proto = getPrototype(value);
...
```

#### <a name="apidoc.element.lodash.curry"></a>[function <span class="apidocSignatureSpan">lodash.</span>curry (func, arity, guard)](#apidoc.element.lodash.curry)
- description and source-code
```javascript
function curry(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrap(func, WRAP_CURRY_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curry.placeholder;
  return result;
}
```
- example usage
```shell
...
* @returns {Function} Returns the new curried function.
* @example
*
* var abc = function(a, b, c) {
*   return [a, b, c];
* };
*
* var curried = _.curry(abc);
*
* curried(1)(2)(3);
* // => [1, 2, 3]
*
* curried(1, 2)(3);
* // => [1, 2, 3]
*
...
```

#### <a name="apidoc.element.lodash.curryRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>curryRight (func, arity, guard)](#apidoc.element.lodash.curryRight)
- description and source-code
```javascript
function curryRight(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrap(func, WRAP_CURRY_RIGHT_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryRight.placeholder;
  return result;
}
```
- example usage
```shell
...
* @returns {Function} Returns the new curried function.
* @example
*
* var abc = function(a, b, c) {
*   return [a, b, c];
* };
*
* var curried = _.curryRight(abc);
*
* curried(3)(2)(1);
* // => [1, 2, 3]
*
* curried(2, 3)(1);
* // => [1, 2, 3]
*
...
```

#### <a name="apidoc.element.lodash.debounce"></a>[function <span class="apidocSignatureSpan">lodash.</span>debounce (func, wait, options)](#apidoc.element.lodash.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var lastArgs,
      lastThis,
      maxWait,
      result,
      timerId,
      lastCallTime,
      lastInvokeTime = 0,
      leading = false,
      maxing = false,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  wait = toNumber(wait) || 0;
  if (isObject(options)) {
    leading = !!options.leading;
    maxing = 'maxWait' in options;
    maxWait = maxing ? nativeMax(toNumber(options.maxWait) || 0, wait) : maxWait;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }

  function invokeFunc(time) {
    var args = lastArgs,
        thisArg = lastThis;

    lastArgs = lastThis = undefined;
    lastInvokeTime = time;
    result = func.apply(thisArg, args);
    return result;
  }

  function leadingEdge(time) {
    // Reset any 'maxWait' timer.
    lastInvokeTime = time;
    // Start the timer for the trailing edge.
    timerId = setTimeout(timerExpired, wait);
    // Invoke the leading edge.
    return leading ? invokeFunc(time) : result;
  }

  function remainingWait(time) {
    var timeSinceLastCall = time - lastCallTime,
        timeSinceLastInvoke = time - lastInvokeTime,
        result = wait - timeSinceLastCall;

    return maxing ? nativeMin(result, maxWait - timeSinceLastInvoke) : result;
  }

  function shouldInvoke(time) {
    var timeSinceLastCall = time - lastCallTime,
        timeSinceLastInvoke = time - lastInvokeTime;

    // Either this is the first call, activity has stopped and we're at the
    // trailing edge, the system time has gone backwards and we're treating
    // it as the trailing edge, or we've hit the 'maxWait' limit.
    return (lastCallTime === undefined || (timeSinceLastCall >= wait) ||
      (timeSinceLastCall < 0) || (maxing && timeSinceLastInvoke >= maxWait));
  }

  function timerExpired() {
    var time = now();
    if (shouldInvoke(time)) {
      return trailingEdge(time);
    }
    // Restart the timer.
    timerId = setTimeout(timerExpired, remainingWait(time));
  }

  function trailingEdge(time) {
    timerId = undefined;

    // Only invoke if we have 'lastArgs' which means 'func' has been
    // debounced at least once.
    if (trailing && lastArgs) {
      return invokeFunc(time);
    }
    lastArgs = lastThis = undefined;
    return result;
  }

  function cancel() {
    if (timerId !== undefined) {
      clearTimeout(timerId);
    }
    lastInvokeTime = 0;
    lastArgs = lastCallTime = lastThis = timerId = undefined;
  }

  function flush() {
    return timerId === undefined ? result : trailingEdge(now());
  }

  function debounced() {
    var time = now(),
        isInvoking = shouldInvoke(time);

    lastArgs = arguments;
    lastThis = this;
    lastCallTime = time;

    if (isInvoking) {
      if (timerId === undefined) {
        return leadingEdge(lastCallTime);
      }
      if (maxing) {
        // Handle invocations in a tight loop.
        timerId = setTimeout(timerExpired, wait);
        return invokeFunc(lastCallTime);
      }
    }
    if (timerId === undefined) {
      timerId = setTimeout(timerExpired, wait);
    }
    return result;
  }
  debounced.cancel = cancel;
  debounced.flush = flush;
  return debounced;
}
```
- example usage
```shell
...
*  The maximum time 'func' is allowed to be delayed before it's invoked.
* @param {boolean} [options.trailing=true]
*  Specify invoking on the trailing edge of the timeout.
* @returns {Function} Returns the new debounced function.
* @example
*
* // Avoid costly calculations while the window size is in flux.
* jQuery(window).on('resize', _.debounce(calculateLayout, 150));
*
* // Invoke 'sendMail' when clicked, debouncing subsequent calls.
* jQuery(element).on('click', _.debounce(sendMail, 300, {
*   'leading': true,
*   'trailing': false
* }));
*
...
```

#### <a name="apidoc.element.lodash.deburr"></a>[function <span class="apidocSignatureSpan">lodash.</span>deburr (string)](#apidoc.element.lodash.deburr)
- description and source-code
```javascript
function deburr(string) {
  string = toString(string);
  return string && string.replace(reLatin, deburrLetter).replace(reComboMark, '');
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category String
 * @param {string} [string=''] The string to deburr.
 * @returns {string} Returns the deburred string.
 * @example
 *
 * _.deburr('déjà vu');
 * // => 'deja vu'
 */
function deburr(string) {
  string = toString(string);
  return string && string.replace(reLatin, deburrLetter).replace(reComboMark, '');
}
...
```

#### <a name="apidoc.element.lodash.defaultTo"></a>[function <span class="apidocSignatureSpan">lodash.</span>defaultTo (value, defaultValue)](#apidoc.element.lodash.defaultTo)
- description and source-code
```javascript
function defaultTo(value, defaultValue) {
  return (value == null || value !== value) ? defaultValue : value;
}
```
- example usage
```shell
...
 * @since 4.14.0
 * @category Util
 * @param {*} value The value to check.
 * @param {*} defaultValue The default value.
 * @returns {*} Returns the resolved value.
 * @example
 *
 * _.defaultTo(1, 10);
 * // => 1
 *
 * _.defaultTo(undefined, 10);
 * // => 10
 */
function defaultTo(value, defaultValue) {
  return (value == null || value !== value) ? defaultValue : value;
...
```

#### <a name="apidoc.element.lodash.defaults"></a>[function <span class="apidocSignatureSpan">lodash.</span>defaults (args)](#apidoc.element.lodash.defaults)
- description and source-code
```javascript
defaults = function (args) {
  args.push(undefined, customDefaultsAssignIn);
  return apply(assignInWith, undefined, args);
}
```
- example usage
```shell
...
   * lodash.isFunction(lodash.bar);
   * // => true
   *
   * // Create a suped-up 'defer' in Node.js.
   * var defer = _.runInContext({ 'setTimeout': setImmediate }).defer;
   */
  var runInContext = (function runInContext(context) {
context = context == null ? root : _.defaults(root.Object(), context, _.pick(root, contextProps));

/** Built-in constructor references. */
var Array = context.Array,
    Date = context.Date,
    Error = context.Error,
    Function = context.Function,
    Math = context.Math,
...
```

#### <a name="apidoc.element.lodash.defaultsDeep"></a>[function <span class="apidocSignatureSpan">lodash.</span>defaultsDeep (args)](#apidoc.element.lodash.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function (args) {
  args.push(undefined, customDefaultsMerge);
  return apply(mergeWith, undefined, args);
}
```
- example usage
```shell
...
 * @category Object
 * @param {Object} object The destination object.
 * @param {...Object} [sources] The source objects.
 * @returns {Object} Returns 'object'.
 * @see _.defaults
 * @example
 *
 * _.defaultsDeep({ 'a': { 'b': 2 } }, { 'a': { 'b': 1, 'c': 3 } });
 * // => { 'a': { 'b': 2, 'c': 3 } }
 */
var defaultsDeep = baseRest(function(args) {
  args.push(undefined, customDefaultsMerge);
  return apply(mergeWith, undefined, args);
});
...
```

#### <a name="apidoc.element.lodash.defer"></a>[function <span class="apidocSignatureSpan">lodash.</span>defer (func, args)](#apidoc.element.lodash.defer)
- description and source-code
```javascript
defer = function (func, args) {
  return baseDelay(func, 1, args);
}
```
- example usage
```shell
...
 * @static
 * @memberOf _
 * @since 2.4.0
 * @category Date
 * @returns {number} Returns the timestamp.
 * @example
 *
 * _.defer(function(stamp) {
 *   console.log(_.now() - stamp);
 * }, _.now());
 * // => Logs the number of milliseconds it took for the deferred invocation.
 */
var now = ctxNow || function() {
  return root.Date.now();
};
...
```

#### <a name="apidoc.element.lodash.delay"></a>[function <span class="apidocSignatureSpan">lodash.</span>delay (func, wait, args)](#apidoc.element.lodash.delay)
- description and source-code
```javascript
delay = function (func, wait, args) {
  return baseDelay(func, toNumber(wait) || 0, args);
}
```
- example usage
```shell
...
 * @category Function
 * @param {Function} func The function to delay.
 * @param {number} wait The number of milliseconds to delay invocation.
 * @param {...*} [args] The arguments to invoke 'func' with.
 * @returns {number} Returns the timer id.
 * @example
 *
 * _.delay(function(text) {
 *   console.log(text);
 * }, 1000, 'later');
 * // => Logs 'later' after one second.
 */
var delay = baseRest(function(func, wait, args) {
  return baseDelay(func, toNumber(wait) || 0, args);
});
...
```

#### <a name="apidoc.element.lodash.difference"></a>[function <span class="apidocSignatureSpan">lodash.</span>difference (array, values)](#apidoc.element.lodash.difference)
- description and source-code
```javascript
difference = function (array, values) {
  return isArrayLikeObject(array)
    ? baseDifference(array, baseFlatten(values, 1, isArrayLikeObject, true))
    : [];
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {...Array} [values] The values to exclude.
 * @returns {Array} Returns the new array of filtered values.
 * @see _.without, _.xor
 * @example
 *
 * _.difference([2, 1], [2, 3]);
 * // => [1]
 */
var difference = baseRest(function(array, values) {
  return isArrayLikeObject(array)
    ? baseDifference(array, baseFlatten(values, 1, isArrayLikeObject, true))
    : [];
});
...
```

#### <a name="apidoc.element.lodash.differenceBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>differenceBy (array, values)](#apidoc.element.lodash.differenceBy)
- description and source-code
```javascript
differenceBy = function (array, values) {
  var iteratee = last(values);
  if (isArrayLikeObject(iteratee)) {
    iteratee = undefined;
  }
  return isArrayLikeObject(array)
    ? baseDifference(array, baseFlatten(values, 1, isArrayLikeObject, true), getIteratee(iteratee, 2))
    : [];
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {...Array} [values] The values to exclude.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns the new array of filtered values.
 * @example
 *
 * _.differenceBy([2.1, 1.2], [2.3, 3.4], Math.floor);
 * // => [1.2]
 *
 * // The '_.property' iteratee shorthand.
 * _.differenceBy([{ 'x': 2 }, { 'x': 1 }], [{ 'x': 1 }], 'x');
 * // => [{ 'x': 2 }]
 */
var differenceBy = baseRest(function(array, values) {
...
```

#### <a name="apidoc.element.lodash.differenceWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>differenceWith (array, values)](#apidoc.element.lodash.differenceWith)
- description and source-code
```javascript
differenceWith = function (array, values) {
  var comparator = last(values);
  if (isArrayLikeObject(comparator)) {
    comparator = undefined;
  }
  return isArrayLikeObject(array)
    ? baseDifference(array, baseFlatten(values, 1, isArrayLikeObject, true), undefined, comparator)
    : [];
}
```
- example usage
```shell
...
 * @param {...Array} [values] The values to exclude.
 * @param {Function} [comparator] The comparator invoked per element.
 * @returns {Array} Returns the new array of filtered values.
 * @example
 *
 * var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
 *
 * _.differenceWith(objects, [{ 'x': 1, 'y': 2 }], _.isEqual);
 * // => [{ 'x': 2, 'y': 1 }]
 */
var differenceWith = baseRest(function(array, values) {
  var comparator = last(values);
  if (isArrayLikeObject(comparator)) {
    comparator = undefined;
  }
...
```

#### <a name="apidoc.element.lodash.divide"></a>[function <span class="apidocSignatureSpan">lodash.</span>divide (value, other)](#apidoc.element.lodash.divide)
- description and source-code
```javascript
divide = function (value, other) {
  var result;
  if (value === undefined && other === undefined) {
    return defaultValue;
  }
  if (value !== undefined) {
    result = value;
  }
  if (other !== undefined) {
    if (result === undefined) {
      return other;
    }
    if (typeof value == 'string' || typeof other == 'string') {
      value = baseToString(value);
      other = baseToString(other);
    } else {
      value = baseToNumber(value);
      other = baseToNumber(other);
    }
    result = operator(value, other);
  }
  return result;
}
```
- example usage
```shell
...
 * @since 4.7.0
 * @category Math
 * @param {number} dividend The first number in a division.
 * @param {number} divisor The second number in a division.
 * @returns {number} Returns the quotient.
 * @example
 *
 * _.divide(6, 4);
 * // => 1.5
 */
var divide = createMathOperation(function(dividend, divisor) {
  return dividend / divisor;
}, 1);

/**
...
```

#### <a name="apidoc.element.lodash.drop"></a>[function <span class="apidocSignatureSpan">lodash.</span>drop (array, n, guard)](#apidoc.element.lodash.drop)
- description and source-code
```javascript
function drop(array, n, guard) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  return baseSlice(array, n < 0 ? 0 : n, length);
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to query.
* @param {number} [n=1] The number of elements to drop.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {Array} Returns the slice of 'array'.
* @example
*
* _.drop([1, 2, 3]);
* // => [2, 3]
*
* _.drop([1, 2, 3], 2);
* // => [3]
*
* _.drop([1, 2, 3], 5);
* // => []
...
```

#### <a name="apidoc.element.lodash.dropRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>dropRight (array, n, guard)](#apidoc.element.lodash.dropRight)
- description and source-code
```javascript
function dropRight(array, n, guard) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  n = length - n;
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to query.
* @param {number} [n=1] The number of elements to drop.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {Array} Returns the slice of 'array'.
* @example
*
* _.dropRight([1, 2, 3]);
* // => [1, 2]
*
* _.dropRight([1, 2, 3], 2);
* // => [1]
*
* _.dropRight([1, 2, 3], 5);
* // => []
...
```

#### <a name="apidoc.element.lodash.dropRightWhile"></a>[function <span class="apidocSignatureSpan">lodash.</span>dropRightWhile (array, predicate)](#apidoc.element.lodash.dropRightWhile)
- description and source-code
```javascript
function dropRightWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), true, true)
    : [];
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': true },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': false }
* ];
*
* _.dropRightWhile(users, function(o) { return !o.active; });
* // => objects for ['barney']
*
* // The '_.matches' iteratee shorthand.
* _.dropRightWhile(users, { 'user': 'pebbles', 'active': false });
* // => objects for ['barney', 'fred']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.dropWhile"></a>[function <span class="apidocSignatureSpan">lodash.</span>dropWhile (array, predicate)](#apidoc.element.lodash.dropWhile)
- description and source-code
```javascript
function dropWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), true)
    : [];
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': false },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': true }
* ];
*
* _.dropWhile(users, function(o) { return !o.active; });
* // => objects for ['pebbles']
*
* // The '_.matches' iteratee shorthand.
* _.dropWhile(users, { 'user': 'barney', 'active': false });
* // => objects for ['fred', 'pebbles']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.each"></a>[function <span class="apidocSignatureSpan">lodash.</span>each (collection, iteratee)](#apidoc.element.lodash.each)
- description and source-code
```javascript
function forEach(collection, iteratee) {
  var func = isArray(collection) ? arrayEach : baseEach;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
*
* // Use backslashes to treat delimiters as plain text.
* var compiled = _.template('<%= "\\<%- value %\\>" %>');
* compiled({ 'value': 'ignored' });
* // => '<%- value %>'
*
* // Use the 'imports' option to import 'jQuery' as 'jq'.
* var text = '<% jq.each(users, function(user) { %><li><%- user %></li><% }); %>';
* var compiled = _.template(text, { 'imports': { 'jq': jQuery } });
* compiled({ 'users': ['fred', 'barney'] });
* // => '<li>fred</li><li>barney</li>'
*
* // Use the 'sourceURL' option to specify a custom sourceURL for the template.
* var compiled = _.template('hello <%= user %>!', { 'sourceURL': '/basic/greeting.jst' });
* compiled(data);
...
```

#### <a name="apidoc.element.lodash.eachRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>eachRight (collection, iteratee)](#apidoc.element.lodash.eachRight)
- description and source-code
```javascript
function forEachRight(collection, iteratee) {
  var func = isArray(collection) ? arrayEachRight : baseEachRight;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.endsWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>endsWith (string, target, position)](#apidoc.element.lodash.endsWith)
- description and source-code
```javascript
function endsWith(string, target, position) {
  string = toString(string);
  target = baseToString(target);

  var length = string.length;
  position = position === undefined
    ? length
    : baseClamp(toInteger(position), 0, length);

  var end = position;
  position -= target.length;
  return position >= 0 && string.slice(position, end) == target;
}
```
- example usage
```shell
...
* @param {string} [string=''] The string to inspect.
* @param {string} [target] The string to search for.
* @param {number} [position=string.length] The position to search up to.
* @returns {boolean} Returns 'true' if 'string' ends with 'target',
*  else 'false'.
* @example
*
* _.endsWith('abc', 'c');
* // => true
*
* _.endsWith('abc', 'b');
* // => false
*
* _.endsWith('abc', 'b', 2);
* // => true
...
```

#### <a name="apidoc.element.lodash.entries"></a>[function <span class="apidocSignatureSpan">lodash.</span>entries (object)](#apidoc.element.lodash.entries)
- description and source-code
```javascript
entries = function (object) {
  var tag = getTag(object);
  if (tag == mapTag) {
    return mapToArray(object);
  }
  if (tag == setTag) {
    return setToPairs(object);
  }
  return baseToPairs(object, keysFunc(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.entriesIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>entriesIn (object)](#apidoc.element.lodash.entriesIn)
- description and source-code
```javascript
entriesIn = function (object) {
  var tag = getTag(object);
  if (tag == mapTag) {
    return mapToArray(object);
  }
  if (tag == setTag) {
    return setToPairs(object);
  }
  return baseToPairs(object, keysFunc(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.eq"></a>[function <span class="apidocSignatureSpan">lodash.</span>eq (value, other)](#apidoc.element.lodash.eq)
- description and source-code
```javascript
function eq(value, other) {
  return value === other || (value !== value && other !== other);
}
```
- example usage
```shell
...
* @param {*} other The other value to compare.
* @returns {boolean} Returns 'true' if the values are equivalent, else 'false'.
* @example
*
* var object = { 'a': 1 };
* var other = { 'a': 1 };
*
* _.eq(object, object);
* // => true
*
* _.eq(object, other);
* // => false
*
* _.eq('a', 'a');
* // => true
...
```

#### <a name="apidoc.element.lodash.escape"></a>[function <span class="apidocSignatureSpan">lodash.</span>escape (string)](#apidoc.element.lodash.escape)
- description and source-code
```javascript
function escape(string) {
  string = toString(string);
  return (string && reHasUnescapedHtml.test(string))
    ? string.replace(reUnescapedHtml, escapeHtmlChar)
    : string;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category String
 * @param {string} [string=''] The string to escape.
 * @returns {string} Returns the escaped string.
 * @example
 *
 * _.escape('fred, barney, & pebbles');
 * // => 'fred, barney, &amp; pebbles'
 */
function escape(string) {
  string = toString(string);
  return (string && reHasUnescapedHtml.test(string))
    ? string.replace(reUnescapedHtml, escapeHtmlChar)
    : string;
...
```

#### <a name="apidoc.element.lodash.escapeRegExp"></a>[function <span class="apidocSignatureSpan">lodash.</span>escapeRegExp (string)](#apidoc.element.lodash.escapeRegExp)
- description and source-code
```javascript
function escapeRegExp(string) {
  string = toString(string);
  return (string && reHasRegExpChar.test(string))
    ? string.replace(reRegExpChar, '\\$&')
    : string;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category String
 * @param {string} [string=''] The string to escape.
 * @returns {string} Returns the escaped string.
 * @example
 *
 * _.escapeRegExp('[lodash](https://lodash.com/)');
 * // => '\[lodash\]\(https://lodash\.com/\)'
 */
function escapeRegExp(string) {
  string = toString(string);
  return (string && reHasRegExpChar.test(string))
    ? string.replace(reRegExpChar, '\\$&')
    : string;
...
```

#### <a name="apidoc.element.lodash.every"></a>[function <span class="apidocSignatureSpan">lodash.</span>every (collection, predicate, guard)](#apidoc.element.lodash.every)
- description and source-code
```javascript
function every(collection, predicate, guard) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (guard && isIterateeCall(collection, predicate, guard)) {
    predicate = undefined;
  }
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
...
* @param {Array|Object} collection The collection to iterate over.
* @param {Function} [predicate=_.identity] The function invoked per iteration.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {boolean} Returns 'true' if all elements pass the predicate check,
*  else 'false'.
* @example
*
* _.every([true, 1, null, 'yes'], Boolean);
* // => false
*
* var users = [
*   { 'user': 'barney', 'age': 36, 'active': false },
*   { 'user': 'fred',   'age': 40, 'active': false }
* ];
*
...
```

#### <a name="apidoc.element.lodash.extend"></a>[function <span class="apidocSignatureSpan">lodash.</span>extend (object, sources)](#apidoc.element.lodash.extend)
- description and source-code
```javascript
extend = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.extendWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>extendWith (object, sources)](#apidoc.element.lodash.extendWith)
- description and source-code
```javascript
extendWith = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.fill"></a>[function <span class="apidocSignatureSpan">lodash.</span>fill (array, value, start, end)](#apidoc.element.lodash.fill)
- description and source-code
```javascript
function fill(array, value, start, end) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  if (start && typeof start != 'number' && isIterateeCall(array, value, start)) {
    start = 0;
    end = length;
  }
  return baseFill(array, value, start, end);
}
```
- example usage
```shell
...
* @param {number} [start=0] The start position.
* @param {number} [end=array.length] The end position.
* @returns {Array} Returns 'array'.
* @example
*
* var array = [1, 2, 3];
*
* _.fill(array, 'a');
* console.log(array);
* // => ['a', 'a', 'a']
*
* _.fill(Array(3), 2);
* // => [2, 2, 2]
*
* _.fill([4, 6, 8, 10], '*', 1, 3);
...
```

#### <a name="apidoc.element.lodash.filter"></a>[function <span class="apidocSignatureSpan">lodash.</span>filter (collection, predicate)](#apidoc.element.lodash.filter)
- description and source-code
```javascript
function filter(collection, predicate) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
...
* @example
*
* var users = [
*   { 'user': 'barney', 'age': 36, 'active': true },
*   { 'user': 'fred',   'age': 40, 'active': false }
* ];
*
* _.filter(users, function(o) { return !o.active; });
* // => objects for ['fred']
*
* // The '_.matches' iteratee shorthand.
* _.filter(users, { 'age': 36, 'active': true });
* // => objects for ['barney']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.find"></a>[function <span class="apidocSignatureSpan">lodash.</span>find (collection, predicate, fromIndex)](#apidoc.element.lodash.find)
- description and source-code
```javascript
find = function (collection, predicate, fromIndex) {
  var iterable = Object(collection);
  if (!isArrayLike(collection)) {
    var iteratee = getIteratee(predicate, 3);
    collection = keys(collection);
    predicate = function(key) { return iteratee(iterable[key], key, iterable); };
  }
  var index = findIndexFunc(collection, predicate, fromIndex);
  return index > -1 ? iterable[iteratee ? collection[index] : index] : undefined;
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'age': 36, 'active': true },
*   { 'user': 'fred',    'age': 40, 'active': false },
*   { 'user': 'pebbles', 'age': 1,  'active': true }
* ];
*
* _.find(users, function(o) { return o.age < 40; });
* // => object for 'barney'
*
* // The '_.matches' iteratee shorthand.
* _.find(users, { 'age': 1, 'active': true });
* // => object for 'pebbles'
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.findIndex"></a>[function <span class="apidocSignatureSpan">lodash.</span>findIndex (array, predicate, fromIndex)](#apidoc.element.lodash.findIndex)
- description and source-code
```javascript
function findIndex(array, predicate, fromIndex) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return -1;
  }
  var index = fromIndex == null ? 0 : toInteger(fromIndex);
  if (index < 0) {
    index = nativeMax(length + index, 0);
  }
  return baseFindIndex(array, getIteratee(predicate, 3), index);
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': false },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': true }
* ];
*
* _.findIndex(users, function(o) { return o.user == 'barney'; });
* // => 0
*
* // The '_.matches' iteratee shorthand.
* _.findIndex(users, { 'user': 'fred', 'active': false });
* // => 1
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.findKey"></a>[function <span class="apidocSignatureSpan">lodash.</span>findKey (object, predicate)](#apidoc.element.lodash.findKey)
- description and source-code
```javascript
function findKey(object, predicate) {
  return baseFindKey(object, getIteratee(predicate, 3), baseForOwn);
}
```
- example usage
```shell
...
*
* var users = {
*   'barney':  { 'age': 36, 'active': true },
*   'fred':    { 'age': 40, 'active': false },
*   'pebbles': { 'age': 1,  'active': true }
* };
*
* _.findKey(users, function(o) { return o.age < 40; });
* // => 'barney' (iteration order is not guaranteed)
*
* // The '_.matches' iteratee shorthand.
* _.findKey(users, { 'age': 1, 'active': true });
* // => 'pebbles'
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.findLast"></a>[function <span class="apidocSignatureSpan">lodash.</span>findLast (collection, predicate, fromIndex)](#apidoc.element.lodash.findLast)
- description and source-code
```javascript
findLast = function (collection, predicate, fromIndex) {
  var iterable = Object(collection);
  if (!isArrayLike(collection)) {
    var iteratee = getIteratee(predicate, 3);
    collection = keys(collection);
    predicate = function(key) { return iteratee(iterable[key], key, iterable); };
  }
  var index = findIndexFunc(collection, predicate, fromIndex);
  return index > -1 ? iterable[iteratee ? collection[index] : index] : undefined;
}
```
- example usage
```shell
...
 * @category Collection
 * @param {Array|Object} collection The collection to inspect.
 * @param {Function} [predicate=_.identity] The function invoked per iteration.
 * @param {number} [fromIndex=collection.length-1] The index to search from.
 * @returns {*} Returns the matched element, else 'undefined'.
 * @example
 *
 * _.findLast([1, 2, 3, 4], function(n) {
 *   return n % 2 == 1;
 * });
 * // => 3
 */
var findLast = createFind(findLastIndex);

/**
...
```

#### <a name="apidoc.element.lodash.findLastIndex"></a>[function <span class="apidocSignatureSpan">lodash.</span>findLastIndex (array, predicate, fromIndex)](#apidoc.element.lodash.findLastIndex)
- description and source-code
```javascript
function findLastIndex(array, predicate, fromIndex) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return -1;
  }
  var index = length - 1;
  if (fromIndex !== undefined) {
    index = toInteger(fromIndex);
    index = fromIndex < 0
      ? nativeMax(length + index, 0)
      : nativeMin(index, length - 1);
  }
  return baseFindIndex(array, getIteratee(predicate, 3), index, true);
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': true },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': false }
* ];
*
* _.findLastIndex(users, function(o) { return o.user == 'pebbles'; });
* // => 2
*
* // The '_.matches' iteratee shorthand.
* _.findLastIndex(users, { 'user': 'barney', 'active': true });
* // => 0
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.findLastKey"></a>[function <span class="apidocSignatureSpan">lodash.</span>findLastKey (object, predicate)](#apidoc.element.lodash.findLastKey)
- description and source-code
```javascript
function findLastKey(object, predicate) {
  return baseFindKey(object, getIteratee(predicate, 3), baseForOwnRight);
}
```
- example usage
```shell
...
*
* var users = {
*   'barney':  { 'age': 36, 'active': true },
*   'fred':    { 'age': 40, 'active': false },
*   'pebbles': { 'age': 1,  'active': true }
* };
*
* _.findLastKey(users, function(o) { return o.age < 40; });
* // => returns 'pebbles' assuming '_.findKey' returns 'barney'
*
* // The '_.matches' iteratee shorthand.
* _.findLastKey(users, { 'age': 36, 'active': true });
* // => 'barney'
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.first"></a>[function <span class="apidocSignatureSpan">lodash.</span>first (array)](#apidoc.element.lodash.first)
- description and source-code
```javascript
function head(array) {
  return (array && array.length) ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.flatMap"></a>[function <span class="apidocSignatureSpan">lodash.</span>flatMap (collection, iteratee)](#apidoc.element.lodash.flatMap)
- description and source-code
```javascript
function flatMap(collection, iteratee) {
  return baseFlatten(map(collection, iteratee), 1);
}
```
- example usage
```shell
...
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * function duplicate(n) {
 *   return [n, n];
 * }
 *
 * _.flatMap([1, 2], duplicate);
 * // => [1, 1, 2, 2]
 */
function flatMap(collection, iteratee) {
  return baseFlatten(map(collection, iteratee), 1);
}

/**
...
```

#### <a name="apidoc.element.lodash.flatMapDeep"></a>[function <span class="apidocSignatureSpan">lodash.</span>flatMapDeep (collection, iteratee)](#apidoc.element.lodash.flatMapDeep)
- description and source-code
```javascript
function flatMapDeep(collection, iteratee) {
  return baseFlatten(map(collection, iteratee), INFINITY);
}
```
- example usage
```shell
...
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * function duplicate(n) {
 *   return [[[n, n]]];
 * }
 *
 * _.flatMapDeep([1, 2], duplicate);
 * // => [1, 1, 2, 2]
 */
function flatMapDeep(collection, iteratee) {
  return baseFlatten(map(collection, iteratee), INFINITY);
}

/**
...
```

#### <a name="apidoc.element.lodash.flatMapDepth"></a>[function <span class="apidocSignatureSpan">lodash.</span>flatMapDepth (collection, iteratee, depth)](#apidoc.element.lodash.flatMapDepth)
- description and source-code
```javascript
function flatMapDepth(collection, iteratee, depth) {
  depth = depth === undefined ? 1 : toInteger(depth);
  return baseFlatten(map(collection, iteratee), depth);
}
```
- example usage
```shell
...
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * function duplicate(n) {
 *   return [[[n, n]]];
 * }
 *
 * _.flatMapDepth([1, 2], duplicate, 2);
 * // => [[1, 1], [2, 2]]
 */
function flatMapDepth(collection, iteratee, depth) {
  depth = depth === undefined ? 1 : toInteger(depth);
  return baseFlatten(map(collection, iteratee), depth);
}
...
```

#### <a name="apidoc.element.lodash.flatten"></a>[function <span class="apidocSignatureSpan">lodash.</span>flatten (array)](#apidoc.element.lodash.flatten)
- description and source-code
```javascript
function flatten(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseFlatten(array, 1) : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {Array} array The array to flatten.
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * _.flatten([1, [2, [3, [4]], 5]]);
 * // => [1, 2, [3, [4]], 5]
 */
function flatten(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseFlatten(array, 1) : [];
}
...
```

#### <a name="apidoc.element.lodash.flattenDeep"></a>[function <span class="apidocSignatureSpan">lodash.</span>flattenDeep (array)](#apidoc.element.lodash.flattenDeep)
- description and source-code
```javascript
function flattenDeep(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseFlatten(array, INFINITY) : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category Array
 * @param {Array} array The array to flatten.
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * _.flattenDeep([1, [2, [3, [4]], 5]]);
 * // => [1, 2, 3, 4, 5]
 */
function flattenDeep(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseFlatten(array, INFINITY) : [];
}
...
```

#### <a name="apidoc.element.lodash.flattenDepth"></a>[function <span class="apidocSignatureSpan">lodash.</span>flattenDepth (array, depth)](#apidoc.element.lodash.flattenDepth)
- description and source-code
```javascript
function flattenDepth(array, depth) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  depth = depth === undefined ? 1 : toInteger(depth);
  return baseFlatten(array, depth);
}
```
- example usage
```shell
...
 * @param {Array} array The array to flatten.
 * @param {number} [depth=1] The maximum recursion depth.
 * @returns {Array} Returns the new flattened array.
 * @example
 *
 * var array = [1, [2, [3, [4]], 5]];
 *
 * _.flattenDepth(array, 1);
 * // => [1, 2, [3, [4]], 5]
 *
 * _.flattenDepth(array, 2);
 * // => [1, 2, 3, [4], 5]
 */
function flattenDepth(array, depth) {
  var length = array == null ? 0 : array.length;
...
```

#### <a name="apidoc.element.lodash.flip"></a>[function <span class="apidocSignatureSpan">lodash.</span>flip (func)](#apidoc.element.lodash.flip)
- description and source-code
```javascript
function flip(func) {
  return createWrap(func, WRAP_FLIP_FLAG);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Function
 * @param {Function} func The function to flip arguments for.
 * @returns {Function} Returns the new flipped function.
 * @example
 *
 * var flipped = _.flip(function() {
 *   return _.toArray(arguments);
 * });
 *
 * flipped('a', 'b', 'c', 'd');
 * // => ['d', 'c', 'b', 'a']
 */
function flip(func) {
...
```

#### <a name="apidoc.element.lodash.floor"></a>[function <span class="apidocSignatureSpan">lodash.</span>floor (number, precision)](#apidoc.element.lodash.floor)
- description and source-code
```javascript
floor = function (number, precision) {
  number = toNumber(number);
  precision = precision == null ? 0 : nativeMin(toInteger(precision), 292);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
...
* @since 3.10.0
* @category Math
* @param {number} number The number to round down.
* @param {number} [precision=0] The precision to round down to.
* @returns {number} Returns the rounded down number.
* @example
*
* _.floor(4.006);
* // => 4
*
* _.floor(0.046, 2);
* // => 0.04
*
* _.floor(4060, -2);
* // => 4000
...
```

#### <a name="apidoc.element.lodash.flow"></a>[function <span class="apidocSignatureSpan">lodash.</span>flow (funcs)](#apidoc.element.lodash.flow)
- description and source-code
```javascript
flow = function (funcs) {
  var length = funcs.length,
      index = length,
      prereq = LodashWrapper.prototype.thru;

  if (fromRight) {
    funcs.reverse();
  }
  while (index--) {
    var func = funcs[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (prereq && !wrapper && getFuncName(func) == 'wrapper') {
      var wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? index : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) &&
          data[1] == (WRAP_ARY_FLAG | WRAP_CURRY_FLAG | WRAP_PARTIAL_FLAG | WRAP_REARG_FLAG) &&
          !data[4].length && data[9] == 1
        ) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func))
        ? wrapper[funcName]()
        : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value)) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
...
 * @see _.flowRight
 * @example
 *
 * function square(n) {
 *   return n * n;
 * }
 *
 * var addSquare = _.flow([_.add, square]);
 * addSquare(1, 2);
 * // => 9
 */
var flow = createFlow();

/**
 * This method is like '_.flow' except that it creates a function that
...
```

#### <a name="apidoc.element.lodash.flowRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>flowRight (funcs)](#apidoc.element.lodash.flowRight)
- description and source-code
```javascript
flowRight = function (funcs) {
  var length = funcs.length,
      index = length,
      prereq = LodashWrapper.prototype.thru;

  if (fromRight) {
    funcs.reverse();
  }
  while (index--) {
    var func = funcs[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (prereq && !wrapper && getFuncName(func) == 'wrapper') {
      var wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? index : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) &&
          data[1] == (WRAP_ARY_FLAG | WRAP_CURRY_FLAG | WRAP_PARTIAL_FLAG | WRAP_REARG_FLAG) &&
          !data[4].length && data[9] == 1
        ) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func))
        ? wrapper[funcName]()
        : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value)) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
...
 * @see _.flow
 * @example
 *
 * function square(n) {
 *   return n * n;
 * }
 *
 * var addSquare = _.flowRight([square, _.add]);
 * addSquare(1, 2);
 * // => 9
 */
var flowRight = createFlow(true);

/**
 * This method returns the first argument it receives.
...
```

#### <a name="apidoc.element.lodash.forEach"></a>[function <span class="apidocSignatureSpan">lodash.</span>forEach (collection, iteratee)](#apidoc.element.lodash.forEach)
- description and source-code
```javascript
function forEach(collection, iteratee) {
  var func = isArray(collection) ? arrayEach : baseEach;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
 * @param {Object} map The map to convert.
 * @returns {Array} Returns the key-value pairs.
 */
function mapToArray(map) {
  var index = -1,
      result = Array(map.size);

  map.forEach(function(value, key) {
    result[++index] = [key, value];
  });
  return result;
}

/**
 * Creates a unary function that invokes 'func' with its argument transformed.
...
```

#### <a name="apidoc.element.lodash.forEachRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>forEachRight (collection, iteratee)](#apidoc.element.lodash.forEachRight)
- description and source-code
```javascript
function forEachRight(collection, iteratee) {
  var func = isArray(collection) ? arrayEachRight : baseEachRight;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
 * @category Collection
 * @param {Array|Object} collection The collection to iterate over.
 * @param {Function} [iteratee=_.identity] The function invoked per iteration.
 * @returns {Array|Object} Returns 'collection'.
 * @see _.forEach
 * @example
 *
 * _.forEachRight([1, 2], function(value) {
 *   console.log(value);
 * });
 * // => Logs '2' then '1'.
 */
function forEachRight(collection, iteratee) {
  var func = isArray(collection) ? arrayEachRight : baseEachRight;
  return func(collection, getIteratee(iteratee, 3));
...
```

#### <a name="apidoc.element.lodash.forIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>forIn (object, iteratee)](#apidoc.element.lodash.forIn)
- description and source-code
```javascript
function forIn(object, iteratee) {
  return object == null
    ? object
    : baseFor(object, getIteratee(iteratee, 3), keysIn);
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.forIn(new Foo, function(value, key) {
 *   console.log(key);
 * });
 * // => Logs 'a', 'b', then 'c' (iteration order is not guaranteed).
 */
function forIn(object, iteratee) {
  return object == null
    ? object
...
```

#### <a name="apidoc.element.lodash.forInRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>forInRight (object, iteratee)](#apidoc.element.lodash.forInRight)
- description and source-code
```javascript
function forInRight(object, iteratee) {
  return object == null
    ? object
    : baseForRight(object, getIteratee(iteratee, 3), keysIn);
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.forInRight(new Foo, function(value, key) {
 *   console.log(key);
 * });
 * // => Logs 'c', 'b', then 'a' assuming '_.forIn' logs 'a', 'b', then 'c'.
 */
function forInRight(object, iteratee) {
  return object == null
    ? object
...
```

#### <a name="apidoc.element.lodash.forOwn"></a>[function <span class="apidocSignatureSpan">lodash.</span>forOwn (object, iteratee)](#apidoc.element.lodash.forOwn)
- description and source-code
```javascript
function forOwn(object, iteratee) {
  return object && baseForOwn(object, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.forOwn(new Foo, function(value, key) {
 *   console.log(key);
 * });
 * // => Logs 'a' then 'b' (iteration order is not guaranteed).
 */
function forOwn(object, iteratee) {
  return object && baseForOwn(object, getIteratee(iteratee, 3));
}
...
```

#### <a name="apidoc.element.lodash.forOwnRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>forOwnRight (object, iteratee)](#apidoc.element.lodash.forOwnRight)
- description and source-code
```javascript
function forOwnRight(object, iteratee) {
  return object && baseForOwnRight(object, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.forOwnRight(new Foo, function(value, key) {
 *   console.log(key);
 * });
 * // => Logs 'b' then 'a' assuming '_.forOwn' logs 'a' then 'b'.
 */
function forOwnRight(object, iteratee) {
  return object && baseForOwnRight(object, getIteratee(iteratee, 3));
}
...
```

#### <a name="apidoc.element.lodash.fromPairs"></a>[function <span class="apidocSignatureSpan">lodash.</span>fromPairs (pairs)](#apidoc.element.lodash.fromPairs)
- description and source-code
```javascript
function fromPairs(pairs) {
  var index = -1,
      length = pairs == null ? 0 : pairs.length,
      result = {};

  while (++index < length) {
    var pair = pairs[index];
    result[pair[0]] = pair[1];
  }
  return result;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Array
 * @param {Array} pairs The key-value pairs.
 * @returns {Object} Returns the new object.
 * @example
 *
 * _.fromPairs([['a', 1], ['b', 2]]);
 * // => { 'a': 1, 'b': 2 }
 */
function fromPairs(pairs) {
  var index = -1,
      length = pairs == null ? 0 : pairs.length,
      result = {};
...
```

#### <a name="apidoc.element.lodash.functions"></a>[function <span class="apidocSignatureSpan">lodash.</span>functions (object)](#apidoc.element.lodash.functions)
- description and source-code
```javascript
function functions(object) {
  return object == null ? [] : baseFunctions(object, keys(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = _.constant('a');
 *   this.b = _.constant('b');
 * }
 *
 * Foo.prototype.c = _.constant('c');
 *
 * _.functions(new Foo);
 * // => ['a', 'b']
 */
function functions(object) {
  return object == null ? [] : baseFunctions(object, keys(object));
}

/**
...
```

#### <a name="apidoc.element.lodash.functionsIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>functionsIn (object)](#apidoc.element.lodash.functionsIn)
- description and source-code
```javascript
function functionsIn(object) {
  return object == null ? [] : baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = _.constant('a');
 *   this.b = _.constant('b');
 * }
 *
 * Foo.prototype.c = _.constant('c');
 *
 * _.functionsIn(new Foo);
 * // => ['a', 'b', 'c']
 */
function functionsIn(object) {
  return object == null ? [] : baseFunctions(object, keysIn(object));
}

/**
...
```

#### <a name="apidoc.element.lodash.get"></a>[function <span class="apidocSignatureSpan">lodash.</span>get (object, path, defaultValue)](#apidoc.element.lodash.get)
- description and source-code
```javascript
function get(object, path, defaultValue) {
  var result = object == null ? undefined : baseGet(object, path);
  return result === undefined ? defaultValue : result;
}
```
- example usage
```shell
...
 * @private
 * @name get
 * @memberOf MapCache
 * @param {string} key The key of the value to get.
 * @returns {*} Returns the entry value.
 */
function mapCacheGet(key) {
  return getMapData(this, key).get(key);
}

/**
 * Checks if a map value for 'key' exists.
 *
 * @private
 * @name has
...
```

#### <a name="apidoc.element.lodash.groupBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>groupBy (collection, iteratee)](#apidoc.element.lodash.groupBy)
- description and source-code
```javascript
groupBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee, 2), accumulator);
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @category Collection
 * @param {Array|Object} collection The collection to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee to transform keys.
 * @returns {Object} Returns the composed aggregate object.
 * @example
 *
 * _.groupBy([6.1, 4.2, 6.3], Math.floor);
 * // => { '4': [4.2], '6': [6.1, 6.3] }
 *
 * // The '_.property' iteratee shorthand.
 * _.groupBy(['one', 'two', 'three'], 'length');
 * // => { '3': ['one', 'two'], '5': ['three'] }
 */
var groupBy = createAggregator(function(result, value, key) {
...
```

#### <a name="apidoc.element.lodash.gt"></a>[function <span class="apidocSignatureSpan">lodash.</span>gt (value, other)](#apidoc.element.lodash.gt)
- description and source-code
```javascript
gt = function (value, other) {
  if (!(typeof value == 'string' && typeof other == 'string')) {
    value = toNumber(value);
    other = toNumber(other);
  }
  return operator(value, other);
}
```
- example usage
```shell
...
* @param {*} value The value to compare.
* @param {*} other The other value to compare.
* @returns {boolean} Returns 'true' if 'value' is greater than 'other',
*  else 'false'.
* @see _.lt
* @example
*
* _.gt(3, 1);
* // => true
*
* _.gt(3, 3);
* // => false
*
* _.gt(1, 3);
* // => false
...
```

#### <a name="apidoc.element.lodash.gte"></a>[function <span class="apidocSignatureSpan">lodash.</span>gte (value, other)](#apidoc.element.lodash.gte)
- description and source-code
```javascript
gte = function (value, other) {
  if (!(typeof value == 'string' && typeof other == 'string')) {
    value = toNumber(value);
    other = toNumber(other);
  }
  return operator(value, other);
}
```
- example usage
```shell
...
* @param {*} value The value to compare.
* @param {*} other The other value to compare.
* @returns {boolean} Returns 'true' if 'value' is greater than or equal to
*  'other', else 'false'.
* @see _.lte
* @example
*
* _.gte(3, 1);
* // => true
*
* _.gte(3, 3);
* // => true
*
* _.gte(1, 3);
* // => false
...
```

#### <a name="apidoc.element.lodash.has"></a>[function <span class="apidocSignatureSpan">lodash.</span>has (object, path)](#apidoc.element.lodash.has)
- description and source-code
```javascript
function has(object, path) {
  return object != null && hasPath(object, path, baseHas);
}
```
- example usage
```shell
...
 *
 * @private
 * @param {Object} cache The cache to query.
 * @param {string} key The key of the entry to check.
 * @returns {boolean} Returns 'true' if an entry for 'key' exists, else 'false'.
 */
function cacheHas(cache, key) {
  return cache.has(key);
}

/**
 * Used by '_.trim' and '_.trimStart' to get the index of the first string symbol
 * that is not found in the character symbols.
 *
 * @private
...
```

#### <a name="apidoc.element.lodash.hasIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>hasIn (object, path)](#apidoc.element.lodash.hasIn)
- description and source-code
```javascript
function hasIn(object, path) {
  return object != null && hasPath(object, path, baseHasIn);
}
```
- example usage
```shell
...
* @param {Object} object The object to query.
* @param {Array|string} path The path to check.
* @returns {boolean} Returns 'true' if 'path' exists, else 'false'.
* @example
*
* var object = _.create({ 'a': _.create({ 'b': 2 }) });
*
* _.hasIn(object, 'a');
* // => true
*
* _.hasIn(object, 'a.b');
* // => true
*
* _.hasIn(object, ['a', 'b']);
* // => true
...
```

#### <a name="apidoc.element.lodash.head"></a>[function <span class="apidocSignatureSpan">lodash.</span>head (array)](#apidoc.element.lodash.head)
- description and source-code
```javascript
function head(array) {
  return (array && array.length) ? array[0] : undefined;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @alias first
 * @category Array
 * @param {Array} array The array to query.
 * @returns {*} Returns the first element of 'array'.
 * @example
 *
 * _.head([1, 2, 3]);
 * // => 1
 *
 * _.head([]);
 * // => undefined
 */
function head(array) {
  return (array && array.length) ? array[0] : undefined;
...
```

#### <a name="apidoc.element.lodash.identity"></a>[function <span class="apidocSignatureSpan">lodash.</span>identity (value)](#apidoc.element.lodash.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
...
 * @category Util
 * @param {*} value Any value.
 * @returns {*} Returns 'value'.
 * @example
 *
 * var object = { 'a': 1 };
 *
 * console.log(_.identity(object) === object);
 * // => true
 */
function identity(value) {
  return value;
}

/**
...
```

#### <a name="apidoc.element.lodash.inRange"></a>[function <span class="apidocSignatureSpan">lodash.</span>inRange (number, start, end)](#apidoc.element.lodash.inRange)
- description and source-code
```javascript
function inRange(number, start, end) {
  start = toFinite(start);
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toFinite(end);
  }
  number = toNumber(number);
  return baseInRange(number, start, end);
}
```
- example usage
```shell
...
* @param {number} number The number to check.
* @param {number} [start=0] The start of the range.
* @param {number} end The end of the range.
* @returns {boolean} Returns 'true' if 'number' is in the range, else 'false'.
* @see _.range, _.rangeRight
* @example
*
* _.inRange(3, 2, 4);
* // => true
*
* _.inRange(4, 8);
* // => true
*
* _.inRange(4, 2);
* // => false
...
```

#### <a name="apidoc.element.lodash.includes"></a>[function <span class="apidocSignatureSpan">lodash.</span>includes (collection, value, fromIndex, guard)](#apidoc.element.lodash.includes)
- description and source-code
```javascript
function includes(collection, value, fromIndex, guard) {
  collection = isArrayLike(collection) ? collection : values(collection);
  fromIndex = (fromIndex && !guard) ? toInteger(fromIndex) : 0;

  var length = collection.length;
  if (fromIndex < 0) {
    fromIndex = nativeMax(length + fromIndex, 0);
  }
  return isString(collection)
    ? (fromIndex <= length && collection.indexOf(value, fromIndex) > -1)
    : (!!length && baseIndexOf(collection, value, fromIndex) > -1);
}
```
- example usage
```shell
...
* @param {Array|Object|string} collection The collection to inspect.
* @param {*} value The value to search for.
* @param {number} [fromIndex=0] The index to search from.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.reduce'.
* @returns {boolean} Returns 'true' if 'value' is found, else 'false'.
* @example
*
* _.includes([1, 2, 3], 1);
* // => true
*
* _.includes([1, 2, 3], 1, 2);
* // => false
*
* _.includes({ 'a': 1, 'b': 2 }, 1);
* // => true
...
```

#### <a name="apidoc.element.lodash.indexOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash.indexOf)
- description and source-code
```javascript
function indexOf(array, value, fromIndex) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return -1;
  }
  var index = fromIndex == null ? 0 : toInteger(fromIndex);
  if (index < 0) {
    index = nativeMax(length + index, 0);
  }
  return baseIndexOf(array, value, index);
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {*} value The value to search for.
 * @param {number} [fromIndex=0] The index to search from.
 * @returns {number} Returns the index of the matched value, else '-1'.
 * @example
 *
 * _.indexOf([1, 2, 1, 2], 2);
 * // => 1
 *
 * // Search from the 'fromIndex'.
 * _.indexOf([1, 2, 1, 2], 2, 2);
 * // => 3
 */
function indexOf(array, value, fromIndex) {
...
```

#### <a name="apidoc.element.lodash.initial"></a>[function <span class="apidocSignatureSpan">lodash.</span>initial (array)](#apidoc.element.lodash.initial)
- description and source-code
```javascript
function initial(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseSlice(array, 0, -1) : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {Array} array The array to query.
 * @returns {Array} Returns the slice of 'array'.
 * @example
 *
 * _.initial([1, 2, 3]);
 * // => [1, 2]
 */
function initial(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseSlice(array, 0, -1) : [];
}
...
```

#### <a name="apidoc.element.lodash.intersection"></a>[function <span class="apidocSignatureSpan">lodash.</span>intersection (arrays)](#apidoc.element.lodash.intersection)
- description and source-code
```javascript
intersection = function (arrays) {
  var mapped = arrayMap(arrays, castArrayLikeObject);
  return (mapped.length && mapped[0] === arrays[0])
    ? baseIntersection(mapped)
    : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @returns {Array} Returns the new array of intersecting values.
 * @example
 *
 * _.intersection([2, 1], [2, 3]);
 * // => [2]
 */
var intersection = baseRest(function(arrays) {
  var mapped = arrayMap(arrays, castArrayLikeObject);
  return (mapped.length && mapped[0] === arrays[0])
    ? baseIntersection(mapped)
    : [];
...
```

#### <a name="apidoc.element.lodash.intersectionBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>intersectionBy (arrays)](#apidoc.element.lodash.intersectionBy)
- description and source-code
```javascript
intersectionBy = function (arrays) {
  var iteratee = last(arrays),
      mapped = arrayMap(arrays, castArrayLikeObject);

  if (iteratee === last(mapped)) {
    iteratee = undefined;
  } else {
    mapped.pop();
  }
  return (mapped.length && mapped[0] === arrays[0])
    ? baseIntersection(mapped, getIteratee(iteratee, 2))
    : [];
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns the new array of intersecting values.
 * @example
 *
 * _.intersectionBy([2.1, 1.2], [2.3, 3.4], Math.floor);
 * // => [2.1]
 *
 * // The '_.property' iteratee shorthand.
 * _.intersectionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
 * // => [{ 'x': 1 }]
 */
var intersectionBy = baseRest(function(arrays) {
...
```

#### <a name="apidoc.element.lodash.intersectionWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>intersectionWith (arrays)](#apidoc.element.lodash.intersectionWith)
- description and source-code
```javascript
intersectionWith = function (arrays) {
  var comparator = last(arrays),
      mapped = arrayMap(arrays, castArrayLikeObject);

  comparator = typeof comparator == 'function' ? comparator : undefined;
  if (comparator) {
    mapped.pop();
  }
  return (mapped.length && mapped[0] === arrays[0])
    ? baseIntersection(mapped, undefined, comparator)
    : [];
}
```
- example usage
```shell
...
     * @param {Function} [comparator] The comparator invoked per element.
     * @returns {Array} Returns the new array of intersecting values.
     * @example
     *
     * var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
     * var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];
     *
     * _.intersectionWith(objects, others, _.isEqual);
     * // => [{ 'x': 1, 'y': 2 }]
     */
    var intersectionWith = baseRest(function(arrays) {
var comparator = last(arrays),
    mapped = arrayMap(arrays, castArrayLikeObject);

comparator = typeof comparator == 'function' ? comparator : undefined;
...
```

#### <a name="apidoc.element.lodash.invert"></a>[function <span class="apidocSignatureSpan">lodash.</span>invert (object, iteratee)](#apidoc.element.lodash.invert)
- description and source-code
```javascript
invert = function (object, iteratee) {
  return baseInverter(object, setter, toIteratee(iteratee), {});
}
```
- example usage
```shell
...
 * @category Object
 * @param {Object} object The object to invert.
 * @returns {Object} Returns the new inverted object.
 * @example
 *
 * var object = { 'a': 1, 'b': 2, 'c': 1 };
 *
 * _.invert(object);
 * // => { '1': 'c', '2': 'b' }
 */
var invert = createInverter(function(result, value, key) {
  result[value] = key;
}, constant(identity));

/**
...
```

#### <a name="apidoc.element.lodash.invertBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>invertBy (object, iteratee)](#apidoc.element.lodash.invertBy)
- description and source-code
```javascript
invertBy = function (object, iteratee) {
  return baseInverter(object, setter, toIteratee(iteratee), {});
}
```
- example usage
```shell
...
* @param {Object} object The object to invert.
* @param {Function} [iteratee=_.identity] The iteratee invoked per element.
* @returns {Object} Returns the new inverted object.
* @example
*
* var object = { 'a': 1, 'b': 2, 'c': 1 };
*
* _.invertBy(object);
* // => { '1': ['a', 'c'], '2': ['b'] }
*
* _.invertBy(object, function(value) {
*   return 'group' + value;
* });
* // => { 'group1': ['a', 'c'], 'group2': ['b'] }
*/
...
```

#### <a name="apidoc.element.lodash.invoke"></a>[function <span class="apidocSignatureSpan">lodash.</span>invoke (object, path, args)](#apidoc.element.lodash.invoke)
- description and source-code
```javascript
function baseInvoke(object, path, args) {
  path = castPath(path, object);
  object = parent(object, path);
  var func = object == null ? object : object[toKey(last(path))];
  return func == null ? undefined : apply(func, object, args);
}
```
- example usage
```shell
...
 * @param {Array|string} path The path of the method to invoke.
 * @param {...*} [args] The arguments to invoke the method with.
 * @returns {*} Returns the result of the invoked method.
 * @example
 *
 * var object = { 'a': [{ 'b': { 'c': [1, 2, 3, 4] } }] };
 *
 * _.invoke(object, 'a[0].b.c.slice', 1, 3);
 * // => [2, 3]
 */
var invoke = baseRest(baseInvoke);

/**
 * Creates an array of the own enumerable property names of 'object'.
 *
...
```

#### <a name="apidoc.element.lodash.invokeMap"></a>[function <span class="apidocSignatureSpan">lodash.</span>invokeMap (collection, path, args)](#apidoc.element.lodash.invokeMap)
- description and source-code
```javascript
invokeMap = function (collection, path, args) {
  var index = -1,
      isFunc = typeof path == 'function',
      result = isArrayLike(collection) ? Array(collection.length) : [];

  baseEach(collection, function(value) {
    result[++index] = isFunc ? apply(path, value, args) : baseInvoke(value, path, args);
  });
  return result;
}
```
- example usage
```shell
...
 * @param {Array|Object} collection The collection to iterate over.
 * @param {Array|Function|string} path The path of the method to invoke or
 *  the function invoked per iteration.
 * @param {...*} [args] The arguments to invoke each method with.
 * @returns {Array} Returns the array of results.
 * @example
 *
 * _.invokeMap([[5, 1, 7], [3, 2, 1]], 'sort');
 * // => [[1, 5, 7], [1, 2, 3]]
 *
 * _.invokeMap([123, 456], String.prototype.split, '');
 * // => [['1', '2', '3'], ['4', '5', '6']]
 */
var invokeMap = baseRest(function(collection, path, args) {
  var index = -1,
...
```

#### <a name="apidoc.element.lodash.isArguments"></a>[function <span class="apidocSignatureSpan">lodash.</span>isArguments (value)](#apidoc.element.lodash.isArguments)
- description and source-code
```javascript
function baseIsArguments(value) {
  return isObjectLike(value) && baseGetTag(value) == argsTag;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is an 'arguments' object,
 *  else 'false'.
 * @example
 *
 * _.isArguments(function() { return arguments; }());
 * // => true
 *
 * _.isArguments([1, 2, 3]);
 * // => false
 */
var isArguments = baseIsArguments(function() { return arguments; }()) ? baseIsArguments : function(value) {
  return isObjectLike(value) && hasOwnProperty.call(value, 'callee') &&
...
```

#### <a name="apidoc.element.lodash.isArray"></a>[function <span class="apidocSignatureSpan">lodash.</span>isArray ()](#apidoc.element.lodash.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
...
 * // Returns an unwrapped value.
 * wrapped.reduce(_.add);
 * // => 6
 *
 * // Returns a wrapped value.
 * var squares = wrapped.map(square);
 *
 * _.isArray(squares);
 * // => false
 *
 * _.isArray(squares.value());
 * // => true
 */
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
...
```

#### <a name="apidoc.element.lodash.isArrayBuffer"></a>[function <span class="apidocSignatureSpan">lodash.</span>isArrayBuffer (value)](#apidoc.element.lodash.isArrayBuffer)
- description and source-code
```javascript
isArrayBuffer = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is an array buffer, else 'false'.
 * @example
 *
 * _.isArrayBuffer(new ArrayBuffer(2));
 * // => true
 *
 * _.isArrayBuffer(new Array(2));
 * // => false
 */
var isArrayBuffer = nodeIsArrayBuffer ? baseUnary(nodeIsArrayBuffer) : baseIsArrayBuffer;
...
```

#### <a name="apidoc.element.lodash.isArrayLike"></a>[function <span class="apidocSignatureSpan">lodash.</span>isArrayLike (value)](#apidoc.element.lodash.isArrayLike)
- description and source-code
```javascript
function isArrayLike(value) {
  return value != null && isLength(value.length) && !isFunction(value);
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is array-like, else 'false'.
* @example
*
* _.isArrayLike([1, 2, 3]);
* // => true
*
* _.isArrayLike(document.body.children);
* // => true
*
* _.isArrayLike('abc');
* // => true
...
```

#### <a name="apidoc.element.lodash.isArrayLikeObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>isArrayLikeObject (value)](#apidoc.element.lodash.isArrayLikeObject)
- description and source-code
```javascript
function isArrayLikeObject(value) {
  return isObjectLike(value) && isArrayLike(value);
}
```
- example usage
```shell
...
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is an array-like object,
*  else 'false'.
* @example
*
* _.isArrayLikeObject([1, 2, 3]);
* // => true
*
* _.isArrayLikeObject(document.body.children);
* // => true
*
* _.isArrayLikeObject('abc');
* // => false
...
```

#### <a name="apidoc.element.lodash.isBoolean"></a>[function <span class="apidocSignatureSpan">lodash.</span>isBoolean (value)](#apidoc.element.lodash.isBoolean)
- description and source-code
```javascript
function isBoolean(value) {
  return value === true || value === false ||
    (isObjectLike(value) && baseGetTag(value) == boolTag);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a boolean, else 'false'.
 * @example
 *
 * _.isBoolean(false);
 * // => true
 *
 * _.isBoolean(null);
 * // => false
 */
function isBoolean(value) {
  return value === true || value === false ||
...
```

#### <a name="apidoc.element.lodash.isBuffer"></a>[function <span class="apidocSignatureSpan">lodash.</span>isBuffer (b)](#apidoc.element.lodash.isBuffer)
- description and source-code
```javascript
function isBuffer(b) {
  return b instanceof Buffer;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a buffer, else 'false'.
 * @example
 *
 * _.isBuffer(new Buffer(2));
 * // => true
 *
 * _.isBuffer(new Uint8Array(2));
 * // => false
 */
var isBuffer = nativeIsBuffer || stubFalse;
...
```

#### <a name="apidoc.element.lodash.isDate"></a>[function <span class="apidocSignatureSpan">lodash.</span>isDate (value)](#apidoc.element.lodash.isDate)
- description and source-code
```javascript
isDate = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a date object, else 'false'.
 * @example
 *
 * _.isDate(new Date);
 * // => true
 *
 * _.isDate('Mon April 23 2012');
 * // => false
 */
var isDate = nodeIsDate ? baseUnary(nodeIsDate) : baseIsDate;
...
```

#### <a name="apidoc.element.lodash.isElement"></a>[function <span class="apidocSignatureSpan">lodash.</span>isElement (value)](#apidoc.element.lodash.isElement)
- description and source-code
```javascript
function isElement(value) {
  return isObjectLike(value) && value.nodeType === 1 && !isPlainObject(value);
}
```
- example usage
```shell
...
* @param {*} value The value to clone.
* @param {Function} [customizer] The function to customize cloning.
* @returns {*} Returns the cloned value.
* @see _.cloneDeepWith
* @example
*
* function customizer(value) {
*   if (_.isElement(value)) {
*     return value.cloneNode(false);
*   }
* }
*
* var el = _.cloneWith(document.body, customizer);
*
* console.log(el === document.body);
...
```

#### <a name="apidoc.element.lodash.isEmpty"></a>[function <span class="apidocSignatureSpan">lodash.</span>isEmpty (value)](#apidoc.element.lodash.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (value == null) {
    return true;
  }
  if (isArrayLike(value) &&
      (isArray(value) || typeof value == 'string' || typeof value.splice == 'function' ||
        isBuffer(value) || isTypedArray(value) || isArguments(value))) {
    return !value.length;
  }
  var tag = getTag(value);
  if (tag == mapTag || tag == setTag) {
    return !value.size;
  }
  if (isPrototype(value)) {
    return !baseKeys(value).length;
  }
  for (var key in value) {
    if (hasOwnProperty.call(value, key)) {
      return false;
    }
  }
  return true;
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is empty, else 'false'.
* @example
*
* _.isEmpty(null);
* // => true
*
* _.isEmpty(true);
* // => true
*
* _.isEmpty(1);
* // => true
...
```

#### <a name="apidoc.element.lodash.isEqual"></a>[function <span class="apidocSignatureSpan">lodash.</span>isEqual (value, other)](#apidoc.element.lodash.isEqual)
- description and source-code
```javascript
function isEqual(value, other) {
  return baseIsEqual(value, other);
}
```
- example usage
```shell
...
 * @param {*} other The other value to compare.
 * @returns {boolean} Returns 'true' if the values are equivalent, else 'false'.
 * @example
 *
 * var object = { 'a': 1 };
 * var other = { 'a': 1 };
 *
 * _.isEqual(object, other);
 * // => true
 *
 * object === other;
 * // => false
 */
function isEqual(value, other) {
  return baseIsEqual(value, other);
...
```

#### <a name="apidoc.element.lodash.isEqualWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>isEqualWith (value, other, customizer)](#apidoc.element.lodash.isEqualWith)
- description and source-code
```javascript
function isEqualWith(value, other, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return result === undefined ? baseIsEqual(value, other, undefined, customizer) : !!result;
}
```
- example usage
```shell
...
 *     return true;
 *   }
 * }
 *
 * var array = ['hello', 'goodbye'];
 * var other = ['hi', 'goodbye'];
 *
 * _.isEqualWith(array, other, customizer);
 * // => true
 */
function isEqualWith(value, other, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return result === undefined ? baseIsEqual(value, other, undefined, customizer) : !!result;
}
...
```

#### <a name="apidoc.element.lodash.isError"></a>[function <span class="apidocSignatureSpan">lodash.</span>isError (value)](#apidoc.element.lodash.isError)
- description and source-code
```javascript
function isError(value) {
  if (!isObjectLike(value)) {
    return false;
  }
  var tag = baseGetTag(value);
  return tag == errorTag || tag == domExcTag ||
    (typeof value.message == 'string' && typeof value.name == 'string' && !isPlainObject(value));
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is an error object, else 'false'.
 * @example
 *
 * _.isError(new Error);
 * // => true
 *
 * _.isError(Error);
 * // => false
 */
function isError(value) {
  if (!isObjectLike(value)) {
...
```

#### <a name="apidoc.element.lodash.isFinite"></a>[function <span class="apidocSignatureSpan">lodash.</span>isFinite (value)](#apidoc.element.lodash.isFinite)
- description and source-code
```javascript
function isFinite(value) {
  return typeof value == 'number' && nativeIsFinite(value);
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is a finite number, else 'false'.
* @example
*
* _.isFinite(3);
* // => true
*
* _.isFinite(Number.MIN_VALUE);
* // => true
*
* _.isFinite(Infinity);
* // => false
...
```

#### <a name="apidoc.element.lodash.isFunction"></a>[function <span class="apidocSignatureSpan">lodash.</span>isFunction (value)](#apidoc.element.lodash.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  if (!isObject(value)) {
    return false;
  }
  // The use of 'Object#toString' avoids issues with the 'typeof' operator
  // in Safari 9 which returns 'object' for typed arrays and other constructors.
  var tag = baseGetTag(value);
  return tag == funcTag || tag == genTag || tag == asyncTag || tag == proxyTag;
}
```
- example usage
```shell
...
* @example
*
* _.mixin({ 'foo': _.constant('foo') });
*
* var lodash = _.runInContext();
* lodash.mixin({ 'bar': lodash.constant('bar') });
*
* _.isFunction(_.foo);
* // => true
* _.isFunction(_.bar);
* // => false
*
* lodash.isFunction(lodash.foo);
* // => false
* lodash.isFunction(lodash.bar);
...
```

#### <a name="apidoc.element.lodash.isInteger"></a>[function <span class="apidocSignatureSpan">lodash.</span>isInteger (value)](#apidoc.element.lodash.isInteger)
- description and source-code
```javascript
function isInteger(value) {
  return typeof value == 'number' && value == toInteger(value);
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is an integer, else 'false'.
* @example
*
* _.isInteger(3);
* // => true
*
* _.isInteger(Number.MIN_VALUE);
* // => false
*
* _.isInteger(Infinity);
* // => false
...
```

#### <a name="apidoc.element.lodash.isLength"></a>[function <span class="apidocSignatureSpan">lodash.</span>isLength (value)](#apidoc.element.lodash.isLength)
- description and source-code
```javascript
function isLength(value) {
  return typeof value == 'number' &&
    value > -1 && value % 1 == 0 && value <= MAX_SAFE_INTEGER;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is a valid length, else 'false'.
* @example
*
* _.isLength(3);
* // => true
*
* _.isLength(Number.MIN_VALUE);
* // => false
*
* _.isLength(Infinity);
* // => false
...
```

#### <a name="apidoc.element.lodash.isMap"></a>[function <span class="apidocSignatureSpan">lodash.</span>isMap (value)](#apidoc.element.lodash.isMap)
- description and source-code
```javascript
isMap = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a map, else 'false'.
 * @example
 *
 * _.isMap(new Map);
 * // => true
 *
 * _.isMap(new WeakMap);
 * // => false
 */
var isMap = nodeIsMap ? baseUnary(nodeIsMap) : baseIsMap;
...
```

#### <a name="apidoc.element.lodash.isMatch"></a>[function <span class="apidocSignatureSpan">lodash.</span>isMatch (object, source)](#apidoc.element.lodash.isMatch)
- description and source-code
```javascript
function isMatch(object, source) {
  return object === source || baseIsMatch(object, source, getMatchData(source));
}
```
- example usage
```shell
...
 * @param {Object} object The object to inspect.
 * @param {Object} source The object of property values to match.
 * @returns {boolean} Returns 'true' if 'object' is a match, else 'false'.
 * @example
 *
 * var object = { 'a': 1, 'b': 2 };
 *
 * _.isMatch(object, { 'b': 2 });
 * // => true
 *
 * _.isMatch(object, { 'b': 1 });
 * // => false
 */
function isMatch(object, source) {
  return object === source || baseIsMatch(object, source, getMatchData(source));
...
```

#### <a name="apidoc.element.lodash.isMatchWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>isMatchWith (object, source, customizer)](#apidoc.element.lodash.isMatchWith)
- description and source-code
```javascript
function isMatchWith(object, source, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return baseIsMatch(object, source, getMatchData(source), customizer);
}
```
- example usage
```shell
...
 *     return true;
 *   }
 * }
 *
 * var object = { 'greeting': 'hello' };
 * var source = { 'greeting': 'hi' };
 *
 * _.isMatchWith(object, source, customizer);
 * // => true
 */
function isMatchWith(object, source, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return baseIsMatch(object, source, getMatchData(source), customizer);
}
...
```

#### <a name="apidoc.element.lodash.isNaN"></a>[function <span class="apidocSignatureSpan">lodash.</span>isNaN (value)](#apidoc.element.lodash.isNaN)
- description and source-code
```javascript
function isNaN(value) {
  // An 'NaN' primitive is the only value that is not equal to itself.
  // Perform the 'toStringTag' check first to avoid errors with some
  // ActiveX objects in IE.
  return isNumber(value) && value != +value;
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is 'NaN', else 'false'.
* @example
*
* _.isNaN(NaN);
* // => true
*
* _.isNaN(new Number(NaN));
* // => true
*
* isNaN(undefined);
* // => true
...
```

#### <a name="apidoc.element.lodash.isNative"></a>[function <span class="apidocSignatureSpan">lodash.</span>isNative (value)](#apidoc.element.lodash.isNative)
- description and source-code
```javascript
function isNative(value) {
  if (isMaskable(value)) {
    throw new Error(CORE_ERROR_TEXT);
  }
  return baseIsNative(value);
}
```
- example usage
```shell
...
 * @since 3.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a native function,
 *  else 'false'.
 * @example
 *
 * _.isNative(Array.prototype.push);
 * // => true
 *
 * _.isNative(_);
 * // => false
 */
function isNative(value) {
  if (isMaskable(value)) {
...
```

#### <a name="apidoc.element.lodash.isNil"></a>[function <span class="apidocSignatureSpan">lodash.</span>isNil (value)](#apidoc.element.lodash.isNil)
- description and source-code
```javascript
function isNil(value) {
  return value == null;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is nullish, else 'false'.
* @example
*
* _.isNil(null);
* // => true
*
* _.isNil(void 0);
* // => true
*
* _.isNil(NaN);
* // => false
...
```

#### <a name="apidoc.element.lodash.isNull"></a>[function <span class="apidocSignatureSpan">lodash.</span>isNull (value)](#apidoc.element.lodash.isNull)
- description and source-code
```javascript
function isNull(value) {
  return value === null;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is 'null', else 'false'.
 * @example
 *
 * _.isNull(null);
 * // => true
 *
 * _.isNull(void 0);
 * // => false
 */
function isNull(value) {
  return value === null;
...
```

#### <a name="apidoc.element.lodash.isNumber"></a>[function <span class="apidocSignatureSpan">lodash.</span>isNumber (value)](#apidoc.element.lodash.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' ||
    (isObjectLike(value) && baseGetTag(value) == numberTag);
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is a number, else 'false'.
* @example
*
* _.isNumber(3);
* // => true
*
* _.isNumber(Number.MIN_VALUE);
* // => true
*
* _.isNumber(Infinity);
* // => true
...
```

#### <a name="apidoc.element.lodash.isObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>isObject (value)](#apidoc.element.lodash.isObject)
- description and source-code
```javascript
function isObject(value) {
  var type = typeof value;
  return value != null && (type == 'object' || type == 'function');
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is an object, else 'false'.
* @example
*
* _.isObject({});
* // => true
*
* _.isObject([1, 2, 3]);
* // => true
*
* _.isObject(_.noop);
* // => true
...
```

#### <a name="apidoc.element.lodash.isObjectLike"></a>[function <span class="apidocSignatureSpan">lodash.</span>isObjectLike (value)](#apidoc.element.lodash.isObjectLike)
- description and source-code
```javascript
function isObjectLike(value) {
  return value != null && typeof value == 'object';
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is object-like, else 'false'.
* @example
*
* _.isObjectLike({});
* // => true
*
* _.isObjectLike([1, 2, 3]);
* // => true
*
* _.isObjectLike(_.noop);
* // => false
...
```

#### <a name="apidoc.element.lodash.isPlainObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>isPlainObject (value)](#apidoc.element.lodash.isPlainObject)
- description and source-code
```javascript
function isPlainObject(value) {
  if (!isObjectLike(value) || baseGetTag(value) != objectTag) {
    return false;
  }
  var proto = getPrototype(value);
  if (proto === null) {
    return true;
  }
  var Ctor = hasOwnProperty.call(proto, 'constructor') && proto.constructor;
  return typeof Ctor == 'function' && Ctor instanceof Ctor &&
    funcToString.call(Ctor) == objectCtorString;
}
```
- example usage
```shell
...
* @returns {boolean} Returns 'true' if 'value' is a plain object, else 'false'.
* @example
*
* function Foo() {
*   this.a = 1;
* }
*
* _.isPlainObject(new Foo);
* // => false
*
* _.isPlainObject([1, 2, 3]);
* // => false
*
* _.isPlainObject({ 'x': 0, 'y': 0 });
* // => true
...
```

#### <a name="apidoc.element.lodash.isRegExp"></a>[function <span class="apidocSignatureSpan">lodash.</span>isRegExp (value)](#apidoc.element.lodash.isRegExp)
- description and source-code
```javascript
isRegExp = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a regexp, else 'false'.
 * @example
 *
 * _.isRegExp(/abc/);
 * // => true
 *
 * _.isRegExp('/abc/');
 * // => false
 */
var isRegExp = nodeIsRegExp ? baseUnary(nodeIsRegExp) : baseIsRegExp;
...
```

#### <a name="apidoc.element.lodash.isSafeInteger"></a>[function <span class="apidocSignatureSpan">lodash.</span>isSafeInteger (value)](#apidoc.element.lodash.isSafeInteger)
- description and source-code
```javascript
function isSafeInteger(value) {
  return isInteger(value) && value >= -MAX_SAFE_INTEGER && value <= MAX_SAFE_INTEGER;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to check.
* @returns {boolean} Returns 'true' if 'value' is a safe integer, else 'false'.
* @example
*
* _.isSafeInteger(3);
* // => true
*
* _.isSafeInteger(Number.MIN_VALUE);
* // => false
*
* _.isSafeInteger(Infinity);
* // => false
...
```

#### <a name="apidoc.element.lodash.isSet"></a>[function <span class="apidocSignatureSpan">lodash.</span>isSet (value)](#apidoc.element.lodash.isSet)
- description and source-code
```javascript
isSet = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a set, else 'false'.
 * @example
 *
 * _.isSet(new Set);
 * // => true
 *
 * _.isSet(new WeakSet);
 * // => false
 */
var isSet = nodeIsSet ? baseUnary(nodeIsSet) : baseIsSet;
...
```

#### <a name="apidoc.element.lodash.isString"></a>[function <span class="apidocSignatureSpan">lodash.</span>isString (value)](#apidoc.element.lodash.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' ||
    (!isArray(value) && isObjectLike(value) && baseGetTag(value) == stringTag);
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a string, else 'false'.
 * @example
 *
 * _.isString('abc');
 * // => true
 *
 * _.isString(1);
 * // => false
 */
function isString(value) {
  return typeof value == 'string' ||
...
```

#### <a name="apidoc.element.lodash.isSymbol"></a>[function <span class="apidocSignatureSpan">lodash.</span>isSymbol (value)](#apidoc.element.lodash.isSymbol)
- description and source-code
```javascript
function isSymbol(value) {
  return typeof value == 'symbol' ||
    (isObjectLike(value) && baseGetTag(value) == symbolTag);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a symbol, else 'false'.
 * @example
 *
 * _.isSymbol(Symbol.iterator);
 * // => true
 *
 * _.isSymbol('abc');
 * // => false
 */
function isSymbol(value) {
  return typeof value == 'symbol' ||
...
```

#### <a name="apidoc.element.lodash.isTypedArray"></a>[function <span class="apidocSignatureSpan">lodash.</span>isTypedArray (value)](#apidoc.element.lodash.isTypedArray)
- description and source-code
```javascript
isTypedArray = function (value) {
  return func(value);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.0.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a typed array, else 'false'.
 * @example
 *
 * _.isTypedArray(new Uint8Array);
 * // => true
 *
 * _.isTypedArray([]);
 * // => false
 */
var isTypedArray = nodeIsTypedArray ? baseUnary(nodeIsTypedArray) : baseIsTypedArray;
...
```

#### <a name="apidoc.element.lodash.isUndefined"></a>[function <span class="apidocSignatureSpan">lodash.</span>isUndefined (value)](#apidoc.element.lodash.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return value === undefined;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is 'undefined', else 'false'.
 * @example
 *
 * _.isUndefined(void 0);
 * // => true
 *
 * _.isUndefined(null);
 * // => false
 */
function isUndefined(value) {
  return value === undefined;
...
```

#### <a name="apidoc.element.lodash.isWeakMap"></a>[function <span class="apidocSignatureSpan">lodash.</span>isWeakMap (value)](#apidoc.element.lodash.isWeakMap)
- description and source-code
```javascript
function isWeakMap(value) {
  return isObjectLike(value) && getTag(value) == weakMapTag;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a weak map, else 'false'.
 * @example
 *
 * _.isWeakMap(new WeakMap);
 * // => true
 *
 * _.isWeakMap(new Map);
 * // => false
 */
function isWeakMap(value) {
  return isObjectLike(value) && getTag(value) == weakMapTag;
...
```

#### <a name="apidoc.element.lodash.isWeakSet"></a>[function <span class="apidocSignatureSpan">lodash.</span>isWeakSet (value)](#apidoc.element.lodash.isWeakSet)
- description and source-code
```javascript
function isWeakSet(value) {
  return isObjectLike(value) && baseGetTag(value) == weakSetTag;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.3.0
 * @category Lang
 * @param {*} value The value to check.
 * @returns {boolean} Returns 'true' if 'value' is a weak set, else 'false'.
 * @example
 *
 * _.isWeakSet(new WeakSet);
 * // => true
 *
 * _.isWeakSet(new Set);
 * // => false
 */
function isWeakSet(value) {
  return isObjectLike(value) && baseGetTag(value) == weakSetTag;
...
```

#### <a name="apidoc.element.lodash.iteratee"></a>[function <span class="apidocSignatureSpan">lodash.</span>iteratee (func)](#apidoc.element.lodash.iteratee)
- description and source-code
```javascript
function iteratee(func) {
  return baseIteratee(typeof func == 'function' ? func : baseClone(func, CLONE_DEEP_FLAG));
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney', 'age': 36, 'active': true },
*   { 'user': 'fred',   'age': 40, 'active': false }
* ];
*
* // The '_.matches' iteratee shorthand.
* _.filter(users, _.iteratee({ 'user': 'barney', 'active': true }));
* // => [{ 'user': 'barney', 'age': 36, 'active': true }]
*
* // The '_.matchesProperty' iteratee shorthand.
* _.filter(users, _.iteratee(['user', 'fred']));
* // => [{ 'user': 'fred', 'age': 40 }]
*
* // The '_.property' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.join"></a>[function <span class="apidocSignatureSpan">lodash.</span>join (array, separator)](#apidoc.element.lodash.join)
- description and source-code
```javascript
function join(array, separator) {
  return array == null ? '' : nativeJoin.call(array, separator);
}
```
- example usage
```shell
...
/** Used to compose unicode regexes. */
var rsMiscLower = '(?:' + rsLower + '|' + rsMisc + ')',
    rsMiscUpper = '(?:' + rsUpper + '|' + rsMisc + ')',
    rsOptContrLower = '(?:' + rsApos + '(?:d|ll|m|re|s|t|ve))?',
    rsOptContrUpper = '(?:' + rsApos + '(?:D|LL|M|RE|S|T|VE))?',
    reOptMod = rsModifier + '?',
    rsOptVar = '[' + rsVarRange + ']?',
    rsOptJoin = '(?:' + rsZWJ + '(?:' + [rsNonAstral, rsRegional, rsSurrPair].join('|') + ')' + rsOptVar + reOptMod + ')*',
    rsOrdLower = '\\d*(?:(?:1st|2nd|3rd|(?![123])\\dth)\\b)',
    rsOrdUpper = '\\d*(?:(?:1ST|2ND|3RD|(?![123])\\dTH)\\b)',
    rsSeq = rsOptVar + reOptMod + rsOptJoin,
    rsEmoji = '(?:' + [rsDingbat, rsRegional, rsSurrPair].join('|') + ')' + rsSeq,
    rsSymbol = '(?:' + [rsNonAstral + rsCombo + '?', rsCombo, rsRegional, rsSurrPair, rsAstral].join('|') + ')';

/** Used to match apostrophes. */
...
```

#### <a name="apidoc.element.lodash.kebabCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>kebabCase (string)](#apidoc.element.lodash.kebabCase)
- description and source-code
```javascript
kebabCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 3.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the kebab cased string.
* @example
*
* _.kebabCase('Foo Bar');
* // => 'foo-bar'
*
* _.kebabCase('fooBar');
* // => 'foo-bar'
*
* _.kebabCase('__FOO_BAR__');
* // => 'foo-bar'
...
```

#### <a name="apidoc.element.lodash.keyBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>keyBy (collection, iteratee)](#apidoc.element.lodash.keyBy)
- description and source-code
```javascript
keyBy = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee, 2), accumulator);
}
```
- example usage
```shell
...
* @example
*
* var array = [
*   { 'dir': 'left', 'code': 97 },
*   { 'dir': 'right', 'code': 100 }
* ];
*
* _.keyBy(array, function(o) {
*   return String.fromCharCode(o.code);
* });
* // => { 'a': { 'dir': 'left', 'code': 97 }, 'd': { 'dir': 'right', 'code': 100 } }
*
* _.keyBy(array, 'dir');
* // => { 'left': { 'dir': 'left', 'code': 97 }, 'right': { 'dir': 'right', 'code': 100 } }
*/
...
```

#### <a name="apidoc.element.lodash.keys"></a>[function <span class="apidocSignatureSpan">lodash.</span>keys (object)](#apidoc.element.lodash.keys)
- description and source-code
```javascript
function keys(object) {
  return isArrayLike(object) ? arrayLikeKeys(object) : baseKeys(object);
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.keys(new Foo);
 * // => ['a', 'b'] (iteration order is not guaranteed)
 *
 * _.keys('hi');
 * // => ['0', '1']
 */
function keys(object) {
  return isArrayLike(object) ? arrayLikeKeys(object) : baseKeys(object);
...
```

#### <a name="apidoc.element.lodash.keysIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>keysIn (object)](#apidoc.element.lodash.keysIn)
- description and source-code
```javascript
function keysIn(object) {
  return isArrayLike(object) ? arrayLikeKeys(object, true) : baseKeysIn(object);
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.keysIn(new Foo);
 * // => ['a', 'b', 'c'] (iteration order is not guaranteed)
 */
function keysIn(object) {
  return isArrayLike(object) ? arrayLikeKeys(object, true) : baseKeysIn(object);
}

/**
...
```

#### <a name="apidoc.element.lodash.last"></a>[function <span class="apidocSignatureSpan">lodash.</span>last (array)](#apidoc.element.lodash.last)
- description and source-code
```javascript
function last(array) {
  var length = array == null ? 0 : array.length;
  return length ? array[length - 1] : undefined;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {Array} array The array to query.
 * @returns {*} Returns the last element of 'array'.
 * @example
 *
 * _.last([1, 2, 3]);
 * // => 3
 */
function last(array) {
  var length = array == null ? 0 : array.length;
  return length ? array[length - 1] : undefined;
}
...
```

#### <a name="apidoc.element.lodash.lastIndexOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(array, value, fromIndex) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return -1;
  }
  var index = length;
  if (fromIndex !== undefined) {
    index = toInteger(fromIndex);
    index = index < 0 ? nativeMax(length + index, 0) : nativeMin(index, length - 1);
  }
  return value === value
    ? strictLastIndexOf(array, value, index)
    : baseFindIndex(array, baseIsNaN, index, true);
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {*} value The value to search for.
 * @param {number} [fromIndex=array.length-1] The index to search from.
 * @returns {number} Returns the index of the matched value, else '-1'.
 * @example
 *
 * _.lastIndexOf([1, 2, 1, 2], 2);
 * // => 3
 *
 * // Search from the 'fromIndex'.
 * _.lastIndexOf([1, 2, 1, 2], 2, 2);
 * // => 1
 */
function lastIndexOf(array, value, fromIndex) {
...
```

#### <a name="apidoc.element.lodash.lowerCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>lowerCase (string)](#apidoc.element.lodash.lowerCase)
- description and source-code
```javascript
lowerCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the lower cased string.
* @example
*
* _.lowerCase('--Foo-Bar--');
* // => 'foo bar'
*
* _.lowerCase('fooBar');
* // => 'foo bar'
*
* _.lowerCase('__FOO_BAR__');
* // => 'foo bar'
...
```

#### <a name="apidoc.element.lodash.lowerFirst"></a>[function <span class="apidocSignatureSpan">lodash.</span>lowerFirst (string)](#apidoc.element.lodash.lowerFirst)
- description and source-code
```javascript
lowerFirst = function (string) {
  string = toString(string);

  var strSymbols = hasUnicode(string)
    ? stringToArray(string)
    : undefined;

  var chr = strSymbols
    ? strSymbols[0]
    : string.charAt(0);

  var trailing = strSymbols
    ? castSlice(strSymbols, 1).join('')
    : string.slice(1);

  return chr[methodName]() + trailing;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category String
 * @param {string} [string=''] The string to convert.
 * @returns {string} Returns the converted string.
 * @example
 *
 * _.lowerFirst('Fred');
 * // => 'fred'
 *
 * _.lowerFirst('FRED');
 * // => 'fRED'
 */
var lowerFirst = createCaseFirst('toLowerCase');
...
```

#### <a name="apidoc.element.lodash.lt"></a>[function <span class="apidocSignatureSpan">lodash.</span>lt (value, other)](#apidoc.element.lodash.lt)
- description and source-code
```javascript
lt = function (value, other) {
  if (!(typeof value == 'string' && typeof other == 'string')) {
    value = toNumber(value);
    other = toNumber(other);
  }
  return operator(value, other);
}
```
- example usage
```shell
...
* @param {*} value The value to compare.
* @param {*} other The other value to compare.
* @returns {boolean} Returns 'true' if 'value' is less than 'other',
*  else 'false'.
* @see _.gt
* @example
*
* _.lt(1, 3);
* // => true
*
* _.lt(3, 3);
* // => false
*
* _.lt(3, 1);
* // => false
...
```

#### <a name="apidoc.element.lodash.lte"></a>[function <span class="apidocSignatureSpan">lodash.</span>lte (value, other)](#apidoc.element.lodash.lte)
- description and source-code
```javascript
lte = function (value, other) {
  if (!(typeof value == 'string' && typeof other == 'string')) {
    value = toNumber(value);
    other = toNumber(other);
  }
  return operator(value, other);
}
```
- example usage
```shell
...
* @param {*} value The value to compare.
* @param {*} other The other value to compare.
* @returns {boolean} Returns 'true' if 'value' is less than or equal to
*  'other', else 'false'.
* @see _.gte
* @example
*
* _.lte(1, 3);
* // => true
*
* _.lte(3, 3);
* // => true
*
* _.lte(3, 1);
* // => false
...
```

#### <a name="apidoc.element.lodash.map"></a>[function <span class="apidocSignatureSpan">lodash.</span>map (collection, iteratee)](#apidoc.element.lodash.map)
- description and source-code
```javascript
function map(collection, iteratee) {
  var func = isArray(collection) ? arrayMap : baseMap;
  return func(collection, getIteratee(iteratee, 3));
}
```
- example usage
```shell
...
* var wrapped = _([1, 2, 3]);
*
* // Returns an unwrapped value.
* wrapped.reduce(_.add);
* // => 6
*
* // Returns a wrapped value.
* var squares = wrapped.map(square);
*
* _.isArray(squares);
* // => false
*
* _.isArray(squares.value());
* // => true
*/
...
```

#### <a name="apidoc.element.lodash.mapKeys"></a>[function <span class="apidocSignatureSpan">lodash.</span>mapKeys (object, iteratee)](#apidoc.element.lodash.mapKeys)
- description and source-code
```javascript
function mapKeys(object, iteratee) {
  var result = {};
  iteratee = getIteratee(iteratee, 3);

  baseForOwn(object, function(value, key, object) {
    baseAssignValue(result, iteratee(value, key, object), value);
  });
  return result;
}
```
- example usage
```shell
...
 * @category Object
 * @param {Object} object The object to iterate over.
 * @param {Function} [iteratee=_.identity] The function invoked per iteration.
 * @returns {Object} Returns the new mapped object.
 * @see _.mapValues
 * @example
 *
 * _.mapKeys({ 'a': 1, 'b': 2 }, function(value, key) {
 *   return key + value;
 * });
 * // => { 'a1': 1, 'b2': 2 }
 */
function mapKeys(object, iteratee) {
  var result = {};
  iteratee = getIteratee(iteratee, 3);
...
```

#### <a name="apidoc.element.lodash.mapValues"></a>[function <span class="apidocSignatureSpan">lodash.</span>mapValues (object, iteratee)](#apidoc.element.lodash.mapValues)
- description and source-code
```javascript
function mapValues(object, iteratee) {
  var result = {};
  iteratee = getIteratee(iteratee, 3);

  baseForOwn(object, function(value, key, object) {
    baseAssignValue(result, key, iteratee(value, key, object));
  });
  return result;
}
```
- example usage
```shell
...
 * @example
 *
 * var users = {
 *   'fred':    { 'user': 'fred',    'age': 40 },
 *   'pebbles': { 'user': 'pebbles', 'age': 1 }
 * };
 *
 * _.mapValues(users, function(o) { return o.age; });
 * // => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)
 *
 * // The '_.property' iteratee shorthand.
 * _.mapValues(users, 'age');
 * // => { 'fred': 40, 'pebbles': 1 } (iteration order is not guaranteed)
 */
function mapValues(object, iteratee) {
...
```

#### <a name="apidoc.element.lodash.matches"></a>[function <span class="apidocSignatureSpan">lodash.</span>matches (source)](#apidoc.element.lodash.matches)
- description and source-code
```javascript
function matches(source) {
  return baseMatches(baseClone(source, CLONE_DEEP_FLAG));
}
```
- example usage
```shell
...
* @since 4.0.0
* @category Util
* @param {Array} pairs The predicate-function pairs.
* @returns {Function} Returns the new composite function.
* @example
*
* var func = _.cond([
*   [_.matches({ 'a': 1 }),           _.constant('matches A')],
*   [_.conforms({ 'b': _.isNumber }), _.constant('matches B')],
*   [_.stubTrue,                      _.constant('no match')]
* ]);
*
* func({ 'a': 1, 'b': 2 });
* // => 'matches A'
*
...
```

#### <a name="apidoc.element.lodash.matchesProperty"></a>[function <span class="apidocSignatureSpan">lodash.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash.matchesProperty)
- description and source-code
```javascript
function matchesProperty(path, srcValue) {
  return baseMatchesProperty(path, baseClone(srcValue, CLONE_DEEP_FLAG));
}
```
- example usage
```shell
...
 * @example
 *
 * var objects = [
 *   { 'a': 1, 'b': 2, 'c': 3 },
 *   { 'a': 4, 'b': 5, 'c': 6 }
 * ];
 *
 * _.find(objects, _.matchesProperty('a', 4));
 * // => { 'a': 4, 'b': 5, 'c': 6 }
 */
function matchesProperty(path, srcValue) {
  return baseMatchesProperty(path, baseClone(srcValue, CLONE_DEEP_FLAG));
}

/**
...
```

#### <a name="apidoc.element.lodash.max"></a>[function <span class="apidocSignatureSpan">lodash.</span>max (array)](#apidoc.element.lodash.max)
- description and source-code
```javascript
function max(array) {
  return (array && array.length)
    ? baseExtremum(array, identity, baseGt)
    : undefined;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category Math
 * @param {Array} array The array to iterate over.
 * @returns {*} Returns the maximum value.
 * @example
 *
 * _.max([4, 2, 8, 6]);
 * // => 8
 *
 * _.max([]);
 * // => undefined
 */
function max(array) {
  return (array && array.length)
...
```

#### <a name="apidoc.element.lodash.maxBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>maxBy (array, iteratee)](#apidoc.element.lodash.maxBy)
- description and source-code
```javascript
function maxBy(array, iteratee) {
  return (array && array.length)
    ? baseExtremum(array, getIteratee(iteratee, 2), baseGt)
    : undefined;
}
```
- example usage
```shell
...
 * @param {Array} array The array to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {*} Returns the maximum value.
 * @example
 *
 * var objects = [{ 'n': 1 }, { 'n': 2 }];
 *
 * _.maxBy(objects, function(o) { return o.n; });
 * // => { 'n': 2 }
 *
 * // The '_.property' iteratee shorthand.
 * _.maxBy(objects, 'n');
 * // => { 'n': 2 }
 */
function maxBy(array, iteratee) {
...
```

#### <a name="apidoc.element.lodash.mean"></a>[function <span class="apidocSignatureSpan">lodash.</span>mean (array)](#apidoc.element.lodash.mean)
- description and source-code
```javascript
function mean(array) {
  return baseMean(array, identity);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Math
 * @param {Array} array The array to iterate over.
 * @returns {number} Returns the mean.
 * @example
 *
 * _.mean([4, 2, 8, 6]);
 * // => 5
 */
function mean(array) {
  return baseMean(array, identity);
}

/**
...
```

#### <a name="apidoc.element.lodash.meanBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>meanBy (array, iteratee)](#apidoc.element.lodash.meanBy)
- description and source-code
```javascript
function meanBy(array, iteratee) {
  return baseMean(array, getIteratee(iteratee, 2));
}
```
- example usage
```shell
...
 * @param {Array} array The array to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {number} Returns the mean.
 * @example
 *
 * var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];
 *
 * _.meanBy(objects, function(o) { return o.n; });
 * // => 5
 *
 * // The '_.property' iteratee shorthand.
 * _.meanBy(objects, 'n');
 * // => 5
 */
function meanBy(array, iteratee) {
...
```

#### <a name="apidoc.element.lodash.memoize"></a>[function <span class="apidocSignatureSpan">lodash.</span>memoize (func, resolver)](#apidoc.element.lodash.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver != null && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result) || cache;
    return result;
  };
  memoized.cache = new (memoize.Cache || MapCache);
  return memoized;
}
```
- example usage
```shell
...
* @param {Function} [resolver] The function to resolve the cache key.
* @returns {Function} Returns the new memoized function.
* @example
*
* var object = { 'a': 1, 'b': 2 };
* var other = { 'c': 3, 'd': 4 };
*
* var values = _.memoize(_.values);
* values(object);
* // => [1, 2]
*
* values(other);
* // => [3, 4]
*
* object.a = 2;
...
```

#### <a name="apidoc.element.lodash.memoize.Cache"></a>[function <span class="apidocSignatureSpan">lodash.</span>memoize.Cache (entries)](#apidoc.element.lodash.memoize.Cache)
- description and source-code
```javascript
function MapCache(entries) {
  var index = -1,
      length = entries == null ? 0 : entries.length;

  this.clear();
  while (++index < length) {
    var entry = entries[index];
    this.set(entry[0], entry[1]);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.merge"></a>[function <span class="apidocSignatureSpan">lodash.</span>merge (object, sources)](#apidoc.element.lodash.merge)
- description and source-code
```javascript
merge = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
...
 *   'a': [{ 'b': 2 }, { 'd': 4 }]
 * };
 *
 * var other = {
 *   'a': [{ 'c': 3 }, { 'e': 5 }]
 * };
 *
 * _.merge(object, other);
 * // => { 'a': [{ 'b': 2, 'c': 3 }, { 'd': 4, 'e': 5 }] }
 */
var merge = createAssigner(function(object, source, srcIndex) {
  baseMerge(object, source, srcIndex);
});

/**
...
```

#### <a name="apidoc.element.lodash.mergeWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>mergeWith (object, sources)](#apidoc.element.lodash.mergeWith)
- description and source-code
```javascript
mergeWith = function (object, sources) {
  var index = -1,
      length = sources.length,
      customizer = length > 1 ? sources[length - 1] : undefined,
      guard = length > 2 ? sources[2] : undefined;

  customizer = (assigner.length > 3 && typeof customizer == 'function')
    ? (length--, customizer)
    : undefined;

  if (guard && isIterateeCall(sources[0], sources[1], guard)) {
    customizer = length < 3 ? undefined : customizer;
    length = 1;
  }
  object = Object(object);
  while (++index < length) {
    var source = sources[index];
    if (source) {
      assigner(object, source, index, customizer);
    }
  }
  return object;
}
```
- example usage
```shell
...
 *     return objValue.concat(srcValue);
 *   }
 * }
 *
 * var object = { 'a': [1], 'b': [2] };
 * var other = { 'a': [3], 'b': [4] };
 *
 * _.mergeWith(object, other, customizer);
 * // => { 'a': [1, 3], 'b': [2, 4] }
 */
var mergeWith = createAssigner(function(object, source, srcIndex, customizer) {
  baseMerge(object, source, srcIndex, customizer);
});

/**
...
```

#### <a name="apidoc.element.lodash.method"></a>[function <span class="apidocSignatureSpan">lodash.</span>method (path, args)](#apidoc.element.lodash.method)
- description and source-code
```javascript
method = function (path, args) {
  return function(object) {
    return baseInvoke(object, path, args);
  };
}
```
- example usage
```shell
...
 * @example
 *
 * var objects = [
 *   { 'a': { 'b': _.constant(2) } },
 *   { 'a': { 'b': _.constant(1) } }
 * ];
 *
 * _.map(objects, _.method('a.b'));
 * // => [2, 1]
 *
 * _.map(objects, _.method(['a', 'b']));
 * // => [2, 1]
 */
var method = baseRest(function(path, args) {
  return function(object) {
...
```

#### <a name="apidoc.element.lodash.methodOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>methodOf (object, args)](#apidoc.element.lodash.methodOf)
- description and source-code
```javascript
methodOf = function (object, args) {
  return function(path) {
    return baseInvoke(object, path, args);
  };
}
```
- example usage
```shell
...
 * @param {...*} [args] The arguments to invoke the method with.
 * @returns {Function} Returns the new invoker function.
 * @example
 *
 * var array = _.times(3, _.constant),
 *     object = { 'a': array, 'b': array, 'c': array };
 *
 * _.map(['a[2]', 'c[0]'], _.methodOf(object));
 * // => [2, 0]
 *
 * _.map([['a', '2'], ['c', '0']], _.methodOf(object));
 * // => [2, 0]
 */
var methodOf = baseRest(function(object, args) {
  return function(path) {
...
```

#### <a name="apidoc.element.lodash.min"></a>[function <span class="apidocSignatureSpan">lodash.</span>min (array)](#apidoc.element.lodash.min)
- description and source-code
```javascript
function min(array) {
  return (array && array.length)
    ? baseExtremum(array, identity, baseLt)
    : undefined;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category Math
 * @param {Array} array The array to iterate over.
 * @returns {*} Returns the minimum value.
 * @example
 *
 * _.min([4, 2, 8, 6]);
 * // => 2
 *
 * _.min([]);
 * // => undefined
 */
function min(array) {
  return (array && array.length)
...
```

#### <a name="apidoc.element.lodash.minBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>minBy (array, iteratee)](#apidoc.element.lodash.minBy)
- description and source-code
```javascript
function minBy(array, iteratee) {
  return (array && array.length)
    ? baseExtremum(array, getIteratee(iteratee, 2), baseLt)
    : undefined;
}
```
- example usage
```shell
...
 * @param {Array} array The array to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {*} Returns the minimum value.
 * @example
 *
 * var objects = [{ 'n': 1 }, { 'n': 2 }];
 *
 * _.minBy(objects, function(o) { return o.n; });
 * // => { 'n': 1 }
 *
 * // The '_.property' iteratee shorthand.
 * _.minBy(objects, 'n');
 * // => { 'n': 1 }
 */
function minBy(array, iteratee) {
...
```

#### <a name="apidoc.element.lodash.mixin"></a>[function <span class="apidocSignatureSpan">lodash.</span>mixin (object, source, options)](#apidoc.element.lodash.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  var props = keys(source),
      methodNames = baseFunctions(source, props);

  if (options == null &&
      !(isObject(source) && (methodNames.length || !props.length))) {
    options = source;
    source = object;
    object = this;
    methodNames = baseFunctions(source, keys(source));
  }
  var chain = !(isObject(options) && 'chain' in options) || !!options.chain,
      isFunc = isFunction(object);

  arrayEach(methodNames, function(methodName) {
    var func = source[methodName];
    object[methodName] = func;
    if (isFunc) {
      object.prototype[methodName] = function() {
        var chainAll = this.__chain__;
        if (chain || chainAll) {
          var result = object(this.__wrapped__),
              actions = result.__actions__ = copyArray(this.__actions__);

          actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
          result.__chain__ = chainAll;
          return result;
        }
        return func.apply(object, arrayPush([this.value()], arguments));
      };
    }
  });

  return object;
}
```
- example usage
```shell
...
* @memberOf _
* @since 1.1.0
* @category Util
* @param {Object} [context=root] The context object.
* @returns {Function} Returns a new 'lodash' function.
* @example
*
* _.mixin({ 'foo': _.constant('foo') });
*
* var lodash = _.runInContext();
* lodash.mixin({ 'bar': lodash.constant('bar') });
*
* _.isFunction(_.foo);
* // => true
* _.isFunction(_.bar);
...
```

#### <a name="apidoc.element.lodash.multiply"></a>[function <span class="apidocSignatureSpan">lodash.</span>multiply (value, other)](#apidoc.element.lodash.multiply)
- description and source-code
```javascript
multiply = function (value, other) {
  var result;
  if (value === undefined && other === undefined) {
    return defaultValue;
  }
  if (value !== undefined) {
    result = value;
  }
  if (other !== undefined) {
    if (result === undefined) {
      return other;
    }
    if (typeof value == 'string' || typeof other == 'string') {
      value = baseToString(value);
      other = baseToString(other);
    } else {
      value = baseToNumber(value);
      other = baseToNumber(other);
    }
    result = operator(value, other);
  }
  return result;
}
```
- example usage
```shell
...
 * @since 4.7.0
 * @category Math
 * @param {number} multiplier The first number in a multiplication.
 * @param {number} multiplicand The second number in a multiplication.
 * @returns {number} Returns the product.
 * @example
 *
 * _.multiply(6, 4);
 * // => 24
 */
var multiply = createMathOperation(function(multiplier, multiplicand) {
  return multiplier * multiplicand;
}, 1);

/**
...
```

#### <a name="apidoc.element.lodash.negate"></a>[function <span class="apidocSignatureSpan">lodash.</span>negate (predicate)](#apidoc.element.lodash.negate)
- description and source-code
```javascript
function negate(predicate) {
  if (typeof predicate != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function() {
    var args = arguments;
    switch (args.length) {
      case 0: return !predicate.call(this);
      case 1: return !predicate.call(this, args[0]);
      case 2: return !predicate.call(this, args[0], args[1]);
      case 3: return !predicate.call(this, args[0], args[1], args[2]);
    }
    return !predicate.apply(this, args);
  };
}
```
- example usage
```shell
...
 * @returns {Function} Returns the new negated function.
 * @example
 *
 * function isEven(n) {
 *   return n % 2 == 0;
 * }
 *
 * _.filter([1, 2, 3, 4, 5, 6], _.negate(isEven));
 * // => [1, 3, 5]
 */
function negate(predicate) {
  if (typeof predicate != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function() {
...
```

#### <a name="apidoc.element.lodash.noConflict"></a>[function <span class="apidocSignatureSpan">lodash.</span>noConflict ()](#apidoc.element.lodash.noConflict)
- description and source-code
```javascript
function noConflict() {
  if (root._ === this) {
    root._ = oldDash;
  }
  return this;
}
```
- example usage
```shell
...
 * @static
 * @since 0.1.0
 * @memberOf _
 * @category Util
 * @returns {Function} Returns the 'lodash' function.
 * @example
 *
 * var lodash = _.noConflict();
 */
function noConflict() {
  if (root._ === this) {
    root._ = oldDash;
  }
  return this;
}
...
```

#### <a name="apidoc.element.lodash.noop"></a>[function <span class="apidocSignatureSpan">lodash.</span>noop ()](#apidoc.element.lodash.noop)
- description and source-code
```javascript
function noop() {
  // No operation performed.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.now"></a>[function <span class="apidocSignatureSpan">lodash.</span>now ()](#apidoc.element.lodash.now)
- description and source-code
```javascript
now = function () {
  return root.Date.now();
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 2.4.0
 * @category Date
 * @returns {number} Returns the timestamp.
 * @example
 *
 * _.defer(function(stamp) {
 *   console.log(_.now() - stamp);
 * }, _.now());
 * // => Logs the number of milliseconds it took for the deferred invocation.
 */
var now = ctxNow || function() {
  return root.Date.now();
};
...
```

#### <a name="apidoc.element.lodash.nth"></a>[function <span class="apidocSignatureSpan">lodash.</span>nth (array, n)](#apidoc.element.lodash.nth)
- description and source-code
```javascript
function nth(array, n) {
  return (array && array.length) ? baseNth(array, toInteger(n)) : undefined;
}
```
- example usage
```shell
...
 * @param {Array} array The array to query.
 * @param {number} [n=0] The index of the element to return.
 * @returns {*} Returns the nth element of 'array'.
 * @example
 *
 * var array = ['a', 'b', 'c', 'd'];
 *
 * _.nth(array, 1);
 * // => 'b'
 *
 * _.nth(array, -2);
 * // => 'c';
 */
function nth(array, n) {
  return (array && array.length) ? baseNth(array, toInteger(n)) : undefined;
...
```

#### <a name="apidoc.element.lodash.nthArg"></a>[function <span class="apidocSignatureSpan">lodash.</span>nthArg (n)](#apidoc.element.lodash.nthArg)
- description and source-code
```javascript
function nthArg(n) {
  n = toInteger(n);
  return baseRest(function(args) {
    return baseNth(args, n);
  });
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Util
* @param {number} [n=0] The index of the argument to return.
* @returns {Function} Returns the new pass-thru function.
* @example
*
* var func = _.nthArg(1);
* func('a', 'b', 'c', 'd');
* // => 'b'
*
* var func = _.nthArg(-2);
* func('a', 'b', 'c', 'd');
* // => 'c'
*/
...
```

#### <a name="apidoc.element.lodash.omit"></a>[function <span class="apidocSignatureSpan">lodash.</span>omit (object, paths)](#apidoc.element.lodash.omit)
- description and source-code
```javascript
omit = function (object, paths) {
  var result = {};
  if (object == null) {
    return result;
  }
  var isDeep = false;
  paths = arrayMap(paths, function(path) {
    path = castPath(path, object);
    isDeep || (isDeep = path.length > 1);
    return path;
  });
  copyObject(object, getAllKeysIn(object), result);
  if (isDeep) {
    result = baseClone(result, CLONE_DEEP_FLAG | CLONE_FLAT_FLAG | CLONE_SYMBOLS_FLAG, customOmitClone);
  }
  var length = paths.length;
  while (length--) {
    baseUnset(result, paths[length]);
  }
  return result;
}
```
- example usage
```shell
...
 * @param {Object} object The source object.
 * @param {...(string|string[])} [paths] The property paths to omit.
 * @returns {Object} Returns the new object.
 * @example
 *
 * var object = { 'a': 1, 'b': '2', 'c': 3 };
 *
 * _.omit(object, ['a', 'c']);
 * // => { 'b': '2' }
 */
var omit = flatRest(function(object, paths) {
  var result = {};
  if (object == null) {
    return result;
  }
...
```

#### <a name="apidoc.element.lodash.omitBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>omitBy (object, predicate)](#apidoc.element.lodash.omitBy)
- description and source-code
```javascript
function omitBy(object, predicate) {
  return pickBy(object, negate(getIteratee(predicate)));
}
```
- example usage
```shell
...
 * @param {Object} object The source object.
 * @param {Function} [predicate=_.identity] The function invoked per property.
 * @returns {Object} Returns the new object.
 * @example
 *
 * var object = { 'a': 1, 'b': '2', 'c': 3 };
 *
 * _.omitBy(object, _.isNumber);
 * // => { 'b': '2' }
 */
function omitBy(object, predicate) {
  return pickBy(object, negate(getIteratee(predicate)));
}

/**
...
```

#### <a name="apidoc.element.lodash.once"></a>[function <span class="apidocSignatureSpan">lodash.</span>once (func)](#apidoc.element.lodash.once)
- description and source-code
```javascript
function once(func) {
  return before(2, func);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Function
 * @param {Function} func The function to restrict.
 * @returns {Function} Returns the new restricted function.
 * @example
 *
 * var initialize = _.once(createApplication);
 * initialize();
 * initialize();
 * // => 'createApplication' is invoked once
 */
function once(func) {
  return before(2, func);
}
...
```

#### <a name="apidoc.element.lodash.orderBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>orderBy (collection, iteratees, orders, guard)](#apidoc.element.lodash.orderBy)
- description and source-code
```javascript
function orderBy(collection, iteratees, orders, guard) {
  if (collection == null) {
    return [];
  }
  if (!isArray(iteratees)) {
    iteratees = iteratees == null ? [] : [iteratees];
  }
  orders = guard ? undefined : orders;
  if (!isArray(orders)) {
    orders = orders == null ? [] : [orders];
  }
  return baseOrderBy(collection, iteratees, orders);
}
```
- example usage
```shell
...
 *   { 'user': 'fred',   'age': 48 },
 *   { 'user': 'barney', 'age': 34 },
 *   { 'user': 'fred',   'age': 40 },
 *   { 'user': 'barney', 'age': 36 }
 * ];
 *
 * // Sort by 'user' in ascending order and by 'age' in descending order.
 * _.orderBy(users, ['user', 'age'], ['asc', 'desc']);
 * // => objects for [['barney', 36], ['barney', 34], ['fred', 48], ['fred', 40]]
 */
function orderBy(collection, iteratees, orders, guard) {
  if (collection == null) {
    return [];
  }
  if (!isArray(iteratees)) {
...
```

#### <a name="apidoc.element.lodash.over"></a>[function <span class="apidocSignatureSpan">lodash.</span>over (iteratees)](#apidoc.element.lodash.over)
- description and source-code
```javascript
over = function (iteratees) {
  iteratees = arrayMap(iteratees, baseUnary(getIteratee()));
  return baseRest(function(args) {
    var thisArg = this;
    return arrayFunc(iteratees, function(iteratee) {
      return apply(iteratee, thisArg, args);
    });
  });
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Util
 * @param {...(Function|Function[])} [iteratees=[_.identity]]
 *  The iteratees to invoke.
 * @returns {Function} Returns the new function.
 * @example
 *
 * var func = _.over([Math.max, Math.min]);
 *
 * func(1, 2, 3, 4);
 * // => [4, 1]
 */
var over = createOver(arrayMap);

/**
...
```

#### <a name="apidoc.element.lodash.overArgs"></a>[function <span class="apidocSignatureSpan">lodash.</span>overArgs (func, transforms)](#apidoc.element.lodash.overArgs)
- description and source-code
```javascript
overArgs = function (func, transforms) {
  transforms = (transforms.length == 1 && isArray(transforms[0]))
    ? arrayMap(transforms[0], baseUnary(getIteratee()))
    : arrayMap(baseFlatten(transforms, 1), baseUnary(getIteratee()));

  var funcsLength = transforms.length;
  return baseRest(function(args) {
    var index = -1,
        length = nativeMin(args.length, funcsLength);

    while (++index < length) {
      args[index] = transforms[index].call(this, args[index]);
    }
    return apply(func, this, args);
  });
}
```
- example usage
```shell
...
*   return n * 2;
* }
*
* function square(n) {
*   return n * n;
* }
*
* var func = _.overArgs(function(x, y) {
*   return [x, y];
* }, [square, doubled]);
*
* func(9, 3);
* // => [81, 6]
*
* func(10, 5);
...
```

#### <a name="apidoc.element.lodash.overEvery"></a>[function <span class="apidocSignatureSpan">lodash.</span>overEvery (iteratees)](#apidoc.element.lodash.overEvery)
- description and source-code
```javascript
overEvery = function (iteratees) {
  iteratees = arrayMap(iteratees, baseUnary(getIteratee()));
  return baseRest(function(args) {
    var thisArg = this;
    return arrayFunc(iteratees, function(iteratee) {
      return apply(iteratee, thisArg, args);
    });
  });
}
```
- example usage
```shell
...
* @since 4.0.0
* @category Util
* @param {...(Function|Function[])} [predicates=[_.identity]]
*  The predicates to check.
* @returns {Function} Returns the new function.
* @example
*
* var func = _.overEvery([Boolean, isFinite]);
*
* func('1');
* // => true
*
* func(null);
* // => false
*
...
```

#### <a name="apidoc.element.lodash.overSome"></a>[function <span class="apidocSignatureSpan">lodash.</span>overSome (iteratees)](#apidoc.element.lodash.overSome)
- description and source-code
```javascript
overSome = function (iteratees) {
  iteratees = arrayMap(iteratees, baseUnary(getIteratee()));
  return baseRest(function(args) {
    var thisArg = this;
    return arrayFunc(iteratees, function(iteratee) {
      return apply(iteratee, thisArg, args);
    });
  });
}
```
- example usage
```shell
...
* @since 4.0.0
* @category Util
* @param {...(Function|Function[])} [predicates=[_.identity]]
*  The predicates to check.
* @returns {Function} Returns the new function.
* @example
*
* var func = _.overSome([Boolean, isFinite]);
*
* func('1');
* // => true
*
* func(null);
* // => true
*
...
```

#### <a name="apidoc.element.lodash.pad"></a>[function <span class="apidocSignatureSpan">lodash.</span>pad (string, length, chars)](#apidoc.element.lodash.pad)
- description and source-code
```javascript
function pad(string, length, chars) {
  string = toString(string);
  length = toInteger(length);

  var strLength = length ? stringSize(string) : 0;
  if (!length || strLength >= length) {
    return string;
  }
  var mid = (length - strLength) / 2;
  return (
    createPadding(nativeFloor(mid), chars) +
    string +
    createPadding(nativeCeil(mid), chars)
  );
}
```
- example usage
```shell
...
* @category String
* @param {string} [string=''] The string to pad.
* @param {number} [length=0] The padding length.
* @param {string} [chars=' '] The string used as padding.
* @returns {string} Returns the padded string.
* @example
*
* _.pad('abc', 8);
* // => '  abc   '
*
* _.pad('abc', 8, '_-');
* // => '_-abc_-_'
*
* _.pad('abc', 3);
* // => 'abc'
...
```

#### <a name="apidoc.element.lodash.padEnd"></a>[function <span class="apidocSignatureSpan">lodash.</span>padEnd (string, length, chars)](#apidoc.element.lodash.padEnd)
- description and source-code
```javascript
function padEnd(string, length, chars) {
  string = toString(string);
  length = toInteger(length);

  var strLength = length ? stringSize(string) : 0;
  return (length && strLength < length)
    ? (string + createPadding(length - strLength, chars))
    : string;
}
```
- example usage
```shell
...
* @category String
* @param {string} [string=''] The string to pad.
* @param {number} [length=0] The padding length.
* @param {string} [chars=' '] The string used as padding.
* @returns {string} Returns the padded string.
* @example
*
* _.padEnd('abc', 6);
* // => 'abc   '
*
* _.padEnd('abc', 6, '_-');
* // => 'abc_-_'
*
* _.padEnd('abc', 3);
* // => 'abc'
...
```

#### <a name="apidoc.element.lodash.padStart"></a>[function <span class="apidocSignatureSpan">lodash.</span>padStart (string, length, chars)](#apidoc.element.lodash.padStart)
- description and source-code
```javascript
function padStart(string, length, chars) {
  string = toString(string);
  length = toInteger(length);

  var strLength = length ? stringSize(string) : 0;
  return (length && strLength < length)
    ? (createPadding(length - strLength, chars) + string)
    : string;
}
```
- example usage
```shell
...
* @category String
* @param {string} [string=''] The string to pad.
* @param {number} [length=0] The padding length.
* @param {string} [chars=' '] The string used as padding.
* @returns {string} Returns the padded string.
* @example
*
* _.padStart('abc', 6);
* // => '   abc'
*
* _.padStart('abc', 6, '_-');
* // => '_-_abc'
*
* _.padStart('abc', 3);
* // => 'abc'
...
```

#### <a name="apidoc.element.lodash.parseInt"></a>[function <span class="apidocSignatureSpan">lodash.</span>parseInt (string, radix, guard)](#apidoc.element.lodash.parseInt)
- description and source-code
```javascript
function parseInt(string, radix, guard) {
  if (guard || radix == null) {
    radix = 0;
  } else if (radix) {
    radix = +radix;
  }
  return nativeParseInt(toString(string).replace(reTrimStart, ''), radix || 0);
}
```
- example usage
```shell
...
 * @category String
 * @param {string} string The string to convert.
 * @param {number} [radix=10] The radix to interpret 'value' by.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {number} Returns the converted integer.
 * @example
 *
 * _.parseInt('08');
 * // => 8
 *
 * _.map(['6', '08', '10'], _.parseInt);
 * // => [6, 8, 10]
 */
function parseInt(string, radix, guard) {
  if (guard || radix == null) {
...
```

#### <a name="apidoc.element.lodash.partial"></a>[function <span class="apidocSignatureSpan">lodash.</span>partial (func, partials)](#apidoc.element.lodash.partial)
- description and source-code
```javascript
partial = function (func, partials) {
  var holders = replaceHolders(partials, getHolder(partial));
  return createWrap(func, WRAP_PARTIAL_FLAG, undefined, partials, holders);
}
```
- example usage
```shell
...
* @returns {Function} Returns the new partially applied function.
* @example
*
* function greet(greeting, name) {
*   return greeting + ' ' + name;
* }
*
* var sayHelloTo = _.partial(greet, 'hello');
* sayHelloTo('fred');
* // => 'hello fred'
*
* // Partially applied with placeholders.
* var greetFred = _.partial(greet, _, 'fred');
* greetFred('hi');
* // => 'hi fred'
...
```

#### <a name="apidoc.element.lodash.partialRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>partialRight (func, partials)](#apidoc.element.lodash.partialRight)
- description and source-code
```javascript
partialRight = function (func, partials) {
  var holders = replaceHolders(partials, getHolder(partialRight));
  return createWrap(func, WRAP_PARTIAL_RIGHT_FLAG, undefined, partials, holders);
}
```
- example usage
```shell
...
* @returns {Function} Returns the new partially applied function.
* @example
*
* function greet(greeting, name) {
*   return greeting + ' ' + name;
* }
*
* var greetFred = _.partialRight(greet, 'fred');
* greetFred('hi');
* // => 'hi fred'
*
* // Partially applied with placeholders.
* var sayHelloTo = _.partialRight(greet, 'hello', _);
* sayHelloTo('fred');
* // => 'hello fred'
...
```

#### <a name="apidoc.element.lodash.partition"></a>[function <span class="apidocSignatureSpan">lodash.</span>partition (collection, iteratee)](#apidoc.element.lodash.partition)
- description and source-code
```javascript
partition = function (collection, iteratee) {
  var func = isArray(collection) ? arrayAggregator : baseAggregator,
      accumulator = initializer ? initializer() : {};

  return func(collection, setter, getIteratee(iteratee, 2), accumulator);
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'age': 36, 'active': false },
*   { 'user': 'fred',    'age': 40, 'active': true },
*   { 'user': 'pebbles', 'age': 1,  'active': false }
* ];
*
* _.partition(users, function(o) { return o.active; });
* // => objects for [['fred'], ['barney', 'pebbles']]
*
* // The '_.matches' iteratee shorthand.
* _.partition(users, { 'age': 1, 'active': false });
* // => objects for [['pebbles'], ['barney', 'fred']]
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.pick"></a>[function <span class="apidocSignatureSpan">lodash.</span>pick (object, paths)](#apidoc.element.lodash.pick)
- description and source-code
```javascript
pick = function (object, paths) {
  return object == null ? {} : basePick(object, paths);
}
```
- example usage
```shell
...
   * lodash.isFunction(lodash.bar);
   * // => true
   *
   * // Create a suped-up 'defer' in Node.js.
   * var defer = _.runInContext({ 'setTimeout': setImmediate }).defer;
   */
  var runInContext = (function runInContext(context) {
context = context == null ? root : _.defaults(root.Object(), context, _.pick(root, contextProps));

/** Built-in constructor references. */
var Array = context.Array,
    Date = context.Date,
    Error = context.Error,
    Function = context.Function,
    Math = context.Math,
...
```

#### <a name="apidoc.element.lodash.pickBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>pickBy (object, predicate)](#apidoc.element.lodash.pickBy)
- description and source-code
```javascript
function pickBy(object, predicate) {
  if (object == null) {
    return {};
  }
  var props = arrayMap(getAllKeysIn(object), function(prop) {
    return [prop];
  });
  predicate = getIteratee(predicate);
  return basePickBy(object, props, function(value, path) {
    return predicate(value, path[0]);
  });
}
```
- example usage
```shell
...
 * @param {Object} object The source object.
 * @param {Function} [predicate=_.identity] The function invoked per property.
 * @returns {Object} Returns the new object.
 * @example
 *
 * var object = { 'a': 1, 'b': '2', 'c': 3 };
 *
 * _.pickBy(object, _.isNumber);
 * // => { 'a': 1, 'c': 3 }
 */
function pickBy(object, predicate) {
  if (object == null) {
    return {};
  }
  var props = arrayMap(getAllKeysIn(object), function(prop) {
...
```

#### <a name="apidoc.element.lodash.property"></a>[function <span class="apidocSignatureSpan">lodash.</span>property (path)](#apidoc.element.lodash.property)
- description and source-code
```javascript
function property(path) {
  return isKey(path) ? baseProperty(toKey(path)) : basePropertyDeep(path);
}
```
- example usage
```shell
...
 * @example
 *
 * var objects = [
 *   { 'a': { 'b': 2 } },
 *   { 'a': { 'b': 1 } }
 * ];
 *
 * _.map(objects, _.property('a.b'));
 * // => [2, 1]
 *
 * _.map(_.sortBy(objects, _.property(['a', 'b'])), 'a.b');
 * // => [1, 2]
 */
function property(path) {
  return isKey(path) ? baseProperty(toKey(path)) : basePropertyDeep(path);
...
```

#### <a name="apidoc.element.lodash.propertyOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>propertyOf (object)](#apidoc.element.lodash.propertyOf)
- description and source-code
```javascript
function propertyOf(object) {
  return function(path) {
    return object == null ? undefined : baseGet(object, path);
  };
}
```
- example usage
```shell
...
 * @param {Object} object The object to query.
 * @returns {Function} Returns the new accessor function.
 * @example
 *
 * var array = [0, 1, 2],
 *     object = { 'a': array, 'b': array, 'c': array };
 *
 * _.map(['a[2]', 'c[0]'], _.propertyOf(object));
 * // => [2, 0]
 *
 * _.map([['a', '2'], ['c', '0']], _.propertyOf(object));
 * // => [2, 0]
 */
function propertyOf(object) {
  return function(path) {
...
```

#### <a name="apidoc.element.lodash.pull"></a>[function <span class="apidocSignatureSpan">lodash.</span>pull (array, values)](#apidoc.element.lodash.pull)
- description and source-code
```javascript
function pullAll(array, values) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values)
    : array;
}
```
- example usage
```shell
...
 * @param {Array} array The array to modify.
 * @param {...*} [values] The values to remove.
 * @returns {Array} Returns 'array'.
 * @example
 *
 * var array = ['a', 'b', 'c', 'a', 'b', 'c'];
 *
 * _.pull(array, 'a', 'c');
 * console.log(array);
 * // => ['b', 'b']
 */
var pull = baseRest(pullAll);

/**
 * This method is like '_.pull' except that it accepts an array of values to remove.
...
```

#### <a name="apidoc.element.lodash.pullAll"></a>[function <span class="apidocSignatureSpan">lodash.</span>pullAll (array, values)](#apidoc.element.lodash.pullAll)
- description and source-code
```javascript
function pullAll(array, values) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values)
    : array;
}
```
- example usage
```shell
...
 * @param {Array} array The array to modify.
 * @param {Array} values The values to remove.
 * @returns {Array} Returns 'array'.
 * @example
 *
 * var array = ['a', 'b', 'c', 'a', 'b', 'c'];
 *
 * _.pullAll(array, ['a', 'c']);
 * console.log(array);
 * // => ['b', 'b']
 */
function pullAll(array, values) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values)
    : array;
...
```

#### <a name="apidoc.element.lodash.pullAllBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>pullAllBy (array, values, iteratee)](#apidoc.element.lodash.pullAllBy)
- description and source-code
```javascript
function pullAllBy(array, values, iteratee) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values, getIteratee(iteratee, 2))
    : array;
}
```
- example usage
```shell
...
 * @param {Array} values The values to remove.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns 'array'.
 * @example
 *
 * var array = [{ 'x': 1 }, { 'x': 2 }, { 'x': 3 }, { 'x': 1 }];
 *
 * _.pullAllBy(array, [{ 'x': 1 }, { 'x': 3 }], 'x');
 * console.log(array);
 * // => [{ 'x': 2 }]
 */
function pullAllBy(array, values, iteratee) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values, getIteratee(iteratee, 2))
    : array;
...
```

#### <a name="apidoc.element.lodash.pullAllWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>pullAllWith (array, values, comparator)](#apidoc.element.lodash.pullAllWith)
- description and source-code
```javascript
function pullAllWith(array, values, comparator) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values, undefined, comparator)
    : array;
}
```
- example usage
```shell
...
 * @param {Array} values The values to remove.
 * @param {Function} [comparator] The comparator invoked per element.
 * @returns {Array} Returns 'array'.
 * @example
 *
 * var array = [{ 'x': 1, 'y': 2 }, { 'x': 3, 'y': 4 }, { 'x': 5, 'y': 6 }];
 *
 * _.pullAllWith(array, [{ 'x': 3, 'y': 4 }], _.isEqual);
 * console.log(array);
 * // => [{ 'x': 1, 'y': 2 }, { 'x': 5, 'y': 6 }]
 */
function pullAllWith(array, values, comparator) {
  return (array && array.length && values && values.length)
    ? basePullAll(array, values, undefined, comparator)
    : array;
...
```

#### <a name="apidoc.element.lodash.pullAt"></a>[function <span class="apidocSignatureSpan">lodash.</span>pullAt (array, indexes)](#apidoc.element.lodash.pullAt)
- description and source-code
```javascript
pullAt = function (array, indexes) {
  var length = array == null ? 0 : array.length,
      result = baseAt(array, indexes);

  basePullAt(array, arrayMap(indexes, function(index) {
    return isIndex(index, length) ? +index : index;
  }).sort(compareAscending));

  return result;
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to modify.
* @param {...(number|number[])} [indexes] The indexes of elements to remove.
* @returns {Array} Returns the new array of removed elements.
* @example
*
* var array = ['a', 'b', 'c', 'd'];
* var pulled = _.pullAt(array, [1, 3]);
*
* console.log(array);
* // => ['a', 'c']
*
* console.log(pulled);
* // => ['b', 'd']
*/
...
```

#### <a name="apidoc.element.lodash.random"></a>[function <span class="apidocSignatureSpan">lodash.</span>random (lower, upper, floating)](#apidoc.element.lodash.random)
- description and source-code
```javascript
function random(lower, upper, floating) {
  if (floating && typeof floating != 'boolean' && isIterateeCall(lower, upper, floating)) {
    upper = floating = undefined;
  }
  if (floating === undefined) {
    if (typeof upper == 'boolean') {
      floating = upper;
      upper = undefined;
    }
    else if (typeof lower == 'boolean') {
      floating = lower;
      lower = undefined;
    }
  }
  if (lower === undefined && upper === undefined) {
    lower = 0;
    upper = 1;
  }
  else {
    lower = toFinite(lower);
    if (upper === undefined) {
      upper = lower;
      lower = 0;
    } else {
      upper = toFinite(upper);
    }
  }
  if (lower > upper) {
    var temp = lower;
    lower = upper;
    upper = temp;
  }
  if (floating || lower % 1 || upper % 1) {
    var rand = nativeRandom();
    return nativeMin(lower + (rand * (upper - lower + freeParseFloat('1e-' + ((rand + '').length - 1)))), upper);
  }
  return baseRandom(lower, upper);
}
```
- example usage
```shell
...
* @category Number
* @param {number} [lower=0] The lower bound.
* @param {number} [upper=1] The upper bound.
* @param {boolean} [floating] Specify returning a floating-point number.
* @returns {number} Returns the random number.
* @example
*
* _.random(0, 5);
* // => an integer between 0 and 5
*
* _.random(5);
* // => also an integer between 0 and 5
*
* _.random(5, true);
* // => a floating-point number between 0 and 5
...
```

#### <a name="apidoc.element.lodash.range"></a>[function <span class="apidocSignatureSpan">lodash.</span>range (start, end, step)](#apidoc.element.lodash.range)
- description and source-code
```javascript
range = function (start, end, step) {
  if (step && typeof step != 'number' && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  // Ensure the sign of '-0' is preserved.
  start = toFinite(start);
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toFinite(end);
  }
  step = step === undefined ? (start < end ? 1 : -1) : toFinite(step);
  return baseRange(start, end, step, fromRight);
}
```
- example usage
```shell
...
* @param {number} [start=0] The start of the range.
* @param {number} end The end of the range.
* @param {number} [step=1] The value to increment or decrement by.
* @returns {Array} Returns the range of numbers.
* @see _.inRange, _.rangeRight
* @example
*
* _.range(4);
* // => [0, 1, 2, 3]
*
* _.range(-4);
* // => [0, -1, -2, -3]
*
* _.range(1, 5);
* // => [1, 2, 3, 4]
...
```

#### <a name="apidoc.element.lodash.rangeRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>rangeRight (start, end, step)](#apidoc.element.lodash.rangeRight)
- description and source-code
```javascript
rangeRight = function (start, end, step) {
  if (step && typeof step != 'number' && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  // Ensure the sign of '-0' is preserved.
  start = toFinite(start);
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = toFinite(end);
  }
  step = step === undefined ? (start < end ? 1 : -1) : toFinite(step);
  return baseRange(start, end, step, fromRight);
}
```
- example usage
```shell
...
* @param {number} [start=0] The start of the range.
* @param {number} end The end of the range.
* @param {number} [step=1] The value to increment or decrement by.
* @returns {Array} Returns the range of numbers.
* @see _.inRange, _.range
* @example
*
* _.rangeRight(4);
* // => [3, 2, 1, 0]
*
* _.rangeRight(-4);
* // => [-3, -2, -1, 0]
*
* _.rangeRight(1, 5);
* // => [4, 3, 2, 1]
...
```

#### <a name="apidoc.element.lodash.rearg"></a>[function <span class="apidocSignatureSpan">lodash.</span>rearg (func, indexes)](#apidoc.element.lodash.rearg)
- description and source-code
```javascript
rearg = function (func, indexes) {
  return createWrap(func, WRAP_REARG_FLAG, undefined, undefined, undefined, indexes);
}
```
- example usage
```shell
...
 * @since 3.0.0
 * @category Function
 * @param {Function} func The function to rearrange arguments for.
 * @param {...(number|number[])} indexes The arranged argument indexes.
 * @returns {Function} Returns the new function.
 * @example
 *
 * var rearged = _.rearg(function(a, b, c) {
 *   return [a, b, c];
 * }, [2, 0, 1]);
 *
 * rearged('b', 'c', 'a')
 * // => ['a', 'b', 'c']
 */
var rearg = flatRest(function(func, indexes) {
...
```

#### <a name="apidoc.element.lodash.reduce"></a>[function <span class="apidocSignatureSpan">lodash.</span>reduce (collection, iteratee, accumulator)](#apidoc.element.lodash.reduce)
- description and source-code
```javascript
function reduce(collection, iteratee, accumulator) {
  var func = isArray(collection) ? arrayReduce : baseReduce,
      initAccum = arguments.length < 3;

  return func(collection, getIteratee(iteratee, 4), accumulator, initAccum, baseEach);
}
```
- example usage
```shell
...
* function square(n) {
*   return n * n;
* }
*
* var wrapped = _([1, 2, 3]);
*
* // Returns an unwrapped value.
* wrapped.reduce(_.add);
* // => 6
*
* // Returns a wrapped value.
* var squares = wrapped.map(square);
*
* _.isArray(squares);
* // => false
...
```

#### <a name="apidoc.element.lodash.reduceRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>reduceRight (collection, iteratee, accumulator)](#apidoc.element.lodash.reduceRight)
- description and source-code
```javascript
function reduceRight(collection, iteratee, accumulator) {
  var func = isArray(collection) ? arrayReduceRight : baseReduce,
      initAccum = arguments.length < 3;

  return func(collection, getIteratee(iteratee, 4), accumulator, initAccum, baseEachRight);
}
```
- example usage
```shell
...
 * @param {*} [accumulator] The initial value.
 * @returns {*} Returns the accumulated value.
 * @see _.reduce
 * @example
 *
 * var array = [[0, 1], [2, 3], [4, 5]];
 *
 * _.reduceRight(array, function(flattened, other) {
 *   return flattened.concat(other);
 * }, []);
 * // => [4, 5, 2, 3, 0, 1]
 */
function reduceRight(collection, iteratee, accumulator) {
  var func = isArray(collection) ? arrayReduceRight : baseReduce,
      initAccum = arguments.length < 3;
...
```

#### <a name="apidoc.element.lodash.reject"></a>[function <span class="apidocSignatureSpan">lodash.</span>reject (collection, predicate)](#apidoc.element.lodash.reject)
- description and source-code
```javascript
function reject(collection, predicate) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  return func(collection, negate(getIteratee(predicate, 3)));
}
```
- example usage
```shell
...
* @example
*
* var users = [
*   { 'user': 'barney', 'age': 36, 'active': false },
*   { 'user': 'fred',   'age': 40, 'active': true }
* ];
*
* _.reject(users, function(o) { return !o.active; });
* // => objects for ['fred']
*
* // The '_.matches' iteratee shorthand.
* _.reject(users, { 'age': 40, 'active': true });
* // => objects for ['barney']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.remove"></a>[function <span class="apidocSignatureSpan">lodash.</span>remove (array, predicate)](#apidoc.element.lodash.remove)
- description and source-code
```javascript
function remove(array, predicate) {
  var result = [];
  if (!(array && array.length)) {
    return result;
  }
  var index = -1,
      indexes = [],
      length = array.length;

  predicate = getIteratee(predicate, 3);
  while (++index < length) {
    var value = array[index];
    if (predicate(value, index, array)) {
      result.push(value);
      indexes.push(index);
    }
  }
  basePullAt(array, indexes);
  return result;
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to modify.
* @param {Function} [predicate=_.identity] The function invoked per iteration.
* @returns {Array} Returns the new array of removed elements.
* @example
*
* var array = [1, 2, 3, 4];
* var evens = _.remove(array, function(n) {
*   return n % 2 == 0;
* });
*
* console.log(array);
* // => [1, 3]
*
* console.log(evens);
...
```

#### <a name="apidoc.element.lodash.repeat"></a>[function <span class="apidocSignatureSpan">lodash.</span>repeat (string, n, guard)](#apidoc.element.lodash.repeat)
- description and source-code
```javascript
function repeat(string, n, guard) {
  if ((guard ? isIterateeCall(string, n, guard) : n === undefined)) {
    n = 1;
  } else {
    n = toInteger(n);
  }
  return baseRepeat(toString(string), n);
}
```
- example usage
```shell
...
* @category String
* @param {string} [string=''] The string to repeat.
* @param {number} [n=1] The number of times to repeat the string.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {string} Returns the repeated string.
* @example
*
* _.repeat('*', 3);
* // => '***'
*
* _.repeat('abc', 2);
* // => 'abcabc'
*
* _.repeat('abc', 0);
* // => ''
...
```

#### <a name="apidoc.element.lodash.replace"></a>[function <span class="apidocSignatureSpan">lodash.</span>replace ()](#apidoc.element.lodash.replace)
- description and source-code
```javascript
function replace() {
  var args = arguments,
      string = toString(args[0]);

  return args.length < 3 ? string : string.replace(args[1], args[2]);
}
```
- example usage
```shell
...
var objectCtorString = funcToString.call(Object);

/** Used to restore the original '_' reference in '_.noConflict'. */
var oldDash = root._;

/** Used to detect if a method is native. */
var reIsNative = RegExp('^' +
  funcToString.call(hasOwnProperty).replace(reRegExpChar, '\\$&')
  .replace(/hasOwnProperty|(function).*?(?=\\\()| for .+?(?=\\\])/g, '$1.*?') + '$'
);

/** Built-in value references. */
var Buffer = moduleExports ? context.Buffer : undefined,
    Symbol = context.Symbol,
    Uint8Array = context.Uint8Array,
...
```

#### <a name="apidoc.element.lodash.rest"></a>[function <span class="apidocSignatureSpan">lodash.</span>rest (func, start)](#apidoc.element.lodash.rest)
- description and source-code
```javascript
function rest(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = start === undefined ? start : toInteger(start);
  return baseRest(func, start);
}
```
- example usage
```shell
...
* @since 4.0.0
* @category Function
* @param {Function} func The function to apply a rest parameter to.
* @param {number} [start=func.length-1] The start position of the rest parameter.
* @returns {Function} Returns the new function.
* @example
*
* var say = _.rest(function(what, names) {
*   return what + ' ' + _.initial(names).join(', ') +
*     (_.size(names) > 1 ? ', & ' : '') + _.last(names);
* });
*
* say('hello', 'fred', 'barney', 'pebbles');
* // => 'hello fred, barney, & pebbles'
*/
...
```

#### <a name="apidoc.element.lodash.result"></a>[function <span class="apidocSignatureSpan">lodash.</span>result (object, path, defaultValue)](#apidoc.element.lodash.result)
- description and source-code
```javascript
function result(object, path, defaultValue) {
  path = castPath(path, object);

  var index = -1,
      length = path.length;

  // Ensure the loop is entered when path is empty.
  if (!length) {
    length = 1;
    object = undefined;
  }
  while (++index < length) {
    var value = object == null ? undefined : object[toKey(path[index])];
    if (value === undefined) {
      index = length;
      value = defaultValue;
    }
    object = isFunction(value) ? value.call(object) : value;
  }
  return object;
}
```
- example usage
```shell
...
* @param {Array|string} path The path of the property to resolve.
* @param {*} [defaultValue] The value returned for 'undefined' resolved values.
* @returns {*} Returns the resolved value.
* @example
*
* var object = { 'a': [{ 'b': { 'c1': 3, 'c2': _.constant(4) } }] };
*
* _.result(object, 'a[0].b.c1');
* // => 3
*
* _.result(object, 'a[0].b.c2');
* // => 4
*
* _.result(object, 'a[0].b.c3', 'default');
* // => 'default'
...
```

#### <a name="apidoc.element.lodash.reverse"></a>[function <span class="apidocSignatureSpan">lodash.</span>reverse (array)](#apidoc.element.lodash.reverse)
- description and source-code
```javascript
function reverse(array) {
  return array == null ? array : nativeReverse.call(array);
}
```
- example usage
```shell
...
    function createFlow(fromRight) {
      return flatRest(function(funcs) {
var length = funcs.length,
    index = length,
    prereq = LodashWrapper.prototype.thru;

if (fromRight) {
  funcs.reverse();
}
while (index--) {
  var func = funcs[index];
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  if (prereq && !wrapper && getFuncName(func) == 'wrapper') {
...
```

#### <a name="apidoc.element.lodash.round"></a>[function <span class="apidocSignatureSpan">lodash.</span>round (number, precision)](#apidoc.element.lodash.round)
- description and source-code
```javascript
round = function (number, precision) {
  number = toNumber(number);
  precision = precision == null ? 0 : nativeMin(toInteger(precision), 292);
  if (precision) {
    // Shift with exponential notation to avoid floating-point issues.
    // See [MDN](https://mdn.io/round#Examples) for more details.
    var pair = (toString(number) + 'e').split('e'),
        value = func(pair[0] + 'e' + (+pair[1] + precision));

    pair = (toString(value) + 'e').split('e');
    return +(pair[0] + 'e' + (+pair[1] - precision));
  }
  return func(number);
}
```
- example usage
```shell
...
* @since 3.10.0
* @category Math
* @param {number} number The number to round.
* @param {number} [precision=0] The precision to round to.
* @returns {number} Returns the rounded number.
* @example
*
* _.round(4.006);
* // => 4
*
* _.round(4.006, 2);
* // => 4.01
*
* _.round(4060, -2);
* // => 4100
...
```

#### <a name="apidoc.element.lodash.runInContext"></a>[function <span class="apidocSignatureSpan">lodash.</span>runInContext (context)](#apidoc.element.lodash.runInContext)
- description and source-code
```javascript
function runInContext(context) {
  context = context == null ? root : _.defaults(root.Object(), context, _.pick(root, contextProps));

<span class="apidocCodeCommentSpan">  /** Built-in constructor references. */
</span>  var Array = context.Array,
      Date = context.Date,
      Error = context.Error,
      Function = context.Function,
      Math = context.Math,
      Object = context.Object,
      RegExp = context.RegExp,
      String = context.String,
      TypeError = context.TypeError;

  /** Used for built-in method references. */
  var arrayProto = Array.prototype,
      funcProto = Function.prototype,
      objectProto = Object.prototype;

  /** Used to detect overreaching core-js shims. */
  var coreJsData = context['__core-js_shared__'];

  /** Used to resolve the decompiled source of functions. */
  var funcToString = funcProto.toString;

  /** Used to check objects for own properties. */
  var hasOwnProperty = objectProto.hasOwnProperty;

  /** Used to generate unique IDs. */
  var idCounter = 0;

  /** Used to detect methods masquerading as native. */
  var maskSrcKey = (function() {
    var uid = /[^.]+$/.exec(coreJsData && coreJsData.keys && coreJsData.keys.IE_PROTO || '');
    return uid ? ('Symbol(src)_1.' + uid) : '';
  }());

  /**
   * Used to resolve the
   * ['toStringTag'](http://ecma-international.org/ecma-262/7.0/#sec-object.prototype.tostring)
   * of values.
   */
  var nativeObjectToString = objectProto.toString;

  /** Used to infer the 'Object' constructor. */
  var objectCtorString = funcToString.call(Object);

  /** Used to restore the original '_' reference in '_.noConflict'. */
  var oldDash = root._;

  /** Used to detect if a method is native. */
  var reIsNative = RegExp('^' +
    funcToString.call(hasOwnProperty).replace(reRegExpChar, '\\$&')
    .replace(/hasOwnProperty|(function).*?(?=\\\()| for .+?(?=\\\])/g, '$1.*?') + '$'
  );

  /** Built-in value references. */
  var Buffer = moduleExports ? context.Buffer : undefined,
      Symbol = context.Symbol,
      Uint8Array = context.Uint8Array,
      allocUnsafe = Buffer ? Buffer.allocUnsafe : undefined,
      getPrototype = overArg(Object.getPrototypeOf, Object),
      objectCreate = Object.create,
      propertyIsEnumerable = objectProto.propertyIsEnumerable,
      splice = arrayProto.splice,
      spreadableSymbol = Symbol ? Symbol.isConcatSpreadable : undefined,
      symIterator = Symbol ? Symbol.iterator : undefined,
      symToStringTag = Symbol ? Symbol.toStringTag : undefined;

  var defineProperty = (function() {
    try {
      var func = getNative(Object, 'defineProperty');
      func({}, '', {});
      return func;
    } catch (e) {}
  }());

  /** Mocked built-ins. */
  var ctxClearTimeout = context.clearTimeout !== root.clearTimeout && context.clearTimeout,
      ctxNow = Date && Date.now !== root.Date.now && Date.now,
      ctxSetTimeout = context.setTimeout !== root.setTimeout && context.setTimeout;

  /* Built-in method references for those with the same name as other 'lodash' methods. */
  var nativeCeil = Math.ceil,
      nativeFloor = Math.floor,
      nativeGetSymbols = Object.getOwnPropertySymbols,
      nativeIsBuffer = Buffer ? Buffer.isBuffer : undefined,
      nativeIsFinite = context.isFinite,
      nativeJoin = arrayProto.join,
      nativeKeys = overArg(Object.keys, Object),
      nativeMax = Math.max,
      nativeMin = Math.min,
      nativeNow = Date.now,
      nativeParseInt = context.parseInt,
      nativeRandom = Math.random,
      nativeReverse = arrayProto.reverse;

  /* Built-in method references that are verified to be native. */
  var DataView = getNative(context, 'DataView'),
      Map = getNative(context, 'Map'),
      Promise = getNative(context, 'Promise'),
      Set = getNative(context, 'Set'),
      WeakMap = getNative(context, 'WeakMap'),
      nativeCreate = getNative(Object, 'create');

  /** Used to store function metadata. */
  var metaMap = WeakMap && new WeakMap;

  /** Used to lookup unminified function names. */
  var realNames = {};

  /** Used to detect maps, sets, and weakmaps. */
  var dataViewCtorString = toSource(D ...
```
- example usage
```shell
...
* @category Util
* @param {Object} [context=root] The context object.
* @returns {Function} Returns a new 'lodash' function.
* @example
*
* _.mixin({ 'foo': _.constant('foo') });
*
* var lodash = _.runInContext();
* lodash.mixin({ 'bar': lodash.constant('bar') });
*
* _.isFunction(_.foo);
* // => true
* _.isFunction(_.bar);
* // => false
*
...
```

#### <a name="apidoc.element.lodash.sample"></a>[function <span class="apidocSignatureSpan">lodash.</span>sample (collection)](#apidoc.element.lodash.sample)
- description and source-code
```javascript
function sample(collection) {
  var func = isArray(collection) ? arraySample : baseSample;
  return func(collection);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 2.0.0
 * @category Collection
 * @param {Array|Object} collection The collection to sample.
 * @returns {*} Returns the random element.
 * @example
 *
 * _.sample([1, 2, 3, 4]);
 * // => 2
 */
function sample(collection) {
  var func = isArray(collection) ? arraySample : baseSample;
  return func(collection);
}
...
```

#### <a name="apidoc.element.lodash.sampleSize"></a>[function <span class="apidocSignatureSpan">lodash.</span>sampleSize (collection, n, guard)](#apidoc.element.lodash.sampleSize)
- description and source-code
```javascript
function sampleSize(collection, n, guard) {
  if ((guard ? isIterateeCall(collection, n, guard) : n === undefined)) {
    n = 1;
  } else {
    n = toInteger(n);
  }
  var func = isArray(collection) ? arraySampleSize : baseSampleSize;
  return func(collection, n);
}
```
- example usage
```shell
...
 * @category Collection
 * @param {Array|Object} collection The collection to sample.
 * @param {number} [n=1] The number of elements to sample.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {Array} Returns the random elements.
 * @example
 *
 * _.sampleSize([1, 2, 3], 2);
 * // => [3, 1]
 *
 * _.sampleSize([1, 2, 3], 4);
 * // => [2, 3, 1]
 */
function sampleSize(collection, n, guard) {
  if ((guard ? isIterateeCall(collection, n, guard) : n === undefined)) {
...
```

#### <a name="apidoc.element.lodash.set"></a>[function <span class="apidocSignatureSpan">lodash.</span>set (object, path, value)](#apidoc.element.lodash.set)
- description and source-code
```javascript
function set(object, path, value) {
  return object == null ? object : baseSet(object, path, value);
}
```
- example usage
```shell
...
 * @private
 * @param {Object} map The map to modify.
 * @param {Array} pair The key-value pair to add.
 * @returns {Object} Returns 'map'.
 */
function addMapEntry(map, pair) {
  // Don't return 'map.set' because it's not chainable in IE 11.
  map.set(pair[0], pair[1]);
  return map;
}

/**
 * Adds 'value' to 'set'.
 *
 * @private
...
```

#### <a name="apidoc.element.lodash.setWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>setWith (object, path, value, customizer)](#apidoc.element.lodash.setWith)
- description and source-code
```javascript
function setWith(object, path, value, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return object == null ? object : baseSet(object, path, value, customizer);
}
```
- example usage
```shell
...
 * @param {*} value The value to set.
 * @param {Function} [customizer] The function to customize assigned values.
 * @returns {Object} Returns 'object'.
 * @example
 *
 * var object = {};
 *
 * _.setWith(object, '[0][1]', 'a', Object);
 * // => { '0': { '1': 'a' } }
 */
function setWith(object, path, value, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return object == null ? object : baseSet(object, path, value, customizer);
}
...
```

#### <a name="apidoc.element.lodash.shuffle"></a>[function <span class="apidocSignatureSpan">lodash.</span>shuffle (collection)](#apidoc.element.lodash.shuffle)
- description and source-code
```javascript
function shuffle(collection) {
  var func = isArray(collection) ? arrayShuffle : baseShuffle;
  return func(collection);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Collection
 * @param {Array|Object} collection The collection to shuffle.
 * @returns {Array} Returns the new shuffled array.
 * @example
 *
 * _.shuffle([1, 2, 3, 4]);
 * // => [4, 1, 3, 2]
 */
function shuffle(collection) {
  var func = isArray(collection) ? arrayShuffle : baseShuffle;
  return func(collection);
}
...
```

#### <a name="apidoc.element.lodash.size"></a>[function <span class="apidocSignatureSpan">lodash.</span>size (collection)](#apidoc.element.lodash.size)
- description and source-code
```javascript
function size(collection) {
  if (collection == null) {
    return 0;
  }
  if (isArrayLike(collection)) {
    return isString(collection) ? stringSize(collection) : collection.length;
  }
  var tag = getTag(collection);
  if (tag == mapTag || tag == setTag) {
    return collection.size;
  }
  return baseKeys(collection).length;
}
```
- example usage
```shell
...
* @memberOf _
* @since 0.1.0
* @category Collection
* @param {Array|Object|string} collection The collection to inspect.
* @returns {number} Returns the collection size.
* @example
*
* _.size([1, 2, 3]);
* // => 3
*
* _.size({ 'a': 1, 'b': 2 });
* // => 2
*
* _.size('pebbles');
* // => 7
...
```

#### <a name="apidoc.element.lodash.slice"></a>[function <span class="apidocSignatureSpan">lodash.</span>slice (array, start, end)](#apidoc.element.lodash.slice)
- description and source-code
```javascript
function slice(array, start, end) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  if (end && typeof end != 'number' && isIterateeCall(array, start, end)) {
    start = 0;
    end = length;
  }
  else {
    start = start == null ? 0 : toInteger(start);
    end = end === undefined ? length : toInteger(end);
  }
  return baseSlice(array, start, end);
}
```
- example usage
```shell
...
 * @private
 * @param {Buffer} buffer The buffer to clone.
 * @param {boolean} [isDeep] Specify a deep clone.
 * @returns {Buffer} Returns the cloned buffer.
 */
function cloneBuffer(buffer, isDeep) {
  if (isDeep) {
    return buffer.slice();
  }
  var length = buffer.length,
      result = allocUnsafe ? allocUnsafe(length) : new buffer.constructor(length);

  buffer.copy(result);
  return result;
}
...
```

#### <a name="apidoc.element.lodash.snakeCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>snakeCase (string)](#apidoc.element.lodash.snakeCase)
- description and source-code
```javascript
snakeCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 3.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the snake cased string.
* @example
*
* _.snakeCase('Foo Bar');
* // => 'foo_bar'
*
* _.snakeCase('fooBar');
* // => 'foo_bar'
*
* _.snakeCase('--FOO-BAR--');
* // => 'foo_bar'
...
```

#### <a name="apidoc.element.lodash.some"></a>[function <span class="apidocSignatureSpan">lodash.</span>some (collection, predicate, guard)](#apidoc.element.lodash.some)
- description and source-code
```javascript
function some(collection, predicate, guard) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (guard && isIterateeCall(collection, predicate, guard)) {
    predicate = undefined;
  }
  return func(collection, getIteratee(predicate, 3));
}
```
- example usage
```shell
...
* @param {Array|Object} collection The collection to iterate over.
* @param {Function} [predicate=_.identity] The function invoked per iteration.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {boolean} Returns 'true' if any element passes the predicate check,
*  else 'false'.
* @example
*
* _.some([null, 0, 'yes', false], Boolean);
* // => true
*
* var users = [
*   { 'user': 'barney', 'active': true },
*   { 'user': 'fred',   'active': false }
* ];
*
...
```

#### <a name="apidoc.element.lodash.sortBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortBy (collection, iteratees)](#apidoc.element.lodash.sortBy)
- description and source-code
```javascript
sortBy = function (collection, iteratees) {
  if (collection == null) {
    return [];
  }
  var length = iteratees.length;
  if (length > 1 && isIterateeCall(collection, iteratees[0], iteratees[1])) {
    iteratees = [];
  } else if (length > 2 && isIterateeCall(iteratees[0], iteratees[1], iteratees[2])) {
    iteratees = [iteratees[0]];
  }
  return baseOrderBy(collection, baseFlatten(iteratees, 1), []);
}
```
- example usage
```shell
...
*   { 'user': 'barney',  'age': 36 },
*   { 'user': 'fred',    'age': 40 },
*   { 'user': 'pebbles', 'age': 1 }
* ];
*
* var youngest = _
*   .chain(users)
*   .sortBy('age')
*   .map(function(o) {
*     return o.user + ' is ' + o.age;
*   })
*   .head()
*   .value();
* // => 'pebbles is 1'
*/
...
```

#### <a name="apidoc.element.lodash.sortedIndex"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedIndex (array, value)](#apidoc.element.lodash.sortedIndex)
- description and source-code
```javascript
function sortedIndex(array, value) {
  return baseSortedIndex(array, value);
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The sorted array to inspect.
 * @param {*} value The value to evaluate.
 * @returns {number} Returns the index at which 'value' should be inserted
 *  into 'array'.
 * @example
 *
 * _.sortedIndex([30, 50], 40);
 * // => 1
 */
function sortedIndex(array, value) {
  return baseSortedIndex(array, value);
}

/**
...
```

#### <a name="apidoc.element.lodash.sortedIndexBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedIndexBy (array, value, iteratee)](#apidoc.element.lodash.sortedIndexBy)
- description and source-code
```javascript
function sortedIndexBy(array, value, iteratee) {
  return baseSortedIndexBy(array, value, getIteratee(iteratee, 2));
}
```
- example usage
```shell
...
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {number} Returns the index at which 'value' should be inserted
 *  into 'array'.
 * @example
 *
 * var objects = [{ 'x': 4 }, { 'x': 5 }];
 *
 * _.sortedIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
 * // => 0
 *
 * // The '_.property' iteratee shorthand.
 * _.sortedIndexBy(objects, { 'x': 4 }, 'x');
 * // => 0
 */
function sortedIndexBy(array, value, iteratee) {
...
```

#### <a name="apidoc.element.lodash.sortedIndexOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedIndexOf (array, value)](#apidoc.element.lodash.sortedIndexOf)
- description and source-code
```javascript
function sortedIndexOf(array, value) {
  var length = array == null ? 0 : array.length;
  if (length) {
    var index = baseSortedIndex(array, value);
    if (index < length && eq(array[index], value)) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {*} value The value to search for.
 * @returns {number} Returns the index of the matched value, else '-1'.
 * @example
 *
 * _.sortedIndexOf([4, 5, 5, 5, 6], 5);
 * // => 1
 */
function sortedIndexOf(array, value) {
  var length = array == null ? 0 : array.length;
  if (length) {
    var index = baseSortedIndex(array, value);
    if (index < length && eq(array[index], value)) {
...
```

#### <a name="apidoc.element.lodash.sortedLastIndex"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndex (array, value)](#apidoc.element.lodash.sortedLastIndex)
- description and source-code
```javascript
function sortedLastIndex(array, value) {
  return baseSortedIndex(array, value, true);
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The sorted array to inspect.
 * @param {*} value The value to evaluate.
 * @returns {number} Returns the index at which 'value' should be inserted
 *  into 'array'.
 * @example
 *
 * _.sortedLastIndex([4, 5, 5, 5, 6], 5);
 * // => 4
 */
function sortedLastIndex(array, value) {
  return baseSortedIndex(array, value, true);
}

/**
...
```

#### <a name="apidoc.element.lodash.sortedLastIndexBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndexBy (array, value, iteratee)](#apidoc.element.lodash.sortedLastIndexBy)
- description and source-code
```javascript
function sortedLastIndexBy(array, value, iteratee) {
  return baseSortedIndexBy(array, value, getIteratee(iteratee, 2), true);
}
```
- example usage
```shell
...
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {number} Returns the index at which 'value' should be inserted
 *  into 'array'.
 * @example
 *
 * var objects = [{ 'x': 4 }, { 'x': 5 }];
 *
 * _.sortedLastIndexBy(objects, { 'x': 4 }, function(o) { return o.x; });
 * // => 1
 *
 * // The '_.property' iteratee shorthand.
 * _.sortedLastIndexBy(objects, { 'x': 4 }, 'x');
 * // => 1
 */
function sortedLastIndexBy(array, value, iteratee) {
...
```

#### <a name="apidoc.element.lodash.sortedLastIndexOf"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedLastIndexOf (array, value)](#apidoc.element.lodash.sortedLastIndexOf)
- description and source-code
```javascript
function sortedLastIndexOf(array, value) {
  var length = array == null ? 0 : array.length;
  if (length) {
    var index = baseSortedIndex(array, value, true) - 1;
    if (eq(array[index], value)) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {*} value The value to search for.
 * @returns {number} Returns the index of the matched value, else '-1'.
 * @example
 *
 * _.sortedLastIndexOf([4, 5, 5, 5, 6], 5);
 * // => 3
 */
function sortedLastIndexOf(array, value) {
  var length = array == null ? 0 : array.length;
  if (length) {
    var index = baseSortedIndex(array, value, true) - 1;
    if (eq(array[index], value)) {
...
```

#### <a name="apidoc.element.lodash.sortedUniq"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedUniq (array)](#apidoc.element.lodash.sortedUniq)
- description and source-code
```javascript
function sortedUniq(array) {
  return (array && array.length)
    ? baseSortedUniq(array)
    : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @returns {Array} Returns the new duplicate free array.
 * @example
 *
 * _.sortedUniq([1, 1, 2]);
 * // => [1, 2]
 */
function sortedUniq(array) {
  return (array && array.length)
    ? baseSortedUniq(array)
    : [];
}
...
```

#### <a name="apidoc.element.lodash.sortedUniqBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>sortedUniqBy (array, iteratee)](#apidoc.element.lodash.sortedUniqBy)
- description and source-code
```javascript
function sortedUniqBy(array, iteratee) {
  return (array && array.length)
    ? baseSortedUniq(array, getIteratee(iteratee, 2))
    : [];
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {Function} [iteratee] The iteratee invoked per element.
 * @returns {Array} Returns the new duplicate free array.
 * @example
 *
 * _.sortedUniqBy([1.1, 1.2, 2.3, 2.4], Math.floor);
 * // => [1.1, 2.3]
 */
function sortedUniqBy(array, iteratee) {
  return (array && array.length)
    ? baseSortedUniq(array, getIteratee(iteratee, 2))
    : [];
}
...
```

#### <a name="apidoc.element.lodash.split"></a>[function <span class="apidocSignatureSpan">lodash.</span>split (string, separator, limit)](#apidoc.element.lodash.split)
- description and source-code
```javascript
function split(string, separator, limit) {
  if (limit && typeof limit != 'number' && isIterateeCall(string, separator, limit)) {
    separator = limit = undefined;
  }
  limit = limit === undefined ? MAX_ARRAY_LENGTH : limit >>> 0;
  if (!limit) {
    return [];
  }
  string = toString(string);
  if (string && (
        typeof separator == 'string' ||
        (separator != null && !isRegExp(separator))
      )) {
    separator = baseToString(separator);
    if (!separator && hasUnicode(string)) {
      return castSlice(stringToArray(string), 0, limit);
    }
  }
  return string.split(separator, limit);
}
```
- example usage
```shell
...
 * Converts an ASCII 'string' to an array.
 *
 * @private
 * @param {string} string The string to convert.
 * @returns {Array} Returns the converted array.
 */
function asciiToArray(string) {
  return string.split('');
}

/**
 * Splits an ASCII 'string' into an array of its words.
 *
 * @private
 * @param {string} The string to inspect.
...
```

#### <a name="apidoc.element.lodash.spread"></a>[function <span class="apidocSignatureSpan">lodash.</span>spread (func, start)](#apidoc.element.lodash.spread)
- description and source-code
```javascript
function spread(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = start == null ? 0 : nativeMax(toInteger(start), 0);
  return baseRest(function(args) {
    var array = args[start],
        otherArgs = castSlice(args, 0, start);

    if (array) {
      arrayPush(otherArgs, array);
    }
    return apply(func, this, otherArgs);
  });
}
```
- example usage
```shell
...
* @since 3.2.0
* @category Function
* @param {Function} func The function to spread arguments over.
* @param {number} [start=0] The start position of the spread.
* @returns {Function} Returns the new function.
* @example
*
* var say = _.spread(function(who, what) {
*   return who + ' says ' + what;
* });
*
* say(['fred', 'hello']);
* // => 'fred says hello'
*
* var numbers = Promise.all([
...
```

#### <a name="apidoc.element.lodash.startCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>startCase (string)](#apidoc.element.lodash.startCase)
- description and source-code
```javascript
startCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 3.1.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the start cased string.
* @example
*
* _.startCase('--foo-bar--');
* // => 'Foo Bar'
*
* _.startCase('fooBar');
* // => 'Foo Bar'
*
* _.startCase('__FOO_BAR__');
* // => 'FOO BAR'
...
```

#### <a name="apidoc.element.lodash.startsWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>startsWith (string, target, position)](#apidoc.element.lodash.startsWith)
- description and source-code
```javascript
function startsWith(string, target, position) {
  string = toString(string);
  position = position == null
    ? 0
    : baseClamp(toInteger(position), 0, string.length);

  target = baseToString(target);
  return string.slice(position, position + target.length) == target;
}
```
- example usage
```shell
...
* @param {string} [string=''] The string to inspect.
* @param {string} [target] The string to search for.
* @param {number} [position=0] The position to search from.
* @returns {boolean} Returns 'true' if 'string' starts with 'target',
*  else 'false'.
* @example
*
* _.startsWith('abc', 'a');
* // => true
*
* _.startsWith('abc', 'b');
* // => false
*
* _.startsWith('abc', 'b', 1);
* // => true
...
```

#### <a name="apidoc.element.lodash.stubArray"></a>[function <span class="apidocSignatureSpan">lodash.</span>stubArray ()](#apidoc.element.lodash.stubArray)
- description and source-code
```javascript
function stubArray() {
  return [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.stubFalse"></a>[function <span class="apidocSignatureSpan">lodash.</span>stubFalse ()](#apidoc.element.lodash.stubFalse)
- description and source-code
```javascript
function stubFalse() {
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.stubObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>stubObject ()](#apidoc.element.lodash.stubObject)
- description and source-code
```javascript
function stubObject() {
  return {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.stubString"></a>[function <span class="apidocSignatureSpan">lodash.</span>stubString ()](#apidoc.element.lodash.stubString)
- description and source-code
```javascript
function stubString() {
  return '';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.stubTrue"></a>[function <span class="apidocSignatureSpan">lodash.</span>stubTrue ()](#apidoc.element.lodash.stubTrue)
- description and source-code
```javascript
function stubTrue() {
  return true;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.subtract"></a>[function <span class="apidocSignatureSpan">lodash.</span>subtract (value, other)](#apidoc.element.lodash.subtract)
- description and source-code
```javascript
subtract = function (value, other) {
  var result;
  if (value === undefined && other === undefined) {
    return defaultValue;
  }
  if (value !== undefined) {
    result = value;
  }
  if (other !== undefined) {
    if (result === undefined) {
      return other;
    }
    if (typeof value == 'string' || typeof other == 'string') {
      value = baseToString(value);
      other = baseToString(other);
    } else {
      value = baseToNumber(value);
      other = baseToNumber(other);
    }
    result = operator(value, other);
  }
  return result;
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Math
 * @param {number} minuend The first number in a subtraction.
 * @param {number} subtrahend The second number in a subtraction.
 * @returns {number} Returns the difference.
 * @example
 *
 * _.subtract(6, 4);
 * // => 2
 */
var subtract = createMathOperation(function(minuend, subtrahend) {
  return minuend - subtrahend;
}, 0);

/**
...
```

#### <a name="apidoc.element.lodash.sum"></a>[function <span class="apidocSignatureSpan">lodash.</span>sum (array)](#apidoc.element.lodash.sum)
- description and source-code
```javascript
function sum(array) {
  return (array && array.length)
    ? baseSum(array, identity)
    : 0;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 3.4.0
 * @category Math
 * @param {Array} array The array to iterate over.
 * @returns {number} Returns the sum.
 * @example
 *
 * _.sum([4, 2, 8, 6]);
 * // => 20
 */
function sum(array) {
  return (array && array.length)
    ? baseSum(array, identity)
    : 0;
}
...
```

#### <a name="apidoc.element.lodash.sumBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>sumBy (array, iteratee)](#apidoc.element.lodash.sumBy)
- description and source-code
```javascript
function sumBy(array, iteratee) {
  return (array && array.length)
    ? baseSum(array, getIteratee(iteratee, 2))
    : 0;
}
```
- example usage
```shell
...
 * @param {Array} array The array to iterate over.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {number} Returns the sum.
 * @example
 *
 * var objects = [{ 'n': 4 }, { 'n': 2 }, { 'n': 8 }, { 'n': 6 }];
 *
 * _.sumBy(objects, function(o) { return o.n; });
 * // => 20
 *
 * // The '_.property' iteratee shorthand.
 * _.sumBy(objects, 'n');
 * // => 20
 */
function sumBy(array, iteratee) {
...
```

#### <a name="apidoc.element.lodash.tail"></a>[function <span class="apidocSignatureSpan">lodash.</span>tail (array)](#apidoc.element.lodash.tail)
- description and source-code
```javascript
function tail(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseSlice(array, 1, length) : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to query.
 * @returns {Array} Returns the slice of 'array'.
 * @example
 *
 * _.tail([1, 2, 3]);
 * // => [2, 3]
 */
function tail(array) {
  var length = array == null ? 0 : array.length;
  return length ? baseSlice(array, 1, length) : [];
}
...
```

#### <a name="apidoc.element.lodash.take"></a>[function <span class="apidocSignatureSpan">lodash.</span>take (array, n, guard)](#apidoc.element.lodash.take)
- description and source-code
```javascript
function take(array, n, guard) {
  if (!(array && array.length)) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to query.
* @param {number} [n=1] The number of elements to take.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {Array} Returns the slice of 'array'.
* @example
*
* _.take([1, 2, 3]);
* // => [1]
*
* _.take([1, 2, 3], 2);
* // => [1, 2]
*
* _.take([1, 2, 3], 5);
* // => [1, 2, 3]
...
```

#### <a name="apidoc.element.lodash.takeRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>takeRight (array, n, guard)](#apidoc.element.lodash.takeRight)
- description and source-code
```javascript
function takeRight(array, n, guard) {
  var length = array == null ? 0 : array.length;
  if (!length) {
    return [];
  }
  n = (guard || n === undefined) ? 1 : toInteger(n);
  n = length - n;
  return baseSlice(array, n < 0 ? 0 : n, length);
}
```
- example usage
```shell
...
* @category Array
* @param {Array} array The array to query.
* @param {number} [n=1] The number of elements to take.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {Array} Returns the slice of 'array'.
* @example
*
* _.takeRight([1, 2, 3]);
* // => [3]
*
* _.takeRight([1, 2, 3], 2);
* // => [2, 3]
*
* _.takeRight([1, 2, 3], 5);
* // => [1, 2, 3]
...
```

#### <a name="apidoc.element.lodash.takeRightWhile"></a>[function <span class="apidocSignatureSpan">lodash.</span>takeRightWhile (array, predicate)](#apidoc.element.lodash.takeRightWhile)
- description and source-code
```javascript
function takeRightWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3), false, true)
    : [];
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': true },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': false }
* ];
*
* _.takeRightWhile(users, function(o) { return !o.active; });
* // => objects for ['fred', 'pebbles']
*
* // The '_.matches' iteratee shorthand.
* _.takeRightWhile(users, { 'user': 'pebbles', 'active': false });
* // => objects for ['pebbles']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.takeWhile"></a>[function <span class="apidocSignatureSpan">lodash.</span>takeWhile (array, predicate)](#apidoc.element.lodash.takeWhile)
- description and source-code
```javascript
function takeWhile(array, predicate) {
  return (array && array.length)
    ? baseWhile(array, getIteratee(predicate, 3))
    : [];
}
```
- example usage
```shell
...
*
* var users = [
*   { 'user': 'barney',  'active': false },
*   { 'user': 'fred',    'active': false },
*   { 'user': 'pebbles', 'active': true }
* ];
*
* _.takeWhile(users, function(o) { return !o.active; });
* // => objects for ['barney', 'fred']
*
* // The '_.matches' iteratee shorthand.
* _.takeWhile(users, { 'user': 'barney', 'active': false });
* // => objects for ['barney']
*
* // The '_.matchesProperty' iteratee shorthand.
...
```

#### <a name="apidoc.element.lodash.tap"></a>[function <span class="apidocSignatureSpan">lodash.</span>tap (value, interceptor)](#apidoc.element.lodash.tap)
- description and source-code
```javascript
function tap(value, interceptor) {
  interceptor(value);
  return value;
}
```
- example usage
```shell
...
* @category Seq
* @param {*} value The value to provide to 'interceptor'.
* @param {Function} interceptor The function to invoke.
* @returns {*} Returns 'value'.
* @example
*
* _([1, 2, 3])
*  .tap(function(array) {
*    // Mutate input array.
*    array.pop();
*  })
*  .reverse()
*  .value();
* // => [2, 1]
*/
...
```

#### <a name="apidoc.element.lodash.template"></a>[function <span class="apidocSignatureSpan">lodash.</span>template (string, options, guard)](#apidoc.element.lodash.template)
- description and source-code
```javascript
function template(string, options, guard) {
  // Based on John Resig's 'tmpl' implementation
  // (http://ejohn.org/blog/javascript-micro-templating/)
  // and Laura Doktorova's doT.js (https://github.com/olado/doT).
  var settings = lodash.templateSettings;

  if (guard && isIterateeCall(string, options, guard)) {
    options = undefined;
  }
  string = toString(string);
  options = assignInWith({}, options, settings, customDefaultsAssignIn);

  var imports = assignInWith({}, options.imports, settings.imports, customDefaultsAssignIn),
      importsKeys = keys(imports),
      importsValues = baseValues(imports, importsKeys);

  var isEscaping,
      isEvaluating,
      index = 0,
      interpolate = options.interpolate || reNoMatch,
      source = "__p += '";

  // Compile the regexp to match each delimiter.
  var reDelimiters = RegExp(
    (options.escape || reNoMatch).source + '|' +
    interpolate.source + '|' +
    (interpolate === reInterpolate ? reEsTemplate : reNoMatch).source + '|' +
    (options.evaluate || reNoMatch).source + '|$'
  , 'g');

  // Use a sourceURL for easier debugging.
  var sourceURL = '//# sourceURL=' +
    ('sourceURL' in options
      ? options.sourceURL
      : ('lodash.templateSources[' + (++templateCounter) + ']')
    ) + '\n';

  string.replace(reDelimiters, function(match, escapeValue, interpolateValue, esTemplateValue, evaluateValue, offset) {
    interpolateValue || (interpolateValue = esTemplateValue);

    // Escape characters that can't be included in string literals.
    source += string.slice(index, offset).replace(reUnescapedString, escapeStringChar);

    // Replace delimiters with snippets.
    if (escapeValue) {
      isEscaping = true;
      source += "' +\n__e(" + escapeValue + ") +\n'";
    }
    if (evaluateValue) {
      isEvaluating = true;
      source += "';\n" + evaluateValue + ";\n__p += '";
    }
    if (interpolateValue) {
      source += "' +\n((__t = (" + interpolateValue + ")) == null ? '' : __t) +\n'";
    }
    index = offset + match.length;

    // The JS engine embedded in Adobe products needs 'match' returned in
    // order to produce the correct 'offset' value.
    return match;
  });

  source += "';\n";

  // If 'variable' is not specified wrap a with-statement around the generated
  // code to add the data object to the top of the scope chain.
  var variable = options.variable;
  if (!variable) {
    source = 'with (obj) {\n' + source + '\n}\n';
  }
  // Cleanup code by stripping empty strings.
  source = (isEvaluating ? source.replace(reEmptyStringLeading, '') : source)
    .replace(reEmptyStringMiddle, '$1')
    .replace(reEmptyStringTrailing, '$1;');

  // Frame code as the function body.
  source = 'function(' + (variable || 'obj') + ') {\n' +
    (variable
      ? ''
      : 'obj || (obj = {});\n'
    ) +
    "var __t, __p = ''" +
    (isEscaping
       ? ', __e = _.escape'
       : ''
    ) +
    (isEvaluating
      ? ', __j = Array.prototype.join;\n' +
        "function print() { __p += __j.call(arguments, '') }\n"
      : ';\n'
    ) +
    source +
    'return __p\n}';

  var result = attempt(function() {
    return Function(importsKeys, sourceURL + 'return ' + source)
      .apply(undefined, importsValues);
  });

  // Provide the compiled function's source by its 'toString' method or
  // the 'source' property as a convenience for inlining compiled templates.
  result.source = source;
  if (isError(result)) {
    throw result;
  }
  return result;
}
```
- example usage
```shell
...
* @param {string} [options.variable='obj']
*  The data object variable name.
* @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
* @returns {Function} Returns the compiled template function.
* @example
*
* // Use the "interpolate" delimiter to create a compiled template.
* var compiled = _.template('hello <%= user %>!');
* compiled({ 'user': 'fred' });
* // => 'hello fred!'
*
* // Use the HTML "escape" delimiter to escape data property values.
* var compiled = _.template('<b><%- value %></b>');
* compiled({ 'value': '<script>' });
* // => '<b>&lt;script&gt;</b>'
...
```

#### <a name="apidoc.element.lodash.throttle"></a>[function <span class="apidocSignatureSpan">lodash.</span>throttle (func, wait, options)](#apidoc.element.lodash.throttle)
- description and source-code
```javascript
function throttle(func, wait, options) {
  var leading = true,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  if (isObject(options)) {
    leading = 'leading' in options ? !!options.leading : leading;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }
  return debounce(func, wait, {
    'leading': leading,
    'maxWait': wait,
    'trailing': trailing
  });
}
```
- example usage
```shell
...
*  Specify invoking on the leading edge of the timeout.
* @param {boolean} [options.trailing=true]
*  Specify invoking on the trailing edge of the timeout.
* @returns {Function} Returns the new throttled function.
* @example
*
* // Avoid excessively updating the position while scrolling.
* jQuery(window).on('scroll', _.throttle(updatePosition, 100));
*
* // Invoke 'renewToken' when the click event is fired, but not more than once every 5 minutes.
* var throttled = _.throttle(renewToken, 300000, { 'trailing': false });
* jQuery(element).on('click', throttled);
*
* // Cancel the trailing throttled invocation.
* jQuery(window).on('popstate', throttled.cancel);
...
```

#### <a name="apidoc.element.lodash.thru"></a>[function <span class="apidocSignatureSpan">lodash.</span>thru (value, interceptor)](#apidoc.element.lodash.thru)
- description and source-code
```javascript
function thru(value, interceptor) {
  return interceptor(value);
}
```
- example usage
```shell
...
      data[1] == (WRAP_ARY_FLAG | WRAP_CURRY_FLAG | WRAP_PARTIAL_FLAG | WRAP_REARG_FLAG) &&
      !data[4].length && data[9] == 1
    ) {
  wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
} else {
  wrapper = (func.length == 1 && isLaziable(func))
    ? wrapper[funcName]()
    : wrapper.thru(func);
}
        }
        return function() {
var args = arguments,
    value = args[0];

if (wrapper && args.length == 1 && isArray(value)) {
...
```

#### <a name="apidoc.element.lodash.times"></a>[function <span class="apidocSignatureSpan">lodash.</span>times (n, iteratee)](#apidoc.element.lodash.times)
- description and source-code
```javascript
function times(n, iteratee) {
  n = toInteger(n);
  if (n < 1 || n > MAX_SAFE_INTEGER) {
    return [];
  }
  var index = MAX_ARRAY_LENGTH,
      length = nativeMin(n, MAX_ARRAY_LENGTH);

  iteratee = getIteratee(iteratee);
  n -= MAX_ARRAY_LENGTH;

  var result = baseTimes(length, iteratee);
  while (++index < n) {
    iteratee(index);
  }
  return result;
}
```
- example usage
```shell
...
* @memberOf _
* @since 2.4.0
* @category Util
* @param {*} value The value to return from the new function.
* @returns {Function} Returns the new constant function.
* @example
*
* var objects = _.times(2, _.constant({ 'a': 1 }));
*
* console.log(objects);
* // => [{ 'a': 1 }, { 'a': 1 }]
*
* console.log(objects[0] === objects[1]);
* // => true
*/
...
```

#### <a name="apidoc.element.lodash.toArray"></a>[function <span class="apidocSignatureSpan">lodash.</span>toArray (value)](#apidoc.element.lodash.toArray)
- description and source-code
```javascript
function toArray(value) {
  if (!value) {
    return [];
  }
  if (isArrayLike(value)) {
    return isString(value) ? stringToArray(value) : copyArray(value);
  }
  if (symIterator && value[symIterator]) {
    return iteratorToArray(value[symIterator]());
  }
  var tag = getTag(value),
      func = tag == mapTag ? mapToArray : (tag == setTag ? setToArray : values);

  return func(value);
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Function
 * @param {Function} func The function to flip arguments for.
 * @returns {Function} Returns the new flipped function.
 * @example
 *
 * var flipped = _.flip(function() {
 *   return _.toArray(arguments);
 * });
 *
 * flipped('a', 'b', 'c', 'd');
 * // => ['d', 'c', 'b', 'a']
 */
function flip(func) {
  return createWrap(func, WRAP_FLIP_FLAG);
...
```

#### <a name="apidoc.element.lodash.toFinite"></a>[function <span class="apidocSignatureSpan">lodash.</span>toFinite (value)](#apidoc.element.lodash.toFinite)
- description and source-code
```javascript
function toFinite(value) {
  if (!value) {
    return value === 0 ? value : 0;
  }
  value = toNumber(value);
  if (value === INFINITY || value === -INFINITY) {
    var sign = (value < 0 ? -1 : 1);
    return sign * MAX_INTEGER;
  }
  return value === value ? value : 0;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.12.0
* @category Lang
* @param {*} value The value to convert.
* @returns {number} Returns the converted number.
* @example
*
* _.toFinite(3.2);
* // => 3.2
*
* _.toFinite(Number.MIN_VALUE);
* // => 5e-324
*
* _.toFinite(Infinity);
* // => 1.7976931348623157e+308
...
```

#### <a name="apidoc.element.lodash.toInteger"></a>[function <span class="apidocSignatureSpan">lodash.</span>toInteger (value)](#apidoc.element.lodash.toInteger)
- description and source-code
```javascript
function toInteger(value) {
  var result = toFinite(value),
      remainder = result % 1;

  return result === result ? (remainder ? result - remainder : result) : 0;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to convert.
* @returns {number} Returns the converted integer.
* @example
*
* _.toInteger(3.2);
* // => 3
*
* _.toInteger(Number.MIN_VALUE);
* // => 0
*
* _.toInteger(Infinity);
* // => 1.7976931348623157e+308
...
```

#### <a name="apidoc.element.lodash.toLength"></a>[function <span class="apidocSignatureSpan">lodash.</span>toLength (value)](#apidoc.element.lodash.toLength)
- description and source-code
```javascript
function toLength(value) {
  return value ? baseClamp(toInteger(value), 0, MAX_ARRAY_LENGTH) : 0;
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to convert.
* @returns {number} Returns the converted integer.
* @example
*
* _.toLength(3.2);
* // => 3
*
* _.toLength(Number.MIN_VALUE);
* // => 0
*
* _.toLength(Infinity);
* // => 4294967295
...
```

#### <a name="apidoc.element.lodash.toLower"></a>[function <span class="apidocSignatureSpan">lodash.</span>toLower (value)](#apidoc.element.lodash.toLower)
- description and source-code
```javascript
function toLower(value) {
  return toString(value).toLowerCase();
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the lower cased string.
* @example
*
* _.toLower('--Foo-Bar--');
* // => '--foo-bar--'
*
* _.toLower('fooBar');
* // => 'foobar'
*
* _.toLower('__FOO_BAR__');
* // => '__foo_bar__'
...
```

#### <a name="apidoc.element.lodash.toNumber"></a>[function <span class="apidocSignatureSpan">lodash.</span>toNumber (value)](#apidoc.element.lodash.toNumber)
- description and source-code
```javascript
function toNumber(value) {
  if (typeof value == 'number') {
    return value;
  }
  if (isSymbol(value)) {
    return NAN;
  }
  if (isObject(value)) {
    var other = typeof value.valueOf == 'function' ? value.valueOf() : value;
    value = isObject(other) ? (other + '') : other;
  }
  if (typeof value != 'string') {
    return value === 0 ? value : +value;
  }
  value = value.replace(reTrim, '');
  var isBinary = reIsBinary.test(value);
  return (isBinary || reIsOctal.test(value))
    ? freeParseInt(value.slice(2), isBinary ? 2 : 8)
    : (reIsBadHex.test(value) ? NAN : +value);
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to process.
* @returns {number} Returns the number.
* @example
*
* _.toNumber(3.2);
* // => 3.2
*
* _.toNumber(Number.MIN_VALUE);
* // => 5e-324
*
* _.toNumber(Infinity);
* // => Infinity
...
```

#### <a name="apidoc.element.lodash.toPairs"></a>[function <span class="apidocSignatureSpan">lodash.</span>toPairs (object)](#apidoc.element.lodash.toPairs)
- description and source-code
```javascript
toPairs = function (object) {
  var tag = getTag(object);
  if (tag == mapTag) {
    return mapToArray(object);
  }
  if (tag == setTag) {
    return setToPairs(object);
  }
  return baseToPairs(object, keysFunc(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.toPairs(new Foo);
 * // => [['a', 1], ['b', 2]] (iteration order is not guaranteed)
 */
var toPairs = createToPairs(keys);

/**
 * Creates an array of own and inherited enumerable string keyed-value pairs
 * for 'object' which can be consumed by '_.fromPairs'. If 'object' is a map
...
```

#### <a name="apidoc.element.lodash.toPairsIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>toPairsIn (object)](#apidoc.element.lodash.toPairsIn)
- description and source-code
```javascript
toPairsIn = function (object) {
  var tag = getTag(object);
  if (tag == mapTag) {
    return mapToArray(object);
  }
  if (tag == setTag) {
    return setToPairs(object);
  }
  return baseToPairs(object, keysFunc(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.toPairsIn(new Foo);
 * // => [['a', 1], ['b', 2], ['c', 3]] (iteration order is not guaranteed)
 */
var toPairsIn = createToPairs(keysIn);

/**
 * An alternative to '_.reduce'; this method transforms 'object' to a new
 * 'accumulator' object which is the result of running each of its own
...
```

#### <a name="apidoc.element.lodash.toPath"></a>[function <span class="apidocSignatureSpan">lodash.</span>toPath (value)](#apidoc.element.lodash.toPath)
- description and source-code
```javascript
function toPath(value) {
  if (isArray(value)) {
    return arrayMap(value, toKey);
  }
  return isSymbol(value) ? [value] : copyArray(stringToPath(toString(value)));
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Util
 * @param {*} value The value to convert.
 * @returns {Array} Returns the new property path array.
 * @example
 *
 * _.toPath('a.b.c');
 * // => ['a', 'b', 'c']
 *
 * _.toPath('a[0].b.c');
 * // => ['a', '0', 'b', 'c']
 */
function toPath(value) {
  if (isArray(value)) {
...
```

#### <a name="apidoc.element.lodash.toPlainObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>toPlainObject (value)](#apidoc.element.lodash.toPlainObject)
- description and source-code
```javascript
function toPlainObject(value) {
  return copyObject(value, keysIn(value));
}
```
- example usage
```shell
...
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.assign({ 'a': 1 }, new Foo);
 * // => { 'a': 1, 'b': 2 }
 *
 * _.assign({ 'a': 1 }, _.toPlainObject(new Foo));
 * // => { 'a': 1, 'b': 2, 'c': 3 }
 */
function toPlainObject(value) {
  return copyObject(value, keysIn(value));
}

/**
...
```

#### <a name="apidoc.element.lodash.toSafeInteger"></a>[function <span class="apidocSignatureSpan">lodash.</span>toSafeInteger (value)](#apidoc.element.lodash.toSafeInteger)
- description and source-code
```javascript
function toSafeInteger(value) {
  return value
    ? baseClamp(toInteger(value), -MAX_SAFE_INTEGER, MAX_SAFE_INTEGER)
    : (value === 0 ? value : 0);
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category Lang
* @param {*} value The value to convert.
* @returns {number} Returns the converted integer.
* @example
*
* _.toSafeInteger(3.2);
* // => 3
*
* _.toSafeInteger(Number.MIN_VALUE);
* // => 0
*
* _.toSafeInteger(Infinity);
* // => 9007199254740991
...
```

#### <a name="apidoc.element.lodash.toUpper"></a>[function <span class="apidocSignatureSpan">lodash.</span>toUpper (value)](#apidoc.element.lodash.toUpper)
- description and source-code
```javascript
function toUpper(value) {
  return toString(value).toUpperCase();
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the upper cased string.
* @example
*
* _.toUpper('--foo-bar--');
* // => '--FOO-BAR--'
*
* _.toUpper('fooBar');
* // => 'FOOBAR'
*
* _.toUpper('__foo_bar__');
* // => '__FOO_BAR__'
...
```

#### <a name="apidoc.element.lodash.transform"></a>[function <span class="apidocSignatureSpan">lodash.</span>transform (object, iteratee, accumulator)](#apidoc.element.lodash.transform)
- description and source-code
```javascript
function transform(object, iteratee, accumulator) {
  var isArr = isArray(object),
      isArrLike = isArr || isBuffer(object) || isTypedArray(object);

  iteratee = getIteratee(iteratee, 4);
  if (accumulator == null) {
    var Ctor = object && object.constructor;
    if (isArrLike) {
      accumulator = isArr ? new Ctor : [];
    }
    else if (isObject(object)) {
      accumulator = isFunction(Ctor) ? baseCreate(getPrototype(object)) : {};
    }
    else {
      accumulator = {};
    }
  }
  (isArrLike ? arrayEach : baseForOwn)(object, function(value, index, object) {
    return iteratee(accumulator, value, index, object);
  });
  return accumulator;
}
```
- example usage
```shell
...
* @category Object
* @param {Object} object The object to iterate over.
* @param {Function} [iteratee=_.identity] The function invoked per iteration.
* @param {*} [accumulator] The custom accumulator value.
* @returns {*} Returns the accumulated value.
* @example
*
* _.transform([2, 3, 4], function(result, n) {
*   result.push(n *= n);
*   return n % 2 == 0;
* }, []);
* // => [4, 9]
*
* _.transform({ 'a': 1, 'b': 2, 'c': 1 }, function(result, value, key) {
*   (result[value] || (result[value] = [])).push(key);
...
```

#### <a name="apidoc.element.lodash.trim"></a>[function <span class="apidocSignatureSpan">lodash.</span>trim (string, chars, guard)](#apidoc.element.lodash.trim)
- description and source-code
```javascript
function trim(string, chars, guard) {
  string = toString(string);
  if (string && (guard || chars === undefined)) {
    return string.replace(reTrim, '');
  }
  if (!string || !(chars = baseToString(chars))) {
    return string;
  }
  var strSymbols = stringToArray(string),
      chrSymbols = stringToArray(chars),
      start = charsStartIndex(strSymbols, chrSymbols),
      end = charsEndIndex(strSymbols, chrSymbols) + 1;

  return castSlice(strSymbols, start, end).join('');
}
```
- example usage
```shell
...
 * @param {*} value The value to provide to 'interceptor'.
 * @param {Function} interceptor The function to invoke.
 * @returns {*} Returns the result of 'interceptor'.
 * @example
 *
 * _('  abc  ')
 *  .chain()
 *  .trim()
 *  .thru(function(value) {
 *    return [value];
 *  })
 *  .value();
 * // => ['abc']
 */
function thru(value, interceptor) {
...
```

#### <a name="apidoc.element.lodash.trimEnd"></a>[function <span class="apidocSignatureSpan">lodash.</span>trimEnd (string, chars, guard)](#apidoc.element.lodash.trimEnd)
- description and source-code
```javascript
function trimEnd(string, chars, guard) {
  string = toString(string);
  if (string && (guard || chars === undefined)) {
    return string.replace(reTrimEnd, '');
  }
  if (!string || !(chars = baseToString(chars))) {
    return string;
  }
  var strSymbols = stringToArray(string),
      end = charsEndIndex(strSymbols, stringToArray(chars)) + 1;

  return castSlice(strSymbols, 0, end).join('');
}
```
- example usage
```shell
...
 * @category String
 * @param {string} [string=''] The string to trim.
 * @param {string} [chars=whitespace] The characters to trim.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {string} Returns the trimmed string.
 * @example
 *
 * _.trimEnd('  abc  ');
 * // => '  abc'
 *
 * _.trimEnd('-_-abc-_-', '_-');
 * // => '-_-abc'
 */
function trimEnd(string, chars, guard) {
  string = toString(string);
...
```

#### <a name="apidoc.element.lodash.trimStart"></a>[function <span class="apidocSignatureSpan">lodash.</span>trimStart (string, chars, guard)](#apidoc.element.lodash.trimStart)
- description and source-code
```javascript
function trimStart(string, chars, guard) {
  string = toString(string);
  if (string && (guard || chars === undefined)) {
    return string.replace(reTrimStart, '');
  }
  if (!string || !(chars = baseToString(chars))) {
    return string;
  }
  var strSymbols = stringToArray(string),
      start = charsStartIndex(strSymbols, stringToArray(chars));

  return castSlice(strSymbols, start).join('');
}
```
- example usage
```shell
...
 * @category String
 * @param {string} [string=''] The string to trim.
 * @param {string} [chars=whitespace] The characters to trim.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {string} Returns the trimmed string.
 * @example
 *
 * _.trimStart('  abc  ');
 * // => 'abc  '
 *
 * _.trimStart('-_-abc-_-', '_-');
 * // => 'abc-_-'
 */
function trimStart(string, chars, guard) {
  string = toString(string);
...
```

#### <a name="apidoc.element.lodash.truncate"></a>[function <span class="apidocSignatureSpan">lodash.</span>truncate (string, options)](#apidoc.element.lodash.truncate)
- description and source-code
```javascript
function truncate(string, options) {
  var length = DEFAULT_TRUNC_LENGTH,
      omission = DEFAULT_TRUNC_OMISSION;

  if (isObject(options)) {
    var separator = 'separator' in options ? options.separator : separator;
    length = 'length' in options ? toInteger(options.length) : length;
    omission = 'omission' in options ? baseToString(options.omission) : omission;
  }
  string = toString(string);

  var strLength = string.length;
  if (hasUnicode(string)) {
    var strSymbols = stringToArray(string);
    strLength = strSymbols.length;
  }
  if (length >= strLength) {
    return string;
  }
  var end = length - stringSize(omission);
  if (end < 1) {
    return omission;
  }
  var result = strSymbols
    ? castSlice(strSymbols, 0, end).join('')
    : string.slice(0, end);

  if (separator === undefined) {
    return result + omission;
  }
  if (strSymbols) {
    end += (result.length - end);
  }
  if (isRegExp(separator)) {
    if (string.slice(end).search(separator)) {
      var match,
          substring = result;

      if (!separator.global) {
        separator = RegExp(separator.source, toString(reFlags.exec(separator)) + 'g');
      }
      separator.lastIndex = 0;
      while ((match = separator.exec(substring))) {
        var newEnd = match.index;
      }
      result = result.slice(0, newEnd === undefined ? end : newEnd);
    }
  } else if (string.indexOf(baseToString(separator), end) != end) {
    var index = result.lastIndexOf(separator);
    if (index > -1) {
      result = result.slice(0, index);
    }
  }
  return result + omission;
}
```
- example usage
```shell
...
* @param {Object} [options={}] The options object.
* @param {number} [options.length=30] The maximum string length.
* @param {string} [options.omission='...'] The string to indicate text is omitted.
* @param {RegExp|string} [options.separator] The separator pattern to truncate to.
* @returns {string} Returns the truncated string.
* @example
*
* _.truncate('hi-diddly-ho there, neighborino');
* // => 'hi-diddly-ho there, neighbo...'
*
* _.truncate('hi-diddly-ho there, neighborino', {
*   'length': 24,
*   'separator': ' '
* });
* // => 'hi-diddly-ho there,...'
...
```

#### <a name="apidoc.element.lodash.unary"></a>[function <span class="apidocSignatureSpan">lodash.</span>unary (func)](#apidoc.element.lodash.unary)
- description and source-code
```javascript
function unary(func) {
  return ary(func, 1);
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category Function
 * @param {Function} func The function to cap arguments for.
 * @returns {Function} Returns the new capped function.
 * @example
 *
 * _.map(['6', '8', '10'], _.unary(parseInt));
 * // => [6, 8, 10]
 */
function unary(func) {
  return ary(func, 1);
}

/**
...
```

#### <a name="apidoc.element.lodash.unescape"></a>[function <span class="apidocSignatureSpan">lodash.</span>unescape (string)](#apidoc.element.lodash.unescape)
- description and source-code
```javascript
function unescape(string) {
  string = toString(string);
  return (string && reHasEscapedHtml.test(string))
    ? string.replace(reEscapedHtml, unescapeHtmlChar)
    : string;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.6.0
 * @category String
 * @param {string} [string=''] The string to unescape.
 * @returns {string} Returns the unescaped string.
 * @example
 *
 * _.unescape('fred, barney, &amp; pebbles');
 * // => 'fred, barney, & pebbles'
 */
function unescape(string) {
  string = toString(string);
  return (string && reHasEscapedHtml.test(string))
    ? string.replace(reEscapedHtml, unescapeHtmlChar)
    : string;
...
```

#### <a name="apidoc.element.lodash.union"></a>[function <span class="apidocSignatureSpan">lodash.</span>union (arrays)](#apidoc.element.lodash.union)
- description and source-code
```javascript
union = function (arrays) {
  return baseUniq(baseFlatten(arrays, 1, isArrayLikeObject, true));
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @returns {Array} Returns the new array of combined values.
 * @example
 *
 * _.union([2], [1, 2]);
 * // => [2, 1]
 */
var union = baseRest(function(arrays) {
  return baseUniq(baseFlatten(arrays, 1, isArrayLikeObject, true));
});

/**
...
```

#### <a name="apidoc.element.lodash.unionBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>unionBy (arrays)](#apidoc.element.lodash.unionBy)
- description and source-code
```javascript
unionBy = function (arrays) {
  var iteratee = last(arrays);
  if (isArrayLikeObject(iteratee)) {
    iteratee = undefined;
  }
  return baseUniq(baseFlatten(arrays, 1, isArrayLikeObject, true), getIteratee(iteratee, 2));
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns the new array of combined values.
 * @example
 *
 * _.unionBy([2.1], [1.2, 2.3], Math.floor);
 * // => [2.1, 1.2]
 *
 * // The '_.property' iteratee shorthand.
 * _.unionBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
 * // => [{ 'x': 1 }, { 'x': 2 }]
 */
var unionBy = baseRest(function(arrays) {
...
```

#### <a name="apidoc.element.lodash.unionWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>unionWith (arrays)](#apidoc.element.lodash.unionWith)
- description and source-code
```javascript
unionWith = function (arrays) {
  var comparator = last(arrays);
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return baseUniq(baseFlatten(arrays, 1, isArrayLikeObject, true), undefined, comparator);
}
```
- example usage
```shell
...
 * @param {Function} [comparator] The comparator invoked per element.
 * @returns {Array} Returns the new array of combined values.
 * @example
 *
 * var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
 * var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];
 *
 * _.unionWith(objects, others, _.isEqual);
 * // => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
 */
var unionWith = baseRest(function(arrays) {
  var comparator = last(arrays);
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return baseUniq(baseFlatten(arrays, 1, isArrayLikeObject, true), undefined, comparator);
});
...
```

#### <a name="apidoc.element.lodash.uniq"></a>[function <span class="apidocSignatureSpan">lodash.</span>uniq (array)](#apidoc.element.lodash.uniq)
- description and source-code
```javascript
function uniq(array) {
  return (array && array.length) ? baseUniq(array) : [];
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 0.1.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @returns {Array} Returns the new duplicate free array.
 * @example
 *
 * _.uniq([2, 1, 2]);
 * // => [2, 1]
 */
function uniq(array) {
  return (array && array.length) ? baseUniq(array) : [];
}

/**
...
```

#### <a name="apidoc.element.lodash.uniqBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>uniqBy (array, iteratee)](#apidoc.element.lodash.uniqBy)
- description and source-code
```javascript
function uniqBy(array, iteratee) {
  return (array && array.length) ? baseUniq(array, getIteratee(iteratee, 2)) : [];
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns the new duplicate free array.
 * @example
 *
 * _.uniqBy([2.1, 1.2, 2.3], Math.floor);
 * // => [2.1, 1.2]
 *
 * // The '_.property' iteratee shorthand.
 * _.uniqBy([{ 'x': 1 }, { 'x': 2 }, { 'x': 1 }], 'x');
 * // => [{ 'x': 1 }, { 'x': 2 }]
 */
function uniqBy(array, iteratee) {
...
```

#### <a name="apidoc.element.lodash.uniqWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>uniqWith (array, comparator)](#apidoc.element.lodash.uniqWith)
- description and source-code
```javascript
function uniqWith(array, comparator) {
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return (array && array.length) ? baseUniq(array, undefined, comparator) : [];
}
```
- example usage
```shell
...
 * @param {Array} array The array to inspect.
 * @param {Function} [comparator] The comparator invoked per element.
 * @returns {Array} Returns the new duplicate free array.
 * @example
 *
 * var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }, { 'x': 1, 'y': 2 }];
 *
 * _.uniqWith(objects, _.isEqual);
 * // => [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }]
 */
function uniqWith(array, comparator) {
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return (array && array.length) ? baseUniq(array, undefined, comparator) : [];
}
...
```

#### <a name="apidoc.element.lodash.uniqueId"></a>[function <span class="apidocSignatureSpan">lodash.</span>uniqueId (prefix)](#apidoc.element.lodash.uniqueId)
- description and source-code
```javascript
function uniqueId(prefix) {
  var id = ++idCounter;
  return toString(prefix) + id;
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @memberOf _
 * @category Util
 * @param {string} [prefix=''] The value to prefix the ID with.
 * @returns {string} Returns the unique ID.
 * @example
 *
 * _.uniqueId('contact_');
 * // => 'contact_104'
 *
 * _.uniqueId();
 * // => '105'
 */
function uniqueId(prefix) {
  var id = ++idCounter;
...
```

#### <a name="apidoc.element.lodash.unset"></a>[function <span class="apidocSignatureSpan">lodash.</span>unset (object, path)](#apidoc.element.lodash.unset)
- description and source-code
```javascript
function unset(object, path) {
  return object == null ? true : baseUnset(object, path);
}
```
- example usage
```shell
...
* @category Object
* @param {Object} object The object to modify.
* @param {Array|string} path The path of the property to unset.
* @returns {boolean} Returns 'true' if the property is deleted, else 'false'.
* @example
*
* var object = { 'a': [{ 'b': { 'c': 7 } }] };
* _.unset(object, 'a[0].b.c');
* // => true
*
* console.log(object);
* // => { 'a': [{ 'b': {} }] };
*
* _.unset(object, ['a', '0', 'b', 'c']);
* // => true
...
```

#### <a name="apidoc.element.lodash.unzip"></a>[function <span class="apidocSignatureSpan">lodash.</span>unzip (array)](#apidoc.element.lodash.unzip)
- description and source-code
```javascript
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var length = 0;
  array = arrayFilter(array, function(group) {
    if (isArrayLikeObject(group)) {
      length = nativeMax(group.length, length);
      return true;
    }
  });
  return baseTimes(length, function(index) {
    return arrayMap(array, baseProperty(index));
  });
}
```
- example usage
```shell
...
 * @param {Array} array The array of grouped elements to process.
 * @returns {Array} Returns the new array of regrouped elements.
 * @example
 *
 * var zipped = _.zip(['a', 'b'], [1, 2], [true, false]);
 * // => [['a', 1, true], ['b', 2, false]]
 *
 * _.unzip(zipped);
 * // => [['a', 'b'], [1, 2], [true, false]]
 */
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var length = 0;
...
```

#### <a name="apidoc.element.lodash.unzipWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>unzipWith (array, iteratee)](#apidoc.element.lodash.unzipWith)
- description and source-code
```javascript
function unzipWith(array, iteratee) {
  if (!(array && array.length)) {
    return [];
  }
  var result = unzip(array);
  if (iteratee == null) {
    return result;
  }
  return arrayMap(result, function(group) {
    return apply(iteratee, undefined, group);
  });
}
```
- example usage
```shell
...
 *  regrouped values.
 * @returns {Array} Returns the new array of regrouped elements.
 * @example
 *
 * var zipped = _.zip([1, 2], [10, 20], [100, 200]);
 * // => [[1, 10, 100], [2, 20, 200]]
 *
 * _.unzipWith(zipped, _.add);
 * // => [3, 30, 300]
 */
function unzipWith(array, iteratee) {
  if (!(array && array.length)) {
    return [];
  }
  var result = unzip(array);
...
```

#### <a name="apidoc.element.lodash.update"></a>[function <span class="apidocSignatureSpan">lodash.</span>update (object, path, updater)](#apidoc.element.lodash.update)
- description and source-code
```javascript
function update(object, path, updater) {
  return object == null ? object : baseUpdate(object, path, castFunction(updater));
}
```
- example usage
```shell
...
* @param {Array|string} path The path of the property to set.
* @param {Function} updater The function to produce the updated value.
* @returns {Object} Returns 'object'.
* @example
*
* var object = { 'a': [{ 'b': { 'c': 3 } }] };
*
* _.update(object, 'a[0].b.c', function(n) { return n * n; });
* console.log(object.a[0].b.c);
* // => 9
*
* _.update(object, 'x[0].y.z', function(n) { return n ? n + 1 : 0; });
* console.log(object.x[0].y.z);
* // => 0
*/
...
```

#### <a name="apidoc.element.lodash.updateWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>updateWith (object, path, updater, customizer)](#apidoc.element.lodash.updateWith)
- description and source-code
```javascript
function updateWith(object, path, updater, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return object == null ? object : baseUpdate(object, path, castFunction(updater), customizer);
}
```
- example usage
```shell
...
 * @param {Function} updater The function to produce the updated value.
 * @param {Function} [customizer] The function to customize assigned values.
 * @returns {Object} Returns 'object'.
 * @example
 *
 * var object = {};
 *
 * _.updateWith(object, '[0][1]', _.constant('a'), Object);
 * // => { '0': { '1': 'a' } }
 */
function updateWith(object, path, updater, customizer) {
  customizer = typeof customizer == 'function' ? customizer : undefined;
  return object == null ? object : baseUpdate(object, path, castFunction(updater), customizer);
}
...
```

#### <a name="apidoc.element.lodash.upperCase"></a>[function <span class="apidocSignatureSpan">lodash.</span>upperCase (string)](#apidoc.element.lodash.upperCase)
- description and source-code
```javascript
upperCase = function (string) {
  return arrayReduce(words(deburr(string).replace(reApos, '')), callback, '');
}
```
- example usage
```shell
...
* @memberOf _
* @since 4.0.0
* @category String
* @param {string} [string=''] The string to convert.
* @returns {string} Returns the upper cased string.
* @example
*
* _.upperCase('--foo-bar');
* // => 'FOO BAR'
*
* _.upperCase('fooBar');
* // => 'FOO BAR'
*
* _.upperCase('__foo_bar__');
* // => 'FOO BAR'
...
```

#### <a name="apidoc.element.lodash.upperFirst"></a>[function <span class="apidocSignatureSpan">lodash.</span>upperFirst (string)](#apidoc.element.lodash.upperFirst)
- description and source-code
```javascript
upperFirst = function (string) {
  string = toString(string);

  var strSymbols = hasUnicode(string)
    ? stringToArray(string)
    : undefined;

  var chr = strSymbols
    ? strSymbols[0]
    : string.charAt(0);

  var trailing = strSymbols
    ? castSlice(strSymbols, 1).join('')
    : string.slice(1);

  return chr[methodName]() + trailing;
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 4.0.0
 * @category String
 * @param {string} [string=''] The string to convert.
 * @returns {string} Returns the converted string.
 * @example
 *
 * _.upperFirst('fred');
 * // => 'Fred'
 *
 * _.upperFirst('FRED');
 * // => 'FRED'
 */
var upperFirst = createCaseFirst('toUpperCase');
...
```

#### <a name="apidoc.element.lodash.values"></a>[function <span class="apidocSignatureSpan">lodash.</span>values (object)](#apidoc.element.lodash.values)
- description and source-code
```javascript
function values(object) {
  return object == null ? [] : baseValues(object, keys(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.values(new Foo);
 * // => [1, 2] (iteration order is not guaranteed)
 *
 * _.values('hi');
 * // => ['h', 'i']
 */
function values(object) {
  return object == null ? [] : baseValues(object, keys(object));
...
```

#### <a name="apidoc.element.lodash.valuesIn"></a>[function <span class="apidocSignatureSpan">lodash.</span>valuesIn (object)](#apidoc.element.lodash.valuesIn)
- description and source-code
```javascript
function valuesIn(object) {
  return object == null ? [] : baseValues(object, keysIn(object));
}
```
- example usage
```shell
...
 * function Foo() {
 *   this.a = 1;
 *   this.b = 2;
 * }
 *
 * Foo.prototype.c = 3;
 *
 * _.valuesIn(new Foo);
 * // => [1, 2, 3] (iteration order is not guaranteed)
 */
function valuesIn(object) {
  return object == null ? [] : baseValues(object, keysIn(object));
}

/*------------------------------------------------------------------------*/
...
```

#### <a name="apidoc.element.lodash.without"></a>[function <span class="apidocSignatureSpan">lodash.</span>without (array, values)](#apidoc.element.lodash.without)
- description and source-code
```javascript
without = function (array, values) {
  return isArrayLikeObject(array)
    ? baseDifference(array, values)
    : [];
}
```
- example usage
```shell
...
 * @category Array
 * @param {Array} array The array to inspect.
 * @param {...*} [values] The values to exclude.
 * @returns {Array} Returns the new array of filtered values.
 * @see _.difference, _.xor
 * @example
 *
 * _.without([2, 1, 2, 3], 1, 2);
 * // => [3]
 */
var without = baseRest(function(array, values) {
  return isArrayLikeObject(array)
    ? baseDifference(array, values)
    : [];
});
...
```

#### <a name="apidoc.element.lodash.words"></a>[function <span class="apidocSignatureSpan">lodash.</span>words (string, pattern, guard)](#apidoc.element.lodash.words)
- description and source-code
```javascript
function words(string, pattern, guard) {
  string = toString(string);
  pattern = guard ? undefined : pattern;

  if (pattern === undefined) {
    return hasUnicodeWord(string) ? unicodeWords(string) : asciiWords(string);
  }
  return string.match(pattern) || [];
}
```
- example usage
```shell
...
 * @category String
 * @param {string} [string=''] The string to inspect.
 * @param {RegExp|string} [pattern] The pattern to match words.
 * @param- {Object} [guard] Enables use as an iteratee for methods like '_.map'.
 * @returns {Array} Returns the words of 'string'.
 * @example
 *
 * _.words('fred, barney, & pebbles');
 * // => ['fred', 'barney', 'pebbles']
 *
 * _.words('fred, barney, & pebbles', /[^, ]+/g);
 * // => ['fred', 'barney', '&', 'pebbles']
 */
function words(string, pattern, guard) {
  string = toString(string);
...
```

#### <a name="apidoc.element.lodash.wrap"></a>[function <span class="apidocSignatureSpan">lodash.</span>wrap (value, wrapper)](#apidoc.element.lodash.wrap)
- description and source-code
```javascript
function wrap(value, wrapper) {
  return partial(castFunction(wrapper), value);
}
```
- example usage
```shell
...
 * @since 0.1.0
 * @category Function
 * @param {*} value The value to wrap.
 * @param {Function} [wrapper=identity] The wrapper function.
 * @returns {Function} Returns the new function.
 * @example
 *
 * var p = _.wrap(_.escape, function(func, text) {
 *   return '<p>' + func(text) + '</p>';
 * });
 *
 * p('fred, barney, & pebbles');
 * // => '<p>fred, barney, &amp; pebbles</p>'
 */
function wrap(value, wrapper) {
...
```

#### <a name="apidoc.element.lodash.xor"></a>[function <span class="apidocSignatureSpan">lodash.</span>xor (arrays)](#apidoc.element.lodash.xor)
- description and source-code
```javascript
xor = function (arrays) {
  return baseXor(arrayFilter(arrays, isArrayLikeObject));
}
```
- example usage
```shell
...
 * @since 2.4.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @returns {Array} Returns the new array of filtered values.
 * @see _.difference, _.without
 * @example
 *
 * _.xor([2, 1], [2, 3]);
 * // => [1, 3]
 */
var xor = baseRest(function(arrays) {
  return baseXor(arrayFilter(arrays, isArrayLikeObject));
});

/**
...
```

#### <a name="apidoc.element.lodash.xorBy"></a>[function <span class="apidocSignatureSpan">lodash.</span>xorBy (arrays)](#apidoc.element.lodash.xorBy)
- description and source-code
```javascript
xorBy = function (arrays) {
  var iteratee = last(arrays);
  if (isArrayLikeObject(iteratee)) {
    iteratee = undefined;
  }
  return baseXor(arrayFilter(arrays, isArrayLikeObject), getIteratee(iteratee, 2));
}
```
- example usage
```shell
...
 * @since 4.0.0
 * @category Array
 * @param {...Array} [arrays] The arrays to inspect.
 * @param {Function} [iteratee=_.identity] The iteratee invoked per element.
 * @returns {Array} Returns the new array of filtered values.
 * @example
 *
 * _.xorBy([2.1, 1.2], [2.3, 3.4], Math.floor);
 * // => [1.2, 3.4]
 *
 * // The '_.property' iteratee shorthand.
 * _.xorBy([{ 'x': 1 }], [{ 'x': 2 }, { 'x': 1 }], 'x');
 * // => [{ 'x': 2 }]
 */
var xorBy = baseRest(function(arrays) {
...
```

#### <a name="apidoc.element.lodash.xorWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>xorWith (arrays)](#apidoc.element.lodash.xorWith)
- description and source-code
```javascript
xorWith = function (arrays) {
  var comparator = last(arrays);
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return baseXor(arrayFilter(arrays, isArrayLikeObject), undefined, comparator);
}
```
- example usage
```shell
...
 * @param {Function} [comparator] The comparator invoked per element.
 * @returns {Array} Returns the new array of filtered values.
 * @example
 *
 * var objects = [{ 'x': 1, 'y': 2 }, { 'x': 2, 'y': 1 }];
 * var others = [{ 'x': 1, 'y': 1 }, { 'x': 1, 'y': 2 }];
 *
 * _.xorWith(objects, others, _.isEqual);
 * // => [{ 'x': 2, 'y': 1 }, { 'x': 1, 'y': 1 }]
 */
var xorWith = baseRest(function(arrays) {
  var comparator = last(arrays);
  comparator = typeof comparator == 'function' ? comparator : undefined;
  return baseXor(arrayFilter(arrays, isArrayLikeObject), undefined, comparator);
});
...
```

#### <a name="apidoc.element.lodash.zip"></a>[function <span class="apidocSignatureSpan">lodash.</span>zip (array)](#apidoc.element.lodash.zip)
- description and source-code
```javascript
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var length = 0;
  array = arrayFilter(array, function(group) {
    if (isArrayLikeObject(group)) {
      length = nativeMax(group.length, length);
      return true;
    }
  });
  return baseTimes(length, function(index) {
    return arrayMap(array, baseProperty(index));
  });
}
```
- example usage
```shell
...
 * @memberOf _
 * @since 1.2.0
 * @category Array
 * @param {Array} array The array of grouped elements to process.
 * @returns {Array} Returns the new array of regrouped elements.
 * @example
 *
 * var zipped = _.zip(['a', 'b'], [1, 2], [true, false]);
 * // => [['a', 1, true], ['b', 2, false]]
 *
 * _.unzip(zipped);
 * // => [['a', 'b'], [1, 2], [true, false]]
 */
function unzip(array) {
  if (!(array && array.length)) {
...
```

#### <a name="apidoc.element.lodash.zipObject"></a>[function <span class="apidocSignatureSpan">lodash.</span>zipObject (props, values)](#apidoc.element.lodash.zipObject)
- description and source-code
```javascript
function zipObject(props, values) {
  return baseZipObject(props || [], values || [], assignValue);
}
```
- example usage
```shell
...
 * @since 0.4.0
 * @category Array
 * @param {Array} [props=[]] The property identifiers.
 * @param {Array} [values=[]] The property values.
 * @returns {Object} Returns the new object.
 * @example
 *
 * _.zipObject(['a', 'b'], [1, 2]);
 * // => { 'a': 1, 'b': 2 }
 */
function zipObject(props, values) {
  return baseZipObject(props || [], values || [], assignValue);
}

/**
...
```

#### <a name="apidoc.element.lodash.zipObjectDeep"></a>[function <span class="apidocSignatureSpan">lodash.</span>zipObjectDeep (props, values)](#apidoc.element.lodash.zipObjectDeep)
- description and source-code
```javascript
function zipObjectDeep(props, values) {
  return baseZipObject(props || [], values || [], baseSet);
}
```
- example usage
```shell
...
 * @since 4.1.0
 * @category Array
 * @param {Array} [props=[]] The property identifiers.
 * @param {Array} [values=[]] The property values.
 * @returns {Object} Returns the new object.
 * @example
 *
 * _.zipObjectDeep(['a.b[0].c', 'a.b[1].d'], [1, 2]);
 * // => { 'a': { 'b': [{ 'c': 1 }, { 'd': 2 }] } }
 */
function zipObjectDeep(props, values) {
  return baseZipObject(props || [], values || [], baseSet);
}

/**
...
```

#### <a name="apidoc.element.lodash.zipWith"></a>[function <span class="apidocSignatureSpan">lodash.</span>zipWith (arrays)](#apidoc.element.lodash.zipWith)
- description and source-code
```javascript
zipWith = function (arrays) {
  var length = arrays.length,
      iteratee = length > 1 ? arrays[length - 1] : undefined;

  iteratee = typeof iteratee == 'function' ? (arrays.pop(), iteratee) : undefined;
  return unzipWith(arrays, iteratee);
}
```
- example usage
```shell
...
 * @category Array
 * @param {...Array} [arrays] The arrays to process.
 * @param {Function} [iteratee=_.identity] The function to combine
 *  grouped values.
 * @returns {Array} Returns the new array of grouped elements.
 * @example
 *
 * _.zipWith([1, 2], [10, 20], [100, 200], function(a, b, c) {
 *   return a + b + c;
 * });
 * // => [111, 222]
 */
var zipWith = baseRest(function(arrays) {
  var length = arrays.length,
      iteratee = length > 1 ? arrays[length - 1] : undefined;
...
```



# <a name="apidoc.module.lodash.bind"></a>[module lodash.bind](#apidoc.module.lodash.bind)

#### <a name="apidoc.element.lodash.bind.bind"></a>[function <span class="apidocSignatureSpan">lodash.</span>bind ()](#apidoc.element.lodash.bind.bind)
- description and source-code
```javascript
function bind() { [native code] }
```
- example usage
```shell
...
*
* function greet(greeting, punctuation) {
*   return greeting + ' ' + this.user + punctuation;
* }
*
* var object = { 'user': 'fred' };
*
* var bound = _.bind(greet, object, 'hi');
* bound('!');
* // => 'hi fred!'
*
* // Bound with placeholders.
* var bound = _.bind(greet, object, _, '!');
* bound('hi');
* // => 'hi fred!'
...
```



# <a name="apidoc.module.lodash.bindKey"></a>[module lodash.bindKey](#apidoc.module.lodash.bindKey)

#### <a name="apidoc.element.lodash.bindKey.bindKey"></a>[function <span class="apidocSignatureSpan">lodash.</span>bindKey (object, key, partials)](#apidoc.element.lodash.bindKey.bindKey)
- description and source-code
```javascript
bindKey = function (object, key, partials) {
  var bitmask = WRAP_BIND_FLAG | WRAP_BIND_KEY_FLAG;
  if (partials.length) {
    var holders = replaceHolders(partials, getHolder(bindKey));
    bitmask |= WRAP_PARTIAL_FLAG;
  }
  return createWrap(key, bitmask, object, partials, holders);
}
```
- example usage
```shell
...
* var object = {
*   'user': 'fred',
*   'greet': function(greeting, punctuation) {
*     return greeting + ' ' + this.user + punctuation;
*   }
* };
*
* var bound = _.bindKey(object, 'greet', 'hi');
* bound('!');
* // => 'hi fred!'
*
* object.greet = function(greeting, punctuation) {
*   return greeting + 'ya ' + this.user + punctuation;
* };
*
...
```



# <a name="apidoc.module.lodash.curry"></a>[module lodash.curry](#apidoc.module.lodash.curry)

#### <a name="apidoc.element.lodash.curry.curry"></a>[function <span class="apidocSignatureSpan">lodash.</span>curry (func, arity, guard)](#apidoc.element.lodash.curry.curry)
- description and source-code
```javascript
function curry(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrap(func, WRAP_CURRY_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curry.placeholder;
  return result;
}
```
- example usage
```shell
...
* @returns {Function} Returns the new curried function.
* @example
*
* var abc = function(a, b, c) {
*   return [a, b, c];
* };
*
* var curried = _.curry(abc);
*
* curried(1)(2)(3);
* // => [1, 2, 3]
*
* curried(1, 2)(3);
* // => [1, 2, 3]
*
...
```



# <a name="apidoc.module.lodash.curryRight"></a>[module lodash.curryRight](#apidoc.module.lodash.curryRight)

#### <a name="apidoc.element.lodash.curryRight.curryRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>curryRight (func, arity, guard)](#apidoc.element.lodash.curryRight.curryRight)
- description and source-code
```javascript
function curryRight(func, arity, guard) {
  arity = guard ? undefined : arity;
  var result = createWrap(func, WRAP_CURRY_RIGHT_FLAG, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryRight.placeholder;
  return result;
}
```
- example usage
```shell
...
* @returns {Function} Returns the new curried function.
* @example
*
* var abc = function(a, b, c) {
*   return [a, b, c];
* };
*
* var curried = _.curryRight(abc);
*
* curried(3)(2)(1);
* // => [1, 2, 3]
*
* curried(2, 3)(1);
* // => [1, 2, 3]
*
...
```



# <a name="apidoc.module.lodash.memoize"></a>[module lodash.memoize](#apidoc.module.lodash.memoize)

#### <a name="apidoc.element.lodash.memoize.memoize"></a>[function <span class="apidocSignatureSpan">lodash.</span>memoize (func, resolver)](#apidoc.element.lodash.memoize.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver != null && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result) || cache;
    return result;
  };
  memoized.cache = new (memoize.Cache || MapCache);
  return memoized;
}
```
- example usage
```shell
...
* @param {Function} [resolver] The function to resolve the cache key.
* @returns {Function} Returns the new memoized function.
* @example
*
* var object = { 'a': 1, 'b': 2 };
* var other = { 'c': 3, 'd': 4 };
*
* var values = _.memoize(_.values);
* values(object);
* // => [1, 2]
*
* values(other);
* // => [3, 4]
*
* object.a = 2;
...
```

#### <a name="apidoc.element.lodash.memoize.Cache"></a>[function <span class="apidocSignatureSpan">lodash.memoize.</span>Cache (entries)](#apidoc.element.lodash.memoize.Cache)
- description and source-code
```javascript
function MapCache(entries) {
  var index = -1,
      length = entries == null ? 0 : entries.length;

  this.clear();
  while (++index < length) {
    var entry = entries[index];
    this.set(entry[0], entry[1]);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash.memoize.Cache"></a>[module lodash.memoize.Cache](#apidoc.module.lodash.memoize.Cache)

#### <a name="apidoc.element.lodash.memoize.Cache.Cache"></a>[function <span class="apidocSignatureSpan">lodash.memoize.</span>Cache (entries)](#apidoc.element.lodash.memoize.Cache.Cache)
- description and source-code
```javascript
function MapCache(entries) {
  var index = -1,
      length = entries == null ? 0 : entries.length;

  this.clear();
  while (++index < length) {
    var entry = entries[index];
    this.set(entry[0], entry[1]);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash.memoize.Cache.prototype"></a>[module lodash.memoize.Cache.prototype](#apidoc.module.lodash.memoize.Cache.prototype)

#### <a name="apidoc.element.lodash.memoize.Cache.prototype.clear"></a>[function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>clear ()](#apidoc.element.lodash.memoize.Cache.prototype.clear)
- description and source-code
```javascript
function mapCacheClear() {
  this.size = 0;
  this.__data__ = {
    'hash': new Hash,
    'map': new (Map || ListCache),
    'string': new Hash
  };
}
```
- example usage
```shell
...
 * @constructor
 * @param {Array} [entries] The key-value pairs to cache.
 */
function Hash(entries) {
  var index = -1,
      length = entries == null ? 0 : entries.length;

  this.clear();
  while (++index < length) {
    var entry = entries[index];
    this.set(entry[0], entry[1]);
  }
}

/**
...
```

#### <a name="apidoc.element.lodash.memoize.Cache.prototype.delete"></a>[function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>delete (key)](#apidoc.element.lodash.memoize.Cache.prototype.delete)
- description and source-code
```javascript
function mapCacheDelete(key) {
  var result = getMapData(this, key)['delete'](key);
  this.size -= result ? 1 : 0;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash.memoize.Cache.prototype.get"></a>[function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>get (key)](#apidoc.element.lodash.memoize.Cache.prototype.get)
- description and source-code
```javascript
function mapCacheGet(key) {
  return getMapData(this, key).get(key);
}
```
- example usage
```shell
...
 * @private
 * @name get
 * @memberOf MapCache
 * @param {string} key The key of the value to get.
 * @returns {*} Returns the entry value.
 */
function mapCacheGet(key) {
  return getMapData(this, key).get(key);
}

/**
 * Checks if a map value for 'key' exists.
 *
 * @private
 * @name has
...
```

#### <a name="apidoc.element.lodash.memoize.Cache.prototype.has"></a>[function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>has (key)](#apidoc.element.lodash.memoize.Cache.prototype.has)
- description and source-code
```javascript
function mapCacheHas(key) {
  return getMapData(this, key).has(key);
}
```
- example usage
```shell
...
 *
 * @private
 * @param {Object} cache The cache to query.
 * @param {string} key The key of the entry to check.
 * @returns {boolean} Returns 'true' if an entry for 'key' exists, else 'false'.
 */
function cacheHas(cache, key) {
  return cache.has(key);
}

/**
 * Used by '_.trim' and '_.trimStart' to get the index of the first string symbol
 * that is not found in the character symbols.
 *
 * @private
...
```

#### <a name="apidoc.element.lodash.memoize.Cache.prototype.set"></a>[function <span class="apidocSignatureSpan">lodash.memoize.Cache.prototype.</span>set (key, value)](#apidoc.element.lodash.memoize.Cache.prototype.set)
- description and source-code
```javascript
function mapCacheSet(key, value) {
  var data = getMapData(this, key),
      size = data.size;

  data.set(key, value);
  this.size += data.size == size ? 0 : 1;
  return this;
}
```
- example usage
```shell
...
 * @private
 * @param {Object} map The map to modify.
 * @param {Array} pair The key-value pair to add.
 * @returns {Object} Returns 'map'.
 */
function addMapEntry(map, pair) {
  // Don't return 'map.set' because it's not chainable in IE 11.
  map.set(pair[0], pair[1]);
  return map;
}

/**
 * Adds 'value' to 'set'.
 *
 * @private
...
```



# <a name="apidoc.module.lodash.partial"></a>[module lodash.partial](#apidoc.module.lodash.partial)

#### <a name="apidoc.element.lodash.partial.partial"></a>[function <span class="apidocSignatureSpan">lodash.</span>partial (func, partials)](#apidoc.element.lodash.partial.partial)
- description and source-code
```javascript
partial = function (func, partials) {
  var holders = replaceHolders(partials, getHolder(partial));
  return createWrap(func, WRAP_PARTIAL_FLAG, undefined, partials, holders);
}
```
- example usage
```shell
...
* @returns {Function} Returns the new partially applied function.
* @example
*
* function greet(greeting, name) {
*   return greeting + ' ' + name;
* }
*
* var sayHelloTo = _.partial(greet, 'hello');
* sayHelloTo('fred');
* // => 'hello fred'
*
* // Partially applied with placeholders.
* var greetFred = _.partial(greet, _, 'fred');
* greetFred('hi');
* // => 'hi fred'
...
```



# <a name="apidoc.module.lodash.partialRight"></a>[module lodash.partialRight](#apidoc.module.lodash.partialRight)

#### <a name="apidoc.element.lodash.partialRight.partialRight"></a>[function <span class="apidocSignatureSpan">lodash.</span>partialRight (func, partials)](#apidoc.element.lodash.partialRight.partialRight)
- description and source-code
```javascript
partialRight = function (func, partials) {
  var holders = replaceHolders(partials, getHolder(partialRight));
  return createWrap(func, WRAP_PARTIAL_RIGHT_FLAG, undefined, partials, holders);
}
```
- example usage
```shell
...
* @returns {Function} Returns the new partially applied function.
* @example
*
* function greet(greeting, name) {
*   return greeting + ' ' + name;
* }
*
* var greetFred = _.partialRight(greet, 'fred');
* greetFred('hi');
* // => 'hi fred'
*
* // Partially applied with placeholders.
* var sayHelloTo = _.partialRight(greet, 'hello', _);
* sayHelloTo('fred');
* // => 'hello fred'
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
