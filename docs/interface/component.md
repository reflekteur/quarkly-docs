Components

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-pages-and-layers-components.png?v=2020-11-06T17:29:03.086Z)

This is where you'll find all the available components. They make it easier and faster to create a website design as they contain ready-to-use styles, content, and logic. In addition, components can be nested within other components.

How to Add a Component

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-interface-page-elements-add-new.png?v=2020-11-06T18:13:08.784Z)

There are several ways to add the component you need to your page. You may want to grab it from the panel with the mouse and drop it in the desired place. If you left-click a component, it is added to the bottom of the page. Also, you can click on the  “+” button on the block to add a component.

About props

To ensure flexibility, components come with props (properties) — through them, you can manage and configure settings. For example, the GoogleMap component contains the “query” property where you can enter the address of the marker that you’d like to appear on the map. A component may have various props, and they’re all very easy to use.

Component copies synchronization

Another important feature is that all copies of the component are synchronized on the page, so if you change something in the original code of a component, all of its copies will change too. This is useful when a component is repeated on all pages, for example, a header or a footer.

System components

There are 2 types of components:

 

**system**

and

 

**custom**.

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-library.png?v=2020-11-06T18:23:44.504Z)

The system ones consist of:

*   Primitives
    
*   Quarkly UI component library
    

Primitives are the simplest, most basic components for a wide variety of tasks. Quarkly UI components are the more complex, composite components designed for specific tasks.

Custom components (created by users)

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom.png?v=2020-11-06T18:23:19.976Z)

About custom components

Custom components are needed when you would like to create your own component from elements on the page or configure it in the code. Components created from page elements come with an interesting option — if you change one copy of this component, you can also change other copies accordingly using the “Push to Master” command. Custom components, just like the other, have the props panel with style and functional properties. Inner properties of custom components can be transferred to the props panel and, will appear under the “Props” section. In custom components, it’s also possible to import other components and modules from

 

[NPM](https://beta.quarkly.io/preview#/docs/getting-started11/interface#interface-context-menu).

Context menu for a component

![](https://uploads.quarkly.io/landing/docs-components-context-menu.png)

You can open the

 

[context menu](https://beta.quarkly.io/preview#/docs/getting-started11/interface#interface-context-menu)

for a component. The menu contains a list of actions you can do to the component. To open it, mouse over the component and right-click on it.

Creating a Component on a Page

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-design-create.png?v=2020-11-06T18:49:56.326Z)

Choose any element (just one, but it can contain others) on a page, click “...” on the props panel and choose “Convert to Component”. In addition, a component can be created with a combination of keys: cmd(ctrl) + alt + k. After that, a window for entering a component name will appear. Type in a unique name and click “Save”.

Detaching a component (transforming back into an element)

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-design-detach.png?v=2020-11-06T18:49:19.036Z)

A custom component can be transformed back into the element or group of elements it was created from. To do this, you need to choose only one component, click “...” on the props panel and choose “Detach”. This action can also be performed by pressing the combination of keys: cmd(ctrl) + alt + b.

Overrides

You can change the styles and content of a parent element as well as all children elements of a custom component. These changes are called overrides.

Reset Overrides and Reset All Overrides

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-design-reset-overrides.png?v=2020-11-06T18:48:57.081Z)

If you changed a custom component and then decide to go back to its original version (Master), use the reset option. Choose only one component, click on the “...” button and select “Reset Overrides”. If you want to reset the changes for all elements, both parent and children, click “Reset All Overrides”.

Push to Master and Push All to Master

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-design-push-to-master.png?v=2020-11-06T18:48:16.914Z)

If you changed a custom component and would like to apply the change to all copies of this component, use the command for sending changes to Master. To do this, choose only one component, click on the “...” on the props panel and choose “Push to Master”. If you want to send the changes of a parent element and all children elements to Master, click “Push All to Master”.

_Important!_

When you use “Push to Master” and “Push All to Master”, all changed styles in the copies will be preserved (those that contain overrides). The styles will be changed only in those copies that you didn’t edit.

Save as New Component

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-design-save-as-new.png?v=2020-11-06T18:47:58.247Z)

You can create a new custom component using the existing custom component. To do this, you need to choose only one component, click “...” on the props panel and select “Save as New Component”.

Creating a Component in the Code Editor

![](https://test-upl.quarkly.io/5e60efa12db4d10024432a9f/images/docs-components-custom-code-create.png?v=2020-11-06T18:47:39.681Z)

To create a code component, click on the “+” button. You should be familiar with JavaScript and React.js. Once you’ve chosen the component name, the code editor will open, and you’ll see a default component. Code components allow:

*   Setting up any kind of content.
    
*   Styling content however you like.
    
*   Configuring any logic.
    
*   Connecting
    
     
    
    [NPM](https://beta.quarkly.io/preview#/docs/getting-started11/https://www.npmjs.com/)
    
    dependencies.
    
*   Connecting primitives and Quarkly UI components.
    
*   Defining props (properties) for a component.
    
*   Connecting to any external databases or API.
    

To edit a component in the code editor, click on the “<>” button.

How to connect an NPM module in components

![](https://uploads.quarkly.io/landing/docs-components-custom-code-npm-module.png)

To connect a module, just import it into the component, as if it had been already installed.

Example code:

```
import Particles from "react-particles-js";
```

Importing atomize

Atomize is a library for creating Quarkly components.  
To make your React component work, you need to wrap it and define the object with the following configuration:

```
const Dasdas = props => <div {...props}>Say hello Dasdas</div>\n\nexport default atomize(Dasdas)({\n name: "Dasdas",\n effects: {\n   hover: ":hover"\n },\n normalize: true,\n mixins: true,\n description: {\n   // paste here the description for your component\n   en:\n     "Dasdas — my awesome component",\n },\n\n propInfo: {\n   // paste here the props description for your component\n   yourCustomProps: {\n     description: {en: 'test'},\n     control: "input"\n   }\n }\n});
```

Component configuration fields:

*   Effects. Defines browser pseudo-classes (hover, focus, etc).
    
*   Description. Defines the component description that shows up when hovering the mouse cursor over its name.
    
*   PropInfo. Configures controls that will be displayed on the right panel (props tab).
    

How to display required properties on the props panel

Here’s how to define properties that will be displayed on the right panel (props tab):

```
propInfo: {\n   yourCustomProps: { // property name\n       description: { en: "test" }, // locale-specific description\n       control: "input" // control type\n   }\n}
```

Possible control types:

*   input
    
*   text-area
    
*   select
    
*   color
    
*   image
    
*   font
    
*   shadow
    
*   transition
    
*   transform
    
*   filter
    
*   background
    
*   checkbox-icon
    
*   radio-icon
    
*   radio-group
    
*   checkbox
    

How to import primitives into your custom component

```
import { PrimitiveComponentName } from "@quarkly/widgets";
```

How to import components from Quarkly UI into your custom component

```
import { QuarklyUIComponentName } from "@quarkly/components";
```

How to import your components into other custom components you have

```
import MyComponent from "./MyComponent";
```