# prototypePatternCSharp
Prototype design Pattern


Prototype Design Pattern

“Prototype Design Pattern specifies the kind of objects to create using a prototypical instance, and create new objects by copying this prototype”

In other words, by using the prototype design pattern, we can create new objects out of existing ones. When we modify the cloned one the original object won’t change, this is not allowed through the use of (=) sign, since when we do that to objects they both will share the same reference in memory, changing fields in one will change fields on the other. However, to avoid fields that are of Reference type will not be copied over only the reference, to avoid this deep cloning needs to  be implemented instead of shallow cloning
