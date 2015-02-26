# grails-db-reverse-engineer

Fork of the official plugin with a couple of bug fixes:
* adds column mapping
* unique constraint generates with property names instead of column names
* when foreign key is also a primary key adds insertable:false, updateable:false mapping
* when id is of character type add type:string to mapping
* exposes detectOneToOne and detectManyToMany as plugin config options
* when foreign key is not unique takes the name for the property from the column
* adds config option to not render hasMany and belongsTo relationships
