# class-157
# https://aframe.io/docs/1.3.0/core/component.html#definition_lifecycle_handler_methods2_thisdata

this.data  :--
Parsed component properties computed from the schema default values, mixins, and the entity’s attributes.
Important: Do not modify the data attribute directly. It is updated internally by A-Frame. To modify a component, use setAttribute.

this.el	  :--
Reference to the entity as an HTML element.

this.el.sceneEl	  :--
Reference to the scene as an HTML element.

this.id	  :--
If the component can have multiple instances, the ID of the individual instance of the component (e.g., foo from sound__foo).
