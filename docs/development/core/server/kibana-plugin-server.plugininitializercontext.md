[Home](./index) &gt; [kibana-plugin-server](./kibana-plugin-server.md) &gt; [PluginInitializerContext](./kibana-plugin-server.plugininitializercontext.md)

## PluginInitializerContext interface

Context that's available to plugins during initialization stage.

<b>Signature:</b>

```typescript
export interface PluginInitializerContext 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [config](./kibana-plugin-server.plugininitializercontext.config.md) | <code>{`<p/>`        create: &lt;Schema extends Type&lt;any&gt;, Config&gt;(ConfigClass: ConfigWithSchema&lt;Schema, Config&gt;) =&gt; Observable&lt;Config&gt;;`<p/>`        createIfExists: &lt;Schema extends Type&lt;any&gt;, Config&gt;(ConfigClass: ConfigWithSchema&lt;Schema, Config&gt;) =&gt; Observable&lt;Config &#124; undefined&gt;;`<p/>`    }</code> |  |
|  [env](./kibana-plugin-server.plugininitializercontext.env.md) | <code>{`<p/>`        mode: EnvironmentMode;`<p/>`    }</code> |  |
|  [logger](./kibana-plugin-server.plugininitializercontext.logger.md) | <code>LoggerFactory</code> |  |

