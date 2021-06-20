# What is a component?

> a constituent part : ingredient an important component of the program stereo components. 2a : any one of the vector terms added to form a vector sum or resultant. b : a coordinate of a vector also : either member of an ordered pair of numbers

## What are the charactistics of a component?

1. Path. A location in the folder in which to store components. Use folders to organize components in a hierarchical manner.
2. Component name. The name of the component.
3. Component type name. The name of the component type that is associated with a component. See Component Type Concepts.
4. Version number. The version number of the component. Each time a component is modified, the version number increments.
5. Platform. The operating system on which this component can be installed.
6. Check-in date. The date and time when the component was checked in.
7. Check-in user. The user ID of the person who checked in the component. This attribute is useful when you want to audit provisioning system processes.
8. Label. An optional string that you can use to categorize or group components.
9. Category. An optional object that you can use to filter the component list. After you create a category object, you can subsequently use it to group components.

### What are the advantages of using component based architecture?

> Component-Based architecture reduces the cost of development and maintenance. It is reusable which means can be used to reusable components to spread the development and maintenance cost across several applications. It increases the reliability of the whole system via reuse.

#### What is props short for?

> Props is short for properties and they are used to pass data between React components. React's data flow between components is uni-directional (from parent to child only)

##### How are props used in React?

> “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another. Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.

###### What is the flow of props?

* Adding Flow types to your React components is incredibly powerful. After typing your component, Flow will statically ensure that you are using the component in the way it was designed to be used.
* Early in React’s history the library provided PropTypes which performed basic runtime checks. Flow is much more powerful as it can tell you when you are misusing a component without running your code.
* There are some Babel plugins which will generate PropTypes from Flow types such as babel-plugin-react-flow-props-to-prop-types if you want both static and runtime checks.