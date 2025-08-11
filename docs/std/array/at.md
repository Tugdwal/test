# [BLink](../../index.md) > [Standard library](../../std.md) > [std#array](../array.md) > at

Returns the `value` at the specified `index` in the `array`.

## Syntax

> **at** <`array`> <*out*: `value`> <`index`>

## Parameters

| Name | Description |
|---|---|
| `array` | the array |
| `value` | reference to the output *value* |
| `index` | position of the element to return |

## Errorlevel

Non-zero if `index` is not within the range of the `array`.

## See also

| Name | Description |
|---|---|
| [`set_at`](set_at.md) | replace the specified element |
| [`back`](back.md) | access the last element |
| [`front`](front.md) | access the first element |
