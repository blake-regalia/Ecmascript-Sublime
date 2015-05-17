# Ecmascript Sublime Syntax

> This is not yet ready for use, only testing!

## Remaining Syntax To Complete

 - Object literal and most class body syntax
 - Decorators
 - Regular Expressions
 - Last steps for handling of ‘in’ vs ‘in’ after expression definitions have
   been confirmed to be solid.

## Other Stuff To Do

 - Real readme w/ proper examples for each scope
 - At least two themes

## Scopes So Far

 - comment.block
 - comment.line
 - comment.line.shebang
 - constant.character.escape
 - constant.character.escape.hexadecimal
 - constant.character.escape.newline
 - constant.character.escape.null
 - constant.character.escape.pointless
 - constant.character.escape.unicode
 - constant.language.boolean.false
 - constant.language.boolean.true
 - constant.language.infinity
 - constant.language.nan
 - constant.language.null
 - constant.language.undefined
 - constant.numeric.binary
 - constant.numeric.decimal
 - constant.numeric.hexadecimal
 - constant.numeric.octal
 - entity.name.class
 - entity.name.function
 - entity.name.function.allCap
 - entity.name.function.generator
 - entity.name.function.generator.allCap
 - entity.name.function.generator.initCap
 - entity.name.function.initCap
 - entity.name.method
 - entity.name.module.export
 - entity.name.module.import
 - entity.name.statement
 - entity.other.property-binding
 - entity.other.property-binding.parameter
 - invalid.deprecated
 - invalid.illegal.newline
 - invalid.illegal.octal-escape
 - invalid.illegal.token
 - keyword.control.conditional.else
 - keyword.control.conditional.if
 - keyword.control.flow.break
 - keyword.control.flow.continue
 - keyword.control.flow.each
 - keyword.control.flow.return
 - keyword.control.flow.throw
 - keyword.control.flow.yield
 - keyword.control.flow.yield.iterate
 - keyword.control.loop.conditional.if.comprehension.array
 - keyword.control.loop.conditional.if.comprehension.generator
 - keyword.control.loop.do
 - keyword.control.loop.for
 - keyword.control.loop.for.comprehension.array
 - keyword.control.loop.for.comprehension.generator
 - keyword.control.loop.in
 - keyword.control.loop.of
 - keyword.control.loop.of.comprehension.array
 - keyword.control.loop.of.comprehension.generator
 - keyword.control.loop.while
 - keyword.control.switch
 - keyword.control.switch.case
 - keyword.control.switch.case.default
 - keyword.control.trycatch.catch
 - keyword.control.trycatch.finally
 - keyword.control.trycatch.try
 - keyword.control.with
 - keyword.operator.accessor
 - keyword.operator.arithmetic.addition
 - keyword.operator.arithmetic.decrement.postfix
 - keyword.operator.arithmetic.decrement.prefix
 - keyword.operator.arithmetic.division
 - keyword.operator.arithmetic.exponentiation
 - keyword.operator.arithmetic.increment.postfix
 - keyword.operator.arithmetic.increment.prefix
 - keyword.operator.arithmetic.modulo
 - keyword.operator.arithmetic.multiplication
 - keyword.operator.arithmetic.sign.negative
 - keyword.operator.arithmetic.sign.positive
 - keyword.operator.arithmetic.subtraction
 - keyword.operator.assignment
 - keyword.operator.assignment.augmented.arithmetic.addition
 - keyword.operator.assignment.augmented.arithmetic.division
 - keyword.operator.assignment.augmented.arithmetic.exponentiation
 - keyword.operator.assignment.augmented.arithmetic.modulo
 - keyword.operator.assignment.augmented.arithmetic.multiplication
 - keyword.operator.assignment.augmented.arithmetic.subtraction
 - keyword.operator.assignment.augmented.bitwise.logical.and
 - keyword.operator.assignment.augmented.bitwise.logical.or
 - keyword.operator.assignment.augmented.bitwise.logical.xor
 - keyword.operator.assignment.augmented.bitwise.shift.left
 - keyword.operator.assignment.augmented.bitwise.shift.right
 - keyword.operator.assignment.augmented.bitwise.shift.right.unsigned
 - keyword.operator.assignment.conditional.default
 - keyword.operator.assignment.conditional.mallet
 - keyword.operator.bitwise.logical.and
 - keyword.operator.bitwise.logical.not
 - keyword.operator.bitwise.logical.or
 - keyword.operator.bitwise.logical.xor
 - keyword.operator.bitwise.shift.left
 - keyword.operator.bitwise.shift.right
 - keyword.operator.bitwise.shift.right.unsigned
 - keyword.operator.comma
 - keyword.operator.comparison.equality.coercive
 - keyword.operator.comparison.equality.strict
 - keyword.operator.comparison.non-equality.coercive
 - keyword.operator.comparison.non-equality.strict
 - keyword.operator.logical.and
 - keyword.operator.logical.not
 - keyword.operator.logical.or
 - keyword.operator.new
 - keyword.operator.relational.gt
 - keyword.operator.relational.gte
 - keyword.operator.relational.in
 - keyword.operator.relational.instanceof
 - keyword.operator.relational.lt
 - keyword.operator.relational.lte
 - keyword.operator.spread
 - keyword.operator.ternary.else
 - keyword.operator.ternary.if
 - keyword.operator.unary.delete
 - keyword.operator.unary.typeof
 - keyword.operator.unary.void
 - keyword.other.debugger
 - keyword.other.extends
 - keyword.other.rest
 - meta.comment.body
 - meta.comment.border
 - meta.comment.box-drawing
 - meta.directive.use-strict
 - meta.idiomatic-cast.boolean
 - meta.invocation
 - meta.numeric.exponent.digit
 - meta.numeric.exponent.e
 - meta.numeric.exponent.sign
 - meta.numeric.prefix
 - meta.symbol-helper.arrow
 - meta.symbol-helper.class
 - meta.symbol-helper.function
 - meta.symbol-helper.generator
 - meta.whitespace
 - punctuation.decimal
 - punctuation.definition.accessor.begin
 - punctuation.definition.accessor.end
 - punctuation.definition.accessor.parameter.begin
 - punctuation.definition.arguments.begin
 - punctuation.definition.arguments.end
 - punctuation.definition.array.begin
 - punctuation.definition.array.end
 - punctuation.definition.binding.array.begin
 - punctuation.definition.binding.array.end
 - punctuation.definition.binding.array.parameter.begin
 - punctuation.definition.binding.array.parameter.end
 - punctuation.definition.binding.object.begin
 - punctuation.definition.binding.object.end
 - punctuation.definition.binding.object.parameter.begin
 - punctuation.definition.binding.object.parameter.end
 - punctuation.definition.block.begin
 - punctuation.definition.block.conditional.begin
 - punctuation.definition.block.conditional.end
 - punctuation.definition.block.end
 - punctuation.definition.block.loop.begin
 - punctuation.definition.block.loop.end
 - punctuation.definition.block.switch.begin
 - punctuation.definition.block.switch.end
 - punctuation.definition.block.trycatch.begin
 - punctuation.definition.block.trycatch.end
 - punctuation.definition.block.with.begin
 - punctuation.definition.block.with.end
 - punctuation.definition.class.body.begin
 - punctuation.definition.class.body.end
 - punctuation.definition.comment.begin
 - punctuation.definition.comment.end
 - punctuation.definition.comprehension.array.begin
 - punctuation.definition.comprehension.array.end
 - punctuation.definition.comprehension.generator.begin
 - punctuation.definition.comprehension.generator.end
 - punctuation.definition.expression.begin
 - punctuation.definition.expression.conditional.begin
 - punctuation.definition.expression.conditional.comprehension.array.begin
 - punctuation.definition.expression.conditional.comprehension.generator.begin
 - punctuation.definition.expression.conditional.end
 - punctuation.definition.expression.end
 - punctuation.definition.expression.loop.begin
 - punctuation.definition.expression.loop.comprehension.array.begin
 - punctuation.definition.expression.loop.comprehension.generator.begin
 - punctuation.definition.expression.loop.end
 - punctuation.definition.expression.switch.begin
 - punctuation.definition.expression.switch.end
 - punctuation.definition.expression.with.begin
 - punctuation.definition.expression.with.end
 - punctuation.definition.function.arrow.body.begin
 - punctuation.definition.function.arrow.body.end
 - punctuation.definition.function.body.begin
 - punctuation.definition.function.body.end
 - punctuation.definition.generator.body.begin
 - punctuation.definition.generator.body.end
 - punctuation.definition.module-binding.begin
 - punctuation.definition.module-binding.end
 - punctuation.definition.object.begin
 - punctuation.definition.object.end
 - punctuation.definition.parameters.catch.begin
 - punctuation.definition.parameters.catch.end
 - punctuation.definition.parameters.function.arrow.begin
 - punctuation.definition.parameters.function.arrow.end
 - punctuation.definition.parameters.function.begin
 - punctuation.definition.parameters.function.end
 - punctuation.definition.parameters.generator.begin
 - punctuation.definition.parameters.generator.end
 - punctuation.definition.string.interpolated.begin
 - punctuation.definition.string.interpolated.element.begin
 - punctuation.definition.string.interpolated.element.end
 - punctuation.definition.string.interpolated.end
 - punctuation.definition.string.quoted.double.begin
 - punctuation.definition.string.quoted.double.end
 - punctuation.definition.string.quoted.double.parameter.begin
 - punctuation.definition.string.quoted.single.begin
 - punctuation.definition.string.quoted.single.end
 - punctuation.definition.string.quoted.single.parameter.begin
 - punctuation.definition.string.regexp.begin
 - punctuation.separator.argument
 - punctuation.separator.array-element
 - punctuation.separator.array-element.binding
 - punctuation.separator.binding-binding
 - punctuation.separator.case-statements
 - punctuation.separator.label-statement
 - punctuation.separator.loop-expression
 - punctuation.separator.module-binding
 - punctuation.separator.object-member.binding
 - punctuation.separator.parameter
 - punctuation.separator.property-binding
 - punctuation.separator.property-binding.parameter
 - punctuation.terminator.statement
 - source.es
 - storage.type.accessor.get
 - storage.type.accessor.set
 - storage.type.async
 - storage.type.async.expression
 - storage.type.class
 - storage.type.class.expression
 - storage.type.constant
 - storage.type.function
 - storage.type.function.arrow
 - storage.type.function.expression
 - storage.type.function.generator
 - storage.type.function.generator.asterisk
 - storage.type.function.generator.asterisk.expression
 - storage.type.function.generator.expression
 - storage.type.module.as
 - storage.type.module.default
 - storage.type.module.export
 - storage.type.module.from
 - storage.type.module.import
 - storage.type.module.namespace
 - storage.type.static
 - storage.type.variable.let
 - storage.type.variable.var
 - string.interpolated
 - string.quoted.double
 - string.quoted.single
 - string.regexp
 - support.class.builtin
 - support.class.node
 - support.function.builtin
 - support.function.node.require
 - support.type.object.builtin
 - support.type.object.dom
 - support.type.object.dom-library
 - support.type.object.functional-library
 - support.type.object.node
 - variable.language.arguments
 - variable.language.new-target.fake-accessor
 - variable.language.new-target.fake-object
 - variable.language.new-target.fake-property
 - variable.language.proto
 - variable.language.prototype
 - variable.language.super
 - variable.language.this
 - variable.other.readwrite
 - variable.other.readwrite.allCap
 - variable.other.readwrite.constructor
 - variable.other.readwrite.export
 - variable.other.readwrite.import
 - variable.other.readwrite.initCap
 - variable.other.readwrite.property
 - variable.other.readwrite.property.allCap
 - variable.other.readwrite.property.initCap
 - variable.other.readwrite.property.proto
 - variable.other.readwrite.property.prototype
 - variable.other.readwrite.tag
 - variable.parameter
 - variable.parameter.catch
 - variable.parameter.rest