# MyBB-Helper-Classes

A collection of PHP classes to assist in MyBB plugin development.

| Group | Class Name | Description | Abstraction |
| ----- | ---------- | ----------- | ----------- |
| Object Classes | `MalleableObject` | basic abstract object with getter/setter functionality and basic validation components | abstract |
| Object Classes | `StorableObject` | extends MalleableObject providing database interaction enabling the storing, retrieval, and deletion of the object | abstract |
| Object Classes | `PortableObject` | extends StorableObject enabling export and import of the object | abstract |
| External Module Classes | `MalleableObject` | basic abstract object with getter/setter functionality and basic validation components | abstract |
| External Module Classes | `ExternalModule` | extends MalleableObject for external modules used as extensions for existing MyBB plugins using single file modules that include validation, versioning, and activation state | abstract |
| General Helper Classes | `WildcardPluginInstaller` | enables installation of common MyBB plugin components based on an installation data file | concrete |
| General Helper Classes | `WildcardPluginCache` | enables advanced cache management, with shortcuts for cache methods, optimized updates, validation, and more | abstract |
| General Helper Classes | `HTMLGenerator` | fills the void left in the MyBB ACP's HTML generating classes using a similar system to generate URLs, anchors, and images programmatically | concrete |