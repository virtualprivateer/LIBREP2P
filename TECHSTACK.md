# The Tech for this project
---
Since we want to make this project secure for the users, RUST is recommended for memory safety and ease of coding.  
  
Rust will be used instead of c++ or other lenguages because of Rust's memory safety, and ecosystem needed.


## Why not c++?

Basically, for 4 main reasons. 
 
- C++ TUI libraries are less actively maintained.
- Threading with `std::thread` is less ergonomic than Rust's async model.
- No built-in protection against undefined behavior.
- You have to manually manage memory around crypto keys.
 
 
--- 
#TECH STACK
###(Recomended by deepseek, could be changed later)
 
- **TUI:** ratatui
- **Async** runtime: tokio
- **AES-GCM:** aes-gcm
- **Random generation:** rand with getrandom 
- **Tor (p2p):** arti with arti-client
- **Networking:** tokio::net
- **Serialization:** serde with bincode
- **Logging:** tracing (Development stage only)
- **Docker:** for working with more devs.
