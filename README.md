# Elixir List Modification During Enum.each Iteration
This example demonstrates a common pitfall in Elixir when attempting to modify a list while iterating using `Enum.each`.  The code intends to remove the element `3` from the list, but due to immutability and the nature of `Enum.each`, it fails to do so.

The solution demonstrates the correct approach using `Enum.filter` for immutably creating a new list without the undesired element.

This is relevant because it highlights the importance of understanding Elixir's immutability and choosing the appropriate iteration method for modifying collections.