# Fido

Manage native browser Fetch calls in React with Fido!  Fido aims to take the hassle out of working with native Fetch in React in two ways: 1. It manages the harder parts of the Fetch request's status internally and exposes simpler status flags that your components can *react* to, and 2. its configuration object can be as simple or complex as you need it to be, going so far as to allow you to pass an options object to the fetch call directly.

This package is currently a work in progress, but the basic hook, `useFido` is ready for use.  Documentation will be written concerning its use in the very near future.  Additional ways to use Fido, including a render-props component `Fido` and higher order component `withFido` are planned (they will likely just be wrappers around `useFido` unless there is a good reason not to do that).
