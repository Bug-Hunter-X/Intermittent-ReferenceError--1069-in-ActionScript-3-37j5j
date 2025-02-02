# Intermittent ReferenceError #1069 in ActionScript 3

This repository demonstrates a problem in ActionScript 3 where a `ReferenceError: Error #1069: Property someVariable not found on SomeClass.` is thrown intermittently. The error is inconsistent; it only occurs under certain, seemingly random conditions, while the code runs correctly in other scenarios.  This makes debugging challenging.

The `bug.as` file contains the problematic code. `bugSolution.as` provides a possible fix and explanation of why the original code was unreliable.