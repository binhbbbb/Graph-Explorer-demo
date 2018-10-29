[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/graph-explorer)
[![Stars on Vaadin Directory](https://img.shields.io/vaadin-directory/star/graph-explorer.svg)](https://vaadin.com/directory/component/graph-explorer)

# Graph Explorer demo repository
Repository containing demos for the [Graph Explorer](https://github.com/vaadin/Graph-Explorer) add-on for 
[Vaadin](https://vaadin.com/).

The only functional demo is currently the Neo4J demo. To build it, you will need 
[Eclipse IDE](http://www.eclipse.org/downloads/), the [Vaadin plug-in](http://vaadin.com/eclipse) (to compile the
widgetset) and the [IvyDE plug-in](http://ant.apache.org/ivy/ivyde/) (to resolve the dependencies). At runtime, you will 
also need to supply your own Neo4J version 1.3.M03 graph DB at `<user.home>/graphdb`.

If anyone wants to fork the Neo4J demo and upgrade it to a newer version of Neo4J, please be my guest and send me a pull 
request when you're done! :)
