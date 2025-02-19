# Unexpected useEffect Behavior in React

This repository demonstrates a common issue encountered when using the `useEffect` hook in React.  The example showcases how `useEffect` can run after every render, even when seemingly unnecessary, potentially leading to performance issues or infinite loops.  The solution provided addresses this by correctly specifying the dependencies array.