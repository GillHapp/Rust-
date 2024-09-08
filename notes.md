 println!("Hello, world!");

 econd, println! calls a Rust macro. If it had called a function instead, it would be entered as println (without the !)


 cargo build 
 gives us 

 cargo build
   Compiling hello_cargo v0.1.0 (file:///projects/hello_cargo)
    Finished dev [unoptimized + debuginfo] target(s) in 2.85 secs

after that we need to write another thing whihc is 

./target/debug/hello_cargo 

this is shows us 
hello word


but alterate this we have one another command which do both the things 

cargo run => hello word



one another thing is cargo check 


cargo build --release  => for production 


cargo build  also helpfull when we clone our repo 