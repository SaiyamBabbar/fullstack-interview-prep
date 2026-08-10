# React Interview Questions

## Q1. What is Virtual DOM?

Virtual DOM is a lightweight JavaScript representation of the
actual DOM.

React compares changes and updates the required parts of the
real DOM.

## Q2. What is useMemo?

`useMemo` memoizes a calculated value and recalculates it when
its dependencies change.

## Q3. What is useCallback?

`useCallback` memoizes a function reference.

It can be useful when passing callbacks to memoized child components.

## Q4. What is React.memo?

`React.memo` prevents unnecessary rendering of a component when
its props have not changed.

## Q5. What causes a React component to re-render?

Common causes include:

- State changes
- Parent re-render
- Props changes
- Context changes
