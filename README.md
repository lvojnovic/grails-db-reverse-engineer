# grails-db-reverse-engineer

Fork of the official plugin with a couple of bug fixes:
* adds column mapping
* unique constraint generates with property names instead of column names
* when foreign key is also a primary key adds insert:false, update:false mapping
* when id is of character type add type:string to mapping
* exposes detectOneToOne and detectManyToMany as plugin config options
