# OrderProcessorDojo
Coding dojo at Headspring Dallas using an order processing system example

## Requirements
Part 1 (7/11/16): Build a system that takes an order from a POS sales register machine, saves it, and returns the order total.

Input: a JSON format input
{ 
  name: <>,
  items: [{name, price}, ...]
}
Expected output: JSON output
{ 
  id: <>,
  name: <>,
  items: [{name, price}, ...],
  total: <>
}

## Structure:
Use Controller > Service > Repository > db
