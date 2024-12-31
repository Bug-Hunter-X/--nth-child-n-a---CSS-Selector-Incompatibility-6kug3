# :nth-child(n+a) CSS Selector Incompatibility

This repository demonstrates a common CSS issue related to the `:nth-child(n+a)` selector's lack of support in older browsers.  This selector is useful for advanced styling but can break compatibility.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides a solution using alternative selectors and browser-specific prefixes, ensuring wider browser support. 

## Bug Report

The `:nth-child(n+a)` selector was used to style specific elements, causing layout errors on browsers that don't support this selector. 

## Solution

The solution implements a more compatible approach, ensuring the styles are applied correctly across a wider range of browsers. 