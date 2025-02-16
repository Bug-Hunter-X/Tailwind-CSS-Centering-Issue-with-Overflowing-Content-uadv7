# Tailwind CSS Centering Issue with Overflowing Content

This repository demonstrates a common issue encountered when using Tailwind CSS for centering elements:  overflowing content breaking the centering layout. The `bug.js` file shows the problematic code, while `solution.js` provides a robust solution.

## Problem
The initial implementation uses `flex justify-center items-center` to center a div. However, if the content within the inner div exceeds its container's width, the centering is disrupted.

## Solution
The solution involves using techniques such as `max-w-xs` to constrain the content width, or `overflow-auto` (with a defined width) to handle content overflow effectively without disrupting centering.