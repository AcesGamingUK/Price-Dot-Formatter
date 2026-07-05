# Price Dot Formatter

A simple Supermarket Together mod that replaces commas in displayed prices with decimal points.

Examples:

* 12,50 -> 12.50
* 1,99 -> 1.99

## Installation

Install with Thunderstore Mod Manager or manually place the DLL into:

BepInEx/plugins

## Requirements

* BepInEx 5.x

## Changelog

### 1.0.0

* Initial release

### 1.1.0

Use harmony Patching

### 1.2.0

add fallback formatting for onscure occurencies

### 1.2.1

Reverted 1.2.0 patch due to ordering bug, working of fix

### 1.2.2

Fixed price formatting across most UI
Kept product ordering totals using decimal points
Preserved purchasing functionality on the ordering screen
Ordering screen item-row prices still use commas to avoid breaking the game’s internal purchase parsing
