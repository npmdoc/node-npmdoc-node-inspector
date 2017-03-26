# api documentation for  [node-inspector (v0.12.10)](http://github.com/node-inspector/node-inspector)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-inspector.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-inspector)
#### Web Inspector based nodeJS debugger

[![NPM](https://nodei.co/npm/node-inspector.png?downloads=true)](https://www.npmjs.com/package/node-inspector)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-inspector/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-node-inspector_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-inspector/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-node-inspector/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "Danny Coates",
        "email": "dannycoates@gmail.com"
    },
    "bin": {
        "node-inspector": "./bin/inspector.js",
        "node-debug": "./bin/node-debug.js"
    },
    "bugs": {
        "url": "https://github.com/node-inspector/node-inspector/issues"
    },
    "contributors": [
        {
            "name": "Danny Coates",
            "email": "dannycoates@gmail.com"
        },
        {
            "name": "Miroslav Bajtoš",
            "email": "miroslav@strongloop.com"
        },
        {
            "name": "3y3",
            "email": "3y3@bk.ru"
        },
        {
            "name": "Adam Hořčica",
            "email": "horcicaa@gmail.com"
        },
        {
            "name": "Akzhan Abdulin",
            "email": "akzhan.abdulin@gmail.com"
        },
        {
            "name": "cattail",
            "email": "zhongchiyu@gmail.com"
        },
        {
            "name": "ChrisWren",
            "email": "cthewren@gmail.com"
        },
        {
            "name": "Dave",
            "email": "badave@gmail.com"
        },
        {
            "name": "Vasil Dininski",
            "email": "dininski@gmail.com"
        },
        {
            "name": "Dick Hardt",
            "email": "dickhardt@gmail.com"
        },
        {
            "name": "Gary Katsevman",
            "email": "git@gkatsev.com"
        },
        {
            "name": "Glenn Block",
            "email": "glenn.block@gmail.com"
        },
        {
            "name": "Ionică Bizău",
            "email": "bizauionica@yahoo.com"
        },
        {
            "name": "Ionuț G. Stan",
            "email": "ionut.g.stan@gmail.com"
        },
        {
            "name": "Ivan Baktsheev",
            "email": "dot.and.thing@gmail.com"
        },
        {
            "name": "junecoder",
            "email": "githubposting@gmail.com"
        },
        {
            "name": "Karan Batra-Daitch",
            "email": "karanganesha04@gmail.com"
        },
        {
            "name": "Kasper Ligaard",
            "email": "kasperligaard@gmail.com"
        },
        {
            "name": "Kenneth Auchenberg",
            "email": "kenneth@auchenberg.dk"
        },
        {
            "name": "Lennon Pulda-Grealy",
            "email": "lennon_puldagrealy@apple.com"
        },
        {
            "name": "Mark Constable",
            "email": "markc@renta.net"
        },
        {
            "name": "Matthew O'Riordan",
            "email": "matthew.oriordan@gmail.com"
        },
        {
            "name": "Michael Schoonmaker",
            "email": "michael@strongloop.com"
        },
        {
            "name": "Panagiotis Astithas",
            "email": "pastith@gmail.com"
        },
        {
            "name": "Peter Lyons",
            "email": "pete@peterlyons.com"
        },
        {
            "name": "Peter Flannery",
            "email": "flannery.peter@ntlworld.com"
        },
        {
            "name": "Philip Tellis",
            "email": "philip.tellis@gmail.com"
        },
        {
            "name": "Pritam Baral",
            "email": "pritam@pritambaral.com"
        },
        {
            "name": "Sam Roberts",
            "email": "sam@strongloop.com"
        },
        {
            "name": "Sergey Krilov",
            "email": "serg.kr@gmail.com"
        },
        {
            "name": "ssafejava",
            "email": "s@safejava.com"
        }
    ],
    "dependencies": {
        "async": "~0.9",
        "biased-opener": "~0.2.2",
        "debug": "^2.2.0",
        "express": "^4.12.3",
        "glob": "^5.0.5",
        "path-is-absolute": "^1.0.0",
        "rc": "^1.0.1",
        "semver": "^4.3.4",
        "serve-favicon": "^2.1.1",
        "strong-data-uri": "^1.0.0",
        "v8-debug": "~0.7.1",
        "v8-profiler": "~5.6.0",
        "which": "^1.1.1",
        "ws": "^1.0.1",
        "yargs": "^3.9.0"
    },
    "description": "Web Inspector based nodeJS debugger",
    "devDependencies": {
        "chai": "^2.1",
        "fs-extra": "~0.8.1",
        "jshint": "^2.4.4",
        "mocha": "^1.21",
        "promise": "^7.0.3"
    },
    "directories": {},
    "dist": {
        "shasum": "3208c523e31774cd792bf8fb929a5dcb96ec2d14",
        "tarball": "https://registry.npmjs.org/node-inspector/-/node-inspector-0.12.10.tgz"
    },
    "engines": {
        "node": ">=0.8.0"
    },
    "gitHead": "4919f44204f9aa2c3a73e5ad63552cacb88a66fb",
    "homepage": "http://github.com/node-inspector/node-inspector",
    "keywords": [
        "debug",
        "debugger",
        "inspector",
        "profiler"
    ],
    "maintainers": [
        {
            "name": "3y3",
            "email": "3y3@bk.ru"
        },
        {
            "name": "bajtos",
            "email": "mbajtoss@gmail.com"
        },
        {
            "name": "dannycoates",
            "email": "dannycoates@gmail.com"
        },
        {
            "name": "piscisaureus",
            "email": "bertbelder@gmail.com"
        },
        {
            "name": "rmg",
            "email": "r.m.graham@gmail.com"
        }
    ],
    "name": "node-inspector",
    "optionalDependencies": {},
    "preferGlobal": true,
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/node-inspector/node-inspector.git"
    },
    "scripts": {
        "generate-front-end": "node --harmony tools/generate-front-end",
        "pretest": "jshint .",
        "test": "mocha"
    },
    "version": "0.12.10"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module node-inspector](#apidoc.module.node-inspector)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>buildInspectorUrl (inspectorHost, inspectorPort, debugPort, isHttps)](#apidoc.element.node-inspector.buildInspectorUrl)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>buildWebSocketUrl (inspectorHost, inspectorPort, debugPort, isSecure)](#apidoc.element.node-inspector.buildWebSocketUrl)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>config (argv, NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>session (config, debuggerPort, wsConnection)](#apidoc.element.node-inspector.session)
1.  object <span class="apidocSignatureSpan">node-inspector.</span>BreakEventHandler
1.  object <span class="apidocSignatureSpan">node-inspector.</span>CallFramesProvider
1.  object <span class="apidocSignatureSpan">node-inspector.</span>ConsoleAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>ConsoleClient
1.  object <span class="apidocSignatureSpan">node-inspector.</span>DebuggerAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>DebuggerClient
1.  object <span class="apidocSignatureSpan">node-inspector.</span>FrontendClient
1.  object <span class="apidocSignatureSpan">node-inspector.</span>FrontendCommandHandler
1.  object <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerClient
1.  object <span class="apidocSignatureSpan">node-inspector.</span>InjectorClient
1.  object <span class="apidocSignatureSpan">node-inspector.</span>NetworkAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>PageAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>ProfilerAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>RuntimeAgent
1.  object <span class="apidocSignatureSpan">node-inspector.</span>ScriptFileStorage
1.  object <span class="apidocSignatureSpan">node-inspector.</span>ScriptManager
1.  object <span class="apidocSignatureSpan">node-inspector.</span>callback
1.  object <span class="apidocSignatureSpan">node-inspector.</span>config.prototype
1.  object <span class="apidocSignatureSpan">node-inspector.</span>convert
1.  object <span class="apidocSignatureSpan">node-inspector.</span>debug_server
1.  object <span class="apidocSignatureSpan">node-inspector.</span>debugger
1.  object <span class="apidocSignatureSpan">node-inspector.</span>plugins
1.  object <span class="apidocSignatureSpan">node-inspector.</span>session.prototype

#### [module node-inspector.BreakEventHandler](#apidoc.module.node-inspector.BreakEventHandler)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>BreakEventHandler (config, session)](#apidoc.element.node-inspector.BreakEventHandler.BreakEventHandler)

#### [module node-inspector.CallFramesProvider](#apidoc.module.node-inspector.CallFramesProvider)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>CallFramesProvider (config, session)](#apidoc.element.node-inspector.CallFramesProvider.CallFramesProvider)

#### [module node-inspector.ConsoleAgent](#apidoc.module.node-inspector.ConsoleAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>ConsoleAgent (config, session)](#apidoc.element.node-inspector.ConsoleAgent.ConsoleAgent)

#### [module node-inspector.ConsoleClient](#apidoc.module.node-inspector.ConsoleClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>ConsoleClient (config, session)](#apidoc.element.node-inspector.ConsoleClient.ConsoleClient)

#### [module node-inspector.DebuggerAgent](#apidoc.module.node-inspector.DebuggerAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>DebuggerAgent (config, session)](#apidoc.element.node-inspector.DebuggerAgent.DebuggerAgent)

#### [module node-inspector.DebuggerClient](#apidoc.module.node-inspector.DebuggerClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>DebuggerClient (debuggerPort)](#apidoc.element.node-inspector.DebuggerClient.DebuggerClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.DebuggerClient.</span>ErrorNotConnected (message)](#apidoc.element.node-inspector.DebuggerClient.ErrorNotConnected)

#### [module node-inspector.FrontendClient](#apidoc.module.node-inspector.FrontendClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>FrontendClient (connection)](#apidoc.element.node-inspector.FrontendClient.FrontendClient)

#### [module node-inspector.FrontendCommandHandler](#apidoc.module.node-inspector.FrontendCommandHandler)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>FrontendCommandHandler (config, session)](#apidoc.element.node-inspector.FrontendCommandHandler.FrontendCommandHandler)

#### [module node-inspector.HeapProfilerAgent](#apidoc.module.node-inspector.HeapProfilerAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerAgent (config, session)](#apidoc.element.node-inspector.HeapProfilerAgent.HeapProfilerAgent)

#### [module node-inspector.HeapProfilerClient](#apidoc.module.node-inspector.HeapProfilerClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerClient (config, session)](#apidoc.element.node-inspector.HeapProfilerClient.HeapProfilerClient)

#### [module node-inspector.InjectorClient](#apidoc.module.node-inspector.InjectorClient)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>InjectorClient (config, session)](#apidoc.element.node-inspector.InjectorClient.InjectorClient)

#### [module node-inspector.NetworkAgent](#apidoc.module.node-inspector.NetworkAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>NetworkAgent (config, session)](#apidoc.element.node-inspector.NetworkAgent.NetworkAgent)

#### [module node-inspector.PageAgent](#apidoc.module.node-inspector.PageAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>PageAgent (config, session)](#apidoc.element.node-inspector.PageAgent.PageAgent)

#### [module node-inspector.ProfilerAgent](#apidoc.module.node-inspector.ProfilerAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>ProfilerAgent (config, session)](#apidoc.element.node-inspector.ProfilerAgent.ProfilerAgent)

#### [module node-inspector.RuntimeAgent](#apidoc.module.node-inspector.RuntimeAgent)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>RuntimeAgent (config, session)](#apidoc.element.node-inspector.RuntimeAgent.RuntimeAgent)

#### [module node-inspector.ScriptFileStorage](#apidoc.module.node-inspector.ScriptFileStorage)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>ScriptFileStorage (config, session)](#apidoc.element.node-inspector.ScriptFileStorage.ScriptFileStorage)

#### [module node-inspector.ScriptManager](#apidoc.module.node-inspector.ScriptManager)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>ScriptManager (config, session)](#apidoc.element.node-inspector.ScriptManager.ScriptManager)

#### [module node-inspector.callback](#apidoc.module.node-inspector.callback)
1.  [function <span class="apidocSignatureSpan">node-inspector.callback.</span>create ()](#apidoc.element.node-inspector.callback.create)

#### [module node-inspector.config](#apidoc.module.node-inspector.config)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>config (argv, NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config.config)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.</span>_collectDefaults (NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config._collectDefaults)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.</span>filterDefaultValues ()](#apidoc.element.node-inspector.config.filterDefaultValues)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.</span>filterNodeDebugOptions ()](#apidoc.element.node-inspector.config.filterNodeDebugOptions)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.</span>filterOptions (filterExpression, options)](#apidoc.element.node-inspector.config.filterOptions)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.</span>serializeOptions (options, filter)](#apidoc.element.node-inspector.config.serializeOptions)

#### [module node-inspector.config.prototype](#apidoc.module.node-inspector.config.prototype)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.prototype.</span>showHelp (NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config.prototype.showHelp)
1.  [function <span class="apidocSignatureSpan">node-inspector.config.prototype.</span>showVersion ()](#apidoc.element.node-inspector.config.prototype.showVersion)

#### [module node-inspector.convert](#apidoc.module.node-inspector.convert)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorScriptIdToV8Id (scriptId)](#apidoc.element.node-inspector.convert.inspectorScriptIdToV8Id)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorUrlToV8Name (url, normalize)](#apidoc.element.node-inspector.convert.inspectorUrlToV8Name)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorValueToV8Value (value)](#apidoc.element.node-inspector.convert.inspectorValueToV8Value)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ErrorToInspectorError (message)](#apidoc.element.node-inspector.convert.v8ErrorToInspectorError)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8FunctionLookupToFunctionDetails (handleData)](#apidoc.element.node-inspector.convert.v8FunctionLookupToFunctionDetails)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8LocationToInspectorLocation (v8loc)](#apidoc.element.node-inspector.convert.v8LocationToInspectorLocation)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8NameToInspectorUrl (v8name)](#apidoc.element.node-inspector.convert.v8NameToInspectorUrl)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ObjectToInspectorProperties (obj, refs, options)](#apidoc.element.node-inspector.convert.v8ObjectToInspectorProperties)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8RefToInspectorObject (ref)](#apidoc.element.node-inspector.convert.v8RefToInspectorObject)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ResultToInspectorResult (result)](#apidoc.element.node-inspector.convert.v8ResultToInspectorResult)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ScopeTypeToString (v8ScopeType)](#apidoc.element.node-inspector.convert.v8ScopeTypeToString)
1.  [function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ScriptIdToInspectorId (scriptId)](#apidoc.element.node-inspector.convert.v8ScriptIdToInspectorId)

#### [module node-inspector.debug_server](#apidoc.module.node-inspector.debug_server)
1.  [function <span class="apidocSignatureSpan">node-inspector.debug_server.</span>DebugServer ()](#apidoc.element.node-inspector.debug_server.DebugServer)

#### [module node-inspector.debugger](#apidoc.module.node-inspector.debugger)
1.  [function <span class="apidocSignatureSpan">node-inspector.debugger.</span>attachDebugger (port)](#apidoc.element.node-inspector.debugger.attachDebugger)

#### [module node-inspector.plugins](#apidoc.module.node-inspector.plugins)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>InspectorJson (config)](#apidoc.element.node-inspector.plugins.InspectorJson)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>PluginError (message)](#apidoc.element.node-inspector.plugins.PluginError)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>ProtocolJson (config)](#apidoc.element.node-inspector.plugins.ProtocolJson)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>_setMockPlugins (pluginPath, plugins)](#apidoc.element.node-inspector.plugins._setMockPlugins)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>getPluginPath (config)](#apidoc.element.node-inspector.plugins.getPluginPath)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>getPlugins (config)](#apidoc.element.node-inspector.plugins.getPlugins)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>init (config)](#apidoc.element.node-inspector.plugins.init)
1.  [function <span class="apidocSignatureSpan">node-inspector.plugins.</span>validateManifest (manifest)](#apidoc.element.node-inspector.plugins.validateManifest)

#### [module node-inspector.session](#apidoc.module.node-inspector.session)
1.  [function <span class="apidocSignatureSpan">node-inspector.</span>session (config, debuggerPort, wsConnection)](#apidoc.element.node-inspector.session.session)
1.  [function <span class="apidocSignatureSpan">node-inspector.session.</span>super_ ()](#apidoc.element.node-inspector.session.super_)

#### [module node-inspector.session.prototype](#apidoc.module.node-inspector.session.prototype)
1.  [function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>_onDebuggerClientClose (reason)](#apidoc.element.node-inspector.session.prototype._onDebuggerClientClose)
1.  [function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>_onDebuggerClientError (e)](#apidoc.element.node-inspector.session.prototype._onDebuggerClientError)
1.  [function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>close ()](#apidoc.element.node-inspector.session.prototype.close)



# <a name="apidoc.module.node-inspector"></a>[module node-inspector](#apidoc.module.node-inspector)

#### <a name="apidoc.element.node-inspector.buildInspectorUrl"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>buildInspectorUrl (inspectorHost, inspectorPort, debugPort, isHttps)](#apidoc.element.node-inspector.buildInspectorUrl)
- description and source-code
```javascript
function buildInspectorUrl(inspectorHost, inspectorPort, debugPort, isHttps) {
  var host = inspectorHost == '0.0.0.0' ? '127.0.0.1' : inspectorHost;
  var port = inspectorPort;
  var protocol = isHttps ? 'https' : 'http';

  var isUnixSocket = !/^\d+$/.test(port);
  if (isUnixSocket) {
    host = path.resolve(__dirname, inspectorPort);
    port = null;
    protocol = 'unix';
  }

  var parts = {
    protocol: protocol,
    hostname: host,
    port: port,
    pathname: '/',
    search: '?port=' + debugPort
  };

  return url.format(parts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.buildWebSocketUrl"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>buildWebSocketUrl (inspectorHost, inspectorPort, debugPort, isSecure)](#apidoc.element.node-inspector.buildWebSocketUrl)
- description and source-code
```javascript
function buildWebSocketUrl(inspectorHost, inspectorPort, debugPort, isSecure) {
  var parts = {
    protocol: isSecure ? 'wss:' : 'ws:',
    hostname: inspectorHost == '0.0.0.0' ? '127.0.0.1' : inspectorHost,
    port: inspectorPort,
    pathname: '/',
    search: '?port=' + debugPort,
    slashes: true
  };

  return url.format(parts);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>config (argv, NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config)
- description and source-code
```javascript
function Config(argv, NODE_DEBUG_MODE) {
  var defaults = collectDefaultsFromDefinitions(NODE_DEBUG_MODE);
  var parsedArgv = parseArgs(argv);

  checkDeprecatedHiddenStyle(parsedArgv);

  var rcConfig = rc('node-inspector', defaults, parsedArgv);
  var config = normalizeOptions(rcConfig);

  checkDeprecatedNoPreloadStyle(config);
  checkDeprecatedWebHostStyle(config);

  util._extend(this, config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.session"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>session (config, debuggerPort, wsConnection)](#apidoc.element.node-inspector.session)
- description and source-code
```javascript
function Session(config, debuggerPort, wsConnection) {
  this.debuggerClient = new DebuggerClient(debuggerPort);
  this.frontendClient = new FrontendClient(wsConnection);
  this.injectorClient = new InjectorClient(config, this);
  this.consoleClient = new ConsoleClient(config, this);
  this.heapProfilerClient = new HeapProfilerClient(config, this);
  this.scriptManager = new ScriptManager(config, this);
  this.breakEventHandler = new BreakEventHandler(config, this);
  this.frontendCommandHandler = new FrontendCommandHandler(config, this);

  this.resourceTreeResolved = false;
  this.once('resource-tree-resolved', function() {
    this.resourceTreeResolved = true;
  }.bind(this));

  this.frontendClient.on('close', this.close.bind(this));
  this.debuggerClient.on('close', this._onDebuggerClientClose.bind(this));
  this.debuggerClient.on('error', this._onDebuggerClientError.bind(this));

  this._pingInterval = setInterval(function() {
    wsConnection.ping(null, null, true);
  }.bind(this), 1000);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.BreakEventHandler"></a>[module node-inspector.BreakEventHandler](#apidoc.module.node-inspector.BreakEventHandler)

#### <a name="apidoc.element.node-inspector.BreakEventHandler.BreakEventHandler"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>BreakEventHandler (config, session)](#apidoc.element.node-inspector.BreakEventHandler.BreakEventHandler)
- description and source-code
```javascript
function BreakEventHandler(config, session) {
  this._config = config;
  this._session = session;
  this._frontendClient = session.frontendClient;
  this._debuggerClient = session.debuggerClient;
  this._injectorClient = session.injectorClient;
  this._scriptManager = session.scriptManager;
  this._callFramesProvider = new CallFramesProvider(config, session);

  this._debuggerClient.on('break', this._onBreak.bind(this));
  this._debuggerClient.on('exception', this._onBreak.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.CallFramesProvider"></a>[module node-inspector.CallFramesProvider](#apidoc.module.node-inspector.CallFramesProvider)

#### <a name="apidoc.element.node-inspector.CallFramesProvider.CallFramesProvider"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>CallFramesProvider (config, session)](#apidoc.element.node-inspector.CallFramesProvider.CallFramesProvider)
- description and source-code
```javascript
function CallFramesProvider(config, session) {
  this._config = config;
  this._debuggerClient = session.debuggerClient;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.ConsoleAgent"></a>[module node-inspector.ConsoleAgent](#apidoc.module.node-inspector.ConsoleAgent)

#### <a name="apidoc.element.node-inspector.ConsoleAgent.ConsoleAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>ConsoleAgent (config, session)](#apidoc.element.node-inspector.ConsoleAgent.ConsoleAgent)
- description and source-code
```javascript
function ConsoleAgent(config, session) {
  try {
    this._noInject = config.inject === false || config.inject.console === false;
  } catch (e) {
    this._noInject = false;
  }

  this._injected = false;
  this._debuggerClient = session.debuggerClient;
  this._frontendClient = session.frontendClient;
  this._injectorClient = session.injectorClient;
  this._consoleClient = session.consoleClient;
  this._translateCommandToInjection(
    'clearMessages'
  );

  if (!this._noInject) this._injectorClient.on('inject', this._inject.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.ConsoleClient"></a>[module node-inspector.ConsoleClient](#apidoc.module.node-inspector.ConsoleClient)

#### <a name="apidoc.element.node-inspector.ConsoleClient.ConsoleClient"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>ConsoleClient (config, session)](#apidoc.element.node-inspector.ConsoleClient.ConsoleClient)
- description and source-code
```javascript
function ConsoleClient(config, session) {
  this._debuggerClient = session.debuggerClient;
  this._frontendClient = session.frontendClient;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.DebuggerAgent"></a>[module node-inspector.DebuggerAgent](#apidoc.module.node-inspector.DebuggerAgent)

#### <a name="apidoc.element.node-inspector.DebuggerAgent.DebuggerAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>DebuggerAgent (config, session)](#apidoc.element.node-inspector.DebuggerAgent.DebuggerAgent)
- description and source-code
```javascript
function DebuggerAgent(config, session) {
  this._enabled = false;
  this._saveLiveEdit = config.saveLiveEdit;
  this._frontendClient = session.frontendClient;
  this._debuggerClient = session.debuggerClient;
  this._breakEventHandler = session.breakEventHandler;
  this._scriptManager = session.scriptManager;
  this._injectorClient = session.injectorClient;
  this._consoleClient = session.consoleClient;
  this._heapProfilerClient = session.heapProfilerClient;
  this._scriptStorage = new ScriptFileStorage(config, session);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.DebuggerClient"></a>[module node-inspector.DebuggerClient](#apidoc.module.node-inspector.DebuggerClient)

#### <a name="apidoc.element.node-inspector.DebuggerClient.DebuggerClient"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>DebuggerClient (debuggerPort)](#apidoc.element.node-inspector.DebuggerClient.DebuggerClient)
- description and source-code
```javascript
function DebuggerClient(debuggerPort) {
  this._conn = createFailingConnection('node-inspector server was restarted');
  this._port = debuggerPort;

  this.target = null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.DebuggerClient.ErrorNotConnected"></a>[function <span class="apidocSignatureSpan">node-inspector.DebuggerClient.</span>ErrorNotConnected (message)](#apidoc.element.node-inspector.DebuggerClient.ErrorNotConnected)
- description and source-code
```javascript
function ErrorNotConnected(message) {
  Error.call(this);
  this.name = ErrorNotConnected.name;
  this.message = message;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.FrontendClient"></a>[module node-inspector.FrontendClient](#apidoc.module.node-inspector.FrontendClient)

#### <a name="apidoc.element.node-inspector.FrontendClient.FrontendClient"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>FrontendClient (connection)](#apidoc.element.node-inspector.FrontendClient.FrontendClient)
- description and source-code
```javascript
function FrontendClient(connection) {
  this._connection = connection;
  this._registerEventHandlers();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.FrontendCommandHandler"></a>[module node-inspector.FrontendCommandHandler](#apidoc.module.node-inspector.FrontendCommandHandler)

#### <a name="apidoc.element.node-inspector.FrontendCommandHandler.FrontendCommandHandler"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>FrontendCommandHandler (config, session)](#apidoc.element.node-inspector.FrontendCommandHandler.FrontendCommandHandler)
- description and source-code
```javascript
function FrontendCommandHandler(config, session) {
  this._config = config;
  this._session = session;
  this._agents = {};
  this._specialCommands = {};
  this._frontendClient = session.frontendClient;
  this._debuggerClient = session.debuggerClient;
  this._breakEventHandler = session.breakEventHandler;
  this._scriptManager = session.scriptManager;
  this._consoleClient = session.consoleClient;
  this._heapProfilerClient = session.heapProfilerClient;
  this._injectorClient = session.injectorClient;
  this._initializeRegistry();
  this._registerEventHandlers();
  this._pauseInitialEvents();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.HeapProfilerAgent"></a>[module node-inspector.HeapProfilerAgent](#apidoc.module.node-inspector.HeapProfilerAgent)

#### <a name="apidoc.element.node-inspector.HeapProfilerAgent.HeapProfilerAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerAgent (config, session)](#apidoc.element.node-inspector.HeapProfilerAgent.HeapProfilerAgent)
- description and source-code
```javascript
function HeapProfilerAgent(config, session) {
  try {
    this._noInject = config.inject === false || config.inject.profiles === false;
  } catch (e) {
    this._noInject = false;
  }

  this._injected = false;
  this._debuggerClient = session.debuggerClient;
  this._injectorClient = session.injectorClient;
  this._frontendClient = session.frontendClient;
  this._heapProfilerClient = session.heapProfilerClient;

  this._translateCommandToInjection(
    'takeHeapSnapshot',
    'getObjectByHeapObjectId',
    'startTrackingHeapObjects',
    'stopTrackingHeapObjects'
  );

  if (!this._noInject) {
    this._injectorClient.on('inject', this._inject.bind(this));
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.HeapProfilerClient"></a>[module node-inspector.HeapProfilerClient](#apidoc.module.node-inspector.HeapProfilerClient)

#### <a name="apidoc.element.node-inspector.HeapProfilerClient.HeapProfilerClient"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>HeapProfilerClient (config, session)](#apidoc.element.node-inspector.HeapProfilerClient.HeapProfilerClient)
- description and source-code
```javascript
function HeapProfilerClient(config, session) {
  this._debuggerClient = session.debuggerClient;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.InjectorClient"></a>[module node-inspector.InjectorClient](#apidoc.module.node-inspector.InjectorClient)

#### <a name="apidoc.element.node-inspector.InjectorClient.InjectorClient"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>InjectorClient (config, session)](#apidoc.element.node-inspector.InjectorClient.InjectorClient)
- description and source-code
```javascript
function InjectorClient(config, session) {
  this._noInject = config.inject === false;
  this._injected = false;
  this._appPausedByInjector = false;

  this._debuggerClient = session.debuggerClient;
  this._frontendClient = session.frontendClient;
  this._debuggerClient.on('close', this.close.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.NetworkAgent"></a>[module node-inspector.NetworkAgent](#apidoc.module.node-inspector.NetworkAgent)

#### <a name="apidoc.element.node-inspector.NetworkAgent.NetworkAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>NetworkAgent (config, session)](#apidoc.element.node-inspector.NetworkAgent.NetworkAgent)
- description and source-code
```javascript
function NetworkAgent(config, session) {
  try {
    this._noInject = config.inject === false || config.inject.network === false;
  } catch (e) {
    this._noInject = false;
  }

  this._debuggerClient = session.debuggerClient;
  this._frontendClient = session.frontendClient;
  this._injectorClient = session.injectorClient;

  this._capturingEnabled = true;
  this._dataStorage = {};

  if (!this._noInject) this._injectorClient.on('inject', this._inject.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.PageAgent"></a>[module node-inspector.PageAgent](#apidoc.module.node-inspector.PageAgent)

#### <a name="apidoc.element.node-inspector.PageAgent.PageAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>PageAgent (config, session)](#apidoc.element.node-inspector.PageAgent.PageAgent)
- description and source-code
```javascript
function PageAgent(config, session) {
  this._session = session;
  this._debuggerClient = session.debuggerClient;
  this._scriptManager = session.scriptManager;
  this._scriptStorage = new ScriptFileStorage(config, session);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.ProfilerAgent"></a>[module node-inspector.ProfilerAgent](#apidoc.module.node-inspector.ProfilerAgent)

#### <a name="apidoc.element.node-inspector.ProfilerAgent.ProfilerAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>ProfilerAgent (config, session)](#apidoc.element.node-inspector.ProfilerAgent.ProfilerAgent)
- description and source-code
```javascript
function ProfilerAgent(config, session) {
  try {
    this._noInject = config.inject === false || config.inject.profiles === false;
  } catch (e) {
    this._noInject = false;
  }

  this._injected = false;
  this._debuggerClient = session.debuggerClient;
  this._injectorClient = session.injectorClient;
  this._frontendClient = session.frontendClient;

  this._translateCommandToInjection(
    'start',
    'stop'
  );

  if (!this._noInject) this._injectorClient.on('inject', this._inject.bind(this));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.RuntimeAgent"></a>[module node-inspector.RuntimeAgent](#apidoc.module.node-inspector.RuntimeAgent)

#### <a name="apidoc.element.node-inspector.RuntimeAgent.RuntimeAgent"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>RuntimeAgent (config, session)](#apidoc.element.node-inspector.RuntimeAgent.RuntimeAgent)
- description and source-code
```javascript
function RuntimeAgent(config, session) {
  this._debuggerClient = session.debuggerClient;
  this._frontendClient = session.frontendClient;
  this._consoleClient = session.consoleClient;
  this._heapProfilerClient = session.heapProfilerClient;
  this._callFramesProvider = new CallFramesProvider(config, session);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.ScriptFileStorage"></a>[module node-inspector.ScriptFileStorage](#apidoc.module.node-inspector.ScriptFileStorage)

#### <a name="apidoc.element.node-inspector.ScriptFileStorage.ScriptFileStorage"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>ScriptFileStorage (config, session)](#apidoc.element.node-inspector.ScriptFileStorage.ScriptFileStorage)
- description and source-code
```javascript
function ScriptFileStorage(config, session) {
  config = config || {};
  this._hidden = config.hidden;
  this._scriptManager = session.scriptManager;
  this._noPreload = config.preload === false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.ScriptManager"></a>[module node-inspector.ScriptManager](#apidoc.module.node-inspector.ScriptManager)

#### <a name="apidoc.element.node-inspector.ScriptManager.ScriptManager"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>ScriptManager (config, session)](#apidoc.element.node-inspector.ScriptManager.ScriptManager)
- description and source-code
```javascript
function ScriptManager(config, session) {
  config = config || {};
  var self = Object.create(ScriptManager.prototype, {
    _sources: { value: {}, writable: true },
    _hidden: { value: config.hidden || [] },
    _frontendClient: { value: session.frontendClient },
    _debuggerClient: { value: session.debuggerClient }
  });
  self._debuggerClient.on('afterCompile', self._onAfterCompile.bind(self));
  self._debuggerClient.on('compileError', self._onCompileError.bind(self));
  return self;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.callback"></a>[module node-inspector.callback](#apidoc.module.node-inspector.callback)

#### <a name="apidoc.element.node-inspector.callback.create"></a>[function <span class="apidocSignatureSpan">node-inspector.callback.</span>create ()](#apidoc.element.node-inspector.callback.create)
- description and source-code
```javascript
create = function () {
  var lastId = 1,
      callbacks = {};

  return Object.create({}, {
    wrap: {
      value: function(callback) {
        var callbackId = lastId++;
        callbacks[callbackId] = callback || function() {};
        return callbackId;
      }
    },
    processResponse: {
      value: function(callbackId, args) {
        var callback = callbacks[callbackId];

        if (callback) {
          callback.apply(null, args);
        }

        delete callbacks[callbackId];
      }
    },
    removeResponseCallbackEntry: {
      value: function(callbackId) {
        delete callbacks[callbackId];
      }
    }
  });
}
```
- example usage
```shell
...
 * @param {{hidden}} config
 * @param {FrontendClient} frontendClient
 * @param {DebuggerClient} debuggerClient
 * @constructor
 */
function ScriptManager(config, session) {
config = config || {};
var self = Object.create(ScriptManager.prototype, {
  _sources: { value: {}, writable: true },
  _hidden: { value: config.hidden || [] },
  _frontendClient: { value: session.frontendClient },
  _debuggerClient: { value: session.debuggerClient }
});
self._debuggerClient.on('afterCompile', self._onAfterCompile.bind(self));
self._debuggerClient.on('compileError', self._onCompileError.bind(self));
...
```



# <a name="apidoc.module.node-inspector.config"></a>[module node-inspector.config](#apidoc.module.node-inspector.config)

#### <a name="apidoc.element.node-inspector.config.config"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>config (argv, NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config.config)
- description and source-code
```javascript
function Config(argv, NODE_DEBUG_MODE) {
  var defaults = collectDefaultsFromDefinitions(NODE_DEBUG_MODE);
  var parsedArgv = parseArgs(argv);

  checkDeprecatedHiddenStyle(parsedArgv);

  var rcConfig = rc('node-inspector', defaults, parsedArgv);
  var config = normalizeOptions(rcConfig);

  checkDeprecatedNoPreloadStyle(config);
  checkDeprecatedWebHostStyle(config);

  util._extend(this, config);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config._collectDefaults"></a>[function <span class="apidocSignatureSpan">node-inspector.config.</span>_collectDefaults (NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config._collectDefaults)
- description and source-code
```javascript
_collectDefaults = function (NODE_DEBUG_MODE) {
  var dashedKeyDefaults = collectDefaultsFromDefinitions(NODE_DEBUG_MODE);
  return normalizeOptions(dashedKeyDefaults);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config.filterDefaultValues"></a>[function <span class="apidocSignatureSpan">node-inspector.config.</span>filterDefaultValues ()](#apidoc.element.node-inspector.config.filterDefaultValues)
- description and source-code
```javascript
filterDefaultValues = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config.filterNodeDebugOptions"></a>[function <span class="apidocSignatureSpan">node-inspector.config.</span>filterNodeDebugOptions ()](#apidoc.element.node-inspector.config.filterNodeDebugOptions)
- description and source-code
```javascript
filterNodeDebugOptions = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config.filterOptions"></a>[function <span class="apidocSignatureSpan">node-inspector.config.</span>filterOptions (filterExpression, options)](#apidoc.element.node-inspector.config.filterOptions)
- description and source-code
```javascript
filterOptions = function (filterExpression, options) {
  var filteredOptions = {};

  Object.keys(options)
    .filter(function(key) {
      var value = options[key];
      var dashedKey = keyToDashedKey(key);
      var definition = definitions[dashedKey];
      return filterExpression(key, value, definition);
    })
    .forEach(function(key) {
      filteredOptions[key] = options[key];
    });

  return filteredOptions;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config.serializeOptions"></a>[function <span class="apidocSignatureSpan">node-inspector.config.</span>serializeOptions (options, filter)](#apidoc.element.node-inspector.config.serializeOptions)
- description and source-code
```javascript
serializeOptions = function (options, filter) {
  filter = filter || {};
  var result = [];
  Object.keys(options).forEach(function(key) {
    if (filter[key]) return;

    var serializedOption = serializeOption(keyToDashedKey(key), options[key]);
    if (serializedOption !== '')
      result.unshift.apply(result, [].concat(serializedOption));
  });
  return result;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.config.prototype"></a>[module node-inspector.config.prototype](#apidoc.module.node-inspector.config.prototype)

#### <a name="apidoc.element.node-inspector.config.prototype.showHelp"></a>[function <span class="apidocSignatureSpan">node-inspector.config.prototype.</span>showHelp (NODE_DEBUG_MODE)](#apidoc.element.node-inspector.config.prototype.showHelp)
- description and source-code
```javascript
showHelp = function (NODE_DEBUG_MODE) {
  var cmd = getCmd();

  var inspectorOptions = [];
  var nodeDebugOptions = [];
  Object.keys(definitions).forEach(function(key) {
    if (definitions[key]._isNodeDebugOption && NODE_DEBUG_MODE) {
      nodeDebugOptions.push(key);
    } else if (definitions[key]._isNodeInspectorOption) {
      inspectorOptions.push(key);
    }
  }, this);

  var inspectorPart = color('green', '[node-inspector-options]');
  var optionsPart = color('cyan', '[options]');
  var scriptPart = color('red', '[script [script-arguments]]');
  var configurationParts = [inspectorPart];
  if (NODE_DEBUG_MODE) {
    configurationParts.unshift(optionsPart);
    configurationParts.push(scriptPart);
  }

  if (typeof this.help == 'string') {
    //Display help for target option
    showOptionHelp(this.help);
  } else if (this.l) {
    //Display options format and options usage info
    console.log('Usage:\n    %s %s\n', cmd, configurationParts.join(' '));
    if (NODE_DEBUG_MODE) {
      nodeDebugOptions.forEach(showOptionHelp);
    }
    inspectorOptions.forEach(showOptionHelp);
  } else {
    //Display options format, options list and some help information
    console.log(
        'Usage:\n    %s %s\n', cmd, configurationParts.join(' '));

    if (NODE_DEBUG_MODE) {
      console.log(
        'Where %s is one or more of:\n' +
        '    %s\n', optionsPart, nodeDebugOptions.join('\n    '));
    }
    console.log(
        'Where %s is one or more of:\n' +
        '    %s\n', inspectorPart, inspectorOptions.join('\n    '));
    console.log('Use:' + formatUsage(definitions.help.usage) + '\n');

    if (NODE_DEBUG_MODE) {
      console.log(
        'The %s argument is resolved relative to the current working\n' +
        'directory. If no such file exists, then env.PATH is searched.\n',
        color('red', '[script]'));
      console.log(
        'The default mode is to break on the first line of the script, to run\n' +
        'immediately on start use '--no-debug-brk' or press the Resume button.\n');
      console.log(
        'When there is no script specified, the module in the current working\n' +
        'directory is loaded in the REPL session as 'm'. This allows you to call\n' +
        'and debug arbitrary functions exported by the current module.\n');
    }

    console.log(
        'Configuration can be also stored in a \'.node-inspectorrc\' file,\n' +
        'see README for more details:\n' +
        '  https://github.com/node-inspector/node-inspector#configuration');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.config.prototype.showVersion"></a>[function <span class="apidocSignatureSpan">node-inspector.config.prototype.</span>showVersion ()](#apidoc.element.node-inspector.config.prototype.showVersion)
- description and source-code
```javascript
showVersion = function () {
  console.log('Node Inspector v' + require('../package.json').version);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.convert"></a>[module node-inspector.convert](#apidoc.module.node-inspector.convert)

#### <a name="apidoc.element.node-inspector.convert.inspectorScriptIdToV8Id"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorScriptIdToV8Id (scriptId)](#apidoc.element.node-inspector.convert.inspectorScriptIdToV8Id)
- description and source-code
```javascript
inspectorScriptIdToV8Id = function (scriptId) {
  return Number(scriptId);
}
```
- example usage
```shell
...
  stepOut: function(params, done) {
this._sendContinue('out', done);
  },

  continueToLocation: function(params, done) {
var requestParams = {
  type: 'scriptId',
  target: convert.inspectorScriptIdToV8Id(params.location.scriptId),
  line: params.location.lineNumber,
  column: params.location.columnNumber
};

this._debuggerClient.request('setbreakpoint', requestParams, function(error, response) {
  if (error != null) {
    done(error);
...
```

#### <a name="apidoc.element.node-inspector.convert.inspectorUrlToV8Name"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorUrlToV8Name (url, normalize)](#apidoc.element.node-inspector.convert.inspectorUrlToV8Name)
- description and source-code
```javascript
inspectorUrlToV8Name = function (url, normalize) {
  var path = normalize(url).replace(/^file:\/\//, '');
  if (/^\/[a-zA-Z]:\//.test(path))
    return path.substring(1).replace(/\//g, '\\'); // Windows disk path
  if (/^\//.test(path))
    return path; // UNIX-style
  if (/^file:\/\//.test(url))
    return '\\\\' + path.replace(/\//g, '\\'); // Windows UNC path

  return url;
}
```
- example usage
```shell
...
if (params.urlRegex !== undefined) {
  // DevTools protocol defines urlRegex parameter,
  // but the parameter is not used by the front-end.
  done('Error: setBreakpointByUrl using urlRegex is not implemented.');
  return;
}

var target = convert.inspectorUrlToV8Name(params.url,
  this._scriptManager.normalizeName.bind(this._scriptManager));

var requestParams = {
  type: 'script',
  target: target,
  line: params.lineNumber,
  column: params.columnNumber,
...
```

#### <a name="apidoc.element.node-inspector.convert.inspectorValueToV8Value"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>inspectorValueToV8Value (value)](#apidoc.element.node-inspector.convert.inspectorValueToV8Value)
- description and source-code
```javascript
inspectorValueToV8Value = function (value) {
  if (value.value === undefined && value.objectId === undefined)
    return { type: 'undefined' };
  if (value.objectId) {
    return { handle: Number(value.objectId) };
  }
  return value;
}
```
- example usage
```shell
...
    ' or newer.');
} else {
  this._doSetVariableValue(params, done);
}
  },

  _doSetVariableValue: function(params, done) {
var value = convert.inspectorValueToV8Value(params.newValue);

this._debuggerClient.request(
  'setVariableValue',
  {
    name: params.variableName,
    scope: {
      number: Number(params.scopeNumber),
...
```

#### <a name="apidoc.element.node-inspector.convert.v8ErrorToInspectorError"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ErrorToInspectorError (message)](#apidoc.element.node-inspector.convert.v8ErrorToInspectorError)
- description and source-code
```javascript
v8ErrorToInspectorError = function (message) {
  var nameMatch = /^([^:]+):/.exec(message);

  return {
    type: 'object',
    objectId: 'ERROR',
    className: nameMatch ? nameMatch[1] : 'Error',
    description: message
  };
}
```
- example usage
```shell
...
{
  expression: params.expression,
  frame: frame
},
function(err, result) {
  // Errors from V8 are actually just messages, so we need to fill them out a bit.
  if (err) {
    err = convert.v8ErrorToInspectorError(err);
  }

  done(null, {
    result: err || convert.v8ResultToInspectorResult(result),
    wasThrown: !!err
  });
}
...
```

#### <a name="apidoc.element.node-inspector.convert.v8FunctionLookupToFunctionDetails"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8FunctionLookupToFunctionDetails (handleData)](#apidoc.element.node-inspector.convert.v8FunctionLookupToFunctionDetails)
- description and source-code
```javascript
v8FunctionLookupToFunctionDetails = function (handleData) {
  return {
    details: {
      location: {
        scriptId: String(handleData.scriptId),
        lineNumber: handleData.line,
        columnNumber: handleData.column
      },
      name: handleData.name || handleData.inferredName,

      // There is a list of scope ids in responseBody.scopes, but not scope
      // details :( // We need to issue 'scopes' request to fetch scopes
      // details, but we don't have frame number where the function was defined.
      // Let's leave the scopeChain empty for now.
      scopeChain: []
    }
  };
}
```
- example usage
```shell
...

  getFunctionDetails: function(params, done) {
var handle = params.functionId;
var callback = function(error, responseBody) {
  if (error) {
    done(error);
  } else {
    done(null, convert.v8FunctionLookupToFunctionDetails(responseBody[handle] || responseBody));
  }
}.bind(this);

if (this._consoleClient.isConsoleId(handle)) {
  this._getFunctionDetailsOfConsoleId(handle, callback);
} else if (this._heapProfilerClient.isHeapObjectId(handle)) {
  this._getFunctionDetailsOfHeapObjectId(handle, callback);
...
```

#### <a name="apidoc.element.node-inspector.convert.v8LocationToInspectorLocation"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8LocationToInspectorLocation (v8loc)](#apidoc.element.node-inspector.convert.v8LocationToInspectorLocation)
- description and source-code
```javascript
v8LocationToInspectorLocation = function (v8loc) {
  return {
    scriptId: v8loc.script_id.toString(),
    lineNumber: v8loc.line,
    columnNumber: v8loc.column
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.convert.v8NameToInspectorUrl"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8NameToInspectorUrl (v8name)](#apidoc.element.node-inspector.convert.v8NameToInspectorUrl)
- description and source-code
```javascript
v8NameToInspectorUrl = function (v8name) {
  if (!v8name || v8name === 'repl') {
    // Call to 'evaluate' from user-land creates a new script with undefined URL.
    // REPL has null main script file and calls 'evaluate' with 'repl'
    // as the file name.
    //
    // When we send an empty string as URL, front-end opens the source
    // as VM-only script (named "[VM] {script-id}").
    //
    // The empty name of the main script file is displayed as "(program)".
    return '';
  }

  if (/^\//.test(v8name)) {
    return 'file://' + v8name;
  } else if (/^[a-zA-Z]:\\/.test(v8name)) {
    return 'file:///' + v8name.replace(/\\/g, '/');
  } else if (/^\\\\/.test(v8name)) {
    return 'file://' + v8name.substring(2).replace(/\\/g, '/');
  }

  return v8name;
}
```
- example usage
```shell
...
  done
);
  },

  _createResourceTreeResponse: function(target, mainAppScript, scriptFiles, done) {
var resources = scriptFiles.map(function(filePath) {
  return {
    url: convert.v8NameToInspectorUrl(filePath),
    type: 'Script',
    mimeType: 'text/javascript'
  };
});

done(null, {
  frameTree: {
...
```

#### <a name="apidoc.element.node-inspector.convert.v8ObjectToInspectorProperties"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ObjectToInspectorProperties (obj, refs, options)](#apidoc.element.node-inspector.convert.v8ObjectToInspectorProperties)
- description and source-code
```javascript
v8ObjectToInspectorProperties = function (obj, refs, options) {
  var proto = obj.protoObject,
      props = obj.properties || [],
      ownProperties = options.ownProperties,
      accessorPropertiesOnly = options.accessorPropertiesOnly;

  props = props.map(function(prop) {
    var ref = refs[prop.ref];
    var inspectorProperty = {
        name: String(prop.name),
        writable: !(prop.attributes & 1 << 0),
        enumerable: !(prop.attributes & 1 << 1),
        configurable: !(prop.attributes & 1 << 2),
        value: exports.v8ResultToInspectorResult(ref)
      };
    return inspectorProperty;
  });

  if (ownProperties && proto) {
    proto = refs[proto.ref];
    if (proto.type !== 'undefined') {
      props.push({
        name: '__proto__',
        value: exports.v8RefToInspectorObject(proto),
        writable: true,
        configurable: true,
        enumerable: false,
        isOwn: true
      });
    }
  }

  props = props.filter(function(prop) {
<span class="apidocCodeCommentSpan">  /*
    Node.js does not return get/set property descriptors now (v0.11.11),
      therefore we can't fully implement 'accessorPropertiesOnly'.
    See https://github.com/joyent/node/issues/7139
  */
</span>    var isAccessorProperty = ('get' in prop || 'set' in prop);

    return accessorPropertiesOnly ? isAccessorProperty : !isAccessorProperty;
  });

  return props;
}
```
- example usage
```shell
...
    request,
    function(error, responseBody, responseRefs) {
      if (error) {
        done(error);
        return;
      }
      var obj = responseBody[handle],
          props = convert.v8ObjectToInspectorProperties(obj, responseRefs, options);

      done(null, { result: props });
    }
  );
},

_getPropertiesOfConsoleId: function(objectId, options, done) {
...
```

#### <a name="apidoc.element.node-inspector.convert.v8RefToInspectorObject"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8RefToInspectorObject (ref)](#apidoc.element.node-inspector.convert.v8RefToInspectorObject)
- description and source-code
```javascript
v8RefToInspectorObject = function (ref) {
  var desc = '',
      type = ref.type,
      subtype,
      size,
      name,
      objectId,
      inspectorResult;

  switch (type) {
    case 'object':
      name = /#<(\w+)>/.exec(ref.text);
      if (name && name.length > 1) {
        desc = name[1];
        if (desc === 'Array' || desc === 'Buffer') {
          size = ref.properties.filter(function(p) { return /^\d+$/.test(p.name);}).length;
          desc += '[' + size + ']';
          subtype = 'array';
        }
      } else if (ref.className === 'Date') {
        desc = new Date(ref.value || NaN).toString();
        subtype = 'date';
      } else {
        desc = ref.className || 'Object';
      }
      break;
    case 'regexp':
      type = 'object';
      subtype = 'regexp';
      desc = ref.text || '';
<span class="apidocCodeCommentSpan">      /*
        We need to collect RegExp flags and append they to description,
        or open issue in NodeJS same as 'RegExp text serialized without flags'
      */
</span>      break;
    case 'function':
      desc = ref.text || 'function()';
      break;
    case 'error':
      type = 'object';
      desc = ref.text || 'Error';
      break;
    default:
      desc = ref.text || '';
      break;
  }
  if (desc.length > 100) {
    desc = desc.substring(0, 100) + '\u2026';
  }

  objectId = ref.handle;
  if (objectId === undefined)
    objectId = ref.ref;

  inspectorResult = {
    type: type,
    subtype: subtype,
    objectId: String(objectId),
    className: ref.className,
    description: desc
  };

  return inspectorResult;
}
```
- example usage
```shell
...
    if (error) return cb(error);

    this._frontendClient.sendEvent(
      'Debugger.paused',
      {
        callFrames: result,
        reason: exception ? 'exception' : 'other',
        data: exception ? convert.v8RefToInspectorObject(exception) : null,
        hitBreakpoints: hitBreakpoints
      });

    cb(null);
  }.bind(this));
};
...
```

#### <a name="apidoc.element.node-inspector.convert.v8ResultToInspectorResult"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ResultToInspectorResult (result)](#apidoc.element.node-inspector.convert.v8ResultToInspectorResult)
- description and source-code
```javascript
v8ResultToInspectorResult = function (result) {
  var subtype,
      inspectorResult;
  if (['object', 'function', 'regexp', 'error'].indexOf(result.type) > -1) {
    return exports.v8RefToInspectorObject(result);
  }

  if (result.type == 'null') {
    // workaround for the problem with front-end's setVariableValue
    // implementation not preserving null type
    result.value = null;
    subtype = 'null';
  }

  inspectorResult = {
    type: result.type,
    subtype: subtype,
    value: result.value,
    description: String(result.value)
  };

  return inspectorResult;
}
```
- example usage
```shell
...
ConsoleAgent.prototype._translateEventToFrontend = function(eventNames) {
  Array.prototype.forEach.call(arguments, function(event) {
    event = 'Console.' + event;
    this._debuggerClient.on(event, function(message) {
      if (event == 'Console.messageAdded') {
        message.message.parameters = message.message.parameters.map(function(ref) {
          this._consoleClient.convertHandleToConsoleHandle(ref, message.message.id);
          return convert.v8ResultToInspectorResult(ref);
        }, this);
      }
      this._frontendClient.sendEvent(event, message);
    }.bind(this));
  }, this);
};
...
```

#### <a name="apidoc.element.node-inspector.convert.v8ScopeTypeToString"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ScopeTypeToString (v8ScopeType)](#apidoc.element.node-inspector.convert.v8ScopeTypeToString)
- description and source-code
```javascript
v8ScopeTypeToString = function (v8ScopeType) {
  switch (v8ScopeType) {
    case 0:
      return 'global';
    case 1:
      return 'local';
    case 2:
      return 'with';
    case 3:
      return 'closure';
    case 4:
      return 'catch';
    default:
      return 'unknown';
  }
}
```
- example usage
```shell
...
  return {
    object: {
      type: 'object',
      objectId: 'scope:' + frame.index + ':' + scope.index,
      className: 'Object',
      description: 'Object'
    },
    type: convert.v8ScopeTypeToString(scope.type)
  };
});

done(null, {
  callFrameId: frame.index.toString(),
  functionName: frame.func.inferredName || frame.func.name,
  location: {
...
```

#### <a name="apidoc.element.node-inspector.convert.v8ScriptIdToInspectorId"></a>[function <span class="apidocSignatureSpan">node-inspector.convert.</span>v8ScriptIdToInspectorId (scriptId)](#apidoc.element.node-inspector.convert.v8ScriptIdToInspectorId)
- description and source-code
```javascript
v8ScriptIdToInspectorId = function (scriptId) {
  return String(scriptId);
}
```
- example usage
```shell
...
    };
  });

  done(null, {
    callFrameId: frame.index.toString(),
    functionName: frame.func.inferredName || frame.func.name,
    location: {
      scriptId: convert.v8ScriptIdToInspectorId(frame.func.scriptId),
      lineNumber: frame.line,
      columnNumber: frame.column
    },
    scopeChain: scopeChain,
    this: convert.v8RefToInspectorObject(frame.receiver)
  });
},
...
```



# <a name="apidoc.module.node-inspector.debug_server"></a>[module node-inspector.debug_server](#apidoc.module.node-inspector.debug_server)

#### <a name="apidoc.element.node-inspector.debug_server.DebugServer"></a>[function <span class="apidocSignatureSpan">node-inspector.debug_server.</span>DebugServer ()](#apidoc.element.node-inspector.debug_server.DebugServer)
- description and source-code
```javascript
function DebugServer() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.debugger"></a>[module node-inspector.debugger](#apidoc.module.node-inspector.debugger)

#### <a name="apidoc.element.node-inspector.debugger.attachDebugger"></a>[function <span class="apidocSignatureSpan">node-inspector.debugger.</span>attachDebugger (port)](#apidoc.element.node-inspector.debugger.attachDebugger)
- description and source-code
```javascript
attachDebugger = function (port) {
  return new Debugger(port);
}
```
- example usage
```shell
...
    get: function() {
      return this._conn.connected && !!this.target;
    }
  }
});

DebuggerClient.prototype.connect = function() {
  this._conn = DebugConnection.attachDebugger(this._port);

  this._conn
    .on('connect', this._onConnectionOpen.bind(this))
    .on('error', this.emit.bind(this, 'error'))
    .on('close', this._onConnectionClose.bind(this))
    .on('event', function(obj) { this.emit(obj.event, obj.body); }.bind(this));
};
...
```



# <a name="apidoc.module.node-inspector.plugins"></a>[module node-inspector.plugins](#apidoc.module.node-inspector.plugins)

#### <a name="apidoc.element.node-inspector.plugins.InspectorJson"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>InspectorJson (config)](#apidoc.element.node-inspector.plugins.InspectorJson)
- description and source-code
```javascript
function InspectorJson(config) {
  var inspectorJsonPath = path.join(__dirname, '../front-end/inspector.json'),
      inspectorJson = JSON.parse(fs.readFileSync(inspectorJsonPath)),
      extendedInspectorJsonPath = path.join(__dirname, '../front-end-node/inspector.json'),
      extendedInspectorJson = JSON.parse(fs.readFileSync(extendedInspectorJsonPath));

  this._config = config;
  this._notes = inspectorJson;

  this._merge(extendedInspectorJson);

  if (!config.plugins) return;

  var plugins = getPlugins(config);

  plugins.forEach(function(plugin) {
    var excludes = (plugin.exclude || []).map(function(name) {
      return { name: name, type: 'exclude' };
    });

    var overrides = plugin.override || [];

    var note = {
      name: 'plugins/' + plugin.name,
      type: plugin.type || ''
    };

    var notes = excludes.concat(overrides).concat(note);

    this._merge(notes);
  }, this);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins.PluginError"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>PluginError (message)](#apidoc.element.node-inspector.plugins.PluginError)
- description and source-code
```javascript
function PluginError(message) {
  this.name = 'Plugin Error';
  this.message = this.name + ':\n' + message;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins.ProtocolJson"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>ProtocolJson (config)](#apidoc.element.node-inspector.plugins.ProtocolJson)
- description and source-code
```javascript
function ProtocolJson(config) {
  var protocolJsonPath = path.join(__dirname, '../tools/protocol.json'),
      protocolJson = JSON.parse(fs.readFileSync(protocolJsonPath)),
      extendedProtocolJsonPath = path.join(__dirname, '../front-end-node/protocol.json'),
      extendedProtocolJson = JSON.parse(fs.readFileSync(extendedProtocolJsonPath));

  this._config = config;
  this._protocol = protocolJson;
  this._domains = protocolJson.domains;
  this._extendedDomains = extendedProtocolJson.domains;

  if (config.plugins) {
    var plugins = getPlugins(config);
    // At first step we merge all plugins in one protocol.
    // We expect what plugins doesn't have equal methods, events or types,
    // otherwise we throw an error, because this is unsolvable situation.
    plugins.forEach(function(plugin) {
      this._merge(THROW_CONFLICTS, plugin.name, this._extendedDomains, plugin.protocol.domains);
    }, this);
  }

  // At second step we merge plugins with main protocol.
  // Plugins can override original methods, events or types,
  // so we don't need to throw error on conflict, we only print a warning to console.
  this._merge(!THROW_CONFLICTS, '', this._domains, this._extendedDomains);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins._setMockPlugins"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>_setMockPlugins (pluginPath, plugins)](#apidoc.element.node-inspector.plugins._setMockPlugins)
- description and source-code
```javascript
function _setMockPlugins(pluginPath, plugins) {
  cachedPlugins[pluginPath] = plugins;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins.getPluginPath"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>getPluginPath (config)](#apidoc.element.node-inspector.plugins.getPluginPath)
- description and source-code
```javascript
function getPluginPath(config) {
  return (config && config.pluginPath) || path.join(__dirname, '../plugins');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins.getPlugins"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>getPlugins (config)](#apidoc.element.node-inspector.plugins.getPlugins)
- description and source-code
```javascript
function getPlugins(config) {
  if (!config || !config.plugins) {
    return [];
  }

  var pluginPath = getPluginPath(config);
  if (cachedPlugins[pluginPath])  {
    return cachedPlugins[pluginPath];
  }

  var dirlist;

  try {
    dirlist = fs.readdirSync(pluginPath);
  } catch (err) {
    dirlist = [];
  }

  var plugins = [];

  dirlist.reduce(function(plugins, subdir) {
    var _path = path.resolve(pluginPath, subdir, 'manifest.json');
    var manifest;

    try {
      manifest = require(_path);

      // This excludes situation where we have two plugins with same name.
      if (subdir !== manifest.name)
        throw new PluginError('Plugin name in manifest.json is different from npm module name');
    } catch (e) {
      console.error('Corrupted manifest.json in %s plugin\n%s\n%s', subdir, e.message, e.stack);
      return plugins;
    }

    validateManifest(manifest);
    plugins.push(manifest);
    return plugins;
  }, plugins);

  cachedPlugins[pluginPath] = plugins;
  return plugins;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.plugins.init"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>init (config)](#apidoc.element.node-inspector.plugins.init)
- description and source-code
```javascript
function init(config) {
  module.exports.CWD = getPluginPath(config);
}
```
- example usage
```shell
...

inherits(DebugServer, EventEmitter);

DebugServer.prototype.start = function(options) {
this._config = extend({}, options);
this._isHTTPS = this._config.sslKey && this._config.sslCert ? true : false;

plugins.init(this._config);

this._inspectorJson = new InspectorJson(this._config);
this._protocolJson = new ProtocolJson(this._config);

var PLUGINS = plugins.CWD;

var app = express();
...
```

#### <a name="apidoc.element.node-inspector.plugins.validateManifest"></a>[function <span class="apidocSignatureSpan">node-inspector.plugins.</span>validateManifest (manifest)](#apidoc.element.node-inspector.plugins.validateManifest)
- description and source-code
```javascript
function validateManifest(manifest) {
  manifest.session = manifest.session || {};
  manifest.protocol = manifest.protocol || {};
  manifest.protocol.domains = manifest.protocol.domains || [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.session"></a>[module node-inspector.session](#apidoc.module.node-inspector.session)

#### <a name="apidoc.element.node-inspector.session.session"></a>[function <span class="apidocSignatureSpan">node-inspector.</span>session (config, debuggerPort, wsConnection)](#apidoc.element.node-inspector.session.session)
- description and source-code
```javascript
function Session(config, debuggerPort, wsConnection) {
  this.debuggerClient = new DebuggerClient(debuggerPort);
  this.frontendClient = new FrontendClient(wsConnection);
  this.injectorClient = new InjectorClient(config, this);
  this.consoleClient = new ConsoleClient(config, this);
  this.heapProfilerClient = new HeapProfilerClient(config, this);
  this.scriptManager = new ScriptManager(config, this);
  this.breakEventHandler = new BreakEventHandler(config, this);
  this.frontendCommandHandler = new FrontendCommandHandler(config, this);

  this.resourceTreeResolved = false;
  this.once('resource-tree-resolved', function() {
    this.resourceTreeResolved = true;
  }.bind(this));

  this.frontendClient.on('close', this.close.bind(this));
  this.debuggerClient.on('close', this._onDebuggerClientClose.bind(this));
  this.debuggerClient.on('error', this._onDebuggerClientError.bind(this));

  this._pingInterval = setInterval(function() {
    wsConnection.ping(null, null, true);
  }.bind(this), 1000);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.session.super_"></a>[function <span class="apidocSignatureSpan">node-inspector.session.</span>super_ ()](#apidoc.element.node-inspector.session.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.node-inspector.session.prototype"></a>[module node-inspector.session.prototype](#apidoc.module.node-inspector.session.prototype)

#### <a name="apidoc.element.node-inspector.session.prototype._onDebuggerClientClose"></a>[function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>_onDebuggerClientClose (reason)](#apidoc.element.node-inspector.session.prototype._onDebuggerClientClose)
- description and source-code
```javascript
_onDebuggerClientClose = function (reason) {
  if (this.frontendClient.isConnected)
    this.frontendClient.sendInspectorDetached(reason);
  this.close();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.session.prototype._onDebuggerClientError"></a>[function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>_onDebuggerClientError (e)](#apidoc.element.node-inspector.session.prototype._onDebuggerClientError)
- description and source-code
```javascript
_onDebuggerClientError = function (e) {
  var err = e.toString();
  if (e.helpString) {
    err += '\n' + e.helpString;
  }
  this.frontendClient.sendLogToConsole('error', err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.node-inspector.session.prototype.close"></a>[function <span class="apidocSignatureSpan">node-inspector.session.prototype.</span>close ()](#apidoc.element.node-inspector.session.prototype.close)
- description and source-code
```javascript
close = function () {
  clearInterval(this._pingInterval);
  if (this.debuggerClient.isConnected)
    this.debuggerClient.close();
  else
    this.emit('close');
}
```
- example usage
```shell
...
 });
};

/**
*/
DebuggerClient.prototype.close = function() {
 if (this.isConnected)
   this._conn.close();
 else
   this.emit('close');
};

/**
* @param {number} breakpointId
* @param {function(error, response, refs)} done
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
