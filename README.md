# Elixir Enum.each and List Immutability Bug

This example demonstrates a common misconception when working with lists in Elixir.  Because Elixir lists are immutable, modifications within an `Enum.each` loop do not affect the original list.  The code attempts to remove the element `3` from the list, but fails to do so correctly. 

The solution demonstrates how to correctly remove an element and use the result.