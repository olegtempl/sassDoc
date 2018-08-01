<a name="navigation"></a>


## Navigation:
  - [@access](#access)
  - [@alias](#alias)
  - [@author](#author)
  - [@content](#content)
  - [@deprecated](#deprecated)
  - [@example](#example)
  - [@group](#group)
  - [@ignore](#ignore)
  - [@link](#link)
  - [@name](#name)
  - [@access](#access)
  - [@todo](#todo)
  - [@throw](#throw)
  - [@since](#since)
  - [@see](#see)
  - [@return](#return)
  - [@require](#require)
  - [@property](#property)
  - [@parameter](#parameter)
  - [@output](#output)
  - [@type](#type)

## API for documentation with [sassDoc](http://sassdoc.com)

<table>
  <thead>
    <tr>
      <th>Annotation</th>
      <th>Description</th>
      <th>Aliases</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="#comment-range">Comment range</a></td>
      <td>Comment range</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#description">Description</a></td>
      <td>Description of the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#access">@access</a></td>
      <td>Access of the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#alias">@alias</a></td>
      <td>Whether the documented item is an alias of another item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#author">@author</a></td>
      <td>Author of the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#content">@content</a></td>
      <td>Whether the documented mixin uses the <code >@content</code> directive</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#deprecated">@deprecated</a></td>
      <td>Whether the documented item is deprecated</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#example">@example</a></td>
      <td>Example for the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#group">@group</a></td>
      <td>Group the documented item belongs to</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#ignore">@ignore</a></td>
      <td>Ignored content</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#link">@link</a></td>
      <td>Link related to the documented item</td>
      <td>@source</td>
    </tr>
    <tr>
      <td><a href="#name">@name</a></td>
      <td>Name of the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#output">@output</a></td>
      <td>Output from the documented mixin</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#parameter">@parameter</a></td>
      <td>Parameters from the documented mixin or function</td>
      <td>@param, @arg, @argument</td>
    </tr>
    <tr>
      <td><a href="#property">@property</a></td>
      <td>Property of the documented map</td>
      <td>@prop</td>
    </tr>
    <tr>
      <td><a href="#require">@require</a></td>
      <td>Requirements from the documented item</td>
      <td>@requires</td>
    </tr>
    <tr>
      <td><a href="#return">@return</a></td>
      <td>Return from the documented function</td>
      <td>@returns</td>
    </tr>
    <tr>
      <td><a href="#see">@see</a></td>
      <td>Resource related to the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#since">@since</a></td>
      <td>Changelog for the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#throw">@throw</a></td>
      <td>Exceptions raised by the documented item</td>
      <td>@throws, @exception</td>
    </tr>
    <tr>
      <td><a href="#todo">@todo</a></td>
      <td>Things to do related to the documented item</td>
      <td>—</td>
    </tr>
    <tr>
      <td><a href="#type">@type</a></td>
      <td>Describes the type of a variable</td>
      <td>—</td>
    </tr>
  </tbody>
</table>

<a name="access"></a>

**[⬆ back to top](#navigation)**

## @access

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines the access of the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td><code >public</code></td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Either <code >public</code> or <code >private</code>.</td>
    </tr>
  </tbody>
</table>

<a name="alias"></a>

**[⬆ back to top](#navigation)**

## @alias


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines if the documented item is an alias of another item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>The other item will automatically have a key named <code >aliased</code> containing the name of aliases.</td>
    </tr>
  </tbody>
</table>

<a name="author"></a>

**[⬆ back to top](#navigation)**

## @author


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes the author of the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="content"></a>

**[⬆ back to top](#navigation)**

## @content


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes the usage of <code >@content</code> Sass directive in the documented mixin</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>mixins</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="deprecated"></a>

**[⬆ back to top](#navigation)**

## @deprecated

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines if the documented item is deprecated</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*<br />Message is optional.</td>
    </tr>
  </tbody>
</table>

<a name="example"></a>

**[⬆ back to top](#navigation)**

## @example


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes a use case for the documented item, with a given language and description if specified</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Lines starting with <code >@</code> need to be indented to work correctly.<br />First word on the same line as <code >@example</code> is the language for syntax highlighting.<br />Currently supported languages: <code >css</code>, <code >scss</code>, <code >markup</code>, <code >javascript</code>. New languages on demand.<br />Everything but the first word on the same line as <code >@example</code> is the description.<br />Hyphen before description is optional.<br />Description is parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="group"></a>

**[⬆ back to top](#navigation)**

## @group

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines to which group (if any) the documented item belongs</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td><code >undefined</code></td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Groups define the way items are displayed in SassDoc’s default theme.<br />Groups can be aliased for friendly names from the configuration (<a href="/configuration/#groups">more infos</a>).</td>
    </tr>
  </tbody>
</table>

<a name="ignore"></a>

**[⬆ back to top](#navigation)**

## @ignore

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines a line which won’t be documented</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>—</td>
    </tr>
  </tbody>
</table>

<a name="link"></a>

**[⬆ back to top](#navigation)**

## @link


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes a link</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@source</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Caption is optional.</td>
    </tr>
  </tbody>
</table>

<a name="name"></a>

**[⬆ back to top](#navigation)**

## @name


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Provide a custom name for the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td><code >item.context.name</code></td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Only useful when wanting to override the self parsed name.</td>
    </tr>
  </tbody>
</table>

<a name="output"></a>

**[⬆ back to top](#navigation)**

## @output


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Provide a description of what’s being printed by the mixin</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@outputs</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>mixins</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="parameter"></a>

**[⬆ back to top](#navigation)**

## @parameter

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes a parameter of the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@arg</code>, <code >@argument</code>, <code >@param</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Default value is optional.<br />Description is optional. Hyphen before description is optional.<br />Description is parsed as Markdown.*<br />Multiple types should be separated by pipes (<code >|</code>).</td>
    </tr>
  </tbody>
</table>

<a name="property"></a>

**[⬆ back to top](#navigation)**

## @property

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Document maps properties, use the dot notation to signify nesting</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@prop</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Description is parsed as Markdown.*<br />If <code >{Type}</code> is omitted, it will default to <code >Map</code> to make it more convenient for nested maps.</td>
    </tr>
  </tbody>
</table>

<a name="require"></a>

**[⬆ back to top](#navigation)**

## @require

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines if the documented item requires any other item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@requires</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Type is optional; default type is <code >function</code>. Can be either <code >function</code>, <code >mixin</code>, <code >variable</code> or <code >placeholder</code>.<br />If <code >{type}</code> is <code >variable</code>, then the <code >$</code> sign before the variable name is optional. Alongside if there is a <code >$</code> sign before the item name, then the <code >{variable}</code> type is optional.<br />If <code >{type}</code> is <code >placeholder</code>, then the <code >%</code> sign before the placeholder name is optional. Alongside if there is a <code >%</code> sign before the item name, then the <code >{placeholder}</code> type is optional.<br />Description is optional. Hyphen before description is optional.<br />Description is parsed as Markdown.*<br />Link is optional.<br />Item name can contain <code >::</code>, <code >:</code>, <code >.</code> and/or <code >/</code> when item is from an external resource.<br />Link is used as a link if present, else it tries to link to an inner item, else it doesn’t have a link.<br />The other item will automatically have a key named <code >usedBy</code> containing the name of function requiring it.</td>
    </tr>
  </tbody>
</table>


<a name="return"></a>

**[⬆ back to top](#navigation)**

## @return

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes the return statement of the documented function</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@returns</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Description is optional. Hyphen before description is optional.<br />Description is parsed as Markdown.*<br />Multiple types must be separated by pipes (<code >|</code>).</td>
    </tr>
  </tbody>
</table>

<a name="see"></a>

**[⬆ back to top](#navigation)**

## @see


<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes an item that is somehow related to the documented item (to describe a dependency, authors should use <code >@require</code> instead)</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Type is optional; default type is <code >function</code>. Can be either <code >function</code>, <code >mixin</code>, <code >variable</code> or <code >placeholder</code>.<br />If <code >{type}</code> is <code >variable</code>, then the <code >$</code> sign before the variable name is optional. Alongside if there is a <code >$</code> sign before the item name, then the <code >{variable}</code> type is optional.<br />If <code >{type}</code> is <code >placeholder</code>, then the <code >%</code> sign before the placeholder name is optional. Alongside if there is a <code >%</code> sign before the item name, then the <code >{placeholder}</code> type is optional.</td>
    </tr>
  </tbody>
</table>

<a name="since"></a>

**[⬆ back to top](#navigation)**

## @since

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes the version at which the documented item has been implemented or updated</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Description is optional. Hyphen before description is optional.<br />Description is parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="throw"></a>

**[⬆ back to top](#navigation)**

## @throw

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes an error thrown by the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td><code >@throws</code>, <code >@exception</code></td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="todo"></a>

**[⬆ back to top](#navigation)**

## @todo

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Defines any task to do regarding the documented item</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>true</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>functions, mixins, placeholders, variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Parsed as Markdown.*</td>
    </tr>
  </tbody>
</table>

<a name="type"></a>

**[⬆ back to top](#navigation)**

## @type

<table>
  <thead>
    <tr>
      <th>Attribute</th>
      <th>Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Description</td>
      <td>Describes the type of the documented variable</td>
    </tr>
    <tr>
      <td>Multiple</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Default</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Aliases</td>
      <td>—</td>
    </tr>
    <tr>
      <td>Autofilled</td>
      <td>false</td>
    </tr>
    <tr>
      <td>Allowed on</td>
      <td>variables</td>
    </tr>
    <tr>
      <td>Extra notes</td>
      <td>Multiple types should be separated with pipes (<code >|</code>).</td>
    </tr>
  </tbody>
</table>

**[⬆ back to top](#navigation)**