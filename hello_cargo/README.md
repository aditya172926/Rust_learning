To create a new project using cargo use `cargo new project_name`

This creates a structure with a TOML file which contains our package configurations and dependencies and a src folder.

Keep all of the source files in the src folder.

To build a cargo project use `cargo build`
An executable file will be generated in a new folder path `target/debug/project_name.exe`

Run the .exe file the usual way in your terminal

To build and run the exe file in a single command use `cargo run`

To check your code use `cargo check`. This will not create an .exe file, it just compiles.

To build your .exe for release use `cargo build --release` this creates the .exe file in `target/release` directory and is optimised for faster execution.