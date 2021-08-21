# State Pattern use case with Rust
## Benefits of the State pattern
1. The struct Post does not have to know about how the different states behave and how they transition
2. Adding new states just implies to create a new struct and implement for them the State trait
3. Post does not have to check the states to decide some logic depending on them
4. Instead, if some specific action is to be performed depending on a specific state, the specific state will implement it using a Post instance passed as argument

## Local execution

Compilation
`rustc main.rs`

Execution
`./main`
