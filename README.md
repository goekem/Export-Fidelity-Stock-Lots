# Export-Fidelity-Stock-Lots
Exports stock lots from the positions page of a fidelity account as a CSV.

1. Navigate to the positions page for an account on Fidelity
2. Make sure 'Cash' is on top
3. Open the browser console (usually Shift + Ctrl + J)
4. Paste the script into the browser console
5. Type expandRows() and hit enter
6. Let the page load
7. Type main() and hit enter

If 'Cash' is not on top, the top position will be excluded. I might fix this in a future version.
