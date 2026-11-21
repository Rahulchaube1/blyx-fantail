## Find which settings layer supplied an invalid override

Returns [accepted, selected value, winning layer, distance outside bounds]. An invalid override remains visible for diagnosis. Invalid arguments and nonfinite results return an empty vector.

1. Open an empty file named `fantail-demo.blyx`.
2. Type `blyx-fantail-demo` and select **Fantail — runnable example**. You can also use **Snippets: Fill File with Snippet**.
3. Choose **Blyx: Run File** from the command palette. Change an argument near the end of `fn main()` to try another input.

Expected output

```text
0
15
1
5
```

[Work through the example in the browser](https://www.blyx-lang.space/play?example=package-fantail)
