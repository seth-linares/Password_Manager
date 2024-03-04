# Overview

I created a simple Password Manager in Rust that lets you store a website, username, and password. It also lets you retrieve the password for a given website. The program allows you to either create your own password or have the program generate the password for you. If you create your own password you are required to have at least 8 characters. Once you have a password entry, you can then go back to the menu and choose to retrieve the password and username. The program will then ask you for the website you want to retrieve the password for. If the website is found, the program will print out the username and password. Before it prints out the password, you will be prompted to choose between seeing the full password or the obscured password. If you choose the obscured password, the program will print out the password with the first 3 and last 3 characters visible and the rest of the characters will be replaced with asterisks. If you choose the full password, the program will print out the full password so the user can copy it if needed.


*This project served as a precursor to my actual password manager, [PawPass](https://github.com/seth-linares/PawPass)*




# Development Environment

* JetBrains Rust Rover

* Programming Language: Rust

* Libraries: `rand::Rng`, `rand::distributions::Alphanumeric`, `std::collections::HashMap`

# Useful Websites



- [Learn Rust](https://www.rust-lang.org/learn)
- [Rust Playground](https://play.rust-lang.org/?version=stable&mode=debug&edition=2021)
- [Rust Documentation](https://doc.rust-lang.org/book/)

# Future Work


- Add a feature that allows the user to delete a password entry
- Add encryption to the password entries
- Improve the password generation algorithm
