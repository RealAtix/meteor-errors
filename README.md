# meteor-errors

A pattern to display application errors to the user. It uses a local collection to collect the errors. Errors will fade out after displaying.

*Testing meteor packages (thanks to discover meteor)*

To start:
* Meteor: `meteor add atix:errors`

## Usage
Add the template to your layout:
`{{> meteorErrors }}`

Throw errors with:
`Errors.throw(error);`
