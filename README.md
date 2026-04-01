# goit-js-hw-02

## Description

Homework for **Topic 2: Branching and Loops**.  
Practice JavaScript fundamentals: conditionals, loops, and string methods.

## Project Structure

```
goit-js-hw-02/
├── js/
│   ├── task-1.js
│   ├── task-2.js
│   ├── task-3.js
│   └── task-4.js
├── index.html
└── README.md
```

## How to Run

Open `index.html` in the browser and check the DevTools console for output.

## Tasks

### Task 1 — Droid Order

Function: `makeTransaction(quantity, pricePerDroid, customerCredits)`

- If the customer's credits are less than `quantity * pricePerDroid` → returns `"Insufficient funds!"`
- Otherwise → returns `"You ordered <quantity> droids worth <totalPrice> credits!"`

### Task 2 — Message Formatting

Function: `formatMessage(message, maxLength)`

- If `message.length <= maxLength` → returns the original message
- If `message.length > maxLength` → returns the string cut at `maxLength` with `"..."` appended

### Task 3 — Spam Check

Function: `checkForSpam(message)`

- Returns `true` if the message contains `"spam"` or `"sale"` (case-insensitive)
- Returns `false` otherwise

### Task 4 — Shipping Cost

Function: `getShippingCost(country)`

Uses a `switch` statement to return the shipping cost:

| Country   | Cost (credits) |
| --------- | -------------- |
| China     | 100            |
| Chile     | 250            |
| Australia | 170            |
| Jamaica   | 120            |

- Supported country → `"Shipping to <country> will cost <price> credits"`
- Unsupported country → `"Sorry, there is no delivery to your country"`

## Requirements

- Code formatted with **Prettier**
- No errors or warnings in the browser console
- Follow the project structure strictly
